- 👋 Hi, I’m @itutores
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
itutores/itutores is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## Panduan Penggunaan Template Bio Link Tool

Cek Demo [Disini](https://itutores.github.io/)


1. Ganti elemen dibawah pada file [index.html](index.html) dengan namamu sendiri.
  ```HTML
  <title>@Your Username</title>
  ```
2. Ubah foto dari avatar dan username pada file [index.html](index.html) dengan avatar juga username milikmu.
  ```HTML
    <div class="header">
        <div class="avatar">
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhH2JpircVxwSLSyrtefjGi7ZaYlnAlIjM4F3QRJqCLaSabuiTotMwR3JWhUFywDx2UJjvZAYH0Dz8Vbcq0q638czdnPaYgkldeufzLbEdEYu9er464hnKPdvjDEhXGuZ1Ck-a43q-07NfnPv6TpeSOhXdX2HfxXLtdQw0i5nmGk3nHmZxuR4AHx2B7qko3/s320-rw/Profile%20itutores.jpg" alt="" />
        </div>
        <div class="username">
          <h3>itutores.com</h3>
        </div>
    </div>
  ```

3. Sesuaikan penggunaan long button dengan kebutuhan pada file [index.html](index.html)
  ```HTML
  <div class="long-button">
      <a
        href=""
        target="_blank"
        class="long-btn"
      >
      Content Long Button
      </a>
    </div>
  ```

4. Gunakan social button dengan syntaks:
  ```HTML
    <li class="instagram">
      <a href="" 
      target="_blank"
      class="fab fa-twitch"
      ></a>
    </li>
  ```
  Tukar class li dengan nama social media juga a class mengikuti syntaks `fab fa-(nama social media)`

  untuk hasil yang responsive, penggunaan social button maksimal 8 Item.

  Warna social media yang tersedia bisa dilihat pada file [Sbutton.css](Style/Sbutton.css)
  dapat ditambahkan dengan syntaks:
  ```CSS
  .circle ul li .fa-(nama social media):hover {
  color: #(warna social media);
  }
  ```
