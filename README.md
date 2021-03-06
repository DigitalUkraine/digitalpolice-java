# digitalpolice-api
[![Build Status](http://162.211.230.155:8181/job/digitalpolice-java/badge/icon)](http://162.211.230.155:8181/job/digitalpolice-java/)

Проект Digital Police fo Lviv передбачає створення інтерактивної карти злочинності м. Львова, інструменти додавання шарів інформації, перегляд дільничих поліцейських на карті Львова та можливість подати електронне звернення через наш сайт про правопорушення. Львів стане першим містом, де буде створено і запущено наші сервіси. Детальніше про проект - https://goo.gl/nSGKpm

Digital Police API - репозиторій проекту, що надає REST сервіси які керують базою інцидентів/злочинів.

### З чого почати

#### Залежності

Java 1.7 або вище

Maven

#### Перед збіркою, тестуванням та запуском

Зкопіюйте код проекту на локальний компютер:

```
git clone https://github.com/digiU-DigitalPolice/digitalpolice-api.git
```

Перейдіть у папку 'digitalpolice-api'

```
cd digitalpolice-api
```

#### Як зібрати

```
mvn clean install -DskipTests
```

#### Як прогнати автоматичні тести

```
mvn test
```

#### Як запустити проект на локальному компютері

```
java -jar digitalpolice-api/target/digitalpolice-api-0.0.1-SNAPSHOT.jar
```

### REST документація

Актуальна REST документація доступна за [посиланням](http://162.211.230.155:8080/docs/index.html).

### Демо середовищ

Середовище на якому розгорнута остання робоча версія REST сервісів доступне за [посиланням](http://162.211.230.155:8080/).

### Безперервна інтеграція (Continuous Integration)

Ми використовуємо Jenkins CI для того щоб збирати та розгортати останню версію проекту. Jenkins UI доступне за  [посиланням](http://162.211.230.155:8181/job/digitalpolice-java).

### Завдання

Кожен бажаючий може створити завдання (task/user story) або зазвітувати дефект (bug/defect) у вигляді github issue, якщо він не повторює існуючий.

### Як долучитися

Будь ласка перечитайте [CONTRIBUTING.md](https://github.com/digiU-DigitalPolice/digitalpolice-api/blob/master/CONTRIBUTING.md), щоб дізнатися деталі того, як внести зміни до репозиторія.
