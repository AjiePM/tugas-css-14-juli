<h1> tugas-css-14-juli </h1>
<h1>css</h1>
<P>digunakan mendisain halaman web</p> 
<i>( bisa kita ungkapkan) </i> <b> seperti HTML yang hanya memiliki Tulang-berulang namun di berikan tubuh dan pakaian kepada tulang tersebut yang biasa di sebut CSS

<h1>strukutr css</h1>
<p>.elementHTML {
    property :value
}

- <i> selektor, property dan valur</i>

contoh : h1 {color : red ;}
 <p> h1 : (Selector), color : (property), red :(value)

- <p> (<b>propperty terdiri dari color font dll</b>) <i>sedangkan</i> (value terdiri dari anngka,merah dll)

<h1> 3 cara menggunakan CSS </h1>
<p>1. inline style :kita menambahkan css ke pada atribut html
<p>conrohnya:</p>

<p> style="color: red; font-size:12px

- inline  style berada di paragrap
<p>2. internal :cara menambahkan CSS dengan menggunakan tag style di dalam tag head </p>
<p>conrohnya:</p>
 <html>
<head>

	<style type="text/css">
	</style>
</head>
</body>
</html>
3. Eksternal <p>cara menambahkan CSS dengan menggunakan tag link</p>
<p>conrohnya:</p>

- link rel="stylesheet" type="text/css" href="style.css">
	
<h1> css class name</h3>
<p> digunakan lebih dari 1 kelas</p>

- id dan class :sama sama bisa digunhakan dalam css namun perbedaaan <i> jika id : hanya berfokus pada 1 value</i> sedangkan <i>Class :bisa melebihi 1 value</i>
- id secara penulisan tidak boleh lebi dari 1 elemen kecuali id dengan value yang berbeda
-yang paling di prioritaskan ketika ada kelas( id, class, tag html)

<h1> !important CSS</h1>
<p>dapat memaksa style yang harus di jalankan </p>
contoh

- h1 {

    color : red !important

    }

<i>maka style title akan override dengan style tag h1 karena menggunakan !important </i>

   - h1.title {

        color : yellow;
    }
