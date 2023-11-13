# Создание таблицы

Напиши функцию, которая по по количеству столбцов и строк создает HTML таблицу.

Для реализации можно использовать либо циклы, либо функцию `map`.

Пример:

```js
function createTable( cols, rows ) { ... }
```

Вызов `createTable( 3, 2 );` должен отдать следующий код:

```html
<table>
    <tbody>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>
```

В качестве бонуса реализуй добавление этой таблицы к выбранному по ID элементу DOM, например:

```js
document.getElementById('#test-element').appendChild( ... );
```