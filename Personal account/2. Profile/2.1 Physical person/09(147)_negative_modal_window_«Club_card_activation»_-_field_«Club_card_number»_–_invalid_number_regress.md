* Тестовые данные: Негативная проверка. Модальное окно “Активация клубной карты” - поле “Номер клубной карты” - невалидный номер.

	тестовый сервер - https://test2.stroyrem-nn.ru/   продовый сервер - https://stroyrem-nn.ru/

* Предусловие: пользователь авторизован, открыт "Личный кабинет" / "Профиль"

* Шаги:
1.	В блоке "Клубная карта" нажать "Активация клубной карты"
	* Ожидаемый результат: открывается модальное окно "Активация клубной карты"
	
2.	В поле "Номер клубной карты" ввести невалидный номер карты
3.	Нажать "Сохранить"
	* Ожидаемый результат: появляется окно с уведомлением "Номер карты не найден"
	
* Постусловие: удалить тестовые данные

Автор: Надежда

* Отчет о тестировании
  
Тестовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA  |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 11.09.23 | 17:50 | Chrome версия 116.0.5845.180 Firefox версия 117.0 | FAIL https://trello.com/c/RUx2lJYZ/541 | Chrome версия 116.0.5845.163 MIUI 12.5.13 | PASS | 03.09.23 | Надежда |  

Продовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 11.09.23 | 17:55 | Chrome версия 116.0.5845.180 Firefox версия 117.0 | FAIL https://trello.com/c/RUx2lJYZ/541 | Chrome версия 116.0.5845.163 MIUI 12.5.13 | PASS | 03.09.23 | Надежда |
 