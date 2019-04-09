# Merealisasi RMA Supplier In

## A. INPUT

* Data RMA supplier in yang akan direalisasi harus memiliki status **Ready To Transfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi RMA supplier in.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> RMA Supplier In**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data RMA supplier in yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/rma-supplier-in/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/rma-supplier-in/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/rma-supplier-in/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/rma-supplier-in/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari RMA supplier in akan berubah menjadi **Transfered**

![](../../img/rma-supplier-in/status-transfered.png)
