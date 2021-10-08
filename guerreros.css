@import url("https://fonts.googleapis.com/css2?family=Public+Sans&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  height: 100%;
}

body {
  font-family: "Public Sans", sans-serif;
  font-size: 1.2rem;
  min-height: 100%;
}

.grid-container > * {
  box-shadow: -1px 1px 7px 0px rgba(0, 0, 0, 0.75);
  border-radius: 4px;
  padding: 10px;
  text-align: center;
}

.header {
  grid-area: header;
  background-color: #FFFF00;
}

.navbar {
  grid-area: navbar;
  background-color: #A41ED2;
}

.sidebar {
  grid-area: sidebar;
  background-color: #AF872C ;
}

.section {
    grid-area: section;
    background-color: #FFFF00;
}


.main {
  grid-area: main;
  background-color: #AF872C;
}



.footer {
  grid-area: footer;
  background-color: #8c96a0;
}

.grid-container {
  display: grid;
  gap: 10px;
  grid-template:
    "header"  100px
    "navbar"  50px
    "main" auto
    "main2" auto
    "sidebar" 100px
    "footer"  100px;
}



@media (min-width: 600px) {
  .grid-container {
    grid-template:
      "header  header" 100px
      "navbar  navbar" 50px
      "sidebar section"   auto
      "footer  footer" 100px /
      200px    auto;
  }
}

@media (min-width: 900px) {
  .grid-container {
    grid-template:
      "header  header header"  100px
      "navbar  navbar navbar"  100px
      "sidebar section section" auto
      "footer  footer footer"  100px /
      200px    auto   200px;
  }
}

