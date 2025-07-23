
![Menu](https://github.com/Erfan-XRay/HPulse/blob/main/menu.png)

## What is FRPulse?
a secure , stable and fast direct tunnel based on [Hysteria](https://v2.hysteria.network/)(UDP/TCP).
## How to Run?
Run the following script on your server (Debian or Ubuntu):
```
bash <(curl -Ls https://raw.githubusercontent.com/Erfan-XRay/HPulse/main/HPulse.sh)
```
## How to use ?
[![Watch on YouTube](https://img.youtube.com/vi/mrXUkbtGxN0/0.jpg)](https://youtu.be/bbC_nseB2Bw?si=nZji-GRvXIOyXfGH)
# راهنمای جامع و حرفه‌ای راه‌اندازی تانل Hysteria با اسکریپت HPulse

این ریپازیتوری یک فورک از پروژه اصلی [Erfan-XRay/HPulse](https://github.com/Erfan-XRay/HPulse) است که با یک راهنمای کامل و قدم به قدم برای نصب، پیکربندی و درک مفاهیم غنی‌سازی شده است.

---

## 🎯 فصل ۱: آماده‌سازی و پیش‌نیازها

> **نکته کلیدی:** موفقیت‌آمیز بودن کل فرآیند به آماده‌سازی صحیح این مرحله بستگی دارد.

1.  **دو سرور مجازی (VPS):**
    * **سرور خارجی (Edge):** یک سرور خارج از ایران (مانند آلمان) با سیستم‌عامل **Ubuntu 22.04**.
    * **سرور داخلی (Gateway):** یک سرور داخل ایران با سیستم‌عامل **Ubuntu 22.04**.

2.  **یک دامنه (Domain):**
    * یک زیردامنه (مثلاً `tunnel.yourdomain.com`) بسازید.
    * در پنل **Cloudflare**، یک رکورد `A` ایجاد کنید که این زیردامنه را به **IP سرور خارجی** شما اشاره دهد.

> **⚠️ هشدار مهم:** پراکسی Cloudflare (ابر نارنجی 🟧) برای این رکورد باید **خاموش (DNS Only 🩶)** باشد تا گواهی SSL به درستی دریافت شود.

---

## 🚀 فصل ۲: نصب و اجرای اسکریپت HPulse

در **هر دو سرور** (داخلی و خارجی)، دستور زیر را برای دانلود و اجرای اسکریپت HPulse اجرا کنید.

```bash
bash <(curl -fsSL [https://raw.githubusercontent.com/Erfan-XRay/HPulse/main/HPulse.sh](https://raw.githubusercontent.com/Erfan-XRay/HPulse/main/HPulse.sh))
## ⚙️ Features
- Add, remove, and manage client/server services
- Support Ipv4/Ipv6
- Support TCP/UDP/Both
- Support Strict and SNI tunnel mode
- Obfs and Masquerade support
- Automated QUIC parameters
- Add and remove certificates ( Using Certbot )
- View logs of specific clients
- Interactive CLI with colorful UI
- Easy integration with Xray/V2Ray/Wireguard/etc.

### My social accounts

[![Telegram](https://img.shields.io/badge/Telegram--0088CC?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Erfan_XRay) 
[![YouTube](https://img.shields.io/badge/YouTube--FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Erfan_XRay/videos)

## Donation Link

<a href="https://nowpayments.io/donation?api_key=HHZTHS8-YC9MEHG-HTC73AH-5WVP950" target="_blank" rel="noreferrer noopener">
    <img src="https://nowpayments.io/images/embeds/donation-button-white.svg" alt="Cryptocurrency & Bitcoin donation button by NOWPayments">
</a>

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
