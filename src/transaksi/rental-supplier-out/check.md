# Mengecek Ketersediaan Rental Supplier Out

## A. INPUT

* Data rental supplier out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/rental-supplier-out/status-waiting-availability.png)

* User yang akan mengecek harus memiliki akses untuk mengecek rental supplier out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Rental Supplier Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data rental supplier out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/rental-supplier-out/tombol-check.png)

## C. OUTPUT

* Status dari rental supplier out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/rental-supplier-out/status-ready-to-transfer.png)

* Status dari rental supplier out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/rental-supplier-out/status-partial.png)

* Status dari rental supplier out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/rental-supplier-out/status-waiting-availability.png)
