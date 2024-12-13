# Ex.07 Restaurant Website
# Date:13.12.2024
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
# RESTAURENT.HTML :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indian Best Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <h1>Indian Best Restaurant</h1>
        <nav>
            <ul>
                <li><a href="rest0.html">Home</a></li>
                <li><a href="rest1.html">Menu</a></li>
                <li><a href="rest2.html">Administration</a></li>
                <li><a href="rest3.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <img width="1500" height="700" src="watercolor-food-landing-page-design_23-2149078876.jpg">
    </section>
    <footer>
        <p>&copy; 2024 @Tharun.V</p>
    </footer>
</body>
</html>
```
# HOME PAGE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indian Best Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <h1>Indian Best Restaurant</h1>
    </header>
    <section>
        <img width="1500" height="500" src="watercolor-food-brochure-design_23-2149078877.jpg">
        We extend our deepest gratitude for choosing our restaurant for your dining experience. It's our utmost pleasure to serve you with the finest cuisine and impeccable service. Your support and patronage mean the world to us, and we are dedicated to continuously exceeding your expectations. Thank you for being a part of our culinary journey.
        It has been an honor to have you as our guest. Your enthusiasm and appreciation for our food and service mean everything to us. We are committed to maintaining the highest standards and providing you with unforgettable dining experiences. Thank you for your trust and for allowing us to share our passion for food with you.
        Your visit brings us immense joy and drives us to deliver our best with every dish. We are humbled by your kind words and loyalty, which motivate us to innovate and elevate your dining experience. Thank you for choosing us and for making our journey in the culinary world so rewarding.
    </section>
    <footer>
        <button onclick="goBack()">Back</button> 
        <script> function 
        goBack() { window.history.back(); } 
        </script> 
        <p>&copy; 2024 @Tharun.V</p>
    </footer>
</body>
</html>
```
# MENU PAGE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Indian Best Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <section>
        <h2>Our Menu</h2>
        <ul class="menu-list">
            <li><center>Biryani-<img width="300" height="300" src="biryani.avif"></center> Biryani is a fragrant rice dish cooked with tender meat and a blend of aromatic spices. The layers of marinated meat, parboiled rice, and fried onions are slow-cooked to perfection. Garnished with saffron, raisins, and cashews, biryani is a feast for both the eyes and the palate. It's typically served with raita, adding a refreshing contrast to the rich flavors.</li>
            <li><center>Chicken platter-<img width="300" height="300" src="chicken platter.png"></center> Chicken platter is a delightful dish featuring succulent grilled or roasted chicken pieces, often accompanied by a variety of sides. These may include fresh salads, fragrant rice, and savory dipping sauces. The chicken is marinated with a blend of spices, ensuring each bite is flavorful and tender. It's a versatile dish perfect for both casual meals and festive occasions.</li>
            <li><center>Grilled chicken-<img width="300" height="300" src="Grilled Chicken.jpeg"></center>Grilled chicken is a succulent dish featuring tender chicken pieces marinated in a blend of spices and herbs. The chicken is then perfectly grilled to achieve a smoky flavor and crisp, charred edges. Each bite is juicy and packed with deliciously balanced flavors. This dish is often served with sides like grilled vegetables or a fresh salad, making it a wholesome and satisfying meal.</li>
            <li><center>BBQ chicken-<img width="300" height="300" src="BBQ Chicken.jpeg"></center>BBQ chicken is a savory delight featuring juicy chicken pieces slathered in rich barbecue sauce. Grilled to perfection, the chicken boasts a smoky flavor with caramelized edges. Each bite offers a perfect blend of tangy, sweet, and slightly spicy notes. This crowd-pleaser is often paired with coleslaw, corn on the cob, or baked beans for a complete meal.</li>
            <li><center>Egg gravy-<img width="300" height="300" src="egg gravy.jpg"></center>Egg gravy is a savory dish featuring hard-boiled eggs simmered in a rich, spiced tomato-based sauce. The gravy is infused with aromatic spices like cumin, coriander, and turmeric, giving it a robust flavor. The eggs absorb the tangy and spicy essence of the gravy, making each bite delightful. Often served with rice, bread, or roti, it's a comforting and satisfying meal.</li>
            <li><center>Soup-<img width="300" height="300" src="spoooop.jpeg"></center>Soup is a comforting and nourishing dish that typically consists of a flavorful broth, vegetables, and often, meat or legumes. It can be prepared in a variety of styles, from creamy and rich to light and brothy. Served hot, soup is perfect for warming up on a chilly day and can be enjoyed as a starter or a main course. It's a versatile dish that can be customized with a wide range of ingredients to suit any palate.</li>
            <li><center>Noodles- <img width="300" height="300" src="noodles.jpeg"></center>Noodles are a versatile and beloved dish made from dough, often boiled and served with a variety of ingredients. They can be prepared in numerous styles, including stir-fried, soup-based, or in salads. Noodles are typically paired with vegetables, meats, and flavorful sauces, offering a delightful balance of textures and tastes. This popular comfort food is enjoyed in many cuisines around the world.</li>
            <li><center>Chicken tandoori- <img width="300" height="300" src="chicken.jpeg"></center>Chicken Tandoori is a mouthwatering dish featuring marinated chicken cooked in a traditional tandoor oven. The chicken is soaked in a mixture of yogurt and spices like cumin, coriander, and garam masala, giving it a vibrant red color and rich flavor. Grilled to perfection, it boasts a smoky aroma and juicy tenderness. Often served with naan or rice, it’s a classic favorite in Indian cuisine.</li>
            <li><center>Fish fry-<img width="300" height="300" src="fish fry.webp"></center>Fish fry is a delightful dish featuring crispy, golden-brown fish fillets, lightly breaded or battered and deep-fried to perfection. The exterior is wonderfully crunchy, while the inside remains moist and tender. It's often served with a side of tartar sauce, lemon wedges, and coleslaw for a refreshing contrast. This classic comfort food is a favorite for seafood lovers and casual dining.</li>
            <li><center>Burger-<img width="300" height="300" src="burger.jpeg"></center>A burger is a mouthwatering delight featuring a juicy patty, usually made of beef or chicken, nestled in a soft bun. It's often topped with fresh lettuce, ripe tomatoes, crunchy pickles, and a slice of cheese, all enhanced by a dollop of sauce. Each bite offers a perfect balance of savory flavors and textures. This classic comfort food is a favorite for casual meals and gatherings.</li>
            <li><center>Chicken gravy-<img width="300" height="300" src="Chicken gravy.jpg"></center>Chicken gravy is a flavorful dish featuring tender chicken pieces simmered in a rich, spiced sauce. The gravy, often made with tomatoes, onions, and a blend of aromatic spices, creates a luscious and savory base. Each bite of chicken is infused with the robust flavors of the gravy. This hearty dish is perfect with rice, bread, or roti, making it a comforting meal.</li>
            <li><center>Chicken 65-<img width="300" height="300" src="Chicken 65.jpg"></center>Chicken 65 is a spicy and flavorful Indian appetizer that features bite-sized pieces of chicken marinated in a blend of yogurt and bold spices. The chicken is deep-fried to achieve a crispy exterior while remaining juicy inside. It is typically garnished with curry leaves, green chilies, and a squeeze of lemon juice, adding an extra layer of zest. This dish is a popular choice for its intense flavors and perfect balance of heat and tanginess.</li>
            <li>Item 11- Description</li>
        </ul>
    </section>
    <footer>
        <button onclick="goBack()">Back</button> 
        <script> function 
        goBack() { window.history.back(); } 
        </script> 
        <p>&copy;2024 @Tharun.V</p>
    </footer>
