# Merealisasi Interwarehouse Out

## A. INPUT

* Data inter-warehouse out yang akan direalisasi harus memiliki status **Ready To Transfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi inter-warehouse out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Inter-Warehouse Out**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data inter-warehouse out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/interwarehouse-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/interwarehouse-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/interwarehouse-out/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/interwarehouse-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari inter-warehouse out akan berubah menjadi **Transfered**

![](../../img/interwarehouse-out/status-transfered.png)
