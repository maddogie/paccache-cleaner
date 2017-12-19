# Maintainer: Jimmie Städele <maddogie {cat} gmail {dog} com>

pkgname=paccache-cleaner
pkgver=0.3
pkgrel=1
pkgdesc="Pacman hook to auromate clean up the pacman cache folder"
arch=('any')
url="https://github.com/maddogie/paccache-cleaner"
license=('')
depends=('')
source=("${pkgname}-${pkgver}.tar.gz::${url}/raw/master/${pkgname}-${pkgver}.tar.gz")
md5sums=('fc4eb62dfe9f366cafd2ebde415ee49b')

package() {
    mkdir -p "$pkgdir"/usr/share/libalpm/hooks
    cp "${srcdir}"/"${pkgname}"/"paccache-install_update.hook" "${pkgdir}"/usr/share/libalpm/hooks
    cp "${srcdir}"/"${pkgname}"/"paccache-remove.hook" "${pkgdir}"/usr/share/libalpm/hooks
     }
