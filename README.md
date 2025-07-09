# CSS-Assignment-1
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Assingnment 1</title>
  <link rel="stylesheet" href="ass1.css" />
</head>
<body>

  <header></header>

  <main>Main Content</main>

  <div class="container">
    <div class="blue-box"></div>
    <div class="right-section">
      <div class="yellow-box"></div>
      <div class="green-box"></div>
    </div>
  </div>

</body>
</html>


style.css

body {
  margin: 0;
  height: 300px;
 
  background-color: #f0ee86;
  font-family: Arial, sans-serif;
}

header {
  background-color: red;
  height: 100px;
  width: 100%;
}

main {
  background-color: #f0ee86;
  text-align: center;
  font-weight: bold;
  padding: 10px 0;
  font-size: 1.2rem;
}

.container {
  margin: 5px auto;
  background-color: rgb(26, 225, 239);
  width: 97%;
  height: 275px;
  display: flex;
  padding: 30px 10px;
  box-sizing: border-box;
}

.blue-box {
  background-color: blue;
  width: 40%;
  height: 100%;
}

.right-section {
  background-color: #4cb4ad;
  flex-grow: 1;
  margin-left: 10px;
  position: relative;
}

.yellow-box {
  background-color: yellow;
  width: 60px;
  height: 60px;
  position: absolute;
  top: 0;
  left: 0;
}

.green-box {
  background-color: #a1dd0a;
  width: 60px;
  height: 60px;
  position: absolute;
  bottom: 0;
  right: 0;
}
