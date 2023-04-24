<DOCTYPE html>
  <html>
  <link rel="stylesheet" href="styles.css">
<style>

</style>

<head>

</head>
<body>

<h1 id="title">Survey form</h1>
<p id="description">Please fill out the form correctly</p>

<form id="survey-form">
<label for="name" id="name-label">Name:</label>
<input type="text" id="name" placeholder="Enter your name" required>
      

<label for="email" id="email-label">Email:</label>
<input type="email" id="email" placeholder="Enter your email" required> 
      
<label for="number" id="number-label">Number:</label>
<input type="number" id="number" placeholder="Enter a number" min="1" max="100" required>

<label for="dropdown">Select an option:</label>
<select id="dropdown">
<option value="option1">Option 1</option>
<option value="option2">Option 2</option>
</select>
      
<label>Choose an option:</label>
<input type="radio" name="option-group" value="option1" id="option1">
<label for="option1">Option 1</label>
<input type="radio" name="option-group" value="option2" id="option2">
<label for="option2">Option 2</label>
      
<label>Choose an option:</label>
<input type="checkbox" name="option1" value="option1">
<label for="option1">Option 1</label>
<input type="checkbox" name="option2" value="option2">
<label for="option2">Option 2</label>

<label for="comments">Additional comments:</label>
<textarea id="comments" placeholder="Enter your comments"></textarea>
      
<button type="submit" id="submit">Submit</button>

</body>
</html>
