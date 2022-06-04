pkgname="inet-comm"
pkgver=3.11
pkgrel=0
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
author="imperzer0"
url="https://github.com/$pkgname/$pkgname"
license=('GPL3')
depends=("log-console>=1.18-1")
_srcprefix="local:/"
source=("$_srcprefix/$pkgname")
md5sums=("821d75e92b329243cf1f80f142869c45")

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
