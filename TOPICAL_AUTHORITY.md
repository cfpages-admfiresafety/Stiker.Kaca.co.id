# Topical Authority — stiker.kaca.co.id

## Role and boundary

stiker.kaca.co.id berperan sebagai pemasok dan kontraktor pemasangan stiker/film kaca untuk gedung, kendaraan, ruang, perabot, serta masjid. Hub edukasi ini membantu pemilik proyek, desainer, pengelola fasilitas, pemilik kendaraan, dan tim pengadaan menyusun kebutuhan, memilih keluarga film, mengoordinasikan desain/pemasangan, serta merawat atau melepas aplikasi. Batasnya bukan katalog stok, daftar harga tetap, petunjuk legal kendaraan final, atau sumber klaim konstruksi film, adhesive, kompatibilitas kaca/substrate, privacy, optical performance, safety, warna/printing longevity, cure time, standar, sertifikasi, dan garansi tanpa bukti produk, aplikasi, serta yurisdiksi yang berlaku.

## Context used

- Dua sitemap utama diperiksa: `sitemap-complete.xml` dan `video-sitemap.xml`. Sitemap lengkap memuat 339 URL unik dan selaras dengan 339 file HTML.
- Sebanyak 264 URL adalah kombinasi delapan tipe (`chromo`, `clear`, `one-way`, `riben`, `sandblast`, `smart`, `vinyl`, dan `warna`) dengan 33 lokasi. Pola itu diperlakukan sebagai delapan keluarga produk, bukan 264 intent geografis.
- Rute semantik non-lokasi mencakup delapan hub tipe, `gedung` dengan enam turunan, `ruang` dengan enam turunan, `mobil` dengan enam turunan, `perabot` dengan dua turunan, `masjid`, dan dua turunan `one-way`.
- Homepage publik memakai H1 “Stiker Kaca Kualitas #1” dan “Jual & Pasang Stiker Kaca”, menyebut pemasangan gedung/mobil, serta menampilkan use case gedung, mobil, ruang, perabot, masjid, jenis film, dan portofolio.
- Hub produk menguatkan tipe clear, chromo, one-way, riben, sandblast/blur, smart/electronic, vinyl, dan warna. Hub aplikasi menguatkan kantor, klinik, rumah sakit, cafe, gereja, apotek, pintu, dinding, jendela, kamar mandi, kitchen set, cermin, aquarium, etalase, serta bagian kendaraan.
- Mode lean dipertahankan. Material, adhesive, substrate, optical/privacy/safety, printing/color longevity, cure, aturan kendaraan, standar, dan sertifikasi dicatat sebagai gerbang publikasi.

## Ignored template noise

- 264 halaman pertukaran tipe dan nama kota `jual-pasang-<tipe>-<kota>` dihitung, tetapi isi dan metadata berulangnya tidak dianalisis.
- 33 rute category/pagination, author, berita/feed, komentar, cache, manifest, verifikasi Google, dan `hello-world` tidak dipakai untuk memperluas taksonomi.
- Entri video sitemap yang berulang tidak diperlakukan sebagai intent baru; sitemap tersebut memiliki 334 entri URL tetapi hanya 299 lokasi halaman unik.
- README dan metadata template tidak dibaca karena sitemap XML, homepage, dan hub semantik sudah memberi konteks keputusan yang cukup.

## Topical map

