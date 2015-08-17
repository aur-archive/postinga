# PKGBUILD: Ignacio Losiggio < http://taringa.net/Kingreil >
# Creator: MukenioArg < http://taringa.net/MukenioArg >

pkgname=postinga
pkgver=1.42
pkgrel=0
pkgdesc="Creador de posts para Taringa!"
arch=('i686' 'x86_64')
url="http://taringa.net/comunidades/comunidadpostinga/"
license=('GPL')
depends=('java-runtime')
source=("http://dl.dropbox.com/u/155504/postinga.jar"
'postinga.desktop'
'postinga.png'
'postinga'
)

md5sums=('ef25a8d3e881d91bdd07637a03e4a58d'
         'a36053ea38fef3daf4c580b9903eb3a2'
         '82f99ff56586e8f6b71f2488b6640bc1'
         'cbc0b8deab09dab344a1ab8ca6f29dcc')



 
build(){
  # Install jar
  install -Dm644 "$srcdir/postinga.jar" "$pkgdir/usr/share/postinga/postinga.jar"
  
  
  # Install icon
  install -Dm644 postinga.png "$pkgdir/usr/share/pixmaps/postinga.png"
  
  # Install .desktop file
  install -Dm644 postinga.desktop "$pkgdir/usr/share/applications/postinga.desktop"
  
  # Install run script
  install -Dm755 postinga  "$pkgdir/usr/bin/postinga"
}

