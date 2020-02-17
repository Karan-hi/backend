# sample-application

This sample project is used for demonstrating Jenkins pipeline on AWS environment with AWS devops tools(CodeBuild, S3 Buckets, CodeDeploy)

## appspec.yml
The application specification file (AppSpec file) is a YAML-formatted or JSON-formatted file used by CodeDeploy to manage a deployment. It must be placed in the root of the directory structure of an application's source code. 
It is used by CodeDeploy to determine:

What it should install onto instances from Amazon S3 or GitHub repositories.
Which lifecycle event hooks to run in response to deployment lifecycle events.

## buildspec.yml
A build spec is a collection of build commands and related settings, in YAML format, that CodeBuild uses to run a build. buildspec is included as part of the source code.



