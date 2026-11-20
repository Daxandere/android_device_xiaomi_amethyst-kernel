# Kernel inputs for amethyst Global 307

This branch provides the kernel, DTBs, DTBO and module sets extracted from
Xiaomi HyperOS Global `OS3.0.307.0.WOPMIXM` for the Redmi Note 14 Pro+ 5G
Global. The kernel release is
`6.1.138-android14-11-g0c3d559bcd85-ab14529422`.

The headers remain at upstream revision
`f118e1dbd36c0446ad9f2d20f4690618d3ccb816`, the header set used in the
verified device builds. The `kernel-kit.sha256` file records the exact
prebuilt bundle. Run `sha256sum -c kernel-kit.sha256` from this checkout to
verify it. The amethyst local manifest selects this branch and the matching
device configuration.
