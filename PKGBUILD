# Maintainer: Lucas Saliés Brum <lucas@archlinux.com.br>
# Contributor: /dev/rs0 <rs0@secretco.de.com>
# Contributor: Robin Martinjak <rob@rmartinjak.de>

pkgname=Endeavouros-xfce-screensaver-theme
pkgver=1.0
pkgrel=3
pkgdesc="Endeavouros logo screensaver theme Xfce4"
arch=('any')
depends=('xfce4-screensaver')
url="http://www.xfce.org"
license=('GPL')
source=("git+https://github.com/ringo32/ringo32")
md5sums=('SKIP')

package() {
  install -d "${pkgdir}/usr/"
  cp -a "${srcdir}/ringo32/usr/." "${pkgdir}/usr/"
}
