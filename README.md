<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zozor Travel Diaries</title>
    <link rel="stylesheet" href="css/PaginaWeb.css">
    <style>
        *{
  margin: 0;
  padding: 0;
}
body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0e6d2;
            color: #333;
            line-height: 1.7;
        }

        .container {
            width: 80%;
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
        }

        .header {
            background-color: #d2b48c; 
            color: #333;
            padding: 20px 0;
        }

        .header h1 {
            margin: 0;
            font-size: 2em;
        }
        .header p {
            color: #333;
            text-decoration: none;
        }

        .header nav {

            text-align: end;
        }

        .header nav a {
            color: #333;
            text-decoration: none;
            padding: 0 15px;
        }

        .main-content {
            display: flex;
            justify-content: space-between;
            padding: 20px 0;
        }

        .main-column {
            width: 65%;
        }

        .sidebar {
            width: 30%;
            background-color: #e6d8c2;
            padding: 20px;
        }

        .article {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .footer {
            background-color: #d2b48c;
            color: #333;
            text-align: center;
            padding: 10px 0;
            font-size: 0.8em;
        }

        .pictures-friends {
            display: flex;
            justify-content: space-between;
        }

        .my-pictures, .my-friends {
            background-color: #e6d8c2;
            padding: 10px;
            margin-top: 10px;
        }

        .my-pictures img {
            height: auto;
            display: block;
            margin-bottom: 5px;
        }

        .my-friends ul {
            list-style-type: none;
            padding: 0;
        }

        .my-friends li {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="container">
            <h1 class="logo"><img src="imagenes/zozor_logo.png" alt="">Zozor </h1>
            <p>Travel diaries</p>
            <nav>
                    <a href="#">HOME</a>
                    <a href="#">BLOG</a>
                    <a href="#">RESUME</a>
                    <a href="#">CONTACT</a>
                </div>
            </nav>
        </div>
    </div>
    <div class="banner">
        <div class="container">
            <img src="imagenes/sanfrancisco.jpg" width="1100">
        </div>
    </div>

    <div class="container">
        <div class="main-content">
            <div class="main-column">
                <div class="article">
                    <h2><img src="imagenes/ico_epingle.png" alt="">I'M A GREAT TRAVELLER</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec sagittis massa. Nulla facilisi. Cras id
                        arcu lorem, et semper purus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur
                        ridiculus mus. Duis vel enim ml, in lobortis sem. Vestibulum luctus elit eu libero ultrices id fermentum
                        sem sagittis. Nulla imperdiet mauris sed sapien dignissim id aliquam est aliquam. Maecenas non odio
                        ipsum, a elementum nisi. Mauris non erat eu erat placerat convallis. Mauris in pretium urma. Cras laoreet
                        molestie odio, consequat consequat velit commodo eu. Integer vitae lectus ac nunc posuere pellentesque
                        non at eros. Suspendisse non lectus lorem.</p>
                    <p>Vivamus sed libero nec mauris pulvinar facilisis ut non sem. Quisque mollis ullamcorper diam vel faucibus.
                        Vestibulum sollicitudin facilisis feugiat. Nulla euismod sodales hendrerit. Donec quis orci arcu. Vivamus
                        fermentum magna a erat ullamcorper dignissim pretium nunc aliquam. Aenean pulvinar condimentum
                        enim a dignissim. Vivamus sit amet lectus at ante adipiscing adipiscing eget vitae felis. In at fringilla
                        est. Cras id velit ut magna rutrum commodo. Etiam ut scelerisque purus. Duis risus elit, venenatis vel
                        rutrum in, Imperdiet in quam. Sed vestibulum, libero ut bibendum consectetur, eros ipsum ultrices nisl, in
                        rutrum diam augue non tortor. Fusce nec massa et risus dapibus aliquam vitae nec diam.</p>
                    <p>Phasellus ligula massa, congue ac vulputate non, dignissim at augue. Sed auctor fringilla quam quis
                        porttitor. Praesent vitae dignissim magna. Pellentesque quis sem purus, vel elementum mi. Pellentesque
                        habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Maecenas consectetur
                        euismod urna. In hac habitasse platea dictumst. Quisque tincidunt porttitor vestibulum. Ut laculls, lacus
                        at molestie lacinia, ipsum mi adipiscing ligula, vel mollis sem risus eu lectus. Nunc elit quam, rutrum ut
                        dignissim sit amet, egestas at sem.</p>
                </div>
            </div>

            <div class="sidebar">
                <h2>ABOUT THE AUTHOR</h2>
                <img src="imagenes/zozor_classe.png" alt="">
                <p>Let me introduce myself: My name's Zozor. I was born on 23 November 2005.</p>
                <p>A bit meager, is it not? This is why I've now decided to write my biography to let my readers know who I really am.</p>
                <img src="imagenes/facebook.png" alt="">
                <img src="imagenes/twitter.png" alt="">
                <img src="imagenes/vimeo.png" alt="">
                <img src="imagenes/flickr.png" alt="">
                <img src="imagenes/rss.png" alt="">
            </div>
        </div>

        <div class="pictures-friends">
            <div class="my-pictures">
                <h3>MY PICTURES</h3>
                <main class="container">
                    <div class="row">
                        <div class="cot 3">
                            <img src="imagenes/photo1.jpg">

                        </div>
                        <div class="cot 3">
                            <img src="imagenes/photo2.jpg">

                        </div>
                        <div class="cot 3">
                            <img src="imagenes/photo3.jpg">

                        </div>
                        <div class="cot 3">
                            <img src="imagenes/photo4.jpg">

                        </div>

                    </div>

                </main>
            </div>

            <div class="my-friends">
                <h3>MY FRIENDS</h3>
                <ul>
                    <li>Pupi the rabbit</li>
                    <li>Mr Baobab</li>
                    <li>Kahwaii</li>
                    <li>Perceval.eu</li>
                    <li>Ji</li>
                    <li>Super cucumber</li>
                    <li>Prince</li>
                    <li>Mr Fan</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
