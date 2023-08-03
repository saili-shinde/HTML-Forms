# HTML-Forms
## HTML Code:
```
<html>
<head>
<title>Form HTML 1</title>
<link rel="stylesheet" href="form1.css">
</head>

<body  align="center">
<h1 align="center"><u>Student Registration Form</u></h1>
<section>
<form action="action.html" method="post" target="_blank" >
<table>

<tr style="height:60px">
<th style="width:50%"><label>First Name: </label></th>
<td><input type="name" name="firstname" id="firstname" min="1" max="30"></td>
</tr>

<tr style="height:60px">
<th><label>Last Name: </label></th>
<td><input type="name" id="lastname" min="1" max="30"></td>
</tr>

<tr style="height:60px">
<th><label>Date Of Birth: </label></th>
<td><input type="date"  id="birthday"></td>
</tr>

<tr style="height:60px">
<th><label for="email">Email: </label></th>
<td><input type="email" id="email"></td>
</tr>

<tr style="height:60px">
<th><label for="mobileno">Mobile no. : </label></th>
<td><input type="tel" id="myphone" placeholder="xx-xxxx-xxxx" required maxlength="10"></td>
</tr>

<tr style="height:60px">
<th><label for="gender">Gender:</label></th>
<td>
<label for="male">male: </label>
<input type="radio" name="male" id="male">
<label for="female">female: </label>
<input type="radio" name="female" id="female">
</td>
</tr>

<tr style="height:60px">
<th><label for="address">Address:</label></th>
<td><textarea name="address" rows="4" cols="50"></textarea></td>
</tr>

<tr style="height:60px">
<th><label>City: </label></th>
<td><input type="city" id="city" min="1" max="30"></td>
</tr>

<tr style="height:60px">
<th><label>Pin Code: </label></th>
<td><input type="number" id="pincode" min="1" max="6"></td>
</tr>

<tr style="height:60px">
<th><label>State: </label></th>
<td><input type="name" id="state" min="1" max="30"></td>
</tr>

<tr style="height:60px">
<th><label>Country: </label></th>
<td><input type="name" id="state" value="India" min="1" max="30"></td>
</tr>

<tr style="height:90px">
<th><label for="hobbies">Hobbies :</label></th>
<td>
<label for="drawing"> drawing: </label>
<input type="checkbox" name="drawing" id="drawing">
<label for="singing"> singing: </label>
<input type="checkbox" name="singing" id="singing">
<label for="dancing"> dancing: </label>
<input type="checkbox" name="dancing" id="dancing">
<label for="sketching"> sketching: </label>
<input type="checkbox" name="sketching" id="sketching"><br>
<label for="other"> other: </label>
<input type="checkbox" name="other" id="other">
<input type="name" id="otherHobby" min="1" max="30">
</td>
</tr>

<tr style="height:60px">
<th><label for="qualification">Qualification:</label></th>
<td>

<table >
<tr>
<th>sr.no</th>
<th>Examination</th>
<th>Board</th>
<th>percentage</th>
<th>year of passing</th>
</tr>

<tr>
<th>1</th>
<th>class X</th>
<td><input type="name" id="classX" min="1" max="10"></td>
<td><input type="text" id="classX" min="1" max="2"></td>
<td><input type="text" id="classX"></td>
</tr>

<tr>
<th>2</th>
<th>class XII</th>
<td><input type="name" id="classXII" min="1" max="10"></td>
<td><input type="text" id="classXII" min="1" max="2"></td>
<td><input type="text" id="classXII"></td>
</tr>

<tr>
<th>3</th>
<th>graduation</th>
<td><input type="name" id="graduation" min="1" max="10"></td>
<td><input type="text" id="graduation" min="1" max="2"></td>
<td><input type="text" id="graduation"></td>
</tr>

<tr>
<th>4</th>
<th>Master</th>
<td><input type="name" id="master" min="1" max="10"></td>
<td><input type="text" id="master" min="1" max="2"></td>
<td><input type="text" id="master"></td>
</tr>

<tr>
<th></th>
<th></th>
<th>(10 char max)</th>
<th>(upto 2 decimal)</th>
<th></th>
</tr>
</table>

</td>
</tr>

<tr style="height:60px">
<th>Courses Applied For</th>
<td>
<label for="bcaS">BCA: </label>
<input type="radio" name="bca" id="bca">
<label for="bcom">B.Com: </label>
<input type="radio" name="bcom" id="bcom">
<label for="bsc">B.Sc: </label>
<input type="radio" name="bsc" id="bsc">
<label for="ba">B.A.: </label>
<input type="radio" name="ba" id="ba">
</td>
</tr>

<tr>
<td></td>
<td align="center">
<input type="submit" name=" submit " value:"submit"="" style="background-color:green">

<input type="reset" name=" reset " value:"reset"="" style="background-color:green"><br><br>
</td>
</tr>

</table>

</section>
</form>
</body>
</html>
```

## CSS Code:
```
section {
margin-top: 70px;
margin-bottom: 50px;
margin-right: 300px;
margin-left: 300px;
background-color:purple
}
h1 {
margin-top: 50px;
color: purple
}
table {
color: #ffffff;
padding: 10px;
margin: auto;
border: solid black;
}
th, td {
border: hidden
}




```
