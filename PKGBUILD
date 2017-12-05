# Maintainer: Ramon Buldó <rbuldo@gmail.com>
# Maintainer: Bernhard Landauer <oberon@manjaro.org

pkgname=browser-settings-kibojoe
pkgver=20171203
pkgrel=1
pkgdesc="Kibojoe Linux settings browser defaults"
arch=(x86_64')
url="https://github.com/manjaro/$pkgname"
license=('GPL')
_gitcommit=19f02dcc9e109fe08abb7b163ec537d0c5cb4fdf
source=("$pkgname-$_gitcommit.tar.gz::$url/archive/$_gitcommit.tar.gz")
md5sums=('b91de27020a6faf58a0c720ef972e847')

pkgver() {
  date +%Y%m%d
}

package() {
  cd $pkgname-$_gitcommit
  mkdir -p $pkgdir/usr/lib/palemoon/distribution
  cp palemoon/* $pkgdir/usr/lib/palemoon/distribution
}