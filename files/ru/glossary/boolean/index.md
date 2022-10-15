---
title: Boolean (Булев, Логический тип данных)
slug: Glossary/Boolean
tags:
  - Boolean
  - JavaScript
  - Глоссарий
  - Логический тип данных
  - Типы данных
  - языки программирования
translation_of: Glossary/Boolean
original_slug: Глоссарий/Boolean
---
**Boolean (Булев, Логический тип данных)** — примитивный тип данных в информатике, которые могут принимать два возможных значения, иногда называемых истиной (`true`) и ложью (`false`). Например, в JavaScript Булевы состояния часто используются для того, чтобы определить какие части кода выполнять (например, в [операторах if](/ru/docs/Web/JavaScript/Reference/Statements/if...else)) или повторять (например, [циклы for](/ru/docs/Web/JavaScript/Reference/Statements/for)).

Ниже приведён некоторый псевдокод JavaScript (это не действительно исполняемый код), демонстрирующий эту концепцию.

Пример использования оператора `if`:

```
if (условие) {
    блок кода, выполняемый если условие возвращает true
} else {
    блок кода, выполняемый если условие возвращает false
}
```

К примеру:

```js
if (hour < 18) {
    greeting = "Добрый день";
} else {
    greeting = "Добрый вечер";
}
```

Пример использования логического условия в цикле `for`:

```
for (начало; условие; шаг) {
    // ... тело цикла ...
}
```

К примеру:

```js
for (let i = 0; i < 3; i++) {
    alert(i);
}
```

Булевы значения названы в честь английского математика {{interwiki("wikipedia", "George Boole")}}, который был первопроходцем в области математической логики.

## Смотрите также

### Общие сведения

- {{Interwiki("wikipedia", "Boolean data type", "Boolean")}} на Wikipedia

### Техническая справка

- Глобальный объект JavaScript: {{jsxref("Boolean")}}
- [Типы данных JavaScript и структуры данных](/ru/docs/Web/JavaScript/Data_structures)