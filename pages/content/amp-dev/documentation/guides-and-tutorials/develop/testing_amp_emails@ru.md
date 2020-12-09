---
"$title": Тестирование AMP-писем
"$order": '2'
"$category": Develop
description: Тестирование AMP-писем перед их рассылкой большой аудитории позволяет обеспечить оптимальный опыт взаимодействия.
formats:
- email
author: fstanis
---

Тестирование AMP-писем перед их рассылкой большой аудитории позволяет обеспечить оптимальный опыт взаимодействия.

## Контрольный список тестирования

1. Включите в AMP-письмо его HTML и/или текстовую версию — это послужит запасным вариантом для клиентов электронной почты, которые не поддерживают AMP.
2. Убедитесь, что ваш AMP корректно сформирован, выполнив шаги, описанные в разделе [Валидация AMP-писем](/content/amp-dev/documentation/guides-and-tutorials/learn/validation-workflow/validate_emails.md).
3. Перечитайте статью [Поддержка CSS в AMP для писем](/content/amp-dev/documentation/guides-and-tutorials/learn/email-spec/amp-email-css.md), чтобы убедиться, что используемый вами код CSS поддерживается всеми клиентами электронной почты.
4. Попробуйте просмотреть свое письмо в [Песочнице AMP](https://playground.amp.dev/?runtime=amp4email) и убедитесь, что все его динамические возможности (например, формы) работают корректно.

## Тестирование отдельных почтовых клиентов

Почтовые клиенты, поддерживающие AMP, также предоставляют документацию для разработчиков, которая может содержать дополнительные рекомендации и требования.

### Gmail

Документация Gmail содержит правила тестирования в статье [Тестирование ваших AMP-писем в Gmail](https://developers.google.com/gmail/ampemail/testing-dynamic-email).

Пользователи Gmail могут использовать песочницу [Gmail AMP for Email Playground](https://amp.gmail.dev/playground/), чтобы отправлять письма самим себе в целях тестирования.

### Mail.ru

В статье [AMP-письма в Mail.ru](https://postmaster.mail.ru/amp) приводится информация о том, как активировать тестирование в вашей учетной записи Mail.ru.

Пользователи Mail.ru могут использовать песочницу [Конструктор AMP-писем](https://postmaster.mail.ru/amp/playground.html), чтобы отправлять письма самим себе для тестирования.

### Outlook.com

В документации Outlook.com размещено руководство [Начало работы с AMP для писем](https://docs.microsoft.com/en-us/outlook/amphtml/get-started), в котором описывается, как создавать и тестировать AMP-письма.