# Ex.07 Restaurant Website
## Date:7/10/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html
<html>
    <head>
        <title>
            Favour Hub
        </title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="title">
            <p>Favour Hub</p>
        <div class="quote">
            <p>Eat.Taste.Enjoy</p>
        </div>
        <div class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">contact-us</a>
        </div>
        <div class="footer">&copy; Dhivya R (25011460)</div>
    </body>
</html>

style1.css
body{
    background-image:url("Screenshot 2025-10-07 075443.png");
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display:flex;
}
.title{
    position: fixed;
    top:0;
    font-family:'serif','sans-serif','monospace','cursive';
    margin-left: 6px;
    font-size: 70px;
    font-weight: bolder;
    color:white;
}
.quote{
    position: absolute;
    bottom:20%;
    margin-left: 6px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bolder;
    font-size: large;
    color:green;
}
.link{
    position : fixed;
    top:0;
    @media(any-hover: hover){
        a:hover{
            background-color: red;

        }
    }
    margin-top: 50px;
    margin-left: 1060px;
    margin-right: 60px;
    font-family:' Arial', 'Helvetica',' sans-serif';
    font-size:24px;
}
.footer{
    position: fixed;
    bottom:0%;
    width: 100%;
    background-color:aqua;
    color:azure;
    text-align: center;
    padding:20px;
}  
menu.html
<html>
    <head>
        <title>
            Menu: Favour Hub
        </title>
          <link rel="stylesheet" href="style2.css">
        </head>
        <body> <div class="link">
        <a href="rest.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">admin</a>
        <a href="contact.html">contact-us</a>
        </div>
            <div class="title">
                <p>Favour Hub</p>
            </div>
            <div class="menu-box">
                <div class="menu-item">
                    <img src="Screenshot 2025-10-06 234557.png">
                    <h3>French fries- $2</h3>
                </div>
                <div class="menu-item">
                    <img src="Screenshot 2025-10-06 234702.png">
                    <h3>Sandwich-$4</h3>
                </div>
                <div class="menu-item">
                    <img src="Screenshot 2025-10-06 234456.png">
                    <h3>momos-$6</h3>
                </div>
                <div class="menu-item">
                    <img src="Screenshot 2025-10-06 235009.png">
                    <h3>cutlet- $1</h3>
                </div>
                <div class="menu-item">
                    <img src="Screenshot 2025-10-06 234821.png">                             "
                    <h3>chicken puff-$4</h3>
                </div>
style2.css
body{
    background-image:
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display: flex;
}
.title{
    position: relative;
    top:0;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    margin-left: 6px;
    font-size: 70px;
    font-weight: bolder;
    color:palevioletred;

}
.link{
    position: fixed;
    top:20;
    @media(any-hover: hover){
        a:hover{
            background-color:rgb(42, 44, 165);
        }
    }
    margin-top: 50px;
    margin-left: 1030px;
    margin-right:40px;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 24px;
}
.menu-box{
    align-items: center;
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 11px;
    padding: 25px;
    background-size: 80%;
    background-color: black;
}
.menu-item {
    background-color: mediumseagreen;
    background-size: 600px;
    padding: 2px;
    border-radius: 5px;
    text-align: center;
    border: 1px solid greenyellow;
}
.menu-item img {
    width: 101%;
    height: 100;
    border-radius: 5px;
    margin-bottom: 6px;
}
.menu-item h3 {
    margin: o;
    font-size: 10px;
    color:black;

}
.footer{
    position: fixed;
    bottom: 0;
    width: 101%;
    background-color: blue;
    color: white;
    text-align: center;
    padding: 9px;

}

