# Vinyl Echo | Web E-Ticaret Projesi

Vinyl Echo, kullanıcıların şarkıları keşfedebileceği, favori plaklarını sepete ekleyebileceği ve hesap oluşturup giriş yapabileceği bir müzik ve e-ticaret sitesidir. Kullanıcılar, siteyi karanlık ve aydınlık modda kullanabilir ve istedikleri şarkıları sepetlerine ekleyerek alışveriş yapabilirler.

## Kullanılan Teknolojiler

- **HTML5**: Sayfa yapısını oluşturmak için kullanıldı.
- **CSS3**: Sayfa tasarımı ve stil düzenlemeleri için kullanıldı.
- **JavaScript**: Dinamik işlemler (karanlık/aydınlık mod, sepet işlemleri) için kullanıldı.
- **Font Awesome**: Sayfa içindeki ikonları eklemek için kullanıldı.
- **LocalStorage**: Kullanıcının temasını ve sepet bilgilerini saklamak için kullanıldı.

## Özellikler

**Navigasyon Çubuğu**

- Ana Sayfa, Türkçe Şarkılar ve Yabancı Şarkılar bölümlerine bağlantılar içerir.

- Karanlık ve aydınlık modlar arasında geçiş yapabilme imkanı sunar.

- "Vinyl Echo" logosu bulunur.

**Şarkı Listesi Bölümü**

- Kullanıcıların şarkıları görüntüleyebileceği alandır.

- Sepete ekle butonu ile şarkılar sepete eklenebilir.

- Şarkı ekleme işlemi başarılı olduğunda kullanıcıya bir uyarı mesajı gösterilir.

**Sepet Bölümü**

- Sepete eklenen şarkılar burada görüntülenir.

- Şarkılar listeden çıkarılabilir.

- Toplam tutar hesaplanarak gösterilir.

**Kullanıcı Girişi**

- Kullanıcılar giriş yaparak alışveriş işlemlerini gerçekleştirebilir.

- E-posta ve şifre giriş alanları bulunur.

- Alternatif olarak Google ve telefon ile giriş seçenekleri mevcuttur.

**Kullanıcı Kaydı**

- Kullanıcılar hesap oluşturabilir.

- Ad, Soyad, E-posta, şifre ve şifre onaylama alanları bulunur.

- Modern ve kullanıcı dostu bir tasarıma sahiptir.

Nasıl Kullanılır?

1. Kullanıcılar ana sayfada şarkıları görüntüleyebilir.

2. Şarkılar "Sepete Ekle" butonu ile sepete eklenebilir.

3. Sepet sayfasında eklenen ürünler listelenir ve silinebilir.

4. Kullanıcılar hesap oluşturabilir veya giriş yapabilir.

5. Karanlık ve aydınlık modlar arasında geçiş yapılabilir.

## Proje İçeriği

Proje aşağıdaki dosyaları içerir:

**HTML Dosyaları**

 - `index.html`: Ana sayfa, kullanıcıların ürünleri sepete eklemesine olanak tanır.

- `sepet.html`: Sepet sayfası, sepete eklenen ürünleri görüntüler.

- `kayıt-ol.html`: Kullanıcıların sisteme kayıt olmalarını sağlayan sayfa.

- `giris-yap.html`: Kullanıcıların sisteme giriş yapmalarını sağlayan sayfa.

**CSS Dosyası**:

- `style.css`: Sayfanın stilini tanımlar, tasarım ve layout için kullanılır.

**JavaScript Dosyası**:

- `script.js`: Sepet işlemleri (ürün ekleme, çıkarma) ve kullanıcı etkileşimlerini yönetir. Veriler localStorage'a kaydedilir, böylece sayfa yenilendiğinde kaybolmaz.

Görseller Klasörü:

`images/`: Sayfa içerisinde kullanılan ikonlar ve albüm kapaklarını içerir.

## Ekran Görüntüleri

**Ana Sayfa - Aydınlık Tema**

