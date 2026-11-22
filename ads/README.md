حبذا إبقاء الإعلانات معطلة حتى اعتماد المعلن. عدّل config.json للتحكم بمساحة الإعلان، دون إعادة بناء التطبيق.

```json
{
  "version": 1,
  "enabled": true,
  "campaign": {
    "id": "iraq-company-001",
    "title": "اسم الشركة",
    "text": "وصف الإعلان",
    "url": "https://example.com",
    "startsAt": "2026-11-22T00:00:00Z",
    "endsAt": "2026-12-22T00:00:00Z"
  }
}
```

Replace all example values before activation. Use a verified advertiser HTTPS page. Set enabled to false to pause. Dates are UTC. This file is public; never store tokens, payment credentials or user information here.
