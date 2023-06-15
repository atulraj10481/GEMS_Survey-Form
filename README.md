<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Survey Form</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out this survey form</p>
  </header>

  <main>
    <form id="survey-form">
      <div class="form-group">
        <label for="name" id="name-label">Name:</label>
        <input type="text" id="name" placeholder="Enter your name" required>
      </div>

      <div class="form-group">
        <label for="email" id="email-label">Email:</label>
        <input type="email" id="email" placeholder="Enter your email" required>
      </div>

      <div class="form-group">
        <label for="number" id="number-label">Number:</label>
        <input type="number" id="number" placeholder="Enter a number" min="1" max="100" required>
      </div>

      <div class="form-group">
        <label for="dropdown">Services:</label>
        <select id="dropdown" required>
          <option value="" disabled selected>Select an option</option>
          <option value="option1">Frontend Developer</option>
          <option value="option2">Backend Developer</option>
        </select>
      </div>

      <div class="form-group">
        <label for="how can we help">How can we help:</label>
        <textarea id="how can we help" placeholder="Enter your comments"></textarea>
      </div>

      <button type="submit" id="submit">Send message</button>
    </form>
  </main>
</body>
</html>
# GEMS_Survey-Form
