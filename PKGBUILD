pkgname=ttf-pushkin
pkgver=5.03
pkgrel=2
pkgdesc="Pushkin font"
arch=('any')
url="http://kde-look.org/content/show.php?content=106881&vote=good&tan=22273350"
license=('Creative Commons')
depends=('fontconfig' 'xorg-font-utils')
install=ttf.install
source=(http://kde-look.org/CONTENT/content-files/106881-newPushkin.ttf)
md5sums=('b0d0ce16f772ed5b62a921e339566347')

build() {
	install -Dm644 $srcdir/*.ttf $pkgdir/usr/share/fonts/TTF/106881-newPushkin.ttf
} 
