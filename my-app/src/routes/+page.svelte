
<script>
	let counter = 0
	function increaseCounter(){
		counter +=1
	}
</script>




<center class="background">
    <body>
        <h3 class="ovn">You found the easter egg</h3>
        <button class="knappDrit" on:click={increaseCounter}> Du har klikket {counter} ganger</button>
    </body>
   
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
        margin: 200px;
        
        
    }

    .ovn{
        color: black;
        background-color: darkgray;
        padding: 50px;
        border: none;
        font-size: 23px;
        width: 1200px;
        margin: 200px;
    }

    .background{
        background-color: grey;
        border: none;
        

    }

    
</style>