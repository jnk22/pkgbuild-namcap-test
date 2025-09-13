# Maintainer: Name <Email>
pkgname=test-pkg
pkgver=0.0.1
pkgrel=1
pkgdesc="Test."
arch=('any')
url="https://github.com/jnk22/pkgbuild-namcap-test"
license=('MIT')
depends=()
# Intentionally fail namcap checks to show error output in GitHub actions log:
# makedepends=('git')  # <-- this is required!
source=("$pkgname-$pkgver::git+$url.git#tag=v$pkgver")
sha256sums=('SKIP')

package() {
  echo "This is just a test"
}
