<script>
    let userName = "Prabowo Subianto";
    let taskname = "Dummy 1";

    // import buttonIcon1 from '$lib/assets/images/rizki.png';
    // import buttonIcon2 from '../../public/assets/images/rizki.png';
    // import buttonIcon3 from '../../public/assets/images/rizki.png';
    // import buttonIcon2 from './assets/button-icon-2.png';
    // import buttonIcon3 from './assets/button-icon-3.png';
</script>

<html lang="eng">
    <body>
        <div class="judul">HACER!</div>
        <div class="containeruji">
            <div class="sidebar">
                <div class="greeting">Hello, {userName}</div>
                <button class="buttonsidebar">Home</button>
                <button class="buttonsidebar">Profile</button>
            </div>
            <div class="content">
                <!-- Isi konten lainnya di sini -->
                <div>
                    <h1 style="align-self: center;">Hello User</h1>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Hic nobis distinctio non unde nemo quas doloremque exercitationem excepturi corrupti optio. Animi consectetur reiciendis doloribus error rerum eaque sequi sit voluptatibus?</p>
                    <div class="containertask1">
                        <h2>{taskname}</h2>
                            <!-- Tombol 1 -->
                            <img src="/assets/images/check-symbol.png" alt="Button 1" class="buttontask" />
                            <!-- <img src="" alt=""> -->
                            <!-- Tombol 2 -->
                            <!-- <img src={buttonIcon2} alt="Button 2" class="option-button" /> -->
                            <!-- Tombol 3 -->
                            <!-- <img src={buttonIcon3} alt="Button 3" class="option-button" /> -->
                        <h2>testt</h2>
                    </div>

                    <div class="containertask2">
                        <p>Description of the task</p>
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>