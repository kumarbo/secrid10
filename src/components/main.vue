<template>
<main>
    
         
        <span>
            Industrial design and<br>
            fashion come together<br>
            in pocket-sized<br>
            essentials.
        </span>
        <span>
            <router-link to="/collection">View collections</router-link></span>
    
     
    
</main>
  

    
</template>

<script>
export default {
  
  data () {
    return {
      
    }
  }
}
</script>

<style scoped lang="scss">
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}
main{
   
    
         background:url('../assets/ivan.jpg');
         background-size:cover;
    padding:200px 0px;
    span{
        font-size:34px;
        display:block;
        margin-left:100px;
       color:white;
       font-weight:bold;
        &:nth-of-type(2){
            border:1px solid white;
            padding:10px 15px;
            margin-top:20px;
            font-size:18px;
            color:white;
            widtH:20%;
            text-align:center;
            &:hover{
                background:black;
                transition:1s ease;
            }

        }
        a{
            text-decoration:none;
            color:white;
        }
    }
    }

    @media screen and (max-width:400px){
        main{
             background:url('../assets/giri.jpg');
            span{
                margin-left:10px;
                font-size:20px;
                &:nth-of-type(2){
                    width:65% !important;
                }
            }
        }
    }
     @media screen and (max-width:500px){
        main{
             
            span{
                margin-left:10px;
                font-size:20px;
                &:nth-of-type(2){
                    width:40%;
                }
            }
        }
    }

</style>