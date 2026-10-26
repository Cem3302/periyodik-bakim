# PEMBA · Periyodik Bakım Yönetim Sistemi

Excel'den içe aktarılmış **219 araçlık filo** için periyodik bakım takip uygulaması.
Kurulum gerektirmez — tek dosya, tarayıcıda çalışır.

**Canlı:** https://cem3302.github.io/periyodik-bakim/

## Özellikler

- **4 kategori / 219 araç**: HEAVY EQUIPMENT (250 saat), HEAVY TRUCKS (5.000 km), LIGHT VEHICLE (10.000 km), LIGHT EQUIPMENT (250 saat)
- **Panel**: KPI kartları, kategori bazlı durum barları, düzenlenebilir periyotlar, "En acil 15 bakım" listesi
- **Filo tablosu**: kod arama, kategori/durum filtreleri, sıralama, bakım kaydı ve sayaç güncelleme
- **Otomatik + elle sonraki bakım**: hesap otomatik yapılır; gerekirse elle değer girilir (✎ işaretiyle gösterilir)
- **Makine ekleme / silme**: yeni kategoriyle birlikte, tekil kod doğrulaması
- **Bakım geçmişi**: tüm bakım ve sayaç kayıtları aranabilir
- **TR / EN arayüz**: tek tıkla dil değiştirme, tercih hatırlanır
- **Veri**: localStorage kalıcılığı, CSV dışa aktarım (Excel uyumlu), JSON yedek/geri yükleme, Excel'e sıfırlama

## Kullanım

`index.html` dosyasını herhangi bir tarayıcıda açmanız yeterlidir. Veriler tarayıcının localStorage'ında tutulur; "⬇ Yedek" ile JSON yedeği alıp başka makineye taşıyabilirsiniz.

## Kaynak veri

Veriler `PEMBA MACHINES.xlsx` dosyasındaki 4 sayfadan çıkarılmıştır.
