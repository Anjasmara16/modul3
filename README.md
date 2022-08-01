##### Nama : Anjasmara
##### Kelas : XII RPL 1
##### NO Absen : 16

Langkah Pertama cari folder web.php seperti di bawah ini

![image](https://user-images.githubusercontent.com/109930540/182107706-fb6930e9-5c5b-4ccb-8d4f-056e9a60d578.png)

# MODUL 3
##### Selanjutnya kita akan membuat Route yang akan menuju ke halaman kategori

```<?php

namespace illuminate\Http\Controllers;

use Illuminate\http\Request;

class BarangController extends Controller
{
    public function index()
    {
        return 'Mengakses Fungsi di controller menggunakan route';
    }

public function add()
{
    return'you';
}           
}
```

lalu membuat folder kategori controller dibawah ini 
"saran menggunakan
