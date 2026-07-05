# CarouselForge — Go-Live Kit

## A. Deploy (3 minutes)
Option 1 (fastest): I drive your Chrome via the Claude extension and deploy for you — just say "deploy via my browser".
Option 2 (manual): 
1. Go to vercel.com → Add New → Project → choose "Deploy without Git" is not offered, so instead use app.netlify.com/drop
2. Drag the `carouselforge` folder onto the page. Done — you get a live URL instantly. Free forever at this traffic level.

## B. Razorpay (5 minutes, do once)
1. Dashboard → Payment Links → Create Payment Link
   - Amount: ₹199, Description: "CarouselForge Lifetime Pro"
   - Under "Redirect URL after payment" paste:
     https://YOUR-LIVE-URL/?unlock=CF-PRO-9V2K4
2. Copy the payment link (looks like https://rzp.io/l/xxxxx)
3. In index.html, line near top of the script, replace:
     const RAZORPAY_LINK = "https://rzp.io/l/REPLACE_ME";
   with your link, and redeploy (drag the folder again).

How it works: buyer pays → Razorpay redirects them back to your site with the
unlock code in the URL → Pro activates automatically on their device. The code
also appears to them if redirect fails: tell them to use code CF-PRO-9V2K4
(put it in the Razorpay receipt note field too).

## C. Launch posts (paste as-is, today)

### LinkedIn (post this from your profile)
I got tired of tools charging Rs 800/month to turn text into a carousel.

So I built CarouselForge. Paste your post, pick a style, download a
swipe-ready PDF in under 60 seconds.

Free to use. Rs 199 once — not per month — removes the watermark forever.

Made this carousel with it: [attach a PDF you export from the tool]

Try it: [YOUR-LIVE-URL]

### X / Twitter
Carousel tools: $19/month.
CarouselForge: Rs 199 once, forever.

Paste text → get a LinkedIn/Instagram carousel PDF in 60 seconds.
Free tier included → [YOUR-LIVE-URL]

### Reddit (r/SideProject, r/IndiaStartups, r/linkedin — adapt tone, be honest)
Title: I built a text-to-carousel tool because subscriptions for this felt absurd

Body: Every carousel maker I found wants $10-20/month for what is essentially
text layout. I made a free one — paste text, it splits into slides, you
download a PDF for LinkedIn or PNGs for Instagram. One-time Rs 199 (~$2.4)
removes the watermark, and that's the whole business model. Would love
feedback on the templates. [YOUR-LIVE-URL]

## D. First-dollar playbook (priority order)
1. Post the LinkedIn post above USING a carousel made by the tool (the product demos itself).
2. Reply to anyone on LinkedIn/X complaining about Canva/Taplio pricing with the link.
3. Reddit posts (space them out, 1/day, engage in comments).
4. WhatsApp: send to 10 friends who post on LinkedIn. Ask them to try it free.

Conversion math: watermark on free tier + Rs 199 impulse price. You need ONE
buyer. Typical tool-launch posts get 200-1000 visits; even 0.5% conversion = first sale.
