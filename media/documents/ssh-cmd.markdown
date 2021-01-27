<!-- 
Подтверждение прав на zzzi.site

Это наиболее простой способ подтверждения прав на управление сайтом.
В корне сайта создайте файл с именем yandex_fcd36b7fc21af82d.html и со следующим содержимым:
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    </head>
    <body>Verification: fcd36b7fc21af82d</body>
</html>

    Убедитесь, что:
        Файл содержит только указанный выше код. Если в HTML-файл автоматически добавляется дополнительный контент, например, элементы дизайна, проверьте настройки вашего сервера. Если вам не удается создать файл с указанным содержимым, используйте другой способ подтверждения прав.
        Файл по адресу http://zzzi.site/yandex_fcd36b7fc21af82d.html открывается.
    Если сайт работает по IPv4 и IPv6, убедитесь, что по всем IP-адресам сайт отвечает корректно.
    Нажмите кнопку Проверить.

 -->

yc iam api-key list --service-account-name quest
yc iam api-key list --service-account-name lamp
+----------------------+---------------------+
|          ID          |     CREATED AT      |
+----------------------+---------------------+
| aje7lcb3vuu0knbtk7ua | 2020-12-21 10:35:01 |
+----------------------+---------------------+


Очистите базу данных firefox.
find ~ / .mozilla / firefox / -type f -name "* .sqlite" -exec sqlite3 {} VACUUM \;


curl https://storage.yandexcloud.net/yandexcloud-yc/install.sh | bash


Если вы знаете имя сервисного аккаунта, получите его идентификатор с помощью команды get:




ajek63f0l1tjr3iq6cnc

yc iam service-account list   
+----------------------+--------+
|          ID          |  NAME  |
+----------------------+--------+
| aje1c1141cdk31o5u8bt | zigi2p |
| ajejh9jt0oahd8f324qa | zzz    |
| ajejr7q31bs6e6ouu7e5 | easy   |
| ajek63f0l1tjr3iq6cnc | quest  |
| ajetug7lgaokuer0jchc | lamp   |
+----------------------+--------+

yc init

yc iam create-token
t1.9euelZqOlI2VjZTPi4nKi86UjpSZl-3rnpWaz83MlMrLicaSy52alZnHjpTl9PcLblh_-e9PdRyY3fT3SxxWf_nvT3UcmA.t33opTcwWTzeZ9TOQmsKT4rewD4_-ke2GvxKUDitG_nIv3OTdLjEtmy4Qw3Cj7J8XSdjqa_q9JxcObqDzPOnCA

export IAM_TOKEN=`t1.9euelZqOlI2VjZTPi4nKi86UjpSZl-3rnpWaz83MlMrLicaSy52alZnHjpTl9PcLblh_-e9PdRyY3fT3SxxWf_nvT3UcmA.t33opTcwWTzeZ9TOQmsKT4rewD4_-ke2GvxKUDitG_nIv3OTdLjEtmy4Qw3Cj7J8XSdjqa_q9JxcObqDzPOnCA`
curl -H "Authorization: Bearer ${IAM_TOKEN}" \
https://resource-manager.api.cloud.yandex.net/resource-manager/v1/clouds
