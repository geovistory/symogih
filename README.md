# First step: Import actors to Geovistory

## Data analysis

See:
- Report about [Actors's](https://github.com/geovistory/project-symogih/blob/master/reports/expl-analysis-actor.html)
- Report about [Actor's name](https://github.com/geovistory/project-symogih/blob/master/reports/expl-analysis-actor-name.html)
- Report about [Actor's text properties](https://github.com/geovistory/project-symogih/blob/master/reports/expl-analysis-actor-text-property.html)

## Record linkage

### Recognize SYMOGIH actors in Geovistory

The goal here is to identify what SYMOGIH actors taht already exisits in Geovistory.
To help with that, we have found a record linkage library that does exactly that and that is used by the Ministery of Justice in the UK. The library name is [SPLINK](https://github.com/moj-analytical-services/splink). We think that identifying the SYMOGIH actors is a good use case to test this library.

The learning, tests, and results are available [here](https://github.com/geovistory/project-symogih/blob/master/reports/link-actors-with-geov.html).

Doing this analysis, we found that it may be necessary to make a record linkage inside the SYMOGIH actors first, because we already found some dupplicated.


### Record linkage inside BHP

With the same strategy as described above, we try to identify dupplicated actors inside the BHP itself. 
Unfortunately results were not as good as expected (see issue #1, and [report](https://github.com/geovistory/project-symogih/blob/master/reports/splink-bhp-record-linkage.html)). 
So we try a more traditionnal way.
