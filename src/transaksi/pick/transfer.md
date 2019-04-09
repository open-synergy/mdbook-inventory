# Merealisasi Pick

## A. INPUT

* Data pick yang akan direalisasi harus memiliki status **Ready To Transfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi pick.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Pick**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data pick yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/pick/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/pick/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/pick/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/pick/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari pick akan berubah menjadi **Transfered**

![](../../img/pick/status-transfered.png)
