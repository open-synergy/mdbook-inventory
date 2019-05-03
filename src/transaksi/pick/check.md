# Mengecek Ketersediaan Pick

## A. INPUT

* Data pick yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/pick/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek pick.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Pick**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data pick yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/pick/tombol-check.png)

## C. OUTPUT

* Status dari Pick akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/pick/status-ready-to-transfer.png)

* Status dari Pick akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/pick/status-partial.png)

* Status dari Pick tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/pick/status-waiting.png)
