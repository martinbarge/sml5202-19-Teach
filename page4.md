<div id="demo">&nbsp;</div>
<script>

handleFiles(input) {
   var files = "test.txt";

    const file = input.target.files[0];
    const reader = new FileReader();

    reader.onload = (event) => {
        const file = event.target.result;
        const allLines = file.split(/\r\n|\n/);
        // Reading line by line
        allLines.forEach((line) => {
            console.log(line);
            document.getElementById("demo").innerHTML = line; 
        });
    };

    reader.onerror = (event) => {
        alert(event.target.error.name);
    };

    reader.readAsText(file);
}

</script>