</body>
</html>
```
# ADMINISTRATION PAGE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Indian Best Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <section>
        <h2>Administration Team</h2>
        <div class="team">
            <div class="member">
                <center><img width="300" height="300" src="chef 1.avif"></center>
                <p>Rachael Ray</p>
                <p>Rachael Ray's designation includes several roles: she is a **celebrity cook, television host, businesswoman, and author**. She is best known for her TV show "30 Minute Meals" and her daily talk show, "The Rachael Ray Show."</p>
            </div>
            <div class="member">
                <center><img width="300" height="300" src="chef 2.avif"></center>
                <p>Gordon Ramsay</p>
                <p>Gordon Ramsay's designation includes several roles: he is a **celebrity chef, restaurateur, television personality, and author**. He is renowned for his Michelin-starred restaurants, his fiery personality on TV shows like "Hell's Kitchen" and "MasterChef," and his numerous best-selling cookbook.</p>
            </div>
            <div class="member">
                <center><img width="300" height="300" src="chef 3.avif"></center>
                <p>Giada De Laurentiis</p>
                <p>Giada De Laurentiis is an Italian-American chef, author, and television personality. She is best known for her popular Food Network shows like "Everyday Italian" and "Giada at Home." Giada has also authored several cookbooks and launched her own lifestyle brand, Giadzy. Her cooking style focuses on simple, fresh ingredients and Italian cuisine.</p>
            </div>
            <div class="member">
                <center><img width="300" height="300" src="chef 4.avif"></center>
                <p>Bobby Flay</p>
                <p>Bobby Flay is a renowned American celebrity chef, restaurateur, and television personality. He is best known for his appearances on Food Network shows like "Iron Chef America," "Beat Bobby Flay," and "Bobby Flay's Barbecue Addiction."1 Flay owns several restaurants, including Bobby's Burger Palace and Mesa Grill, and has authored numerous cookbooks1.</p>
            </div>
            <div class="member">
                <center><img width="300" height="300" src="chef 5.avif"></center>
                <p>David Chang</p>
                <p>David Chang is an American celebrity chef, restaurateur, author, podcaster, and television personality. He is the founder of the Momofuku restaurant group, known for popularizing modern Asian cuisine. Chang has hosted several TV shows, including the Netflix series "Ugly Delicious," and has won multiple James Beard Awards2. His innovative approach to food has made him a significant figure in the culinary world.</p>
            </div>
            <div class="member">
                <center><img width="300" height="300" src="chef 6.avif"></center>
                <p>Guy Fieri</p>
                <p>Guy Fieri is an American celebrity chef, restaurateur, author, and Emmy Award-winning television host. He is best known for his Food Network shows like "Diners, Drive-Ins and Dives," "Guy's Grocery Games," and "Guy's Family Road Trip."1 Fieri has also opened several restaurants, including Guy's American Kitchen and Bar, and is known for his bold and enthusiastic personality.</p>
            </div>
        </div>
    </section>
    <footer>
        <button onclick="goBack()">Back</button> 
        <script> function 
        goBack() { window.history.back(); } 
        </script> 
        <p>&copy; 2024 @Tharun.V</p>
    </footer>
</body>
</html>
```
# CONTACT US PAGE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Indian Best Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <section>
        <img width="1500" height="500" src="watercolor-food-facebook-cover_23-2149078873.jpg">
        <h2><center>Contact Us</center></h2>
        <p><center>Address: 123 Restaurant St, Food City</center></p>
        <p><center>Phone: +99 123 456</center></p>
        <p><center>Email: indianfood@gmail.com</center></p>
    </section>
    <footer>
        <button onclick="goBack()">Back</button> 
        <script> function 
        goBack() { window.history.back(); } 
        </script> 
        <p>&copy; 2024 @Tharun.V</p>
    </footer>
