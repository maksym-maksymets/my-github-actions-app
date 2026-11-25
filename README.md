# my-github-actions-app

Лабораторна робота №6. Максимець Максим, П-31.

```bash
npm ci
npm test
npm start
```

Локальна адреса: http://localhost:3000/ . Відповідь: Hello World!

Workflow запускається для push і pull request до master, встановлює залежності,
кешує npm, виконує тест і збирає Docker-образ.

Для розгортання на Heroku потрібні створений застосунок зі стеком container,
тариф Heroku та GitHub Actions secrets HEROKU_API_KEY, HEROKU_EMAIL,
HEROKU_APP_NAME. Без цих налаштувань розгортання явно пропускається.
На момент виконання обліковий запис Heroku не надано, розгортання не виконано.
