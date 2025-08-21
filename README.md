<h1 align="center">🥗 Diyet Asistanı</h1>

<p align="center">
  <img src="logo.png" alt="Diyet Asistanı Logo" width="120" />
</p>

<p align="center">
  <strong>Beslenme takibi hiç bu kadar kolay olmamıştı.</strong><br>
  Günlük öğünlerini, makro değerlerini takip et ve <u>yapay zekâ</u> ile değerlendir!
</p>

---

## 📂 Proje Yapısı

DiyetAsistanı/
├── beslenme.py # Streamlit ile çalışan ana uygulama
├── yiyecekler.csv # Besin bilgileri (isim, kalori, protein, karbonhidrat, yağ)
├── gunluk_kayit.csv # Günlük eklenen içeriklerin kaydedildiği dosya
├── requirements.txt # Gerekli Python kütüphaneleri
├── logo.png # Uygulama için logo
└── .streamlit/
└── secrets.toml # OpenAI API anahtarı (GitHub’a yükleme!)


---

## 💻 Kurulum & Çalıştırma

1. **Projeyi klonla:**

```bash
git clone https://github.com/ozgur90gungor-lang/beslenme-asistani.git
cd beslenme-asistani


Gerekli paketleri yükle:

pip install -r requirements.txt


API anahtarını ayarla:

.streamlit/secrets.toml dosyası oluştur ve içine şunu yaz:

OPENAI_API_KEY = "sk-xxxxxxxxxxxxxxxxxxxxxxxx"


Uygulamayı başlat:

streamlit run beslenme.py


Uygulama genellikle 👉 http://localhost:8501 adresinde açılır.

✨ Özellikler

Öğün seç, yiyecek seç, gram belirle, istediğin kadar öğün ekle.

Günlük kalori, protein, karbonhidrat ve yağ değerlerini takip et.

Veriler gunluk_kayit.csv dosyasında kaydedilir.

AgGrid tablosu sayesinde modern, filtrelenebilir ve mobil uyumlu tablolar.

“Beslenmeni Değerlendir” butonuyla OpenAI yapay zekâ yorumunu al.

logo.png sayesinde mobilde “Masaüstüne Ekle” yapıldığında özel ikon görünür.

ℹ️ Notlar

yiyecekler.csv dosyasına istediğin yemekleri ekleyebilirsin.

gunluk_kayit.csv otomatik olarak günlük kayıtları günceller.

Mobilde Masaüstüne Ekle seçeneği ile uygulama kendi başlığı ve logonla açılır.

👨‍💻 Geliştirici

Bu proje ozgur90gungor-lang tarafından geliştirilmiştir.
Fikirlerin veya katkıların varsa pull request gönderebilirsin. 💡
