# Ex.05 Book Front Cover Page Design
## Date: 26.05.2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Book Cover</title>

<style>

body{
    margin:0;
    padding:20px;
    background:#d9ecff;
    font-family:Georgia, serif;
}

.book{
    width:700px;
    margin:auto;
    padding:40px;
    border:3px solid #0b4a91;
    border-radius:15px;

    background-image:url('background.jpg');
    background-size:cover;
    background-position:center;

    box-sizing:border-box;
}

h1{
    color:#003c80;
    font-size:42px;
    margin-bottom:10px;
    text-align:center;
}

.line{
    height:3px;
    background:#003c80;
    margin-bottom:25px;
}

.about-title{
    font-size:32px;
    font-weight:bold;
    color:#003c80;
    margin-bottom:15px;
}

.content{
    font-size:20px;
    line-height:1.7;
    color:#222;
    text-align:justify;
}

.highlight{
    background:yellow;
    padding:2px 5px;
}

.quote{
    margin-top:30px;
    background:#e8edf4;
    padding:20px;
    text-align:center;
    font-size:24px;
    font-style:italic;
    color:#003c80;
    border-left:6px solid #0056b3;
}

.author-box{
    margin-top:40px;
    background:white;
    padding:25px;
    border-radius:15px;

    display:flex;
    align-items:center;

    box-shadow:0px 4px 12px rgba(0,0,0,0.2);
}

.author-box img{
    width:130px;
    height:300px;
    object-fit:cover;

    border-radius:12px;
    border:4px solid #004a99;

    margin-right:25px;
}

/* Neat coat style effect */
.author-box img:hover{
    transform:scale(1.02);
    transition:0.4s;
}

.author-name{
    font-size:32px;
    font-weight:bold;
    color:#003c80;
}

.author-text{
    margin-top:10px;
    font-size:18px;
    line-height:1.7;
    color:#333;
}

.footer{
    margin-top:50px;

    background:#004a99;
    color:white;

    padding:20px 25px;

    border-radius:0px 0px 10px 10px;

    display:flex;
    justify-content:space-between;
    align-items:center;

    font-size:20px;
}

.publisher{
    color:#ffd400;
    font-weight:bold;
    font-size:28px;
}

.price{
    color:#ffd400;
    font-weight:bold;
    font-size:28px;
}

</style>

</head>

<body>

<div class="book">

    <h1>You and Me Its Complicated</h1>

    <div class="line"></div>

    <div class="about-title">
        About the Book
    </div>

    <p class="content">

        This book 
        <span class="highlight">
            "You and Me Its Complicated"
        </span>

        is a romantic drama novel by Aditya Nighhot. The story follows Aditya, a quiet and nerdy college student, who falls deeply in love with Rutuja, a popular girl in college.
        
        Their relationship goes through emotional ups and downs, misunderstandings, heartbreak, friendship, and personal struggles.

             The book mainly talks about:

                    * Love and complicated relationships
                    * Friendship and trust
                    * Emotional pain and self-discovery
                    * How love can change a person’s life

    </p>

    <div class="quote">

      “Love is simple, but feelings make it complicated.”

    </div>

    <div class="author-box">

        <!-- Your Photo -->
        <img src="book author.jpeg" alt="Suwetha Thiyagarajan">

        <div>

            <div class="author-name">
                Suwetha Thiyagarajan
            </div>

            <div class="author-text">

               Suwetha Thiyagarajan is a young and creative writer who wrote the romantic story You And Me Its Complicated. Her writing focuses on emotions, friendship, trust, and complicated relationships between people.
               
               Through this book, she expresses how love can bring happiness, confusion, pain, and personal growth at the same time.

                She presents relatable college-life emotions and shows the importance of understanding, trust, and strong bonds in relationships.
                
                Her simple writing style makes readers connect easily with the characters and feelings in the story.

“Love may be complicated, but true feelings always remain special.”
            </div>

        </div>

    </div>

    <div class="footer">

        <div>

            <div class="publisher">
                SEC Publishers
            </div>

            Printed in India

        </div>

        <div>
            Price: <span class="price">₹1000</span>
        </div>

    </div>

</div>

</body>
</html>


---


## OUTPUT:


![alt text](<Screenshot 2026-05-26 134432.png>)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
