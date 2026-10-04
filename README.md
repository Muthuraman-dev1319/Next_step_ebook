# Next Step — Mobile Responsive Demo

This is the Razorpay-free approval/demo version of the Next Step eBook store.

## Run on Windows
1. Open this folder in VS Code.
2. Open Terminal.
3. Run: `npm install`
4. Run: `npm start`
5. Open: `http://localhost:3000`

## Phone testing on the same Wi-Fi
- Find your laptop IPv4 address with `ipconfig`.
- On the phone, open `http://YOUR-LAPTOP-IP:3000`.
- Keep the laptop and phone on the same Wi-Fi.
- If Windows Firewall asks, allow Node.js on Private networks.

## Demo behavior
- Mobile-responsive layout keeps the same Next Step dark/blue visual style.
- All ebook covers are included and topic-specific.
- Add-to-cart opens a demo checkout only.
- No Razorpay and no real payment are enabled in this approval version.
- Demo order details are saved locally to `demo-orders.log` after a successful demo submission.
