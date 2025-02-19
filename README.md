Nama : Muhammad Naufal Zaki

Kelas : SKU2B

NIM : 09011382429154

---

## RASPBERRY PI 5 - SPESIFIKASI, STRUKTUR, DAN KONTROL UNIT

Apa itu Raspberry PI 5? Raspberry PI 5 adalah generasi terbaru dari komputer single-board yang dikembangkan oleh Raspberry Pi Foundation. Dibandingkan dengan pendahulunya, Raspberry Pi 4, model ini menghadirkan peningkatan signifikan dalam performa, efisiensi daya, dan fitur tambahan. Lalu, apa itu Raspberry PI? Raspberry Pi adalah sebuah komputer single-board (SBC) berukuran kecil yang dikembangkan oleh Raspberry Pi Foundation, sebuah organisasi nirlaba di Inggris. Raspberry Pi dirancang untuk pendidikan, eksperimen, dan proyek elektronik, tetapi kini juga banyak digunakan dalam berbagai aplikasi, termasuk robotika, IoT (Internet of Things), server mini, hingga media center.

Raspberry Pi memiliki beberapa karakteristik utama. Ukurannya kecil dan hemat daya, dengan bentuk yang mirip kartu kredit serta dapat dijalankan menggunakan daya dari USB-C atau Micro-USB. Perangkat ini menggunakan prosesor berbasis ARM yang mirip dengan ponsel dan sistem operasi utamanya adalah Raspberry Pi OS (sebelumnya Raspbian), meskipun juga dapat menjalankan berbagai sistem operasi berbasis Linux, serta beberapa varian Windows dan Android. Selain itu, Raspberry Pi dilengkapi dengan port I/O seperti GPIO (General Purpose Input Output) yang memungkinkan pengguna menghubungkan sensor, motor, dan perangkat elektronik lainnya. Keunggulan lain dari Raspberry Pi adalah harganya yang terjangkau, karena dirancang agar komputer dapat diakses dengan mudah, terutama untuk keperluan pendidikan.  

Raspberry Pi memiliki berbagai kegunaan. Perangkat ini dapat digunakan sebagai komputer mini yang berfungsi sebagai desktop ringan. Selain itu, Raspberry Pi mampu menjalankan emulator game klasik seperti NES dan PlayStation 1, sehingga cocok untuk gaming retro. Dalam bidang jaringan, Raspberry Pi dapat berfungsi sebagai server mini yang digunakan untuk web server, cloud pribadi, atau server media seperti Plex. Perangkat ini juga banyak dimanfaatkan dalam robotika dan IoT untuk proyek smart home, otomasi, serta pengembangan robot pintar. Selain itu, Raspberry Pi dapat digunakan sebagai media center, yang memungkinkan pengguna mengubahnya menjadi TV Box untuk streaming dan menonton video.

