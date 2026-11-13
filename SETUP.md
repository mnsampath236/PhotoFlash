# Photo Flash website – setup

## How the quote form works
- As visitors fill the form, it saves automatically in their own browser. If they close the page or refresh, their details are still there when they come back.
- When they tap **Send on WhatsApp**, WhatsApp opens a chat with +91 63006 51422, with every detail already typed out (name, phone, function, venue, date, time, services, theme). They just tap Send.
- Once they submit, the saved draft is cleared.

There's no Google Sheet or server to set up.

## Put the site online
Upload `index.html` and the `img` folder together to any static host, such as Netlify (drag and drop the folder), GitHub Pages, Hostinger, or GoDaddy's file manager. Then connect your domain.

## Things to change later
- WhatsApp number: `WHATSAPP_NUMBER` near the bottom of `index.html` (country code + number, no + or spaces)
- Photos: replace the files in `img/`, keeping the same file names
