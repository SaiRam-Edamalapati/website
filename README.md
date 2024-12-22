# Ex.07 Restaurant Website
# Date:8/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="C:\Users\admin\Documents\Games\resto sai.css" />
    <title>Foodie</title>
</head>

<body>

    <link rel="preconnect" href="https://fonts.googleapis.com">

    <div class="container">

        <header>
            <nav id="navbar">
                <div class="logo"><span>Foodie</span></div>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#order">Order</a></li>
                </ul>
            </nav>
            <div id="mobile">
                <div class="logo1"><span>Foodie</span></div>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#order">Order</a></li>
                </ul>
            </div>

            <div class="overlay">
                <section id="home">
                    <h1 class="h-primary">Welcome to Foodie</h1>
                    <br>
                    <p>Where flavor meets comfort—welcome to your ultimate dining experience! </p>
                    <button class="btn">Order Now</button>
                </section>
            </div>
        </header>



        <div id="menu">
            <div class="heading">
                <h1>Menu</h1>
                <h3>Today's Special</h3>
            </div>
            <div class="card">
                <img
                    src="https://images.unsplash.com/photo-1626074353765-517a681e40be?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80">
                <div class="details">
                    <div class="details-sub">
                        <h5>Chicken Tandoori</h5>
                        <h5 class="price"> ₹300 </h5>
                    </div>
                    <p>Indulge in the smoky, spicy perfection of our Chicken Tandoori,
                     marinated with rich spices and grilled to juicy tenderness.
                     A timeless delight for every food lover!</p>
                    <button>Add To Cart</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1593179241557-bce1eb92e47e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"
                    alt="">
                <div class="details">
                    <div class="details-sub">
                        <h5>Hong Kong Noodles</h5>
                        <h5 class="price"> ₹240 </h5>
                    </div>
                    <p>"Savor the authentic taste of Hong Kong Noodles, 
                        a perfect blend of crispy veggies, flavorful sauces, and tender noodles.
                         A symphony of flavors in every bite!"</p>
                    <button>Add To Cart</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1606491956689-2ea866880c84?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1921&q=80"
                    alt="">
                <div class="details">
                    <div class="details-sub">
                        <h5>Pav Bhaji</h5>
                        <h5 class="price"> ₹120 </h5>
                    </div>
                    <p>Experience the magic of street-style Pav Bhaji,
                         a zesty blend of mashed veggies and spices,
                          served with buttery buns. A true taste of Mumbai's soul!</p>
                    <button>Add To Cart</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80"
                    alt="">
                <div class="details">
                    <div class="details-sub">
                        <h5>Pizza</h5>
                        <h5 class="price"> ₹270 </h5>
                    </div>
                    <p>Delight in our cheesy, oven-baked Pizza,
                         topped with the freshest ingredients and irresistible flavors.
                          A slice of happiness in every bite!</p>
                    <button>Add To Cart</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1899&q=80"
                    alt="">
                <div class="details">
                    <div class="details-sub">
                        <h5>Cheese Burger</h5>
                        <h5 class="price"> ₹180 </h5>
                    </div>
                    <p>Sink your teeth into our juicy, 
                        loaded Burger, stacked with mouthwatering layers of flavor.
                        A classic treat for every craving!
                    </p>
                    <button>Add To Cart</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1603894584373-5ac82b2ae398?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80"
                    alt="">
                <div class="details">
                    <div class="details-sub">
                        <h5>Butter Chicken</h5>
                        <h5 class="price"> ₹350 </h5>
                    </div>
                    <p>Relish the creamy, spiced perfection of Butter Chicken,
                         cooked to tender excellence in a rich tomato gravy.
                          A royal feast for your taste buds!</p>
                    <button>Add To Cart</button>
                </div>
            </div>
        </div>


        <div id="about">
            <h1 class="title">About us</h1>
            <div class="about_row">
                <div class="about_column">
                    <p>About Us  
                        Welcome to Foodie, where every bite is a journey of flavor, passion, and joy! At Foodie, we blend authentic recipes with a modern twist, using the freshest ingredients to craft dishes that tantalize your taste buds.  
                        
                        Whether you're here for a cozy meal, a quick snack, or a celebration, we’re dedicated to making every moment special. With warm hospitality and a menu full of irresistible delights, Foodie is more than a restaurant—it’s an experience.  
                        
                        Come, indulge, and let your inner foodie rejoice! Your table is ready!</p>
                    <button id="btn1">learn more</button>
                </div>
                <div class="about_column">
                    <img src="https://img.freepik.com/free-photo/chef-making-ok-sign-white-background_1368-2804.jpg?w=2000
        " alt="">
                </div>
            </div>
        </div>
        <div id="order">
            <h1 class="title1">order</h1>
            <form action="">
                <input type="text" class="inp_box" placeholder="Name">
                <input type="email" class="inp_box" placeholder="Email">
                <textarea type="text" class="inp_box text_area" placeholder="Adress"></textarea>
                <button class="btn2">Order Now</button>
        </div>
        </form>

    </div>
    <footer>
        <div>
            &copy;copyright 2024
            <p>
                Designed by E SAI RAM
            </p>
        </div>
    </footer>
    </div>

</body>

</html>
```

# OUTPUT:
![Screenshot (38)](https://github.com/user-attachments/assets/8016acc4-4a51-4bfa-be6a-e6e3e0611441)
![Screenshot (39)](https://github.com/user-attachments/assets/8d588c8d-5a62-444f-bae6-67f3712d3464)
![Screenshot (40)](https://github.com/user-attachments/assets/4abd7600-8014-42ab-b693-3e3d4c944eea)
![Screenshot (41)](https://github.com/user-attachments/assets/0c03b9df-d69d-46a6-8227-291bfe7e309e)
![Screenshot (42)](https://github.com/user-attachments/assets/cae0f396-3e41-48a8-8602-18d4fc86fe85)
![Screenshot (43)](https://github.com/user-attachments/assets/85b529ce-2d14-4807-a96c-8f53ba02c6c2)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
