# Maintainer: Ramon Buldó <rbuldo@gmail.com>
# Maintainer: Bernhard Landauer <oberon@manjaro.org

pkgname=browser-settings-kibojoe
pkgver=20171203
pkgrel=1
pkgdesc="Kibojoe Linux settings browser defaults"
arch=('x86_64')
url="https://github.com/kibojoe/$pkgname"
license=('GPL')
source=("git+$url.git")
md5sums=('SKIP')

pkgver() {
  date +%Y%m%d
}

package() {
  mkdir -p $pkgdir/usr/lib/palemoon/distribution
  cp palemoon/* $pkgdir/usr/lib/palemoon/distribution
}