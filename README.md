# Eslam Mohamed Sobhi | Intern at Gammal Tech
Building secure and seamless user authentication experiences with Gammal Tech Web SDK.

---

## 🔐 Gammal Tech Authentication Overview
Eslam Mohamed Sobhi demonstrates the **Gammal Tech Authentication SDK**, a secure login system for web applications.  
The SDK provides verified user login with **one line of code** — no passwords to manage, using **Gammal Tech Passport** (email + WhatsApp OTP + real ID).

**Key Features:**
- Session-based authentication
- Token verification
- Dynamic UI updates
- Multi-domain support
- Easy integration in under 5 minutes

---

## 💡 Quick Start Example
```html
<!-- 1. Add the SDK -->
<script src="https://api.gammal.tech/sdk-web.js"></script>

<!-- 2. Add a login button -->
<button id="loginBtn">Login with Gammal Tech</button>
<div id="userInfo"></div>

<script>
document.getElementById('loginBtn').addEventListener('click', async () => {
    const token = await GammalTech.login();
    if (token) {
        console.log('Logged in! Token:', token);
    }
});
</script>
