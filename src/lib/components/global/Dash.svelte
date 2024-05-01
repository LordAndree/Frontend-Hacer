<script>
    export let color;
    
    import Container from "./Container.svelte";
    import Box from "./Box.svelte";
    import Task from "./Task.svelte";
</script>
<style>
.containeruji {
    display: flex;
    flex-direction: row;
    /* height: 70vh; */
    width: 50%;
    height: auto;
    border: solid;
    margin: auto;
    height: 50%;
    border-radius: 10px;
    justify-content: center;
}
.sidebar {
    width: 15%;
    background-color: #f0f0f0;
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    /* align-items: center; */
}
.buttonsidebar {
    width: 100%; /* Atur lebar tombol sebagai 15% dari lebar kontainer */
    height: 50px; /* Atur tinggi tombol sesuai kebutuhan */
    margin-bottom: 20px; /* Jarak antara tombol */
}

</style>


<div class="containeruji">
 <Task></Task>
</div>
