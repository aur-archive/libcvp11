# Maintainer: Slavi Pantaleev <s.pantaleev at gmail.com>
# To report issues or contribute: https://github.com/spantaleev/PKGBUILDs

pkgname=libcvp11
pkgver=1.0.0
pkgrel=2
pkgdesc="libcvP11.so (CryptoVision Smart Card driver)"
arch=('x86_64')
license=('unknown')
url="http://www.cryptovision.com/"
install=$pkgname.install
source=('http://www.b-trust.org/download/libcvP11_x64.zip')
md5sums=('6ef18ed5795c341421474ba9a811d2a4')

package() {
	install -Dm 644 $srcdir/libcvP11.so $pkgdir/usr/lib/libcvP11.so
}
