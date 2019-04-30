# Merealisasi Inter-Warehouse In

## A. INPUT

* Data inter-warehouse in yang akan direalisasi harus memiliki status **Ready To Transfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi inter-warehouse in.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Inter-Warehouse In**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data inter-warehouse in yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/interwarehouse-in/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/interwarehouse-in/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/interwarehouse-in/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/interwarehouse-in/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari inter-warehouse in akan berubah menjadi **Transfered**

![](../../img/interwarehouse-in/status-transfered.png)