| Topic ID | Parent topic | Reader outcome | Boundary | Article target |
|---|---|---|---|---:|
| STK-01 | Dasar stiker dan film kaca | Memahami istilah, lapisan, fungsi, dan batas aplikasi sebelum memilih | Fondasi konsep; tidak menyatakan konstruksi atau performa produk tertentu | 6 |
| STK-02 | Brief dan pemilihan film | Menerjemahkan tujuan, lokasi, pengguna, visual, dan anggaran menjadi shortlist | Edukasi kebutuhan lintas tipe; permintaan penawaran tetap di rute komersial | 6 |
| STK-03 | Konstruksi film dan adhesive | Menilai lapisan film, adhesive, liner, surface treatment, dan dokumennya | Komposisi, chemistry, tack, cure, dan removability wajib berdasarkan data produk aktual | 6 |
| STK-04 | Kompatibilitas kaca dan substrate | Mengidentifikasi kondisi kaca, coating, sealant, frame, atau permukaan lain yang perlu diuji | Bukan deklarasi kompatibel; hasil bergantung rakitan, kondisi, dan persetujuan produsen | 6 |
| STK-05 | Privacy, optik, dan klaim keselamatan | Memeriksa bukti privacy, visibility, glare, cahaya, panas, UV, dan safety | Tidak menjamin one-way privacy, heat/UV control, atau peningkatan keselamatan tanpa data | 6 |
| STK-06 | Desain, printing, warna, dan cutting | Menyiapkan artwork, motif, warna, proof, cutting, dan ekspektasi umur visual | Klaim colorfastness, outdoor life, dan hasil warna wajib didukung sistem cetak aktual | 6 |
| STK-07 | Film clear, chromo, vinyl, dan warna | Membedakan keluarga film dekoratif/branding dasar dan use case-nya | Klasifikasi keluarga; bukan katalog SKU atau klaim material/performa | 6 |
| STK-08 | Sandblast, riben, one-way, dan smart film | Memahami mekanisme serta batas sistem privacy/fungsional khusus | Operasi smart film dan klaim privacy/vision wajib dibuktikan untuk konfigurasi aktual | 6 |
| STK-09 | Gedung dan fasilitas publik | Menyusun kebutuhan film untuk kantor, cafe, klinik, rumah sakit, apotek, dan gereja | Khusus fasilitas gedung; bukan rute jasa lokasi atau panduan kendaraan | 6 |
| STK-10 | Ruang dan perabot | Merencanakan aplikasi pada pintu, dinding, jendela, kamar mandi, kitchen set, cermin, etalase, dan aquarium | Khusus elemen ruang/perabot; kompatibilitas substrate tetap dimiliki STK-04 | 6 |
| STK-11 | Masjid dan ruang ibadah | Mengatur privacy, cahaya, motif, operasional, dan perawatan aplikasi masjid | Khusus brief ruang ibadah; bukan klaim material atau ketentuan desain keagamaan universal | 6 |
| STK-12 | Kendaraan dan batas regulasi | Menilai aplikasi pada kaca depan/belakang, bus, pick-up, spion, dan lampu secara legal-aware | Bukan nasihat hukum; visibilitas dan izin harus diverifikasi pada aturan terkini | 6 |
| STK-13 | Pengukuran, pemasangan, dan curing | Menghasilkan ukuran/layout, menyiapkan substrate, memasang, dan memeriksa hasil | Bukan metode universal; toleransi, akses, suhu, serta cure mengikuti produk/proyek | 6 |
| STK-14 | Pembersihan, pelepasan, residu, dan pemulihan | Merawat film, mengenali kegagalan, melepas, dan menangani residu secara terkendali | Tidak menjanjikan removal tanpa residu atau tidak merusak substrate tanpa uji | 6 |
| STK-15 | Pengadaan, harga, jadwal, dan garansi | Menyiapkan RFQ, membandingkan biaya, mengatur logistik, dan membaca garansi | Harga dan garansi harus aktual; transaksi tetap berada di rute kontak | 6 |
| STK-16 | Standar, sertifikasi, QA, dan dokumentasi | Memeriksa relevansi bukti kepatuhan dan kelengkapan serah terima | Tidak menyatakan patuh atau tersertifikasi tanpa dokumen dan verifikasi aplikasi | 6 |

## Internal-link rule

Setiap artikel menaut ke hub topiknya, satu artikel pendamping dalam topik yang sama, dan satu atau dua topik tetangga yang mendukung langkah berikutnya. Artikel pemilihan dapat mengarah ke hub komersial tipe atau aplikasi yang relevan serta `kontak`; tidak ada artikel baru berbasis kota. Pembahasan konstruksi film, adhesive, removal/residue, kaca/substrate compatibility, privacy, optical/thermal/UV, safety, printing/color longevity, ukuran, cure, aturan kendaraan, standar, sertifikasi, warranty, dan price harus menahan angka atau klaim sampai data produk, sampel, instalasi, atau regulasi terkini tersedia.

## First publication wave

Terbitkan 12 aset fondasi dan keputusan terlebih dahulu: `STK-01-01`, `STK-02-01`, `STK-02-02`, `STK-03-01`, `STK-04-01`, `STK-05-01`, `STK-06-01`, `STK-08-01`, `STK-09-01`, `STK-12-01`, `STK-13-01`, dan `STK-15-01`. Gelombang ini membangun kosakata, brief, jalur pemilihan, dan gerbang bukti tanpa memperluas halaman geografis.
