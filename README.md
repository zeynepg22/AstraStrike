# AstraStrike v2 - Neon Core Defense

AstraStrike, renk eşleştirme odaklı 2D tarayıcı oyunudur. Oyuncu merkezdeki core'u savunur, doğru renk mermilerle düşmanları yok eder ve seviyeleri ilerletir.

## Proje Notu (Geliştirme Süreci)
Bu proje, **hayal edilen oyun tasarımı ve teknik bilgiler temel alınarak** geliştirilmiştir.
Eksik kalınan kısımlarda ve denge/oynanabilirlik iyileştirmelerinde **Codex'e başvurularak v2 sürümü tamamlanmıştır**.

Kısaca:
- Teknik uygulama sırasında zorlanılan bölümler Codex desteğiyle çözüldü.
- Sonuç: Ana sürüm korunarak daha oynanabilir bir `v2` çıkarıldı.

## Neden v2?
İlk sürümde ana mekanik çalışıyor olsa da oynanış adaleti ve geri bildirim tarafında boşluklar vardı:
- Kaybetme koşulu net değildi.
- Renk atış sistemi fazla rastgeleydi.
- Zorluk artışı fazla sertti.
- Kontroller ve oyun içi yönlendirme yetersizdi.

v2 ile hedef, projeyi çok karmaşıklaştırmadan daha adil ve anlaşılır bir deneyim oluşturmaktır.

## v2 ile Gelen İyileştirmeler
- `HP` sistemi eklendi (`coreHP = 5`).
- Net `Game Over` akışı eklendi.
- `Space` ile başlat / yeniden başlat akışı eklendi.
- Atış için kısa cooldown eklendi (spam azaltıldı).
- Seviye geçişlerinde kısa spawn molası eklendi.
- Zorluk artış eğisi yumuşatıldı (`spawnRate`, `enemySpeed`).
- HUD geliştirildi (HP + seçili renk + kontrol hatırlatması).
- Yanlış renk atışında anlık geri bildirim mesajı eklendi.

## Kullanılan Teknolojiler
- HTML5
- CSS3
- Vanilla JavaScript
- Canvas 2D API

Ek framework veya oyun motoru kullanılmadı.

## Kontroller
- Nişan alma: Mouse hareketi
- Ateş: Sol tık
- Renk seçimi: `Q/W/E/R` veya `1/2/3/4`
- Başlat / yeniden başlat: `Space`

## Oyun Döngüsü
1. Düşmanlar merkeze doğru ilerler.
2. Oyuncu doğru renkte mermi ile düşmanı vurursa puan kazanır.
3. Düşman core'a ulaşırsa HP azalır.
4. HP sıfırlanınca oyun biter.
5. Puan hedefi geçilince seviye atlanır.

## Geliştirme Vizyonu
Bu proje, tek kişilik bir geliştirme sürecinde tasarlanmış; pratikte zorlanılan yerlerde Codex'ten teknik destek alınmış bir çalışmadır. Oluşumu ve son haline gelişi süreç içermektedir.
Amaç, "tek başına sıfırdan yazılmış" görünümü vermek değil; doğru araçları doğru şekilde kullanarak fikri çalışan ve geliştirilebilir bir ürüne dönüştürmektir.

## Sonraki Adım Fikirleri
- Mobil dokunmatik kontrol
- Combo / zincir skor sistemi
- Basit ses efektleri
- Wave tabanlı spawn yapısı
- Daha detaylı denge ayarları

