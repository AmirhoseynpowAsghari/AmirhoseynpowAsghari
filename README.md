
<html>
<head>

  <style>
    #qubit {
      width: 100px;
      height: 100px;
      background-color: black;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      border-radius: 50%;
      transition: all 0.5s ease-in-out;
    }
  </style>
</head>
<body>
  <div id="qubit"></div>

  <script>
// Get the qubit element
const qubit = document.getElementById('qubit');

// Define the initial state of the qubit
let state = 0; // 0 for |0⟩, 1 for |1⟩

// Function to toggle the state of the qubit
function toggleQubit() {
  state = (state + 1) % 2; // Toggle the state between 0 and 1
  qubit.style.backgroundColor = state === 0 ? 'black' : 'red'; // Update the qubit color based on the state
}

// Add event listener to toggle the qubit on click
qubit.addEventListener('click', toggleQubit);
  </script>
  </body>
  </html>
  state = (state + 1) % 2; // Toggle the state between 0 and 1
  qubit.style.backgroundColor = state === 0 ? 'black' : 'red'; // Update the qubit color based on the state
}

// Add event listener to toggle the qubit on click
qubit.addEventListener('click', toggleQubit);
  </script>
</body>
</html>
