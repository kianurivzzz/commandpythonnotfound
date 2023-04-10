# Если не работает команда 'python3' или 'python' или 'py'

## Или 'pip'

![example error](img/error_2.png)

Начинающие разработчики часто встречаются с ошибкой говорящей о том, что команд 'python' или 'pip' не существует. Ниже расскажу о причинах возникновения этой ошибки и как её исправить.

## Почему возникает эта ошибка?

Причины возникновения две:

1. Python не установлен или работает некорректно;
2. Python при установке не был добавлен в PATH.

Если первая причина понятна, то вот вторая не совсем.

На вашем компьютере есть [переменные окружения](https://ru.wikipedia.org/wiki/%D0%9F%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%B0%D1%8F_%D1%81%D1%80%D0%B5%D0%B4%D1%8B). В них хранится разная служебная информация – например, данные о настройках. Одна из таких переменных окружения хранит в себе пути до исполняемых файлов. Нужна она для обращения к этим исполняемым файлам в терминале и дальнейшего запуска их функций. Называется такая переменная **PATH**.

Чаще всего все исполняемые файлы автоматически сохраняются в эту переменную. Но если этого не произошло,то оболочка терминала будет не в курсе о существовании этого инструмента.

В случае с Python это происходит по причине неправильной установки.

## Как исправить эту ошибку?

Ниже приведу примеры исправления разных ситуаций. Обращаю внимание, что в дальйнешем все команды будут указаны без символа разделителя $, так как в терминале он стоит в каждой строке.

### Python не установлен (Windows/MacOS/Linux)

Решение этой проблемы – установить Python.


Windows/MacOS no brew/Linux:


![Python Site](/img/python_site.png)

1. Перейдите на [официальный сайт](https://www.python.org/);
2. Наведите мышкой на вкладку Downloads;
3. Скачайте последнюю версию или выберите другую, но актуальную;
4. Запустите установочный файл.
5. Дождитесь установки и проверьте работу команд.

MacOS brew/Linux on terminal:

![Terminal](/img/install_py_on_brew.png)

1. В терминале напишите следующую команду:
```
# для brew в MacOS
brew install python3.11

# для Debian-подобных Linux систем
sudo apt-get install python3.11
```
2. Проверить работу команд Python.


