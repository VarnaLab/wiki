
# Скриптове

Скрипт                    | Период         | Описание
:--                       | :--:           | :--
[varnalab-whois]          | 3мин           | Взима актуалните устройства/потребители в локалната мрежа на VarnaLab
[varnalab-static]         | 5мин           | Генерира цялото съдържание на varnalab.org под формата на HTML файлове
[slack-incoming-facebook] | 8мин           | Проверява за нови съобщения във Facebook групата на организацията и ги изпраща в #events канала на VarnaLab в Slack
[slack-incoming-twitter]  | 9мин           | Проверява за нови съобщения в Twitter акаунта на организацията и ги изпраща в #events канала на VarnaLab в Slack
[facebook-events-sync]    | 10мин (add)    | Проверява за нови събития във Facebook страницата и групата на организацията и ги добавя, ако се провеждат на физическият адрес на VarnaLab
[varnalab-notifier]       | 15мин          | Изпраща известия за нови Facebook събития (добавени чрез горният скрипт) към Google Calendar, Google Groups и Twitter акаунтите на организацията
[slack-incoming-trello]   | 15мин          | Проверява за нова активност в публичните бордове на VarnaLab в Trello и ги изпраща в #trello канала на VarnaLab в Slack
[facebook-events-sync]    | 30мин (update) | Проверява за промени по вече добавените Facebook събития
[varnalab-finance]        | всеки ден в 12:00 вечерта | Опреснява финансовата статистика за текущата година
[slack-incoming-quotes]   | Понеделник, Сряда, Петък 10:15 сутринта | Изпраща цитати в #spam канала на VarnaLab в Slack


  [varnalab-whois]: https://github.com/varnalab/varnalab-whois
  [varnalab-static]: https://github.com/varnalab/varnalab-static
  [varnalab-notifier]: https://github.com/varnalab/varnalab-notifier
  [varnalab-finance]: https://github.com/varnalab/varnalab-finance
  [facebook-events-sync]: https://github.com/varnalab/facebook-events-sync
  [slack-incoming-facebook]: https://github.com/varnalab/slack-incoming-facebook
  [slack-incoming-twitter]: https://github.com/varnalab/slack-incoming-twitter
  [slack-incoming-trello]: https://github.com/varnalab/slack-incoming-trello
  [slack-incoming-quotes]: https://github.com/simov/slack-incoming-quotes
