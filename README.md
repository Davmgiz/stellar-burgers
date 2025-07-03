# Stellar Burgers

Приложение для сборки бургеров, оформления заказов и управления профилем. Поддерживает работу с WebSocket, авторизацию и историю заказов.

## Функции

* Конструктор бургеров с drag-and-drop
* Авторизация и восстановление пароля
* Оформление и отслеживание заказов
* Личный кабинет с историей заказов

## Стек

* React, TypeScript, Redux Toolkit
* React Router v6, React DnD
* WebSocket, Vite
* Jest, Cypress

## Установка

```bash
git clone https://github.com/DarKingRD/stellar-burgers.git
cd stellar-burgers
npm install
npm start
```

## Сборка

```bash
npm run build
```

## Тесты

```bash
npm test
npm run cypress:open
npm run storybook
```

## Структура

```
src/
├── components/
├── hooks/
├── pages/
├── services/
├── store/
├── styles/
├── tests/
└── utils/
```

[Сайт](https://Davmgiz.github.io/stellar-burgers/)
