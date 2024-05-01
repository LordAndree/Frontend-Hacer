<script>
  export let color;

  import Container from "./Container.svelte";
  import Box from "./Box.svelte";
  import Task from "./Task.svelte";
  import Sidebar from "./Sidebar.svelte";
</script>

<div class="title-brand">
    <h1>HACER !</h1>
</div>
<div class="container-wrapper">
  <Sidebar></Sidebar>
  <div class="containeruji">
    <Task></Task>
    <br><br>
    <button class="add-button">+</button>
  </div>
</div>

<style>
  .container-wrapper {
    display: flex;
    padding-left: 50px;
    padding-right: 50px;
    z-index: 11;
    padding-top: 20px;
  }

  .containeruji {
    width: 1300px;
    height: fit-content;
    background-color: #ffffff;
    border-radius: 10px;
    padding: 20px;
    margin-left: 50px; /* Menggeser container ke kanan */
    position: relative;
    padding-right: 20px;
    padding-left: 20px;
    padding-bottom: 2%;
    margin-bottom: 20px;
  }

  .add-button {
    background-color: #007bff; /* Warna latar belakang */
    color: white; /* Warna teks */
    border: none; /* Hapus border */
    border-radius: 50%; /* Atur border-radius */
    width: 40px; /* Ukuran lebar */
    height: 40px; /* Ukuran tinggi */
    font-size: 16px; /* Ukuran teks */
    bottom: 10px; /* Atur jarak dari bawah */
    right: 10px; /* Atur jarak dari kanan */
    position: absolute; /* Tetapkan posisi absolut */
  }

  .add-button:hover {
    background-color: #0056b3; /* Warna latar belakang saat hover */
  }

  .title-brand {
    text-align: center; /* Mengatur agar teks berada di tengah */
    padding-top: 20px;
}

.title-brand h1 {
    color: white; /* Mengatur warna teks menjadi putih */
    font-weight: 800;
    font-size: 24px;
}
</style>
