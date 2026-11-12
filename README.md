# Theatron extension template

This repository is the home of the Kotlin starter for independently developed Theatron extensions, including integrations with other Minecraft plugins.

> **Availability:** This repository currently contains a README only. The starter project and SDK are not available here yet, and this is not yet a usable GitHub template.

## Extension structure

The starter will include a Kotlin project using the Theatron extension SDK, a manifest, examples of event, action, and value nodes, and a Paper plugin integration example. Tests and a build workflow will show how to package a compatible extension.

Extensions will run in the Paper plugin environment and communicate with the panel through the core's versioned contracts. A third-party extension should not need to deploy custom code in the engine or panel. Operators will be able to install their own extensions without publishing them to an official registry.

## Where it fits

- [Theatron core](https://github.com/theatronmc/theatron) provides the extension protocol, SDK, and Paper runtime.
- [Extension registry](https://github.com/theatronmc/extension-registry) indexes community extension metadata.
