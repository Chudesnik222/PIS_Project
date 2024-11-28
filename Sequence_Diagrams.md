# Диаграммы последовательностей

## Вход в систему
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%92%D1%85%D0%BE%D0%B4%20%D0%B2%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%83.png)

Описание:
* Пользователь пытается войти в систему, предоставляя свои учетные данные.

* AuthController передает запрос на вход в AutoService.

* AuthService использует HashPasswordService для хеширования пароля.

* AuthService запрашивает у AuthRepository данные пользователя.

* AuthRepository возвращает данные пользователя.

* AuthService проверяет соответствие хешированного пароля и возвращает статус операции.


## Просмотр личных данных и документов
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%20%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.png)

Описание:
* Участник Гоc программы инициирует запрос на просмотр личных данных и документов.

* ProfileController передает запрос в ProfileService.

* ProfileService запрашивает данные из ProfileRepository.

* ProfileRepository возвращает данные о профиле.

* ProfileService возвращает данные участнику.


## Обновление личных данных
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.png)

Описание:
* Участник Гоc программы инициирует запрос на обновление личных данных.

* ProfileController передает запрос в ProfileService.

* ProfileService обновляет данные профиля и передает их в ProfileRepository.

* ProfileRepository сохраняет обновленные данные в базе данных.

* ProfileService возвращает статус операции и обновленный объект Profile.


## Получение информации о процедуре постановки на учет
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BE%20%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D0%B4%D1%83%D1%80%D0%B5%20%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%BD%D0%B0%20%D1%83%D1%87%D0%B5%D1%82.png)

Описание:
* Участник Гоc программы инициирует запрос на получение информации о процедуре постановки на учет.

* AccountingController передает запрос в AccountingService.

* AccountingService запрашивает информацию из AccountingRepository.

* AccountingRepository возвращает данные о процедуре постановки на учет.

* AccountingService возвращает информацию участнику.


## Запись на прием в Управление по вопросам миграции МВД России
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D0%BD%D0%B0%20%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%20%D0%B2%20%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%20%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D0%B0%D0%BC%20%D0%BC%D0%B8%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%B8.png))

Описание:
* Участник Гоc программы инициирует запрос на запись на прием.

* RequestController передает запрос в RequestService.

* RequestService создает запись о записи на прием и передает ее в RequestRepository.

* RequestRepository сохраняет запись в базе данных.

* RequestService возвращает статус операции и обновленный объект Request.


## Получение информации о мерах государственной поддержки
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BE%20%D0%BC%D0%B5%D1%80%D0%B0%D1%85%20%D0%B3%D0%BE%D1%81%D1%83%D0%B4%D0%B0%D1%80%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B8.png)

Описание:
* Участник Гоc программы инициирует запрос на получение информации о мерах государственной поддержки.

* SupportService обрабатывает запрос и возвращает информацию о мерах поддержки.


## Отмена записи на прием
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D1%82%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D0%B8%20%D0%BD%D0%B0%20%D0%BF%D1%80%D0%B8%D0%B5%D0%BC.png))

Описание:
* Участник Гоc программы инициирует запрос на отмену записи на прием.

* RequestControlLier передает запрос в RequestService.

* RequestService отменяет запись и передает ее в RequestRepository.

* RequestRepository обновляет данные в базе данных.

* RequestService возвращает статус операции и обновленный объект Request.


## Редактирование сроков и условий получения услуги
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%81%D1%80%D0%BE%D0%BA%D0%BE%D0%B2%20%D0%B8%20%D1%83%D1%81%D0%BB%D0%BE%D0%B2%D0%B8%D0%B9%20%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%83%D1%81%D0%BB%D1%83%D0%B3%D0%B8.png)

Описание:
* Администратор инициирует процесс редактирования сроков и условий получения услуги.

* SupportControl1er передает запрос на редактирование в SupportService.

* SupportService обрабатывает запрос и передает новые настройки в SupportRepository.

* SupportRepository обновляет данные в базе данных.

* SupportService возвращает статус операции и обновленный объект Support.


## Получение уведомлений о статусе заявки
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%83%D0%B2%D0%B5%D0%B4%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BE%20%D1%81%D1%82%D0%B0%D1%82%D1%83%D1%81%D0%B5%20%D0%B7%D0%B0%D1%8F%D0%B2%D0%BA%D0%B8.png)

Описание:
* Участник Гоc программы инициирует запрос на получение уведомления о статусе заявки.

* RequestController передает запрос в RequestService.

* RequestService запрашивает информацию о заявке из RequestRepository.

* RequestRepository возвращает данные о заявке.

* RequestService возвращает статус заявки участнику.


## Отмена заявки и запись пояснений
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%9E%D1%82%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%B7%D0%B0%D1%8F%D0%B2%D0%BA%D0%B8%20%D0%B8%20%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D0%BF%D0%BE%D1%8F%D1%81%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9.png)

Описание:
* Сотрудник Управления по вопросам миграции МВД России инициирует запрос на отмену заявки и запись пояснений.

* RequestController передает запрос в RequestService.

* RequestService отменяет заявку и записывает пояснения, передавая данные в RequestRepository.

* RequestRepository сохраняет данные в базе данных.

* RequestService возвращает статус операции и обновленный объект Request.


## Выдача результата постановки на учет
![](https://github.com/Chudesnik222/PIS_Project/blob/main/Sequence_Diagrams/%D0%92%D1%8B%D0%B4%D0%B0%D1%87%D0%B0%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%B0%20%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%BD%D0%B0%20%D1%83%D1%87%D0%B5%D1%82.png)

Описание:
* Корпоративный участник программы инициирует запрос на выдачу результата постановки на учет.

* AccountingController передает запрос в AccountingService.

* AccountingService создает запись о постановке на учет и передает ее в AccountingRepository.

* AccountingRepository сохраняет запись в базе данных.

* AccountingService возвращает статус операции и обновленный объект Accounting.
