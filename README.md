# jnl221_Elad
Oz's JNL221 Assignments page
<!-- Complete this worksheet in HTML and CSS. Instructions are as comments; you may use reference_sheet.html and the internet to jog your memory on HTML tags and CSS. -->

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Basic HTML</title>
        <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,400,300,600,700&subset=latin,latin-ext' rel='stylesheet' type='text/css'>
        
        <style>
        div{
  width: 100px;
  height: 100px;
  background: red;
  position: relative;
  animation: mymove 5s infinite;
}

@keyframes mymove {
  from {left: 0px;}
  to {left: 200px;}
}
h1 {border: 6px solid deepskyblue;
    font-family: cursive;
}
            .alert{
                height: 100px;
                width: auto;
                border: 2px solid black;
                margin: 5px auto;
                text-align: center;
            }

            #quote {font-style: italic;}

            #byline {
                color: deepskyblue;
            width: auto
            }
            
            .books{
                border: 1px solid maroon;
            }

            p {
                color: #A9A9A9;
                font-size: 16px;
                font-family: 'Open Sans', serif;
                width: 50%;
            }
            #quote {
                color: magenta;
                font-style: italic;
                border: solid lightskyblue 2px;
            }

            #bargraph {
                border: 1px solid gray;
                padding-left: 10px;
                padding-bottom: 10px;
                width: 25%;
            }
            .bar_label {
                color: red;
            }
            #longest {
                width: 300px;
                height: 10px;
                background: gray;
                border: 1px solid red;
            }
            #longer {
                
            }
            #long {
                
            }

        </style>
    </head>
    
    <body>

        <!-- Messing with CSS -->
        <div class="alert">
            <h3>Breaking News: Container ship knocks bridge down.</h3>
            <p id="byline">Reporting by JNL221</p>
        </div>
        <h1>Oz Elad!</h1>
        
        <div></div>
        
        
        <h2>My intro</h2>
        <!-- Include: a brief intro to yourself -- where you're from, what you like to do for fun, what you're studying, and who your community or family is. -->
        <!-- Tags to use: <p>, <strong>, <i> -->
        <p>My name is <strong>Oz Elad</strong>, and I am from <i>Tokyo, Japan</i>. I play <strong>basketball</strong>, and I study <i>Sport Management</i>.</p>

        <h2>My handles</h2>
        <!-- Include: at least two handles for your social media accounts -->
        <!-- Tags to use: <p>, <a> -->
        <p>This is <a href="https://www.google.com/" target="_blank">
        google.com</a>.</p>
    
        <h2> ~ Challenge: Why is my text maroon? ~</h2>
        <!-- Challenge! The text in your p tags is currently maroon. Figure out why and make it dark gray, using a hex code. (Hint: use google to find a hex code for a dark gray) When you're done, change the text in the <p> tag below to "My text is gray." -->
        <p>My text is gray.</p>


        <h2>My favorite meme</h2>
        <!-- Include: "large_wink.png" as an icmage -->
        <!-- Tags to use: <img> -->
        <!-- Hint! Use 'reference_sheet.html', which you downloaded with this file, to remember how to include an image. -->
        <img src="large_wink.png">
    
        <h2>Why I'm a great student</h2>
        <!-- Include: Use 'reference_sheet.html' to figure out how to add an unordered list here -->
        <!-- Tags to use: <ul>, <li>, <strong> -->
        <ul>
            <li>I work hard</li>
            <li>I ask a lot of questions</li>
            <li>I work well with others</li>
            <li>I enjoy learning</li>
        </ul>

    
        <h2>Top 3 most famous people from my hometown</h2>
        <!-- Include: an ordered list -->
        <!-- Tags to use: <ol>, <li>, <a> -->
        <ol type="1">
            <li>Hayao Miyazaki</li>
            <li>Yoko Ono</li>
            <li>Hideo Kojima</li>
        </ol>


        <h2> ~ Challenge: Read my poetry ~</h2>
        <!-- Challenge! Use the internet to figure out what a <br> tag is. Write a short poem about your college experience so far. -->
        <!-- Tags to use: <p> tags for your lines of poetry, and at least two <br> tags -->
        <p>
            The humidity lessens and the cool winds blow.<br>
            Getting to class becomes a trek.<br>
            The gym fills with people.<br>
            Ordering in becomes the move.<br>
        </p>
    

        <h2>This is one of my favorite quotes</h2>
        <!-- Include: a quote from a book -- quote should be in italics and gray, title of source should be in an <h3> tag -->
        <!-- Tags to use: <h3>, <p> with an id named 'quote' that is styled in the <style> section -->
         <h3>A Quote from 1984</h3> 
         <p id="quote">"We know that no one ever seizes power with the intention of relinquishing it."</p>  


        <h2>These are more of my favorite books</h2>
        <!-- Include: an unordered list of at least three books, list items should have a border -->
        <!-- Tags to use: <ul>, <li> with classes named 'book' that is styled in the <style> section -->
        <div class="books">
            <ul>
                <li>Animal Farm</li>
                <li>David and Goliath</li>
                <li>Outliers</li>
            </ul>
        </div>

        <h2>Here's how I normally spend my weekend</h2>
        <!-- Include: a complete Datawrapper chart (you can make up data) showing what you normally spend time on over the weekend; must include all requirements of a complete chart (hed, subhed, intentional colors, byline, etc.) -->
        <!-- Tags to use: <iframe> -->
        <iframe src="https://datawrapper.dwcdn.net/YqcRc/1/" title="How Oz Spends His Weekends"></iframe>


        <h3>~ Challenge: A very simple bar graph ~</h3>
        <!-- Challenge! Add CSS styles to '#longer' and '#long' to make the bar graph look like it's ordered from longest to shortest. (Use the CSS in #longest as a reference.) You may also change the h4 text and the p text to make this simple bar chart reflect real (or fake) data. -->

        <div id="bargraph">
            <h4>Length of bars</h4>
            <p class="bar_label">Longest</p>
            <div id="longest"></div>
            <p class="bar_label">Longer</p>
            <div id="longer"></div>
            <p class="bar_label">Long</p>
            <div id="long"></div>
        </div>
     
    </body>
</html>
