# GoogleFruadDefensePhish

# GoogleFruadDefensePhish

In the near future, Google might train the world at large to scan QR codes to access websites. 

![[3_-_blog_-_qr_code.max-1900x1900.png]]

This repo contains a basic phishing landing page which mimics Googles QR pop-up to misdirect targets to an attacker controlled webpage. 

To use, simply edit this HTML section to contain your landing page and the QR code will automatically update. 

```
  <script>

    // ─────────────────────────────────────────────

    // EDIT THIS URL to change the QR code target:

    const QR_URL = "https://www.google.com/recaptcha/api2/demo";

    // ─────────────────────────────────────────────
```

More details can be found on Googles website: 

https://cloud.google.com/blog/products/identity-security/introducing-google-cloud-fraud-defense-the-next-evolution-of-recaptcha/


