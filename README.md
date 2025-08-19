# NYC TLC Trip Record - Green Taxi Analysis

## **1. Ringkasan**

New York City Taxi & Limousine Commission (NYC TLC) bertanggung jawab atas regulasi, perizinan, lisensi kendaraan (Yellow Taxi, Green Taxi, For Hire Vehicle, Commuter Van, Paratransit Vehicle). Green Taxi diperkenalkan oleh NYC TLC pada tahun 2013. Green Taxi bertujuan untuk menangani wilayah Manhattan Utara dan Luar Manhattan, kepemilikan Green Taxi bisa oleh individu atau perusahaan taxi maupun pengusaha lokal.

Tantangan yang dihadapi oleh Fleet Owner Green Taxi adalah persaingan antara Yellow Taxi dan FHV (Uber, Lyft). Seiring dengan perkembangan teknologi, tantangan lain yang dihadapi yaitu pemesanan secara online/aplikasi, Green Taxi sudah tersedia dalam aplikasi NYC TLC Official App maupun aplikasi pihak ketiga lain. Namun perlu peningkatan kinerja lain untuk mempertahankan serta meningkatkan kepercayaan pelanggan agar tetap memilih Green Taxi

Dari permasalahan yang ada, diharapkan masalah dapat diselesaikan dengan cara :
-Mencari lokasi yang ramai permintaan berdasarkan wilayah dan zona
-Mencari waktu yang ramai permintaan berdasarkan tanggal, hari, dan jam
-Mengidentifikasi preferensi/perilaku pelanggan berdasarkan metode pembayaran, tip yang diberikan, penggunaan taksi oleh pelanggan


## **2. Data**
Data yang digunakan berasal dari situs resmi NYC TLC ([NYC TLC Official Site](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page))
- NYC TLC Trip Record.csv
- taxi_zone_lookup.csv

File Analisis :
- Green Taxi Analysis by yanfa121.ipynb (Jupyter Notebook)
- Green Taxi Analysis Presentation.pdf [(Canva Link)](https://www.canva.com/design/DAGwJ9FM9Mw/lrjL-3ozm90E-16t0Y02VA/edit?utm_content=DAGwJ9FM9Mw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- Green Taxi Dashboard.twb [(Tableau Public Link)](https://public.tableau.com/views/GreenTaxiDashboard_17555258827810/NYC?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- NYC TLC Trip Record.csv (Raw Data)
- NYC TLC Trip Record CLEAN.csv (Cleaned Data)
- taxi_zone_lookup.csv (Additional Data)

## **3. Tools yang Digunakan**
- Microsoft Visual Studio Code, Jupyter Notebook
- Programming Language : Python (Pandas, Numpy, SciPy)
- Visualisasi : Seaborn, Matplotlib
- Dashboard Interaktif : Tableau
- Presentation : Canva


## **4. Kesimpulan dan Rekomendasi**
**Kesimpulan**
Dari analisis yang sudah dilakukan, kita dapat menarik kesimpulan bahwa :
1. WIlayah dengan permintaan tertinggi adalah Manhattan, diikuti oleh wilayah Queens dan Brooklyn
2. Zona dengan permintaan tertinggi berada pada wilayah Manhattan
3. Hari hari kerja (weekdays) lebih ramai permintaan dibanding akhir pekan (weekend). Kecuali pada wilayah Brooklyn yang lebih ramai di akhir pekan (weekend)
4. Pada tanggal merah (hari libur) permintaan cenderung turun karena mobilitas masyarakat yang tidak tinggi
5. Jam jam sibuk mendominasi permintaan yaitu pada Pagi hari (7:00 - 9:00), Siang hari (10:00 - 14:00) dan Sore hari (15:00 - 18:00)
6. Pelanggan lebih banyak melakukan pembayaran menggunakan kartu kredit
7. Banyak pelanggan yang menggunakan taksi untuk berpergian dengan jarak <5 mil
8. Tip memiliki korelasi positif dengan total biaya perjalanan, meskipun tingkat korelasinya sedang
9. Adanya faktor lain diluar biaya perjalanan yang mempengaruhi besaran tip
10. Setiap wilayah memiliki besaran tip yang berbeda

**Rekomendasi**
Beberapa strategi yang dapat dilakukan :
1. Mengoptimalisasi armada di Manhattan terutama pada jam sibuk, alihkan zona rendah ke zona tinggi permintaan
2. Memfokuskan armada pada akhir pekan (weekend) di wilayah Brooklyn, dengan mengalihkan beberapa armada pada zona sepi di wilayah lain ke Brooklyn
3. Mengurangi jumlah armada yang aktif di hari libur untuk efisiensi operasional
4. Menyediakan armada lebih responsif pada jam sibuk agar supply selalu tersedia
5. Karena kartu kredit lebih dominan, bisa menjalin kerja sama dengan penyedia kartu kredit untuk promo cashback atau poin untuk menarik pelanggan
6. Bisa menerapkan tarif flat untuk perjalanan dengan jarak <5 mil agar pelanggan lebih merasa hemat dan semakin loyal
7. Perkuat layanan di area Central Bussiness District yaitu Manhattan, karena demand jarak dekat yang tinggi
8. Membuat survey kepuasan pelanggan untuk evaluasi
9. Meningkatkan keramahan driver, menjaga kebersihan kendaraan untuk meningkatkan kenyamanan dan kepuasan pelanggan
10. Mengoptimalkan pelayanan disetiap wilayah, contoh seperti Manhattan jangan terfokus dengan tip, tetapi manfaatkan volume tinggi pada wilayah tesebut


## **5. Contact**
- Yanfa Anandika
- Email : yanfaanandika21@gmail.com
- LinkedIn : [Yanfa Anandika](https://www.linkedin.com/in/yanfa-anandika-a663bb170/)
- GitHub : [yanfa121](https://github.com/yanfa121)
