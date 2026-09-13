# JTE Maven library selection

This repository contains `pipeline_config.groovy`, which selects the `maven` library for a Jenkins Templating Engine pipeline. It does not contain a standalone application or a Maven build definition.

Configure JTE in Jenkins, provide a governance pipeline template, and register a library source that defines `maven`. The companion [JTE examples](https://github.com/merhan123/JTE) include demonstration library steps that print messages. Configure the Jenkins job to read this repository's pipeline configuration, then run it through your governance template.

There is no local build or test command. Validate the library resolution and pipeline in your Jenkins environment.
