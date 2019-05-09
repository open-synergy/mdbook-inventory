# Mengecek Ketersediaan Stolen

## A. INPUT

* Data stolen yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/stolen/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek stolen.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Stolen**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data stolen yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/stolen/tombol-check.png)


## C. OUTPUT

* Status dari Stolen akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/stolen/status-ready-to-transfer.png)

* Status dari Stolen akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/stolen/status-partial.png)

* Status dari Stolen tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/stolen/status-waiting.png)
