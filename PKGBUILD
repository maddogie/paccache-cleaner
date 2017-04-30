# Maintainer: Jimmie Städele <maddogie {cat} gmail {dog} com>

pkgname=paccache-cleaner
pkgver=0.2
pkgrel=1
pkgdesc="Pacman hook to auromate clean up the pacman cache folder"
arch=('any')
url="https://github.com/maddogie/paccache-cleaner"
license=('')
depends=('')
#source=("${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/${pkgname}-${pkgver}.tar.gz")
source=("${pkgname}-${pkgver}.tar.gz::${url}/${pkgname}-${pkgver}.tar.gz")
md5sums=('e2727c73c769ebe97f72d9bce49d43b7')

package() {
    cd "${pkgdir}"
#    cp "${srcdir}"/"${pkgname}"-"${pkgver}"/usr/share/libalpm/hooks/"${pkgname}.hook" "${pkgdir}"/usr/share/libalpm/hooks
#    mkdir -p "$pkgdir"/tmp/hundededreck/stinkt/
    cp "${srcdir}"/usr/share/libalpm/hooks/"${pkgname}.hook" "${pkgdir}"/usr/share/libalpm/hooks
#     install -Dm0644 "${srcdir}"/usr/share/libalpm/hooks/"${pkgname}.hook" "${pkgdir}"/usr/share/libalpm/hooks
     }
