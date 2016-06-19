---
layout: post
---

<img src="/images/fulls/03.jpg" class="fit image">
<html manifest="cache.manifest">
<body>
<div id="result"></div>
<script>
if(typeof(Storage)!=="undefined")
  {
  localStorage.keterangan="<p>Github Pages ini merupakan tugas kelompok dari mata kuliah Application Mobile .Kelompok kami beranggotakan 5 orang ,yaitu : Gita Adryana, Nursaleha, R.Recha Astari, Wetenrisoi Hafsa, dan Yulisa Rosliana .Github pages ini menggunakan thema jekyll, dan tulisan ini disimpan di local storage browser.Di bawah ini kami akan menampilkan beberapa multimedia berupa lagu yang kualitasnya berbeda-beda.</p>";
  document.getElementById("result").innerHTML="" + localStorage.keterangan;
  }
else
  {
  document.getElementById("result").innerHTML="Sorry, your browser does not support web storage...";
  }
</script>

