# tugaswebservice2
Langkah-langkah untuk membuat file XSD adalah sebagai berikut:

1.Buatlah project baru di aplikasi Eclipse dengan memilih menu 1.FileNew 2.Project 3.Plug-in Development 4.Plug-in Project

2.lalu buat nama project jasaservice(nama project bebas) 1. Next 2. Finish

3.Pada package explorer masuk ke jasa service

4.pada src klik kanan 
  pilih 1. new 2. other 3. folder XML 4. XML file(atau ketik saja di kotak XML FILE) jasaservice.XML(sesuaikan dengan nama      project yang telah anda buat)
finish

5.sesudah file xml berhasil di buat isilah data atau project yang sesuai dengan apa yang anda buat(sama seperti data project yang di buat di atas).

6.sesudah selesai membuat file dan mengisi data project anda kemudian klik kanan pada file xml 
1.create definition XML

7.Kemudian ok

8.lalu beri nama jasaservice.xsd

9.setelah itu kita mengkoneksikan antara file xml dan xsd

10.klik kanan pada file xsd
generate
XML File
buat nama file (sesuai dengan nama project)

11.klik file xml yang baru kemudian copy(xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="jasaservice.xsd")

12.kemudian paste di file xml yang pertama 

13.save 

14.klik kanan jasa service.xml
  kemudian validate

15.setelah berhasil 

16.masuk ke file XSD lalu pilih email lalu di bawah terdapat properties
constraints
patterns
add

17.isi current regular expression dengan (.+@)

18.finish
Sekian dan terimakasih.
