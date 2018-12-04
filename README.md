# Jargon Alexa Hello World skill

This is a fork of the [Alexa Hello World skill template](https://github.com/alexa/skill-sample-nodejs-hello-world#readme) template that uses the [Jargon SDK](https://github.com/JargonInc/jargon-sdk-nodejs/tree/master/packages/alexa-skill-sdk#readme) to manage content.

## Changes from the source template
* Add dependency on the Jargon SDK npm package (@jargon/alexa-skill-sdk)
* Use the Jargon skill builder during initialization
* Use the Jargon response builder to construct all responses
* Move response content into locale-specific resource files

## Instructions

See https://github.com/JargonInc/skill-sample-nodejs-hello-world/blob/master/instructions/cli.md for instructions on how to use this template via the ASK CLI.

In general the instructions from the source template are also applicable, with the exception that the Lambda needs to be deployed via the CLI to ensure that all dependencies and resources are included.