admin.css
<html>
    <head>
        <title>
            Admin: Favour Hub
        </title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <div class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">admin</a>
            <a href="contact.html">contact-us</a>
        </div>
        <div class="title">
            <p>Favour Hub - Meet Our Team</p>
        </div>
        <div class="team-grid">
            <div class="team-item">
                <img src="my pic.jpg">
                <h2>Dhivya</h2>
                <p>CEO</p>
            </div>
            <div class="team-item">
                <img src="Screenshot 2025-10-06 235340.png ">
                <h2>Tamana</h2>
                <p>Manager</p>
            </div>
            <div class="team-item">
                <img src="Screenshot 2025-10-06 235443.png ">
                <h2>samantha</h2>
                <p>Master chef</p>
            </div>
            <div class="team-item">
                <img src="Screenshot 2025-10-06 235548.png">
                <h2>chyan vikram</h2>
                <p>owner</p>
            </div>
            <div class="team-item">
                <img src="Screenshot 2025-10-06 235413.png">
                <h2>hardhik pandiya</h2>
                <p>waiter</p>
            </div>
            <div class="team-item">
                <img src="Screenshot 2025-10-06 235621.png">
                <h2>vijay</h2>
                <p>HR Manager</p>
            </div>
        </div>
        <div class="footer">&copy; Dhivya R(25011460)</div>
    </body>
</html>

style3.css
body{
    background-image:url('Screenshot 2025-10-07 075443.png');
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display: flex;
}
.title{
    position: absolute;
    top:0;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    margin-left: 5px;
    font-size:60px;
    font-weight: bold;
    color:rgb(240, 21, 57)
}
.link{
    position: fixed;
    top: 0;
    @media(any-hover: hover){
        a:hover{
            background-color: pink;
        }
    }
    margin-top: 40px;
    margin-left: 1040px;
    margin-right: 50px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 22px;
}
.team-grid{
    /* align-items: center; */
    bottom:0;
    display:grid;
    grid-template-columns: repeat(6,1fr);
    gap: 30px;
    padding: 40px;
    max-width: 1200px;
    margin: 0 auto;
}

.team-item {
  background-color: rgba(239, 23, 156, 0.41);
  background-size: 200px;
  border-radius: 5px;
  text-align: center;
  border: 2px solid #460814;
  margin-top: 200px;
  height: 250px;
}
.team-item img {
  width: 120px;
  height: auto;
  border-radius:50%;
  border: 3px solid rgb(28, 202, 118);
  margin-bottom: 20px;
  margin-left: auto;
  margin-right: auto;
}
.team-item h2{
  margin: 0;
  font-size: 20px;
color: rgb(51, 2, 10);
}
.team-item p{
    margin: 0;
    font-size: 20px;
    color:rgb(93, 14, 27)
}
.footer{
  position: fixed;
  bottom: 0;
  width: 100%;
  background-color: rgb(119, 32, 46);
  color: rgb(231, 12, 220);
  text-align: center;
  padding: 10px;
}

contact.html
<html>
    <head>
        <title>
            contact-us: Favour Hub
        </title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body> <div class="link">
        <a href="rest.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">admin</a>
        <a href="contact.html">contact-us</a>
    </div>
    <div class="title">
        <p>Favour Hub</p>
    </div>
    <div class="grid">
        <h2>contact us</h2>
        <p>visit us</p>
        <p>19/paradise town,bangalore</p>
        <p>phone: +9876543210</p>
        <p>Email: Favourite123@gmail.com</p>
    </div>
    <div class="footer">&copy; Dhivya R (25011460)</div>
    </body>
</html>

style4.css

body{
    background-image:url('Screenshot 2025-10-07 134450.png') ;
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display: flex;
    align-items: center;

    }
.title{
    position: absolute;
    top: 10;
    font-family:'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', sans-serif;
    margin-left: 5px;
    font-size: 40px;
    font-weight: bolder;
    color:green;
}
.link{
    position: fixed;
    top:0;
    @media(any-hover: hover){
        a:hover{
            background-color: red;
        }
    }
    margin-top: 50px;
    margin-left: 1000px;
    margin-right: 40px;
    font-family: 'Georgia', 'Times New Roman', Times, serif;
    font-size: 24px;


}
.grid{
    margin-left: 1000px;
    border: black;
    background-color: violet;
    width: 200px;
    height: auto;
    text-align: center;
    padding: 30px;

}
.grid h2{
    font-size: 40px;
    color: orange;


}
.grid p{
    font-size: larger;
    color:black;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: yellow;
    color: black;
    text-align: center;
    padding: 11px;
}

```


## OUTPUT:
![alt text](<dhivya/restapp/Screenshot (24).png>)

![alt text](<dhivya/restapp/Screenshot (25).png>)
![alt text](<dhivya/restapp/Screenshot (26).png>)
![alt text](<dhivya/restapp/Screenshot (27).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