![image](https://github.com/user-attachments/assets/6fc21802-7c2a-4ded-95f1-5f28c86e4fe9)

## SPESIFIKASI DAN STRUKTUR

- Broadcom BCM2712 2.4GHz quad-core 64-bit Arm Cortex-A76 CPU, with cryptography extensions, 512KB per-core L2 caches and a 2MB shared L3 cache

- VideoCore VII GPU, supporting OpenGL ES 3.1, Vulkan 1.2

- Dual 4Kp60 HDMI® display output with HDR support

- 4Kp60 HEVC decoder

- LPDDR4X-4267 SDRAM (2GB, 4GB, 8GB, and 16GB)

- Dual-band 802.11ac Wi-Fi®

- Bluetooth 5.0 / Bluetooth Low Energy (BLE)

- microSD card slot, with support for high-speed SDR104 mode

- 2 × USB 3.0 ports, supporting simultaneous 5Gbps operation

- 2 × USB 2.0 ports

- Gigabit Ethernet, with PoE+ support (requires separate PoE+ HAT)

- 2 × 4-lane MIPI camera/display transceivers

- PCIe 2.0 x1 interface for fast peripherals (requires separate M.2 HAT or other adapter)

- 5V/5A DC power via USB-C, with Power Delivery support

- Raspberry Pi standard 40-pin header

- Real-time clock (RTC), powered from external battery

- Power button

![image](https://github.com/user-attachments/assets/d976beaf-76e5-4455-9eda-477b33f47b57)

1. Komponen Utama
   
   
- BCM2712 Processor = Prosesor quad-core Cortex-A76 2.4 GHz yang memberikan peningkatan performa dibanding model sebelumnya.

- SRAM (1GB, 2GB, 4GB, atau 8GB) = Modul RAM LPDDR4X-4267 yang digunakan untuk menyimpan data sementara.

- PMIC (Power Management IC) = Komponen untuk mengatur distribusi daya ke berbagai bagian board.

- On/Off Button = Tombol daya yang memungkinkan pengguna mematikan atau menyalakan Raspberry Pi 5 secara langsung.

2. Port Konektivitas & Ekspansi

   
- Dual-band 802.11ac Wireless + Bluetooth 5 = Modul konektivitas nirkabel untuk Wi-Fi dan Bluetooth.

- PCI Express Interface = Slot ekspansi untuk menambahkan SSD NVMe atau perangkat lain.

- USB-C Power Jack = Port utama untuk memberikan daya ke Raspberry Pi 5 (5V/5A).

- 2 × USB 3.0 = Port USB berkecepatan tinggi untuk perangkat seperti SSD eksternal atau kamera.

- 2 × USB 2.0 = Port tambahan untuk keyboard, mouse, atau perangkat lainnya.

- Ethernet Jack & Transceiver = Port jaringan untuk konektivitas Gigabit Ethernet, mendukung PoE+ dengan modul tambahan.

- PoE HAT Connector = Konektor untuk modul PoE (Power over Ethernet), memungkinkan daya dikirim melalui kabel jaringan.

- UART Connector = Antarmuka komunikasi serial untuk debugging atau pengendalian perangkat eksternal.

3. Port Output & Display

   
- 2 × Micro-HDMI = Mendukung output video hingga 4K@60Hz dual display.

- 2 × 4-lane MIPI DSI/CSI Connectors = Konektor untuk menghubungkan layar (DSI) dan kamera (CSI).

4. Fitur Tambahan

   
- Raspberry Pi RP1 I/O Controller = Chip tambahan yang mengelola berbagai fungsi I/O, termasuk USB dan GPIO.

- Fan Connector = Konektor untuk kipas pendingin, yang membantu menjaga suhu Raspberry Pi tetap stabil.

- RTC Battery Connector = Port untuk memasang baterai RTC (Real-Time Clock) agar dapat menyimpan waktu meskipun tidak ada daya.

## CONTROL UNIT

Pada Raspberry Pi 5, Control Unit utama terdapat dalam prosesor Broadcom BCM2712, yang menggunakan arsitektur ARM Cortex-A76 dengan kecepatan 2.4 GHz. Prosesor ini berfungsi untuk menjalankan perintah, mengelola data, serta mengontrol jalannya operasi dalam perangkat. Control Unit di dalam prosesor berkomunikasi dengan berbagai komponen lain, termasuk memori, unit pemrosesan angka (ALU), dan perangkat input/output.

![image](https://github.com/user-attachments/assets/3529ab99-565c-48f8-94cb-0816d024429f)

Selain prosesor, Raspberry Pi RP1 I/O Controller juga berperan sebagai pengatur komunikasi antara berbagai perangkat eksternal. Chip ini bertanggung jawab atas pengelolaan GPIO (General Purpose Input/Output), USB 3.0, USB 2.0, serta jaringan Ethernet. Dengan adanya RP1, sistem dapat mengakses dan mengontrol berbagai perangkat eksternal dengan lebih cepat dan efisien.

![image](https://github.com/user-attachments/assets/131eeec4-bad0-4641-b4a0-c6831826dbbf)

Selanjutnya, Raspberry Pi 5 memiliki Power Management IC (PMIC) yang bertugas untuk mengelola distribusi daya ke seluruh komponen. PMIC memastikan bahwa CPU, RAM, dan berbagai modul lainnya mendapatkan daya yang cukup dan stabil agar dapat beroperasi tanpa gangguan.

![image](https://github.com/user-attachments/assets/786be748-bd72-485c-8ad9-3d86f0bac8f8)

Untuk ekspansi perangkat, Raspberry Pi 5 dilengkapi dengan PCIe 2.0 Interface, yang memungkinkan pengguna menambahkan perangkat seperti SSD NVMe untuk meningkatkan kecepatan penyimpanan. Control Unit juga mengelola komunikasi dengan UART (Universal Asynchronous Receiver-Transmitter), yang digunakan untuk debugging atau kontrol perangkat berbasis mikrokontroler.

---
