1. Melakukan koneksi ke MongoDB menggunakan connection string dengan tidak menggunakan mangodb atlas. <br />
![Screen shoot mangodb connection without atlas](../Modul2/Screenshots/ConnectWithoutAtlas.png)
2. Membuat database dengan melakukan klik “Create Database”. <br />
![Screen shoot create new database](../Modul2/Screenshots/createNewDatabase.png)
3. Melakukan insert buku pertama dengan melakukan klik “Add Data”, pilih “Insert
Document”, isi dengan data yang diinginkan dan klik “Insert”. <br /><br />
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
![Screen shoot insert data ke 2](../Modul2/Screenshots/insertDataMangoDB2.png)
