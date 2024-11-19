# Maintainer: Your Name <comradelukmanov@gmail.com>
pkgname=hyprscreenshot
pkgver=1.0
pkgrel=1
pkgdesc="Simple screenshots script for Hyprland."
url="https://github.com/comradelukmanov/hyprscreenshot/releases/edit/untagged-ed834c8ce3bda7d8c233"
packager="Lukmanov Lukman <comradelukmanov@gmail.com>"
license=(nah)
arch=("any")
depends=("jq" "hyprland" "grim" "wl-clipboard")
source=("${pkgname}")
sha256sums=("74b67cbe7148389de5e5ae0f7d25c6e6072af90f5d1c4c7bd3c8cc4c8358a777")

package() {
	mkdir -p "${pkgdir}/usr/local/bin"
	cp "${srcdir}/${pkgname}" "${pkgdir}/usr/local/bin/${pkgname}"
	chmod 755 "${pkgdir}/usr/local/bin/${pkgname}"
}
