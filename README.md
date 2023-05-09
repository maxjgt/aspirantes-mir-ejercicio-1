Max García@MAX MINGW64 ~
$ git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=G:/Programas/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Max
user.email=max.j.garcia.t@outlook.com

Max García@MAX MINGW64 ~
$ ls
'3D Objects'/
 AMD_Chipset_IODrivers.log
 AppData/
 Apple/
'Application Data'/
'Configuración local'@
 Contacts/
 Cookies@
'Creative Cloud Files'/
'Datos de programa'@
 Desktop/
 Device_ID.log
 Documents/
 Documents-assets/
 Downloads/
'Entorno de red'@
 Favorites/
 Games/
 Impresoras@
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{6b076577-6393-11ed-9ad9-18c04d3152f0}.TM.blf
 NTUSER.DAT{6b076577-6393-11ed-9ad9-18c04d3152f0}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{6b076577-6393-11ed-9ad9-18c04d3152f0}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 PaceKeyChain
 Pictures/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

Max García@MAX MINGW64 ~
$ cd /c/users/Desktop
bash: cd: /c/users/Desktop: No such file or directory

Max García@MAX MINGW64 ~
$ cd /c/users/usuarios/Desktop
bash: cd: /c/users/usuarios/Desktop: No such file or directory

Max García@MAX MINGW64 ~
$ cd /c/users/usuario/Desktop

Max García@MAX MINGW64 /c/users/usuario/Desktop
$ cd /c/users/usuario/Desktop/ejercicios

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios
$ git init
Initialized empty Git repository in C:/Users/usuario/Desktop/ejercicios/.git/

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios (master)
$ ls
README.md  ejercicio1/

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios (master)
$ git add .

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios (master)
$ git commit -m 'Version Inicial'
[master (root-commit) 666873d] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios (master)
$ gt log -p
bash: gt: command not found

Max García@MAX MINGW64 /c/users/usuario/Desktop/ejercicios (master)
$ git log -p
commit 666873dd153984873e72a2c8e9ea7a9bca7ce2c3 (HEAD -> master)
Author: Max <max.j.garcia.t@outlook.com>
Date:   Mon May 8 19:00:49 2023 -0500

    Version Inicial

diff --git a/README.md b/README.md
new file mode 100644
index 0000000..e69de29
