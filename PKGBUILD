# Maintainer: Bernhard Landauer <oberon@manjaro.org>

pkgname=i3exit
pkgver=20200217
pkgrel=1
pkgdesc="Systemd/OpenRC-compatible exit-script for i3, including 'blurlock'"
arch=('any')
groups=('i3-manjaro')
license=('GPL')
depends=('i3-wm'
    'i3lock'
    'imagemagick')
optdepends=('lightdm-gtk-greeter: switch user with lightdm')
source=("$pkgname"
    'blurlock')
md5sums=('6052962bd441aa1f023c81e60a3a5580'
         'e3699b2b3acaa6e59e4d40d9229273ea')

pkgver() {
	date +'%Y%m%d'
}

package() {
	install -Dm755 $srcdir/$pkgname $pkgdir/usr/bin/i3exit
	install -Dm755 $srcdir/blurlock $pkgdir/usr/bin/blurlock
}
