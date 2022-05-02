pkgname="inet-comm"
pkgver=3.8
pkgrel=1
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
author="imperzer0"
url="https://github.com/$pkgname/$pkgname"
license=('GPL3')
depends=("log-console>=1.18-1")
makedepends=()
_srcprefix="local:/"
source=("$_srcprefix/$pkgname")
md5sums=("724e233a064358cdf2199fe251870c0c")

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
