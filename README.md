# Karaciğer Fibroz ve Steatoz Hesaplayıcı

Serum ve elastografi temelli invaziv olmayan testler (FIB-4, APRI, NFS, BARD, FIB-5, FIB-8, SAFE, MAF-5, LSM, CAP, SSM, FAST, Agile 3+, Agile 4, ELF, HSI, FLI), FIB-6/9/11/12 için dış değer girişi, kardiyometabolik risk faktörü ve metabolik sendrom sayımı, MASLD/MetALD/ALD sınıflaması, antropometrik indeksler ve Baveno VII portal hipertansiyon değerlendirmesi.

Tek dosyalık statik sayfadır (`index.html`); sunucu gerekmez. Hasta verisi hiçbir yere gönderilmez veya kaydedilmez; PDF ve Excel dosyaları tarayıcıda oluşturulur.

## GitHub Pages ile yayınlama

1. GitHub'da yeni bir depo oluşturun (örn. `karaciger-nit`). GitHub Pages ücretsiz hesapta **public** depo ister.
2. `index.html` ve bu `README.md` dosyasını depoya yükleyin (**Add file → Upload files → Commit changes**).
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, **Branch: `main` / `(root)`** seçip **Save**.
4. 1–2 dakika sonra sayfa şu adreste açılır: `https://<kullanıcı-adınız>.github.io/karaciger-nit/`

## Excel veritabanı

**Sonuçları dışa aktar → Excel veritabanı** bölümünden hasta kayıtlarınızı tuttuğunuz `.xlsx` dosyasını seçin (veya yeni bir veritabanı başlatın). **Bu hastayı veritabanına ekle** hastayı yeni satır olarak ekler; aynı hasta no ve tetkik tarihi varsa üzerine yazma veya yeni satır seçeneği sunar. Chrome'da dosyaya doğrudan yazılabilir; diğer tarayıcılarda **Güncel veritabanını indir** ile güncel dosyayı alıp eskisinin yerine koyun. Dosya bilgisayarınızda kalır.

## Güncelleme

`index.html` dosyasını depoda değiştirip commit ettiğinizde aynı adres otomatik güncellenir; bağlantıyı paylaştığınız herkes yeni sürümü görür (tarayıcı önbelleği nedeniyle birkaç dakika gecikebilir).

## Uyarı

Klinik karar desteği içindir; sonuçlar etiyoloji ve karıştırıcı faktörlerle birlikte yorumlanmalıdır. Formül ve eşiklerin kaynakları sayfanın altında listelenmiştir.
