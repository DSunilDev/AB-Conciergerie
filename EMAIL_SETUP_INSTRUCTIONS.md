# Contact Form Setup Instructions

## Current Configuration

Your contact form is now configured with **Web3Forms**:
- **Access Key**: `8bac95ea-749a-494b-a2f8-ca327980b437`
- **Form Action**: `https://api.web3forms.com/submit`
- **Subject**: New Contact Form Submission from AB CONCIERGERIE

Web3Forms is a free, simple form service that sends form submissions directly to your email without requiring server-side code.

## How Web3Forms Works

1. **No Setup Required**: The form is already configured and ready to use!
2. **Automatic Email Delivery**: Form submissions are sent directly to the email address associated with your access key
3. **Free Tier**: 250 submissions per month for free
4. **No Server Needed**: Everything works client-side

## Form Fields

The contact form includes:
- **Name** (required)
- **Email** (required)
- **Phone** (required)
- **Message** (required)

## Testing

To test the form:
1. Fill out the contact form on your website
2. Submit it
3. Check your email inbox (the email associated with your Web3Forms access key)
4. You should receive the form submission!

## Managing Your Web3Forms Account

1. Go to https://web3forms.com/
2. Sign in with your account
3. View your access key dashboard
4. Check submission statistics
5. Configure email settings and notifications

## Troubleshooting

- **Form not submitting**: Check browser console (F12) for any errors
- **Not receiving emails**: 
  - Verify your access key is correct
  - Check spam/junk folder
  - Verify email address in Web3Forms dashboard
- **Validation errors**: Make sure all required fields are filled
- **Network errors**: Check your internet connection

## Need to Change the Access Key?

If you need to update the access key:
1. Get your new access key from https://web3forms.com/
2. Open `index.html`
3. Find the line: `<input type="hidden" name="access_key" value="8bac95ea-749a-494b-a2f8-ca327980b437">`
4. Replace the value with your new access key

## Form Features

- ✅ Client-side validation
- ✅ Success/error messages
- ✅ Form reset after successful submission
- ✅ Loading state during submission
- ✅ No page reload required
