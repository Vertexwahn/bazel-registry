# Bazel registry

This is a [Bazel registry](https://bazel.build/external/registry).

## How to use?

You can add this registry to your `.bazelrc` file via:

```
common --registry=https://raw.githubusercontent.com/Vertexwahn/bazel-registry/main/
```

## Supported modules

### embree

Embree is middleware for ray tracing that computes intersections points between rays and different shape types.
Currently, there is [an attempt](https://github.com/bazelbuild/bazel-central-registry/pull/964) to move this module to the [Bazel Central Registry](https://registry.bazel.build/).

### libwebp

Still experimental.

### pugixml

Still experimental.

## Differences to Bazel Central Registry

- Changes to existing modules are allowed and performed (e.g. updating dependencies)
- Main target are C++ third party libraries
- Half-backend and experimental modules are allowed
