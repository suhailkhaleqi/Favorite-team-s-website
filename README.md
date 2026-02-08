Favorite Team's Website
=======================

Overview
--------
This is a small static website showcasing a favorite sports team. It provides pages for matches, players, highlights, and links. The site is built with plain HTML, CSS, and image assets — no build tools required.

Preview
-------
- Open the site locally by opening `index.html` in your browser.

Included pages
--------------
- `index.html` — Home / landing page
- `Maçlar.html` — Matches (match list / results)
- `oyuncular.html` — Players overview
- `Efsane_oyuncu.html` — Featured player
- `Şompiyonlar.html` — Champions / honors
- `Bağlantı.html` — Links / resources
- `proje.html` — Project / about

Assets
------
- `css/guzellik.css` — Main stylesheet
- `fotograf/` — Images used by the site

Favorite Team's Website
=======================

Overview
--------
This is a small static website showcasing a favorite sports team. It provides pages for matches, players, highlights, and links. The site is built with plain HTML, CSS, and image assets — no build tools required.

Preview
-------
- Open the site locally by opening `index.html` in your browser.

Included pages
--------------
- `index.html` — Home / landing page
- `Maçlar.html` — Matches (match list / results)
- `oyuncular.html` — Players overview
- `Efsane_oyuncu.html` — Featured player
- `Şompiyonlar.html` — Champions / honors
- `Bağlantı.html` — Links / resources
- `proje.html` — Project / about

Assets
------
- `css/guzellik.css` — Main stylesheet
- `fotograf/` — Images used by the site

How to use / develop
---------------------
1. Clone or copy the project folder to your machine.
2. Open `index.html` in a browser to view the site.
3. To edit styles, modify `css/guzellik.css`.
4. To add images, place them in the `fotograf/` folder and reference them in the HTML.

GitHub Pages — Simple Deployment
--------------------------------
You can host this static site on GitHub Pages in a few steps.

1. Create a new repository on GitHub and push this project to it (replace `your-repo` below):

```powershell
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/your-repo.git
git push -u origin main
```

2. In the repository on GitHub, go to `Settings` → `Pages`.
3. Under "Build and deployment" choose `Deploy from a branch`, set branch to `main` and folder to `/ (root)`, then save.
4. After a few minutes the site will be available at `https://<your-username>.github.io/your-repo/`.

Notes and alternatives:
- If you prefer a `gh-pages` branch, use the `gh-pages` action or push the built site to `gh-pages` and select that branch in Pages settings.
- GitHub Pages serves static files — make sure `index.html` is in the repository root (it is by default here).

Notes
-----
- Some filenames contain Turkish characters (e.g. `Şompiyonlar.html`). If you move files between systems, ensure your filesystem and tools handle Unicode filenames correctly.
- This project is static — no server required. For simple local testing you can also serve the folder with a static server, e.g. Python 3:

```powershell
python -m http.server 8000
```

Contributing
------------
Feel free to open issues or submit pull requests adding content, improving styling, or fixing typos.

License & Credits
-----------------
Use this content freely for personal or learning purposes. Credit the original author(s) of any third-party images or media found in `fotograf/`.

Contact
-------
If you want help improving the site (accessibility, responsive layout, or deployment), tell me what you want changed and I can implement it.

Türkçe (Çeviri)
---------------
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

Notlar
-----
- Bazı dosya isimleri Türkçe karakter içerir (ör. `Şompiyonlar.html`). Başka sistemlere taşırken dosya sistemi ve kullandığınız araçların Unicode dosya isimlerini doğru işlediğinden emin olun.
- Proje statiktir — bir sunucu gerektirmez. Yerel test için Python'un basit sunucusunu kullanabilirsiniz:

```powershell
python -m http.server 8000
```
