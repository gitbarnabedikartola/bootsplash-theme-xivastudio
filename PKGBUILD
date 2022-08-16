pkgbase=bootsplash-themes
pkgname=('bootsplash-theme-xivastudio')
pkgver=0.1
pkgrel=3
url="https://github.com/gitbarnabedikartola/bootsplash-theme-xivastudio.git"
arch=('x86_64')
license=('GPL')

depends=("bootsplash-systemd" "bootsplash-manager" "imagemagick")
options=('!libtool' '!emptydirs')

source=('bootsplash-packer'
	'bootsplash-xivastudio.sh'
	'bootsplash-xivastudio.initcpio_install'
	'logo.gif')

sha256sums=('SKIP'
            'SKIP'
            'SKIP'
            'SKIP')
install=post.install
build() {
  cd "$srcdir"
  sh ./bootsplash-xivastudio.sh
}

package_bootsplash-theme-xivastudio() {
  pkgdesc="Bootsplash Theme with xivastudio logo"
  cd "$srcdir"

#   install -Dm644 "$srcdir/bootsplash-xivastudio" "$pkgdir/usr/lib/firmware/bootsplash-themes/xivastudio/bootsplash"
#   install -Dm644 "$srcdir/bootsplash-xivastudio.initcpio_install" "$pkgdir/usr/lib/initcpio/install/bootsplash-xivastudio"
#   cp -R "$srcdir/usr" "$pkgdir/"

} 
