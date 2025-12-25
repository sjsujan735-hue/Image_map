# Ex04 Places Around Me
# Date:24/11/25
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<!DOCTYPE html>
<html>
    <head>
        <center>
        <title>Image mapping</title>
        </center>
    </head>
    <body>
        <center>
        <img src="c:\Users\admin\Desktop\gmap-tutorial-google-map-provider.jpg" 
         title="food" alt="food" 
          usemap="#mapping">
        </center>

        <map name="mapping">
            <area shape="circle" coords="25,122,48" title="Circle" href="file:///C:/Users/admin/Desktop/WEB/image%20map/Burger%20king.html">
            <area shape="circle" coords="321,214,18" title="Circle" href="file:///C:/Users/admin/Desktop/WEB/image%20map/pizzahut.html">
            <area shape="circle" coords="427,350,12" title="Circle" href="file:///C:/Users/admin/Desktop/WEB/image%20map/starbucks.html">
        </map>
    </body>
</html>

burgerking.html

<html>
    <head>
        <title>BURGER KING</title>
    </head>
    <body bgcolor="violet">
        <center>
            <h3><i><b>Burger King</b></i></h3>
            <img src="c:\Users\admin\Downloads\Red and White Modern Burger Logo.png" style="width:150px;">
            <hr>
            <h3><b><i>Current Deals</i></b></h3>
        </center>
            <table>
                <style>
                    table,th,td{border:2px solid black;
                   border-collapse:collapse;}
                   </style>
                   <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\images (6).jpg" style="width:350px;" >
                        <p>American fast-food franchise, It now has approximately 16,000 outlets all across the globe. It was initially known for its all Americano meals of burgers, fries, and shakes; the organization has grown since then and has introduced a wider variety of
                        </p>
                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\images (7).jpg" style="width:350px;" >
                        <P>Avail Flat 50% Off Code on Orders over ₹229 - Offer for new users | Burger King Promo Codes updated 5 minutes ago | Also, Check Burger King Signup Offers.
                        </P>

                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\hq720.jpg" style="width:350px;">
                        <p>Burger King India offers a variety of deals, including:2 for 79 or 99: Two Crispy Veg Burgers for ₹79 or two Crispy Chicken Burgers for ₹99, valid for dine-in or takeaway</p>
                            
                    </td>
                   </tr>
            </table>
    </body>
</html>

starbucks.html

<html>
    <head>
        <title>STARBUCKS</title>
    </head>
    <body bgcolor="violet">
        <center>
            <h3><i><b>starbucks</b></i></h3>
            <img src="c:\Users\admin\Desktop\images (5).jpg" style="width:150px;">
            <hr>
            <h3><b><i>Current Deals</i></b></h3>
        </center>
            <table>
                <style>
                    table,th,td{border:2px solid black;
                   border-collapse:collapse;}
                   </style>
                   <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\1695989234543.jpg" style="width:350px;" >
                        <p>Customize your drink
                            Make your drink just right with an extra espresso shot or a dash of your favorite syrup.
                        </p>
                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\images (9).jpg" style="width:350px;" >
                        <P>Food and drinks at a discount: Starbucks has offered food and drinks at a discount on Swiggy and Zomato. 
                            25% off handcrafted coffees: New Starbucks Rewards members can get 25% off their next three handcrafted coffees. 
                            
                    </P>

                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\download (1).jpg" style="width:350px;">
                        <p>Free drink with purchase: New Rewards members can get a free drink with purchase. 
                            Earn stars: Starbucks Rewards members earn one star for every ₹400 spent with a Starbucks card, or every ₹500 spent with other payment methods. 
                            Starbucks Rewards members also get exclusive offers and privileges. </p>
                            
                    </td>
                   </tr>
            </table>
    </body>
</html>

pizza.html

<html>
    <head>
        <title>Pizza Hut</title>
    </head>
    <body bgcolor="violet">
        <center>
            <h3><i><b>Pizza Hut</b></i></h3>
            <img src="c:\Users\admin\Downloads\Colorful Playful Illustrative Mascot Pizza Logo.png" style="width:150px;">
            <hr>
            <h3><b><i>Current Deals</i></b></h3>
        </center>
            <table>
                <style>
                    table,th,td{border:2px solid black;
                   border-collapse:collapse;}
                   </style>
                   <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\momo-mia-meal-for-1-veg.bfb5f5e59e080933cfaf8f1adcc3b194.1.jpg" style="width:350px;" >
                        <p>Enjoy a combo of 1 Veg Momo Mia! personal pizza with 1 Pepsi PET bottle.Fridays are when Pizza Hut lets you eat all the pizza there is. For INR 249, you can have as many vegetarian slices as you want and that includes personal pizzas too. And for INR 299, it's a delight for those who prefer meat on their pies. The slices are medium pan pizza slices and cannot be shared.
                        </p>
                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\Pizza-Hut-Unlimited-Offer (2).jpg" style="width:350px;" >
                        <P>The perfect "We Time" meal. Choose any 2 Melts flavour & enjoy with 1 Exotica Veggie Garlic Bread & 1 Pepsi PETFridays are when Pizza Hut lets you eat all the pizza there is. For INR 249, you can have as many vegetarian slices as you want and that includes personal pizzas too. And for INR 299, it's a delight for those who prefer meat on their pies. The slices are medium pan pizza slices and cannot be shared.
                        </P>

                    </td>
                    </tr>
                    <tr>
                    <td>
                        <img src="c:\Users\admin\Desktop\images (4).jpg" style="width:350px;">
                        <p>Pizza & Classic Bread Stix 2 Personal Pizza&Classic Bread Stix Fridays are when Pizza Hut lets you eat all the pizza there is. For INR 249, you can have as many vegetarian slices as you want and that includes personal pizzas too. And for INR 299, it's a delight for those who prefer meat on their pies. The slices are medium pan pizza slices and cannot be shared.
                        </p>
                    </td>
                   </tr>
            </table>
    </body>
</html>
```


# OUTPUT
<img width="1920" height="1200" alt="392504288-8b46d874-08a7-4fab-a899-4ddfa409e1b2" src="https://github.com/user-attachments/assets/41152c2f-5e65-461b-8f2c-ce4049e35e4b" />
<img width="1838" height="1095" alt="393502285-b4fb06ea-fb5c-4015-b4cd-6004d996527f" src="https://github.com/user-attachments/assets/d63c625f-cefc-4a9c-a106-3e52d878b579" />
<img width="1798" height="1023" alt="392504616-0d0627f4-89f5-494a-9ae4-4b329679a728" src="https://github.com/user-attachments/assets/4244f4e0-c557-4f36-8842-8d2357587d6e" />
<img width="1783" height="1015" alt="392504810-d2e38521-2462-408a-938a-831c66fa644a" src="https://github.com/user-attachments/assets/94453b08-76dc-4023-987c-ce72858d85fa" />

# RESULT
The program for implementing image maps using HTML is executed successfully.
