# Contributor: Nebulosa <nebulosa2007 na yandekse>

pkgname=2gis-spb
pkgver=1
pkgrel=1
pkgdesc="Map of Spb for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Spb-${pkgver}.orig.zip")
md5sums=('7c1ce573487220b10a04a422dbd3d04f')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Spb.dgdat "${startdir}/pkg/opt/2gis/spb.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Spb.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Spb.dglf" || return 1

}
