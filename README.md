# goit-markup-hw-08

::after {
position: absolute;
bottom: 0;
left: 0;
content: "";
width: 100%;
height: 4px;
background-color: var(--accent-color);
border-radius: 2px;
}

/_ Применится когда ширина вьюпорта больше чем 900px _/
@media (min-width: 900px) {
body {
background-color: green;
}
}

/_ Применится когда ширина вьюпорта меньше чем 600px _/
@media (max-width: 600px) {
body {
background-color: yellow;
}
}
