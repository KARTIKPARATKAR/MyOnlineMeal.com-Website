<!--Below Is the HTML code of website  -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width:1170px)" href="phone.css">
    <link rel="stylesheet" href="Bree_Serif.zip">
    <title>MyOnlineMeal.com</title>

 </head>

<body>
    <nav id="navbar">
        <div id="logo">
            <img src="restaurant-logos-png-png_25706.jpg" alt="MyOnlineMeal">
        </div>
        <ul>
            <li class="item"><a href="#Home">Home</a></li>
            <li class="item"><a href="#Services">Our-Clients</a></li>
            <li class="item"><a href="#">About Us</a></li>
            <li class="item"><a href=".contact">Contact Us</a></li>

        </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome To MyOnlineMeal</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Minus laudantium officia earum dolorem velit
            perferendis!</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. At quasi placeat vel dolor sint eligendi.</p>
        <button class="btn">OrderNow</button>
    </section>
    <section class="services-container">
        <h1 class="h-primarycenter" id="thisheading">Our Services</h1>
        <div id="services">
            <div class="box">
                <img src="pngtree-modern-kitchen-food-box-italian-pizza-png-image_6651521.png" alt="MyOnlineFood">
                <h2 class="h-secondarycenter">Food Ordering</h2>
                <p class="center">Lorem Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptas expedita quo,
                    saepe doloribus iste odit in, at earum atque id omnis repellendus impedit. ipsum dolor sit, amet
                    consectetur adipisicing elit. Ducimus architecto voluptatum incidunt fuga ea beatae aperiam a quod
                    eaque nostrum minus odit aliquam nesciunt dignissimos, neque nemo tempora! Qui rerum expedita
                    excepturi ducimus voluptatem.</p>
            </div>
            <div class="box">
                <img src="food-grass-fed-beef-foodservice-products-grass-run-farms-4.png" alt="MyOnlineFood">
                <h2 class="h-secondarycenter">Food Catering</h2>
                <p class="center">Lorem Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsum eos praesentium
                    optio tenetur culpa quia deleniti libero eum quaerat obcaecati at, animi rerum!ipsum dolor sit, amet
                    consectetur adipisicing elit. Ducimus architecto voluptatum incidunt fuga ea beatae aperiam a quod
                    eaque nostrum minus odit aliquam nesciunt dignissimos, neque nemo tempora! Qui rerum expedita
                    excepturi ducimus voluptatem.</p>
            </div>
            <div class="box">
                <img src="png-clipart-man-riding-motorcycle-pizza-delivery-take-out-pizza-delivery-restaurant-pizza-deliveryman-food-boy-thumbnail.png"
                    alt="MyOnlineFood">
                <h2 class="h-secondarycenter">Bulk Ordering</h2>
                <p class="center">Lorem Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quisquam fuga
                    voluptate aperiam alias. Blanditiis nesciunt culpa optio consequuntur assumenda atque aspernatur
                    earum dicta!ipsum dolor sit, amet consectetur adipisicing elit. Ducimus architecto voluptatum
                    incidunt fuga ea beatae aperiam a quod eaque nostrum minus odit aliquam nesciunt dignissimos, neque
                    nemo tempora! Qui rerum expedita excepturi ducimus voluptatem.</p>
            </div>
        </div>
    </section>
    <SECTION class="client-section">
        <h1 class="h-primarycenter"><b>Our Clients</b></h1>
        <div id="clients">
            <div class="client-item">
                <img src="burger_king_PNG9.png" alt="Website ">
            </div>
            <div class="client-item">
                <img src="Dominos_pizza_logo.svg.png" alt="Website ">
            </div>
            <div class="client-item">
                <img src="download.png" alt="Website ">
            </div>
            <div class="client-item">
                <img src="images.png" alt="Website ">
            </div>
        </div>
    </SECTION>
    <section class="contact">
        <h1 class="h-primarycenter">Contact Us</h1>
        <div id="contactbox">
            <form action="">
                <div class="formgroup">
                    <label for="Name">Name:</label>
                    <input type="text" name="Name" id="Name" class="pointer" placeholder="Enter Your Name:">
                </div>
                <div class="formgroup">
                    <label for="Email">Email:</label>
                    <input type="email" name="Email" id="Email" class="pointer" placeholder="Enter Your Email:">
                </div>
                <div class="formgroup">
                    <label for="Phone">Contact-No:</label>
                    <input type="phone" name="Name" id="Contact" class="pointer" placeholder="Enter Your Contact-NO:">
                </div>
                <div class="formgroup">
                    <label for="Name">Message:</label>
                    <textarea name="Message" id="Message" cols="30" rows="10" class="pointer"
                        placeholder="Enter Your Remark:"></textarea>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            Copyright &copy; wwww.myOnlineMeal.com All Rights Reserved
        </div>
    </footer>
</body>

</html>
