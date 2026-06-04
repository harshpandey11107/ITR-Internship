1_CSS_Styling_Ways

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Different Ways To Apply CSS .</title>
    <!-- Style Tag Attribute for Styling. i.e Internal -->
    <!-- <style> 
        h1{
            color: goldenrod;
        }
    </style> -->

    <!--External File for Styling -->
    <!--Link tag to link the stylesheet css file with index.html file -->
    <!-- href-->
    <link rel ="stylesheet" href="style.css">
</head>
<body>
    <!--Inline Attribute of Styling. -->
    <h1 style="color: purple;">Heading</h1> 
    <h1>Heading</h1>
    

    <!-- Priorities Of CSS :-->
    <!--
        Priorites Arranged From Most to Least below :
        1. Inline CSS
        2. Internal/Embedded (with Style tag) CSS
        3. External CSS
    -->
</body>
</html>

CSS:- 

h1{
    color: blue;
} 

2_CSS_Fonts

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>

    </style>
    <link rel = "stylesheet" href="style.css">
    <!-- <link rel="preconnect" href="https://fonts.googleapis.com"> -->
    <!-- <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> -->
    <!-- <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet"> -->

    <title>CSS fonts</title>
</head>
<body>
    <h1>Main Heading.</h1>
    <!-- Your Default Font can be Different Based on your OS and Browser Being Used . -->
    <!--Time New Roman For Me -->

    <!-- Serifs Fonts Default Thick and thin Strokes -->
    <!-- San Serifs Strokes have even Width -->

    <!--To Import Fonts From Online -->
        <!-- https://fonts.google.com/ -->

    <p>Nature is the ultimate source of our well-being, surrounding us with endless beauty. It supplies everything we need to thrive, from the fresh air we breathe to the vibrant greenery that brings us peace. Whether it is the gentle rustling of leaves, a warm breeze, or the song of birds, simply observing the outdoors can quickly refresh a tired mind</p>

    <p>Nature is the ultimate source of our well-being, surrounding us with endless beauty. It supplies everything we need to thrive, from the fresh air we breathe to the vibrant greenery that brings us peace. Whether it is the gentle rustling of leaves, a warm breeze, or the song of birds, simply observing the outdoors can quickly refresh a tired mind</p>
    
    <p>Nature is the ultimate source of our well-being, surrounding us with endless beauty. It supplies everything we need to thrive, from the fresh air we breathe to the vibrant greenery that brings us peace. Whether it is the gentle rustling of leaves, a warm breeze, or the song of birds, simply observing the outdoors can quickly refresh a tired mind</p>
    
</body>
</html>

CSS:-


  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap');

body{
    /* font-family: Arial, Helvetica, sans-serif; */
    /* font-family: 'Poppins', sans-serif; */
    font-family: 'Roboto', sans-serif;
    font-weight: 500;
}


3_CSS_colors

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel = "stylesheet" href="style.css">
    <title>Colors in CSS</title>
</head>
<body>
       <h1> Colors In CSS</h1>
</body>
</html>

CSS:-

h1{
     /* color:red; */
     color:aqua;
     /* color:rgb(255,0,0); */
     /* color: rgb(0,255,0); */
     /* color: rgb(0,0,255); */
     color :rgb(255,0,100);
     /* Hex Code(color Picker) */
     color : #ffa53d;
     /*0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f */
     color : #ffffff;
     color : #000000;
     color : #343434;
     color : #676767;
     color : #cdcdcd;
     color : #ff00ff;
    
     background-color: aqua;

}

4_CSS_Selectors

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>CSS Selectors</title>
</head>
<body>
    <!-- id Selector -->
    <div id="main-heading">
       <h1> MAIN HEADING </h1>
    </div>

    <!-- class Selector-->
    <div class="main-section">
        <h2>SUB HEADING </h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsa, quas at mollitia harum beatae dolore facilis enim? Veniam quam assumenda fugiat accusamus, laborum, quaerat, quisquam atque mollitia earum sint adipisci!</p>
        <!--Home && End Key #start and End of Line of Code-->
        <!--Ctrl + Enter # to new Line. -->
        <!--Ctrl + / # to Comment out the Line.-->
    </div>

    