</body>
</html>
```
# CSS CODE :
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #444;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.banner {
    width: 100%;
    height: auto;
}

section {
    padding: 20px;
}

.menu-list {
    list-style: none;
    padding: 0;
}

.menu-list li {
    background: #eee;
    margin: 5px 0;
    padding: 10px;
    border-radius: 5px;
}

.team {
    display: flex;
    flex-wrap: wrap;
}

.member {
    flex: 1 1 calc(33.333% - 20px);
    margin: 10px;
    text-align: center;
}

.member img {
    border-radius: 50%;
    width: 100px;
    height: 100px;
}

footer {
    background-color: #444;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```
# OUTPUT:
![Screenshot 2024-12-13 204458](https://github.com/user-attachments/assets/65ae7867-4183-4285-8f0e-00aceb6559e4)
![Screenshot 2024-12-13 204516](https://github.com/user-attachments/assets/2e18e409-666f-4b5f-b4dd-df2db6108d5b)
![Screenshot 2024-12-13 204545](https://github.com/user-attachments/assets/abe7f6a0-fed5-48f1-aad9-5368ff8310be)
![Screenshot 2024-12-13 204602](https://github.com/user-attachments/assets/261cdc95-cbc3-4659-a081-b72b7ee51e48)
![Screenshot 2024-12-13 204616](https://github.com/user-attachments/assets/0c590ea4-6cd4-4e6b-98b6-cd4515f0522b)
![Screenshot 2024-12-13 204635](https://github.com/user-attachments/assets/7156c31b-8ab9-46e6-a67c-5fd43f7109b3)
![Screenshot 2024-12-13 204704](https://github.com/user-attachments/assets/07f32e22-91f9-4ba4-b944-e02a6eefccdb)
![Screenshot 2024-12-13 204721](https://github.com/user-attachments/assets/fe3634dd-13a0-4bb9-91ad-f4ba319553bd)
![Screenshot 2024-12-13 204740](https://github.com/user-attachments/assets/8785ac72-67f9-4999-858b-f7c998644d90)
![Screenshot 2024-12-13 204759](https://github.com/user-attachments/assets/c2e2b92f-0a54-4557-9caa-62ea8058780f)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
