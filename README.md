# AstraStrike v2 - Neon Core Defense

AstraStrike, renk eslestirme odakli hizli bir 2D tarayici oyunudur. Oyuncu merkezdeki core'u savunur, dogru renk mermilerle dusmanlari yok eder ve seviyeleri ilerletir.

## Proje Notu (Gelistirme Sureci)
Bu proje, **hayal edilen oyun tasarimi ve teknik bilgiler temel alinarak** gelistirilmistir.
Eksik kalinan kisimlarda ve denge/oynanabilirlik iyilestirmelerinde **Codex'e basvurularak v2 surumu tamamlanmistir**.

Kisaca:
- Fikir, yon ve oyun hedefleri insan tarafindan belirlendi.
- Teknik uygulama sirasinda zorlanilan bolumler Codex destegiyle cozuldu.
- Sonuc: ana surum korunarak daha oynanabilir bir `v2` cikarildi.

## Neden v2?
Ilk surumde ana mekanik calisiyor olsa da oynanis adaleti ve geri bildirim tarafinda buyuk bosluklar vardi:
- Kaybetme kosulu net degildi.
- Renk atis sistemi fazla rastgeleydi.
- Zorluk artisi fazla sertti.
- Kontroller ve oyun ici yonlendirme yetersizdi.

v2 ile hedef, projeyi asiri karmasiklastirmadan daha adil ve anlasilir bir deneyim olusturmaktir.

## v2 ile Gelen Iyilestirmeler
- `HP` sistemi eklendi (`coreHP = 5`).
- Net `Game Over` akisi eklendi.
- `Space` ile baslat / yeniden baslat akisi eklendi.
- Atis icin kisa cooldown eklendi (spam azaltildi).
- Seviye gecislerinde kisa spawn molasi eklendi.
- Zorluk artis egisi yumusatildi (`spawnRate`, `enemySpeed`).
- HUD gelistirildi (HP + secili renk + kontrol hatirlatmasi).
- Yanlis renk atisinda anlik geri bildirim mesaji eklendi.

## Kullanilan Teknolojiler
- HTML5
- CSS3
- Vanilla JavaScript
- Canvas 2D API

Ek framework veya oyun motoru kullanilmadi.

## Calistirma
1. Proje klasorune girin.
2. `astra_v2.html` dosyasini tarayicida acin.
3. Oyunu baslatmak icin `Space` tusuna basin.

## Kontroller
- Nisan alma: Mouse hareketi
- Ates: Sol tik
- Renk secimi: `Q/W/E/R` veya `1/2/3/4`
- Baslat / yeniden baslat: `Space`

## Oyun Dongusu
1. Dusmanlar merkeze dogru ilerler.
2. Oyuncu dogru renkte mermi ile dusmani vurursa puan kazanir.
3. Dusman core'a ulasirsa HP azalir.
4. HP sifirlaninca oyun biter.
5. Puan hedefi gecilince seviye atlanir.

## Gelistirme Vizyonu
Bu proje, tek kisilik bir gelistirme surecinde tasarlanmis; pratikte zorlanilan yerlerde Codex'ten teknik destek alinmis bir calismadir.
Amaç, "tek basina sifirdan yazilmis" gorunumu vermek degil; dogru araclari kullanarak fikri calisan ve gelistirilebilir bir urune donusturmektir.

## Sonraki Adim Fikirleri
- Mobil dokunmatik kontrol
- Combo / zincir skor sistemi
- Basit ses efektleri
- Wave tabanli spawn yapisi
- Daha detayli denge ayarlari

---
Hazirlayan: Proje sahibi + Codex destekli gelistirme sureci
