Regfiz19

Переход в личный кабинет без регистрации при нажатии кнопки "Уже есть аккаунт"

* Тестовые данные: 

Предусловия:

1. Создан юзер аккаунт с электронной почтой

2. Создан тестовый электронный ящик(и)

3. Открыта форма регистрации (ссылка на прод [Регистрация](https://stroyrem-nn.ru/user/register) и на тест [Регистрация](https://test2.stroyrem-nn.ru/user/register))
* Шаги:
1. Не заполняя поля нажать кнопку "Уже есть аккаунт"
   
   **ОР:** После нажатия на кнопку "Уже есть аккаунт" открывается страница входа в личный кабинет

Автор: Татьяна Жукаускене

Отчет о тестировании

Тестовый сервер

| Дата       | Время | Версия браузера Десктоп             | Результат/Баг в Трелло Десктоп     | Версия браузера и ОС Тач          | Результат/Баг в Трелло Тач         | Дата релиза | QA      |
| ---------- | ----- | ----------------------------------- | ---------------------------------- | --------------------------------- | ---------------------------------- | ----------- | ------- |
| 2023-09-12 | 11:36 | Chrome 116.0.5845.182 Firefox 117.0 | FAIL https://trello.com/c/bgQExF0M | Chrome 116.0.5845.172, Android 10 | FAIL https://trello.com/c/bgQExF0M | 03.09.2023  | Татьяна |
|            |       |                                     |                                    |                                   |                                    |             |         |

Продовый сервер

| Дата       | Время | Версия браузера Десктоп             | Результат/Баг в Трелло Десктоп     | Версия браузера и ОС Тач          | Результат/Баг в Трелло Тач         | Дата релиза | QA      |
| ---------- | ----- | ----------------------------------- | ---------------------------------- | --------------------------------- | ---------------------------------- | ----------- | ------- |
| 2023-09-12 | 11:38 | Chrome 116.0.5845.182 Firefox 117.0 | FAIL https://trello.com/c/bgQExF0M | Chrome 116.0.5845.172, Android 10 | FAIL https://trello.com/c/bgQExF0M | 03.09.2023  | Татьяна |
|            |       |                                     |                                    |                                   |                                    |             |         |
