# MaviDurak-IO E-posta Şablonu
Bu repository MaviDurak-IO tarfından kullanılan e-posta imza kartı şablonunu içermektedir.

## Nasıl Kullanılır?

[template.html](template.html) dosyası şablonun html kodlarını içerir.Bu kod indirilerek tarayıcı üzerinde çalıştırıldığında veya online html converter sitelerinde çıktısı alındığında imza şablonu ortaya çıkar.Bu şablonu çıktının tümünü seçerek kopyalayınız.Sonrasında ise E-posta hizmet sağlayıcınızın imza böylümüne yapıştırınız.Bazı E-posta hizmet sağlayıcılarının imza ekleme adımları şöyledir:

+ **Gmail**:
  + Gmail'i açın.
  + Sağ üstte, Ayarlar'a tıklayın.
  + "İmza" bölümünde, kutuya yeni imza metninizi girin. İsterseniz kutuya yazdığınız mesajı bir resim ekleyerek veya metin stilini değiştirerek de biçimlendirebilirsiniz.
  + Sayfanın alt tarafında, Değişiklikleri Kaydet'i tıklayın.
  + Detaylı bilgi için [tıklayın](https://support.google.com/mail/answer/8395?co=GENIE.Platform%3DDesktop&hl=tr)

+ **Outlook**
  + Yeni bir e-posta iletisi açın.
  + İleti menüsünde imza ardından imzalar'ı seçin.(Outlook pencerenizin boyutuna bağlı olarak, yeni bir e-posta iletisi ya da yanıt veya iletme ya da iletme gibi bir ileti menüsü ve imza düğmesi iki farklı konumda olabilir.)
  + Düzenlenecek Imzayı seçinaltında Yeni'Yi seçin ve yeni imza iletişim kutusunda imza için bir ad yazın.
  + Imzayı Düzenle'nin altında imzanızı yapıştırın.
  + Varsayılan imzayı seç’in altında, imzanız için aşağıdaki seçenekleri ayarlayın:

E-posta hesabı açılan kutusunda, imzayla ilişkilendirilecek bir e-posta hesabı seçin. Her e-posta hesabı için farklı imzalar kullanabilirsiniz.

İmzanızın varsayılan olarak tüm yeni iletilere eklenmesini istiyorsanız, yeni iletiler açılan kutusunda imzalarınızdan birini seçin. Yeni iletilere otomatik olarak imza eklemek istemezseniz (yok) seçeneğini belirleyin. Bu, yanıtladığınız veya ilettiğiniz iletilere imza eklemez.

İmzanızın yanıtladığınız ve ilettiğiniz iletilerde gösterilmesini istiyorsanız, yanıtlar/iletir açılır listesinde imzalarınızdan birini seçin. İstemiyorsanız, varsayılan (yok) seçeneğini kabul edin.
 + Yeni imzanızı kaydedip iletinize dönmek için Tamam 'ı seçin. İmzayı tüm yeni iletilere uygulamayı seçseniz bile, Outlook yeni imzanızı adım 1 ' de açtığınız iletiye eklemez. İmzayı el ile bu iletiye eklemeniz gerekir. Tüm gelecek iletilerde imza otomatik olarak eklenir. İmzayı el ile eklemek için, ileti menüsünde imza 'yı seçin ve sonra yeni oluşturduğunuz imzayı seçin.
+ Detaylı bilgi için [tıklayın](https://support.microsoft.com/tr-tr/office/%C4%B0letilere-imza-olu%C5%9Fturma-ve-ekleme-8ee5d4f4-68fd-464a-a1c1-0e1c80bb27f2)

## Şablon üzerinde nasıl değişiklik yaparım?
[template.html](template.html) dosyasını herhangi bir kod veya metin editörü ile açın.

**Resim Değiştirme**:
 - Kodda " <!-- Image, chance to src and alt--> " satırda ki src=" " kısmına tırnaklar içerisine fotoğrafınızın linkini yazınız.
 - Kodda " <!-- Image, chance to src and alt--> " satırda ki alt=" " kısmına tırnaklar içerisine isminizi yazınız.Fotoğraf görüntülenemezse isim görüntülenecek.

**İsim Değiştirme**:
 - Kodda " <!-- Full name --> " satırda ki <h1> </h1> içerisine adınızı ve soyadınızı yazınız.

**Ünvan Değiştirme**:
 - Kodda " <!-- Job title --> " satırda ki <h2> </h2> içerisine iş ünvanınızı yazınız.

**E-posta Adresi Değiştirme**:
 - Kodda " <!-- Mail adress, change to href and Email:--> " satırda ki href="mailto: " kısmına 'mailto:' dan sonra e-posta adresinizi  yazınız.
 - Kodda " <!-- Mail adress, chance to src and Email:--> " satırının en sonundaki ' </a> ' dan önce e-posta adresinizi yazınız.

**Telefon Numarası Değiştirme**:
 - Kodda " <!-- Phone number, change to href and Tel:--> " satırda ki href="tel: " kısmına 'tel:' dan sonra telefon numaranızı  yazınız.
 - Kodda " <!-- Phone number, chance to src and Tel:--> " satırının en sonundaki ' </a> ' dan önce telefon numaranızı yazınız.

**Adres Değiştirme**:
 - Kodda " <!-- Adress, change to href and Adres:--> " satırda ki href=" " kısmına harita uygulaması üzerinden alacağınız konumunuzun paylaşım linkini yazınız.
 - Kodda " <!-- Adress, chance to src and Adress:--> " satırının en sonundaki ' </a> ' dan önce açık adresinizi yazınız.
