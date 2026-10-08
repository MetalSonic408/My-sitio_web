body {
    font-family: Arial,  sans-serif; /* Familia de fuentes */
    font-size: 11px; /* El tamaño de la fuente principal en el tag <p></p> */
    background-color: grey; /* El color del fondo de la página web */
    color: rgb(51, 51, 51); /* El color del texto*/ 
}
h1 {
    color: blue; /* El color de la cabecera */
    font-size: 40px; /* El tamaño de la fuente de la cabecera */
    font-family: Georgia, serif; /* La familia tipográfica utilizada en la cabecera */
}

h1:hover {
    color: blue; /* El color de la cabecera */
    font-size: 60px; /* El tamaño de la fuente de la cabecera */
    font-family: Georgia, serif; /* La familia tipográfica utilizada en la cabecera */
    animation: color-change 3s infinite;
}

p {
   color: pink;
   font-size: 28px;
   font-family: Inter;
   animation: color-p 3s infinite;
}

h2 {
    color: green;
    font-size: 26px;
    font-family: Inter;
    animation: color-h2 3s infinite;
}

li {
    color: white;
    font-size: 24px; 
    font-family: Inter;
    animation: color-li 3s infinite;
}

@keyframes color-change {
  0%   { color: rgb(0, 255, 55); }
  50%  { color: rgb(255, 0, 76); }
  100% { color: rgb(255, 251, 0); }
}

@keyframes color-p {
  0%   { color: rgb(0, 4, 255); }
  50%  { color: rgb(255, 0, 140); }
  100% { color: rgb(255, 136, 0); }
}

@keyframes color-h2 {
  0%   { color: rgb(208, 255, 0); }
  50%  { color: rgb(30, 255, 0); }
  100% { color: rgb(0, 247, 255); }
}

@keyframes color-li {
  0%   { color: rgb(231, 217, 13); }
  50%  { color: rgb(255, 0, 128); }
  100% { color: rgb(0, 255, 179); }
}

button {
background-color: #ff5975;
}

button:hover {
background-color: #59ff90;
}
