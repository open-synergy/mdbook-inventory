# Merealisasi RMA Customer Out

## A. INPUT

* Data RMA customer out yang akan direalisasi harus memiliki status **Ready To Transfer** atau **Partially Available**

![](../../img/rma-customer-out/status-ready-to-transfer.png)

![](../../img/rma-customer-out/status-partial.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi RMA customer out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Customer Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data RMA customer out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/rma-customer-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/rma-customer-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/rma-customer-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari RMA customer out akan berubah menjadi **Transfered**

![](../../img/rma-customer-out/status-transfered.png)
