<div class="header">
  <h2>Radja's Blog</h2>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>UBUNTU</h2>
      <h5>Penjelasan Tentang Ubuntu, Oct 25, 2022</h5>
      <div class="fakeimg" style="height: 300px;"><img src="https://w7.pngwing.com/pngs/193/622/png-transparent-logo-ubuntu-friends-help-ubuntu-extension-logo-love-free-logo-design-template-orange-thumbnail.png" alt="ubuntu"></div>
      <p>Ubuntu adalah sebuah sistem operasi berbasis Linux yang kaya fitur. Sistem operasi Ubuntu bersifat open source sehingga bisa digunakan secara gratis.</p>
    </div>
    <div class="card">
      <h2>MANJARO</h2>
      <h5>Penjelasan Tentang Manjaro, Oct 25, 2022</h5>
      <div class="fakeimg" style="height:200px;"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Manjaro-logo.svg/384px-Manjaro-logo.svg.png?20210414143234 1.5x, https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Manjaro-logo.svg/512px-Manjaro-logo.svg.png?20210414143234 2x"" alt="manjaro"></div>
      <p>Manjaro adalah salah satu distribusi linux yang dikembangkan secara independen berdasarkan sistem operasi Arch, Arch sendiri dikenal sebagai distribusi yang cepat ringan dan juga handal. hanya saja Arch ini lebih ditunjukan kepada pengguna yang sudah berpengalaman dalam mengoperasikan sistem operasi linux.</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>hanya seseorang biasa yang mencintaimu</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>kamu boleh namai itu rumah selama ada orang yang kau cinta didalamnya.</p>
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
          <p><a href="https://instagram.com/teukuradjasha" class="fa fa-instagram">teukuradjasha</a></p> 
    </div>
  </div>
</div>

<div class="footer">
  <h2>Have a good luck.</h2>
</div>





<!---CSS--->





<style>
  * {
box-sizing: border-box;
}

body {
font-family: Arial;
padding: 20px;
background: #81a127;
}

/* Header/Blog Title */
.header {
padding: 30px;
font-size: 40px;
text-align: center;
background: rgb(16, 224, 8);
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {
float: left;
width: 75%;
}

/* Right column */
.rightcolumn {
float: left;
width: 25%;
padding-left: 20px;
}

/* Fake image */
.fakeimg {
background-color: rgb(136, 231, 223);
width: 25%;
padding: 20px;
}

/* Add a card effect for articles */
.card {
background-color: white;
padding: 20px;
margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
content: "";
display: table;
clear: both;
}

/* Footer */
.footer {
padding: 20px;
text-align: center;
background: #ddd;
margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
.leftcolumn, .rightcolumn {
  width: 100%;
  padding: 0;
}
}
</style>