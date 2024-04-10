# Copyright © 2024 slashOS Team and Contributors

pkgname=spm-slashos
pkgver=0.1
pkgrel=1
pkgdesc="next-gen package manager wrapper"
arch=('any')
license=('GPL')
depends=('pacman' 'curl' 'python' 'flatpak' 'sudo')
source=("https://github.com/slashOS-Team/spm")
url="https://slashos-team.github.io/website/"
sha256sums=('SKIP'
            'SKIP') # THIS WILL BE REPLACED BY A PROPER SUMS WHEN SPM DEVELOPMENT IS COMPLETED

build() {
    chmod +x spm
}

package() {
    install -v -D -t "$pkgdir/usr/bin" spm
}
