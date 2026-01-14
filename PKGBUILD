# Maintainer: Petexy <https://github.com/Petexy>

pkgname=linexin-desktop
pkgver=1.0.2.r
pkgrel=1
_currentdate=$(date +"%Y-%m-%d%H-%M-%S")
pkgdesc='Linexin GNOME Desktop Full Experience'
url='https://github.com/Petexy'
arch=(x86_64)
license=('GPL-3.0')
depends=(
	colord-gtk-common
	colord-gtk4
	cups-pk-helper
	gnome-keybindings
	gsound
	ibus
	libgdm
	libibus
	libnma-gtk4
	libspelling
	baobab
	decibels
	epiphany
	gdm
	gnome-backgrounds
	gnome-calculator
	gnome-calendar
	gnome-characters
	gnome-clocks
	gnome-color-manager
	gnome-connections
	gnome-console
	gnome-contacts
	gnome-control-center
	gnome-disk-utility
	gnome-font-viewer
	gnome-keyring
	gnome-logs
	gnome-maps
	gnome-menus
	gnome-music
	gnome-remote-desktop
	gnome-session
	gnome-settings-daemon
	gnome-shell
	gnome-software
	gnome-system-monitor
	gnome-text-editor
	gnome-tour
	gnome-user-docs
	gnome-user-share
	gnome-weather
	grilo-plugins
	gvfs
	gvfs-afc
	gvfs-dnssd
	gvfs-goa
	gvfs-google
	gvfs-gphoto2
	gvfs-mtp
	gvfs-nfs
	gvfs-onedrive
	gvfs-smb
	gvfs-wsdd
	loupe
	malcontent
	nautilus
	orca
	papers
	rygel
	showtime
	simple-scan
	snapshot
	sushi
	tecla
	xdg-desktop-portal-gnome
	xdg-user-dirs-gtk
	yelp
)
makedepends=(
)
options=(!strip !debug)
install="${pkgname}.install"

package() {
   cp -rf ${srcdir}/* ${pkgdir}/
}
