<!-- +page.svelte -->

<script>
    import Header from './Header.svelte';
    import Body from './Body.svelte';
    import Footer from './Footer.svelte';
    
    export let nombre = "";

    

    function handle (e){
      const target = e.target;
      nombre = e.target.value;
    }
</script>

<style>
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }

 
  
  body {
        background-image: url('link2innovate.png');
        background-repeat: no-repeat;
        background-size: cover;
        height :100vh;
        width:100%;
        object-fit:cover;
  }

.boton1 {
position: absolute;
width: 30px;
height: 10px;
left: 165px ;
top: 160px;

opacity: 0;

}

.boton2{
position: absolute;
width: 30px;
height: 10px;
left: 650px ;
top: 160px;

opacity: 0;

}

.boton3{
position: absolute;
width: 30px;
height: 10px;
left: 1045px ;
top: 160px;

opacity: 0;

}

.boton4{
position: absolute;
width: 30px;
height: 10px;
left: 307px ;
top: 40px;

opacity: 0;

}

.boton5{
position: absolute;
width: 30px;
height: 10px;
left: 965px ;
top: 43px;

opacity: 0;

}

.boton6{
position: absolute;
width: 30px;
height: 10px;
left: 186px ;
top: 543px;

opacity: 0;

}

.boton7{
position: absolute;
width: 30px;
height: 10px;
left: 630px ;
top: 540px;

opacity: 0;

}

.boton8{
position: absolute;
width: 30px;
height: 10px;
left: 1060px ;
top: 543px;

opacity: 0;

}
</style>


<body>
 
    <div class="boton1"><li><a href="/santiago">publishprojectttttttttttttttttt</a></li></div>
  
    <div class="boton2"><li><a href="/targets">tagsssss</a></li></div>

    <div class="boton3"><li><a href="/santiago">meetpeopleeeeeeee</a></li></div>

    <div class="boton4"><li><a href="/santiago">exploreeeeeeee</a></li></div>

    <div class="boton5"><li><a href="/santiago">learnnnnnn</a></li></div>

    <div class="boton6"><li><a href="/project1">learnmoreeeeeeee</a></li></div>

    <div class="boton7"><li><a href="/santiago">learnmoreeeeeeee</a></li></div>

    <div class="boton8"><li><a href="/santiago">learnmoreeeeeeee</a></li></div>
  

  
</body>