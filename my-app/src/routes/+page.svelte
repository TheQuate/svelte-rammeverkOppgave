
<script>
	let counter = 0
	function increaseCounter(){
		counter +=1
	}
</script>



<center class="background">
    <div class="box">
        Settings
    </div>
    <button class="knappDrit" on:click={increaseCounter}> Du har klikket {counter} ganger</button>
    <center>
    
        <body>
        <h3 class="ovn">You found the easter egg</h3> 
    </body>
   
</center>
</center>


<style>
    .knappDrit{
        color: red;
        background-color: darkred;
        border: none;
        text-align: center;
        display: inline-block;
        font-size: 24px;
        padding: 15px 32px;
        margin-top: 10px;
        
    }

    .ovn{
        color: darkgrey;
        background-color: darkgray;
        padding: 50px;
        border: none;
        font-size: 23px;
        width: 1500px;
        margin: 0px;
        height: 600px;
    }

    .background{
        background-color: grey;
        border: none;
        height: 1000px;

    }
    .box{
        background-color: rgb(75, 73, 72);
        width: 1810px;
        height: 100px;
        border: 3px solid black;
        padding: 10px;
        
    }
</style>