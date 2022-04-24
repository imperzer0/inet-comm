pkgname="inet-comm"
epoch=3
pkgver=7
pkgrel=0
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
author="imperzer0"
url="https://github.com/$pkgname/$pkgname"
license=('GPL3')
depends=("log-console>=1.17-1")
makedepends=()
_prefix_src="local:/"
source=("$_prefix_src/$pkgname")
md5sums=("520684ecb0d62c681886092e0584bf4a")

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
