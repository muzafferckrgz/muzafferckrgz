HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ana Sayfa</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://fonts.google.com/share?selection.family=Oxygen:wght@300">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css"
        integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">
    <link rel="stylesheet" href="https://fonts.google.com/share?selection.family=Mukta:wght@200">
</head>

<body>
    <div id="social">

        <font>MUZAFFER ÇAKIRGÖZ | <span>Medeniyet Tarihi...</span></font>

        <i class="fas fa-search"></i>
        <i class="fab fa-facebook"></i>
        <i class="fab fa-instagram"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-google"></i>

    </div>

    <div id="container">
        <header>
            <img id="headerresim" src="img/842e2e03-16cb-47e6-9663-d1a5e25ae37e.jpg" alt="">
            <div id="centered">MUZAFFER ÇAKIRGÖZ</div>
        </header>
        <section>
            <nav>
                <ul>
                    <li><a href="index.html"><i class="fas fa-home"></i>Anasayfa</a></li>
                    <li><a href="hatti.html">Hatti Medeniyeti</a></li>
                    <li><a href="zapotek.html">Zapotek Medeniyeti</a></li>
                    <li><a href="norte.html">Norte Chico Medeniyeti</a></li>
                    <li><a href="elam.html">Elam Medeniyeti</a></li>
                    <li><a href="hakkimizda.html"><i class="fas fa-users"></i>Hakkımızda</a></li>
                    <li><a href="referanslar.html"><i class="fas fa-asterisk"></i>Referanslar</a></li>
                    <li><a href="galeri.html"><i class="fas fa-images"></i>Galeri</a></li>
                    <li><a href="iletisim.html"><i class="fas fa-address-book"></i>İletişim</a></li>
                </ul>
            </nav>
            <main>
                <div class="icerik">

                    <img src="img/1.-Hatti-600x400.jpg" alt="" class="rsm">

                    <h5>Hatti Medeniyeti</h5>

                    <p class="iceriktext">2500-2000/1700 yıllarında Anadolu'da yaşamış bir uygarlık. Anadolu Yarımadası'nın bilinen en eski adı Hatti ülkesi'dir. İlk defa Mezopotamya yazılı kaynaklarında Akad sülalesi döneminde (M.Ö. ...) Böylece Anadolu en az 1.500 yıl boyunca Hatti ülkesi olarak tanındı.</p>

                    <a href="hatti.html" class="btndevam">Detaylı Bilgi..</a>
                </div>

                <div class="icerik">

                    <img src="img/2.-Zapotek-600x399.jpg" alt="" class="rsm">

                    <h5>Zapotek Medeniyeti</h5>

                    <p class="iceriktext">Zapotekler Orta Amerika'daki Kolomb öncesi bir uygarlığa ve bu uygarlığı kuranların soyundan gelenlere verilen bir addır. ... Orta Amerika kültürünü etkileyen birçok şehir-devletler kurmuşlardır. Zapotekler'in ana yerleşim bölgesi Maya ülkesi ile yukarı Meksika ovaları arasında kalan Oaxaca vadisi ve Monte Albán'dır.</p>

                    <a href="zapotek.html" class="btndevam">Detaylı Bilgi..</a>
                </div>
                <div class="icerik">

                    <img src="img/7.Norte-Chico-600x428.jpg" alt="" class="rsm">

                    <h5>Norte Chico Medeniyeti</h5>

                    <p class="iceriktext">Caral Uygarlığı, şu anda kuzey-orta kıyı Peru'nun Caral bölgesinde bulunan otuz kadar büyük nüfus merkezini içeren Kolomb öncesi dönemden kalma karmaşık bir toplumdu. Medeniyet, MÖ dördüncü ve ikinci binyıllar arasında gelişti, ilk şehrin oluşumu genellikle MÖ 3500 civarında, Fortaleza bölgesindeki Huaricanga'da.</p>

                    <a href="norte.html" class="btndevam">Detaylı Bilgi..</a>
                </div>
                <div class="icerik">

                    <img src="img/8.-Elam-600x459.jpg" alt="" class="rsm">

                    <h5>Elam Medeniyeti</h5>

                    <p class="iceriktext">Elamlar ya da Elamlılar (M.Ö. 3000 - M.Ö. 646) Güneydoğu Mezopotamya ve Güneybatı İran'da Antik Çağ'da varlık gösteren İran öncesi bir medeniyettir. Elam ülkesi Sümer ülkesinin doğusunda Kerha ve Karun Irmakları'nın geçtiği bölgede idi.</p>

                    <a href="elam.html" class="btndevam">Detaylı Bilgi..</a>
                </div>
                    
            </main>
        </section>

        <footer>Tüm Hakları Saklıdır &copy; 2021</footer>

    </div>
</body>

</html>


CSS

*{
    box-sizing: border-box;
}

body{
    margin: 0;
    padding: 0;
    background-color: #dbdbdb;
    font-family: 'Oxygen', sans-serif;
}

#social{
    background-color: black;
    color:white;
    height: 55px;
    width: 100%;
    position: sticky;
    top: 0;
    z-index: 1;
    font-size: 18px;
    text-align: right;
    padding: 15px;

}

