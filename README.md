# TensorFlow Mac OS X GPU Build patches

## Tested environment

- Mac OS X 10.12.6 16G1314 / MAC OS X 10.13.6 17G65
- CUDA 9.1.128
- cuDNN 7.0
- Python 2.7.15 Homebrew
- Bazel 0.11.1 (for v1.9 and previous); Bazel 0.15.2 (for v1.10.1 and later)
- CommandLine Tools for Xcode 8.3.2 / Xcode 8.3.2 (for Bazel 0.15.2 due to a bug that Bazel cannot recognize CommandLine Tools properly)

## Instruction

-- Apply patch to tensorflow repo.
-- Run build-mac-os-x.sh or manually do the steps inside.

## Notes

NCCL builds in my env with patch, but doesn’t actually work yet.


## References

- https://storage.googleapis.com/74thopen/tensorflow_osx/index.html
- https://gist.github.com/mattiasarro/1f3498a26ad111a8d99199eaf64551be
- https://github.com/NVIDIA/nccl/pull/62/commits
- https://github.com/yifeif/tensorflow/commit/5de9b8463ee214a02aa71815c837b49c6ea2f93c
- https://devtalk.nvidia.com/default/topic/1032646/cuda-setup-and-installation/macos-10-13-4-and-xcode-9-3-compatibility-broken-with-cuda-toolkit-9-1/
- https://segmentfault.com/a/1190000015807229
