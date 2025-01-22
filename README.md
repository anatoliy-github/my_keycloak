# my_keycloak

1. BOOTSTRAP_ADMIN временная учетная запись только для первичных настроек. Необходимо создать permanent admin account, а эту учетную запись удалить.
Для этого создать нового пользователя Users - Add User - Role mapping - Assign role - ```admin``` и ```create-realm```