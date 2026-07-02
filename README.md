# Netflix Kontent və Trend Analizi (SQL, Python & Power BI)

Bu layihədə Netflix platformasındakı film və serialların (TV Shows) janrları, buraxılış illəri, reytinqləri, istehsal olunduğu ölkələr və kontent növlərinin paylanması analiz edilmişdir. Project verilənlərin Python ilə vizuallaşdırma öncəsi hazırlanmasını, SQL ilə sorğulanmasını və Power BI-da interaktiv şəkildə hesabatlaşdırılmasını əhatə edir.

## 🛠️ İstifadə Olunan Texnologiyalar
* **Python (Pandas, NumPy):** İlkin məlumat analizi (EDA), çatışmayan (null) dəyərlərin doldurulması və data manipulyasiyası.
* **SQL:** Kontentin növlərinə görə qruplaşdırılması, ölkə və aktyor heyətinə görə süzgəclənməsi və analitik sorğuların yazılması.
* **Power BI:** Data modelləşdirilməsi, DAX metrikalarının hesablanması və interaktiv idarəetmə panelinin (Dashboard) qurulması.

---

## 🐍 Python mərhələsində görülən işlər (Data Preprocessing)
* `Jupyter Notebook` mühitində Netflix verilənlər çoxluğu (Dataset) yükləndi və ümumi strukturu analiz edildi.
* Ölkə və direktor sütunlarındakı boş buraxılmış (`NaN`) dəyərlər uyğun metodlarla təmizləndi və ya fərqli kateqoriyaya qruplaşdırıldı.
* Tarix formatları analizə uyğun formaya gətirildi.

---

## 💾 SQL mərhələsində görülən işlər (Data Queries)
* **Qruplaşdırma və Aqreqasiya:** Film və serialların say fərqi, illər üzrə platformaya əlavə olunma dinamikası `COUNT()` və `GROUP BY` sorğuları ilə çıxarıldı.
* **Mürəkkəb Süzgəcləmə:** Bir filmdə birdən çox ölkə adı qeyd olunan sətirlər SQL funksiyaları ilə təmizlənərək analizə hazır vəziyyətə gətirildi.

---

## 📊 Power BI mərhələsində görülən işlər (Data Visualization)
* **DAX Metrikaları:** Ümumi Filmlərin Sayı, Serialların Sayı və Kontentlərin artım faizləri dinamik DAX ölçüləri (`Measures`) ilə hesablandı.
* **Vizual Dizayn:** * Kontent növlərinin payı dairəvi qrafiklə (Donut chart) əks olundu.
  * Janrların və ölkələrin populyarlığı Tree-map və Bar qrafikləri vasitəsilə göstərildi.
  * Slicer-lar (filtrlər) vasitəsilə istifadəçiyə il və reytinq üzrə dinamik seçim imkanı verildi.

---

## 📈 Hesabat Görüntüləri (Dashboard Screens)

### 1. Kino sənayesi analizi
![Netflix Dashboard Səhifə 1](Ekran%20şəkli%202026-07-01%20113815.png)

### 2. Kino sənayesi və səs vermə analizi
![Netflix Dashboard Səhifə 2](Ekran%20şəkli%202026-07-01%20113859.png)

### 3.Filmlərin keyfiyyət və reytinq təhlili
![Netflix Dashboard Səhifə 3](Ekran%20şəkli%202026-07-01%20113933.png)

### 4. Kino istehsalı və həcm tehlili
![Netflix Dashboard Səhifə 4](Ekran%20şəkli%202026-07-01%20114000.png)
