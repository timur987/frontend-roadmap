# Делаем счетчик нажатий с помощью React.useState()

[Документация](https://react.dev/reference/react/useState).

Используя React-приложение (можно создать с помощью [Create-React-App](https://create-react-app.dev/)), создать пользовательский интерфейс, содержащий:
- Кнопку "+1",
- Кнопку "Сброс",
- Поле (только чтение) для показа количества нажатий

Каждое нажатие на "+1" увеличивает количество нажатий на 1. Нажатие на "Сброс" обнуляет счетчик.

Для хранения состояния будем использоваться useState.

Пример инициализации: 
```js
const [clicks, setClicks] = React.useState(0);
```

Пример использования:
```js
function increase() {
    setClicks(clicks + 1);
}

function reset() {
    // TODO: Реализовать по аналогии
}
return (
    <>
        <button onClick={increase}>+1</button>
        <button onClick={reset}>Сброс</button>
        <input type="text" readonly value={clicks}/>
    </>
);
```