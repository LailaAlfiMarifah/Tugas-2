<template>

<html>
    <head>
        <title>Laila</title>
    </head>
    <body>
      <h1><b>Laila's Fine Foods </b></h1>
   <img src="https://bfff.co.uk/wp-content/uploads/2013/06/Lailas-resized.png" alt="Logo" style="width:100px;height:90px;" /> 
   <h2>Description</h2>
        <p>Laila's Fine Food provides a variety of noodle-based dishes. This food has a spicy level.</p>
        <h3>Login</h3>
    <form action="/action_page.php">
        <label for="usname">Username:</label>
        <input type="text" id="usname" name="usname"><br><br>
        <label for="password">Password:</label>
        <input type="text" id="Password" name="Password"><br><br>
        <input type="submit" value="Submit">
    </form>
    <h4>Nama Foods</h4>
    <table border = "3">
        <tr>
            <th>Nama Foods</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>Mie Nyemek</td>
            <td>10000</td>
        </tr>
        <tr>
            <td>Seblak</td>
            <td>15000</td>
        </tr>
    </table>
    <form action="/action_page.php">
        <p><label for="Laila's Fine Foods">Review of Laila's Fine Foods:</label></p>
        <textarea id="w3review" name="w3review" rows="4" cols="50">Kritik Dan Saran</textarea>
        <br>
    </form>
        <h5><i>Contacts</i></h5>
            <a href="account1 link" target="_blank">Instagram</a>
            <a href="account2 link" target="_blank">WhatssApp</a>
        <h2><i>Write me a message</i></h2>
        <form>
            <input placeholder="Name"/><br>
            <input placeholder="Email"/><br>
            <textarea placeholder="Message" required ></textarea><br>
            <input type="submit" value="SEND"/> 
        </form>
    </body>
</html>
</template>
<style scoped>
  table, th, td {
  border:2px solid black;}

</style>