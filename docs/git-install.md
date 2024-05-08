## git 2.45.0 ¼³ġ

1. Àx¼º ¶ó귯¸®
```sh
# yum -y install curl-devel
# yum -y install expat-devel
# yum -y install gettext-devel
# yum -y install openssl-devel
# yum -y install zlib-devel
# yum -y install perl-devel
```

2. ´ٿîµå``sh
# wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.45.0.tar.gz
```

3. ¾Ðà®±â``sh
# tar xvfz git-2.45.0.tar.gz
```

4.¼ҽº µð丮 Àµ¿
```sh
  # cd git-2.45.0
```

5. configure build Environment
```sh   
# ./configure --prefix=/usr/local/poscodx/git-2.45.0
```

6. ºô```sh
# make all
```
   
7. ¼³ġ
```sh   
# make install
```

8. ¸µũ
```sh   
# In -s /usr/local/poscodx/git-2.45.0 /usr/local/poscodx/git
# ln -s git-2.45.0/ git
```

9. ¼³d(/etc/profile)
```sh
export PATH=$PATH:/usr/local/poscodx/git/bin
```

9. ȮÀ
```sh
# source /etc/profile  
# git --version
```
