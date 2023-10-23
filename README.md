# w3_school_js

- JS HOME
- JS Introduction
    - JavaScript Can Change HTML Content
        - Одним из многих HTML-методов JavaScript является getElementById(). В
            приведенном ниже примере "находит" элемент HTML (с id="demo") и
            изменяется содержимое элемента (innerHTML) на "Hello JavaScript":
            > Example
            ```
            document.getElementById("demo").innerHTML = "Hello JavaScript";
            ```
        - JavaScript принимает как двойные, так и одинарные кавычки:
            > Example
            ```
            document.getElementById('demo').innerHTML = 'Hello JavaScript';
            ```
    - JavaScript Can Change HTML Attribute Value
        - В этом примере JavaScript изменяет значение атрибута src (source) тега
            `<img>`:
            > Example
            ```
            <button
            onclick="document.getElementById('myImage').src='images/pic_bulgon.gif'">
                Turn on the light
            </button>
            <img id="myImage" src="images/pic_bulboff.gif" style="width:100px">
            <button
            onclick="document.getElementById('myImage').src='images/pic_bulboff.gif'">
                Turn off the light
            </button>
            ```
    - JavaScript Can Change HTML Style (CSS)
        - Изменение стиля элемента HTML - это вариант изменения атрибута HTML:
            > Example
            ```
            document.getElementById('id').style.fontSize = '35px';
            ```
    - JavaScript Can Hide HTML Elements
        - Скрыть HTML-элементы можно, изменив стиль отображения:
            > Example
            ```
            document.getElementById('demo').style.display = 'none';
            ```
    - JavaScript Can Show HTML Elements
        - Отобразить скрытые элементы HTML также можно, изменив стиль
            отображения:
            > Example
            ```
            document.getElementById('demo').style.display = 'block';
            ```
