# Generated file; do not modify.
subdir('Status')
generated_others += custom_target(
    'xyz/openbmc_project/State/OperatingSystem/Status__markdown'.underscorify(),
    input: [ meson.source_root() / 'xyz/openbmc_project/State/OperatingSystem/Status.interface.yaml',  ],
    output: [ 'Status.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.source_root(),
        'xyz/openbmc_project/State/OperatingSystem/Status',
    ],
    build_by_default: true,
)

