# TensorFlow Mac OS X GPU Build patches

## Tested environment

- Mac OS X 10.12.6 16G1314
- CommandLine Tools for Xcode 8.3.2
- CUDA 9.1.128
- cuDNN 7.0
- Python 2.7.15 Homebrew
- Bazel 0.11.1

## Notes

NCCL builds in my env with patch, but doesn’t actually work yet.


## References

- https://storage.googleapis.com/74thopen/tensorflow_osx/index.html
- https://gist.github.com/mattiasarro/1f3498a26ad111a8d99199eaf64551be
- https://github.com/NVIDIA/nccl/pull/62/commits
- https://github.com/yifeif/tensorflow/commit/5de9b8463ee214a02aa71815c837b49c6ea2f93c
