# Contact Form Setup Instructions

Your contact form is now configured to send emails using **Web3Forms** - a free, reliable service.

## Steps to Activate:

### 1. Get Your Free Access Key
1. Visit: **https://web3forms.com**
2. Enter your email: **aawhanadhikari@gmail.com**
3. Click "Get Access Key"
4. Check your email for the access key (it's instant)

### 2. Add Access Key to Your Form
1. Open: `pages/contact.html`
2. Find this line (around line 51):
   ```html
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
   ```
3. Replace `YOUR_ACCESS_KEY_HERE` with your actual access key

### 3. Test Your Form
1. Open your website in a browser
2. Go to the Contact page
3. Fill out the form and submit
4. You should receive the message at **aawhanadhikari@gmail.com**

## Features Included:
✅ Spam protection (honeypot)
✅ Success/error messages
✅ Loading state on button
✅ Form validation
✅ Email notification to you
✅ Professional email formatting
✅ Mobile responsive

## Optional Customization:

### Change redirect page after submission:
In `contact.html`, modify:
```html
<input type="hidden" name="redirect" value="https://your-website.com/thank-you.html">
```

### Add CC/BCC emails:
```html
<input type="hidden" name="cc" value="another@email.com">
<input type="hidden" name="bcc" value="backup@email.com">
```

### Custom email template:
Visit https://web3forms.com/configure and customize your email template.

## Support:
- Web3Forms Documentation: https://docs.web3forms.com
- No backend server needed
- 100% Free forever
- Unlimited submissions

---

**Need help?** Just ask me to troubleshoot any issues!
