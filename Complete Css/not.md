# Text Property

## Text Align

```html
<style>
    #box1 {
        height: 200px;
        width: 200px;
        background-color: greenyellow;
        color: red;
        text-align: center;
    }
</style>

</head>
<body>

    <div id="box1">box</div>

</body>
</html>
```

---

## Text Decoration

```html
<style>
    #box1 {
        background-color: greenyellow;
        color: red;
        text-align: center;
        text-decoration: underline;
    }

    #link {
        text-decoration: none;
    }
</style>

</head>
<body>

    <div id="box1">Shivendra</div>
    <a href="#google" id="link">css.com</a>

</body>
</html>
```

### 1. `text-decoration: none;` se link ke niche ki line (underline) remove kar sakte hain.

---

## Text Decoration Color Property

```css
#box1 {
    background-color: greenyellow;
    color: red;
    text-align: center;
    text-decoration: underline;
    text-decoration-color: red;
}
```
## text- Transform

```html

            <style>      
                #txt{

                    text-transform: uppercase;
                    
                }
                #txt2{

                    text-transform: lowercase;

                }

            </style>
</head>
<body>
            <div id="txt">
            
            </div>
           
           

</body>
```
## Text Height

```html
 <style>      
                #txt{
                        line-height: 40px;
                    
                }
              
            </style>
</head>
<body>
            <div id="txt"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis excepturi aspernatur, eaque doloremque amet dignissimos, obcaecati vero iure incidunt dolor aperiam nam inventore natus ullam impedit porro, voluptas quibusdam! Nam!</p> </div>
            

</body>
```
### 1. line hight se line ke beech gap ata hai 



## Font Weight

```html
 <style>      
                #txt{
                       font-weight: 900;
                    
                }
              
            </style>
</head>
<body>
            <div id="txt"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis excepturi aspernatur, eaque doloremque amet dignissimos, obcaecati vero iure incidunt dolor aperiam nam inventore natus ullam impedit porro, voluptas quibusdam! Nam!</p> </div>
            

</body>
</html>
```

### 1. font weight 100 to 900 hota hai 


## Font Family

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playwrite+ID:wght@100..400&display=swap" rel="stylesheet">

            <style>      
           
#txt {
  font-family: "Playwrite ID", cursive;

}
              
            </style>
</head>
<body>
            <div id="txt"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis excepturi aspernatur, eaque doloremque amet dignissimos, obcaecati vero iure incidunt dolor aperiam nam inventore natus ullam impedit porro, voluptas quibusdam! Nam!</p> </div>
            
</body>
</html>
```
### 1. google font ki site se font la sakte hai phele uska code ka link lagana hai then style
