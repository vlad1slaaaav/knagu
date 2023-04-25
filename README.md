# knagu
Лабораторная работа
Описание проекта
7 варик -- Фронтенд: проекты и примеры кода для разработки фронтенда
приложений, включая HTML, CSS и JavaScript, а также различные
библиотеки и фреймворки для работы с пользовательским
интерфейсом.


// Пример кода для создания динамического интерфейса с помощью React.js

import React, { useState } from 'react';

function App() {
  const [count, setCount] = useState(0);

  function handleIncrement() {
    setCount(count + 1);
  }

  function handleDecrement() {
    setCount(count - 1);
  }

  return (
    <div>
      <h1>Counter: {count}</h1>
      <button onClick={handleIncrement}>+</button>
      <button onClick={handleDecrement}>-</button>
    </div>
  );
}

export default App;
