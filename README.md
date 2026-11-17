# ✂️ Makas — Alıntı ve Deneme Masası

**[→ Canlı Demo](https://gamzeguckiran.com/makas.html)**

Araştırma denemeleri için dijital yazı masası. Alıntılarını ve notlarını getir, istediğin yeri kaynağıyla birlikte kes, kenara diz, aralarına kendi cümlelerini yaz. Çıktıda kaynaklar dipnot ya da parantez içi atıf olur, sona kaynakça eklenir.

Kâğıda döküp makasla kesmenin, masaya dizip aralarına bağlantı cümleleri yazmanın dijital hâli — kâğıt harcamadan, kestiğin her parça kaynağıyla birlikte.

*Lryiu Labs — Experimental Suite'in bir parçasıdır.*

https://github.com/user-attachments/assets/08e0fa94-dd20-401b-92a8-28f3e4cdc055

### 🇬🇧 English

A writing desk for research essays. Bring in your quotes and notes, cut any passage together with its source, lay the pieces out in the margin and write your own sentences between them. In the output, sources become footnotes or in-text citations, with a bibliography at the end. Makas works in Turkish and English: switch with the TR / EN button in the top bar.

*makas: Turkish for “scissors”.*

https://github.com/user-attachments/assets/517f154c-db35-48d1-bf81-cbf161429a1a

---

## ✨ Özellikler

- **Kaynağıyla kesme** — metinde bir yeri seç, ✂ Kes (ya da `Ctrl+K`); parça yazar, eser, çevirmen, yayınevi, yıl ve sayfa bilgisiyle kenara gider
- **Kenar ve yığınlar** — kesikler sağdaki kenarda birikir; Giriş · Gelişme · Sonuç gibi renkli yığınlara ayırabilir, arayıp kaynağa göre süzebilirsin
- **Aralara yazma** — iki parçanın arasında beliren **+ yaz** ile bağlantı cümlelerini yazarsın; parçaları sürükleyip yerini değiştirirsin
- **Alıntı, atıf, düz metin** — alıntı kelimesi kelimesine ve girintili; atıf tırnaksız ama kaynaklı; düz metin kaynaksız
- **Cümle içine alıntı** — yazında bir yere tıkla, kenardaki parçada **Cümleye ekle** de; tırnak içinde o noktaya girer, kaynağı altında görünür
- **Kaynak kütüphanesi** — bir kaynağı bir kez düzeltirsin, ona bağlı bütün parçalarda ve çıktıda düzelir
- **Okuma modu** — metni okurun göreceği hâliyle görürsün
- **Saklanan hâller** — bir taslağı adıyla saklayıp sonra ona dönebilirsin (en fazla 20)
- **Kelime sayacı ve hedef** — yalnızca senin yazdıkların ve atıfların sayılır
- **Dosya yükleme** — `.txt`, `.md`, `.docx` ve seçilebilir metni olan `.pdf`
- **Çıktılar** — Word (`.docx`, gerçek Word dipnotlarıyla), yazdırılabilir sayfa (`.html`), düz metin (`.txt`), Markdown (`.md`) ve tam yedek için proje dosyası (`.json`)
- **Türkçe / İngilizce** — arayüz, kılavuz ve çıktılar seçilen dile göre (İngilizcede *trans.*, *p.*, *Bibliography*); ilk açılışta tarayıcının diline göre seçilir, sonra hatırlanır
- **Karşılama ekranı** — ilk ziyarette tanıtım videosuyla kısa bir karşılama
- **Gece modu**, geri al / yinele

## 🔒 Metinlerin Nerede Saklanıyor?

Makas bir sunucu ya da veritabanı kullanmaz. Çalışmaların **yalnızca kendi tarayıcında**, `localStorage` üzerinde durur.

- ✅ Metinlerin sana özel — kimseye gönderilmez
- ✅ Kayıt / giriş gerekmez
- ⚠️ Tarayıcı verilerini temizlersen çalışmaların **silinir**
- ⚠️ Başka bir cihaz ya da tarayıcıdan girersen çalışmalarını **görmezsin**

**Öneri:** Önemli bir çalışmayı ara ara **İndir › Proje dosyası (.json)** ile yedekle. Başka bir bilgisayarda Makas'ı açıp **Çalışmalarım › Proje dosyası aç** ile kaldığın yerden sürersin.

## 🚀 Kullanım

**Online:** Kurulum gerekmez — [canlı demo](https://gamzeguckiran.com/makas.html) adresine git, alıntılarını yapıştır, **Parçalara ayır** de.

**Kendi bilgisayarında:**
1. Bu repoyu indir ya da klonla
2. `makas.html` dosyasını herhangi bir modern tarayıcıda aç (çift tıklamak yeterli)
3. İnternet bağlantısı yalnızca fontlar, Word çıktısı için JSZip ve PDF okumak için PDF.js'i yüklemek üzere gerekir

### Kısayollar

- `Ctrl+K` — seçili yeri kes
- `Ctrl+Z` — geri al
- `Ctrl+Shift+Z` — yinele
- `Esc` — vazgeç

## 🛠️ Teknoloji

Tek dosyada vanilla HTML / CSS / JavaScript. Harici framework ya da build süreci yok.

- [JSZip](https://stuk.github.io/jszip/) — `.docx` okuma ve Word çıktısı
- [PDF.js](https://mozilla.github.io/pdf.js/) — `.pdf` dosyalarından metin okuma (yalnızca PDF yüklendiğinde yüklenir)
- [Literata](https://fonts.google.com/specimen/Literata) ve [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) — Google Fonts

## 📄 Lisans

© 2026 Lryiu Labs — Tüm hakları saklıdır.
