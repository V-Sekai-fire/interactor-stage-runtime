# interactor-stage-runtime

A prebuilt USD scene-description runtime per platform triplet, shipped as the `stage_runtime` Mix package.

## Use

A port, adapter or Elixir consumer adds `stage_runtime` as a dependency and asks `StageRuntime` for the include directory, library directory and target triplet to build against. The project began from [idtx-flow](https://github.com/Immersive-Data-Center-Management/idtx-flow).

## Build and run

On first use the package downloads and verifies the prebuilt archive that matches its version and the host. To build the runtime from source instead:

```sh
OPENUSD_BUILD=true mix compile
```

## Licence

Apache-2.0. See `LICENSE`.
