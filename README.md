<!DOCTYPE html>
<html>
<head>
    <title>Be My Valentine</title>
    <style>
        body {
            text-align: center;
            padding: 10%;
            font-size: 2em;
        }
        #response {
            margin-top: 2em;
            color: red;
        }
    </style>
</head>
<body>
    <h1>Will you be my Valentine?</h1>
    <button onclick="response('Yes')">Yes</button>
    <button onclick="response('No')">No</button>
    <p id="response"></p>
    <script>
        function response(answer) {
            if (answer === 'No') {
                alert("Oops! The 'No' button seems to be not working. Please try the 'Yes' button.");
            } else {
                document.getElementById('response').textContent = "Thank you! You've made my day!";
            }
        }
    </script>
</body>
</html>
