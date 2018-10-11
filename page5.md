<dl id="quote"></dl>

<script>
var quotes=[
'A bird in the bush is worth two in the hand.used to say that it is better to hold onto something one has than to risk losing it by trying to get something better', 

'Make hay while the sun shines.', 

'Don\'t count your chickens before they hatch.'
];

var meanings=[
'It is better to hold onto something one has than to risk losing it by trying to get something better.', 

'Take advantage of the chance to do something while conditions are good.', 

'Do not make plans that depend on something good happening before you know that it has actually happened.'
];

function loadQuote() {
    var quoteNo = Math.floor(Math.random() * (quotes.length));
    //alert(quotes[quoteNo]);
    document.getElementById("quote").innerHTML = "<dt>" + quotes[quoteNo] + "</dt>" + "<dd>" + meanings[quoteNo] + "</dd>"
}
loadQuote();
</script>
