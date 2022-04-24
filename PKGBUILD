pkgname="inet-comm"
pkgver=3.7
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
md5sums=("1015ed26e90ac5704b8ec022a371fbcd")

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
