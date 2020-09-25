<!DOCTYPE html>
<html>
 <head>
 <title>HTML Cheat Sheet</title>
 </head>
 <body>
 
 <a href="blog.html">Go to blog</a>
 <hr>
 <!--Headings-->
 <h1>Heading One</h1>
 <h2>Heading Two</h2>
 <h3>Heading Three</h3>
 <h4>Heading Four</h4>
 <h5>Heading Five</h5>
 <h6>Heading Six</h6>
 
 <!--Paragraph-->
 <p>
 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor<strong> incididunt ut labore</strong> et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud<em>exercitation ullamco</em> laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
 </p>
 <p>
 Lorem ipsum dolor sit amet, consectetur adipiscing elit,<a href="http://google.com" target="_blank">sed do eiusmod</a> tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
 </p>
 <!--Lists-->
 <ul>
 
 <li>List item 1</li>
 <li>List item 2</li>
 <li>List item 3</li>
 <li>List item 4</li>
 </ul>
 
 <ol>
 
 <li>List item 1</li>
 <li>List item 2</li>
 <li>List item 3</li>
 <li>List item 4</li>
 </ol>
 
 <!--Table-->
 
 <table>
 <thead>
 <tr>
 <th>Name</th>
 <th>Email</th>
 <th>Age</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <td>Brad Traversy</td>
 <td>brad@something.com</td>
 <td>35</td>
 </tr>
 </tbody>
 
 <tbody>
 <tr>
 <td>John Doe</td>
 <td>jdoe@something.com</td>
 <td>45</td>
 </tr>
 </tbody>
 
 <tbody>
 <tr>
 <td>Sara Williams</td>
 <td>sara@something.com</td>
 <td>25</td>
 </tr>
 </tbody>
 </table>
 
 <br>
 <hr>
 <br>
 
 <!--forms-->
 <form action="prosess.php" method="POST">
 <div>
 <label>First Name</label>
 <input type="text" name="firstName" placeholder="Enter First Name">
 </div>
 <br>
 <div>
 <label>Last Name</label>
 <input type="text" name="lastName">
 </div>
 <br>
 <div>
 <label>Email</label>
 <input type="email" name="email">
 </div>
 <br>
 <div>
 <label>Message</label>
 <textarea name="message"></textarea>
 </div>
 <br>
 <div>
 <label>Gender</label>
 <select name="gender">
 <option value="male">Male</option>
 <option value="female">Female</option>
 <option value="other">Other</option>
 </select>
 </div>
 <br>
 <div>
 <label>Age:</label>
 <input type="number" name="age" value="30">
 </div>
 <br>
 <div>
 <label>Birthday:</label>
 <input type="date" name="birthday">
 </div>
 <br>
 <input type="submit" name="submit" value="Submit">
 </form>
 
 <!--Button-->
 <button>Click Me</button>
 <br>
 <!--Image-->
 <a href="images/CSIP.jpg">
 <img src="images/CSIP.jpg" alt="My Sample Image" width="200">
 </a>
 
 <!--Quotations-->
 <blockquote cite="http://traversymidia.com">
 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
 </blockquote>
 
 <p>The <abbr title="World Wide Web">WWW</abbr> is awesome</p>
 
 
 <p><cite>HTML crash course</cite> by Brad Traversy </p>
 <div style="margin-top:500px"></div>
 </body>
</html>
