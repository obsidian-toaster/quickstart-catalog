# Quickstart Catalog
Set of known example applications conforming to the minimal set of requirements necessary to become part of the QuickStart experience.

For each example application, create a YAML file with information containing:

Name   | Description 
------ | -----------
githubRepo| The GitHub repository location
gitRef | The git reference (tag/branch/SHA1)
obsidianDescriptorPath|  Path in the repository specified to `obsidian.yaml` (defaults to `.obsidian/obsidian.yaml`)

The `obsidian.yaml` file is expected to have the following structure:

Name   | Description | Required | Size
------ | ----------- | -----    | ----
name | The quickstart name  |  Yes  |  50
description  |  The quickstart description  |Yes  |  255  
