pkgname=msysVim
pkgver=1.0
pkgrel=1
pkgdesc='Helpers to integrate vim into the Windows shell'
arch=('x86_64' 'i686')
url='https://github.com/AeliusSaionji/msysVim'
optdepends=('dash: launch vim faster')
depends=('vim')
source=('msysVim' 'msysVim.bat' 'msysVim.reg')
sha256sums=('496bdcb19988b066835a4cc96745e06bd82ae74823f9a735a90ed3ef7340a8e7'
            '6e69e0a3658853f13fff3b1e3e3e814a43938ab91da2e115b004c28973c1cf89'
            '80ea2209dfa6f6d9b60b4690845e3aa74a362d2d3a8be603f10a85ca04a17fa2')

package() {
  cd ${srcdir}

  install -D -m0644 'msysVim' "${pkgdir}/usr/bin/msysVim"
  install -D -m0644 'msysVim.bat' "${pkgdir}/usr/share/msysVim/msysVim.bat"
  install -D -m0644 'msysVim.reg' "${pkgdir}/usr/share/msysVim/msysVim.reg"
}
