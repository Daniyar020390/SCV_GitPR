![Logo Git](Git-Logo-2Color.png)
# Работа с Git и GitHub
## 1. Проверка наличия установленного Git

В терминале выполнить команду __git version__
Если Git установлен появится сообщение с информацией о версии программы. Иначе будет сообщение об ошибке.
## 2. Установка Git
Загружаем последнюю версию Git c [сайта](https://git-scm.com/downloads). 
Устанавливаем с настройками по умолчанию.
## 3. Настройка Git
При первом использовании Git необходимо представиться.
Для этого нужно ввести в терминале 2 команды:
```
git config --global user.name «Ваше имя английскими буквами»
git config --global user.email ваша почта@example.com
```

## 4. Инициализация репозитория
Для того чтобы инциализировать репозиторий нужно набрать команду __git init__.

## 5. Запись изменений в репозиторий
Чтобы записать изменения в репозитории, необходимо ввести команды:
__git add "Название файла"__

После ввести команду: __git commit -m "Указать совершенное действие"__

## 6. Просмотр истории коммитов
Чтобы просмотреть историю коммитов нужно набрать команду: *__git log__*
## 7. Перемещение между сохранениями
Для перемещения между сохранениями нужно набрать команду: __git checkout "номер коммита"__.

Например: __git checkout 5cdc7a8__

## 8. Игнорирование файлов 
Для того чтобы исключить из отслеживания в репозитории определенные файлы или папки необходимо создать там файл ***.gitignore*** и записать в него их названия или шаблоны, соответствующие  таким файлам или папкам. 

## 9. Создание веток в Git
Создать ветку можно командой:
```
git branch <имя  для новой ветки>
```
Список веток в репозитории можно посмотреть с помощью команды:
```
git branch
```
текущая ветка будет отмечена звездочкой: __* *master*__


## 10. Слияние веток и разрешение конфликтов
Для слияния выбранной ветки с текущей нужно выполнить команду:
```
git merge <название выбранной ветки>
```

Если была изменена одна и та же часть файла в обеих ветках, то может возникнуть конфликт, который потребует участия пользователя. VSCode предлагает варианты разрешения.
## 11. Удаление веток
Чтобы удалить ветку нужно ввести команду: 
## git branch -d <название ветки> ##
__Принудительное удаление ветки:__
## git branch -D <название ветки> ##

#  *Работа с удаленными репозиториями*
1. Создать аккаунт на GitHub
2. Создать локальный репозиторий
3. Создать удаленный репозиторий 
4. Связать удаленный репозиторий с локальным

 Добавить удаленный репозиторий к проекту:
```
git remote add <имя для репозитория> <url адрес репозитория в сети>
```
```C#
while( n<0)
{
 n++;
}
```
Отправить изменения локального репозитория в удаленный:
```
git push
```
Посмотреть список удаленных репозиториев: 
***git remote***

# Репозиторий для **pull request**
* В своём аккаунте на GitHub создать копию репозитория **"AndreyBulgakov19/SCV_GitPR"** с помощью кнопки **"Fork"**.
---
* Клонировать копию репозитория на локальный компьютер.
---
* Создать новую ветку.
---
* Добавить файл с инструкцией в новую ветку.
---
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
---
* Зафиксировать изменения (коммиты).
---
* Отправить изменения на GitHub.
---
* На сайте GitHub выполнить **Pull request**.

Все
---
