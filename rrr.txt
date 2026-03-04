//сделать фон body красным
// 1)document.body.style.backgroud = 'red'
// 2)document.getElementdyId("id элемента") //поиск элемента по ID
// 3)document.querySelector
// 4)document
// 5)document
//
//


//создание обработчика событий click
// const clicker = () => {
//     const div = document.querySelector("div")
//     div.textContent = "Hello,world"
// }

// document.querySelector("button").addEventListener("click", clicker)

// <!DOCTYPE html>
// <html lang="en">
// <head>
//     <meta charset="UTF-8">
//     <meta http-equiv="X-UA-Compatible" content="IE=edge">
//     <meta name="viewport" content="width=device-width, initial-scale=1.0">
//     <title>Document</title>
//     <link rel="stylesheet" href="./style.css">
// </head>
// <body>
//     <div></div>
//     <button>CLICK</button>
//     <script src="./script.js"></script>
// </body>
// </html>

// 1) Изменение текста элемента при клике. 
// Создайте кнопку и элемент <p>. При клике на кнопку измените текст внутри <p> на фразу "Текст изменен" .
// 2) Переключение класса при наведении.
// Создайте блок с текстом. При наведении на блок добавляйте ему класс, который меняет цвет фона. При уходе курсора удаляйте этот атрибут класс.
// 3) Переключение видимости элемента.
// Создайте кнопку <button> и элемент <div>. По нажатию на кнопку скрывайте и показывайте элемент <div>
// 4) Изменение стилей элементов.
// Создайте несколько блоков (div) и кнопок (button). Каждая из них должна изменять стиль (цвет фона, размер шрифта) какого-либо блока по нажатию на соответствующую кнопку.
// 5) Добавление и удаление элементов списка.
// Создайте список <ul> с элементами списка (<li>). Добавьте текстовое поле и кнопку, при нажатии на которую добавляется новый элемент в список. Также рядом с каждым элементов создайте кнопку "Удалить", которая удаляет конкретный элемент из списка.
// 6) Изменение нескольких элементов на странице.
// Сделайте таблицу с несколькими строками и столбцами. При нажатии на ячейку она должна менять свой цвет на зеленый. При повторном нажатии - возвращаться в исходное состояние.
// (подсказка) - используйте метод classList.toggle() для переключения класса.
// Всё в одном файле разными функциями

// <!DOCTYPE html>
// <html lang="en">
// <head>
//     <meta charset="UTF-8">
//     <meta http-equiv="X-UA-Compatible" content="IE=edge">
//     <meta name="viewport" content="width=device-width, initial-scale=1.0">
//     <title>Document</title>
//     <link rel="stylesheet" href="./style.css">
// </head>
// <body>
//     <div class="white">ЭТО ПЕРВЫЙ DIV</div>
//     <button onclick="clicker()">CLICK</button>
//     <script src="./script.js"></script>
// </body>
// </html>
 
// .white {
//     background-color: white;
//     height: 80px;
//     color: black;
// }
 
// .black {
//     background-color: rgb(0, 0, 0);
//     height: 80px;
//     color: rgb(255, 255, 255);
// }
 
// //работа с атрибутами class элементов
// //элемент.classList.add/remove/toggle("название")
// //toggle("название") - добавляет класс, если отсутствует у элемента
// // или удаляет класс, если он уже имеется
// const clicker = () => {
// const firstDiv = document.querySelector("div")
// firstDiv.classList.toggle("black")
// }
 
 