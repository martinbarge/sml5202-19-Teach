<p id="demo">Here</p>

<style>
    .image {
    display: none;
}
    </style>
<script>
var quotes = [
    "Saab",
    "Volvo",
    "BMW",
    "Horse"
]; 
    
var q = quotes.length;
var whichquote=Math.round(Math.random()*(q-1));

function showquote(){
    document.getElementById('quote').innerHTML = quotes[whichquote];
    document.getElementsByTagName('img')[whichquote].style.display="block";
}

</script>


<div id="quote"></div>
<div>
    <img class="image" src="http://www.placehold.it/100x50&text=1" />
     <img class="image" src="http://www.placehold.it/100x50&text=2" />
     <img class="image" src="http://www.placehold.it/100x50&text=3" />
       <img class="image" src="http://www.placehold.it/100x50&text=4" />
</div>
showquote();
