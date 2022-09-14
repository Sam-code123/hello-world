

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Registration Form With Validation</title>
    <link rel="stylesheet" href="register.css" />
    <script src="form.js" defer></script>
  </head>
  <body>
    <div class="box">
      <form class="form" id="form">
        <h2 align="center">Registration Form</h2>

        <table class="tableForm" cellspacing="25px">
          <tr>
            <td><label for="name">Name :</label></td>
            <td>
              <input
                class="input"
                type="text"
                name="name"
                id="name"
                placeholder="Full Name"
                required
              />
            </td>
          </tr>
          <tr>
            <td><label for="email">E-mail :</label></td>
            <td>
              <input
                class="input"
                type="email"
                name="email"
                id="email"
                placeholder="Email"
                required
              />
            </td>
          </tr>
          <tr>
            <td><label for="name">Password :</label></td>
            <td>
              <input
                class="input"
                type="password"
                name="password"
                id="password"
                placeholder="Password"
                required
              />
            </td>
          </tr>
          <tr>
            <td><label for="dob">Date Of Birth :</label></td>
            <td>
              <input
                style="width: 220px"
                class="input"
                type="date"
                name="dob"
                id="dob"
                required
              />
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <input type="checkbox" name="agree" id="agree" />
              <label for="checkbox">Accept Terms & Conditions</label>
            </td>
          </tr>
          <tr>
            <td>
              <button class="button" type="submit">Submit</button>
            </td>
          </tr>
        </table>
      </form>
    </div>

    <div class="entry">
      <h2 class="subHead">Entries</h2>
      <div id="tableDiv"></div>
    </div>
  </body>
</html>

