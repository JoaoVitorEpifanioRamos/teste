# teste<html>
    <body>
        <style>
            .box {
                width: 200px;
                height: 200px;
                background-color: purple;
                margin-left: 0;
            }
            .animEsquerda {
                transition: 1s;
                margin-left: 200px;
                margin-top: 20px;
                background-color: blue;
            }
            .box1 {
                width: 200px;
                height: 200px;
                background-color: brown;
                margin-left: 0;
                border-style: groove;
            }
            .animEsquerda1 {
                transition: 1s;
                margin-left: 200px;
                margin-top: 20px;
                background-color: blue;
            }
        </style>
        <div class="box"></div>
        <div class="box1"></div>
        <script>
             var box = document.querySelectorAll('.box')[0];

             box.addEventListener('click', () => {
                box.classList.toggle('animEsquerda');
             });

             var box1 = document.querySelectorAll('.box1')[0];

             box1.addEventListener('click', () => {
                box1.classList.toggle('animEsquerda1');
             });
        </script>
    </body>
</html>
