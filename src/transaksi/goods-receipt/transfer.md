# Merealisasi Goods Receipt

## A. INPUT

* Data goods receipt yang akan direalisasi harus memiliki status **Ready To Trasfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi goods receipt.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Receipts**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data goods receipt yang akan direalisasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/goods-receipt/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/goods-receipt/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/goods-receipt/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/goods-receipt/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari goods receipt akan berubah menjadi **Transfered**

![](../../img/goods-receipt/status-transfered.png)
