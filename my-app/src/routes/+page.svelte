
<script>
	let counter = 0
	function increaseCounter(){
		counter +=1
	}

    function decreaseCounter(){
        counter -=1
    }

    if (counter >=20 ) {
        const imageContainer = document.getElementById("imageContainer");

        const image = document.createElement("img");

        image.src = "https://images.rawpixel.com/dark_image_png_800/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvcGYtczExNC1wLTA3LnBuZw.png"

        imageContainer.appendChild(image);
    }
</script>



<div class="background">
    <div class="box">
        OVEN
    </div>
    <center class="parent">
        <button class="knappDrit" on:click={increaseCounter}> +</button>
        <button class="knappDrit" on:click={decreaseCounter}> -</button>
        <div class="degreeCounter"> {counter}° </div>

    </center>
    
    <center>
    
        <body>
        <h3 class="ovn">You found the easter egg</h3> 
        <div id="imageContainer" class="customImage"></div>
    </body>
    </center>
</div>



<style>
    .knappDrit{
        font-size: 50px;
        color: yellow;
        background-color:darkslategray;
        border: 1px solid black;
        text-align: right;
        display: inline-block;
        font-size: 24px;
        padding: 15px 32px;
        margin-top: 10px;
        margin-left: 60px;
        margin-bottom: 10px;
        display: inline-block;
        border-radius: 25px;
        
    }

    .ovn{
        color: firebrick;
        background-color:firebrick;
        padding: 50px;
        border: none;
        font-size: 23px;
        width: auto;
        margin: 20px;
        height: 600px;
        border: 70px solid rgb(72, 80, 80);
        margin-bottom: 20px;
    }

    .background{
        background-color: grey;
        border: none;
        height: auto;

    }
    .box{
        background-color: rgb(75, 73, 72);
        width: auto;
        height: 25px;
        border: 3px solid black;
        padding: 10px;
        text-align: center;
        
        
    }
    .degreeCounter{
        text-align: center;
        padding: 10px;
        border: 1px solid black;
        display: inline-block;
        margin-left: 250px;
        color: yellow;
        background-color:darkslategray;
        font-size: 30px;
        border-radius: 25px;
        width: 70px;
        

    }
    .parent{
        border: 1px solid black;
        background-color: rgb(75, 73, 72);
        
    }
</style>