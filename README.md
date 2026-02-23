# 📦 Kargo-Takip

Kargo Takip Sistemi - Kargo gönderimleri için gerçek zamanlı izleme ve yönetim platformu.

## ✨ Özellikler

- 📍 **Gerçek Zamanlı Takip** - Kargo konumunu anlık olarak takip edin
- 🔔 **Bildirimler** - Kargo durumu değiştiğinde anında bilgilendirilmek
- 📊 **Detaylı Raporlar** - Teslimat geçmişi ve istatistikler
- 🗺️ **Harita Entegrasyonu** - Kargo rotalarını görsel olarak görmek
- 👥 **Kullanıcı Yönetimi** - Gönderici ve alıcı hesapları
- 🔐 **Güvenli API** - Güvenli veri iletişimi

## 🚀 Hızlı Başlangıç

### Gereksinimler
- Node.js 14+ veya Python 3.8+
- Git

### Kurulum

```bash
# Repository'yi klonlayın
git clone https://github.com/Hasan543717/Kargo-Takip.git
cd Kargo-Takip

# Bağımlılıkları yükleyin
npm install
# veya
pip install -r requirements.txt

# Uygulamayı başlatın
npm start
# veya
python app.py
```

## 📖 Kullanım

### Basit Örnek

```javascript
// Kargo takip etme
const cargo = new CargoTracker('CARGO123');
cargo.track().then(location => {
  console.log('Kargo Konumu:', location);
});
```

## 📁 Proje Yapısı

```
Kargo-Takip/
├── src/
│   ├── api/           # API endpointleri
│   ├── models/        # Veri modelleri
│   └── utils/         # Yardımcı fonksiyonlar
├── public/            # Statik dosyalar
├── tests/             # Test dosyaları
├── README.md          # Bu dosya
├── package.json       # Bağımlılıklar
└── .gitignore         # Git için yok sayılacak dosyalar
```

## 🛠️ Teknolojiler

- **Backend:** Node.js / Express.js veya Python / Flask
- **Frontend:** React / Vue.js
- **Veritabanı:** MongoDB / PostgreSQL
- **Harita:** Google Maps API / Leaflet
- **Deployment:** Docker / Heroku

## 📝 API Dokümantasyonu

### Kargo Durumu Sorgula

```
GET /api/cargo/:trackingNumber
```

**Yanıt:**
```json
{
  "trackingNumber": "CARGO123",
  "status": "In Transit",
  "location": "İstanbul",
  "estimatedDelivery": "2026-02-25"
}
```

## 🧪 Testler

```bash
# Tüm testleri çalıştırın
npm test
# veya
pytest
```

## 🤝 Katkıda Bulunma

Katkılarınız memnuniyetle karşılanır! 

1. Repository'yi forklayın
2. Feature branch'i oluşturun (``git checkout -b feature/AmazingFeature``)
3. Değişiklikleri commit edin (``git commit -m 'Add AmazingFeature'``)
4. Branch'i push edin (``git push origin feature/AmazingFeature``)
5. Pull Request açın

## 📋 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👤 Geliştirici

**Hasan543717**
- GitHub: [@Hasan543717](https://github.com/Hasan543717)

## 📧 İletişim

Sorularınız veya önerileriniz için:
- 📝 Issue açın: [GitHub Issues](https://github.com/Hasan543717/Kargo-Takip/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/Hasan543717/Kargo-Takip/discussions)

## 🐛 Hata Bildirme

Bir hata bulduysanız, lütfen [Issues](https://github.com/Hasan543717/Kargo-Takip/issues) kısmında detaylı bir rapor açın.

---

⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!