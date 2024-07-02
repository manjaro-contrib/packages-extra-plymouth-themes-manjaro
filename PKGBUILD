# Contributor: Bernhard Landauer <oberon@manjaro.org>

pkgname=(
  'plymouth-theme-manjaro-cinnamon'
  'plymouth-theme-manjaro-circle'
  'plymouth-theme-manjaro-deepin-circle'
  'plymouth-theme-manjaro-deepin'
  'plymouth-theme-manjaro-extra-elegant'
  'plymouth-theme-manjaro-gnome'
)
pkgbase=plymouth-themes-manjaro
pkgver=2.0
pkgrel=5
pkgdesc="Manjaro Plymouth themes"
arch=('any')
url="https://github.com/oberon-manjaro/plymouth-themes-manjaro"
license=('GPL-3.0-or-later')
depends=('plymouth')
makedepends=('git')
_commit=499339f76fdbf16af2d194d9c2c2178b48513090
source=("git+https://github.com/oberon-manjaro/plymouth-themes-manjaro.git#commit=${_commit}")
sha256sums=('0b7c0715961f492244b6827c8a0e98526e82568bd46c33ebdc29a6526f5a2d49')

package_plymouth-theme-manjaro-cinnamon() {
  pkgdesc="Plymouth theme for Manjaro Cinnamon"
  install=manjaro-cinnamon.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-cinnamon "$pkgdir/usr/share/plymouth/themes"
}

package_plymouth-theme-manjaro-circle() {
  pkgdesc="Green and grey Plymouth theme with round icon"
  install=manjaro-circle.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-circle "$pkgdir/usr/share/plymouth/themes"
}

package_plymouth-theme-manjaro-deepin-circle() {
  pkgdesc="Plymouth theme for Manjaro Deepin with round icon"
  install=manjaro-deepin-circle.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-deepin-circle "$pkgdir/usr/share/plymouth/themes"
}

package_plymouth-theme-manjaro-deepin() {
  pkgdesc="Plymouth theme for Manjaro Deepin"
  install=manjaro-deepin.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-deepin "$pkgdir/usr/share/plymouth/themes"
}

package_plymouth-theme-manjaro-extra-elegant() {
  pkgdesc="Green Manjaro Plymouth theme with round icon"
  install=manjaro-extra-elegant.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-extra-elegant "$pkgdir/usr/share/plymouth/themes"
}

package_plymouth-theme-manjaro-gnome() {
  pkgdesc="Plymouth theme for Manjaro GNOME"
  install=manjaro-gnome.install

  cd "$pkgbase"
  install -d "$pkgdir/usr/share/plymouth/themes"
  cp -r manjaro-gnome "$pkgdir/usr/share/plymouth/themes"
}
