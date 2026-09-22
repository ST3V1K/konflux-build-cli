# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-09-22

### Added

- `image build`: build and optionally push container images, including
  hermetic and multi-platform builds.
- `image apply-tags` and `image build-image-index`: manage image tags and
  assemble multi-architecture image indexes.
- `image push-containerfile`: publish Containerfiles and Dockerfiles as OCI
  artifacts.
- `git-clone`: clone repositories with authentication, submodules, sparse
  checkout, branch merging, and symlink safety checks.
- `prefetch-dependencies` and `config cache-proxy`: support hermetic
  dependency prefetching and Konflux proxy configuration.
- `image build`: support image metadata, content scanning, dependency
  prefetching, and reliable registry operations.
