# Статический сайт в Yandex Object Storage

С помощью этой инструкции вы научитесь загружать статические файлы вашего сайта в [Object Storage](https://yandex.cloud/ru/docs/storage) и привязывать к бакету доменное имя. Для управления доменом можно воспользоваться сервисом [Yandex Cloud DNS](https://yandex.cloud/ru/docs/dns).

По умолчанию сайт доступен только по протоколу HTTP. Чтобы поддержать для сайта протокол HTTPS, можно загрузить сертификат безопасности из [Yandex Certificate Manager](https://yandex.cloud/ru/docs/certificate-manager).

Подготовка инфраструктуры для статического сайта описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/web/static/), необходимые для настройки конфигурационные файлы `static.tf`, `index.html` и `error.html` расположены в этом репозитории.
