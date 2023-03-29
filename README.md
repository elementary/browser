# Epiphany
Epiphany (aka GNOME Web) Flatpak'd for elementary OS

## Building, Testing, and Installation

Run `flatpak-builder` to configure the build environment, download dependencies, build, and install

    flatpak-builder build org.gnome.epiphany.json --user --install --force-clean --install-deps-from=appcenter

execute with `org.gnome.Epiphany`

    flatpak run org.gnome.Epiphany
