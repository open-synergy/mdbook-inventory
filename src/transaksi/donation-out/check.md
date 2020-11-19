# Mengecek Ketersediaan Donation Out

## A. INPUT

* Data donation out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/donation-out/status-waiting-availability.png)

* User yang akan mengecek harus memiliki akses untuk mengecek donation out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Donation Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data donation out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/donation-out/tombol-check.png)

## C. OUTPUT

* Status dari donation out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/donation-out/status-ready-to-transfer.png)

* Status dari donation out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/donation-out/status-partial.png)

* Status dari donation out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/donation-out/status-waiting-availability.png)
