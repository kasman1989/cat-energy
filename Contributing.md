# Руководство по внесению изменений

Поддерживайте ваш репозиторий обновлённым. 

#### 1. Не коммитьте ничего самостоятельно в `master` вашего репозитория

Это помешает вам аккуратно обновлять ваш репозиторий, могут возникнуть конфликты.

#### 2. Прежде чем приступать к новому заданию, обновите `master`

Обновляйте ваш репозиторий перед работой:

```
# В вашей локальной копии переключитесь в ветку master
git checkout master

# Заберите изменения из репозитория на GitHub
git pull

```

```
# Когда вы обновили `master`, создайте ветку для нового задания:

git checkout -b module2-task1
```

`module2-task1` — это название ветки. Под описанием каждого задания в интерфейсе интенсива для вас будет указано правильное название ветки.

--

#### Есть вопрос?

Посмотрите [коллекцию часто задаваемых вопросов по Git](http://firstaidgit.ru).


