pkgname=parrotsay
pkgver=2.0.0
pkgrel=1
pkgdesc="A cowsay clone because they didn't add a parrot..."
arch=('any')
depends=('python')

package() {
    install -Dm755 "$startdir/parrotsay" "$pkgdir/usr/bin/parrotsay"
    ln -s parrotsay "$pkgdir/usr/bin/parrotsay-c"
}
