<script>
export default {

}

</script>

<template>
    <footer>
        <div class="menu-bar">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque porro ea dolores nemo optio magnam rerum
            consequatur iusto illo quisquam tempora, assumenda ad libero nulla, odio officiis ducimus eveniet. Quaerat.
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>

        <div class="social-bar">
            <button>
                SIGN-UP NOW!
            </button>
            <div class="social-icons">
                <h4>FOLLOW US</h4>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </footer>
</template>
  
<style scoped>
.menu-bar {
    background-image: url(../assets/img/footer-bg.jpg);
    color: #fff;
    display: flex;
    position: relative;
    justify-content: flex-end;
    max-height: 500px;
}

.menu-bar img {
    overflow: hidden;
}

.social-bar {
    background-color: #303030;
    padding: 3rem;
    display: flex;
    justify-content: space-between;

}

.social-bar h4 {
    display: flex;
    align-items: center;
    color: #0088FF;
}

.social-bar button {
    display: flex;
    align-items: center;
    background-color: #303030;
    color: #fff;
    padding: .7rem;
    border-color: #0088FF;
}

.social-icons {
    display: flex;
    justify-content: space-between;
}
.social-icons h4 {
    padding: .5rem;
    margin-bottom: 0;
}
.social-icons img {
    padding: .5rem;
}

</style>
  