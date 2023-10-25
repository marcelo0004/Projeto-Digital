<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital</title>
</head>
<body>
    <header>
        <div class="tittle">
            <h1>Figma</h1>
        </div>

            <ul>
                <a href="#"><li>Products</li></a>
                <a href="#"><li>Pricing</li></a>
                <a href="#"><li>Community</li></a>
                <a href="#"><li>Resources</li></a>
            </ul>

            <input class="butao" type="submit" value="Get Started">
    </header>
    <main> 
        <aside>
            <div class="text">
            <h2>Unleash Your </h2>
            <h2>Creativity With</h2>
            <h2>Figma</h2> 
            <input class="botaobaixo" type="submit" value="Try Figma Free">
        </div>
            
        <aside>
            <div class="img">
                <img src="4cc623b1-a6ad-4bc2-bc2d-902301a7355e-removebg-preview (1).png" alt="logopng">
            </div>
    
    </main>
    </body>
</html>


body {background-color: rgb(0, 0, 0); color: white; font-family: Work Sans, sans-serif; max-width: 1200px; margin: 0 auto; padding: 10px}
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@500&display=swap');

header {display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;}

.tittle {display: flex;
flex-direction: column;}

li {display: inline-block; margin: 10px;}

h1 {font-weight: 1200; margin-left: 35px;}

a {color: white}

a:hover {color: rgb(102, 2, 196); transition: 0.3s all;}

.botaobaixo {background-color: rgb(243, 53, 53); color: white; height: 50px; width: 150px; border-radius: 8px; 
     font-size: 16px; font-weight: 550;
    border-color: transparent;}
h2 {font-size: 75px; line-height: 13px; font-weight: 100;;}

main {display: flex; flex-direction: row; margin-top: 50px;}

.text {margin-top: 110px; margin-left: 20px;}

.botaobaixo:hover {background-color: rgb(92, 0, 179); transition: 0.5s all;}

img {position: absolute; right: 6rem; top: 4.5rem; margin-top: 56px;}

ul {position: absolute; left: 25rem;}

.butao {background-color: rgb(243, 53, 53); color: white; height: 40px; width: 115px; border-radius: 11px; 
    font-size: 16px; font-weight: 550;
   border-color: transparent; margin-right: 35px; margin-top: 3px;}

   .butao:hover {background-color: rgb(106, 0, 206); transition: 0.5s all;}

header {background-color: rgba(100, 100, 100, 0.466); border-radius: 21px;}
