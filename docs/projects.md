
# Проекти

# Нова версия на varnalab.org

- [varnalab.org](https://github.com/VarnaLab/varnalab.org)
  - Настоящата версия на сайта имплементирана с [node-organic](https://github.com/VarnaLab/node-organic)
- [varnalab-data](https://github.com/VarnaLab/varnalab-data)
  - Експорт на събитията и статиите публикувани на varnalab.org
  - Експорт на всички събития от Facebook групата и Facebook страницата
  - Данните са в JSON формат и могат да бъдат конвертирани към всяка една база данни
  - Експорт на финансовият отчет във CSV формат
- [open-data-explorer](https://github.com/VarnaLab/open-data-explorer) / [live](https://varnalab.github.io/open-data-explorer/)
  - Тестово приложение което консумира данните от [varnalab-data](https://github.com/VarnaLab/varnalab-data)
  - Представените данни са snapshot представляващ последният commit във [varnalab-data](https://github.com/VarnaLab/varnalab-data)
- [varnalab.org-generator](https://github.com/VarnaLab/varnalab.org-generator)
  - Целта на този проект е да генерира статично съдържание за новият сайт
  - Съдържанието ще бъде писано с Markdown
- varnalab.org-admin
  - Това ще бъде потребителски интерфейс от който могат да бъдат въвеждани статия и събития в базата
- [varnalab.org-storage](https://github.com/VarnaLab/varnalab.org-storage)
  - Примерен NodeJS сървър, който менажира новата база на сайта
  - Базата е SQLite
- [varnalab.org-notifier](https://github.com/VarnaLab/varnalab.org-notifier)
  - Ще бъде помощен скрипт, който ще се стартира с crontab и ще изпраща автоматизирани съобщения към социалните мрежи
- [website-new-design](https://github.com/VarnaLab/website-new-design)
  - Новият дизайн на varnalab.org

# Проекти отнасящи се до Slack

- [slack-incoming-facebook](https://github.com/VarnaLab/slack-incoming-facebook)
  - cronjob който проверява за нови съобщения във Facebook групата на VarnaLab и ги изпраща към Slack каналите: [varnalab.slack.com](https://varnalab.slack.com) и [itclubs.slack.com](https://itclubs.slack.com)
- [slack-incoming-twitter](https://github.com/VarnaLab/slack-incoming-twitter)
  - cronjob който проверява за нови съобщения в Twitter акаунта на VarnaLab и ги изпраща към Slack каналите: [varnalab.slack.com](https://varnalab.slack.com) и [itclubs.slack.com](https://itclubs.slack.com)
- [slack-incoming-trello](https://github.com/VarnaLab/slack-incoming-trello)
  - cronjob който проверява за нови съобщения в Trello организацията на VarnaLab и ги изпраща към Slack каналите: [varnalab.slack.com](https://varnalab.slack.com) и [itclubs.slack.com](https://itclubs.slack.com)
- [varnalab-whois](https://github.com/VarnaLab/varnalab-whois)
  - cronjob който проверява за свързаните машини в мрежата на VarnaLab
  - /whois командата се използва в Slack каналите: [varnalab.slack.com](https://varnalab.slack.com) и [itclubs.slack.com](https://itclubs.slack.com)
  - Командата работи в комбинация с [varnalab-cli](https://github.com/VarnaLab/varnalab-cli)
- [varnalab-server](https://github.com/VarnaLab/varnalab-server)
  - NodeJS сървър, който се използва за страниците за изпращане на покани [slack.varnalab.org](https://slack.varnalab.org/) и [github.varnalab.org](https://github.varnalab.org/)
  - Този сървър лесно може да бъде разширяван с допълнителни middlewares
- [varnalab-matrix](https://github.com/VarnaLab/varnalab-matrix)
  - Matrix анимацията за страниците с поканите

# Други

- [node-organic](https://github.com/VarnaLab/node-organic)
  - Organic Framework
- [varnalab-design](https://github.com/VarnaLab/varnalab-design)
  - Всички design файлове на VarnaLab
- [varnalab-cli](https://github.com/VarnaLab/varnalab-cli)
  - NodeJS CLI инструмент за менажиране на Mikrotik рутера в лаба
- [varnalab-finance](https://github.com/VarnaLab/varnalab-finance) / [live](https://varnalab.github.io/varnalab-finance/)
  - Финансови статистики за VarnaLab
  - Този модул консумира финансовите данни от [varnalab-data](https://github.com/VarnaLab/varnalab-data)
- [wiki](https://github.com/VarnaLab/wiki)
  - Това wiki, хостнато на https://varnalab.gitbooks.io/wiki/
