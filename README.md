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

## Layout CSS:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #fcfdfc;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/images.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #000000;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #f7f7f7;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #0a0a0a;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  color: white;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: white;
  font-size: larger;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~
## Home html:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Jithendra Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/download2.png" alt="Building" />
          <div class="contenttext">
            Epic Games, Inc. is an American video game and software developer and publisher based in Cary, North Carolina. 
The company was founded by Tim Sweeney as Potomac Computer Systems in 1991, originally located in his parents' house in Potomac, Maryland. 
Following his first commercial video game release, ZZT (1991), the company became Epic MegaGames, 
Inc. in early 1992 and brought on Mark Rein, who is the company's vice president to date. 
Moving their headquarters to Cary in 1999, the studio's name was simplified to Epic Games.
            <ul>
              <li>Game Over develops the Unreal Engine</li>
              <li>The developed video games, such as Fortnite and the Unreal, Gears of
                War and Infinity Blade series</li>
              <li>In 2014, Unreal Engine was named the "most successful videogame engine"
                by Guinness World Records.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169;  2021 Total gaming ltd, Developed by Jithendra.
      </div>
    </div>
  </body>
</html>
~~~
## product:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Age.png" alt="product image">
                  </div>
                  <div class="itemname">Age of Empires IV Cover</div>
                  <div class="itemprice">Price: Rs. 2,100 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Halo_Infinite.png"  alt="product image">
                  </div>
                  <div class="itemname">Halo Infinite</div>
                  <div class="itemprice">Price: Rs. 1,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Minecraft_cover.png"  alt="product image">
                </div>
                <div class="itemname">Mine Craft</div>
                <div class="itemprice">Price: Rs.1,500 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/Fallout.jpg"  alt="product image">
              </div>
              <div class="itemname">Fallout</div>
              <div class="itemprice">Price: Rs.3,000 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Overwatch.jpg"  alt="product image">
            </div>
            <div class="itemname">Overwatch</div>
            <div class="itemprice">Price: Rs.2,350 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/final fantasy.jpg"  alt="product image">
          </div>
          <div class="itemname">Final Fantasy</div>
          <div class="itemprice">Price: Rs.4,000 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/Mortal_Kombat.png"  alt="product image">
        </div>
        <div class="itemname">Mortal Kombat</div>
        <div class="itemprice">Price: Rs.4,500 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/Batman_Arkham_knight.jpg"  alt="product image">
      </div>
      <div class="itemname">Batman Arkham Knight</div>
      <div class="itemprice">Price: Rs.7,000 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/Until_Dawn_cover.jpg"  alt="product image">
    </div>
    <div class="itemname">Until Dawn cover</div>
    <div class="itemprice">Price: Rs.10,000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/League_of_Legends.png"  alt="product image">
  </div>
  <div class="itemname">League of Legends</div>
  <div class="itemprice">Price: Rs.12,000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/Days_Gone_cover_art.jpg"  alt="product image">
  </div>
  <div class="itemname">Days Gone Cover Art</div>
  <div class="itemprice">Price: Rs.13,750 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/Dark_Souls_Cover.jpg"  alt="product image">
  </div>
  <div class="itemname">Dark Soul Cover</div>
  <div class="itemprice">Price: Rs.17,000 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169;  2021 Total gaming ltd, Developed by:Jithendra.
      </div>
    </div>
  </body>
</html>
~~~
## people:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Company Leaders: </h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ceo.jpeg" alt="product image">
                  </div>
                  <div class="itemname">V.A.Jithendra</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/cto.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Sameer</div>
                  <div class="itemprice">CTO </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Rajesh.jpg"  alt="product image">
                </div>
                <div class="itemname">RAJESH</div>
                <div class="itemprice">VP </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/jeeva.jpg"  alt="product image">
                </div>
                <div class="itemname">JEEVA</div>
                <div class="itemprice">PRESIDENT</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/natrajan.jpg"  alt="product image">
                </div>
                <div class="itemname">NATRAJAN</div>
                <div class="itemprice">CCO </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Azim.jpg"  alt="product image">
                </div>
                <div class="itemname">AZIM</div>
                <div class="itemprice">SWFA </div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Total gaming ltd, Developed by:Jithendra.
      </div>
    </div>
  </body>
</html>
~~~
## contact us:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Total gaming ltd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <ul>
          <h1>Address:</h1>
            <li>NORTH CALIFORNIA<br></li>
            <h1>Contact:</h1>
            <li>760-767-9484<br></li>
            <h1>E-mail:</h1>
            <li>totalgaming.com<br></li>
            <br>VERIFIED*
        </ul>    
      </div>
  </div>
  </div>
  </div>
    <div class="footer">
      Copyright &#169; 2021 Total gaming ltd, Developed by:Jithendra.
    </div>
  </div>
</body>
</html>
~~~

## OUTPUT:

### Home Page:

![output 1](.\images\output1.png)
## product:
![output 2](output2.png)
## people:
![output 3]()
## contact us:
![output 4]()
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
