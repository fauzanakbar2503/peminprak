## MongoDB Compass
1. Melakukan koneksi ke MongoDB menggunakan connection string dengan tidak menggunakan mangodb atlas. <br />
![Screen shoot mangodb connection without atlas](../Modul2/Screenshots/ConnectWithoutAtlas.png)
2. Membuat database dengan melakukan klik “Create Database”. <br />
![Screen shoot create new database](../Modul2/Screenshots/createNewDatabase.png)
3. Melakukan insert buku pertama dengan melakukan klik “Add Data”, pilih “Insert
Document”, isi dengan data yang diinginkan dan klik “Insert”. <br />
Source Code :<br />
```
/** 
* Paste one or more documents here
*/
{
  "_id": {
    "$oid": "650826bd1044825c9f07cbab"
  },
  "title":"No longer Human",
  "author":"Osamu Dazai",
  "year":1948,
  "pages":271,
  "summary":"Lorem ipsum dolor sit amet",
  "publisher":"Gramedia"
}
``` 
Screenshot : <br />
![Screen shoot insert data](../Modul2/Screenshots/insertDataMangoDB.png)
4. Melakukan insert buku kedua dengan cara yang sama. <br />
Source Code :<br />
```
/** 
* Paste one or more documents here
*/
{
  "_id": {
    "$oid": "650829ed1044825c9f07cbac"
  },
  "title": "I am a Cat",
  "author": "Natsume Souseki",
  "year": 1905,
  "pages": 532,
  "summary": "Lorem ipsum dolor si amet",
  "publisher":"Gramedia"
}
``` 
Screenshot : <br />
![Screen shoot insert data](../Modul2/Screenshots/insertDataMangoDB2.png)
5. Melakukan pencarian buku dengan author “Osamu Dazai” dengan mengisi filter yang
diinginkan dan klik “Find” <br />
![Screen shoot find author](../Modul2/Screenshots/findOsamu.png)
5. Melakukan perubahan summary pada buku “No Longer Human” menjadi “Buku yang
bagus (<NAMA>,<NIM>) dengan melakukan klik “Edit Document” (berlambang
pensil), mengisi nilai summary yang baru, dan melakukan klik “Update” <br />
![Screen shoot find author](../Modul2/Screenshots/updateSummary.png)
6. Lakukan penghapusan pada buku “I Am a Cat” dengan melakukan klik “Remove
Document” (berlambang tong sampah) dan melakukan klik “Delete” <br />
![Screen shoot find author](../Modul2/Screenshots/deleteBook.png)
## MongoDB Shell
1. 


