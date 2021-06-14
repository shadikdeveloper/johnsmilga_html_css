# johnsmilga_html_css

Learning about html &amp;Css
Html: Hyper text markup language.
Html is responsible for web page structure.
<element>content goes here </element>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My favourite Website</title>
    <style>
      .bg {
        color: red;
        background-color: blue;
        padding: 10px;
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <h1>this is heading one</h1>
    <p>this is paragraph</p>
    <img src="" alt="" />
    <br />

    <!-- external links -->
    <a href="https://www.google.com">Google</a>

    <sup>super element</sup>
    <sub>sub element</sub>
    <strong>strong element</strong>
    <em>emphasis text</em>
    # nested list
    <ol>
      <li>one</li>
      <li>two</li>
      <li>three</li>
    </ol>

    <ul>
      <li>One</li>
      <li>One</li>
      <li>One</li>
    </ul>

    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Place</th>
          <th>Money</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Shadik</td>
          <td>Tiruapti</td>
          <td>500000</td>
        </tr>
      </tbody>
    </table>

    <form>
      <label for="Name">Name</label>
      <input type="text" name="Name" id="Name" placeholder="Name" />
      <br />
      <br />
      <label for="Email">Email </label>
      <input type="email" name="Email" id="Email" placeholder="Email" />
      <br />
      <br />
      <label for="Password">Password</label>
      <input
        type="password"
        name="Password"
        id="Password"
        placeholder="Password"
      />
      <br />
      <br />
      <label for="Gender">Gender</label>
      <input type="radio" name="Gender" id="Gender" value="Male" />Male
      <input type="radio" name="Gender" id="Gender" value="Female" />Female
      <br />
      <br />
      <label for="Description">Description</label>
      <br />
      <textarea
        name="Description"
        id="Description"
        cols="30"
        rows="10"
      ></textarea>
      <br />
      <br />
      <label for="Programming">Select Programming languages</label>
      <input
        type="checkbox"
        name="Programming"
        id="Programming"
        value="Java"
      />Java
      <input
        type="checkbox"
        name="Programming"
        id="Programming"
        value="Python"
      />Python
      <input
        type="checkbox"
        name="Programming"
        id="Programming"
        value="JavaScript"
      />JavaScript
      <br />
      <br />
      <label for="DropDown">DropDown</label>
      <select name="DropDown" id="DropDown">
        <option value="Bicycle">Bicyle</option>
        <option value="Scooter">Scooter</option>
        <option value="Car">Car</option>
      </select>
      <br />
      <br />
      <input type="submit" value="Submit" />
    </form>

  </body>
</html>

Css: cascading style sheet

html is responsible for web page structure.
css is reponsible for stying the web.

selector {property:value;}
