# wheather-page
<!DOCTYPE html>
<html lang="en">

<head>
  <link href="style.css" rel="stylesheet">
  <script src="wheather.js">

  </script>
</head>

<body>
  <div class="container-fluid">
    <section class="main">
      <section class="inputs">
        <input type="text" placeholder="Enter any city..." id="cityinput">
        <input type="submit" value="Submit" id="add">
        <button placeholder="submit" id="add"></button>
      </section>

      <section class="display">
        <div class="wrapper">
          <h2 id="cityoutput"></h2>
          <p id="description"></p>
          <p id="temp"></p>
          <p id="wind"></p>
        </div>
      </section>
    </section>

  </div>
</body>

</html>


#wheather page css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body
{
    background: #85d70a;
}
.container-fluid
{
    width: 400px;
    margin: 60px auto;
    padding: 10px;
}
.inputs 
{
    padding: 2rem 0 2rem 0;
    text-align: center;
    justify-content: center;
    background: rgb(255, 255, 255);
}
.inputs input[type="text"] 
{
    height: 4rem;
    width: 20rem;
    background: #212121;
    font-weight: bold;
    font-size: 1rem;
    padding: 10px;
    border: none;
    background-color: transparent;
    border: 2px solid #e50505;
    border-radius: 2px;
    margin-right:4px ;
}
.inputs input[type="submit"] 
{
    height: 3rem;
    width: 6rem;
    background: #0a67ca;
    font-weight: bold;
    color: white;
    font-size: 1rem;
    margin-top: 20px;
    border: none;
    border-radius: 2px;
}
.display 
{
    text-align: center;
    width: 400px;
    color: #16a864;
}
.wrapper 
{
    margin: 0 9rem;
    background-color: white;
    height: 45vh;
    margin: 50px auto;
    border-radius: 2px;
}

.wrapper h2
{
    padding: 5px 0;
    text-align: center;
    background: #0548b5;
    color: white;
    font-family: sans-serif;
}
.wrapper p
{
    margin:20px 50px;
    margin-right: 20px;
    text-align: left;
    color: #04214c;
    font-size:23px;
}
.wrapper h2 span
{
    font-size: 26px;
    color: #9beefb;
}
.wrapper p span
{
    color: #f4780d;
    font-size: 25px;
}
