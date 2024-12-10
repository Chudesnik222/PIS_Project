# Диаграмма классов

![](https://github.com/Chudesnik222/PIS_Project/blob/main/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BE%D0%B2.jpg)

## Многослойная архитектура WEB API
Controllers - слой API.

Services - слой бизнес логики.

Repositories - слой доступа к данным.

Models - слой данных.

## Enums:
Role - перечесление ролей пользователя, нужен для распределения ролей.
Status - перечесление статусов заявки.

## Вспомогательные классы:
ApplicationDbContext - класс для Entity Freimwork, используемые для настройки связей между таблицами базы данных.

## Models:
User - модель пользователя, который еще не имеет роли.
Request - заявка, которую создает иностранный гражданин.
Support - модель гос. поддержки
Profile - модель для личных данных или документов пользователей.
Accuting - документ постановки на учет.

## Controllers:
ProfileController - класс-контроллер, включает в себя запросы со стороны клиента на редактирование и заполнения персональных данных Иностранного гражданина.
AuthController - класс-контроллер, отвечающий за регистрацию и авторизацию пользователей.
AccoutingController - класс-контроллер, отвечающий за постановку на учет.
RequestController - класс-контроллер, отвечающий за действия с заявками.
SupportController - класс-контроллер, отвечающий за условия заявок

## Services:
ProfileService - класс-сервис, содержащий бизнес логику личных данных.
AuthService- класс-сервис, содержащий бизнес логику регистрации и авторизации.
AccoutingService- класс-сервис, содержащий бизнес логику постановки на учет.
RequestService - класс-сервис, отвечающий за бизнес логику заявок.
SupportService - класс-сервис, отвечающий забизнес логику условий заявок

## Interfaces:
ISupportService - интерфейс для реализации Dependency Injection.
ISupportRepository - интерфейс для реализации Dependency Injection.
IProfileService - интерфейс для реализации Dependency Injection.
IProfileRepository - интерфейс для реализации Dependency Injection.
IAccoutingService - интерфейс для реализации Dependency Injection.
IAccoutingRepository - интерфейс для реализации Dependency Injection.
IRequestService - интерфейс для реализации Dependency Injection.
IRequestRepository - интерфейс для реализации Dependency Injection.
IAuthService - интерфейс для реализации Dependency Injection.
IAuthRepository - интерфейс для реализации Dependency Injection.
