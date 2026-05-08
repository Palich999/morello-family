MORELLO FAMILY SITE

1) Залей index.html и папку assets в GitHub Pages.
2) В Cloudflare Worker замени код на worker.js.
3) В Variables/Secrets должен быть секрет DISCORD_WEBHOOK с новой webhook-ссылкой Discord.
4) После Deploy форма будет отправлять заявки и скриншоты в Discord.

Важно: старый webhook, который был отправлен в чат, лучше сбросить в Discord и добавить новый в Cloudflare Secret.
