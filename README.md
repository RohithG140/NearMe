# Ex03 Places Around Me
## Date: 29/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title>my native</title>
    </head>
    <body>
        <h1 align="center">Chennai</h1>
        <h3 align="center">Rohith(25018770)</h3>

        <img src="Screenshot 2025-11-26 113337.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="A2B Restaurants" title="A2B Restaurants" href="A2B.html" coords="773,220,929,271" shape="rect">
    <area target="" alt="Madras kebab N pizza" title="Madras kebab N pizza" href="kebab.html" coords="696,482,473,417" shape="rect">
    <area target="" alt="J J collections" title="J J collections" href="JJ.html" coords="476,245,542,278,562,321,415,333,431,285" shape="poly">
    <area target="" alt="Bata Shoe store" title="Bata Shoe store" href="Shoe.html" coords="537,695,65" shape="circle">
    <area target="" alt="Chennai super market" title="Chennai super market" href="market.html" coords="902,123,80" shape="circle">
</map>
    </body>
</html>
A2B.html
<html>
    <head>
        <title>A2B</title>
    </head>
    <body>
        <h1 align="center" style="color: red;">A2B</h1>
        <h3 style="color: cyan; font-size: 40;">Adyar Ananda Bhavan (A2B) is an Indian chain of vegetarian restaurants and confectioners founded in 1979 by K.S. Thirupathi Raja in Rajapalayam, Tamil Nadu. The chain has grown to over 170 outlets across India, primarily in Tamil Nadu and Karnataka, and has expanded internationally to countries like the United States, Malaysia, and Singapore. A2B is known for its authentic South Indian cuisine, offering a wide range of vegetarian dishes, sweets, and snacks. The brand has become a significant player in the food industry, focusing on quality and traditional recipes, and is recognized for its contribution to the Indian food landscape.</h3>
        <hr>
        <h3 style="color: cyan; font-size: 40;">A2B, or Adyar Ananda Bhavan, is one of India’s most popular vegetarian restaurant chains, known for its delicious South Indian dishes, sweets, and snacks. It offers a wide variety of traditional foods like idli, dosa, pongal, and authentic sweets such as mysore pak and badam halwa. With clean service and consistent quality, A2B has become a trusted brand for families and food lovers across India and abroad.</h3>
    </body>
</html>
kebab.html
<html>
    <head>
        <title>Madras kebab N pizza</title>
    </head>
    <body>
        <h1 align="center" style="color: brown;">Madras kebab N pizza</h1>
         <h3 style="color: aqua; font-size: 35;">Madras Kebab n Pizza is a popular casual fast-food spot in Chennai, known for serving tasty kebabs, pizzas, and other quick bites at budget-friendly prices. It’s a go-to place for people who enjoy a mix of Indian-style kebabs and cheesy pizzas, offering dine-in, takeaway, and delivery options. With simple service and a menu loved by local foodies, it has become a convenient choice for a satisfying meal.</h3>
        <br>
        <h3 style="color: aqua; font-size: 35;">🍴 Cuisine & Menu
Madras Kebab n Pizza offers a wide range of cuisines, making it a versatile choice for groups with different tastes:

Indian Specialties: Tandoori chicken, biryani, shawarma, kebabs

International Flavors: Pizzas, Chinese noodles, North Indian curries, Italian-inspired dishes

Desserts & Drinks: Falooda (blackcurrant, strawberry, kesar), ice creams, juices, and bakery items

Must-try items often mentioned in reviews:

Perfectly cooked tandoori chicken

Flavorful shawarma rolls

Variety of falooda desserts

Affordable pizzas with Indian-style toppings</h3>
        <hr>
       

    </body>
</html>
market.html
<html>
    <body>
        <h1 align="center" style="color: darkviolet;">Chennai super market</h1>
        <hr>
        <h3 style="color: deeppink; font-size: 45;">Chennai Super Market is a well-known retail store that offers a wide selection of groceries, fresh produce, and household essentials. Known for its quality products and reasonable prices, the store provides a convenient and pleasant shopping experience. With organized aisles, friendly service, and a variety of daily-use items, Chennai Super Market has become a trusted choice for many customers.</h3>
        <br>
        <h3 style="color: deeppink; font-size: 45;">Along with its wide variety of products, Chennai Super Market is appreciated for its neat arrangement and quick billing service, which helps customers save time. The store regularly updates its stock to offer fresh and new items, ensuring that shoppers always find what they are looking for. Whether it’s daily groceries, personal care items, or household supplies, the market provides everything under one roof, making it a dependable and convenient shopping spot for the community.</h3>
    </body>
</html>
shoe.html
<html>
    <body>
        <h1 align="center" style="color: darkred;">Bata shoe store</h1>
        <hr>
        <h3 style="color: darkorange; font-size: 35;">Bata Shoe Store is a trusted and popular footwear outlet known for its durable, comfortable, and affordable shoes. It offers a wide range of options, including school shoes, casual wear, sandals, and formal footwear for all age groups. With its reliable quality and customer-friendly service, Bata remains a go-to choice for everyday footwear needs.</h3>
        <hr>
        <h3 style="color: darkorange; font-size: 35;">👞 Product Range
Bata offers a diverse collection of footwear and accessories:

Men’s Footwear: Formal shoes, loafers, boots, sandals, sneakers, sports shoes.

Women’s Footwear: Heels, flats, sandals, wedges, casual sneakers, formal wear.

Kids’ Footwear: School shoes, casual sandals, sports shoes.

Accessories: Bags, belts, socks, and shoe care products.

Brands under Bata: Hush Puppies, North Star, Power, Comfit, Bubblegummers (kids), Weinbrenner.

💰 Pricing & Accessibility
Affordable Range: Everyday shoes priced from ₹500–₹1,500.

Premium Range: Branded collections like Hush Puppies and Weinbrenner range from ₹2,000–₹5,000.

Online Shopping: Available on Bata’s official website and marketplaces like Flipkart and Amazon.

Discounts: Seasonal sales often offer 50–80% off on select footwear</h3>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
