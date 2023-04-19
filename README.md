# js
Write a program to find the sum of all the elements in an array using a for loop and display the result in the DOM.

<html>
<head>
</head>
<body>

  <div id="result"></div>

  <script>
    // Define an array of numbers
    const numbers = [5, 10, 15, 20, 25];

    // Initialize a variable to store the sum of all elements
    let sum = 0;

    // Iterate through the array using a for loop and add each element to the sum
    for (let i = 0; i < numbers.length; i++) {
      sum += numbers[i];
    }

    // Display the result in the DOM
    const resultDiv = document.getElementById("result");
    resultDiv.textContent = `The sum of the array elements is ${sum}.`;
  </script>
</body>
</html>
