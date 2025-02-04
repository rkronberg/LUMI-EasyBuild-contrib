# GROMACS user instructions

## A note about the GPU versions.

There exist two different versions of GROMACS for AMD GPUs.

-   The authors of GROMACS use SYCL for an implementation for AMD GPUs. These versions
    are or will be part of the official GROMACS distribution channels.
-   AMD has made a hip port of the CUDA version. It is not clear though to what extent
    that branch will see further development as GROMACS evolves.

When testing in early 2023, the HIP port offered significantly better performance than the
SYCL port.

Check the technical documentation of the EasyConfigs to find out on which branch of GROMACS
the recipes are based. That documentation is more towards the bottom of the page.

