<!-- @format -->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Github Profile Page Design</title>
    <link rel="stylesheet" href="style.css" />
    <script
      src="https://kit.fontawesome.com/fef272fe1f.js"
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <nav>
      <i class="fab fa-github fa-2x"></i>
      <h2>GITHUB</h2>
    </nav>
    <main>
      <aside></aside>
      <article>
        <section>
          <input type="text" placeholder="Search" />
        </section>
        <section class="card-section">
          <div class="card"></div>
          <div class="card"></div>
          <div class="card"></div>
        </section>
        <section id="summary-section"></section>
      </article>
    </main>
  </body>
</html>
/** @format */
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

/* nav bar */
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 1rem;
  background-color: #2f3d46;
  color: white;
  padding: 2rem;
}
nav h2 {
  font-family: open sans;
  margin: 0 auto;
  letter-spacing: 3px;
  font-weight: 600;
}

/* main */

main {
  background-color: #cad2c5;
  display: flex;
  height: 91vh;
  overflow: hidden;
  padding: 10vh 5vw;
}

/* aside */

aside {
  width: 32%;
  height: 70vh;
  background-color: #353535;
  border-radius: 2rem;
}

/* article */

article {
  margin-left: 15vh;
  width: 100%;
  height: 70vh;
  /* background-color: #353535; */
  border-radius: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}

/* search bar */

article input[type="text"] {
  width: 40vw;
  height: 7vh;
  color: #cad2c5;
  background-color: #353535;
  border-radius: 0.5rem;
}

article input[type="text"]::placeholder {
  color: #cad2c5;
  font-size: 1.2rem;
  padding: 1rem;
  letter-spacing: 0.3rem;
  opacity: 0.6;
}

article section[class="card-section"] {
  height: 30%;
  width: 100%;
  display: flex;
  justify-content: space-between;
}

.card {
  width: 15vw;
  height: 100%;
  background-color: #353535;

  border-radius: 1rem;
}

article section[id="summary-section"] {
  height: 30%;
  width: 100%;
  border-radius: 1rem;
  background-color: #353535;
}
