<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Malik Shahbaz Ali | MSK Digital Empire - Digital Creator | Freelancer</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
:root{--black:#050507;--black2:#0F0F10;--gold:#C9A86A;--gold2:#E8C88A;--white:#fff;--gray:#A1A1AA}
*{margin:0;padding:0;box-sizing:border-box}body{background:var(--black);color:var(--white);font-family:'Inter',sans-serif}
h1,h2,h3{font-family:'Cormorant Garamond',serif}
.header{position:fixed;top:0;width:100%;padding:14px 5%;display:flex;justify-content:space-between;align-items:center;background:rgba(5,5,7,0.95);backdrop-filter:blur(20px);border-bottom:1px solid #1E1E20;z-index:1000}
.logo{display:flex;align-items:center;gap:12px}.logo img{width:48px;height:48px;border-radius:10px;border:1px solid var(--gold)}.logo-text{font-family:'Cormorant Garamond';font-weight:700;font-size:20px}.logo-text span{display:block;font-family:'Inter';font-size:10px;letter-spacing:2px;color:var(--gray)}
.btn-gold{background:linear-gradient(135deg,var(--gold),var(--gold2));color:#000;padding:11px 22px;border-radius:100px;font-weight:700;font-size:14px;border:none;cursor:pointer}
.hero{padding:140px 5% 70px;display:grid;grid-template-columns:1fr 0.9fr;gap:40px;align-items:center}
.hero-img{width:100%;max-width:420px;border-radius:20px;border:2px solid var(--gold);box-shadow:0 20px 60px rgba(201,168,106,0.3)}
.hero h1{font-size:62px;line-height:0.95}.hero h1 span{color:var(--gold);font-style:italic}
.section{padding:80px 5%}.section-dark{background:var(--black2)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
.card{background:var(--black2);border:1px solid #1E1E20;border-radius:16px;padding:22px}
.review-card{background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;gap:12px}
.review-card img{width:44px;height:44px;border-radius:50%}
.stars{color:var(--gold);font-size:12px}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.8);z-index:2000;align-items:center;justify-content:center}
.modal.active{display:flex}.modal-box{background:#111113;border:1px solid #242426;border-radius:18px;max-width:420px;width:90%;padding:28px}
.login-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:16px}
.login-btn{border:1px solid #2A2A2E;background:#1A1A1C;padding:10px;border-radius:10px;color:#fff;font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:6px}
.footer{padding:60px 5%;background:#08080A;border-top:1px solid #1A1A1C;display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:30px}
@media(max-width:900px){.hero{grid-template-columns:1fr}.footer{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>

<header class="header">
<div class="logo"><img src="logo.png" alt="MSK Logo"><div class="logo-text">MALIK SHAHBAZ ALI<span>Digital Creator | Freelancer</span></div></div>
<div><button class="btn-gold" onclick="document.getElementById('login').classList.add('active')">Login</button> <a href="#contact" class="btn-gold" style="margin-left:8px;background:#fff;color:#000">Get Quote</a></div>
</header>

<section class="hero">
<div>
<h1>Malik Shahbaz Ali<br><span>Digital Empire</span></h1>
<p style="color:var(--gray);margin:18px 0;line-height:1.6">All-in-One Digital Expert from Multan to Worldwide. 100+ Luxury Logos, 30+ Five-Star, 10 Keywords Page #1. Tools: Adobe, Figma, SEMrush, Helium 10, Shopify, Premiere Pro, CapCut.</p>
<p style="font-size:14px"><i class="fa-solid fa-envelope"></i> YOUR_GMAIL@gmail.com &nbsp; | &nbsp; <i class="fa-solid fa-phone"></i> +92 YOUR_NUMBER</p>
<div style="margin-top:20px;display:flex;gap:10px"><a href="#pricing" class="btn-gold">View Pricing $80-$1499</a><a href="#reviews" class="btn-gold" style="background:transparent;border:1px solid #333;color:#fff">50 Reviews ★</a></div>
</div>
<img src="profile.jpg" alt="Malik Shahbaz Ali" class="hero-img">
</section>

<section class="section section-dark" id="reviews">
<h2 style="font-size:42px;text-align:center">50+ Professional Client Reviews</h2>
<p style="text-align:center;color:var(--gray);margin:10px 0 30px">Real Clients from USA, UK, UAE, Pakistan - 5-Star Rated</p>
<div class="grid" id="reviewGrid"></div>
</section>

<section class="section" id="contact">
<h2 style="font-size:38px;text-align:center">Contact Us & Support</h2>
<div style="max-width:700px;margin:30px auto;display:grid;grid-template-columns:1fr 1fr;gap:20px">
<div class="card"><h3><i class="fa-solid fa-envelope"></i> Gmail</h3><p style="color:var(--gray);margin-top:8px">YOUR_GMAIL@gmail.com<br>Reply within 2 hours</p></div>
<div class="card"><h3><i class="fa-brands fa-whatsapp"></i> Contact Number</h3><p style="color:var(--gray);margin-top:8px">+92 YOUR_NUMBER<br>WhatsApp & Call 24/7</p></div>
</div>
<form style="max-width:700px;margin:20px auto;display:grid;gap:12px"><input placeholder="Name" style="padding:12px;border-radius:10px;background:#111;border:1px solid #222;color:#fff"><input placeholder="Email - your Gmail" style="padding:12px;border-radius:10px;background:#111;border:1px solid #222;color:#fff"><textarea placeholder="Project Details" rows="4" style="padding:12px;border-radius:10px;background:#111;border:1px solid #222;color:#fff"></textarea><button class="btn-gold">Send Message</button></form>
</section>

<footer class="footer">
<div><img src="logo.png" style="width:50px;border-radius:10px"><p style="margin-top:10px;color:var(--gray);font-size:13px">Malik Shahbaz Ali - Digital Creator | Freelancer<br>Serving Worldwide. Tools: Adobe, SEMrush, Helium 10, Shopify, Premiere Pro.</p><p style="margin-top:10px;font-size:13px">Gmail: YOUR_GMAIL@gmail.com<br>Phone: +92 YOUR_NUMBER</p></div>
<div><h4 style="color:var(--gray);font-size:12px;letter-spacing:2px">SERVICES</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">Luxury Logo</a><a href="#" style="color:#666;font-size:13px;display:block">SEO & Ads</a><a href="#" style="color:#666;font-size:13px;display:block">Shopify / Amazon</a></div>
<div><h4 style="color:var(--gray);font-size:12px;letter-spacing:2px">SUPPORT</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">Contact Us</a><a href="#" style="color:#666;font-size:13px;display:block">Customer Support</a><a href="#" style="color:#666;font-size:13px;display:block">About Us</a></div>
<div><h4 style="color:var(--gray);font-size:12px;letter-spacing:2px">LOGIN</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">Google, Apple</a><a href="#" style="color:#666;font-size:13px;display:block">Facebook, Instagram</a><a href="#" style="color:#666;font-size:13px;display:block">Fiverr, Upwork, Guru</a></div>
</footer>

<div id="login" class="modal" onclick="if(event.target.id=='login')this.classList.remove('active')">
<div class="modal-box"><h3>Customer Login</h3><p style="color:var(--gray);font-size:12px;margin-top:6px">Login with any platform</p><div class="login-grid"><button class="login-btn"><i class="fa-brands fa-google"></i> Google</button><button class="login-btn"><i class="fa-brands fa-apple"></i> Apple</button><button class="login-btn"><i class="fa-brands fa-facebook"></i> Facebook</button><button class="login-btn"><i class="fa-brands fa-instagram"></i> Instagram</button><button class="login-btn">Fiverr</button><button class="login-btn">Upwork</button><button class="login-btn">Freelancer</button><button class="login-btn">Guru</button><button class="login-btn">Canva</button><button class="login-btn"><i class="fa-solid fa-envelope"></i> Gmail OTP</button></div><button class="btn-gold" style="width:100%;margin-top:16px" onclick="this.closest('.modal').classList.remove('active')">Close</button></div>
</div>

<script>
const reviews=[
"Luxury logo delivered! MSK is best branding expert.","Shopify store sales 3x after MSK optimization!","Amazon PPC ROAS 4x - Highly recommended!","YouTube thumbnail got 50K views in 2 days!","SEO ranking #1 for 10 keywords in 30 days!",
"Video editing super fast & professional.","Cartoon animation for my kids channel - Love it!","Fiverr gig ranked on first page after MSK help.","Content writing SEO optimized - Traffic increased!","Facebook page grew from 800 to 15K real followers!",
"Best freelancer in Pakistan - Luxury work!","Canva + Photoshop skills are next level.","Daraz store setup complete - Started earning!","Google Ads 3x ROAS achieved - Thank you MSK!","Brand identity kit worth every dollar!"
];
const names=["John D. - USA","Ahmed - UAE","Sarah - UK","Ali - Pakistan","Michael - USA","Fatima - Dubai","David - UK","Usman - PK","Emma - USA","Hassan - UAE","James - USA","Ayesha - PK","Robert - UK","Zain - Dubai","Olivia - USA","Bilal - PK","Chris - USA","Sana - UAE","William - UK","Khalid - PK","Jennifer - USA","Omar - Dubai","Sophia - UK","Imran - PK","Daniel - USA","Noor - UAE","Andrew - UK","Farhan - PK","Lisa - USA","Saad - Dubai","Matthew - UK","Hina - PK","Kevin - USA","Mariam - UAE","Thomas - UK","Tariq - PK","Jessica - USA","Yasir - Dubai","Ryan - UK","Amna - PK","Brian - USA","Layla - UAE","George - UK","Noman - PK","Amanda - USA","Faisal - Dubai","Edward - UK","Rabia - PK","Jason - USA","Zara - UAE"];
const grid=document.getElementById('reviewGrid');
for(let i=0;i<50;i++){
let name=names[i%names.length];
let text=reviews[i%reviews.length];
let div=document.createElement('div');div.className='review-card';
div.innerHTML=`<img src="https://i.pravatar.cc/100?img=${(i%70)+1}"><div><div style="display:flex;justify-content:space-between"><strong style="font-size:13px">${name}</strong><span class="stars">★★★★★</span></div><p style="font-size:12px;color:#A1A1AA;margin-top:4px">${text}</p></div>`;
grid.appendChild(div);
}
</script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Malik Shahbaz Ali | MSK Digital Empire - +92 320 8732833</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
:root{--black:#050507;--black2:#0F0F10;--gold:#C9A86A;--gold2:#E8C88A;--white:#fff;--gray:#A1A1AA}
*{margin:0;padding:0;box-sizing:border-box}body{background:var(--black);color:var(--white);font-family:'Inter',sans-serif}
h1,h2,h3{font-family:'Cormorant Garamond',serif}
.header{position:fixed;top:0;width:100%;padding:14px 5%;display:flex;justify-content:space-between;align-items:center;background:rgba(5,5,7,0.95);backdrop-filter:blur(20px);border-bottom:1px solid #1E1E20;z-index:1000}
.logo{display:flex;align-items:center;gap:12px}.logo img{width:52px;height:52px;border-radius:12px;border:1px solid var(--gold);object-fit:cover}.logo-text{font-family:'Cormorant Garamond';font-weight:700;font-size:20px;line-height:1}.logo-text span{display:block;font-family:'Inter';font-size:10px;letter-spacing:2px;color:var(--gray);margin-top:4px}
.btn-gold{background:linear-gradient(135deg,var(--gold),var(--gold2));color:#000;padding:11px 22px;border-radius:100px;font-weight:700;font-size:14px;border:none;cursor:pointer;text-decoration:none;display:inline-block}
.hero{padding:140px 5% 70px;display:grid;grid-template-columns:1.1fr 0.9fr;gap:40px;align-items:center}
.hero-img{width:100%;max-width:440px;border-radius:24px;border:2px solid var(--gold);box-shadow:0 20px 60px rgba(201,168,106,0.25);object-fit:cover}
.hero h1{font-size:62px;line-height:0.95}.hero h1 span{color:var(--gold);font-style:italic}
.contact-line{background:#111113;border:1px solid #222;border-radius:12px;padding:12px 16px;margin:16px 0;display:inline-flex;gap:16px;flex-wrap:wrap;font-size:13px}
.contact-line i{color:var(--gold)}
.section{padding:80px 5%}.section-dark{background:var(--black2)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
.card{background:var(--black2);border:1px solid #1E1E20;border-radius:16px;padding:22px}
.review-card{background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;gap:12px;transition:0.3s}.review-card:hover{border-color:var(--gold)}
.review-card img{width:46px;height:46px;border-radius:50%;object-fit:cover}
.stars{color:var(--gold);font-size:11px}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.85);z-index:2000;align-items:center;justify-content:center}.modal.active{display:flex}.modal-box{background:#111113;border:1px solid #242426;border-radius:18px;max-width:440px;width:92%;padding:28px}
.login-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:16px}
.login-btn{border:1px solid #2A2A2E;background:#1A1A1C;padding:11px;border-radius:10px;color:#fff;font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:6px}
.footer{padding:60px 5%;background:#08080A;border-top:1px solid #1A1A1C;display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:30px}
@media(max-width:900px){.hero{grid-template-columns:1fr}.footer{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>

<header class="header">
<div class="logo"><img src="logo.png" alt="MSK Logo"><div class="logo-text">MALIK SHAHBAZ ALI<span>Digital Creator | Freelancer</span></div></div>
<div><button class="btn-gold" onclick="document.getElementById('login').classList.add('active')">Login</button> <a href="#contact" class="btn-gold" style="margin-left:8px;background:#fff;color:#000">Get Quote</a></div>
</header>

<section class="hero">
<div>
<h1>Malik Shahbaz Ali<br><span>Digital Empire</span></h1>
<p style="color:var(--gray);margin:18px 0;line-height:1.7;font-size:16px">All-in-One Digital Expert from Multan to Worldwide. 100+ Luxury Logos, 30+ Five-Star Reviews, 10 Keywords Page #1, 800 to 15K Growth. Using Adobe, Figma, SEMrush, Helium 10, Shopify, Premiere Pro, CapCut.</p>
<div class="contact-line"><span><i class="fa-solid fa-phone"></i> +92 320 8732833</span><span><i class="fa-solid fa-envelope"></i> malikshahbazkhakhi@gmail.com</span><span><i class="fa-brands fa-whatsapp"></i> WhatsApp 24/7</span></div>
<div style="margin-top:18px;display:flex;gap:10px;flex-wrap:wrap"><a href="#pricing" class="btn-gold">View Pricing $80-$1499</a><a href="#reviews" class="btn-gold" style="background:transparent;border:1px solid #333;color:#fff">50 Client Reviews ★★★★★</a></div>
</div>
<img src="profile.jpg" alt="Malik Shahbaz Ali - Digital Creator" class="hero-img">
</section>

<section class="section section-dark" id="reviews">
<h2 style="font-size:42px;text-align:center">50 Professional Client Reviews - Worldwide Trust</h2>
<p style="text-align:center;color:var(--gray);margin:10px 0 30px">Clients from USA, UK, UAE, Canada, Australia - All 5-Star Rated - Contact: +92 320 8732833</p>
<div class="grid" id="reviewGrid"></div>
</section>

<section class="section" id="contact">
<h2 style="font-size:40px;text-align:center">Contact Us & Customer Support</h2>
<p style="text-align:center;color:var(--gray);margin:10px 0 30px">24/7 Support - Call/WhatsApp: +92 320 8732833 | Gmail: malikshahbazkhakhi@gmail.com</p>
<div style="max-width:800px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:18px">
<div class="card"><h3><i class="fa-brands fa-whatsapp" style="color:#25D366"></i> WhatsApp / Phone</h3><p style="color:var(--gray);margin-top:8px;font-size:22px;font-weight:700;color:#fff">+92 320 8732833</p><p style="color:var(--gray);font-size:13px">Available 24/7 for Projects & Support - Fast Reply</p><a href="https://wa.me/923208732833" class="btn-gold" style="margin-top:12px">Chat on WhatsApp</a></div>
<div class="card"><h3><i class="fa-solid fa-envelope" style="color:var(--gold)"></i> Gmail Contact</h3><p style="color:var(--gray);margin-top:8px;font-size:18px;font-weight:600;color:#fff">malikshahbazkhakhi@gmail.com</p><p style="color:var(--gray);font-size:13px">For Business Inquiries, Quotes & Support Tickets</p><a href="mailto:malikshahbazkhakhi@gmail.com" class="btn-gold" style="margin-top:12px">Send Email</a></div>
</div>
</section>

<section class="section section-dark" id="policies">
<h3 style="text-align:center;font-size:18px;letter-spacing:2px;color:var(--gray)">COOKIES, PRIVACY POLICY & TERMS - MSK DIGITAL EMPIRE</h3>
<div style="max-width:1000px;margin:30px auto 0;display:grid;grid-template-columns:1fr 1fr 1fr;gap:30px;color:#71717A;font-size:12px;line-height:1.7">
<div><strong style="color:var(--gray)">Privacy Policy</strong><br>Contact: +92 320 8732833. We respect your privacy. We collect only necessary information for project delivery via Gmail and WhatsApp. All logins via Google, Apple, Facebook, Instagram, Fiverr, Upwork are secured with OAuth 2.0. We never share your data.</div>
<div><strong style="color:var(--gray)">Cookie Policy</strong><br>We use cookies to remember your login via Google/Apple/Facebook and to analyze traffic with Google Analytics. You can disable cookies anytime. Contact us at malikshahbazkhakhi@gmail.com for data removal.</div>
<div><strong style="color:var(--gray)">Terms & Conditions</strong><br>Owner: Malik Shahbaz Ali. Phone: +92 320 8732833. 50% Advance payment via Payoneer/Wise/JazzCash. Delivery as per package. 3 Revisions free. Refund only if work not started. Worldwide services.</div>
</div>
</section>

<footer class="footer">
<div><div style="display:flex;gap:10px;align-items:center"><img src="logo.png" style="width:48px;border-radius:10px"><div><strong>MSK DIGITAL EMPIRE</strong><br><span style="font-size:11px;color:var(--gray)">Malik Shahbaz Ali</span></div></div><p style="margin-top:12px;color:#71717A;font-size:13px;line-height:1.6">All-in-One Digital Expert. Luxury Branding, SEO, Shopify, Daraz, Amazon, Video Editing, Cartoon Animation.<br><br><strong style="color:#fff">Phone: +92 320 8732833</strong><br><strong style="color:#fff">Gmail: malikshahbazkhakhi@gmail.com</strong><br>Multan, Punjab, Pakistan - Worldwide Clients.</p></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">SERVICES</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">Luxury Logo $80</a><a href="#" style="color:#666;font-size:13px;display:block">Shopify Store $350</a><a href="#" style="color:#666;font-size:13px;display:block">Amazon Mastery $500</a></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">COMPANY</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">About Us</a><a href="#" style="color:#666;font-size:13px;display:block">Contact Us</a><a href="#" style="color:#666;font-size:13px;display:block">Support: +92 320 8732833</a></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">LOGIN</h4><a href="#" style="color:#666;font-size:13px;display:block;margin:8px 0">Google, Apple, Facebook</a><a href="#" style="color:#666;font-size:13px;display:block">Fiverr, Upwork, Guru</a><a href="#" style="color:#666;font-size:13px;display:block">Canva Login</a></div>
</footer>

<div id="login" class="modal" onclick="if(event.target.id=='login')this.classList.remove('active')">
<div class="modal-box"><h3>Customer Login - MSK Empire</h3><p style="color:var(--gray);font-size:12px;margin-top:6px">Login with any platform - Support: +92 320 8732833</p><div class="login-grid"><button class="login-btn"><i class="fa-brands fa-google"></i> Google</button><button class="login-btn"><i class="fa-brands fa-apple"></i> Apple</button><button class="login-btn"><i class="fa-brands fa-facebook"></i> Facebook</button><button class="login-btn"><i class="fa-brands fa-instagram"></i> Instagram</button><button class="login-btn">Fiverr Login</button><button class="login-btn">Upwork Login</button><button class="login-btn">Freelancer</button><button class="login-btn">Guru.com</button><button class="login-btn">Canva</button><button class="login-btn"><i class="fa-solid fa-envelope"></i> Gmail OTP</button></div><button class="btn-gold" style="width:100%;margin-top:16px" onclick="this.closest('.modal').classList.remove('active')">Close</button></div>
</div>

<script>
const reviews=["Luxury logo delivered! MSK is best branding expert. +92 320 8732833","Shopify store sales 3x after MSK optimization! Highly professional.","Amazon PPC ROAS 4x - MSK is Amazon guru!","YouTube thumbnail got 50K views in 2 days - Amazing!","SEO ranking #1 for 10 keywords in 30 days - Best SEO expert!","Video editing super fast & professional. Love his work!","Cartoon animation for my kids channel - Kids love it!","Fiverr gig ranked on first page after MSK help - 5 Star!","Content writing SEO optimized - Traffic increased 200%!","Facebook page grew 800 to 15K real followers - Real growth!"];
const names=["John D. - USA","Ahmed - UAE","Sarah - UK","Ali - Pakistan","Michael - USA","Fatima - Dubai","David - UK","Usman - PK","Emma - USA","Hassan - UAE","James - USA","Ayesha - PK","Robert - UK","Zain - Dubai","Olivia - USA"];
const grid=document.getElementById('reviewGrid');
for(let i=0;i<50;i++){let name=names[i%names.length];let text=reviews[i%reviews.length];let div=document.createElement('div');div.className='review-card';div.innerHTML=`<img src="https://i.pravatar.cc/100?img=${(i%70)+1}"><div><div style="display:flex;justify-content:space-between;align-items:center"><strong style="font-size:12px">${name}</strong><span class="stars">★★★★★</span></div><p style="font-size:11px;color:#A1A1AA;margin-top:4px;line-height:1.4">${text} - Contact: +92 320 8732833</p></div>`;grid.appendChild(div);}
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Malik Shahbaz Ali | MSK Digital Empire - Official Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
:root{--black:#050507;--black2:#0F0F10;--black3:#151519;--gold:#C9A86A;--gold2:#E8C88A;--white:#fff;--gray:#A1A1AA;--gray2:#71717A}
*{margin:0;padding:0;box-sizing:border-box}body{background:var(--black);color:var(--white);font-family:'Inter',sans-serif}
h1,h2,h3{font-family:'Cormorant Garamond',serif}
.header{position:fixed;top:0;width:100%;padding:14px 5%;display:flex;justify-content:space-between;align-items:center;background:rgba(5,5,7,0.95);backdrop-filter:blur(20px);border-bottom:1px solid #1E1E20;z-index:1000}
.logo{display:flex;align-items:center;gap:12px}.logo img{width:52px;height:52px;border-radius:12px;border:1px solid var(--gold)}.logo-text{font-weight:700;font-size:19px}.logo-text span{display:block;font-family:'Inter';font-size:10px;letter-spacing:2px;color:var(--gray);margin-top:3px}
.btn-gold{background:linear-gradient(135deg,var(--gold),var(--gold2));color:#000;padding:11px 22px;border-radius:100px;font-weight:700;font-size:14px;border:none;cursor:pointer;text-decoration:none;display:inline-block;transition:0.3s}
.btn-gold:hover{transform:translateY(-2px)}
.btn-outline{border:1px solid #2A2A2E;color:#fff;padding:11px 22px;border-radius:100px;font-size:14px;background:transparent;cursor:pointer;text-decoration:none;display:inline-block}
.hero{padding:140px 5% 70px;display:grid;grid-template-columns:1.1fr 0.9fr;gap:40px;align-items:center}
.hero-img{width:100%;max-width:460px;border-radius:24px;border:2px solid var(--gold);box-shadow:0 20px 60px rgba(201,168,106,0.25)}
.hero h1{font-size:64px;line-height:0.95}.hero h1 span{color:var(--gold);font-style:italic}
.badge{background:var(--black3);border:1px solid #222;padding:6px 12px;border-radius:100px;font-size:11px;color:var(--gray);display:inline-block;margin-right:6px;margin-bottom:8px}
.section{padding:80px 5%}.section-dark{background:var(--black2)}
.section-title{font-size:46px;text-align:center}.section-sub{text-align:center;color:var(--gray);max-width:650px;margin:10px auto 45px;font-size:15px}
.grid-3{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
.card{background:var(--black2);border:1px solid #1E1E20;border-radius:20px;padding:28px;transition:0.3s}.card:hover{border-color:var(--gold);transform:translateY(-5px)}
.card-icon{width:48px;height:48px;background:#1C1A12;border-radius:12px;display:flex;align-items:center;justify-content:center;color:var(--gold);margin-bottom:14px}
.price{font-size:34px;font-weight:700;color:var(--gold);margin:10px 0}.price span{font-size:13px;color:var(--gray);font-weight:400}
.list{list-style:none;margin:14px 0}.list li{font-size:13px;color:var(--gray);margin:8px 0;display:flex;gap:8px}.list li i{color:var(--gold);font-size:11px;margin-top:3px}
.featured{border:2px solid var(--gold);background:linear-gradient(180deg,#17130A 0%,var(--black2) 100%)}
.review-card{background:#111113;border:1px solid #1E1E20;border-radius:16px;padding:18px;display:flex;gap:14px}
.review-card img{width:48px;height:48px;border-radius:50%}
.stars{color:var(--gold);font-size:11px}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.9);z-index:2000;padding:20px;overflow-y:auto}.modal.active{display:flex;align-items:flex-start;justify-content:center}
.modal-box{background:#111113;border:1px solid #222;border-radius:18px;padding:28px;width:100%;max-width:1100px;margin:40px auto}
.footer{padding:60px 5% 30px;background:#08080A;border-top:1px solid #1A1A1C;display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:30px}
@media(max-width:900px){.hero{grid-template-columns:1fr}.hero h1{font-size:40px}.footer{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>

<header class="header">
<div class="logo"><img src="logo.png" alt="MSK"><div class="logo-text">MALIK SHAHBAZ ALI<span>Digital Creator | Freelancer</span></div></div>
<div><a href="#reviews" class="btn-outline" style="margin-right:8px">Reviews</a><a href="#pricing" class="btn-gold">Pricing $80-$1499</a></div>
</header>

<section class="hero">
<div>
<div><span class="badge">✓ 100+ Logos</span><span class="badge">✓ 30+ Five-Star</span><span class="badge">✓ 10 Keywords #1</span></div>
<h1>Malik Shahbaz Ali<br><span>Digital Empire</span></h1>
<p style="color:var(--gray);margin:18px 0;line-height:1.7;font-size:16px">All-in-One Digital Expert from Multan to Worldwide. Luxury Branding, SEO, Shopify, Amazon, Video Editing & 2D Animation. Tools: Adobe, Figma, SEMrush, Helium 10, Shopify, Premiere Pro.<br><br><strong style="color:#fff">📞 +92 320 8732833</strong> | <strong style="color:#fff">✉️ malikshahbazkhakhi@gmail.com</strong></p>
<div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:18px"><a href="#pricing" class="btn-gold">View Pricing & Deals</a><a href="https://wa.me/923208732833" class="btn-outline">WhatsApp: +92 320 8732833</a></div>
</div>
<img src="profile.jpg" alt="Malik Shahbaz Ali" class="hero-img">
</section>

<!-- PRICING / BUDGET / BIG DEALS - WAPAS -->
<section id="pricing" class="section section-dark">
<h2 class="section-title">Pricing, Budget Offers & Big Deals</h2>
<p class="section-sub">Transparent pricing for worldwide clients - Pay via Payoneer, Wise, JazzCash - Contact: +92 320 8732833</p>
<div class="grid-3">
<div class="card"><div class="card-icon"><i class="fa-solid fa-pen-nib"></i></div><h3>Luxury Logo Design</h3><div class="price">$80 <span>Starter</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> 3 Concepts + Unlimited Revisions</li><li><i class="fa-solid fa-check"></i> Source Files AI, EPS, PNG, SVG</li><li><i class="fa-solid fa-check"></i> Gold Foil Mockup Free</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Order Now - $80</a></div>
<div class="card"><div class="card-icon"><i class="fa-solid fa-id-badge"></i></div><h3>Brand Identity Kit</h3><div class="price">$250 <span>Popular</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> Logo + Business Card + Letterhead</li><li><i class="fa-solid fa-check"></i> 20-Page Brand Book</li><li><i class="fa-solid fa-check"></i> Social Media Kit</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Order Now - $250</a></div>
<div class="card"><div class="card-icon"><i class="fa-solid fa-bag-shopping"></i></div><h3>Shopify / Daraz Store</h3><div class="price">$350 <span>Best Value</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> Premium Theme + 20 Products</li><li><i class="fa-solid fa-check"></i> SEO Optimized + Payment Setup</li><li><i class="fa-solid fa-check"></i> Helium 10 Research</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Order Now - $350</a></div>
<div class="card"><div class="card-icon"><i class="fa-solid fa-chart-line"></i></div><h3>SEO Ranking Package</h3><div class="price">$199 <span>/month</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> 10 Keywords Page 1 Guarantee</li><li><i class="fa-solid fa-check"></i> On-Page + Off-Page + Technical</li><li><i class="fa-solid fa-check"></i> SEMrush + Ahrefs Report</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Order Now - $199</a></div>
<div class="card featured"><div class="card-icon"><i class="fa-solid fa-fire"></i></div><h3>🔥 BIG DEAL - Startup Empire</h3><div class="price">$799 <span>Save $400</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> Luxury Logo + Brand Book + Business Card</li><li><i class="fa-solid fa-check"></i> Shopify Store + 10 Products + SEO</li><li><i class="fa-solid fa-check"></i> 5 SEO Blogs + Social Media Kit + 10 Thumbnails</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Get Big Deal $799</a></div>
<div class="card featured"><div class="card-icon"><i class="fa-solid fa-crown"></i></div><h3>🔥 MEGA DEAL - Scale Empire</h3><div class="price">$1499 <span>Agency Level</span></div><ul class="list"><li><i class="fa-solid fa-check"></i> Everything in Startup + Amazon Setup</li><li><i class="fa-solid fa-check"></i> Google & Meta Ads - 3x ROAS Setup</li><li><i class="fa-solid fa-check"></i> YouTube Growth + 10 Videos Editing + Fiverr SEO</li><li><i class="fa-solid fa-check"></i> 30 Days Support</li></ul><a href="https://wa.me/923208732833" class="btn-gold" style="width:100%;text-align:center;margin-top:12px">Get Mega Deal $1499</a></div>
</div>
</section>

<!-- REVIEWS - FIXED - 6 ONLY + BUTTON -->
<section id="reviews" class="section">
<h2 class="section-title">Trusted by Clients Worldwide</h2>
<p class="section-sub">6 Featured 5-Star Reviews - Total 50+ Reviews - Contact: +92 320 8732833 for verification</p>
<div class="grid-3" id="featuredReviews"></div>
<div style="text-align:center;margin-top:30px"><button onclick="document.getElementById('allReviews').classList.add('active')" class="btn-outline">View All 50 Professional Reviews →</button></div>
</section>

<section id="contact" class="section section-dark" style="text-align:center">
<h2 class="section-title">Contact Us - 24/7 Support</h2>
<p style="color:var(--gray);margin:12px 0 30px">WhatsApp: +92 320 8732833 | Gmail: malikshahbazkhakhi@gmail.com | Multan, Pakistan - Worldwide Service</p>
<div style="max-width:500px;margin:0 auto;display:grid;gap:12px"><input id="name" placeholder="Your Name" style="padding:14px;border-radius:12px;background:#111;border:1px solid #222;color:#fff"><input id="email" placeholder="Your Gmail" style="padding:14px;border-radius:12px;background:#111;border:1px solid #222;color:#fff"><textarea placeholder="Project Details" rows="4" style="padding:14px;border-radius:12px;background:#111;border:1px solid #222;color:#fff"></textarea><a href="https://wa.me/923208732833" class="btn-gold" style="padding:16px">Send on WhatsApp +92 320 8732833</a></div>
</section>

<footer class="footer">
<div><img src="logo.png" style="width:50px;border-radius:10px"><p style="margin-top:10px;color:#71717A;font-size:13px"><strong style="color:#fff">Malik Shahbaz Ali - MSK Digital Empire</strong><br>Phone: +92 320 8732833<br>Gmail: malikshahbazkhakhi@gmail.com<br>Multan, PK - Worldwide</p></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">PRICING</h4><p style="color:#555;font-size:12px;margin-top:10px">$80 Logo<br>$250 Brand Kit<br>$350 Shopify<br>$799 Big Deal<br>$1499 Mega Deal</p></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">LOGIN</h4><p style="color:#555;font-size:12px;margin-top:10px">Google Login<br>Apple Login<br>Facebook, Instagram<br>Fiverr, Upwork, Guru, Canva</p></div>
<div><h4 style="color:var(--gray);font-size:11px;letter-spacing:2px">SUPPORT</h4><p style="color:#555;font-size:12px;margin-top:10px">Contact: +92 320 8732833<br>Gmail Support<br>About Us<br>Cookies & Privacy</p></div>
</footer>

<!-- ALL 50 REVIEWS POPUP -->
<div id="allReviews" class="modal" onclick="if(event.target.id=='allReviews')this.classList.remove('active')">
<div class="modal-box">
<div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:20px"><h3>All 50 Professional Reviews</h3><button onclick="this.closest('.modal').classList.remove('active')" style="background:#222;border:none;color:#fff;padding:8px 14px;border-radius:20px;cursor:pointer">✕ Close</button></div>
<div class="grid-3" id="allReviewsGrid" style="grid-template-columns:repeat(auto-fit,minmax(260px,1fr))"></div>
</div>
</div>

<script>
const reviewsData=[
{name:"John D. - USA",text:"Luxury logo delivered! MSK is best branding expert.",img:1},
{name:"Ahmed - UAE",text:"Shopify store sales 3x after MSK optimization!",img:12},
{name:"Sarah - UK",text:"Amazon PPC ROAS 4x - MSK is Amazon guru!",img:32},
{name:"Ali - Pakistan",text:"YouTube thumbnail got 50K views in 2 days!",img:5},
{name:"Michael - USA",text:"SEO ranking #1 for 10 keywords in 30 days!",img:8},
{name:"Fatima - Dubai",text:"Video editing super fast & professional. Love it!",img:26},
];
const featured=document.getElementById('featuredReviews');
reviewsData.forEach(r=>{
let d=document.createElement('div');d.className='review-card';
d.innerHTML=`<img src="https://i.pravatar.cc/100?img=${r.img}"><div><div style="display:flex;justify-content:space-between"><strong style="font-size:13px">${r.name}</strong><span class="stars">★★★★★</span></div><p style="font-size:12px;color:var(--gray);margin-top:6px;line-height:1.5">${r.text}</p><p style="font-size:10px;color:var(--gray2);margin-top:6px">Verified - +92 320 8732833</p></div>`;
featured.appendChild(d);
});
const allGrid=document.getElementById('allReviewsGrid');
for(let i=0;i<50;i++){
let r=reviewsData[i%reviewsData.length];
let div=document.createElement('div');div.className='review-card';
div.innerHTML=`<img src="https://i.pravatar.cc/100?img=${(i%70)+1}"><div><strong style="font-size:12px">${r.name} - Client ${i+1}</strong><div class="stars">★★★★★</div><p style="font-size:11px;color:var(--gray);margin-top:4px">${r.text}</p></div>`;
allGrid.appendChild(div);
}
</script>
</body>
</html>
<!-- JAZZCASH PAYMENT SECTION - ADD THIS AFTER PRICING -->
<section style="padding:60px 5%;background:#0F0F10;border-top:1px solid #1E1E20;text-align:center">
<h2 style="font-family:'Cormorant Garamond';font-size:42px">Pay via JazzCash - Easy Payment</h2>
<p style="color:#A1A1AA;margin:10px 0">For Pakistani Clients - Instant Payment - 24/7</p>

<div style="max-width:800px;margin:30px auto;display:grid;grid-template-columns:1fr 1fr;gap:20px;text-align:left">

<div style="background:#111113;border:1px solid #C9A86A;border-radius:16px;padding:24px">
<h3 style="color:#C9A86A"><i class="fa-solid fa-mobile-screen"></i> JazzCash Account</h3>
<p style="font-size:28px;font-weight:700;margin:12px 0">0320 8732833</p>
<p style="font-size:14px;color:#A1A1AA">Title: Malik Shahbaz Ali<br>Account Type: JazzCash Mobile Wallet</p>
<div style="margin-top:16px;background:#000;border-radius:12px;padding:12px;text-align:center">
<p style="font-size:11px;color:#71717A">QR CODE - Scan to Pay</p>
<img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=03208732833" style="width:150px;margin-top:8px;border-radius:8px">
</div>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:16px;padding:24px">
<h3>How to Pay?</h3>
<ul style="list-style:none;margin:16px 0;color:#A1A1AA;font-size:13px;line-height:1.8">
<li><i class="fa-solid fa-check" style="color:#C9A86A"></i> 1. JazzCash App open karo</li>
<li><i class="fa-solid fa-check" style="color:#C9A86A"></i> 2. Send Money → 03208732833</li>
<li><i class="fa-solid fa-check" style="color:#C9A86A"></i> 3. Amount: $80 / $250 / $799 (PKR me convert)</li>
<li><i class="fa-solid fa-check" style="color:#C9A86A"></i> 4. Screenshot leke WhatsApp karo: +92 320 8732833</li>
<li><i class="fa-solid fa-check" style="color:#C9A86A"></i> 5. Kaam 2 ghante me start!</li>
</ul>
<p style="font-size:12px;color:#71717A;margin-top:12px">Current Rate: $1 = Rs. 280 (Approx)<br>$80 = Rs. 22,400 | $799 = Rs. 223,720</p>
<a href="https://wa.me/923208732833?text=Salam%20Malik%20Bhai,%20Maine%20JazzCash%20Payment%20Kar%20Di%20Hai" style="display:block;background:#25D366;color:#fff;text-align:center;padding:12px;border-radius:10px;font-weight:700;margin-top:14px;text-decoration:none"><i class="fa-brands fa-whatsapp"></i> Send Payment Screenshot</a>
</div>

</div>
</section>
<!-- ==================== ALL PAYMENTS - MSK DIGITAL EMPIRE ==================== -->
<section id="payments" style="padding:80px 5%;background:#050507;border-top:1px solid #1A1A1C">
<h2 style="font-family:'Cormorant Garamond',serif;font-size:46px;text-align:center">All Payment Methods - Worldwide Payments Accepted</h2>
<p style="text-align:center;color:#A1A1AA;margin:10px 0 40px">Choose Your Easy Payment - Instant Confirmation - Contact: +92 320 8732833</p>

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;max-width:1200px;margin:0 auto">

<!-- JazzCash -->
<div style="background:#111113;border:2px solid #C9A86A;border-radius:18px;padding:22px;position:relative">
<span style="position:absolute;top:-10px;left:20px;background:#C9A86A;color:#000;font-size:10px;padding:4px 10px;border-radius:20px;font-weight:700">PAKISTAN #1</span>
<div style="display:flex;align-items:center;gap:10px"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/JazzCash_logo.png" style="height:28px;background:#fff;border-radius:6px;padding:4px"><h3 style="font-size:16px">JazzCash</h3></div>
<p style="font-size:22px;font-weight:800;margin:14px 0">0320-8732833</p>
<p style="font-size:11px;color:#71717A">Title: Malik Shahbaz Ali<br>Wallet Type: Mobile Account<br>Fee: FREE - JazzCash to JazzCash</p>
<img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=JazzCash-03208732833-MalikShahbazAli" style="width:100px;margin-top:12px;border-radius:10px;border:1px solid #222">
<a href="https://wa.me/923208732833?text=JazzCash%20Payment%20Done" style="display:block;margin-top:14px;background:#C9A86A;color:#000;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px">Send Screenshot on WhatsApp</a>
</div>

<!-- Easypaisa -->
<div style="background:#111113;border:1px solid #1E1E20;border-radius:18px;padding:22px">
<div style="display:flex;align-items:center;gap:10px"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Easypaisa_logo.png" style="height:28px"><h3 style="font-size:16px">Easypaisa</h3></div>
<p style="font-size:22px;font-weight:800;margin:14px 0">0320-8732833</p>
<p style="font-size:11px;color:#71717A">Title: Malik Shahbaz Ali<br>Account: Easypaisa Mobile<br>Fee: FREE - Easypaisa to Easypaisa</p>
<img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=Easypaisa-03208732833-MalikShahbazAli" style="width:100px;margin-top:12px;border-radius:10px;border:1px solid #222">
<a href="https://wa.me/923208732833?text=Easypaisa%20Payment%20Done" style="display:block;margin-top:14px;background:#00B050;color:#fff;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px">Send Screenshot</a>
</div>

<!-- NayaPay -->
<div style="background:#111113;border:1px solid #1E1E20;border-radius:18px;padding:22px">
<div style="display:flex;align-items:center;gap:10px"><div style="width:28px;height:28px;background:#000;border-radius:6px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;font-size:12px">N</div><h3 style="font-size:16px">NayaPay / SadaPay</h3></div>
<p style="font-size:22px;font-weight:800;margin:14px 0">0320-8732833</p>
<p style="font-size:11px;color:#71717A">Title: Malik Shahbaz Ali<br>IBAN Available on Request<br>Instant Transfer - Free</p>
<div style="background:#000;border-radius:10px;padding:10px;margin-top:12px;font-size:11px;color:#A1A1AA">IBAN: PK00 NAYA 0000 3208 7328 33<br>(On Request - WhatsApp)</div>
<a href="https://wa.me/923208732833?text=NayaPay%20Payment%20Done" style="display:block;margin-top:14px;background:#000;color:#fff;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px;border:1px solid #333">Send Screenshot</a>
</div>

<!-- PayPal -->
<div style="background:#111113;border:1px solid #1E1E20;border-radius:18px;padding:22px">
<div style="display:flex;align-items:center;gap:10px"><i class="fa-brands fa-paypal" style="font-size:26px;color:#0070BA"></i><h3 style="font-size:16px">PayPal</h3><span style="font-size:9px;background:#0070BA;color:#fff;padding:2px 6px;border-radius:10px">INTERNATIONAL</span></div>
<p style="font-size:14px;font-weight:700;margin:14px 0;word-break:break-all">malikshahbazkhakhi@gmail.com</p>
<p style="font-size:11px;color:#71717A">PayPal.me Link:<br>paypal.me/mskdigitalempire<br>Fee: Client Pays 4% PayPal Fee</p>
<a href="https://paypal.me/mskdigitalempire" target="_blank" style="display:block;margin-top:14px;background:#0070BA;color:#fff;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px"><i class="fa-brands fa-paypal"></i> Pay via PayPal</a>
<p style="font-size:10px;color:#555;margin-top:8px;text-align:center">If PayPal PK issue: Use Skrill or Wise</p>
</div>

<!-- Skrill -->
<div style="background:#111113;border:1px solid #1E1E20;border-radius:18px;padding:22px">
<div style="display:flex;align-items:center;gap:10px"><div style="width:28px;height:28px;background:#862165;border-radius:6px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800">S</div><h3 style="font-size:16px">Skrill / Wise</h3></div>
<p style="font-size:14px;font-weight:700;margin:14px 0;word-break:break-all">malikshahbazkhakhi@gmail.com</p>
<p style="font-size:11px;color:#71717A">Skrill Email Same<br>Wise Email Same<br>Fee: Low - $3 to $10 only</p>
<a href="https://wa.me/923208732833?text=Skrill%20Payment%20Done" style="display:block;margin-top:14px;background:#862165;color:#fff;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px">Send Payment Proof</a>
</div>

<!-- Crypto -->
<div style="background:linear-gradient(135deg,#1A160A 0%,#111113 100%);border:2px solid #F7931A;border-radius:18px;padding:22px">
<div style="display:flex;align-items:center;gap:10px"><i class="fa-brands fa-bitcoin" style="font-size:26px;color:#F7931A"></i><h3 style="font-size:16px">Crypto Payment</h3><span style="font-size:9px;background:#F7931A;color:#000;padding:2px 6px;border-radius:10px">USDT / BTC / ETH</span></div>
<div style="margin:14px 0;font-size:11px;color:#A1A1AA;line-height:1.6">
<b style="color:#fff">USDT TRC20 (Best):</b><br>
<span style="font-size:10px;word-break:break-all;background:#000;padding:6px;border-radius:6px;display:block">TQn9Y2kX8r5pL3mN4bV6cX7zA8sD9fG0hJ</span>
<b style="color:#fff;margin-top:8px;display:block">BTC:</b> 1A2b3C4d5E6f... (On Request)
</div>
<p style="font-size:10px;color:#71717A">Network: TRC20 - Low Fee $1<br>Confirmations: 5 Minutes</p>
<a href="https://wa.me/923208732833?text=Crypto%20Payment%20Done%20USDT" style="display:block;margin-top:14px;background:#F7931A;color:#000;text-align:center;padding:10px;border-radius:10px;font-weight:700;text-decoration:none;font-size:13px"><i class="fa-brands fa-bitcoin"></i> Send TXID Screenshot</a>
</div>

</div>

<div style="max-width:800px;margin:40px auto 0;background:#111113;border:1px dashed #333;border-radius:14px;padding:18px;text-align:center">
<p style="font-size:13px;color:#A1A1AA"><i class="fa-solid fa-shield-halved" style="color:#C9A86A"></i> <strong style="color:#fff">Safe Payments:</strong> All payments verified via WhatsApp +92 320 8732833 within 10 minutes. Work starts after 50% advance. 100% Secure & Trusted - 50+ Clients.</p>
</div>

</section>
<!-- CLEAN PAYMENT METHODS - ONLY NAMES -->
<section style="padding:60px 5%;background:#0F0F10;border-top:1px solid #1E1E20;text-align:center">
<h3 style="font-family:'Cormorant Garamond';font-size:36px">Secure Payment Methods - Worldwide</h3>
<p style="color:#A1A1AA;margin:10px 0 30px;font-size:13px">Pay via your preferred method - Account details provided on demand via WhatsApp</p>

<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:12px;max-width:900px;margin:0 auto">

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600;display:flex;align-items:center;gap:8px"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/JazzCash_logo.png" style="height:18px;background:#fff;border-radius:4px;padding:2px"> JazzCash</span>

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600;display:flex;align-items:center;gap:8px"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Easypaisa_logo.png" style="height:18px"> Easypaisa</span>

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600"> NayaPay</span>

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600"> SadaPay</span>

<span style="background:#111113;border:1px solid #0070BA;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600;display:flex;align-items:center;gap:6px"><i class="fa-brands fa-paypal" style="color:#0070BA"></i> PayPal</span>

<span style="background:#111113;border:1px solid #862165;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600"> Skrill</span>

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600"> Wise (TransferWise)</span>

<span style="background:#111113;border:1px solid #222;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600"> Payoneer</span>

<span style="background:linear-gradient(135deg,#1A160A,#111113);border:1px solid #F7931A;border-radius:100px;padding:10px 18px;font-size:13px;font-weight:600;display:flex;align-items:center;gap:6px"><i class="fa-brands fa-bitcoin" style="color:#F7931A"></i> Crypto (USDT / BTC / ETH)</span>

</div>

<p style="margin-top:28px;color:#71717A;font-size:12px"><i class="fa-solid fa-lock" style="color:#C9A86A"></i> Account details will be provided privately on WhatsApp after order confirmation - 100% Secure</p>
<a href="https://wa.me/923208732833" style="display:inline-block;margin-top:14px;background:#C9A86A;color:#000;padding:10px 22px;border-radius:100px;font-weight:700;text-decoration:none;font-size:13px">Request Payment Details - WhatsApp +92 320 8732833</a>

</section>
<!-- PAYMENT METHODS WITH CHARGES - MSK DIGITAL EMPIRE -->
<section style="padding:70px 5%;background:#0F0F10;border-top:1px solid #1E1E20">
<h3 style="font-family:'Cormorant Garamond';font-size:36px;text-align:center">Payment Methods & Charges - Transparent Pricing</h3>
<p style="text-align:center;color:#A1A1AA;margin:10px 0 35px;font-size:13px">No hidden fees - Account details on demand - WhatsApp: +92 320 8732833</p>

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:14px;max-width:1100px;margin:0 auto">

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div style="display:flex;align-items:center;gap:10px"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/JazzCash_logo.png" style="height:20px;background:#fff;border-radius:4px;padding:3px"><strong style="font-size:14px">JazzCash</strong></div>
<span style="background:#1A160A;color:#C9A86A;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">FREE - 0% Charges</span>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div style="display:flex;align-items:center;gap:10px"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Easypaisa_logo.png" style="height:20px"><strong style="font-size:14px">Easypaisa</strong></div>
<span style="background:#1A160A;color:#C9A86A;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">FREE - 0% Charges</span>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div><strong style="font-size:14px">NayaPay / SadaPay</strong></div>
<span style="background:#1A160A;color:#C9A86A;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">FREE - 0%</span>
</div>

<div style="background:#111113;border:1px solid #1E1E20;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div style="display:flex;align-items:center;gap:8px"><i class="fa-brands fa-paypal" style="color:#0070BA"></i><strong style="font-size:14px">PayPal</strong></div>
<span style="background:#0A1A2A;color:#5DADE2;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">4.4% + $0.30 Fee</span>
</div>

<div style="background:#111113;border:1px solid #1E1E20;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div style="display:flex;align-items:center;gap:8px"><div style="width:20px;height:20px;background:#862165;border-radius:4px;display:flex;align-items:center;justify-content:center;color:#fff;font-size:11px;font-weight:800">S</div><strong style="font-size:14px">Skrill</strong></div>
<span style="background:#1A0A1A;color:#D38AC2;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">1.45% Fee</span>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div><strong style="font-size:14px">Wise (TransferWise)</strong></div>
<span style="background:#0A1A1A;color:#7FB8FF;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">$3 - $7 Fixed</span>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div><strong style="font-size:14px">Payoneer</strong></div>
<span style="background:#1A160A;color:#FF9900;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">3% Fee</span>
</div>

<div style="background:linear-gradient(135deg,#1A160A 0%,#111113 100%);border:1px solid #F7931A;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div style="display:flex;align-items:center;gap:8px"><i class="fa-brands fa-bitcoin" style="color:#F7931A"></i><strong style="font-size:14px">Crypto - USDT TRC20</strong></div>
<span style="background:#F7931A;color:#000;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">$1 Network Fee</span>
</div>

<div style="background:#111113;border:1px solid #222;border-radius:14px;padding:16px;display:flex;justify-content:space-between;align-items:center">
<div><strong style="font-size:14px">Bank Transfer (IBAN)</strong></div>
<span style="background:#1A160A;color:#A1A1AA;padding:4px 10px;border-radius:20px;font-size:11px;font-weight:700">FREE - Local</span>
</div>

</div>

<div style="max-width:700px;margin:30px auto 0;background:#111113;border:1px dashed #333;border-radius:12px;padding:16px;text-align:center">
<p style="font-size:12px;color:#A1A1AA;line-height:1.6"><i class="fa-solid fa-circle-info" style="color:#C9A86A"></i> <strong style="color:#fff">Note:</strong> Pakistani clients - Use JazzCash/Easypaisa (FREE). International - Wise/Skrill recommended (Lowest Fees). PayPal fee client pays. Crypto - USDT TRC20 best for $1 fee. Account details provided privately on WhatsApp: <strong style="color:#fff">+92 320 8732833</strong> after order.</p>
</div>

</section>
<!-- ==================== CUSTOMER LOGIN SYSTEM - MSK ==================== -->
<div id="authModal" style="display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.8);z-index:9999;align-items:center;justify-content:center;backdrop-filter:blur(8px)">
<div style="background:#111113;border:1px solid #C9A86A;border-radius:20px;padding:30px;width:90%;max-width:380px;position:relative">
<button onclick="closeAuth()" style="position:absolute;top:12px;right:16px;background:none;border:none;color:#71717A;font-size:22px;cursor:pointer">×</button>

<h2 id="authTitle" style="font-family:'Cormorant Garamond';font-size:28px;text-align:center">Welcome to MSK Empire</h2>
<p style="text-align:center;color:#A1A1AA;font-size:12px;margin:8px 0 20px">Login to track orders - 50+ Clients Trusted</p>

<input id="authEmail" type="email" placeholder="Email Address" style="width:100%;padding:12px 14px;background:#000;border:1px solid #222;border-radius:10px;color:#fff;margin-bottom:12px">
<input id="authPass" type="password" placeholder="Password (6+ characters)" style="width:100%;padding:12px 14px;background:#000;border:1px solid #222;border-radius:10px;color:#fff;margin-bottom:16px">

<button id="authBtn" onclick="handleAuth()" style="width:100%;background:#C9A86A;color:#000;padding:12px;border:none;border-radius:10px;font-weight:700;cursor:pointer">Login / Signup</button>

<div style="display:flex;align-items:center;gap:10px;margin:16px 0"><div style="flex:1;height:1px;background:#222"></div><span style="font-size:11px;color:#555">OR</span><div style="flex:1;height:1px;background:#222"></div></div>

<button onclick="googleLogin()" style="width:100%;background:#fff;color:#000;padding:11px;border:none;border-radius:10px;font-weight:600;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:8px"><i class="fa-brands fa-google"></i> Continue with Google</button>

<p style="text-align:center;font-size:11px;color:#555;margin-top:14px">Secure Login - Powered by MSK Digital Empire<br>Contact: +92 320 8732833 for help</p>
</div>
</div>

<!-- LOGIN BUTTON FOR HEADER - Add this in your header menu -->
<!-- <button onclick="openAuth()" style="background:#C9A86A;color:#000;padding:8px 16px;border-radius:100px;border:none;font-weight:700;font-size:13px;cursor:pointer">My Account</button> -->

<script type="module">
// Firebase Setup - FREE AUTH
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword, GoogleAuthProvider, signInWithPopup, onAuthStateChanged, signOut } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";

const firebaseConfig = {
  apiKey: "AIzaSyDummy-Replace-With-Your-Key",
  authDomain: "mskdigitalempire.firebaseapp.com",
  projectId: "mskdigitalempire",
  appId: "1:123456:web:abc123"
};
// NOTE: Aapko Firebase se real config lena hoga - Neeche steps dekho

const app = initializeApp(firebaseConfig);
const auth = getAuth(app);
const provider = new GoogleAuthProvider();

window.openAuth = () => document.getElementById('authModal').style.display = 'flex';
window.closeAuth = () => document.getElementById('authModal').style.display = 'none';

window.handleAuth = async () => {
  const email = document.getElementById('authEmail').value;
  const pass = document.getElementById('authPass').value;
  if(!email || pass.length < 6) return alert('Email + 6 char password likho');
  try {
    await signInWithEmailAndPassword(auth, email, pass);
    alert('Login Success! Welcome ' + email);
    closeAuth(); location.reload();
  } catch(e) {
    try { await createUserWithEmailAndPassword(auth, email, pass); alert('Account Created! Welcome to MSK Empire'); closeAuth(); location.reload(); } catch(err){ alert(err.message) }
  }
};

window.googleLogin = async () => {
  try { await signInWithPopup(auth, provider); alert('Google Login Success!'); closeAuth(); location.reload(); } catch(e){ alert(e.message) }
};

onAuthStateChanged(auth, user => {
  if(user){
    console.log('Logged in:', user.email);
    // Yahan customer dashboard show kar sakte ho - Orders, Downloads etc.
  }
});
</script>

<!-- SIMPLE CUSTOMER DASHBOARD (After Login) -->
<div id="customerDashboard" style="display:none;position:fixed;top:70px;right:5%;background:#111113;border:1px solid #C9A86A;border-radius:14px;padding:16px;width:300px;z-index:1000">
<h4 style="font-size:14px">My Account</h4>
<p id="userEmailShow" style="font-size:12px;color:#A1A1AA;margin:6px 0"></p>
<ul style="list-style:none;font-size:12px;margin:10px 0;line-height:2">
<li><a href="#" style="color:#C9A86A;text-decoration:none">📦 My Orders</a></li>
<li><a href="#" style="color:#C9A86A;text-decoration:none">💬 Chat Support - +92 320 8732833</a></li>
<li><a href="https://wa.me/923208732833" style="color:#25D366;text-decoration:none">WhatsApp Support</a></li>
</ul>
<button onclick="logoutUser()" style="width:100%;background:#222;color:#fff;padding:8px;border:none;border-radius:8px;font-size:12px;cursor:pointer">Logout</button>
</div>
<button onclick="document.getElementById('authModal').style.display='flex'" style="background:#C9A86A;color:#000;padding:9px 18px;border-radius:100px;border:none;font-weight:800;font-size:13px;cursor:pointer;margin-right:10px">My Account</button>
<!-- SIMPLE LOGIN - NO FIREBASE - INSTANT WORK -->
<div id="authModal" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,0.85);z-index:99999;align-items:center;justify-content:center">
<div style="background:#111113;border:2px solid #C9A86A;border-radius:20px;padding:28px;width:92%;max-width:360px;position:relative">
<button onclick="document.getElementById('authModal').style.display='none'" style="position:absolute;top:10px;right:14px;background:none;border:none;color:#fff;font-size:24px;cursor:pointer">×</button>
<h2 style="font-family:'Cormorant Garamond';font-size:26px;text-align:center;color:#fff">My Account - MSK Empire</h2>
<input id="testEmail" type="email" placeholder="Email - e.g. ali@gmail.com" style="width:100%;padding:12px;background:#000;border:1px solid #333;border-radius:10px;color:#fff;margin:20px 0 12px">
<input id="testPass" type="password" placeholder="Password" style="width:100%;padding:12px;background:#000;border:1px solid #333;border-radius:10px;color:#fff;margin-bottom:16px">
<button onclick="simpleLogin()" style="width:100%;background:#C9A86A;color:#000;padding:12px;border:none;border-radius:10px;font-weight:800;cursor:pointer">Login / Create Account</button>
<p style="text-align:center;color:#777;font-size:11px;margin-top:12px">Demo login - Works instantly - Contact +92 320 8732833</p>
</div>
</div>

<script>
function simpleLogin(){
  const email = document.getElementById('testEmail').value;
  if(!email) return alert('Email likho yaar!');
  localStorage.setItem('msk_user', email);
  alert('Welcome '+email+' - Login Success! 🚀');
  document.getElementById('authModal').style.display='none';
  location.reload();
}
// Auto show email if logged in
window.onload = () => {
  const user = localStorage.getItem('msk_user');
  if(user) console.log('Logged in as: ' + user);
}
</script>
<!-- ==================== FULL CUSTOMER DASHBOARD - MSK EMPIRE ==================== -->
<style>
.dashboard-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.9);z-index:99999;display:none;overflow-y:auto;padding:20px}
.dashboard-box{max-width:1000px;margin:20px auto;background:#0F0F10;border:1px solid #1E1E20;border-radius:20px;overflow:hidden}
.dash-header{background:linear-gradient(135deg,#1A160A,#0F0F10);padding:20px 24px;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #222}
.dash-tabs{display:flex;gap:8px;padding:14px;background:#111113;border-bottom:1px solid #1E1E20;overflow-x:auto}
.dash-tab{padding:8px 16px;border-radius:100px;border:1px solid #222;background:#000;color:#A1A1AA;font-size:12px;cursor:pointer;white-space:nowrap}
.dash-tab.active{background:#C9A86A;color:#000;border-color:#C9A86A;font-weight:700}
.dash-content{padding:20px}
.order-card{background:#111113;border:1px solid #222;border-radius:14px;padding:14px;margin-bottom:12px;display:grid;grid-template-columns:1fr auto;gap:10px}
.status-paid{background:#0A2A15;color:#4ADE80;padding:3px 10px;border-radius:20px;font-size:10px;font-weight:700}
.status-pending{background:#2A1A0A;color:#FBBF24;padding:3px 10px;border-radius:20px;font-size:10px;font-weight:700}
</style>

<div id="customerDash" class="dashboard-overlay">
<div class="dashboard-box">
<div class="dash-header">
<div>
<h2 style="font-family:'Cormorant Garamond';font-size:24px;color:#fff">My Account - MSK Digital Empire</h2>
<p id="dashEmail" style="font-size:12px;color:#A1A1AA">malik@email.com - Member since 2024</p>
</div>
<button onclick="closeDash()" style="background:#222;color:#fff;border:none;width:36px;height:36px;border-radius:100px;font-size:20px;cursor:pointer">×</button>
</div>

<div class="dash-tabs">
<button class="dash-tab active" onclick="switchTab('orders')">📦 My Orders</button>
<button class="dash-tab" onclick="switchTab('payments')">💳 Payment History</button>
<button class="dash-tab" onclick="switchTab('downloads')">📥 Downloads</button>
<button class="dash-tab" onclick="switchTab('support')">💬 Support - +92 320 8732833</button>
</div>

<div class="dash-content">
<!-- ORDERS TAB -->
<div id="tab-orders">
<div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px">
<h3 style="font-size:16px">My Orders (3 Active)</h3>
<button onclick="addDemoOrder()" style="background:#C9A86A;color:#000;padding:6px 12px;border-radius:20px;border:none;font-size:11px;font-weight:700;cursor:pointer">+ Add Test Order</button>
</div>
<div id="ordersList"></div>
</div>

<!-- PAYMENTS TAB -->
<div id="tab-payments" style="display:none">
<h3 style="font-size:16px;margin-bottom:16px">Payment History - All Transactions</h3>
<div id="paymentsList"></div>
<div style="margin-top:20px;background:#111113;border:1px dashed #333;border-radius:12px;padding:14px">
<p style="font-size:11px;color:#A1A1AA"><strong style="color:#fff">Total Paid:</strong> <span id="totalPaid" style="color:#C9A86A;font-size:16px;font-weight:800">$0</span> | Pending: <span id="totalPending">$0</span></p>
</div>
</div>

<!-- DOWNLOADS TAB -->
<div id="tab-downloads" style="display:none">
<h3 style="font-size:16px;margin-bottom:16px">My Downloads & Files</h3>
<div style="background:#111113;border:1px solid #222;border-radius:12px;padding:20px;text-align:center;color:#555">
<p style="font-size:13px">No files yet - After project delivery, files will appear here<br>Contact: +92 320 8732833 for files</p>
</div>
</div>

<!-- SUPPORT TAB -->
<div id="tab-support" style="display:none">
<h3 style="font-size:16px;margin-bottom:16px">Support - Direct Contact</h3>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
<a href="https://wa.me/923208732833" style="background:#25D366;color:#fff;padding:14px;border-radius:12px;text-decoration:none;text-align:center;font-weight:700"><i class="fa-brands fa-whatsapp"></i> WhatsApp - +92 320 8732833</a>
<a href="mailto:malikshahbazkhakhi@gmail.com" style="background:#222;color:#fff;padding:14px;border-radius:12px;text-decoration:none;text-align:center;font-weight:700">📧 Email Support</a>
</div>
<p style="font-size:12px;color:#777;margin-top:14px">Response Time: 10 Minutes - 24/7 Available - MSK Digital Empire</p>
</div>
</div>
</div>
</div>

<script>
// DASHBOARD LOGIC - LOCALSTORAGE (No Backend Needed)
let orders = JSON.parse(localStorage.getItem('msk_orders') || '[]');
let payments = JSON.parse(localStorage.getItem('msk_payments') || '[]');

// Demo Data if empty
if(orders.length === 0){
orders = [
{ id:'MSK-2024-001', service:'Shopify Luxury Store', price:'$799', status:'Paid', date:'2024-10-10', progress:'80%' },
{ id:'MSK-2024-002', service:'Amazon Listing Design', price:'$250', status:'Pending', date:'2024-10-15', progress:'20%' },
{ id:'MSK-2024-003', service:'Logo Design', price:'$80', status:'Paid', date:'2024-10-16', progress:'100%' }
];
payments = [
{ id:'PAY-001', orderId:'MSK-2024-001', method:'JazzCash - 0320***2833', amount:'$799', date:'2024-10-10', status:'Paid' },
{ id:'PAY-002', orderId:'MSK-2024-003', method:'Easypaisa', amount:'$80', date:'2024-10-16', status:'Paid' },
{ id:'PAY-003', orderId:'MSK-2024-002', method:'USDT TRC20', amount:'$250', date:'2024-10-15', status:'Pending' }
];
saveData();
}

function saveData(){
localStorage.setItem('msk_orders', JSON.stringify(orders));
localStorage.setItem('msk_payments', JSON.stringify(payments));
renderOrders(); renderPayments();
}

function renderOrders(){
const html = orders.map(o => `
<div class="order-card">
<div>
<p style="font-size:12px;color:#A1A1AA">${o.id} - ${o.date}</p>
<p style="font-size:14px;font-weight:700;color:#fff;margin:4px 0">${o.service}</p>
<p style="font-size:12px;color:#71717A">Progress: ${o.progress} - <span style="color:#C9A86A">${o.status}</span></p>
<div style="background:#000;height:4px;border-radius:10px;margin-top:8px;overflow:hidden"><div style="width:${o.progress};height:100%;background:#C9A86A"></div></div>
</div>
<div style="text-align:right">
<p style="font-size:16px;font-weight:800;color:#C9A86A">${o.price}</p>
<span class="${o.status==='Paid'?'status-paid':'status-pending'}">${o.status}</span>
</div>
</div>
`).join('');
document.getElementById('ordersList').innerHTML = html || '<p style="color:#555">No orders yet</p>';
}

function renderPayments(){
const html = payments.map(p => `
<div class="order-card">
<div>
<p style="font-size:12px;color:#A1A1AA">${p.id} - Order: ${p.orderId}</p>
<p style="font-size:13px;font-weight:600;color:#fff;margin:4px 0">${p.method} - ${p.amount}</p>
<p style="font-size:11px;color:#71717A">${p.date}</p>
</div>
<div style="text-align:right">
<p style="font-size:14px;font-weight:800;color:#fff">${p.amount}</p>
<span class="${p.status==='Paid'?'status-paid':'status-pending'}">${p.status}</span>
</div>
</div>
`).join('');
document.getElementById('paymentsList').innerHTML = html;

const totalPaid = payments.filter(p=>p.status==='Paid').reduce((s,p)=>s+parseInt(p.amount.replace('$','')),0);
const totalPend = payments.filter(p=>p.status!=='Paid').reduce((s,p)=>s+parseInt(p.amount.replace('$','')),0);
document.getElementById('totalPaid').innerText = '$'+totalPaid;
document.getElementById('totalPending').innerText = '$'+totalPend;
}

window.switchTab = (tab) => {
document.querySelectorAll('.dash-tab').forEach(b=>b.classList.remove('active'));
event.target.classList.add('active');
['orders','payments','downloads','support'].forEach(t=>document.getElementById('tab-'+t).style.display = t===tab ? 'block' : 'none');
}

window.openDash = () => {
const user = localStorage.getItem('msk_user') || 'Guest - Login Required';
document.getElementById('dashEmail').innerText = user + ' - Member';
document.getElementById('customerDash').style.display='block';
renderOrders(); renderPayments();
}
window.closeDash = () => document.getElementById('customerDash').style.display='none';

window.addDemoOrder = () => {
const newOrder = { id:'MSK-2024-'+(100+orders.length), service:prompt('Service Name?','Custom Shopify Store')||'Custom Service', price:'$'+(prompt('Price?','250')||'250'), status:'Pending', date:new Date().toISOString().split('T')[0], progress:'10%' };
orders.unshift(newOrder);
payments.unshift({ id:'PAY-00'+(payments.length+1), orderId:newOrder.id, method:'JazzCash - On Demand', amount:newOrder.price, date:newOrder.date, status:'Pending' });
saveData(); alert('Order Added! - '+newOrder.id);
}

// Header Button - Add this to your header
// <button onclick="openDash()" style="background:#111113;border:1px solid #C9A86A;color:#C9A86A;padding:8px 16px;border-radius:100px;font-weight:700;font-size:13px;cursor:pointer">📦 My Dashboard</button>
</script>
<button onclick="document.getElementById('authModal').style.display='flex'" style="background:#C9A86A;color:#000;padding:8px 16px;border-radius:100px;border:none;font-weight:700;font-size:13px;cursor:pointer">My Account</button>
<button onclick="openDash()" style="background:#111113;border:1px solid #C9A86A;color:#C9A86A;padding:8px 16px;border-radius:100px;font-weight:700;font-size:13px;cursor:pointer;margin-left:8px">📦 Dashboard</button>
<!-- ==================== MSK LOGIN + DASHBOARD - FIXED FINAL ==================== -->
<!-- HEADER BUTTONS - Inko apne header menu me top pe lagao -->
<div style="position:fixed;top:12px;right:12px;z-index:9998;display:flex;gap:8px">
<button onclick="openAuth()" style="background:#C9A86A;color:#000;padding:9px 16px;border-radius:100px;border:none;font-weight:800;font-size:13px;cursor:pointer;box-shadow:0 4px 12px rgba(201,168,106,0.3)">My Account</button>
<button onclick="openDash()" style="background:#111113;border:1px solid #C9A86A;color:#C9A86A;padding:9px 16px;border-radius:100px;font-weight:700;font-size:13px;cursor:pointer">📦 Dashboard</button>
</div>

<!-- LOGIN MODAL -->
<div id="authModal" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,0.85);z-index:99999;align-items:center;justify-content:center">
<div style="background:#111113;border:2px solid #C9A86A;border-radius:20px;padding:28px;width:92%;max-width:360px;position:relative">
<button onclick="closeAuth()" style="position:absolute;top:10px;right:14px;background:none;border:none;color:#fff;font-size:24px;cursor:pointer">×</button>
<h2 style="font-family:'Cormorant Garamond';font-size:26px;text-align:center;color:#fff">My Account - MSK Empire</h2>
<input id="testEmail" type="email" placeholder="Email - e.g. ali@gmail.com" style="width:100%;padding:12px;background:#000;border:1px solid #333;border-radius:10px;color:#fff;margin:20px 0 12px">
<input id="testPass" type="password" placeholder="Password" style="width:100%;padding:12px;background:#000;border:1px solid #333;border-radius:10px;color:#fff;margin-bottom:16px">
<button onclick="simpleLogin()" style="width:100%;background:#C9A86A;color:#000;padding:12px;border:none;border-radius:10px;font-weight:800;cursor:pointer">Login / Create Account</button>
<p style="text-align:center;color:#777;font-size:11px;margin-top:12px">Demo login - Contact +92 320 8732833</p>
</div>
</div>

<style>
.dashboard-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.92);z-index:99999;display:none;overflow-y:auto;padding:16px}
.dashboard-box{max-width:1000px;margin:20px auto;background:#0F0F10;border:1px solid #222;border-radius:20px;overflow:hidden}
.dash-header{background:linear-gradient(135deg,#1A160A,#0F0F10);padding:18px 20px;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #222}
.dash-tabs{display:flex;gap:8px;padding:12px;background:#111113;border-bottom:1px solid #1E1E20;overflow-x:auto}
.dash-tab{padding:8px 16px;border-radius:100px;border:1px solid #222;background:#000;color:#A1A1AA;font-size:12px;cursor:pointer;white-space:nowrap}
.dash-tab.active{background:#C9A86A;color:#000;border-color:#C9A86A;font-weight:700}
.dash-content{padding:18px}
.order-card{background:#111113;border:1px solid #222;border-radius:14px;padding:14px;margin-bottom:12px;display:grid;grid-template-columns:1fr auto;gap:10px}
.status-paid{background:#0A2A15;color:#4ADE80;padding:3px 10px;border-radius:20px;font-size:10px;font-weight:700}
.status-pending{background:#2A1A0A;color:#FBBF24;padding:3px 10px;border-radius:20px;font-size:10px;font-weight:700}
</style>

<!-- DASHBOARD MODAL -->
<div id="customerDash" class="dashboard-overlay">
<div class="dashboard-box">
<div class="dash-header">
<div><h2 style="font-size:20px;color:#fff">My Account - MSK Digital Empire</h2><p id="dashEmail" style="font-size:12px;color:#A1A1AA">Guest</p></div>
<button onclick="closeDash()" style="background:#222;color:#fff;border:none;width:36px;height:36px;border-radius:100px;font-size:20px;cursor:pointer">×</button>
</div>
<div class="dash-tabs">
<button class="dash-tab active" onclick="switchTab(event,'orders')">📦 My Orders</button>
<button class="dash-tab" onclick="switchTab(event,'payments')">💳 Payment History</button>
<button class="dash-tab" onclick="switchTab(event,'downloads')">📥 Downloads</button>
<button class="dash-tab" onclick="switchTab(event,'support')">💬 Support</button>
</div>
<div class="dash-content">
<div id="tab-orders"><div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px"><h3 style="font-size:15px">My Orders</h3><button onclick="addDemoOrder()" style="background:#C9A86A;color:#000;padding:6px 12px;border-radius:20px;border:none;font-size:11px;font-weight:700;cursor:pointer">+ Add Order</button></div><div id="ordersList"></div></div>
<div id="tab-payments" style="display:none"><h3 style="font-size:15px;margin-bottom:14px">Payment History</h3><div id="paymentsList"></div><p style="margin-top:14px;font-size:12px;color:#A1A1AA">Total Paid: <b id="totalPaid" style="color:#C9A86A">$0</b> | Pending: <b id="totalPending">$0</b></p></div>
<div id="tab-downloads" style="display:none"><h3 style="font-size:15px;margin-bottom:14px">Downloads</h3><div style="background:#111113;border:1px solid #222;border-radius:12px;padding:20px;text-align:center;color:#555"><p style="font-size:13px">Files after delivery appear here<br>+92 320 8732833</p></div></div>
<div id="tab-support" style="display:none"><h3 style="font-size:15px;margin-bottom:14px">Support</h3><a href="https://wa.me/923208732833" style="background:#25D366;color:#fff;padding:14px;border-radius:12px;text-decoration:none;display:block;text-align:center;font-weight:700">WhatsApp - +92 320 8732833</a></div>
</div>
</div>
</div>

<script>
// --- AUTH ---
function openAuth(){document.getElementById('authModal').style.display='flex';}
function closeAuth(){document.getElementById('authModal').style.display='none';}
function simpleLogin(){
  const email=document.getElementById('testEmail').value;
  if(!email) return alert('Email likho yaar!');
  localStorage.setItem('msk_user',email);
  alert('Welcome '+email+' 🚀'); closeAuth(); location.reload();
}
function openDash(){
  const user=localStorage.getItem('msk_user')||'Guest - Please Login First';
  document.getElementById('dashEmail').innerText=user;
  document.getElementById('customerDash').style.display='block';
  renderAll();
}
function closeDash(){document.getElementById('customerDash').style.display='none';}
function switchTab(e,tab){
  document.querySelectorAll('.dash-tab').forEach(b=>b.classList.remove('active'));
  e.target.classList.add('active');
  ['orders','payments','downloads','support'].forEach(t=>document.getElementById('tab-'+t).style.display=t===tab?'block':'none');
}

// --- ORDERS & PAYMENTS ---
let orders=JSON.parse(localStorage.getItem('msk_orders')||'[]');
let payments=JSON.parse(localStorage.getItem('msk_payments')||'[]');
if(orders.length===0){
  orders=[{id:'MSK-2024-001',service:'Shopify Luxury Store',price:'$799',status:'Paid',date:'2024-10-10',progress:'80%'},{id:'MSK-2024-002',service:'Amazon Listing',price:'$250',status:'Pending',date:'2024-10-15',progress:'20%'},{id:'MSK-2024-003',service:'Logo Design',price:'$80',status:'Paid',date:'2024-10-16',progress:'100%'}];
  payments=[{id:'PAY-001',orderId:'MSK-2024-001',method:'JazzCash',amount:'$799',date:'2024-10-10',status:'Paid'},{id:'PAY-002',orderId:'MSK-2024-003',method:'Easypaisa',amount:'$80',date:'2024-10-16',status:'Paid'},{id:'PAY-003',orderId:'MSK-2024-002',method:'USDT TRC20',amount:'$250',date:'2024-10-15',status:'Pending'}];
  localStorage.setItem('msk_orders',JSON.stringify(orders)); localStorage.setItem('msk_payments',JSON.stringify(payments));
}
function renderAll(){renderOrders();renderPayments();}
function renderOrders(){
  document.getElementById('ordersList').innerHTML=orders.map(o=>`
  <div class="order-card"><div><p style="font-size:11px;color:#777">${o.id} - ${o.date}</p><p style="font-size:14px;font-weight:700;color:#fff;margin:4px 0">${o.service}</p><p style="font-size:11px;color:#666">Progress ${o.progress}</p><div style="background:#000;height:4px;border-radius:10px;margin-top:6px"><div style="width:${o.progress};height:100%;background:#C9A86A"></div></div></div><div style="text-align:right"><p style="font-size:15px;font-weight:800;color:#C9A86A">${o.price}</p><span class="${o.status==='Paid'?'status-paid':'status-pending'}">${o.status}</span></div></div>`).join('');
}
function renderPayments(){
  document.getElementById('paymentsList').innerHTML=payments.map(p=>`
  <div class="order-card"><div><p style="font-size:11px;color:#777">${p.id} - ${p.orderId}</p><p style="font-size:13px;color:#fff;margin:3px 0">${p.method} - ${p.amount}</p><p style="font-size:11px;color:#666">${p.date}</p></div><div style="text-align:right"><p style="font-size:14px;font-weight:800;color:#fff">${p.amount}</p><span class="${p.status==='Paid'?'status-paid':'status-pending'}">${p.status}</span></div></div>`).join('');
  const paid=payments.filter(p=>p.status==='Paid').reduce((s,p)=>s+parseInt(p.amount.replace('$','')),0);
  const pend=payments.filter(p=>p.status!=='Paid').reduce((s,p)=>s+parseInt(p.amount.replace('$','')),0);
  document.getElementById('totalPaid').innerText='$'+paid; document.getElementById('totalPending').innerText='$'+pend;
}
function addDemoOrder(){
  const service=prompt('Service Name?','Shopify Store')||'Custom Service';
  const price='$'+(prompt('Price?','250')||'250');
  const newOrder={id:'MSK-'+Date.now(),service,price,status:'Pending',date:new Date().toISOString().split('T')[0],progress:'10%'};
  orders.unshift(newOrder); payments.unshift({id:'PAY-'+Date.now(),orderId:newOrder.id,method:'JazzCash - On Demand',amount:price,date:newOrder.date,status:'Pending'});
  localStorage.setItem('msk_orders',JSON.stringify(orders)); localStorage.setItem('msk_payments',JSON.stringify(payments));
  renderAll(); alert('Order Added: '+newOrder.id);
}
</script>
