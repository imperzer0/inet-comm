pkgname="inet-comm"
epoch=1
pkgver=3
pkgrel=3
pkgdesc="ipv4 internet tcp socket communication library"
arch=("x86_64")
url="https://github.com/imperzer0/inet-comm"
license=('GPL')
depends=("log-console>=1.3-1")
makedepends=("cmake>=3.0")
source=("local://inet-comm")
md5sums=("SKIP")
# install=inet-comm.install

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
