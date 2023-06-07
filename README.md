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

# Home.html :-
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Hariharan A.
      </div>
    </div>
  </body>
</html>
```

# Products.html :-
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/microsoft.png"  alt="product image">
                  </div>
                  <div class="itemname">Microsoft Book</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kaspersky.png"  alt="product image">
                  </div>
                  <div class="itemname">Kaspersky Antivirus</div>
                  <div class="itemprice">Price: Rs.5,400.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/adobe.png"  alt="product image">
                  </div>
                  <div class="itemname">Adobe Acrobat Pro</div>
                  <div class="itemprice">Price: Rs.5000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/nortan.png"  alt="product image">
                  </div>
                  <div class="itemname">Nortan Antivirus</div>
                  <div class="itemprice">Price: Rs.7,800.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Hariharan A.
      </div>
    </div>
  </body>
</html>
```

# People.html :-
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduScoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected">
          <a href="/static/people.html">People</a>
        </div>
        
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our PEOPLES :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Hari.png" alt="product image">
                  </div>
                  <div class="itemname">Hariharan A</div>
                  <div class="itemprice">Founder</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/nethraa.png"  alt="product image">
                  </div>
                  <div class="itemname">Nethraa J</div>
                  <div class="itemprice">Post: CEO</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mithra.png"  alt="product image">
                  </div>
                  <div class="itemname">Mithra Mukunda</div>
                  <div class="itemprice">Post: Research director</div>
              </div>
            
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/shanmathi.png"  alt="product image">
                  </div>
                  <div class="itemname">Shanmathi Shanmugam</div>
                  <div class="itemprice">Post: Product designer</div>
              </div> 

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Kothai.png"  alt="product image">
                  </div>
                  <div class="itemname">Kothai Kumarapandian</div>
                  <div class="itemprice">Post: manufacturing specialist </div>
              </div>

               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/prithvi.png"  alt="product image">
                  </div>
                  <div class="itemname">Prithvi raj</div>
                  <div class="itemprice">Post: Coordinator</div>
              </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 TCS Private Limited, Developed by Hariharan A.
      </div>
    </div>
  </body>
</html>
```

# Contact.html :-
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected">
          <a href="/static/contact.html">Contact us</a>
        </div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>TO CONTACT US :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/phone.png" alt="product image">
                  </div>
                  <div class="itemname">Call us:- </div>
                  <div class="itemprice">9094701002</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/email.png"  alt="product image">
                  </div>
                  <div class="itemname">Email us:-</div>
                  <div class="itemprice">edusoftpvt@gmail.com</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/location.png"  alt="product image">
                  </div>
                  <div class="itemname">Reach us:-</div>
                  <div class="itemprice">Block-87,Gandhi nagar,Chennai-81,Tamilnadu,India.</div>
              </div>
             

         </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 TCS Private Limited, Developed by Hariharan A.
      </div>
    </div>
  </body>
</html>
```

# OUTPUT:-

## Home Page :

![home](https://github.com/Hariharanashok/productcompanywebsite/assets/120353431/2aab247a-7235-40d1-abe9-e2ec9716c6e4)

## Product Page :

![image](https://github.com/Hariharanashok/productcompanywebsite/assets/120353431/33e987ce-7de6-4700-b4a7-0670c765fbdf)

## People Page :

![image](https://github.com/Hariharanashok/productcompanywebsite/assets/120353431/69ce818d-c8b9-433b-bf98-cc44b838e96f)

## Contact Us Page :

![image](https://github.com/Hariharanashok/productcompanywebsite/assets/120353431/c6346c2e-244e-41fd-bba0-4496e5813868)

## Result :

The program for designing company website for sale of products using HTML and CSS is completed successfully.
