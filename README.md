# Engelsiz Nota

**Engelsiz Nota**, NVDA ekran okuyucusu kullanıcıları için geliştirilmiş erişilebilir bir e-katalog asistanıdır.

Eklenti, Engelsiz Nota sistemindeki eserlere daha hızlı, düzenli ve klavye ile erişilebilir biçimde ulaşılmasını sağlamak amacıyla hazırlanmıştır. Kullanıcı; eser adı, alındığı kurum, besteci, eser türü ve çalgı türü gibi ölçütlerle arama yapabilir, eser ayrıntılarını inceleyebilir, ilgili eser sayfasını tarayıcıda açabilir ve eserleri favorilerine ekleyebilir.

## Sürüm

```text
1.1.0
```

## Geliştirici

```text
Mehmet Aykurt
```

İletişim:

```text
m.aykurt38@gmail.com
```

## Genel Amaç

Engelsiz Nota eklentisinin temel amacı, görme engelli müzisyenlerin, müzik öğrencilerinin ve müzikle ilgilenen NVDA kullanıcılarının Engelsiz Nota e-katalog sistemindeki eserlere daha erişilebilir ve düzenli biçimde ulaşabilmesini sağlamaktır.

## Başlıca Özellikler

- Eser adına göre arama yapma.
- Alındığı kurum, besteci, eser türü ve çalgı türü alanlarıyla aramayı daraltma.
- Arama sonuçlarını erişilebilir liste yapısında görüntüleme.
- Eser ayrıntılarını inceleme.
- İlgili eser sayfasını tarayıcıda açma.
- Eser bilgilerini panoya kopyalama.
- Eserleri favorilere ekleme ve favorilerden çıkarma.
- Favori eserleri ayrı pencerede listeleme.
- Yardım dosyasına doğrudan eklenti penceresinden erişme.
- Engelsiz Nota web sayfası üzerinden yorum ve geri bildirim bırakma.
- İleride farklı dillere çevrilebilmesi için hazırlanmış çeviri altyapısı.

## Sürüm 1.1.0 ile Gelen Düzenlemeler

- NVDA Araçlar menüsündeki Engelsiz Nota alt menüsü kaldırıldı.
- Favorilerim, Yardım ve Yorum bırak seçenekleri ana pencereye taşındı.
- Yorum bırak düğmesi, Engelsiz Nota eklentisine ait web sayfasını açacak biçimde düzenlendi.
- Girdi Hareketleri bölümünde yalnızca Engelsiz Nota arama penceresini açan komut bırakıldı.
- Pencere içi kısayollar yalnızca Engelsiz Nota penceresi açıkken çalışacak biçimde korundu.
- Kullanıcıya görünen metinler gözden geçirildi.
- Çeviri altyapısı hazırlandı.
- Yardım dosyası, README.md ve update.json dosyaları 1.1.0 sürümüne göre güncellendi.

## Kullanım

Eklenti varsayılan olarak aşağıdaki kısayol ile açılır:

```text
NVDA+Shift+E
```

Kullanıcı isterse bu kısayolu NVDA menüsünde yer alan **Tercihler > Girdi Hareketleri** bölümünden değiştirebilir.

Girdi Hareketleri bölümünde yalnızca Engelsiz Nota arama penceresini açan komut bulunur. Arama, temizleme, favoriler, yardım, yorum bırakma ve kapatma işlemlerine ait kısayollar yalnızca Engelsiz Nota penceresi açıkken geçerlidir.

## Ana Pencere

Ana pencerede sırasıyla şu bölümler yer alır:

- Eser adı alanı.
- Alındığı kurum seçim kutusu.
- Besteci seçim kutusu.
- Eser türü seçim kutusu.
- Çalgı türü seçim kutusu.
- Ara ve Temizle düğmeleri.
- Arama sonuçları listesi.
- Sayfa alanı.
- Favorilerim, Yardım, Yorum bırak ve Kapat düğmeleri.

## Klavye Kısayolları

Ana pencere açıkken kullanılabilecek temel erişim tuşları:

```text
Alt+E: Eser adı alanına gider.
Alt+M: Alındığı kurum seçim kutusuna gider.
Alt+B: Besteci seçim kutusuna gider.
Alt+T: Eser türü seçim kutusuna gider.
Alt+Ç: Çalgı türü seçim kutusuna gider.
Alt+A: Arama işlemini başlatır.
Alt+Z: Arama alanlarını temizler.
Alt+P: Sayfa alanına gider.
Alt+F: Favorilerim penceresini açar.
Alt+H: Yardım dosyasını açar.
Alt+O: Engelsiz Nota web sayfasını açarak yorum bırakma bölümüne erişim sağlar.
Alt+K: Engelsiz Nota penceresini kapatır.
```

## Favoriler

Kullanıcı, sık erişmek istediği eserleri favorilerine ekleyebilir. Favori kayıtları kullanıcının NVDA yapılandırma klasöründe yerel bir JSON dosyasında saklanır.

Favori dosyası:

```text
engelsiznota_favoriler.json
```

## Gizlilik

Engelsiz Nota eklentisi, arama yapılırken Engelsiz Nota web sitesindeki e-katalog sayfalarına erişir. Bunun dışında favori kayıtlarını, kişisel kullanım verilerini veya kullanıcının bilgisayarındaki herhangi bir dosyayı kendiliğinden bir sunucuya göndermez.

Yorum bırak düğmesi yalnızca kullanıcının isteğiyle Engelsiz Nota eklentisine ait web sayfasını tarayıcıda açar.

## Yorum ve Geri Bildirim

Kullanıcılar, eklentiye ilişkin görüş, öneri ve değerlendirmelerini Engelsiz Nota web sayfası üzerinden iletebilir.

Engelsiz Nota sayfası:

```text
https://mehmetaykurt.com.tr/erisilebilirlik/engelsiz-nota.html
```

## Çeviri Katkıları

Engelsiz Nota Türkçe olarak hazırlanmıştır. Bununla birlikte, ileride farklı dillere çevrilebilmesi için eklenti metinleri çeviriye uygun biçimde düzenlenmiştir.

Temel çeviri dosyaları:

```text
po/engelsiz_nota.pot
locale/en/LC_MESSAGES/nvda.po
```

Çeviri yapılırken:

- `msgid` satırları değiştirilmemelidir.
- Yalnızca `msgstr` alanları çevrilmelidir.
- `&` işareti erişim tuşunu belirtir; hedef dilde uygun harfin önüne taşınabilir.
- `{0}`, `{1}` gibi yer tutucular aynen korunmalıdır.

Tamamlanmış çeviri, derlenmiş `nvda.mo` dosyası olarak ilgili dil klasörüne eklenir.

Örnek:

```text
locale/en/LC_MESSAGES/nvda.mo
```

## Yardım Dosyası

Ayrıntılı kullanım ve bilgilendirme kılavuzu eklenti içinde şu konumda yer alır:

```text
doc/tr/readme.html
```

NVDA içinden Yardım düğmesine basıldığında bu dosya açılır.

## Lisans

Bu eklenti **GNU General Public License v2.0** kapsamında lisanslanmıştır.

## Telif ve Geliştirici Bildirimi

```text
Telif hakkı © 2026 Mehmet Aykurt
```

Engelsiz Nota NVDA eklentisi Mehmet Aykurt tarafından geliştirilmiştir.

Bu eklentinin değiştirilmiş sürümleri dağıtılırken yapılan değişikliklerin açıkça belirtilmesi ve özgün çalışmanın Mehmet Aykurt tarafından geliştirildiği bilgisinin korunması gerekir.
