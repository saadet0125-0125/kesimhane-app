# Kesimhane – Çalışan İlk Sürüm

FireVibe HTML dışa aktarımının üzerine hazırlanmış statik/Vercel uyumlu ilk sürümdür.

## Özellikler
- Mevcut FireVibe tasarımı korunur.
- Standart/Faturalı kesim kaydı tarayıcıda saklanır.
- Kasap kesimi kaydı çalışır.
- Kasap + kesimi yapan kişi + hayvan cinsi + adet + toplam kilo tutulur.
- Kesim ücreti cins ve adet üzerinden otomatik hesaplanır.
- Kayıtlar `localStorage` içinde tutulur.
- Vercel/GitHub Pages gibi statik yayınlarda çalışır.

## Önemli
Bu ilk sürümde gerçek ortak veritabanı yoktur. Veriler yalnızca uygulamayı kullanan cihaz/tarayıcıda saklanır. Çoklu kullanıcı, giriş sistemi ve ortak veritabanı için sonraki aşamada Supabase/Firebase gibi bir backend eklenmelidir.

## Kesim ücretleri
İlk sürümde prototipte görünen ücretlerden hareketle örnek değerler kullanılmıştır:
- Tosun: 650 TL
- İnek: 500 TL
- Düve: 600 TL
- Kuzu: 150 TL
- Diğer küçükbaş: 150 TL

Bunlar gerçek işletme tarifesi değildir; uygulamada gerçek ücretleri belirledikten sonra sabitleyeceğiz.
