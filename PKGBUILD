# Maintainer: Santiago Soler <santiago.r.soler@gmail.com>

pkgname=i3exit-lightdm
pkgver=20200712
pkgrel=1
pkgdesc="Systemd/OpenRC-compatible exit-script for i3, uses 'lightdm'"
arch=('any')
groups=('i3-manjaro')
license=('GPL')
depends=('i3-wm'
    'i3lock'
    'lightdm'
    'imagemagick')
optdepends=('lightdm-gtk-greeter: switch user with lightdm')
source=("$pkgname")
md5sums=('6052962bd441aa1f023c81e60a3a5580')

pkgver() {
	date +'%Y%m%d'
}

package() {
	install -Dm755 $srcdir/$pkgname $pkgdir/usr/bin/i3exit-lightdm
}
