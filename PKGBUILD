pkgname="inet-comm"
epoch=3
pkgver=0
pkgrel=0
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
url="https://github.com/imperzer0/inet-comm"
license=('GPL')
depends=("log-console>=1.17-1")
makedepends=()
source=("local://inet-comm")
md5sums=("SKIP")
# install=inet-comm.install

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
