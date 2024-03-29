## Анализ сделанных изменений 
---

Для просмотра информации о том, что конкретно было изменено используется команда:
 
`$ git diff`
  
Команда используется для получения ответов на два вопроса: 
1. Что изменили, но ещё не проиндексировали?
2. Что проиндексировали и собираемся включить в коммит?

Команда *git status* отвечает на эти вопросы в общем виде, перечисляя имена файлов, *git diff* показывает добавленные и удалённые строки.

Если надо посмотреть что уже проиндексировано и войдёт в следующий коммит, то выполняется команда:

`$ git diff --staged`
    
[Предыдущая](./gitwork.md) | [К содержанию](./readme.md) | [Следующая](./historycommit.md) |