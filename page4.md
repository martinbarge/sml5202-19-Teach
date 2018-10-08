<p id="demo">Here</p>

<script>
var fs = require('fs'),
    readline = require('readline');

var rd = readline.createInterface({
    input: fs.createReadStream('test.txt'),
    output: process.stdout,
    console: false
});

rd.on('line', function(line) {
    document.getElementByID("demo").innerHTML = line;
});
</script>
