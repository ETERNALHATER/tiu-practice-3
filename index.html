<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="forms.css">

</head>

<body>
    <div class="head">
        <h1>Практическое задание №3</h1>
        <p>В рамках задания вам необходимо создать на сайте форму обратной связи.</p>
        <p>На данной странице будет 2 примера: заполнение небольшой анкеты и подсчет купленных товаров</p>
    </div>


    <!-- Пример №1 -->
    <div>
        <form action="" method="post">
            <fieldset>
                <legend>Пример №1. Анкета</legend>
                <label>Фамилия <input class="field" type="text" name="surname"> </label><br>
                <label>Имя <input class="field" type="text" name="name"> </label><br>
                <label>Отчество <input class="field" type="text" name="lastname"> </label><br>
                <label>Год рождения <input class="field" type="date" name="date"> </label><br>
                <label><b>Пол</b></label><br>
                <label><input type="radio" name="gender" id="g-1" value="Мужской">Мужской</label>
                <label><input type="radio" name="gender" id="g-2" value="Женский">Женский</label><br>
                <input class="button" type="submit" value="Отправить" name="search_example_1">
            </fieldset>
        </form>
    </div>



    <?php
    //Скрипт будет отрабатывать только по нажатию клавишу отправить 
    if (isset($_POST["search_example_1"])) {
        //Создаем div, в котором будут отображаться данные, переданные на сервер
        echo "<div class=out>";
        echo "<h2>Вами были введены следующие данные: </h2>";

        /*
            Считываем значения, которые пришли на сервер
            Для этого используем тот же метод, который был написан при создании формы
            В этом случае, метод был Post, поэтому используется массив $_POST, откуда будет браться информация
            Обязательно соблюдайте синтаксис - если массив будет называться по другому, то считываться
            информация не будет!
            Считываем по тем именам, которые были написаны в атрибут name у input-ов
        */
        //Создаются переменные для считывания и в них сразу записываются данные из массива $_POST
        $name = $_POST["name"];
        $surname = $_POST["surname"];
        $lastname = $_POST["lastname"];
        $date = $_POST["date"];
        $gender = $_POST["gender"];
        //Выводим информацию на экран через абзацы и функцию echo
        echo "<p>ФИО: $surname $name $lastname</p>";
        echo "<p>Дата рождения: $date</p>";
        echo "<p>Пол: $gender</p>";
        //Закрываем тег div
        echo "</div>";
    }
    ?>


    <!-- Пример №2 -->
    <!-- Создадим средствами php таблицу с товарами, которые нужно будет купить и их количество -->


    <div>
        <form action="" method="post">
            <fieldset>
                <legend>Пример №2. Список купленных товаров</legend>
                <table>
                    <thead>
                        <th>Название</th>
                        <th>Цена</th>
                        <th>Количество</th>
                    </thead>
                    <tbody>
                        <?php
                        function create_row($product, $price)
                        {

                            echo "<td>$product</td>";
                            echo "<td>$price</td>";
                            echo "<td><input class= 'tfield' type='number' min=0  name=\"$product\"></td>";
                        }


                        $products = ["milk", "apple", "water", "fish", "cookies"];
                        $price = [95, 67, 35, 877, 120];
                        for ($i = 0; $i < count($products); $i++) {
                            echo "<tr>";
                            create_row($products[$i], $price[$i]);
                            echo "</tr>";
                        }


                        if (isset($_POST["search_example_2"])) {
                            $sum = 0;
                            echo "<tr>";
                            echo "<td class='allprice'>";
                            for ($i = 0; $i < count($products); $i++) {
                                if ($_POST[$products[$i]] != "") {
                                    $quan = $_POST[$products[$i]];
                                    $sum = $sum + $quan * $price[$i];
                                    echo "Товар $products[$i] - $quan шт. <br>";
                                }
                            }
                            
                            echo "Итого: $sum<td>";
                            echo "</tr>";
                        }


                        ?>
                    </tbody>
                </table>

                <input class="button" type="submit" value="Рассчитать" name="search_example_2">

            </fieldset>
        </form>
    </div>





</body>

</html>