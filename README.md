# CreateXMLtoClass
 
Untuk generate file xml ke class dotnet

Prerequist:
+++++++++++++++++++++++++++++++++++++++++++


[Xsd2code](https://www.4shared.com/archive/BjEtNPV0ba/xsd2code_full.html) 

disable internet connection ketika run applikasi

Langkah:
1. XML to XSD

[*] open xml file dengan visual studio navigate menu XML->create schema save schema 

2. XSD to class

bisa menggunakan tools microsoft visual studio (xsd.exe) atau tools yang telah di download

++++ 1. kalau mengunakan tools microsoft executed dari command line xsd.exe namafile.xsd /classes /n:namanamespace 

hasil nya namafile.cs 

+++++ 2 kalau mengunakan xsd2code lebih mudah

3. import class file ke project. class tersebut berisi properties(get, set) function dari fungsi headings sampai sub headings. implement ur logic to code


