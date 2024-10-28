# LLM artifacts 

All artifacts are uploaded as binaries to the release tagged v0.0.1

- Scipy:  [en_core_sci_md-0.5.4.tar.gz](https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_core_sci_md-0.5.4.tar.gz)
- Open-MPI (For multi-GPU processing): [openmpi_4.1.6.orig.tar.xz](http://archive.ubuntu.com/ubuntu/pool/universe/o/openmpi/openmpi_${OPENMPI_VERSION}.orig.tar.xz)

# Llama-cpp-pyhton custom pre-built wheels

- Current pre-built wheels do not support tesla v100 due to CMAKE args settings used within llama-cpp-python CUDA wheel release process. Uploaded artifact aims to  overrid the said CMAKE args and build CUDA compatible pre-built wheels.
- Also aims to fixe a musl linux bug in the llama-cpp-python CPU pre-built wheel as well. 

