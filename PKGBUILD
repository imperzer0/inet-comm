pkgname="inet-comm"
epoch=1
pkgver=2
pkgrel=1
pkgdesc="ipv4 internet tcp socket communication library"
arch=("x86_64")
url="https://github.com/imperzer0/inet-comm"
license=('GPL')
depends=("log-console")
makedepends=("cmake>=3.0")
source=("local://log-console")
md5sums=("SKIP")
# install=inet-comm.install

package()
{
	install -Dm755 "./$pkgname" "$pkgdir/usr/include/$pkgname"
}
