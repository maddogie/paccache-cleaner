# Maintainer: Jimmie Städele <maddogie {cat} gmail {dog} com>

pkgname=paccache-cleaner
pkgver=0.1
pkgrel=1
pkgdesc="Pacman hook to auromate clean up the pacman cache folder"
arch=('any')
url="https://github.com/maddogie/paccache-cleaner"
license=('none')
depends=('pacman>=5.0')
#source=("${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/${pkgname}-${pkgver}.tar.gz")
source=("${pkgname}-${pkgver}.tar.gz::${url}/${pkgname}-${pkgver}.tar.gz")
md5sums=('8993690cfb5918d607b77b2998c8a87a')

package() {
    cd "${pkgname}"
#    cp "${srcdir}"/"${pkgname}"-"${pkgver}"/usr/share/libalpm/hooks/"${pkgname}.hook" "${pkgdir}"/usr/share/libalpm/hooks
    cp "${srcdir}"/"${pkgname}"-"${pkgver}"/usr/share/libalpm/hooks/"${pkgname}.hook" "${pkgdir}"/tmp
}
