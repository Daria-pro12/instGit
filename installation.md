## Установка Git
---
Дистрибутивы и инструкции по установке для разных ОП [здесь](https://git-scm.com/downloads).

Установка Git отличается в разных операционных системах. 

### ***Установка Git в Ubuntu***

Ubuntu позволяет поставить Git с помощью команды в терминале:

`$ sudo apt install git`

### ***Установка Git в Windows***

GIT в Windows ставится через стандартные установщики (перейдите на [страницу](https://git-scm.com/download/win), скачайте подходящий дистрибутив и следуйте инструкциям). 

### ***Установка Git в MacOS***

Есть несколько вариантов установки Git на macOS. Вот некоторые из них:

```
# Установите homebrew, если у вас его еще нет 
$ brew install git

или

# Установите MacPorts, если у вас его еще нет
$ sudo port install git
```


### ***Базовая настройка Git***
После установки Git нужно зайти в терминал и проверить, что он работает:

`$ git --version`
   
Информация о версии Git

![Версия Git](./images/version.png)

 Глобальные настройки Git задаются командой


`$ git config --global parameter "value"`

Для начала нас интересуют только 2 настройки: имя и почта, под которыми нас будут видеть сам git и наши коллеги. Эти данные подставляются в историю изменений. Только так можно узнать, кто и что сделал в проекте:


```
$ git config --global user.name "Ваше имя фамилия"
$ git config --global user.email "Ваша почта"
```

Глобальные настройки задаются один раз и используются во всех проектах по умолчанию. Если для каких-то отдельных проектов вы хотите указать другое имя или электронную почту, можно выполнить эту же команду без параметра --global в каталоге с нужным проектом.

[Предыдущая](/history.md) | [К содержанию](./readme.md) | [Следующая](./repo.md) |