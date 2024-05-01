<style>
    @import '../../css/stye.css';

    .container-main {
        display: flex;
        flex-direction: column;
        position: relative; /* Tambahkan posisi relatif untuk container */
    }

    .centered-box-container {
        display: flex;
        flex-direction: column;
    }

    .centered-box {
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 100%;
        height: auto;
        background-color: #E2E7FA;
        border-radius: 10px;
        padding: 10px;
        margin-top: 15px;
        margin-bottom: 15px;
    }

    hr {
        border: solid;
        height: 3px;
        background-color: #000000;
        margin: 10px 0;
        width: 100%;
    }

    .title-todo {
        font-weight: var(--fwmedium);
        color: #000000;
        font-size: 16px;
        margin: 10px 5px -15px;
        align-self: flex-start;
    }

    .deskripsi-todo {
        margin-top: 20px;
    }

    .badge {
        display: flex;
        align-items: center;
        background-color: #dc3545;
        color: white;
        padding: 5px 10px;
        border-radius: 5px;
        margin-top: 10px;
        margin-right: auto;
    }

    .badge i {
        margin-right: 5px;
    }

    .schedule {
        font-weight: 600;
        font-size: 20px;
        color: #000000;
    }

    .menu-icon {
        margin-left: auto; /* Posisikan menu icon di sebelah kanan */
        color: #007bff; /* Warna icon */
        cursor: pointer; /* Tambahkan cursor pointer */
        font-size: 16px; /* Ukuran icon */
        position: relative; /* Tambahkan posisi relatif */
    }

    .menu-icon:hover {
        color: #0056b3; /* Warna icon saat hover */
    }
</style>

<div class="container-main">
    <div class="centered-box-container">
        <h1 class="schedule">Schedule Today</h1>
        <div class="centered-box">
            <h1 class="title-todo">Makan Siang</h1>
            <i class="menu-icon fas fa-bars"></i>
            <hr>
            <p class="deskripsi-todo">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa neque expedita quia earum nostrum autem nam totam beatae, rerum esse? Placeat, illum ex in corrupti iste eaque enim totam tempora.</p>
            <div class="badge">
                <i class="fa fa-exclamation-triangle"></i> Urgent
            </div>
        </div>

        <div class="centered-box">
            <h1 class="title-todo">Makan Malam</h1>
            <i class="menu-icon fas fa-bars"></i>
            <hr>
            <p class="deskripsi-todo">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa neque expedita quia earum nostrum autem nam totam beatae, rerum esse? Placeat, illum ex in corrupti iste eaque enim totam tempora.</p>
            <div class="badge">
                <i class="fa fa-exclamation-triangle"></i> Urgent
            </div>
        </div>
        <div class="centered-box">
            <h1 class="title-todo">Fitnes</h1>
            <i class="menu-icon fas fa-bars"></i>
            <hr>
            <p class="deskripsi-todo">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa neque expedita quia earum nostrum autem nam totam beatae, rerum esse? Placeat, illum ex in corrupti iste eaque enim totam tempora.</p>
            <div class="badge">
                <i class="fa fa-exclamation-triangle"></i> Urgent
            </div>
        </div>
    </div>
</div>
