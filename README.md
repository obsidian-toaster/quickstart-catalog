# Booster Catalog
Set of known example applications (Boosters) conforming to the minimal set of requirements necessary to be served by the Launchpad.

For each example application, create a YAML file with information containing:

Name   | Description 
------ | -----------
githubRepo| The GitHub repository location
gitRef | The git reference (tag/branch/SHA1)
launchpadDescriptorPath|  Path in the repository specified to `launchpad.yaml` (defaults to `.openshiftio/launchpad.yaml`)

The `launchpad.yaml` file is expected to have the following structure:

Name   | Description | Required | Size
------ | ----------- | -----    | ----
name|The name |Yes|
description  |  The quickstart description  |Yes  |  255  
