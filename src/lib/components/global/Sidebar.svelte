<div class="sidebar">
  <!-- Tombol Home dengan ikon Font Awesome -->
  <button class="buttonsidebar">
    <i class="fas fa-home"></i> Home
  </button>
  <!-- Tombol Profile dengan ikon Font Awesome -->
  <button class="buttonsidebar">
    <i class="fas fa-user"></i> Profile
  </button>
  <button class="buttonsidebar">
    <i class="fas fa-sign-out-alt"></i> Logout
  </button>
</div>

<style>
  @import "../../css/stye.css";

  .sidebar {
    width: 280px;
    height: 800px;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 20px;
    border-radius: 10px;
  }

  .buttonsidebar {
    width: 260px;
    height: 62px;
    margin-bottom: 20px;
    background-color: #e2e7fa;
    border-radius: 10px;
    border: 0;
    border-left: 20px;
    margin-left: -10px; /* Tambahkan margin kiri */
    display: flex;
    align-items: center;
    padding-left: 10px; /* Tambahkan padding kiri untuk memberi ruang bagi ikon */
  }

  .buttonsidebar i {
    margin-right: 10px; /* Beri ruang di antara ikon dan teks */
  }

  /* Menambahkan garis atas di bawah tombol Profile */
  .buttonsidebar:nth-child(2) {
    border-top: 1px solid #ccc;
  }

  /* Menyesuaikan posisi tombol Logout */
  .buttonsidebar:last-child {
    margin-top: auto; /* Tombol Logout akan berada di bawah profil dan mendekati batas panjang container */
  }
</style>
