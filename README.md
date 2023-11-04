# Bazel registry

This is a [Bazel registry](https://bazel.build/external/registry).

- Changes to existing modules are allowed and performed (e.g. updating dependencies)
- The main target are C++ third-party libraries
- Half-backend and experimental modules are allowed
- Some dependencies may be moved to the [Bazel Central Registry](https://registry.bazel.build/) in the future

## How to use?

You can add this registry to your `.bazelrc` file via:

```
common --registry=https://raw.githubusercontent.com/Vertexwahn/bazel-registry/main
```

## Supported modules

See the [modules](/modules/) folder for currently supported modules.
