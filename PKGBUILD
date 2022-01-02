pkgname="inet-comm"
epoch=2
pkgver=3
pkgrel=0
pkgdesc="ipv4 internet tcp socket c++ library"
arch=("x86_64")
url="https://github.com/imperzer0/inet-comm"
license=('GPL')
depends=("log-console>=1.16-0")
makedepends=()
source=("local://inet-comm")
md5sums=("SKIP")
# install=inet-comm.install

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
