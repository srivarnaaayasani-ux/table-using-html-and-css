# table-using-html-and-css
created a table with html and styled using css
<!DOCTYPE html>
<html lang="en">
<head>
<style>

td,th{
border-color:black;
border-collapse:collapse;
border-radius:10px;
border:5px solid black;
font-style:italic;
text-align:center;
}


body{
display:flex;
justify-content:center;
align-items:center;
height:100vh;
background-image: url("download.jpg");
background-position:center;
background-repeat:no-repeat;
background-size:cover;

}

table{
padding:5px;
background:linear-gradient(grey,white);
height:60vh;
width:80vh;
border-radius:10px;
}

h2{
text-align:center;
height:5vh;
color:white;
}

</style>
</head>
<body>
<div>
<h2><i>Learning Schedule<i></h2> 
<table>
<tr>
<th>Work Schedule</th>
<th>Date</th>
<th>Done</th>
<th>Remark</th>
</tr>
<tr>
<td>1st Jan</td>
<td>-HTML Basics</td>
<td><input type="checkbox"></td>
<td>Successfully Completed</td>
</tr>
<tr>
<td>2nd Jan</td>
<td>-CSS Basics</th>
<td><input type="checkbox"></td>
<td>Successfully completed</td>
</tr>
<tr>
<td>3rd Jan</td>
<td>-JavaScript Basics</th>
<td><input type="checkbox"></td>
<td>In Progress</td>
</tr>
<tr>
<td>4th Jan</td>
<td>-Project using HTML</th>
<td><input type="checkbox"></td>
<td>Not Done Yet</td>
</tr>
<tr>
<td>5th Jan</td>
<td>-Project using CSS</th>
<td><input type="checkbox"></td>
<td>Not Done Yet</td>
</tr>
<tr>
<td>6th Jan</td>
<td>-Project using JavaScript</th>
<td><input type="checkbox"></td>
<td>Not Done Yet</td>
</tr>
</div>
</table>
</body>
</html>
