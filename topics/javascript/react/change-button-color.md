# Смена цвета кнопки

Дана кнопка. По нажатию на неё нужно менять цвет.

Для реализации будем использовать useState.

```js
import { useState } from "react";

function ButtonTask () {
    // Цвета, в которые будем раскрашивать кнопку
    const colors = [
        '#2692e3',
        '#e326e3',
        '#38e326',
    ];

    // <-- Используй useState для хранения состояния colorIndex (индекс массива цветов)

    function getButtonColor() {
        // <-- Отдать текущий цвет кнопки
    }

    function changeColor() {
        // <-- Поменять текущий цвет кнопки на следующий
    }

    return (
        <button
            style={{
                backgroundColor: getButtonColor(),
            }}
            onClick={changeColor}
        >
            Сменить цвет
        </button>
    );
}

export default ButtonTask;
```

Пример работы кнопки:

![image](./images/change-button-color.gif)