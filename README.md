# Born2BeRoot #

Резюме: этот документ представляет собой упражнение, связанное с системным администрированием.

# Содержание #

1. Преамбула
2. Вступление
3. Общие инструкции
4. Обязательная часть
5. Бонусная часть
6. Представление и Экспертная оценка

# Глава 1 #

## Преамбула ##

Ты можешь делать все, что хочешь. Виртуальная машина - это твой мир

![a](https://drive.google.com/file/d/196c3l3g5nATcx3yKwrwzvvHq8jCnoC_x/view?usp=sharing)

# Глава 2 #

## Вступление ##

Этот проект призван познакомить вас с чудесным миром виртуализации.

Вы создадите свою первую машину в VirtualBox (или UTM, если вы не можете использовать VirtualBox) в соответствии с конкретными инструкциями. Затем, в конце этого проекта, вы сможете настроить вашу собственная операционную системы с соблюдением строгих правил.

# Глава 3 #

## Общие инструкции ##

* Использование VirtualBox (или UTM, если вы не можете использовать VirtualBox) обязательно;
* Вам нужно только включить файл signature.txt в корень вашего репозитория. Вы должны вставить в него подпись виртуального диска вашей машины. Перейдите в раздел "Представление и экспертная оценка" для получения дополнительной информации.

# Глава 4 #

## Обязательная часть ##

Этот проект состоит из того, что вы настраиваете свой первый сервер, следуя определенным правилам.

> Поскольку речь идет о настройке сервера, вы установите минимум услуг. По этой причине графический интерфейс не имеет смысла. Поэтому запрещено устанавливать X.org или любой другой эквивалентный графический сервер. В противном случае ваша оценка будет 0.

Вы должны выбрать в качестве операционной системы либо последнюю стабильную версию Debian (no testing / unstable) или последней стабильной версии CentOS. Debian настоятельно рекомендуется если вы новичок в системном администрировании

> Настроить CentOS довольно сложно. Следовательно, вам не обязательнонастроить KDump. Однако SELinux должен быть запущен при запуске, а егоконфигурация должна быть адаптирована к потребностям проекта. AppArmorдля Debian также должен быть запущен при запуске

Вы должны создать как минимум 2 зашифрованных раздела с помощью LVM. Ниже приведен примерожидаемое разбиение: