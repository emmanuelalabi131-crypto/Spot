SPOT TUTORIALS — STUDENT MANAGEMENT SYSTEM
============================================
Files in this package:
- index.html              ← Landing page (share this link with students)
- register.html           ← Student registration & payment
- portal.html             ← Student portal (login with ID number)
- admin-spot2026-secure.html ← Admin panel (keep this link private!)

SETUP STEPS:
1. Open admin-spot2026-secure.html → Settings
2. Enter your tutorial fees for each month
3. Enter your WhatsApp/Telegram group links
4. Change the admin password from SPOT2026 to something private

PAYSTACK:
- Open register.html in a text editor
- Find: pk_test_REPLACE_WITH_YOUR_PAYSTACK_PUBLIC_KEY
- Replace with your actual Paystack public key (pk_live_... or pk_test_...)

LOGO / PHOTOS:
- Logo is already embedded from your graduate.png file
- Slideshow: Open index.html, find SLIDE 1 through SLIDE 10
  Replace <div class="slide-placeholder"> sections with:
  <img src="your-photo.jpg" style="width:100%;height:100%;object-fit:cover;">

SUPABASE (ALREADY CONNECTED):
- URL: https://klrfpbwauxmbydizisoxf.supabase.co
- Tables needed: students + settings (see SPOT_Supabase_Table_Setup.docx)

GO LIVE (FREE):
1. Go to netlify.com → Sign up free
2. Drag and drop this entire folder
3. You get a live link instantly!
   e.g. https://spot-tutorials.netlify.app
4. Share index.html link with students
5. Keep admin-spot2026-secure.html link private

ADMIN DEFAULT PASSWORD: SPOT2026
Change it immediately in Settings after first login!
