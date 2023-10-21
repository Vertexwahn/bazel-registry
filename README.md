# Bazel registry

This is a [Bazel registry](https://bazel.build/external/registry).

## How to use?

You can add this registry to your `.bazelrc` file via:

```
common --registry=https://raw.githubusercontent.com/Vertexwahn/bazel-registry/main/
```

## Supported modules

### libwebp

Moved to the [Bazel Central Registry](https://registry.bazel.build/) (see this [PR](https://github.com/bazelbuild/bazel-central-registry/pull/1038)).

### libpng

Moved to the [Bazel Central Registry](https://registry.bazel.build/) (see this [PR](https://github.com/bazelbuild/bazel-central-registry/pull/1005)).

### embree

Moved to the [Bazel Central Registry](https://registry.bazel.build/) (see this [PR](https://github.com/bazelbuild/bazel-central-registry/pull/964)).

### libwebp

Moved to the [Bazel Central Registry](https://registry.bazel.build/) (see this [PR](https://github.com/bazelbuild/bazel-central-registry/pull/1038)).

### nasm

Moved to the [Bazel Central Registry](https://registry.bazel.build/) (see this [PR](https://github.com/bazelbuild/bazel-central-registry/pull/1042)).

### libjpeg_turbo

### pugixml

Still experimental.

## Differences to Bazel Central Registry

- Changes to existing modules are allowed and performed (e.g. updating dependencies)
- Main target are C++ third party libraries
- Half-backend and experimental modules are allowed
