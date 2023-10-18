<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="styles.css">
    <style type="text/css">
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
    color: #333;
}



h1 {
    font-size: 2.5em;
    margin: 0;
}

p {
    font-size: 1.2em;
    margin: 0;
}



.moscow {
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    padding: 20px;
    margin: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
}

td {
    padding: 8px;
    border: 1px solid #ddd;
}

.left-column {
    width: 50%;
    background-color: #f0f0f0;
}

.right-column {
    width: 50%;
    background-color: #f7f7f7;
}

.personal-table {
    width: 100%;
    background-color: #f0f0f0;
}

.expirience-table,
.education-table,
info-table,
skills-table {
    width: 100%;
    background-color: #f7f7f7;
}

.skills-table {
    border-radius: 5px;
}

.skills-table td {
    border: none;
}

img {
    width: 285px
    }
    #a {
    border-top: 1px solid #000;

}
/* Добавьте дополнительные стили по вашему усмотрению для красочного оформления. */

    </style>
    <title>Резюме Ивана Петрова</title>
</head>
<body>
    <section id="preview-box">
        <section id="preview" class="preview block">
            <div class="moscow">
                <table>
                    <tr>
                        <td class="left-column">
                            <div class="moscow__head">
                                <div class="moscow__head__photo">
                                    <img src="123.jpeg" alt="">
                                </div>
                                <div class="moscow__head__name" id="preview-fullname">
                                    <span>Совхоз Абай Сәкенұлы</span>
                                </div>
                                <div class="moscow__head__geo">Г. ТАРАЗ (готовность к командировкам)</div>
                            </div>
                            <div class="moscow__title moscow__title--personal">Личная информация</div>
                            <table class="personal-table">
                                <tr>
                                    <td><b>Гражданство:</b></td>
                                    <td>Казахстан</td>
                                </tr>
                                <tr>
                                    <td><b>Образование:</b></td>
                                    <td>Высшее</td>
                                </tr>
                                <tr>
                                    <td><b>Дата рождения:</b></td>
                                    <td>15 августа 1995 (28 лет)</td>
                                </tr>
                                <tr>
                                    <td><b>Пол:</b></td>
                                    <td>Мужской</td>
                                </tr>
                                <tr>
                                    <td><b>Семейное положение:</b></td>
                                    <td>Женат (есть дети)</td>
                                </tr>
                            </table>
                        </td>
                        <td class="right-column">
                            <div class="moscow__title moscow__title--expirience">Опыт работы</div>
                            <table class="expirience-table">
                                <tr>
                                    <td class="position">Преподаватель информатики</td>
                                    <td class="company">ЖПЖК</td>
                                    <td class="period">октябрь 2021 - настоящее время (2 лет)</td>
                                </tr>
                            </table>
                            <div class="moscow__title moscow__title--education">Образование</div>
                            <table class="education-table">
                                <tr>
                                    <td class="school">Таразский региональный университет имени М.Х. Дулати</td>
                                    <td class="class">ИНФОРМАЦИОННЫЕ СИСТЕМЫ (Преподаватель информатики)</td>
                                    <td class="year">2021, очная форма обучения (2 года назад)</td>
                                </tr>
                                <tr>
                                    <td class="school">Таразский региональный университет имени М.Х. Дулати</td>
                                    <td class="class">ВХЭС (Безопасность жизнедеятельности и защита окружающей среды)</td>
                                    <td class="year">2017, очная форма обучения (6 лет назад)</td>
                                </tr>
                            </table>
                            <div class="moscow__title moscow__title--info">Дополнительная информация</div>
                            <table class="info-table">
                                <tr>
                                    <td><b>Служба в армии:</b></td>
                                    <td>служил</td>
                                </tr>
                                <tr>
                                    <td><b>Наличие водительских прав (категории):</b></td>
                                    <td>B, C</td>
                                </tr>
                            </table>
                            <div class="moscow__title moscow__title--skills">Компьютерные навыки</div>
                            <table class="skills-table">
                                <tr>
                                    <td id="a">Печать, сканирование, копирование документов</td>
                                </tr>
                                <tr>
                                    <td id="a">Интернет</td>
                                </tr>
                                <tr>
                                    <td id="a">Электронная почта</td>
                                </tr>
                                <tr>
                                    <td id="a">Microsoft Word</td>
                                </tr>
                                <tr>
                                    <td id="a">Microsoft Excel</td>
                                </tr>
                                <tr>
                                    <td id="a">Microsoft Power Point</td>
                                </tr>
                            </table>
                        </td>
                    </tr>
                </table>
            </div>
        </section>
    </section>
</body>
</html>
