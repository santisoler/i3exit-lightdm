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
md5sums=('7efe8a07db38effea294b9e3ddaa898f')

pkgver() {
	date +'%Y%m%d'
}

package() {
	install -Dm755 $srcdir/$pkgname $pkgdir/usr/bin/i3exit-lightdm
}
