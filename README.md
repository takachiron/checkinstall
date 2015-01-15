
## 概要

Fork from [http://checkinstall.izto.org/checkinstall.git](http://checkinstall.izto.org/checkinstall.git)

オリジナルの checkinstall に次の変更を行なっています。

 - デフォルトの除外ディレクトリに /selinux を指定

# インストール

```
git clone https://github.com/takachiron/checkinstall.git
cd checkinstall/
make
make install
mkdir -p ~/rpmbuild/SOURCES
checkinstall --pkgversion=1.6.3
rpm -ivh ~/rpmbuild/RPMS/x86_64/checkinstall-1.6.3-1.x86_64.rpm
```

