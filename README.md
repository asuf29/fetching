# Fetching 
- **Fetch**, tarayıcıdan node.js veya XMLHttpRequests’den HTTP istekleri yapmak için kullanılan, datayı ağ üzerinden eşzamansız almanın kolay ve mantıklı bir yolunu sağlar.
- **Axios**, tarayıcıdan node.js veya XMLHttpRequests’den HTTP istekleri yapmak için kullanılan bir Javascript kütüphanesidir.
### Farklılıklar ve Benzerlikler 
1. Her iki metot da bir API’a HTTP Request atma ve data’yı çekme işlemini gerçekleştirmektedir.
2. Her iki metotta da **“get”** isteği atmak istediğimizde isteğin metodunu yazmamıza gerek yok. Varsayılan olarak her iki metot da “get” isteği atmaktadır.
3. Fetch metodunu kullanırken proje dosyamıza herhangi bir paket yüklememiz gerekmemektedir ve direkt javascript kodlarımızın arasına yazabiliriz.
Fakat axios metodunu kullanmak için npm veya yarn yardımıyla, axios kütüphanesini projemize paket olarak yüklememiz gerekmektedir.
4. Axios’u kullanmak istediğimiz takdirde kütüphaneyi projemize import etmek durumundayız.
