# Merealisasi Delivery Order

## A. INPUT

* Data delivery order yang akan direalisasi harus memiliki status **Ready To Transfer**.

![](../../img/delivery-order/status-ready-to-transfer.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi delivery order.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Delivery Order**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data delivery order yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/delivery-order/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/delivery-order/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/delivery-order/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari delivery order akan berubah menjadi **Transfered**

![](../../img/delivery-order/status-transfered.png)
