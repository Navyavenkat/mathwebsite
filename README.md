# Web Page for Mathematical Calculations

## AIM:

To design a static website with validation to perform mathematical calculations in client side.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Write javascript to perform the calculations.

### Step 4:

Include regularexpression based input validation.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Volume</title>
    <style>
        * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:rgb(219, 245, 125);
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
}
.content {
  display: block;
  width: 100%;
  background-color: #92ebf1;
  min-height: 500px;
  margin-top: 150px;
}
.content2{
    display: block;
    width: 100%;
    background-color: #b33e65;
    min-height: 500px;
    margin-top: 150px;
    margin-bottom: 150px;
}
h1{
    text-align: center;
    padding-top: 50px;
    color: rgba(23, 36, 32, 0.438);
}
.formelement{
    text-align: center;
    font-size:xx-large;
    margin-top: 5px;
    margin-bottom: 5px;

}
    </style>
</head>
<body>
    <div class="container">
        <div class="content">
            <h1> VOLUME OF PYRAMID</h1>
            <form>
                <div class=formelement>
                    <lable for="aedit">BREATH:</lable>
                    <input type="text" id="aedit" value="0"/>
                </div><br>
                <div class=formelement>
                    <lable for="bedit">Height:</lable>
                    <input type="text" id="bedit" value="0"/>
                </div><br>
                <div class=formelement>
                    <input type="button" value="CALCULATE" id="calbutton"/>
                </div><br>
                <div class=formelement>
                    <lable for="cedit">Volume:</lable>
                    <input type="text" id="cedit" value="0"/>
                </div><br>
                <div class=formelement>
                    Formula is = (1/3) b h
                </div>
            </form>
        </div>
        <script type="text/javascript">
            var button;
            button=document.querySelector("#calbutton");
            button.addEventListener("click",function(){
                var atext,btext,ctext;
                var aval,bval,cval;
                atext=document.querySelector("#aedit");
                btext=document.querySelector("#bedit");
                ctext=document.querySelector("#cedit");

                aval=parseInt(atext.value);
                bval=parseInt(btext.value);
                cval=(22/7)aval*2(bval);
                ctext.value=""+cval;
            });
        </script>
        <div class="content2">
            <h1>VOLUME OF Ellipsoid</h1>
            <form>
                <div class="formelement">
                  <lable for="radiusedit">RADIUS 1:</lable>
                  <input type="text" id="radiusedit" value="0"/>
                </div><br>
                <div class="formelement">
                  <lable for="heightedit">RADIUS 2:</lable>
                  <input type="text" id="radiusedit" value="0"/>
                </div><br>
                <div class="formelement">
                    <lable for="heightedit">RADIUS 3:</lable>
                    <input type="text" id="radiusedit" value="0"/>
                  </div><br>
                <div class="formelement">
                  <input type="button" value="CALCULATE" id="calbutton2"/>
                </div><br>
                <div class="formelement">
                  <lable for="volumeedit">VOLUME:</lable>
                  <input type="text" id="volumeedit" value="0"/>
                </div><br>
                <div class="formelement">
                Formula is:ellipsoid = (4/3) pi r1 r2 r3 
                </div><br>
                
            </form>
    
            </div>
        </div>
        <script type="text/javascript">
          var button;
          button=document.querySelector("#calbutton2");
          button.addEventListener("click",function(){
            
              var radiustext,heighttext,volumetext;
              var aval,bval,cval;
    
              radiustext=document.querySelector("#radiusedit");
              heighttext=document.querySelector("#heightedit");
              volumetext=document.querySelector("#volumeedit");
      
              aval=parseInt(radiustext.value);
              bval=parseInt(heighttext.value);
              cval=(22/7)aval*2(bval/3);
              volumetext.value=""+cval;
        
      
            });
      
        </script>     
    </div>
    
</body>
</html>

```


## OUTPUT:

![GITHUB LOGO](maths.png)
## Result:

Thus a website is designed to perform mathematical calculations in the client side.
