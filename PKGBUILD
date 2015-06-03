pkgname=webcore-fonts
pkgver=3.0
pkgrel=3
pkgdesc="Collection of minimum popular high quality TrueType fonts"
url="http://avi.alkalay.net/software/webcore-fonts/"
source=(http://avi.alkalay.net/software/webcore-fonts/$pkgname-$pkgver.tar.gz)
sha512sums=('7fabb900cd17d326a4e8bbb6d59ae156ba8685fd9b1e9fa8de76f593ab7f29866730de059d520af63c6ce87b7ba0970564cf9282c7889fa00b85f1234eaf9f6a')
install=webcore-fonts.install
arch=('x86_64')
license=('EULA')

package() {
    cd $srcdir/$pkgname
    
    mkdir -p $pkgdir/usr/share/fonts/webcore
    mkdir -p $pkgdir/usr/share/fonts/webcore-vista
    mkdir -p $pkgdir/usr/share/doc/webcore-fonts
    
    mv fonts/* $pkgdir/usr/share/fonts/webcore
    mv vista/* $pkgdir/usr/share/fonts/webcore-vista
    mv doc/* $pkgdir/usr/share/doc/webcore-fonts
    }
