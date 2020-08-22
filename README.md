# Profiles REST API
Kullanıcı profillerini yönetmek için temel işlevsellik sağlayan REST API.

  - Kullanıcı Ekleme, Silme ve Değiştirme
  - Kullanıcı Profili Görme
  - Kullanıcı girişi yapma.(Token)

# Kurulumlar

  - [VirtualBox](virtualbox.org/wiki/Downloads)
  - [Vagrant](https://www.vagrantup.com/downloads) 

# Proje İndirme
```sh
$ git clone https://github.com/Andronovo-bit/Rest-Api-for-Profiles.git
```

# Ayarlamalar
  - Proje dosyasını açın. ``` $ cd Rest-Api-for-Profiles\ ```
  
  - Vagrant ile sanal bilgisayarı hazırlayın.  ``` $ vagrant up  ```
  
  - Vagrant ile sanal bilgisayara bağlanın. ``` $ vagrant ssh  ```
  
  - Daha sonra python sanal ortamı oluşturun. ``` $ mkvirtualenv profiles_api --python=python3```
  
  - Python sanal ortamı devre dışı bırakmak için ``` $ deactivate```
  
  - Python sanal ortamını aktif etmek için ``` $ workon profiles-api ```
  
  - Gerekli kütüphaneleri kurun.  ```  $ pip install -r requirements.txt ```
# Çalıştırma

```sh
$ cd /vagrant/src/profiles_project
```
- Super user oluşturma.
```
$ python manage.py createsuperuser
```

```sh
$ python manage.py runserver 0.0.0.0:8080
```
- Tarayıcıya 127.0.0.1:8080/api yazarak projeyi açabilirsiniz.

# Görünüş

![alt text](https://github.com/Andronovo-bit/Rest-Api-for-Profiles/blob/master/api.jpg)
