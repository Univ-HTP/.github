<div align="center">

  <img src="https://raw.githubusercontent.com/Univ-HTP/.github/main/profile/logo-uhtp.png" alt="Universitas Hang Tuah Pekanbaru" width="130" />

  <br><br>

  <h1>Universitas Hang Tuah Pekanbaru</h1>

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=0284C7&center=true&vCenter=true&width=650&lines=Pusat+Teknologi+Informasi+%26+Transformasi+Digital;Building+Integrated+Campus+Ecosystem;Sinergi+Unggul+Kesehatan+%26+Teknologi;Menuju+Kampus+Berdaya+Saing+Asia+Tenggara+2036" alt="Typing Banner" />

  <p>
    Pekanbaru, Riau, Indonesia &nbsp;|&nbsp; <a href="https://htp.ac.id" target="_blank">htp.ac.id</a>
  </p>

  <p>
    <a href="https://htp.ac.id"><img src="https://img.shields.io/badge/Institusi-Universitas_Hang_Tuah_Pekanbaru-0f172a?style=flat-square&logo=googlemaps&logoColor=white" alt="Institusi" /></a>
    <img src="https://img.shields.io/badge/Infrastruktur-Hybrid_Dedicated_%26_Cloud-0369a1?style=flat-square&logo=linux&logoColor=white" alt="Infrastruktur" />
    <img src="https://img.shields.io/badge/Containerization-Docker_Microservices-0284c7?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Repository-Private_%26_Internal_Governance-334155?style=flat-square&logo=github&logoColor=white" alt="Repository Access" />
  </p>

</div>

---

### Profil Organisasi

Organisasi GitHub **Univ-HTP** merupakan pusat pengembangan perangkat lunak, otomatisasi CI/CD, dan repositori teknologi resmi di bawah pengelolaan tim Teknologi Informasi dan Komunikasi (TIK) **Universitas Hang Tuah Pekanbaru**.

Universitas Hang Tuah Pekanbaru (UHTP) hadir sebagai wujud sinergi penggabungan institusi pendidikan tinggi bidang Kesehatan dan Teknologi Informasi. Organisasi ini didedikasikan untuk membangun dan memelihara seluruh arsitektur sistem informasi institusi yang reliabel, skalabel, serta menjamin integritas data akademik dan riset.

---

### Ekosistem Digital & Sistem Layanan

Repositori kode sumber sistem produksi di bawah organisasi ini dikelola secara privat untuk menjaga privasi data civitas akademika dan kepatuhan keamanan institusi. Berikut adalah layanan utama yang aktif dikembangkan dan dioperasikan:

| Layanan / Sistem | Deskripsi Fungsional | Status Operasional | Pilar Teknologi |
| :--- | :--- | :---: | :--- |
| **Data Center & SKI** | Platform pengumpulan instrumen survei kesehatan, analisis data lapangan terpusat, dan integrasi pelaporan data kesehatan. | [survey.htp.ac.id](https://survey.htp.ac.id)<br>`Production` | TypeScript, React / Next.js, Django REST Framework, Docker |
| **GIS Data Center** | Sistem Informasi Geografis spasial untuk analisis sebaran kesehatan, demografi, dan fasilitas medis regional Riau. | [gis.htp.ac.id](https://gis.htp.ac.id)<br>`Production` | PostGIS, Martin Vector Tile Server, Django Geo, Docker Compose |
| **OBE Curriculum System** | Sistem tata kelola kurikulum berbasis *Outcome-Based Education*, asesmen CPL (Capaian Pembelajaran Lulusan), dan evaluasi CPMK. | `Internal Network`<br>`Active Development` | PHP, Laravel, TypeScript, MySQL |
| **Portal Akademik & PMB** | Layanan admisi terpadu penerimaan mahasiswa baru, informasi program studi, dan administrasi akademik universitas. | [htp.ac.id](https://htp.ac.id)<br>`Production` | PHP / Laravel, Web Engine, aaPanel Reverse Proxy |

---

### Arsitektur & Teknologi

Pengembangan sistem di lingkungan Universitas Hang Tuah Pekanbaru mengadopsi standar arsitektur modern yang memisahkan lapisan data, layanan backend, dan antarmuka pengguna:

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,php,laravel,react,nextjs,tailwind,postgres,mysql,docker,linux,git,github&theme=dark" alt="Technology Stack" />
</div>

<br>

<table width="100%">
  <thead>
    <tr>
      <th width="50%" align="left">Komponen Infrastruktur & Backend</th>
      <th width="50%" align="left">Antarmuka & Lingkungan Operasional</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <ul>
          <li><b>Bahasa Pemrograman:</b> Python, TypeScript, PHP, SQL</li>
          <li><b>Framework Backend:</b> Django REST Framework, Laravel, Node.js</li>
          <li><b>Basis Data Spasial & Relasional:</b> PostgreSQL / PostGIS, MySQL</li>
          <li><b>Vector & Map Engine:</b> Martin Tile Server, GeoDjango, PostGIS Functions</li>
        </ul>
      </td>
      <td valign="top">
        <ul>
          <li><b>Framework Frontend:</b> React, Next.js, Blade Engine</li>
          <li><b>Desain Antarmuka:</b> Tailwind CSS, Responsive Web Design</li>
          <li><b>Server Operasional:</b> Dedicated Node (Debian 12 x86_64)</li>
          <li><b>Web Server & Gateway:</b> Apache 2.4 (aaPanel), Nginx Reverse Proxy, Docker Engine</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

### Tata Kelola Repositori & Keamanan

Seluruh repositori sistem internal diatur dengan standar operasional ketat:

1. **Akses Terbatas:** Akses modifikasi repositori hanya diberikan kepada staf dan tim pengembang resmi TIK Universitas Hang Tuah Pekanbaru.
2. **Proteksi Branch & CI/CD:** Setiap perubahan kode pada cabang utama (`main`) wajib melalui proses *code review* dan verifikasi *health check* sebelum diintegrasikan ke server produksi.
3. **Perlindungan Data:** Konfigurasi kredensial, kunci rahasia (*secret keys*), dan basis data produksi diisolasi melalui manajemen variabel lingkungan terenkripsi.

---

### Informasi Kontak & Kampus

* **Alamat Kampus Utama:** Jl. Mustafa Sari No. 5, Tangkerang Selatan, Pekanbaru, Riau 28282
* **Website Resmi:** [https://htp.ac.id](https://htp.ac.id)
* **Layanan Informasi:** [info@htp.ac.id](mailto:info@htp.ac.id)

<br>

<div align="center">
  <sub>Hak Cipta &copy; 2026 Universitas Hang Tuah Pekanbaru. Seluruh hak cipta dilindungi undang-undang.</sub>
</div>
