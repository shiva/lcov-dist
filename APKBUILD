# Contributor: Shiva Velmurugan <shiv@shiv.me>
# Maintainer: Shiva Velmurugan <shiv@shiv.me>
pkgname=lcov
pkgver=1.13
pkgrel=1
pkgdesc="LCOV is an extension to GCOV. It provides a graphical frontend for converage information"
url="https://github.com/linux-test-project/lcov"
arch="all"
license="GPL"
depends="bash perl"
makedepends=""
install=""
subpackages="$pkgname-doc"
source="https://github.com/linux-test-project/${pkgname}/releases/download/v${pkgver}/${pkgname}-${pkgver}.tar.gz"
builddir="$srcdir/$pkgname-$pkgver"

build() {
	cd "$builddir"
	
}

package() {
	cd "$builddir"
	make DESTDIR="$pkgdir" PREFIX="/usr" install || return 1
}

dev() {
	cd "$builddir"

}

md5sums="27c003662136063c8dfe479242eff0b5  lcov-1.13.tar.gz"
sha256sums="44972c878482cc06a05fe78eaa3645cbfcbad6634615c3309858b207965d8a23  lcov-1.13.tar.gz"
sha512sums="54033c0f99dbf7b332fcd70730df8672713ffc36c010809353dfd83a73fcc4f504b6a68e3b5010002d6992da5fa940a7d5f4e03dc3fe6930ab713a7b980dff9e  lcov-1.13.tar.gz"
