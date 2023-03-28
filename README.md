# mavka-ca-1d

Клітинковий автомат у [Мавці](https://xn--80aaf6ah.xn--j1amh/).

Приклад виводу для параметрів:

```text
правило = 90
початковий_стан = [0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0]
```

```text
_______К_______
______К_К______
_____К___К_____
____К_К_К_К____
___К_______К___
__К_К_____К_К__
_К___К___К___К_
К_К_К_К_К_К_К_К
К_____________К
КК___________КК
_КК_________КК_
КККК_______КККК
___КК_____КК___
__КККК___КККК__
_КК__КК_КК__КК_
ККККККК_ККККККК
______К_К______
_____К___К_____
____К_К_К_К____
___К_______К___
```

## Встановлення

> **Note**
> Встановлення є необов'язковим, оскільки ви можете
> спробувати мову прямо в браузері [ось тут](https://xn--80abeya8cf6f.xn--80aaf6ah.xn--j1amh/)
>
> В такому випадку просто скопіюйте файли `старт.м` та `функційні_операції.м` у гральний майданчик.
Необхідно встановити NodeJS та пакетний менеджер NPM.

1. Встановлення Мавки:

    - глобально

        ```bash
        npm i -g mavka
        ```

    - лише у проєкті

        ```bash
        npm install
        ```

2. Запуск проєкту

    - за допомогою [завдань VS Code](https://github.com/dkostmii/mavka-vs-code-setup#%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D0%B7%D0%B0%D0%B2%D0%B4%D0%B0%D0%BD%D0%BD%D1%8F-%D0%B7%D0%B0-%D0%B7%D0%B0%D0%BC%D0%BE%D0%B2%D1%87%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F%D0%BC-default-task)

    - за допомогою [скрипта NPM](https://github.com/dkostmii/mavka-npm-setup#%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D0%BF%D1%80%D0%BE%D1%94%D0%BA%D1%82%D1%83)
