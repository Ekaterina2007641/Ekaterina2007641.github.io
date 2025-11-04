<idoctype htmIl>
<html>
    <head>
        <script>
            function greet()
            {
                alert("Привет " + document.querySelector("#name").value);
            }
        </script>
    </head>
    <body>
        <form onsubmit="greet(); return false;">


