# Mengecek Ketersediaan RMA Customer In

## A. INPUT

* Data RMA customer in yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/rma-customer-in/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek RMA customer in.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Customer In**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data RMA customer in yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/rma-customer-in/tombol-check.png)

## C. OUTPUT

* Status dari RMA customer in akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/rma-customer-in/status-ready-to-transfer.png)

* Status dari RMA customer in akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/rma-customer-in/status-partial.png)

* Status dari RMA customer in tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/rma-customer-in/status-waiting.png)
