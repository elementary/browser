project('org.gnome.Epiphany',
    meson_version: '>= 0.57.0'
)

subdir('data')

gnome = import('gnome')
gnome.post_install(
    gtk_update_icon_cache: true
)
