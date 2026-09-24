# Maintainer: smtdfc <me.smtdfc@gmail.com>

pkgname=bakeryos-wallpapers
pkgver=1.0.0
pkgrel=1
pkgdesc="Wallpapers for BakeryOS"
arch=('any')
url="https://github.com/bakeryos-project/bakeryos-wallpapers"
license=('GPL-3.0-or-later')
depends=(
  'plymouth'
)
source=(
  
)
sha256sums=(
  
)
options=(!debug !strip)

package() {
  install -d "${pkgdir}/usr/share/doc/bakeryos/wallpapers"
  install -d "${pkgdir}/usr/share/gnome-background-properties"
  install -d "${pkgdir}/usr/share/backgrounds/bakeryos-wallpapers"
  
  install -Dm644 "${srcdir}/CREDIT.md" "${pkgdir}/usr/share/doc/bakeryos/wallpapers/CREDIT.md"
  install -Dm644 "${srcdir}/gnome-background-properties/bakeryos.xml" "${pkgdir}/usr/share/gnome-background-properties/bakeryos.xml"
  cp -a ${srcdir}/bakeryos-wallpapers/* "${pkgdir}/usr/share/backgrounds/bakeryos-wallpapers/"
}