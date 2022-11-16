# Онлайн-школа английского языка SkyEng

<H2>Тестирование обновления SkyEng в личном кабинете преподавателя</H2>

<b>Область тестирования:</b> Личные события в календаре

<b>Основные требования к обновлению (главная user-story):</b> Преподаватель может использовать календарь для собственных встреч. Он использует “личные события”, которые служат напоминанием, что у преподавателя что-то запланировано на это время.

Требования можно посмотреть по ссылке: https://skyengpublic.notion.site/bd5a4b593e2d46ff94cca0b455cb1684

<h3> 1. Декомпозиция </h3>

Ссылка на доску в Miro: https://miro.com/app/board/uXjVOgy3VZM=/?share_link_id=596892039144

<h3> 2. План тестирования </h3>

Будут проведены следующие виды тестирования:

<OL> 
<li>Smoke-тестирование (ручное и API)</li>
<li>Тестирование API</li>
<li>Функциональное (на уровне системы, на уровне интеграции, на уровне компонентов)</li>
<li>Регрессионное тестирование</li>
</OL> 


<h3> 3. Тестирование </h3>

<b>Тестирование API в Postman: </b>

https://www.postman.com/security-cosmonaut-14770752/workspace/personal-ivents

<b>Smoke-тест в Qase.io (ручное тестирование):</b>

<img width="1277" alt="Снимок экрана 2022-11-16 в 18 46 13" src="https://user-images.githubusercontent.com/106274596/202227260-8b381baf-d263-4bc3-a5bf-ec00b35bee59.png">
<img width="1276" alt="Снимок экрана 2022-11-16 в 18 46 37" src="https://user-images.githubusercontent.com/106274596/202227309-d3647752-1d65-4c83-a9b6-ebb56dd02d47.png">
<img width="1279" alt="Снимок экрана 2022-11-16 в 18 46 45" src="https://user-images.githubusercontent.com/106274596/202227365-bf1f215e-7ad7-4cd7-aa5f-e64786fead70.png">

<b>Чек-листы в Sitechko:</b>

<img width="989" alt="Снимок экрана 2022-11-16 в 18 56 41" src="https://user-images.githubusercontent.com/106274596/202230249-45a492c6-ec8d-4d78-b819-ca6fb9348137.png">
<img width="996" alt="Снимок экрана 2022-11-16 в 18 56 50" src="https://user-images.githubusercontent.com/106274596/202230262-bb352f4f-3113-44b6-baa2-f9ad25a87db2.png">
<img width="1001" alt="Снимок экрана 2022-11-16 в 18 56 59" src="https://user-images.githubusercontent.com/106274596/202230279-f693c712-86d6-481f-bc8e-eb637fefef12.png">
<img width="998" alt="Снимок экрана 2022-11-16 в 18 57 09" src="https://user-images.githubusercontent.com/106274596/202230296-126560ba-156e-4699-a65b-d24dc37c17a8.png">

<b>Регрессионное тестирование:</b>

Чек-лист в Sitechko:
<img width="1014" alt="Снимок экрана 2022-11-16 в 19 50 11" src="https://user-images.githubusercontent.com/106274596/202242948-27aa5089-ac22-4528-be33-6b615ddaa1dd.png">
<img width="1022" alt="Снимок экрана 2022-11-16 в 19 50 17" src="https://user-images.githubusercontent.com/106274596/202242957-bf53927e-afee-4643-8481-c91939c56862.png">

<h3> 4. Результаты тестирования: </h3>

Отчет по Smoke-test: https://app.qase.io/public/report/8754e4c7d9fbd085e5f42d729b1539c867c42c0f

API-тестирование пройдено успешно: 

![85c0d18a-d7bd-4b5b-86c8-7e3e6ee6a259](https://user-images.githubusercontent.com/106274596/202244303-00487986-589a-488e-8ea2-030041c98efa.png)

Функциональное тестирование по чек-листу:

![b36384d2-ca7f-452a-9361-b0f3ae2cac89](https://user-images.githubusercontent.com/106274596/202241446-326a18d6-4e90-4465-8799-1f84d40824f1.png)

Регрессионое тестирование:

<img width="1015" alt="Снимок экрана 2022-11-16 в 19 52 47" src="https://user-images.githubusercontent.com/106274596/202243577-1f007647-968d-4c29-8ea3-17104bb7738d.png">
<img width="995" alt="Снимок экрана 2022-11-16 в 19 52 57" src="https://user-images.githubusercontent.com/106274596/202243587-045647de-2bab-4b6d-ad83-41587dfebbd2.png">
<img width="1009" alt="Снимок экрана 2022-11-16 в 19 53 12" src="https://user-images.githubusercontent.com/106274596/202243600-48845ba0-80b2-4dcd-803e-c60f2f8b114a.png">

Баг-репорты в Jira: 

<img width="1143" alt="Снимок экрана 2022-11-16 в 19 48 30" src="https://user-images.githubusercontent.com/106274596/202242414-c9341b72-344e-4c7e-ae5a-f84136a3b846.png">
<img width="1131" alt="Снимок экрана 2022-11-16 в 19 55 01" src="https://user-images.githubusercontent.com/106274596/202243976-c0858b21-0259-4a27-828f-5b8d175bd2ff.png">

<h3>Отчет о тестировании итогового проекта</h3>

<ol>
 <li>По результатам API-тестирования багов не найдено</>
 <li>При функциональном тестировании найден один баг с серьезностью Minor</li>
 <li>При регрессионном тестировании найден баг с серьезностью High</li>
<ol>
  
<p COLOR=cc0000>По результатам регрессионного тестирования выявлена поломка в системе. Теперь учителю невозможно отменить урок. До починки этого бага новый функционал выпускать не рекомендуется!</p>


