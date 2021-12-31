# Basic Css Reset Snipets
```basic
@import url('https://fonts.googleapis.com/css2?family=Pushster&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@700&display=swap');
*,
*:after,
*:before {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
:root {
  --bg: #222327;
  --transition: stroke-dashoffset 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275)
    forwards;
  --font-1: 'Pushster', cursive;
  --font-2: 'Fira Sans Condensed', sans-serif;
  --white: #fff;
}

body {
  font-size: 62.5%;
  background: var(--bg);
}
.container {
  margin: 0 auto;
  max-width: 114rem;
  width: calc(100% - 2rem);
  padding: 0 1rem;
  height: 100vh;
}
```