font{
    float: left;
    letter-spacing: 2px;
}

span{
    font-size: 12px;
    letter-spacing: 1px;
}

#social>i{
    margin-right: 15px;
}

#social>i:hover{
    opacity: 0.8;
}

#container{
    width: 96%;
    max-width: 1200px;
    margin: auto;
    height: auto;
}

header{
    width: 100%;
    height: 250px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    position: relative;
    color: white;
    font-family: 'Mukta', sans-serif;
    font-size: 35px;
    background-color: black;
    margin-bottom: 5px;
}



#headerresim{
    width: 100%;
    height: 250px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    opacity: 0.8;
}

#centered{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}

section{
    width: 100%;
    height: auto;
    background-color: #f1f1f1;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
    margin-top: 15px;
    overflow: auto;
}

nav{
    width: 20%;
    float: left;
    margin-top: 10px;
    height: auto;
}

nav ul{
    width: auto;
    height: 100%;
    margin: 0;
    padding: 0;
}

nav li{
    list-style-type: none;

}

nav li a{
    height: 50px;
    line-height: 50px;
    text-decoration: none;
    color: black;
    border-bottom: 1px solid #b4b4b4;
    padding-left: 20px;
    display: block;
}

nav li a:hover{
    color:white;
    background-color: #adadad;
}

i{
    margin-right: 10px;

}

main{
    float: left;
    height: auto;
    width: 80%;
    padding: 10px;
}

.icerik{
    width: 48%;
    height: auto;
    display: inline-block;
    margin-right: 15px;
    border-radius: 10px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
    margin-bottom: 15px;
    float: left;
}

.rsm{
    width: 100%;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;;
}

.rsm:hover{
    opacity: 0.6;
    transition: opacity 0.8s;
}

h5{
    margin: 10px;
    color: dimgray;
}

.iceriktext{
    margin: 10px;
    color: dimgray;
}

.btndevam{
    display: block;
    width: 150px;
    height: 45px;
    padding: 10px 20px;
    background-color: #0071ce;
    color: white;
    text-decoration: none;
    margin: 15px;
    border-radius: 10px;
}

.btndevam:hover{
    opacity: 0.8;
}

footer{
    width: 100%;
    height: 75px;
    background-color: black;
    color: white;
    line-height: 75px;
    text-align: center;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
}

h1{
    text-align: center;
    background-color: black;
    color: white;
    height: 50px;
    line-height: 50px;
    margin: 0 10px;
    border-radius: 10px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
}

#hakkimizdarsm{
    width: 350px;
    height: 300px;
    float: left;
    border-radius: 10px;
    margin: 25px;
    margin-bottom: 10px;
    transition: opacity 0.8s;
}

#hakkimizdarsm:hover{
    opacity: 0.6;
}

.hakyazi{
    margin-right: 15px;
    font-size: 15px;
    font-family: cambria;
    text-indent: 40px;
    color: #494949;
}

.referans{
    width: 30%;
    height: 300px;
    background-color: white;
    float: left;
    margin: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
}

.refresim{
    width: 100%;
    height: 180px;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    margin: 0;
    opacity: 0.6;
    transition: opacity 0.8s;
}

.refresim:hover{
    opacity: 1;
}

.refbaslik{
    font-size: 20px;
    display: inline-block;
    margin-top: 0px;
    color: black;
    text-align: center;
    height: 45px;
    line-height: 45px;
    background-color: #f1f1f1;
    width: 100%;
    margin-top: -5px;
}

.refdetay{
    text-align: center;
}

.galresim{
    width: 22%;
    height: 200px;
    border-radius: 5px;
    opacity: 0.8;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
    margin: 10px;
    transition: all 0.6s;
    object-fit: cover;

}

.galresim:hover{
    opacity: 1;
    border: 5px solid white;
    cursor: pointer;
}

.link:link{
    text-decoration: none;
}

iframe{
    width: 98%;
    height: 350px;
    border-radius: 10px;
    margin-top: 10px;
    box-shadow: 0 2px 8px 2px rgba(20, 23, 28, .15);
    margin-left: 10px;
}

.section1{
    width: 98%;
    height: auto;
    margin: auto;
    margin-top: 10px;
    background-color: #f2f2f2;
    padding: 10px;
}

.form{
    width: 49%;
    float: left;
    height: 380px;
    border: 1px solid #d8d8d8;
    padding: 10px;
    margin-right: 10px;
}

.col25{
    width: 25%;
    float: left;
    margin-top: 6px;
}

.col75{
    width: 75%;
    float: left;
    margin-top: 6px;
}

label{
    padding: 12px 12px 12px 0;
    display: inline-block;
}

input[type=text], textarea{
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.row:after{
    content: "";
    clear: both;
    display: block;
}

input[type=submit]{
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    float: right;
}

.adres{
    width: 49%;
    float: left;
    height: 380px;
    border: 1px solid #d8d8d8;
    padding: 10px;
}

h2{
    text-align: center;
}

.span1{
    display: block;
    font-family: Calibri;
    margin: 10px;
    letter-spacing: 1.5px;
    text-align: center;
    font-size: 16px;
}


