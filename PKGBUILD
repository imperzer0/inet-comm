pkgname="inet-comm"
pkgver=3.10
pkgrel=0
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
author="imperzer0"
url="https://github.com/$pkgname/$pkgname"
license=('GPL3')
depends=("log-console>=1.18-1")
makedepends=()
_srcprefix="local:/"
source=("$_srcprefix/$pkgname")
md5sums=("23f4d20ec8ff267681bcdbfbd9571072")

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
