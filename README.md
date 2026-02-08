Favori Takımın Web Sitesi
=========================
Genel Bakış
-----------
Bu, favori bir spor takımını tanıtan küçük, statik bir web sitesidir. Maçlar, oyuncular, öne çıkanlar ve bağlantılar için sayfalar içerir. Site yalnızca HTML, CSS ve resim varlıkları kullanılarak hazırlanmıştır — herhangi bir derleme aracı gerekmez.

Önizleme
--------
- Siteyi yerel olarak görüntülemek için tarayıcınızda `index.html` dosyasını açın.

Dahil Edilen Sayfalar
--------------------
- `index.html` — Ana sayfa
- `Maçlar.html` — Maçlar (maç listesi / sonuçlar)
- `oyuncular.html` — Oyuncular listesi
- `Efsane_oyuncu.html` — Öne çıkan oyuncu
- `Şompiyonlar.html` — Şampiyonluklar / başarılar
- `Bağlantı.html` — Bağlantılar / kaynaklar
- `proje.html` — Proje / hakkında

Varlıklar
--------
- `css/guzellik.css` — Ana stil dosyası
- `fotograf/` — Sitede kullanılan görseller

Kullanım / Geliştirme
--------------------
1. Proje klasörünü bilgisayarınıza kopyalayın.
2. Siteyi görüntülemek için `index.html` dosyasını tarayıcıda açın.
3. Stil üzerinde değişiklik yapmak için `css/guzellik.css` dosyasını düzenleyin.
4. Görsel eklemek için `fotograf/` klasörüne dosya koyun ve HTML içinde referans verin.

GitHub Pages — Basit Dağıtım
----------------------------
Bu statik siteyi GitHub Pages'te birkaç adımda barındırabilirsiniz.

1. GitHub'da yeni bir depo oluşturun ve bu projeyi ona gönderin (aşağıdaki `your-repo` değiştirin):

```powershell
git init
git add .
git commit -m "İlk site"
git branch -M main
git remote add origin https://github.com/<your-username>/your-repo.git
git push -u origin main
```

2. GitHub'da depoyu açın, `Settings` → `Pages` kısmına gidin.
3. "Build and deployment" altında `Deploy from a branch` seçin, branch olarak `main` ve klasör olarak `/ (root)` seçip kaydedin.
4. Birkaç dakika sonra site `https://<your-username>.github.io/your-repo/` adresinde açık olacaktır.

Notlar ve alternatifler:
- `gh-pages` branch'ini tercih ederseniz, `gh-pages` action kullanabilir veya `gh-pages` branch'ine site gönderdikten sonra Pages ayarlarında bu branch'i seçebilirsiniz.
- GitHub Pages statik dosyaları sunar — `index.html` dosyasının depo kökünde olması gerekir (varsayılan olarak buradadır).

Notlar
-----
- Bazı dosya isimleri Türkçe karakter içerir (ör. `Şompiyonlar.html`). Başka sistemlere taşırken dosya sistemi ve kullandığınız araçların Unicode dosya isimlerini doğru işlediğinden emin olun.
- Proje statiktir — bir sunucu gerektirmez. Yerel test için Python'un basit sunucusunu kullanabilirsiniz:

```powershell
python -m http.server 8000
```

Katkı Yapma
-----------
İçerik ekleyen, stil iyileştiren veya yazım hatalarını düzelten issues ya da pull request'ler açmaktan çekinmeyin.

Lisans & Krediler
-----------------
Bu içeriği personal veya öğrenme amaçları için özgürce kullanabilirsiniz. `fotograf/` klasöründeki üçüncü taraf görseller ve medya için orijinal yazar(lar)ı kredi verin.

İletişim
--------
Siteyi geliştirmek istiyorsanız (erişilebilirlik, duyarlı tasarım veya dağıtım), neyi değiştirmek istediğinizi bana söyleyin ve bunu uygulayabilirim.
