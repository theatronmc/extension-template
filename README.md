# Theatron extension template

This repository will become a runnable starter for independently developed Theatron extensions, including integrations with other Minecraft plugins.

> **Status — starter code in preparation.** This repository currently contains documentation only. It is not yet a usable GitHub template. The public extension SDK, sample extension, build workflow, and license have not been published.

## Planned starter

A working template will include a Kotlin project using a versioned public extension SDK, a declarative manifest, examples of event/action/value nodes, a Paper integration example that handles an absent or incompatible dependency, conformance and runtime tests, CI, and release instructions.

Extensions will run in the Paper plugin environment and communicate with the panel through the core's versioned contracts. A third-party extension should not need to deploy custom code in the engine or panel. Operators will be able to install their own extensions without publishing them to an official registry.

## Where it fits

- [Theatron core](https://github.com/theatronmc/theatron) will own the extension protocol, SDK, runtime, and documentation.
- [Extension registry](https://github.com/theatronmc/extension-registry) will index reviewed community extension metadata after its submission workflow is ready.

We will enable GitHub's template feature when the starter builds and passes its tests. Until then, please do not use this repository as the basis for an extension.
