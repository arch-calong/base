# Maintainer: Manjaro Linux Team
# Contributor: Levente Polyak <anthraxx[at]archlinux[dot]org>
# Contributor: Eli Schwartz <eschwartz@archlinux.org>

pkgname=base
pkgver=3
pkgrel=3
pkgdesc='Minimal package set to define a basic Manjaro Linux installation'
url='https://manjaro.org'
arch=('any')
license=('GPL')
depends=(
  # very very base
  'filesystem' 'gcc-libs' 'glibc' 'bash'

  # POSIX tools
  'coreutils' 'file' 'findutils' 'gawk' 'grep' 'procps-ng' 'sed' 'tar'

  # standard linux toolset
  'gettext' 'pciutils' 'psmisc' 'shadow' 'util-linux' 'bzip2' 'gzip' 'xz'

  # distro defined requirements
  'licenses' 'pacman' 'archlinux-keyring' 'manjaro-keyring' 'systemd' 'systemd-sysvcompat'

  # networking, ping, etc
  'iputils' 'iproute2'
)
optdepends=(
  'linux: bare metal support'
)

# vim:set sw=2 sts=-1 et:

