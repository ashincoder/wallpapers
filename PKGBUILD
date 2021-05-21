# Maintainer: Ashin Antony <ashinant15@gmail.com>

pkgname=ashin-wallpapers
pkgver=1
pkgrel=1
pkgdesc="A collection of cool wall papers!"
arch=('any')
groups=('')
url="https://github.com/ashincoder/wallpapers"
license=('')
optdepends=('feh: Allows setting wallpaper' 'multimonitorlock-gui: Allows the background to be changed')
makedepends=('git')
source=("git+$url")
md5sums=('SKIP')

package() {
  mkdir -p $pkgdir/usr/share/backgrounds
	cp -a $srcdir/wallpapers $pkgdir/usr/share/backgrounds
}
