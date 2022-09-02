# PostmanAPI-Reqres.in
Proyek ini dibuat sebagai simulasi untuk lebih memahami bagaimana teknis pengujian API melalui Postman. Script yang dibuat dapat diexport dan kemudian dijalankan menggunakan Newman dalam rangka otomasi. Sehingga memudahkan jika ingin melakukan pengujian secara berulang-ulang dengan cepat.

 ## File meliputi : 
- File export dari Postman (JSON)
- File report dari Newman (HTML)

## Fitur yang dijalankan :
- 1 Request untuk Method GET
- 1 Request untuk Method POST
- 1 Request untuk Method PATCH
- 1 Request untuk Method PUT
- 1 Request untuk Method DELETE
- Masing-masing menggunakan minimal 3 assertion
- Menggunakan variabel untuk data yang dipakai

## API Provider :
https://reqres.in/

## Tangkapan Layar

- Melakukan testing collection menggunakan Postman
![Screenshot (163)](https://user-images.githubusercontent.com/106912197/188056831-63e300ad-a514-4095-a7a3-f1577440bd0a.png)

- Melakukan testing dengan Newman
![Screenshot (164)](https://user-images.githubusercontent.com/106912197/188057141-1d1f5ad2-ceea-4c9c-926b-d780c349fd4f.png)

- Hasil report HTML
![Screenshot (161)](https://user-images.githubusercontent.com/106912197/188057200-a7ff6fc1-dcbc-487c-95cd-46a8285f8825.png)

## Cara menjalankan :
```bash
newman run PostmanAPI-Reqres.in.postman_collection.json
``` 
  
## Membuat HTML Report
```bash
newman run PostmanAPI-Reqres.in.postman_collection.json -r html
``` 