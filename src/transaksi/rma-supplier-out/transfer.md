# Merealisasi RMA Supplier Out

## A. INPUT

* Data RMA supplier out yang akan direalisasi harus memiliki status **Ready To Transfer** atau **Partially Available**

![](../../img/rma-supplier-out/status-ready-to-transfer.png)

![](../../img/rma-supplier-out/status-partial.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi RMA supplier out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Supplier Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data RMA supplier out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/rma-supplier-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/rma-supplier-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/rma-supplier-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari RMA supplier out akan berubah menjadi **Transfered**

![](../../img/rma-supplier-out/status-transfered.png)
