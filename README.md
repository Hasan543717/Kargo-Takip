cd /path/to/kargo-takip
git init
git add .
git commit -m "İlk proje yüklemesi"
git branch -M main
git remote add origin https://github.com/kullaniciadi/kargo-takip.git
git push -u origin main
$conn = new mysqli("sqlXXX.infinityfree.com", "db_user", "db_password", "db_name");
kargo-takip/
│
├── index.php          ← Kullanıcı paneli
├── track.php          ← Kargo sorgu sonucu (opsiyonel)
├── db.php             ← Veritabanı bağlantısı
├── style.css          ← Tasarım dosyası
│
└── admin/
    ├── login.php      ← Admin giriş
    ├── dashboard.php  ← Admin ana panel
    ├── add_shipment.php ← Yeni kargo ekleme
    ├── logout.php     ← Çıkış
    CREATE DATABASE kargo_db;

USE kargo_db;

CREATE TABLE admins (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(255)
);

CREATE TABLE shipments (
    id INT AUTO_INCREMENT PRIMARY KEY,
    tracking_no VARCHAR(20),
    customer_name VARCHAR(100),
    status VARCHAR(100),
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);

CREATE TABLE shipment_logs (
    id INT AUTO_INCREMENT PRIMARY KEY,
    shipment_id INT,
    location VARCHAR(100),
    description TEXT,
    log_date DATETIME DEFAULT CURRENT_TIMESTAMP
);

-- Demo admin
INSERT INTO admins (username, password) 
VALUES ('admin', '$2y$10$wH6W6QvV9n2yY8V9pV8u6eO9H7l8Y5sGJH8dKjH9fLkJH8dJH8dJH'); 
-- Şifre: 123456
git init
git add .
git commit -m "İlk yükleme"
git branch -M main
git remote add origin https://github.com/KULLANICIADI/kargo-takip.git
git push -u origin main
