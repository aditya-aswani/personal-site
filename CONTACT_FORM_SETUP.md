# Contact Form Setup Instructions

The contact form has been added to your contact page with the following fields:
- Name (required)
- Email (required) 
- Subject (required)
- Message (required)

## To Complete the Setup

1. **Sign up for Formspree** (free tier available):
   - Go to https://formspree.io
   - Create a free account
   - Create a new form

2. **Get your Formspree endpoint**:
   - After creating a form, you'll get an endpoint like: `https://formspree.io/f/YOUR_FORM_ID`

3. **Update the form action**:
   - Open `content/contact.md`
   - Replace `YOUR_FORM_ID` with your actual Formspree form ID
   - Example: Change `https://formspree.io/f/YOUR_FORM_ID` to `https://formspree.io/f/xeojvqpr`

4. **Configure Formspree settings** (optional):
   - In your Formspree dashboard, you can:
     - Set up email notifications to hello@adityaaswani.com
     - Add spam protection
     - Customize confirmation messages
     - Set up auto-responders

5. **Alternative services** (if you prefer):
   - **Netlify Forms**: If you host on Netlify
   - **EmailJS**: Client-side email service
   - **Basin**: Another form handling service

## Form Features Included

- ✅ All requested fields (name, email, subject, message)
- ✅ Proper validation and required fields
- ✅ Responsive design matching your site theme
- ✅ Success page redirect after submission
- ✅ Styled to match your existing design system
- ✅ Accessible form labels and structure

## Files Modified

- `content/contact.md` - Updated with new contact form
- `content/contact-success.md` - New success page
- `sass/_extra.scss` - Added form styling

The form will automatically send submissions to hello@adityaaswani.com once you complete the Formspree setup.