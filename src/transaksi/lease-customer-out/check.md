# Mengecek Ketersediaan Lease Customer Out

## A. INPUT

* Data lease customer out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/lease-customer-out/status-waiting-availability.png)

* User yang akan mengecek harus memiliki akses untuk mengecek lease customer out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Lease Customer Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data lease customer out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/lease-customer-out/tombol-check.png)

## C. OUTPUT

* Status dari lease customer out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/lease-customer-out/status-ready-to-transfer.png)

* Status dari lease customer out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/lease-customer-out/status-partial.png)

* Status dari lease customer out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/lease-customer-out/status-waiting-availability.png)
