# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
#Index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HTML5 Elements Practice</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    table, th, td {
      border: 1px solid #000;
      border-collapse: collapse;
      padding: 8px;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h1>Welcome to HTML5 Practice Page By Regomoditswe Dibobo</h1>

  <!-- Ordered list with Roman numerals -->
  <section>
    <h2>Topics Covered</h2>
    <ol type="I">
      <li>Images</li>
      <li>Lists</li>
      <li>Tables</li>
      <li>Forms</li>
      <li>Multimedia</li>
    </ol>
  </section>

  <!-- External image from Pexels -->
  <section>
    <h2>Sample Image</h2>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Pexels Example" width="400" />
  </section>

  <!-- Table of 5 contacts -->
  <section>
    <h2>Contact List</h2>
    <table>
      <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>Email</th>
      </tr>
      <tr>
        <td>Sarah Nkosi</td>
        <td>123 Main Street</td>
        <td>0831234567</td>
        <td>sarah@gmail.com</td>
      </tr>
      <tr>
        <td>Thabo Mokoena</td>
        <td>45 Freedom Park</td>
        <td>0829876543</td>
        <td>thabo@gmail.com</td>
      </tr>
      <tr>
        <td>Lerato Khumalo</td>
        <td>789 Rose Avenue</td>
        <td>0845671234</td>
        <td>lerato@gmail.com</td>
      </tr>
      <tr>
        <td>John Dlamini</td>
        <td>10 Soweto Street</td>
        <td>0812345678</td>
        <td>john@yahoo.com</td>
      </tr>
      <tr>
        <td>Nomsa Sibanda</td>
        <td>256 Madiba Lane</td>
        <td>0734567890</td>
        <td>nomsa@outlook.com</td>
      </tr>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form>
      <!-- Name -->
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required />

      <!-- Email -->
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" placeholder="example@mail.com" required />

      <!-- Password -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter password" required minlength="6" />

      <!-- Date of Birth -->
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required />

      <!-- Dropdown -->
      <label for="country">Select Country:</label>
      <select id="country" name="country" required>
        <option value="">-- Choose a country --</option>
        <option value="za">South Africa</option>
        <option value="zw">Zimbabwe</option>
        <option value="ng">Nigeria</option>
        <option value="ke">Kenya</option>
      </select>

      <!-- Radio Buttons -->
      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required />
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" required />
      <label for="female">Female</label>

      <!-- Checkboxes -->
      <label>Hobbies:</label>
      <input type="checkbox" id="reading" name="hobby" value="Reading" />
      <label for="reading">Reading</label>
      <input type="checkbox" id="music" name="hobby" value="Music" />
      <label for="music">Music</label>
      <input type="checkbox" id="sports" name="hobby" value="Sports" />
      <label for="sports">Sports</label>

      <br /><br />
      <input type="submit" value="Register" />
    </form>
  </section>

  <!-- Multimedia -->
  <section>
    <h2>Multimedia</h2>
    <p>Sample audio and video elements:</p>

    <audio controls>
      <source src="https://www.w3schools.com/html/horse.ogg" type="audio/ogg" />
      Your browser does not support the audio element.
    </audio>

    <br /><br />

    <video width="320" height="240" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </section>

</body>
</html>
