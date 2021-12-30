# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

### PROGRAM :
### HOMEPAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dhanush Industries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Dhanush Industries Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="	https://img.freepik.com/free-vector/industry-logo_23-2147512323.jpg?size=338&ext=jpg" alt="Building" />
          <div class="contenttext">
            designs and manufactures mobile communication devices, personal computers, portable digital music players and digital watches.
             The company also sells a range of relatedsoftware, services, accessories, networking solutions, music and entertainment streaming,
            as well as third-party digital content and applications.
            <br />
            Computer hardware components are fixed parts that make up a personal computer, on which software and operating systems are installed. Mass-market consumer computers use highly homogeneous components that are simple for end users to assemble without assistance. Standard desktop computers contain the following hardware components: a power supply, motherboard, and hard disk.
             Monitors, keyboards, and mice are external hardware devices that also connect to personal computers.We could make that for you
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Dhanush Industries Private Limited, Developed by S Dhanush.
      </div>
    </div>
  </body>
</html>
~~~
### Peoplepage:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dhanush Industries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Dhanush Industries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board Of Directors :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a13.jpg"alt="People">
                  </div>
                  <div class="itemname">Mr.Chandrasekar</div>
                  <div class="itemprice">Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a14.jpg" alt="People">
                  </div>
                  <div class="itemname">Advani Davada</div>
                  <div class="itemprice">Co-Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a15.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Rajesh</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a16.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. saurabh agarwal</div>
                  <div class="itemprice"> CEO </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by S Dhanush
      </div>
    </div>
  </body>
</html>
~~~
### PRODUCT PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dhanush Industries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Dhanush Industries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Softwares We Offer :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Iphone 11</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone Xr</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus Nord</div>
                  <div class="itemprice">Price: Rs.25,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus 7t</div>
                  <div class="itemprice">Price: Rs.17,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus 9</div>
                  <div class="itemprice">Price: Rs.65,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus 9r</div>
                  <div class="itemprice">Price: Rs.29,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a7.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone 13 pro max</div>
                  <div class="itemprice">Price: Rs.140,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a8.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone 12</div>
                  <div class="itemprice">Price: Rs.90,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a9.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone 13 mini</div>
                  <div class="itemprice">Price: Rs.60,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a10.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone SE</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a11.jpg"  alt="product image">
                  </div>
                  <div class="itemname">oneplus 9 pro</div>
                  <div class="itemprice">Price: Rs.55,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a12.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Iphone 12 pro max</div>
                  <div class="itemprice">Price: Rs.1,00,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Dhanush Indusries Private Limited, Developed by Dhanush
      </div>
    </div>
  </body>
</html>
~~~
### CONTACT PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dhanush Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Dhanush Indusries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <img src="https://cdn.corporatefinanceinstitute.com/assets/Industry.jpeg" alt="Building" />
          <div class="contenttext">
            CIT Nagar,Nandanam,Chennai
          </div>
          <h1>Phone:</h1>
          <div class="contenttext">
              Mr.Rajesh(HR):8569741230<br/>
              Mr.Praneet(Assistant HR):9865327415
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:sales@Dhanush Indusries Private Limited.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by S Dhanush
      </div>
    </div>
  </body>
</html>
~~~


## OUTPUT:

### Home Page:

![HomePage](homepage.png)

### People Page:

![PeoplePage](peoples.png)

### Product Page:

![ProductPage](product1.png)
![ProductPage](product2.png)

### ContactUs Page:
![ContactUsPage](contactus.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
