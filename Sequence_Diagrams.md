# Диаграммы последовательностей

## Вход в систему
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%92%D1%85%D0%BE%D0%B4%20%D0%B2%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%83.png)


Участник: Пользователь

Действия:

* Пользователь вводит данные для входа или регистрации.

* Система обращается к AuthController, который вызывает AuthService.

* AuthService проверяет или добавляет пользователя в базу данных через AuthRepository.

* Результат возвращается обратно через цепочку вызовов.


## Просмотр личных данных и документов
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%20%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.png)

Участник: Пользователь (User)

Действия:

* Пользователь запрашивает просмотр своих личных данных и документов.

* Система обращается к ProfileController, который вызывает ProfileService.

* ProfileService запрашивает данные из ProfileRepository.

* ProfileRepository обращается к базе данных для получения данных пользователя.

* Результат возвращается обратно через цепочку вызовов.


## Обновление личных данных
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.png)

Участник: Пользователь (User)

Действия:

* Пользователь обновляет свои личные данные и документы.

* Система обращается к ProfileController, который вызывает ProfileService.

* ProfileService обновляет данные в ProfileRepository.

* ProfileRepository сохраняет изменения в базе данных.

* Результат возвращается обратно через цепочку вызовов.


## Получение информации о процедуре постановки на учет
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BE%20%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D0%B4%D1%83%D1%80%D0%B5%20%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%BD%D0%B0%20%D1%83%D1%87%D0%B5%D1%82.png)

Участник: Участник Гос. программы

Действия:

* Участник запрашивает информацию о процедуре постановки на учет.

* Система обращается к AccountingController, который вызывает AccountingService.

* AccountingService запрашивает данные из AccountingRepository.

* AccountingRepository обращается к базе данных для получения информации.

* Результат возвращается обратно через цепочку вызовов.


## Запись на прием в Управление по вопросам миграции МВД России
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D0%BD%D0%B0%20%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%20%D0%B2%20%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%20%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D0%B0%D0%BC%20%D0%BC%D0%B8%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%B8.png))

Участник: Участник Гос. программы

Действия:

* Участник запрашивает запись на прием в Управление по вопросам миграции.

* Система обращается к RequestController, который вызывает RequestService.

* RequestService создает запись в RequestRepository.

* RequestRepository сохраняет данные в базе данных.

* Результат возвращается обратно через цепочку вызовов.


## Получение информации о мерах государственной поддержки
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BE%20%D0%BC%D0%B5%D1%80%D0%B0%D1%85%20%D0%B3%D0%BE%D1%81%D1%83%D0%B4%D0%B0%D1%80%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B8.png)

Участник: Участник Гос. программы

Действия:

* Участник запрашивает информацию о мерах государственной поддержки.

* Система обращается к SupportController, который вызывает SupportService.

* SupportService запрашивает данные из SupportRepository.

* SupportRepository обращается к базе данных для получения информации.

* Результат возвращается обратно через цепочку вызовов.


## Отмена записи на прием
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D1%82%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D0%B8%20%D0%BD%D0%B0%20%D0%BF%D1%80%D0%B8%D0%B5%D0%BC.png))

Участник: Участник Гос. программы

Действия:

* Участник отменяет запись на прием.

* Система обращается к RequestController, который вызывает RequestService.

* RequestService удаляет запись из RequestRepository.

* RequestRepository удаляет данные из базы данных.

* Результат возвращается обратно через цепочку вызовов.


## Редактирование сроков и условий получения услуги
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%81%D1%80%D0%BE%D0%BA%D0%BE%D0%B2%20%D0%B8%20%D1%83%D1%81%D0%BB%D0%BE%D0%B2%D0%B8%D0%B9%20%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%83%D1%81%D0%BB%D1%83%D0%B3%D0%B8.png)

Участник: Участник Гос. программы

Действия:

* Участник вносит изменения в настройки (Settings) сроков и условий получения услуги.

* Система обращается к SettingsController, который вызывает SettingsService.

* SettingsService обновляет настройки в SettingsRepository.

* SettingsRepository сохраняет изменения в базе данных.

* Результат возвращается обратно через цепочку вызовов.


## Получение уведомлений о статусе заявки
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%83%D0%B2%D0%B5%D0%B4%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BE%20%D1%81%D1%82%D0%B0%D1%82%D1%83%D1%81%D0%B5%20%D0%B7%D0%B0%D1%8F%D0%B2%D0%BA%D0%B8.png)

Участник: Участник Гос. программы

Действия:

* Участник запрашивает уведомление о статусе своей заявки.

* Система обращается к RequestController, который вызывает RequestService.

* RequestService запрашивает данные из RequestRepository.

* RequestRepository обращается к базе данных для получения статуса заявки.

* Результат возвращается обратно через цепочку вызовов.


## Отмена заявки и запись пояснений
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D1%82%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%B7%D0%B0%D1%8F%D0%B2%D0%BA%D0%B8%20%D0%B8%20%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D0%BF%D0%BE%D1%8F%D1%81%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9.png)

Участник: Участник Гос. программы

Действия:

* Участник отменяет заявку и записывает пояснения.

* Система обращается к RequestController, который вызывает RequestService.

* RequestService удаляет заявку и сохраняет пояснения в RequestRepository.

* RequestRepository обновляет данные в базе данных.

* Результат возвращается обратно через цепочку вызовов.


## Выдача результата постановки на учет
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%92%D1%8B%D0%B4%D0%B0%D1%87%D0%B0%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%B0%20%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%BD%D0%B0%20%D1%83%D1%87%D0%B5%D1%82.png)

Участник: Участник Гос. программы

Действия:

* Система обращается к AccountingController, который вызывает AccountingService.

* AccountingService создает запись о результате постановки на учет в AccountingRepository.

* AccountingRepository сохраняет данные в базе данных.

* Результат возвращается обратно через цепочку вызовов.
