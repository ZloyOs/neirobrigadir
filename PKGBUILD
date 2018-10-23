# Maintainer: Grey Wolf
pkgname=ping-indicator
pkgver=1.0
pkgrel=2
pkgdesc="Ping monitor applet"
arch=('x86_64')
url="https://zvvubuntu.blogspot.com"
license=('custom')
#depends=(‘pyqt5-common’ ‘python-pyqt5’ ‘vlc’ ‘python-six’)
source=(ping-indicator_${pkgver}-${pkgrel}_amd64.deb)
md5sums=('fa49d47918084b983f96f6336e8c5514')

package() {
cd "${srcdir}"
bsdtar -xf data.tar.xz -C "$pkgdir"
}
