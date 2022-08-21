# project1
<html>
<head>
  <title>
    Form
  </title>
</head>
<body>
<style>
  body{
  background-image:
  url('mahima/dost.jpg');
  background-repeat: no-repeat;
  background-size:cover;
}
</style>
<form action="">
<h2>Information<h2>
<p>Name: <input type ="text" name="name" required></p>
<fieldset>
<legend>Gender</legend>
  <p>
    Male <input type="radio" name="gender" id="male">
    Female <input type="radio" name="gender" id="female">
  </p>
</fieldset>
<p>Address: <textarea name="address" id="address" cols="100"rows="8"></textarea></p>
<h2>REMARK</h2>
<p style="font-size:25px">Review :
  <select name="review" id="review">
    <option value="">--Select a option --</option>
    <option value="Bad">Bad</option>
    <option value="Good">Good</option>
  </select>
</p>
<p style="font-size:25px">
  Birthday Date: <input type="date" name="birthday_date">
</p>
<input type="submit" value="SUBMIT">
</form>
</body>
</html>
