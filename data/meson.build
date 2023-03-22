icon_sizes = ['16', '24', '32', '48', '64', '128']

foreach i : icon_sizes
    install_data(
        join_paths('icons', i + '.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons', 'hicolor', i + 'x' + i, 'apps'),
        rename: meson.project_name() + '.svg'
    )
    install_data(
        join_paths('icons', i + '.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons', 'hicolor', i + 'x' + i + '@2', 'apps'),
        rename: meson.project_name() + '.svg'
    )
endforeach

install_data(
    'adw-expander-arrow-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'actions' / 'symbolic',
)

install_data(
    'list-drag-handle-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'actions' / 'symbolic',
)

install_data(
    'selection-mode-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'actions' / 'symbolic',
)

install_data(
    'adw-tab-counter-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)

install_data(
    'adw-tab-icon-missing-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)

install_data(
    'adw-tab-overflow-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)

install_data(
    'adw-tab-unpin-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)

install_data(
    'ephy-non-starred-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)

install_data(
    'ephy-starred-symbolic.svg',
    install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
)
