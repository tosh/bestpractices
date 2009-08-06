# motivation

* not only the person who wrote the code is familiar with it
  * improved awareness
    * people feel more involved, identify more strongly with the project
    * easier to enforce coding conventions, documentation and overall code quality
  * increased bus factor

# proposed workflow

* a new branch for every new feature
  * if branching is too expensive or no dvcs can be used one can use patches (google does this - mondrian)
* when the feature is completed the code is shown to 1 or more additional developers
* code gets discussed (mention tools like diff, gitg, gitk, gerrit, …)
  * branch gets merged into mainline/master
  * or code gets improved and a new iteration of the process is started

As a side effect of this approach, code reviews are linked with code contributions to the mainline. Atomic commits do help a lot when doing code reviews (see revision-control.md).

# pair programming

introduce pair programming as extreme version of code reviews

* advantages
  * shorter feedback cycle
  * not only the code but also the workflow might get improved (ide, …)
* disadvantages
  * might not work depending on environment
    * not be applicable for teams which are distributed around the world?
    * companies who refuse to pay more than one person for a certain programming task in fear of wasted time?

propose pair programming for essential features in addition to code reviews?

# suggestions

* add code review discussion and conclusions as comments to written code
  * improves/adds documentation about reasoning
  * makes the process more transparent to others or when reviewed in the future
* try to improve the situation together instead of blaming
  * this might be easier in pair programming as it is not asynchronous and everyone is involved
  * whereas code reviews usually pose a "submit - accept/reject" scenario
  * though ultimately it comes down to how well people work and communicate with each other

# tools

* diff
* gitg
* gitk
* gerrit
* rietveld
* mondrian

## references

* http://www.codinghorror.com/blog/archives/000999.html
* http://en.wikipedia.org/wiki/Bus_factor
* http://code.google.com/p/gerrit/
* http://code.google.com/p/rietveld/
* http://www.youtube.com/watch?v=sMql3Di4Kgc (mondrian)
