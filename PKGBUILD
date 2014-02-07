# Maintainer: Macquarie <macquarie.sharpless@gmail.com>
pkgname=invisibleink
pkgver=0.1.0
pkgrel=1
epoch=0
pkgdesc="A small tool to simplify working with gpg-encrypted text"
arch=(any)
url="https://github.com/grimheart/invisibleink"
license=('MIT')
depends=(bash coreutils gnupg)
source=(https://github.com/grimheart/invisibleink/archive/v$pkgver.tar.gz)
md5sums=('a68612b33bb3f1f560499a287d6c0b4c')

package() {
	cd "$srcdir/$pkgname-$pkgver"
	install -D      ii      "$pkgdir/usr/bin/ii"
	install -Dm 644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm 644 README  "$pkgdir/usr/share/doc/$pkgname/README"
}

