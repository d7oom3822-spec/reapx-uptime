# ReapX · المراقبة

فحص كل ٥ دقائق من خارج Cloudflare (GitHub Actions في مستودع عامّ · مجاني بلا حدّ للدقائق):

| الفحص | الرابط | المطلوب |
|---|---|---|
| الخدمة + الدورة الخلفية | https://reapx.thetasterspage.workers.dev/health?strict=1 | 200 و `"ok":true` |
| لوحة المالك | https://reapx-panel.pages.dev/login.html | 200 |
| صفحة الزبون | https://reapx-qr.pages.dev/pager | 200 |
| تطبيق الشاشة | https://reapx-app.pages.dev/ | 200 |

عند السقوط يصل بريد «Run failed» من GitHub. لا أسرار في هذا المستودع.
