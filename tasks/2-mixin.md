# Миксины

В этом задании вам необходимо создать три миксина:

1. Миксин `opacity-transition-1s`. Он отвечает за наличие свойства `transition`, которое применяется к свойству `opacity`. Время выполнения `transition` — 1 секунда. Добавьте вендорные префиксы `-moz`- и `-webkit`- для наилучшей совместимости со старыми браузерами. Прочитать о свойстве `transition` вы можете в [документации MDN](https://developer.mozilla.org/ru/docs/Web/CSS/transition). Используйте вариант с двумя значениями: имя свойства и длительность.
2. Миксин `link-hover`. В этом миксине будут находиться свойства для события наведения мыши на наш элемент. Внутри него нужно свойство `opacity` со значением 0.5. После этого подключите в него миксин `opacity-transition-1s`.
3. Миксин `link`. Наш главный миксин, внутри которого находятся следующие свойства:
    - Цвет текста: `#333`.
    - Отсутствие подчёркивания у элемента.
    - Жирное начертание текста.
    - После этого для события *hover* подключите соответствующий миксин.