# Maintainer: Macquarie <macquarie.sharpless@gmail.com>
pkgname=invisibleink
pkgver=0.1.1
pkgrel=1
epoch=0
pkgdesc="A small tool to simplify working with gpg-encrypted text"
arch=(any)
url="https://github.com/grimheart/invisibleink"
license=('MIT')
depends=(bash coreutils gnupg)
source=(https://github.com/grimheart/invisibleink/archive/v$pkgver.tar.gz)
md5sums=('a620ec39c5d10d3b16174c0a2cfce4f9')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  install -d "$pkgdir/usr/bin"                     \
             "$pkgdir/usr/share/doc/$pkgname"      \
             "$pkgdir/usr/share/licenses/$pkgname"
  install        ii          "$pkgdir/usr/bin"
  install -m 644 LICENSE     "$pkgdir/usr/share/licenses/$pkgname"
  install -m 644 README TODO "$pkgdir/usr/share/doc/$pkgname"
}

