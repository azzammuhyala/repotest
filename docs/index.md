<p align="center">
    <b>
        Index -
        <a href="syntax/index.md">Syntax</a> -
        <a href="modules/index.md">Modules</a> -
        <a href="builtins/index.md">Builtins</a>
    </b>
</p>

[Syntax](syntax/index.md)

# PyScript

<p align="center">
    <img src="https://github.com/azzammuhyala/pyscript/blob/main/PyScript.png?raw=true" alt="PyScript Logo" width="200">
</p>

PyScript adalah bahasa pemprograman sederhana yang dibuat di atas bahasa Python. Bahasa ini mengabungkan beberapa sintaks dari Python dan JavaScript, jadi bagi Anda yang sudah familiar dengan sintaks Python atau JavaScript atau keduanya pasti seharusnya cukup mudah mempelajari bahasa ini.

## Bagaimana Cara Pemasangannya?
1. Pertama-tama Anda perlu mengunduh Python terlebih dahulu. Usahakan versi yang digunakan sudah paling terbaru di atas versi `3.5` agar kode bisa di jalankan dengan benar. Kunjungi [website resmi Python](https://python.org) untuk mengunduhnya.
2. Setelah mengunduh dan melakukan beberapa konfigurasi aplikasi Python, unduh repositori ini atau melalui direktori `pyscript` atau jika Anda sudah mengunduh Python gunakan dengan perintah `python -m pip install pyscript-programming-language` (_Direkomendasikan_).
3. Sekarang silahkan Anda jalankan PyScript shell (_REPL_) dengan perintah `python -m pyscript`. Jika berhasil maka harusnya Anda akan melihat versi, tanggal dan tanda `>>>`.
4. _OPSIONAL_. Anda bisa mengunduh dan menyiapkan kode editor seperti VS Code atau kode editor lainnya untuk menulis program. Atau kalau mau yang berbeda Anda bisa menggunakan Notepad.
5. Jika semua sudah aman dan berjalan dengan benar, sekarang Anda sudah bisa masuk ke sesi pengenalan bahasa PyScript!

## Pengenalan PyScript
Mungkin PyScript dikenal bukanlah bahasa yang akan kita bahas, tetapi sebenarnya nama PyScript sendiri sudah ada yang merupakan platform untuk menjalankan Python dalam browser yang fleksibel dan mudah. Sebelumnya sejak awal bahasa ini dibuat, nama ini dipilih karena memang terinspirasi dengan bahasa Python dan JavaScript yang bahasanya cukup mudah untuk di baca manusia. Dengan itulah nama itu dipilih, karena memang belum diketahui secara langsung apakah nama ini sudah dipakai atau belum. 


Bahasa ini tidak di rancang untuk masuk sebagai bahasa pemprograman modern yang bersaing dengan bahasa lain, tetapi bahasa ini sebagai metode pembelajaran soal bagaimana bahasa pemprograman bekerja dan cara sebuah kode yang manusia tulis bisa di mengerti oleh mesin. Selain daripada itu, bahasa ini dibuat sebagai projek yang cukup kompleks. Dengan bahasa Python sebagai dasar pembuatan bahasa PyScript dengan sintaksnya yang cukup mudah dipahami membuatnya bisa menjadi mudah di mengerti soal bagaimana bahasa itu dibuat tanpa memahami tentang instruksi lain yang kompleks seperti di C, C++, dan bahasa tingkat rendah lain.

<pre class="pyscript-code"><span id="identifier-call">print</span><span id="parenthesis-0">(</span><span id="string">&quot;Hello World!&quot;</span><span id="parenthesis-0">)</span></pre>


<style>
    /*
        if you seeing this it means this platform has disabled style tags
        for security reasons.
    */

    :root {
        --default: #D4D4D4;
        --keyword: #C586C0;
        --keyword-identifier: #307CD6;
        --identifier: #8CDCFE;
        --identifier-const: #2EA3FF;
        --identifier-call: #DCDCAA;
        --identifier-class: #4EC9B0;
        --number: #B5CEA8;
        --string: #CE9178;
        --parenthesis-unmatch: #B51819;
        --parenthesis-0: #FFD705;
        --parenthesis-1: #D45DBA;
        --parenthesis-2: #1A9FFF;
        --comment: #549952;
    }

    .pyscript-code span#default {
        color: var(--default);
    }

    .pyscript-code span#keyword {
        color: var(--keyword);
    }

    .pyscript-code span#keyword-identifier {
        color: var(--keyword-identifier);
    }

    .pyscript-code span#identifier {
        color: var(--identifier);
    }

    .pyscript-code span#identifier-const {
        color: var(--identifier-const);
    }

    .pyscript-code span#identifier-call {
        color: var(--identifier-call);
    }

    .pyscript-code span#identifier-class {
        color: var(--identifier-class);
    }

    .pyscript-code span#number {
        color: var(--number);
    }

    .pyscript-code span#string {
        color: var(--string);
    }

    .pyscript-code span#parenthesis-unmatch {
        color: var(--parenthesis-unmatch);
    }

    .pyscript-code span#parenthesis-0 {
        color: var(--parenthesis-0);
    }

    .pyscript-code span#parenthesis-1 {
        color: var(--parenthesis-1);
    }

    .pyscript-code span#parenthesis-2 {
        color: var(--parenthesis-2);
    }

    .pyscript-code span#comment {
        color: var(--comment);
    }
</style>
