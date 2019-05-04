# Mengecek Ketersediaan RMA Supplier Out

## A. INPUT

* Data RMA supplier out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/rma-supplier-out/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek RMA supplier out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Supplier Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data RMA supplier out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/rma-supplier-out/tombol-check.png)

## C. OUTPUT

* Status dari RMA supplier out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/rma-supplier-out/status-ready-to-transfer.png)

* Status dari RMA supplier out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/rma-supplier-out/status-partial.png)

* Status dari RMA supplier out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/rma-supplier-out/status-waiting.png)
