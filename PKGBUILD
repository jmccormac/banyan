pkgname=python2-banyan
_pkgname=banyan
pkgver=0.1.5
pkgrel=1
pkgdesc='Library providing high performance trees for Python.'
arch=(any)
makedepends=(python2-setuptools)
source=(git+https://github.com/jmccormac/banyan.git)
md5sums=('SKIP')

build() {
  cd ${srcdir}/${_pkgname}
  python2 setup.py build
}

package() {
  cd ${srcdir}/${_pkgname}
  python2 setup.py install --root=${pkgdir}
}
