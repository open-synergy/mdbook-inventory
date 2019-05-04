# Mengecek Ketersediaan RMA Customer Out

## A. INPUT

* Data RMA customer out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/rma-customer-out/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek RMA customer out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Customer Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data RMA customer out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/rma-customer-out/tombol-check.png)

## C. OUTPUT

* Status dari RMA customer out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/rma-customer-out/status-ready-to-transfer.png)

* Status dari RMA customer out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/rma-customer-out/status-partial.png)

* Status dari RMA customer out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/rma-customer-out/status-waiting.png)
