<template>
    <div class="box-home">
        <div class="box-img-home">
            <div class="d-flex flex-column mb-3">
                <h1 class="first-title">
                    <span class="red-letter">T</span>uk Tuk
                </h1>
                <p class="second-title-home">asian streetfood</p>
            </div>
        </div>
    </div>
    <!-- 2eme partie -->
    <div class="box-second">
        <div class="box-img-second">
            <div class="box-second-container">
                <div class="box-second-info-1">
                    <div class="box-info-2">
                        <h1 class="second-title">
                            <span class="red-letter">T</span>uk Tuk
                        </h1>
                        <p class="title-2">asian streetfood</p>
                    </div>
                    <div class="box-info-text">
                        <p>
                            Vous n'avez pas encore gouté nos plat ? Alors
                            n'hésitez plus tout nos plats sont fait maison !
                            Rien de mieux pour bien manger et vous satisfaire !
                            Vous pouvez retrouver comme plat :
                        </p>
                        <ul>
                            <li>Nems</li>
                            <li>Samoussa</li>
                            <li>Boeuf sauté</li>
                            <li>Pad thaï</li>
                        </ul>
                        <p>
                            Et bien d'autre plat n'hésitez pas a consulter notre
                            carte !
                        </p>
                    </div>
                </div>
                <div class="box-info-img"></div>
            </div>
        </div>
    </div>

    <!-- 3eme partie -->

    <div class="box-three-img">
        <div class="plat">
            <img
                class="img-plat"
                src="../assets/plat_camion1.jpg"
                alt="plat1"
            />
            <p>Boeuf sauté</p>
        </div>
        <div class="plat">
            <img
                class="img-plat"
                src="../assets/plat_camion2.jpg"
                alt="plat2"
            />
            <p>Nems</p>
        </div>
        <div class="plat">
            <img
                class="img-plat"
                src="../assets/plat_camion3.jpg"
                alt="plat3"
            />
            <p>Nouille sauté</p>
        </div>
    </div>

    <!-- 4eme partie -->

    <div class="box-four-img">
        <p>Venez deguster nos délicieux plat !</p>
    </div>

    <!-- 5eme partie -->
    <div class="box-five-img">
        <div class="box-five-info">
            <h1 class="second-title">
                <span class="red-letter">T</span>uk Tuk
            </h1>
            <p class="title-2">asian streetfood</p>
        </div>
        <div class="box-carte">
            <div class="specialite">
                <h4>SPÉCIALITÉS</h4>
                <p><span class="red-letter">P</span>ad Thaï ....8€</p>
                <p class="description">
                    Nouilles de riz , poulet, oignon, œuf, cacahuète, bœuf,
                    soja, coriandre
                </p>
                <p><span class="red-letter">B</span>obun ....8€</p>
                <p class="description">
                    Salade, vermicelle, carotte, soja, cacahuète, bœuf, nems et
                    menthe
                </p>
                <p><span class="red-letter">R</span>iz Thaï ....8€</p>
                <p>
                    <span class="red-letter">B</span>rochette Yakitori +
                    <span class="red-letter">R</span>iz ....8€
                </p>
                <p>
                    <span class="red-letter">R</span>amene +
                    <span class="red-letter">S</span>oja ....8€
                </p>
            </div>
            <div class="accompagnements">
                <h4>ACCOMPAGNEMENTS</h4>
                <p><span class="red-letter">N</span>ems x6 ....8€</p>
                <p><span class="red-letter">S</span>amosas x6 ....8€</p>
                <p><span class="red-letter">G</span>yosa x6 ....8€</p>
                <p><span class="red-letter">B</span>oissons ....8€</p>
            </div>
        </div>
    </div>

    <!-- 6eme partie -->

    <div class="box-six-img">
        <div class="box-six-info">
            <h3>Contactez-nous</h3>
            <p>N'hésitez a nous contactez pour plus d'information</p>
            <p>
                <img
                    src="https://img.icons8.com/ios-filled/20/null/phone.png"
                />
                07 83 00 21 03
            </p>
            <p>
                <img
                    src="https://img.icons8.com/fluency/20/null/facebook.png"
                />tuktuk.salondeprovence
            </p>
            <p>
                <span class="red-letter">T</span>uk Tuk se déplace pour vos
                événements privés ( anniversaire,entreprise etc...)
            </p>
        </div>
        <div class="box-camion-img"></div>
    </div>
</template>

<script>
export default {
    name: "Home",
    components: {},
};
</script>

<style>
.red-letter {
    color: red;
}

/* 1ere partie*/

.box-img-home {
    background-image: url(../assets/Home.png);
    width: 100%;
    height: 844px;
    background-position: center;
    background-size: cover;

    display: flex;
    justify-content: center;
    align-items: center;
}

.d-flex {
    color: white;
    padding-top: 77px;
    padding-left: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.first-title {
    font-size: 75px;
    margin: 0;
}
.second-title-home {
    font-size: 30px;
    width: 365px;
    color: white;
    padding-left: 100px;
}

/*  2eme partie */

.box-img-second {
    background-image: url(../assets/2.png);
    width: 100%;
    height: 844px;
    background-position: center;
    background-size: cover;

    display: flex;
    justify-content: space-evenly;
    flex-direction: column;
}
.box-img-second h1 {
    font-size: 30px;
    color: black;
    margin: 0;
}
.title-2 {
    font-size: 10px;
    padding-left: 40px;

    color: black;
}
.box-info-2 {
    padding: 15px;
}
.box-second-info-1 {
    width: 100%;
    height: 315px;
    text-align: left;
    font-size: 10px;
    font-weight: 500;

    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}
.box-info-img {
    background-image: url(../assets/carte_recto.jpeg);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 529px;
}
.box-info-text {
    width: 70%;
}

/* 3eme partie */

.box-three-img {
    background-image: url(../assets/3.png);
    background-position: center;
    background-size: cover;
    height: 250px;
    width: 100%;

    display: flex;
    justify-content: space-around;
    align-items: center;
}

.img-plat {
    height: 160px;
    width: 120px;
    background-position: center;
    background-size: cover;
}
.plat {
    color: white;
    text-align: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
}

/* 4eme partie */

@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

.box-four-img {
    background-image: url(../assets/4.png);
    background-position: center;
    background-size: cover;
    height: 594px;
    width: 100%;
}

.box-four-img {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    font-family: "Lobster", cursive;
    font-size: 60px;
}

/* 5eme partie */

.box-five-img {
    background-image: url(../assets/5.png);
    background-position: center;
    background-size: cover;
    height: 844px;
    width: 100%;
    padding: 15px;
}

.box-five-info {
    padding-left: 15px;
}
.box-five-info h1 {
    margin: 0;
}

.specialite {
    width: 100%;
    font-size: 14px;
    font-weight: 600;
}
.specialite h4 {
    text-align: center;
}
.accompagnements {
    width: 100%;
    font-size: 14px;
    font-weight: 600;
}
.accompagnements h4 {
    text-align: center;
}
.box-carte {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: column;
    height: 100%;
}
/* 6eme partie */
.box-six-img {
    background-image: url(../assets/6.png);
    background-position: center;
    background-size: cover;
    height: 844px;
    width: 100%;

    display: flex;
    justify-content: space-evenly;
    flex-direction: column;
    align-items: center;
}

.box-six-info {
    width: 50%;
    height: 227px;
    font-size: 14px;
    text-align: center;
}
.box-camion-img {
    background-image: url(../assets/camion.jpg);
    width: 84%;
    height: 269px;
    background-position: center;
    background-size: cover;
}
</style>