</body>
</html>

CSS:-

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap');

body{
    font-family: sans-serif;
    font-family: Arial, Helvetica, sans-serif;
}

/* ID selector --> # tag */
#main-heading{
    background-color: #cdcdcd;
}

/* Class Selector --> . tag */
.main-section{
    background-color: #efefef;
}

p{
    color: blueviolet;
    font-weight: 400;
}

/*
Developers :

 id vs Classes.
 id --> less Used  --> Dont Use Same id Twice on One Pafe.
 class --> most Used --> Classes Can be used multiple times.

 Web Theme:
 Utility Classes(pre-made classes for multi use):
 */

 .text-red{
    color : red;
 }

 .text-green{
    color : green;
 }

 .bg-grey{
   background-color:  #cdcdcd;
 }

 .bg-dark {
    background-color: rgb(42, 41, 41);
 }


5_UtilityClass_ID_Class

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel = "stylesheet" href="style.css">
    <title>Utility Classes && ID && Class</title>
</head>
<body>
    <div class="main-header">
       <h1 id="main-heading">Main Header</h1>
    <ul>
        <li>item</li>
        <li>item</li>
        <li>item</li>
    </ul>
       
    </div>


    <div class="blog-section">
      <h2 id="blog-heading1">My First Blog</h2>
      <p class="blog-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores tenetur officiis repudiandae voluptatibus dolorum non quasi, pariatur cum, exercitationem atque ratione odit ut reprehenderit aliquam doloremque facilis consequatur provident. <span style="background-color: aqua;"> quam ratione ex error. Vel quos ut obcaecati facere magnam nemo dolore ipsam nobis,</span> quo delectus minima culpa ab labore tempore sequi, ea consectetur laborum ipsa, consequuntur voluptates veniam sed ratione velit. Sed, eum. Ex quibusdam porro voluptates error, itaque maxime possimus rem perspiciatis quos consequatur praesentium omnis voluptas voluptate labore neque et repellat in distinctio vel fugiat. Provident, dolores unde et sed dicta illo quo neque laboriosam dolore quos!</p>
    </div>

      <div class="blog-section">
      <h2 id="blog-heading2">My Second Blog</h2>
      <p class="blog-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores tenetur officiis repudiandae voluptatibus dolorum non quasi,<span style="background-color: aqua;"> pariatur cum, exercitationem atque ratione odit ut reprehenderit </span>aliquam doloremque facilis consequatur provident. Quae quam ratione ex error. Vel quos ut obcaecati facere magnam nemo dolore ipsam nobis, quo delectus minima culpa ab labore tempore sequi, ea consectetur laborum ipsa, consequuntur voluptates veniam sed ratione velit. Sed, eum. Ex quibusdam porro voluptates error, itaque maxime possimus rem perspiciatis quos consequatur praesentium omnis voluptas voluptate labore neque et repellat in distinctio vel fugiat. Provident, dolores unde et sed dicta illo quo neque laboriosam dolore quos!</p>
    </div>

    </div>
</body>
</html>

CSS:-

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap');

body{
    font-family: sans-serif;
    font-family: Arial, Helvetica, sans-serif;
}

/* ID selector --> # tag */
#main-heading{
    color: darkolivegreen;
}

/* Class Selector --> . tag */
.main-section{
    background-color: #efefef;
}

/* p{ 
    color: blueviolet;
    font-weight: 400;
}*/

/*
Developers :

 id vs Classes.
 id --> less Used  --> Dont Use Same id Twice on One Pafe.
 class --> most Used --> Classes Can be used multiple times.

 Web Theme:
 Utility Classes(pre-made classes for multi use):
 */

 .text-red{
    color : red;
 }

 .text-green{
    color : green;
 }

 .bg-grey{
   background-color:  #cdcdcd;
 }

 .bg-dark {
    background-color: rgb(42, 41, 41);
 }

 /* CSS Exercise 1 */

 .main-header{
    background-color: rgb(215, 226, 223);
 }

 .blog-section{
    background-color: beige;
}
 #blog-heading1{
    color: purple;
 }
 #blog-heading2{   
     color: purple;
 }

 .blog-content{
    color: blueviolet;
    font-weight: 400;
 }

 6_More_CSS_Selectors

 html:-

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">

    <title> More CSS Selectors</title>
