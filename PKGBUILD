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
md5sums=('84fd2e0878c7d70932d7a8d94e1958a8')

package() {
    mkdir -p "$pkgdir"/usr/share/libalpm/hooks
    cp "${srcdir}"/"${pkgname}"/"${pkgname}.hook" "${pkgdir}"/usr/share/libalpm/hooks
     }
