# Maintainer: Your Name <comradelukmanov@gmail.com>
pkgname=hyprscreenshot
pkgver=1.0
pkgrel=1
pkgdesc="Simple screenshot bash script for Hyprland."
url="https://github.com/comradelukmanov/hyprscreenshot"
packager="Lukmanov Lukman <comradelukmanov@gmail.com>"
license=(nah)
arch=("any")
depends=("hyprland" "jq" "grim" "wl-clipboard")
source=("${pkgname}")
sha256sums=("da4590035fbe41a9539bc3b477811167097347a4b72fe519d518fa5ca1342f11")

package() {
	mkdir -p "${pkgdir}/usr/local/bin"
	cp "${srcdir}/${pkgname}" "${pkgdir}/usr/local/bin/${pkgname}"
	chmod 755 "${pkgdir}/usr/local/bin/${pkgname}"
}
