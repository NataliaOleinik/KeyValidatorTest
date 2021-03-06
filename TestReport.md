# Отчёт о тестировании KeyValidator
## Краткое описание
15.09.2020 было проведено Функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

  * https://github.com/NataliaOleinik/KeyValidatorTest/issues/1
  * https://github.com/NataliaOleinik/KeyValidatorTest/issues/2

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

  * Инструкция по установке OpenJDK 11
  * Руководство использования KeyValidator

В качестве тестовых данных использовались:
   * Данные из Инструкцит по установке OpenJDK 11 (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md):

     Инструкция по установке OpenJDK 11 работает под систему Windows 10 Версия 1909(Сборка ОС 18363.1016) 64-разрядная ОС
     Приложение успешно запускается и совместимо с Java openjdk version "11.0.8" 2020-07-14


   * Данные из Руководства использования KeyValidator (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

     Валидные ключи:

       * 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
       * 80b427f8-92cd-3aae-ba04-3927fbe17c6
       * b295bc63-9f03-3b4b-af80-969b39f8c262
       * 387eedc6-12e9-3b32-9881-63b6b5e85317
       * c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

     Невалидные ключи:

       * 18252235-78e0-44a5-8720-556f0c7da17a
       * e66075b6-ddad-445e-baf6-161b3289522b
       * b6d53250-f07e-4352-a293-6102ddf7f1ca
       * c2bc778a-1cb9-46c6-b435-0489649d2a42
       * 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

  ## Ожидаемый результат:

   Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
   Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
   Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
   Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
   Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

   Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
   Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
   Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
   Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
   Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL


  ## Фактический Результат:

   Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
   Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: FAIL
   Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
   Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
   Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

   Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
   Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
   Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
   Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
   Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: OK

 ## Тестирование производилось в следующем окружении:
   Windows 10 Версия 1909(Сборка ОС 18363.1016) 64-разрядная ОС
   Java openjdk version "11.0.8" 2020-07-14
