# Maven CI Pipeline
This template will create a pipeline that showcases the features of the [MvnBuild](https://www.jfrog.com/confluence/display/JFROG/MvnBuild) native step. These features include:

* Building a Maven project and pushing the resulting artifacts to Artifactory
* Publishing an Artifactory build and updating an output [BuildInfo resource] (https://www.jfrog.com/confluence/display/JFROG/BuildInfo)
* Utilizing JFrog Xray to scan the artifacts for security vulnerabilities
* Writing to an output [FileSpec resource] (https://www.jfrog.com/confluence/display/JFROG/FileSpec) that can be connected to another pipeline

This template requires a few configurations to be set up:

* An [Artifactory] (https://www.jfrog.com/confluence/display/JFROG/Artifactory+Integration) integration for resolving dependencies and publishing artifacts
* A Git integration (like [GitHub](https://www.jfrog.com/confluence/display/JFROG/GitHub+Integration)) that can connect with your Maven project
* Resolver and deployer Artifactory Maven repositories for snapshots and releases

## Live Example 
Click [here](https://pipelines.jfrog.io/ui/pipelines/myPipelines/viewPipelines?projectKey=templates) to see this Global template in action.
