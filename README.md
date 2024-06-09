# Bazel registry

This is a [Bazel registry](https://bazel.build/external/registry).

- Changes to existing modules are allowed and performed (e.g. updating dependencies)
- The main target are C++ third-party libraries
- Half-backend and experimental modules are allowed
- Some modules may be moved to the [Bazel Central Registry](https://registry.bazel.build/) in the future

## How to use?

You can add this registry to your `.bazelrc` file via:

```
common --registry=https://raw.githubusercontent.com/Vertexwahn/bazel-registry/main
```

To make sure the Bazel Central registry is still working for you make sure that also this line is in your `.bazelrc` file:

```
common --registry=https://bcr.bazel.build
```

## Supported modules

See the [modules](/modules/) folder for currently supported modules.

## Other registries

- [bazelboost/registry](https://github.com/bazelboost/registry)
- [bazel-eomii-registry](https://github.com/eomii/bazel-eomii-registry)
- [obazl/registry](https://github.com/obazl/registry)

If you know of any other public registries please drop me a mail.
