# adhi
template
template.html
===============================================================================
<!DOCTYPE html>
<html>

<head>
    <title>Template</title>
    <link rel="stylesheet" href="template.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>

<body>
    <div class="header">
        <img src="Screenshot 2023-06-23 133534.jpj.png" alt="">
    </div>
    <div class="display">
    <div class="div2">
        <ul>
            <li><a href="#">Home</a></li>
        </ul>
        <ul>
            <li><a href="#">Newpage</a></li>
        </ul>
        <ul>
            <li><a href="#">Newpage2</a></li>
        </ul>
        <ul>
            <li><a href="#">Newpage3</a></li>
        </ul>
        <ul>
            <li><a href="#">Newpage4</a></li>
        </ul>
        <ul>
            <li><a href="#">Newpage5</a></li>
        </ul>
    </div>
    
        <div class="division">
            <div class="one">
                <div class="mainmenu"> 
                    <div class="">
                        <h2 class="heading"><i class="fas fa-arrow-right"></i>Main Menu</h2>
                    </div>
                    <ul class="menuicon">
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item1</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item2</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item3</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item4</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item5</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item6</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item7</a></li>
                        <li><i class="fas fa-align-justify"></i><a href="#">Menu item8</a></li>
                    </ul>
                </div>

                <div class="block">
                    <h2 class="heading2"><i class="fas fa-arrow-right"></i>Block</h2>
                    <h6>Enter block content here</h6>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut vero eligendi perspiciatis mollitia
                        perferendis omnis quaerat eaque praesentium vitae repudiandae!</p>

                </div>
            </div>
            <div class="div3">
                <div class="galery">
                    <h1>Galery</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat at accusamus sed rerum! Mollitia
                        consectetur veritatis eius sint esse, saepe totam expedita molestiae porro itaque? Atque odio
                        impedit sequi sint ipsum! Pariatur incidunt quaerat ratione sequi obcaecati. Debitis impedit
                        officia dolores recusandae incidunt voluptatibus ipsam quisquam illum itaque, delectus, quia
                        dicta quo aperiam! Quis tempore cumque et ipsam quidem numquam sint, doloribus minima labore
                        nemo! Laboriosam modi, unde harum totam tempore nemo alias fuga fugiat quidem voluptatem
                        molestiae possimus? A quaerat commodi non pariatur voluptates. Exercitationem consectetur
                        pariatur possimus numquam. Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim quisquam illum tempora. Omnis quisquam doloribus earum illum soluta incidunt impedit.</p>
                    <div class="down">
                        <div>
                            <h1>Subscription</h1>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. At assumenda dolorem esse et
                                est? Voluptatum iure molestiae nisi corporis consequatur quis maxime explicabo odio fuga
                                impedit ea in delectus dignissimos ipsum, velit doloribus labore eaque! Officiis fuga
                                tempore, minus, in nesciunt doloribus accusamus, perspiciatis eum nam at eos non quis?
                            </p>
                            <button>Read More</button>
                        </div>
                        <div class="down2">
                            <h1>Other Services</h1>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dignissimos cupiditate libero,
                                id ipsam laboriosam vero itaque sed voluptatem pariatur culpa, blanditiis consectetur
                                fugiat incidunt beatae iure nesciunt ut aspernatur est corrupti, natus voluptatibus eos
                                nemo quisquam. Exercitationem sequi dolore deleniti consectetur? Rem sapiente quaerat
                                excepturi rerum, porro nulla. Eius, ipsam?</p>
                            <button>Read More</button>

                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="floater">
            <p>Copyright@2014.</p>
        </div>
    </div>

</body>

</html>
===================================================================
template.css
==========================================================
body {
  margin: 0;
}

.header {
  background-color: #b7d72a;
  height: 100px;
  border-top: 1px solid black;
  border-left: 1px solid black;

}

img {
  position: absolute;
  right: 30px;
  margin-top: 10px;
  right: 30px;
}

.div2 {
  background-color: #eae6cb;
  display: flex;
  justify-content: space-around;
  border-top: 1px solid;
  border-left: 1px solid;
  margin: 5px;
  border-right: 1px solid;
}

.div2 ul {
  margin: 0;
  padding: 30px;
}

.div2 li {
  display: inline-block;
}

.div2 a {
  text-decoration: none;
  color: #484f41
}

.main {
  background-color: #f1e8c7;

}

.menuicon {
  list-style-type: none;
  /* Remove default list numbering */
}

.menuicon li {
  position: relative;
  /* Create a positioning context */
  padding-left: 10px;
  /* Add space for the menu icon */
  margin-top: 5px;
}

.menuicon li i {
  position: absolute;
  /* Position the icon */
  top: 50%;
  /* Align the icon vertically */
  left: 0;
  /* Position the icon to the left */
  transform: translate(-50%, -50%);
}

.division {
  display: flex;
  gap: 14px;

}

.mainmenu {
  background-color: #f0e8c3;
  padding: 5px;
}

@media screen and (min-width: 320px) and (max-width:677px) {
  body {
    background-color: lightgreen;
  }

  .main .heading {
    padding: 0px;
  }
}

@media screen and (min-width: 678px) and (max-width:991px) {
  body {
    background-color: red;
  }
}
@media screen and (min-width: 992px) {
  body {
    background-color: rgb(32, 224, 128);
  }
}


.mainmenu .heading {
  margin: 0;
  background-color: #d2d35e;
  padding: 10px 0 10px 47px
}

.mainmenu .heading ul {
  margin: 0;
  padding-top: 0;
}

.block .heading2 {
  background-color: #d2d35e;
  margin-top: 10px;
  margin-bottom: 0;
  padding: 10px 0 o 47px;


}

.block {
  background-color: #f0e8c3;
  padding: 5px;

}

.block h2 {
  padding: 10px 0;
}

.one {
  margin-left: 5px;
}

.down {
  display: flex;
  gap: 25px;
}

.down2 {
  border-left: 1px solid;
  padding: 0px 13px;
}

.div3 {
  background-color: #f2e9c8;
}

button {
  background-color: #bdd342;
  color: #000505;
  font-family: emoji;
  font-size: 14px;
}

button:hover {
  cursor: pointer;
}

.div2 ul li a:hover {
  color: #000505;
}

.div3 p {
  font-size: 18px;

}

.galery {
  margin-right: 20px;
}

.mainmenu ul {
  margin: 0;
}

.display {
  background-color: #f2e9c8;

  margin-bottom: 0;
  border-top: 1px solid;
  border-left: 1px solid;
}

.block h6 {
  margin-top: 15px;
}

.mainmenu .heading {
  position: relative;
  /* Create a positioning context */
  /* Add space for the menu icon */

}

.mainmenu .heading i {
  position: absolute;
  /* Position the icon */
  top: 50%;
  /* Align the icon vertically */
  left: 32px;
  /* Position the icon to the left */
  transform: translate(-50%, -50%);
}

.floater {
  background-color: #cbde4e;
  height: 100px;
  position: relative;
}

.floater p{
  position: absolute;
  top: 50px;
  margin: 0;
  left: 50%;
}
=======================
