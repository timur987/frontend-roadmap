# Создать объект, описывающий собаку

Необходимо создать объект
```js
const dog = {
    // <-- Нужно добавить поля
}
```

Для проверки объекта можно использовать функцию:
```js
function isDog(obj) {
    if (typeof obj !== "object") {
        return false;
    }
    if (!obj?.name) {
        return false;
    }
    if (!obj?.legs || isNaN(obj.legs) || obj.legs !== 4) {
        return false;
    }
    if (!obj?.tails || isNaN(obj.tails) || obj.tails !== 1) {
        return false;
    }
    return true;
};
```

Например результатом выполнения следующей строки:
```js
isDog(dog);
```

должно быть `true`.