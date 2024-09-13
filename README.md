<!DOCTYPE>
<html>
    <head>
        <title>MUHAMMAD FAUDZI</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </header>
    <body>
        <header>
            <div class="container">
                <h1><a href="index.html">M.FAUDZI</a></h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="Alamat.html">Alamat</a></li>
                    <li><a href="Skil.html">Skil</a></li>
                    <li><a href="Pengalaman.html">Pengalaman</a></li>
                </ul>
            </div>
        </header>
    <!-- banner -->
    <section class="banner">
        <h2>Halo nemtas people</h2>
    </section>
      <!-- about -->
      <section class="about">
        <div class="container">
            
                </tr>
              </table>   
        </div>
    </section>
    <section class="service">
        <div class="container">
          
                </div>
            </div>
        </div>
    </section>
     <!-- footer -->
     <footer>
        <div class="container">
            <small>Copyright &copy; All Rights Reserved.</small>
        </div>
    </footer>

    </body>
</html>

* {
    padding: 0;
    margin: 0;
    font-family: sans-serif;
}

a {
    color: inherit;
    text-decoration: none;
}

.container {
    width: 80%;
    margin: 0 auto;
}

.container:after {
    content: '';
    display: block;
    clear: both;
}

header h1 {
    float: left;
    padding: 15px 0;
    color: blue;
}

header ul {
    float: right;
}

header ul li {
    display: inline-block;
}

header ul li a {
    padding: 25px 20px;
    display: inline-block;
}

header ul li a:hover {
    background-color: navy;
    color: #fff;
}

.active {
    background-color: navy;
    color: #fff;
}
.banner {
    height: 70vh;
    background-image: url('../img/IMG-20240516-WA0035.jpg');
    background-size: cover;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}

.banner:after {
    content: '';
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(68, 76, 143, 0.6);
}

.banner h2 {
    color: #fff;
    z-index: 1;
    padding: 20px 25px;
    border: 3px solid #fff;
}

section {
    padding: 50px 0;
}
 about table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 100%;
  }
  
  td, th {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 8px;
  }
  
  tr:nth-child(even) {
    background-color: #dddddd;
  }
  .about,
.service {
    padding-bottom: 100px;
}
table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
  }

.service {
    background-color: #f9f9f9;
}

.box {
    color: #91ae0e;
}

.box:after {
    content: '';
    display: block;
    clear: both;
}

.box .col-4 {
    width: 25%;
    padding: 20px;
    box-sizing: border-box;
    text-align: center;
    float: left;
}

.icon {
    width: 70px;
    height: 70px;
    border: 1px solid;
    border-radius: 50%;
    text-align: center;
    line-height: 70px;
    font-size: 20px;
    margin: 0 auto;
}

.box .col-4 h4 {
    margin: 20px 0;
}

footer {
    padding: 30px 0;
    background-color: #333;
    color: #fff;
    text-align: center;
}
