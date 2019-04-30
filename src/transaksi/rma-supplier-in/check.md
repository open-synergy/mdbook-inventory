# Mengecek Ketersediaan RMA Supplier In

## A. INPUT

* Data RMA supplier in yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/rma-supplier-in/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek RMA supplier in.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Supplier In**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data RMA supplier in yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/rma-supplier-in/tombol-check.png)

## C. OUTPUT

* Status dari RMA supplier in akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/rma-supplier-in/status-ready-to-transfer.png)

* Status dari RMA supplier in akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/rma-supplier-in/status-partial.png)

* Status dari RMA supplier in tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/rma-supplier-in/status-waiting.png)
