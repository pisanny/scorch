# scorch runbook`s

5.10.1 AD join Computer v.0.3.ois_export - добавление компьютера в домен с ОС: win,linux,solaris
5.1.1.1 Update SR (5.1.1 Access 3d partners request).ois_export - №1 создание пользователя и по необходимости ОУ (Организация), группа (проект, необходимо для доступа) в external AD
5.1.1.2 Create External Account (5.1.1 Access 3d partners request).ois_export - №2 создание пользователя и по необходимости ОУ (Организация), группа (проект, необходимо для доступа) в external AD
5.1.1 External AD. Synchronization OU External to CMDB.ois_export - создание в CMDB SCSM конфигурационной еденицы ОУ (организация), запускается регулярно
5.1.2.1 Update SR (5.1.2 Extension of the External Account).ois_export  - №1 продление учётной записи в external AD
5.1.2.2 Extension of the External Account (5.1.2 Extension of the External Account).ois_export  - №2 продление учётной записи в external AD
5.1.3.1 Password reset (External).ois_export - сброс пароля для учётной записи в external AD
5.3.3 Add User to Group sec_velcom_jira.ois_export - добавление учётной записи в группу sec_velcom_jira - для доступа к Jira
5.7.2 Password reset.ois_export - сброс пароля для учётной записи в AD
5.8.1 Create SC_SG group (Tech Service).ois_export - создание группы безопасности в AD, включение функции группы рассылки (exchange), назначение менеджера группы. Группа создаётся для управления сервисом, назначения ответственного за сервис, рассылки оповещения ответственным с системы мониторинга и системы бэкапа.
5.9.1 Add Permission (Domain Admins).ois_export - добавление заранее определённой учётной записи прав доменного администратора на определённый период (используется функция 2016). Для запроса доменного администатора ответственным работникам.
7.1.1 Update Reviewer Head Division.ois_export - №1 для воркфло "Access to the data center" - согласование с ответственным за доступ к ДЦ
7.1.2 Send SR via Email.ois_export - №2 для воркфло "Access to the data center" - отсылка задачи на исполнение
9.1.1 Assigned To User.ois_export - для воркфло "Universal Service Request" - получение ответственного за сервис (из конфигурационной еденицы service) и назначение МА на ответственного.
LAPS Get User and Computer.ois_export - получение пароля локального администратора компьютера по технологии LAPS и передача его запросившему по смс, сброс пароля через 2 дня.
