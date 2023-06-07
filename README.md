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

## PROGRAM :
### sample.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAMSUNG PRIVATE LIMITED</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/img1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>SAMSUNG PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/img1.png" alt="Building" />
          <div class="contenttext">
            SAMSUNG PRIVATE LIMITED  is the exclusive dealer for SAMSUNG across Tamil Nadu and runs world class 4S (Sales, Service, Spares, Systems) facilities across the state. Trusted by many proud owners and adding more to the BMW family, SAMSUNG PRIVATE LIMITED continues to remain committed in setting high benchmarks in sales and after sales in the luxury automotive sector across Tamil Nadu in Chennai, Ambattur, Coimbatore and in Puducherry.

            SAMSUNG PRIVATE LIMITED team works with one motto – providing you with facts and details to make an informed decision and thereby helping you find the right BMW for yourself. We believe that it is essential to completely understand customer requirements and showcase the options that would best match his or her style, comfort and finances. All of this is further made easy by financing and leasing options made available by our BMW Financial Services team.

            SAMSUNG PRIVATE LIMITED takes great pride in its state-of-art BMW Certified Service facilities across Tamil Nadu. Each of these facilities is fully equipped equipment and BMW trained technicians. With all these facilities we are ready to cater to our customers’ desires and exceed with SAMSUNG their expectations.

You know you have come to the right place when you reach a SAMSUNG PRIVATE LIMITED facility. Feel free to walk into any of our facilities across Tamil Nadu or call us. It would be our pleasure to welcome you to any of our offices at your convenience. We look forward to share the sheer driving pleasure experience of a BMW with you.
            <br />
            
            <ul>
              <li>MODERN</li>
              <li>LUXURY</li>
              <li>CLASSIC</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 SAMSUNG PRIVATE LIMITED DEVELOPED BY Tejusve Kabeer.F.
      </div>
    </div>
  </body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAMSUNG Private Limited</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>SAMSUNG PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/a23.png" alt="product image">
                  </div>
                  <div class="itemname">SAMSUNG A23</div>
                  <div class="itemprice">Price: Rs:19k</div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m53.png"  alt="product image">
                  </div>
                  <div class="itemname">SAMSUNG M53</div>
                  <div class="itemprice">Price: Rs:26k </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m33.png" alt="product image">
                  </div>
                  <div class="itemname">SAMSUNG M33</div>
                  <div class="itemprice">Price: Rs:20k</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/m52.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG M52</div>
                <div class="itemprice">Price: Rs:30k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/a54.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG A54</div>
                <div class="itemprice">Price: Rs:28k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/a34.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG A34</div>
                <div class="itemprice">Price: Rs:25k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s23.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG S23</div>
                <div class="itemprice">Price: Rs:75k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s22.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG S22</div>
                <div class="itemprice">Price: Rs:1L</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s21.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG S21 FE</div>
                <div class="itemprice">Price: Rs:21k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/flip4.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG Z Flip4</div>
                <div class="itemprice">Price: Rs:89K</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/fold4.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG Z Fold4</div>
                <div class="itemprice">Price: Rs:70k</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/f54.png" alt="product image">
                </div>
                <div class="itemname">SAMSUNG F54</div>
                <div class="itemprice">Price: Rs:40K</div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 SAMSUNG PRIVATE LIMITED DEVELOPED BY Tejusve Kabeer.F.
      </div>
    </div>
  </body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAMSUNG PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>SAMSUNG PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/cm.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Lee Kun-hee (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/he.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Dipesh Shah (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/he1.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                 Vineet Taneja (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/m.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Vipin Agrawal (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/m1.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Piyush Saxena (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/dm.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                   ISHAN SAXENA (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 SAMSUNG PRIVATE LIMITED DEVELOPED BY Tejusve Kabeer.F.
      </div>
    </div>
  </body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAMSUNG PRIVATE LIMITED </title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>SAMSUNG PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:6A,Thirumangalaam main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;9934567789</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <li><b>&emsp;Shop Manager Number:</b>7010586334</li>
                        <li><b>&emsp;Email Id:</b>&emsp;samsungprivatelimited1@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;samsungprivatelimited2@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 SAMSUNG PRIVATE LIMITED DEVELOPED BY Tejusve Kabeer.F.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:

### Home Page
![p1](https://github.com/kaviya2839/productcompanywebsite/assets/120553351/604a7a1d-442c-449e-84d0-572e44ecac36)

### product
![p2](https://github.com/kaviya2839/productcompanywebsite/assets/120553351/3552052f-5ba1-4949-8655-f03c812e192e)

### people
![p3](https://github.com/kaviya2839/productcompanywebsite/assets/120553351/cd073b22-814a-40f3-8ed5-567003c7ae5e)

### contact
![p4](https://github.com/kaviya2839/productcompanywebsite/assets/120553351/d11631cb-0114-4b3d-9587-ff5c7c75ab45)

## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
