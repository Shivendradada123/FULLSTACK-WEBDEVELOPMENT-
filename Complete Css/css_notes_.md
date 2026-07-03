# CSS Notes 

## color property

```css
<style>

        h1{
         color: red;
        }
         p{
            color: pink;
         }

   </style>
</head>
<body>
    
<h1>Hello world </h1>
<p>hii my name is shivendra and i  am fullstack devloper</p>
```

## Inline Style 

```css
<p style="color: blue;">hii my name is shivendra and i  am fullstack devloper</p>
 <h2 style="color: pink;">I am Aditya</h2>
 ```


## Internal Style 

```css

<style>

        h1{
         color: red;
        }
         p{
            color: pink;
         }

   </style>
   ```


## External Css 

## 1. create a alag se 
## 2. link file 

```css

h1{
    color: red;
}

p{
    color: rgb(0, 182, 24);
    background-color: red
}

h2{
    color: aqua;
}
```

## Universal property
 
 ```css
    <style>

         *{
            color: green;
         }
   </style>
   ```
   ###  isse pure page me style hojeygi jo deng


   # Selectors

   ## 1. Id Selectors
   ## 2. Class Selectors
   ## 3. Group Selectors
   ## 4. Descendant Selectotrs

   ### ID Selectors
   
   ```css 

<style>

         #hello{
            color: hotpink;
         };
         #bio{
            color:aqua
         };
         #aditya{
            color: brown;
         };
   </style>
</head>
<body>

<h1 id="hello">Hello world </h1>
<p  id="bio">hii my name is shivendra and i  am fullstack devloper</p>
 <h2  id="aditya">I am Aditya</h2>

</body>
```

### 1. id unique honi chaiye 
### 2. id ko # se access karke style wagera karte hai

### Class Selectors

```css
  <style>
         .hello{
            color: hotpink;
         };
         .bio{
            color:aqua
         };
   </style>
</head>
<body>
<h1 class="hello">Hello world </h1>
<p  class="bio">hii my name is Aditya and i  am fullstack devloper</p>
 <h2  class="bio">I am Aditya</h2>

</body>
```
#### 1. css ko . se access karte hai aur css kisi bhi tag ki same ho sakti hai 


## Group Selectors

```css

 <style>
         .hello, #bio, p
         {
            color: hotpink;
         };
      
   </style>
</head>
<body>
<h1 class="hello">Hello world </h1>
<p  >hii my name is Aditya and i  am fullstack devloper</p>
 <h2  id="bio">I am Aditya</h2>

</body>
```
### 1. group selectors se ham kahi cheez ko ek sath style de satke hai chaie kisi bhi type ke selectotrs ho ek sath use ho jayega 


## Descendant Selectotrs