<template>
    <div class="container">
  <div style="text-align:center">
    <h2>Kontak Kami</h2>
    <p>Mampir untuk membeli sepatu, atau tinggalkan pesan kepada kami:</p>
  </div>
  <div class="row">
    <div class="column">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d247.50609824414173!2d107.59958700778606!3d-6.997789971662415!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e68e9da933de21f%3A0x82a2073ba7e3298e!2sHerbal%20Victory!5e0!3m2!1sen!2sid!4v1690423354566!5m2!1sen!2sid" width="700" height="500" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="fname">Nama</label>
        <input type="text" id="fname" name="firstname" placeholder="Masukan Nama..">
        <label for="lname">Email</label>
        <input type="text" id="lname" name="lastname" placeholder="Masukan Email..">
        <label for="Kota">Kota</label>
        <select id="Kota" name="Kota">
          <option value="Bandung">Bandung</option>
          <option value="Jakarta">Jakarta</option>
          <option value="Solo">Solo</option>
        </select>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:100px"></textarea>
       <center><input type="submit" value="Submit"></center> 
      </form>
    </div>
  </div>
</div>
</template>

<style>
* {
  box-sizing: border-box;
}

/* Style inputs */
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

/* Style the container/contact section */
.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}


/* Create two columns that float next to eachother */
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}
.row .map {
  flex: 1 1 45rem;
  width: 100%;
  object-fit: cover;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>