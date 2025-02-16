/* styles.css */
body {
    background-color: #f0f0f0; /* Light gray background */
    font-family: sans-serif; /* Default font if Arial isn't available */
    margin: 0; /* Remove default body margins */
}

header {
    text-align: center;
    padding: 20px 0; /* Add some padding to the header */
}

h1 {
  font-size: 2em; /* Make the heading larger */
}

main {
    display: flex;
    flex-direction: column; /* Stack elements vertically */
    align-items: center; /* Center horizontally */
    padding: 20px;
}

img {
    width: 450px;
    height: 300px;
    margin-bottom: 20px; /* Add space below the image */
}

p {
    font-family: Arial, sans-serif;
    font-size: 18px;
    text-align: center; /* Center the paragraph text */
    margin-bottom: 20px; /* Space below paragraph */
}

footer {
    background-color: #333; /* Darker background for footer */
    color: white;
    text-align: center;
    padding: 24px 0; /* Top and bottom padding */
    position: fixed; /* Stick the footer to the bottom */
    bottom: 0;
    width: 100%;
}

a {
    color: blue; /* Default link color */
    text-decoration: none; /* Remove underline from link */
}

a:hover {
    text-decoration: underline; /* Add underline on hover */
}
