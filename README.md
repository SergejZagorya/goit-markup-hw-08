# goit-markup-hw-08

<!-- *===================Работа 8====================== -->

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

<picture>
  <source media="(min-width: 1200px)" srcset="./images/portfolio/1-1200.jpg 1x, ./images/portfolio/1-1200@2x.jpg 2x" />

  <source media="(min-width: 480px)" srcset="./images/portfolio/1-480.jpg 1x, ./images/portfolio/1-480@2x.jpg 2x" />

  <img src="./images/portfolio/1-1200.jpg" alt="Пример веб-сайта" width="370" height="294" />
</picture>

  <source media="(min-width: 768px)" srcset="./images/portfolio/1-768.jpg 1x, ./images/portfolio/1-768@2x.jpg 2x" />
