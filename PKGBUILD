# Maintainer:  trashstar <trash@ps3zone.org>

pkgname=etm_qt
pkgver=2.3.27
pkgrel=2
pkgdesc="Manage events and tasks using simple text files."
arch=('any')
url="http://people.duke.edu/~dgraham/etmqt/"
license=('GPL')
depends=('python-pyqt5' 'python-dateutil' 'python-yaml' 'libxkbcommon-x11')
optdepends=('python-icalendar: iCalendar support')
conflicts=('etm_qt-qt4')
makedepends=('python-setuptools')
source=("http://people.duke.edu/~dgraham/etmqt/etm_qt-$pkgver.tar.gz")
md5sums=('09d48fc81850ce77b9fe73540d3f664d')

package() {
    cd "$srcdir/$pkgname-$pkgver"
    python setup.py install --prefix=/usr --root=$pkgdir 
}
