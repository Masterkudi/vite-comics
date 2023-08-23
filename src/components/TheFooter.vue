<script>
export default {

}

</script>

<template>
    <footer>
        <div class="menu-bar">
            <div class="menu-column">
                <div class="d-flex">
                    <div>
                        <h4>DC COMICS</h4>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <h4>SHOP</h4>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <div>
                        <h4>DC</h4>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                    <div>
                        <h4>SITES</h4>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
            </div>
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
    overflow: hidden;
    justify-content: space-around;
    position: relative;
    max-height: 400px;
}

.menu-bar img {
    height: 620px;
    align-self: center;
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

.menu-column {
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
}
.menu-column div {
    padding: 2rem;
}
.menu-column li {
    text-align: start;
    list-style: none;
    color: #959595;
}
.menu-column ul {
    padding-left: 0;
}

</style>
  