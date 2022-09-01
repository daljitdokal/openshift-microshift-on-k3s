## MicroShift

MicroShift is a project that is exploring how OpenShift Kubernetes can be optimized for small form factor and edge computing.

Edge devices deployed out in the field pose very different operational, environmental, and business challenges from those of cloud computing. These motivate different engineering trade-offs for Kubernetes at the far edge than for cloud or near-edge scenarios. MicroShift's design goals cater to this:

make frugal use of system resources (CPU, memory, network, storage, etc.),
tolerate severe networking constraints,
update (resp. rollback) securely, safely, speedily, and seamlessly (without disrupting workloads), and
build on and integrate cleanly with edge-optimized OSes like Fedora IoT and RHEL for Edge, while
providing a consistent development and management experience with standard OpenShift.
We believe these properties should also make MicroShift a great tool for other use cases such as Kubernetes applications development on resource-constrained systems, scale testing, and provisioning of lightweight Kubernetes control planes.

## System Requirements

To run MicroShift, you need a machine with at least:

- x86_64/AMD64 or ARM64 CPU architecture
- Red Hat Enterprise Linux 8 with Extended Update Support (8.6 or later)
- 2 CPU cores
- 2GB of RAM
- 1GB of free storage space for MicroShift

## K3S setup




## Note:

- It is only available in single node , `Multi node cluster support` is not available at this stage but under `PR` or `Work in progress`. 

## References:

- https://github.com/openshift/microshift
- https://microshift.io/docs/getting-started/
- https://www.youtube.com/watch?v=yLf6J3t5XnU
