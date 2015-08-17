# Contributor: Vinicius de Avila <vinicius.avila.jorge@gmail.com>
# Update Based on Geoff Teale's PKGBUILD. To support only python3
pkgname=python3-odfpy
pkgver=0.9.4
pkgrel=2
pkgdesc="A complete API for OpenDocument in Python. Python 3.x support"
arch=('i686' 'x86_64')
url="http://opendocumentfellowship.com/projects/odfpy"
license=('GPL')
depends=('python')
conflicts=('odfpy' 'python-odfpy' 'python2-odfpy' 'python-all-odfpy')
source=("http://pypi.python.org/packages/source/o/odfpy/odfpy-$pkgver.tar.gz")
md5sums=('f5adf8bb439e0c4624d2ef11c69a985b')

build() {
      cd "$srcdir/odfpy-${pkgver}"
      python3 setup.py install --root=${pkgdir}
}
