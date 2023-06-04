<template>
  <div>
    <!-- halaman header -->
    <header>
      <div class="user">
        <img src="../assets/gambar1.jpg" alt="" />
        <h3 class="nama">Hidayatullah</h3>
        <p class="tentang">Mahasiswa</p>
      </div>

      <nav class="navbar">
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About Me</a></li>
          <li><a href="#education">Pendidikan</a></li>
          <li><a href="#projects">Project</a></li>
          <li><a href="#contact">Hubungi Saya</a></li>
        </ul>
      </nav>
    </header>

    <div id="menu" class="fa fa-bars"></div>

    <section class="home" id="home">
      <h3>HALO !!</h3>
      <h1>Namaku <span>Hidayatullah</span></h1>
      <p>
        Saya seorang mahasiswa semester 6 dengan prodi Pendidikan Teknik
        Informatika dan Komputer di Universitas Negeri Makassar. Sedang
        menjalani kegiatan sehari-hari dengan mengikuti Studi Independen
        dibarengi dengan kuliah. Saya merupakan mahasiswa yang antusias, aktif,
        dan bermotivasi tinggi dengan kemampuan kerjasama, inisiatif, dan suka
        mencari tantangan baru
      </p>
      <a href="#about">
        <button class="btn">About Me <i class="fas fa-user"></i></button>
      </a>
    </section>

    <section class="about" id="about">
      <h1 class="heading"><span>About</span> Me</h1>

      <div class="row">
        <div class="info">
          <h3><span>Nama:</span> Hidayatullah</h3>
          <h3><span>Umur:</span> 21 Tahun</h3>
          <h3><span>Alamat:</span> Kota Makassar, Provinsi Sulawesi Selatan</h3>
          <h3><span>Hobi:</span> Bermain Game, Coding, dan Memasak</h3>
          <h3><span>Asal Kampus:</span> Universitas Negeri Makassar</h3>
          <a
            href="https://drive.google.com/file/d/1jH1Zmftvp2r7Tf8yVTHZIuJRW2230V30/view?usp=share_link"
            target="_blank"
            rel="noopener noreferrer"
          >
            <button class="btn">
              Download CV <i class="fas fa-download"></i>
            </button>
          </a>
        </div>
      </div>
    </section>

    <section class="education" id="education">
      <h1 class="heading"><span>Pendidikan</span></h1>

      <div class="box-container">
        <div class="box">
          <i class="fas fa-graduation-cap"></i>
          <span>2017-2022</span>
          <h3>SMK Negeri 3 Bantaeng</h3>
        </div>

        <div class="box">
          <i class="fas fa-graduation-cap"></i>
          <span>2020-Sekarang</span>
          <h3>Universitas Negeri Makassar</h3>
        </div>
      </div>
    </section>

    <section class="projects" id="projects">
      <h1 class="heading"><span>Portofolio Project</span></h1>

      <div class="row2">
        <div class="info1">
          <img
            src="../assets/gambar2.jpeg"
            alt="Deskripsi gambar"
            width="150"
            height="150"
          />
          <h3><span>1.</span> Membuat Website Toko Online</h3>
          <router-link to="/project">
            <button class="btn">
              Detail Project <i class="fas fa-info"></i>
            </button>
          </router-link>
        </div>
      </div>

      <div class="row2">
        <div class="info1">
          <img
            src="../assets/gambar3.jpeg"
            alt="Deskripsi gambar"
            width="150"
            height="150"
          />
          <h3><span>2.</span> Membuat Website Club Motor</h3>
          <router-link to="/project2">
            <button class="btn">
              Detail Project <i class="fas fa-info"></i>
            </button>
          </router-link>
        </div>
      </div>

      <div class="row2">
        <div class="info1">
          <img
            src="../assets/gambar4.jpeg"
            alt="Deskripsi gambar"
            width="150"
            height="150"
          />
          <h3>
            <span>3.</span> Membuat Aplikasi Pendeteksi Kematangan Cabe
            Menggunakan Aplikasi Matlab
          </h3>
          <router-link to="/project3">
            <button class="btn">
              Detail Project <i class="fas fa-info"></i>
            </button>
          </router-link>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h1 class="heading"><span>Hubungi</span> Saya</h1>
      <div class="row">
        <div class="content">
          <h3 class="title">Info Kontak</h3>

          <div class="info">
            <h3>
              <i class="fas fa-envelope"></i> daya.hidayatullah024@gmail.com
            </h3>
            <h3><i class="fas fa-phone"></i> 082348050512</h3>
            <h3>
              <i class="fas fa-map-marked-alt"></i> Kota Makassar, Provinsi
              Sulawesi Selatan
            </h3>
          </div>
        </div>

        <form>
          <input type="text" class="box" placeholder="Nama" />
          <input type="email" class="box" placeholder="Email" />
          <textarea
            name=""
            id=""
            cols="30"
            rows="10"
            class="box message"
            placeholder="Pesan"
          ></textarea>
          <button type="submit" class="btn">
            Kirim <i class="fas fa-paper-plane"></i>
          </button>
        </form>
      </div>
    </section>
    <a href="#home" class="top">
      <img src="../assets/scroll.png" alt="" />
    </a>
  </div>
</template>

<script>
export default {
  name: "Master",
};
</script>