</head>
<body>

    <header>

        <p>short paragraph inside header</p>
        <h1 class="main-logo">Main Logo</h1>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Contact</a></li>
        </ul>
        <!-- Alt + Shift + Down (copy previous line down) -->
        <p>short paragraph inside header</p>

    </header>

    <main>
        <h2> Main Content Of Our Webpage.</h2>

        <section class="my-articles">

            <h2>Articles Section</h2>
            <article>
                <h2> Article heading </h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio, totam eaque! Voluptatibus minima inventore laborum, molestiae suscipit nulla amet atque sed debitis illum nisi quibusdam animi! Vero cumque explicabo tempora. Esse explicabo consequuntur eligendi amet ratione est blanditiis dignissimos repellat. Doloribus cum incidunt eum laboriosam harum odit vitae provident esse.</p>
            </article>
        
        
            <article>
                <h2> Article heading </h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio, totam eaque! Voluptatibus minima inventore laborum, molestiae suscipit nulla amet atque sed debitis illum nisi quibusdam animi! Vero cumque explicabo tempora. Esse explicabo consequuntur eligendi amet ratione est blanditiis dignissimos repellat. Doloribus cum incidunt eum laboriosam harum odit vitae provident esse.</p>
            </article>
        </section>
    </main>
    
</body>
</html>

CSS:-

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap');

/*

Universal Selector '*' 
*{
    color:plum;
}
*/
 header{
    background-color: #f2e9e9 ;
    font-family: Arial, Helvetica, sans-serif;
 }

 section.my-articles{
   background-color: #f2e9e9;
 }

 header p{
    color:blueviolet;
 }

 li a {
    font-weight: 700;
    font-family: Arial, Helvetica, sans-serif;
    color:blue;
 }

 /* 
 // It Changes All h2 inside the section
 
 section.my-articles h2{ 
    font-family: sans-serif;
    color: green;
 }

 */

  /* Change the direct Child */
 section.my-articles > h2{    
    font-family: sans-serif;
    color: green;
 }

 /* Changes paragraph directly after h2 anywhere 
 h2+p{
    color : orangered;
 }
*/
 /* Changes paragraph directly after ul anywhere */
 ul+p{
    color :darkmagenta;
 }

/* Changes paragraph directly after h2 where section is myarticles */
section.my-articles h2+p{
    color : orangered;
 }


7_CSS_AttributeSelector

html:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel = "stylesheet" href="style.css">
    <title>Attribute Selector</title>
</head>
<body>
    <!-- shift + alt + downarrow -->
    <h2> Links </h2>
    <ul>       
        <!-- a -anchor tag-->
        <!--input tag-->
        <li>    <a href ="https://google.co.in">Google In</a><br> </li>
        <li>    <a href ="https://google.co.uk">Google Uk</a><br>  </li>
        <li>    <a href ="https://flipkart.com">Flipkart </a><br> </li>
        <li>    <a href ="facebook.com">facebook</a><br>  </li>
    </ul>
    
    <h2>Form</h2>
    <form>
        <label for="fname">First Name : </label><br>
        <input type="text" id="fname"> <br>
        <label for="lname">Last Name : </label><br>
        <input type="text" id="lname"> <br>
        <label for="pass">password : </label><br>
        <input type="password" id="pass"> <br> <br>
        <input type = "button" value="submit">
    </form>
</body>
</html>

CSS:-

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500;700&family=Roboto:wght@400;500;700;900&display=swap');

input[type = "password"]{
    color : purple;
}
input[type = "text"]{
    color : red;
    background-color : aqua;
}

/* 
a[href ="https://google.co.in"]{ 
    color: red;
}
*/

/*
 Universal Selector 
 used for Particular word
*/
a[href *="google"]{ 
    color: red;
}

/*caret Symbol*/
a[href ^="https"]{ 
    color: green;
}

a[href $=".com"]{ 
 color: red;
}

input[type ^="t"]{ 
    color: green;
}
input[password ^="t"]{ 
    color: rebeccapurple;
}g