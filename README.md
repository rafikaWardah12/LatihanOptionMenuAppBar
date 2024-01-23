# Latihan Option Menu AppBar
Project ini merupakan latihan untuk membuat option menu appbar. Selain itu juga menerapkan fitur untuk searchBar dan SearchView. Fitur ini akan muncul ketika Menu 2 dipilih yang merupakan menu pilihan pada Main App. Bahasa yang digunakan yaitu kotlin dengan XML

## Implementasi
1. Membuat Option Menu
2. Menambahkan aksi saat Option Menu
3. Menambahkan SearchBar dan SearchView

## What I Learn
1. **android:icon** = mengganti icon
2. 5 kondisi pada tag **app:showAsAction:**
    * ifRoom = menampilkan action ketika ada ruangan pada AppBar
    * withText = menampilkan actionitem beserta judulnya
    * never = tidak akan pernah ditampilkan pada AppBar dan hanya akan ditampilkan pada overflow menu
    * always = selalu tampil pada AppBar
    * collapseActionView = berhubungan dengan komponen collapsible
3. **CoordinatorLayout** = ViewGroup untuk mengatur interaksi antar elemen view
4. **AppBarLayout** = ViewGroup untuk bahan atas dari tampilan
5. **MaterialToolBar** = komponen untuk menampilkan judul, ikon untuk aksi, dan menu
6. **NestedScrollView** = subClass dari *ScrollView* sehingga dapat scrolling page
7. Menggunakan percabangan dengan *switch* sehingga dapat diberikan listener untuk setiap item
     * *Contoh ketika id berada pada:*
       *  R.id.menu1 = fragment pada R.id.fragment_container diganti dengan fragment baru yaitu MenuFragment
       *  R.id.menu2 = menjalankan activity baru yaitu MenuActivity
8. SearchBar = ekstensi dari ToolBar yang khusus untuk menu pencarian
