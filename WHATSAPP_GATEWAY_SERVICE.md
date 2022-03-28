# WhatsApp Gateway Service

---

### Validate Number is WhatsApp Account
[GET] => https://whatsapp-gateway.jefripunza.repl.co/api/whatsapp-gateway-service/v1/validate/isregistered/081329524389

---

### Send OTP
[GET] => https://whatsapp-gateway.jefripunza.repl.co/api/whatsapp-gateway-service/v1/message/otp/081329524389/BG123F

---

### Broadcast Message
[POST] => https://whatsapp-gateway.jefripunza.repl.co/api/whatsapp-gateway-service/v1/message/broadcast

[BODY] :
```json
{
  "message": "ini hanya testing, jangan hiraukan...",
  "targets": [
    "081329524389",
    "085643805670",
    "082387405917",
    "085156573257"
  ]
}
```

---
