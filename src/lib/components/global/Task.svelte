<!-- <script>
    import Box from "./Box.svelte";
</script>

<style>
    .taskcard1{
        width: 85%;
        height: 20px;
        margin-top: 10px;
        border-radius: 10px;
        border: solid;
    }

    .taskcard {
        width: auto;
        border-radius: 10px;
    }

</style>

<div class="taskcard">

</div> -->


<!-- CenteredBox.svelte -->

<style>
    .centered-box {
        display: flex;
        align-items: center;
        width: 80%;
        height: 75px;
        background-color: #f0f0f0;
        border-radius: 10px;
        padding: 10px;
        margin-top: 15px;
        border: solid;
        border-radius: 10px;
        justify-content: space-between;
    }

    .text {
        margin-right: 10px;
    }

    .button {
        width: 70px;
        height: 30px;
        background-color: #007bff;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        margin: 5px;
    }

    .containerbutton{
        width: 250px;
        height: fit-content;
        justify-content: flex-end;
    }
</style>

<script>
    export let buttonText1 = "Button 1";
    export let buttonText2 = "Button 2";
    export let buttonText3 = "Button 3";
</script>

<div class="centered-box">
    <h1 class="text">Makan malam</h1>
    <button class="button">{buttonText1}</button>
    <button class="button">{buttonText2}</button>
    <button class="button">{buttonText3}</button>
</div>
