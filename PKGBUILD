# Maintainer: Parchlinux
pkgname=parch-community-backgrounds
destname="/"
pkgver=2
pkgrel=0
pkgdesc="parchlinux community backgrounds"
arch=('any')
url="https://github.com/parchlinuxb/"
license=('GPL3')
makedepends=()
depends=()
conflicts=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}#branch=package-a")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${destname}
	cp -r ${srcdir}/${pkgname}${destname}/* ${pkgdir}${destname}
}
