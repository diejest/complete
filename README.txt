
Щоб задеплоїти 1000 редіректів на Render.com:

1. Зайди в свій GitHub та створи новий репозиторій, наприклад: `redirect-mass`.
2. Завантаж в нього вміст цієї папки (файли з `public/` і `render.yaml`).
3. Зайди на https://render.com та створи новий Static Site, вибери цей репозиторій.
4. У полі `Build Command` нічого не пиши, а у `Publish directory` введи `public`.
5. Натисни Deploy.

Після цього редіректи будуть доступні за адресами:
https://your-render-subdomain.onrender.com/redirect_1.html
...
https://your-render-subdomain.onrender.com/redirect_1000.html
