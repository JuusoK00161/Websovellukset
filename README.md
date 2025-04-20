WS02 CSS 
<!DOCTYPE html>
>
<head>
<title>Laurea</title>
</head>
<body>
<h1>Minun verkkosivusto</h1>
<p>Tässä on ensimmäinen nettisivu 
</html
></body>
<html>
<h2>Juuson harrastukset</h2>
</h2>
<ol>Harrastukseni:
<li>Kuntosali</li> 
<li>Potkunyrkkeily</li>
<li>Lukeminen</li>
<a href="https://www.laurea.fi">Visit Laurea</a>
<h1 style="color: red;">Juuson verkkosivu</h1>
<style>
    h1 {
      color: green;
    }
    </style>
<link rel="stylesheet" href="styles.css">
p {
    color: rgb(7, 7, 27);
}

body {
    background-color: rgb(139, 36, 36);
}

h1 {
    font-size: 2em;
}
div {
    padding: 20px;
    margin: 10px;
  }
  table {
    width: 100%;
    border-collapse: collapse;
  }
  
  th, td {
    border: 1px solid #c5b8b8;
    padding: 8px;
    text-align: left;
  }
  
  th {
    background-color: #531616;
  }
  
  form {
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  
  label {
    font-weight: bold;
  }
  
  input[type="text"], input[type="email"] {
    padding: 8px;
    border: 1px solid #b4abab;
    border-radius: 4px;
  }
  
  input[type="submit"] {
    background-color: #4CAF50;
    color: rgb(85, 38, 38);
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  input[type="submit"]:hover {
    background-color: #45a049;
  }
