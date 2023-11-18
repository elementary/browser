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

icon_names = [
    'ephy-audio-muted-symbolic.svg',
    'ephy-audio-playing-symbolic.svg',
    'ephy-bookmark-tag-symbolic.svg',
    'ephy-download-done-symbolic.svg',
    'ephy-download-symbolic.svg',
    'ephy-non-starred-symbolic.svg',
    'ephy-open-link-symbolic.svg',
    'ephy-permission-camera-symbolic.svg',
    'ephy-permission-generic-symbolic.svg',
    'ephy-permission-location-symbolic.svg',
    'ephy-permission-microphone-symbolic.svg',
    'ephy-permission-notifications-symbolic.svg',
    'ephy-starred-symbolic.svg'
]

foreach icon_name : icon_names
    install_data(
        icon_name,
        install_dir: get_option('datadir') / 'icons' / 'elementary' / 'status' / 'symbolic',
    )
endforeach
