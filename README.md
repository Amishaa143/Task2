<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task 2</title>
    <link rel="stylesheet" href="task2.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
 <nav class="navbar bg-dark fixed-top navbar-expand-lg" data-bs-theme="dark">
    <div class="logo">MyWebApp</div>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarnavAtMarkup" ><span class="navbar-toggler-icon"></span>
 </button>
 <div class="collapse navbar-collapse" id="navbarnavAtMarkup">
 <div class="navbar-nav">
    <ul>
      <li>Home</li>
      <li>Form</li>
      <li>To-Do</li>
    </ul>
    </div></div>
  </nav>
<br><br>
  <div class="main-content">

    <div class="section">
      <h2 style="color: purple;">Contact Form</h2>
      <form id="contactForm" novalidate>
        <div class="form-group">
          <label for="name"><b>Name:</b></label>
          <input type="text" id="name" />
          <div class="error" id="nameError"></div>
        </div>

        <div class="form-group">
          <label for="email"><b>Email:</b></label>
          <input type="email" id="email" />
          <div class="error" id="emailError"></div>
        </div>

        <input type="submit" value="Submit" />
      </form>
    </div>

    <div class="section">
      <h2 style="color: purple;">To-Do List</h2>
      <input type="text" id="taskInput" placeholder="Enter task" />
      <button id="addTaskBtn">Add</button>
      <ul id="taskList"></ul>
    </div>
  </div>
    <script src="script2.js">
    </script>
</body>
</html>
