# supreme-pancake
# JAVA SCRIPT HTML DOM

<!DOCTYPE html>
<html>
    <head>
        <body>
            <h2>JavaScript HTML DOM</h2>
            <p>Finding HTML Elements by Tag Name.</p>
            <p>This Example demonstrates the
                <b>getElementsByTagName</b> method.</p>
                <p id = "demo"></p>

                <script>
                const element = document.getElementsByTagName("p");

                document.getElementById("demo").innerHTML = "The text in first paragraph(index 0)is: "+ element[0].innerHTML;
                </script>
        </body>
    </head>
</html>
