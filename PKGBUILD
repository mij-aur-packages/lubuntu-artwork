# Maintainer: lestb <b.lester011+arch at gmail dot com>
# Contributor: 謝致邦<Yeking@Red54.com>

pkgname=lubuntu-artwork
pkgver=0.41
pkgrel=1
pkgdesc='artwork of Lubuntu'
arch=('any')
url='http://wiki.ubuntu.com/Lubuntu/Artwork'
license=('GPL')
optdepends=('gtk-engine-murrine: gtk2 theme support'
            'elementary-icon-theme: icons support'
            'gtk-engine-unico: gtk3 theme support')
source=("http://archive.ubuntu.com/ubuntu/pool/universe/l/${pkgname}/${pkgname}_${pkgver}.tar.gz")
sha256sums=('a802683b13956478f10fbee35555c107bec436aae59fc3beda1050bbdfc45db6')

package(){
    cp -r "${srcdir}/${pkgname}-${pkgver}/usr" "${pkgdir}"
}