![ana-sayfa-aydınlık sc1](https://github.com/user-attachments/assets/1b063336-0af4-4dfa-8bb0-0cc77dc82b65)

**Ana Sayfa - Karanlık Tema**

![ana-sayfa-karanlık sc2](https://github.com/user-attachments/assets/d60724b6-9c34-42b1-9f4a-c5ca548b276c)
 
**Footer - Aydınlık Tema**

![ana-sayfa-aydınlık sc2](https://github.com/user-attachments/assets/0ad55bff-38bc-48dc-83ce-911b92aefcc4)

**Hakkımızda Sayfası**

![hakkımızda](https://github.com/user-attachments/assets/5e46bf97-c103-4843-931a-688679bdce20)

**Giriş Sayfası**

![giris-yap](https://github.com/user-attachments/assets/60ca80e4-bde1-4c76-a0d3-76fcf999cfb0)

**Kayıt Sayfası**

![kayıt-ol](https://github.com/user-attachments/assets/745c7b1f-cabd-4910-b14e-b64e5a4a28af)

**Türkçe Şarkılar**

![turkce-sarkılar](https://github.com/user-attachments/assets/18ceb198-39ec-4173-a1f9-24905e2d640d)

**Türkçe Şarkılar V2**

![turkce-sarkılar sc2](https://github.com/user-attachments/assets/4dddbd6a-2fd9-43ac-87ad-0a0dc9cae784)

**Yabancı Şarkılar**

![yabanci-sarkilar sc1](https://github.com/user-attachments/assets/7e35e194-fdd4-41c7-adf4-0e444080657c)

**Yabancı Şarkılar V2**

![yabanci-sarkilar sc2](https://github.com/user-attachments/assets/194a16e8-fa56-4e88-a7a7-fa79e24721c4)

## Dosya Yapısı

```
├── index.html          
├── sepet.html  
├── kayıtol.html          
├── girisyap.html        
├── style.css              
├── script.js    
└── images/              
    ├── social-icons/ 
    │   ├── google.png
    │   ├── log-in.png
    │   ├── main-bg.jpeg
    └── turkce-sarki-isimleri/
        └── baris-manco-hal-hal.jpg
        └── ....
    └── yabanci-sarki-isimleri/
        └── 21-savage-a-lot.jpeg
        └── ....
````


## Kullanım Kılavuzu

### 1. Tema Değiştirme (Karanlık / Aydınlık Mod)
Kullanıcılar siteyi karanlık ve aydınlık modda kullanabilir.

- 🌙 **Karanlık Mod** için ay düğmesine basın.
- ☀️ **Aydınlık Mod** için güneş düğmesine basın.

### 2. Kayıt Olma ve Giriş Yapma

- Kullanıcılar **kayıt ol** sayfasından hesap oluşturabilir.
- **Giriş yap** sayfası ile giriş yapabilirler.
- Kayıt işlemi ve giriş yapma kısmı henüz arka planda bir veritabanına bağlı değildir.

### 3. Sepete Ürün Ekleme

- Kullanıcılar şarkıları sepete ekleyebilir.
- **LocalStorage** sayesinde sepet bilgileri kaydedilir ve sayfa kapansa bile korunur.
- "Listeden Çıkar" butonu ile sepetteki ürünler silinebilir.

## Nasıl Kullanılır?

### Adım 1: Projeyi klonlayın veya Proje Dosyasını İndirin:

```sh
git clone <repo-url>
````

### Adım 2: Tarayıcıda Açın
Projenin HTML dosyalarını, herhangi bir tarayıcıda açarak kullanabilirsiniz. Örneğin:
- `index.html` dosyasını açarak ana sayfayı görüntüleyebilirsiniz.
- `sepet.html` dosyasına giderek sepete eklenen ürünleri görebilirsiniz.

## Gelecek Güncellemeler
- Kullanıcı kayıt ve giriş işlemleri için **gerçek bir kimlik doğrulama sistemi** (Firebase veya JWT tabanlı).
- **Ödeme entegrasyonu** (Stripe veya PayPal ile ödeme işlemleri).
- Kullanıcıların satın alma geçmişini görüntüleyebileceği bir **profil sayfası**.
- **Gelişmiş filtreleme ve arama özellikleri** ile müzikleri daha hızlı bulma imkanı.

## Lisans

Bu proje **MIT Lisansı** ile lisanslanmıştır. Lisans bilgilerini [LICENSE](LICENSE) dosyasından görebilirsiniz.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

1. Bu projeyi kendi GitHub hesabınıza fork'layın.
2. Değişikliklerinizi yapın ve pull request gönderin.


