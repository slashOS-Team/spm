# Copyright © 2024 slashOS Team and Contributors
# WIP FILE

pkgname=spm-slashos
pkgver=0.1
pkgrel=1
pkgdesc="next-gen package manager wrapper"
arch=('any')                                                
license=('GPL')                                                                                                                                
depends=('pacman', 'curl', 'python')
source=("https://github.com/slashOS-Team/spm")
url="https://slashos-team.github.io/website/"
source=('spm')
sha256sums=('SKIP'
            'SKIP') # THIS WILL BE REPLACED BY A PROPER SUMS WHEN SPM DEVELOPMENT IS COMPLETED

build() {
       chmod +x spm
}            

package()
       install -Dm644 spm -t "$pkgdir/usr/bin"
}
