# Dashboard VDR (DM100 Voyage Data Recorder)

DM100 VDR, gemi üzeri veri kaydedici (Voyage Data Recorder) sistemlerinin durumlarını, ağ bölgelerini, donanım metriklerini ve sensör verilerini izlemek, yönetmek ve görselleştirmek amacıyla geliştirilmiş bir denizcilik yönetim panelidir.

## Öne Çıkan Özellikler

* **Canlı Telemetri:** data.json üzerinden alınan CPU sıcaklığı, depolama kullanımı, eMMC ömrü ve PoE güç tüketimi verilerinin anlık takibi.
* **3D Vessel Topology:** Three.js kütüphanesi ile geliştirilmiş etkileşimli (Assemble ve Explode modlu) 3D gemi ve sistem topolojisi görünümü.
* **Canlı Konum Haritası (Bridge Monitor):** Leaflet.js entegrasyonu ile geminin enlem, boylam ve hareket verilerinin harita üzerinde gösterimi.
* **Veri Analitiği:** Chart.js kullanılarak oluşturulmuş depolama dağılımı ve PoE güç tüketimi grafikleri.
* **Rol Tabanlı Erişim (RBAC):** Admin ve Officer kullanıcı seviyelerine göre ayrıştırılmış yetkilendirme ve yönetim arayüzü.
* **Audit Logs:** Sistem ve ağ olaylarının takibi, filtrelenmesi ve verilerin CSV formatında dışa aktarılması.

## Teknolojiler ve Kütüphaneler

* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Tailwind CSS
* **3D & Grafik:** Three.js, Chart.js
* **Harita:** Leaflet.js (OpenStreetMap)
* **Veri Biçimi:** REST API / JSON
