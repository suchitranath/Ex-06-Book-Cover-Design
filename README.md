# Ex-06-Book-Cover-Design
Name: Suchitra Nath
Ref no: 23000325
Dept : IT

# AIM:
To develop a website to display the cover page design of a book.

# Design Steps:

# Step 1:
Create a new Django project and app.

# Step 2:
Create a static file directory and mention the changes in settings.

# Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

# Step 4:
Write down the code for book cover using HTML and CSS.

# Step 5:
Add images and other contents using CSS record a screenshot of it.

# Code:
```<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Book Coverpage</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('annebook.jpg');
             background-position: center;
             background-color: black;
             background-repeat: no-repeat;
         }
         .toptext{
             color:white;
             padding-left: 5px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
             
         }
         .tophr{
             color: orange;
              width: 180px;
         }
         hr{
             color: orange;
            
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
             align-items: center;
             justify-content: center;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 20px;
             line-height:normal;
         }
         .author{
             color:white;
             display:inline;
             position:relative;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             line-height: 5px;
              
             
         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

            
            
  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }
  
.footer {
    color:orange;
    padding-top:180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    margin-right: px;
}
.bottomhr { 
    color: red;
              width: 400px;

}
img {
    width: 100px;
    height: 100px;
    margin-right: 20px;
    vertical-align:right;
}
.edition {
    color:orange;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    line-height: bottom;
 
}


        </style>
        </head>
            <body>
                <div class="bookpage">
                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dutch-language diary</div>
                    <div class="tophr"><hr></div> 
               <div class="booktitle"><h1> THE DIARY OF A YOUNG GIRL</h1></div>
               <h3 class="sub-text">&nbsp;&nbsp;&nbsp;The Diary of a Young Girl, published on 25 June 1947 </h3>
                    <h3 class="sub-text">&nbsp;&nbsp;&nbsp;&nbsp;Often referred to as The Diary of Anne Frank</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="annefrank2.jpg"></h2>              
                      
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Anne Frank &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Packt></h3></div>
                    
                </div>
                </div> 
                
            </body>
        
    
</html>
```

# Output:



# Result:
Thus a website to display the cover page design of a book was successfully created.