# Easy Certbot Installation

Secure your websites with SSL/TLS certificates using Certbot effortlessly.

## 🚀 Installation

```bash
sudo apt update
sudo apt install certbot python3-certbot-nginx
```

## 🔐 Setting Up SSL Certificates

### For All Domains

```bash
sudo certbot --nginx -d example.com -d www.example.com
```

### For a Specific Subdomain

```bash
sudo certbot --nginx -d subdomain.example.com
```

## 🔄 Enable Automatic Certificate Renewal

```bash
sudo certbot renew --dry-run
```

## 📋 Check Existing Certificates

```bash
sudo certbot certificates
```

---

**Note:** Replace `example.com` and `subdomain.example.com` with your actual domain names.

