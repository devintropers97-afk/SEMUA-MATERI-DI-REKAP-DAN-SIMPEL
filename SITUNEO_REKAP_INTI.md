# 📌 SITUNEO - REKAP INTI MATERI

## 🎯 TENTANG PROJECT
**Nama:** SITUNEO Digital Platform  
**Perusahaan:** PT SITUNEO DIGITAL SOLUSI INDONESIA  
**Tipe:** Platform Digital Multi-Level Marketing untuk Jasa Website

---

## ⏱️ TIMELINE DEVELOPMENT

### TOTAL: 12-16 minggu (60-90 hari kerja)

**15 BATCH DEVELOPMENT:**

### 📍 FASE 1: FOUNDATION (Week 1-3)
- **Batch 1:** Database (85+ tables) - 3-5 hari 🔥
- **Batch 2:** Core System (MVC, Router, Classes) - 5-7 hari 🔥
- **Batch 3:** Public Website (11 pages, premium) - 5-7 hari 🔥

### 📍 FASE 2: AUTH & CLIENT (Week 4-5)
- **Batch 4:** Auth System (Login, Register, Reset) - 4-5 hari 🔥
- **Batch 5:** Client Dashboard (18 pages, 26 fields) - 5-7 hari 🔥

### 📍 FASE 3: PARTNER & SPV (Week 6-8)
- **Batch 6:** Partner Dashboard (30 pages, tier) - 5-7 hari 🟠
- **Batch 7:** SPV Dashboard (35 pages, ARPU) - 5-7 hari 🟠
- **Batch 8:** Commission & ARPU (Auto, Cron) - 4-5 hari 🔥

### 📍 FASE 4: MANAGER & ADMIN (Week 9-11)
- **Batch 9:** Manager Dashboard (35 pages, area) - 5-7 hari 🟡
- **Batch 10:** Admin Part 1 (User, Order, Payment) - 7-10 hari 🔥
- **Batch 11:** Admin Part 2 (Commission, CMS, Settings) - 7-10 hari 🔥

### 📍 FASE 5: ADVANCED FEATURES (Week 12-13)
- **Batch 12:** Demo Request (26 fields, copy detail) - 3-4 hari 🟡
- **Batch 13:** Task Board (post, take, submit) - 4-5 hari 🟡

### 📍 FASE 6: POLISH & DEPLOY (Week 14-16)
- **Batch 14:** 50 Demo Websites (10 categories) - 10-14 hari 🟢
- **Batch 15:** Polish & Deploy (test, optimize, deploy) - 5-7 hari 🔥

---

## 💰 SISTEM KOMISI

### CONTOH PERHITUNGAN:
**Client Order:** Rp 10,000,000

| Role | Persentase | Jumlah |
|------|-----------|---------|
| Partner (Tier 2) | 40% | Rp 4,000,000 |
| SPV | 10% | Rp 1,000,000 |
| Manager | 5% | Rp 500,000 |
| **Total Komisi** | **55%** | **Rp 5,500,000** |
| **SITUNEO Net** | **45%** | **Rp 4,500,000** |

### TIER PARTNER:
- **Tier 1:** 30% (0-10 orders, no maintenance)
- **Tier 2:** 40% (10-25 orders, maintain 10/month)
- **Tier 3:** 50% (50-75 orders, maintain 25/month)
- **Tier MAX:** 55% (75+ orders, maintain 50/month)

### ATURAN KOMISI:
- **Beli Putus:** Commission 1x (setelah project selesai)
- **Sewa:** Commission 1x bulan pertama saja
- **Tanggungan:** Jika client stop <3 bulan, partner bayar balik

---

## 📊 BONUS ARPU (Average Revenue Per User)

### SPV BONUS (Monthly):
| ARPU | Bonus |
|------|-------|
| Rp 15M | Rp 500K |
| Rp 35M | Rp 1M |
| Rp 75M | Rp 2M |
| Rp 200M+ | Rp 10M |

### MANAGER BONUS (Monthly):
| ARPU | Bonus |
|------|-------|
| Rp 45M | Rp 1M |
| Rp 105M | Rp 2M |
| Rp 225M | Rp 3M |
| Rp 600M+ | Rp 15M |

**Cara Hitung:** Total revenue bulan ini dari semua downline = ARPU → Cek tier → Dapat bonus (akhir bulan via cron job)

---

## 🗄️ DATABASE INFO

**Total:** 85+ tables

### KEY TABLES:
- `users` - Master user (admin, manager, spv, partner, client)
- `partners` - Tier, commission, referral_code
- `spv_supervisors` - Team, ARPU, bonus
- `manager_area_managers` - Area, ARPU, bonus
- `clients` - Orders, payments
- `orders` - Order type, status, amount
- `services` - 232+ services
- `demo_requests` - 26 fields
- `commission_calculations` - Auto-calc

### CREDENTIALS:
- **Host:** localhost
- **User:** nrrskfvk_user_situneo_digital
- **Pass:** Devin1922$
- **Database:** nrrskfvk_situneo_digital

---

## 🔐 SECURITY CHECKLIST

✅ bcrypt password (cost 12)  
✅ CSRF token (all forms)  
✅ PDO prepared statements (SQL injection)  
✅ Rate limiting (5 attempts / 15 min)  
✅ Session security (httponly, secure, samesite)  
✅ Input validation (client + server)  
✅ Output encoding (htmlspecialchars)  
✅ XSS protection (CSP headers)  
✅ SSL/TLS (HTTPS only)  
✅ File upload validation (type, size)

---

## 📧 EMAIL TEMPLATES (14 jenis)

1. Welcome Email (after register)
2. Email Verification (activate account)
3. Application Received (Partner/SPV/Manager)
4. Application Approved (welcome + credentials)
5. Application Rejected (with reason)
6. Password Reset (reset link)
7. Order Confirmation (after order)
8. Payment Verified (after admin approve)
9. Project Update (status change)
10. Project Completed (ready for download)
11. Commission Earned (after order complete)
12. ARPU Bonus (monthly, if achieved)
13. Withdrawal Request (confirmation)
14. Withdrawal Processed (transfer done)

---

## 🎨 DESIGN SYSTEM

### COLORS:
- Primary Blue: #1E5C99
- Dark Blue: #0F3057
- Gold: #FFB400
- Bright Gold: #FFD700

### FONTS:
- Body: 'Inter', sans-serif
- Heading: 'Plus Jakarta Sans', sans-serif
- Mono: 'Fira Code', monospace

### FRAMEWORK:
- Bootstrap 5.3.3
- Bootstrap Icons 1.11.3
- GSAP 3.12+
- AOS 2.3+
- Canvas API
- Chart.js 4.4+

---

## 📱 RESPONSIVE BREAKPOINTS

| Size | Range | Device |
|------|-------|--------|
| xs | 0-575px | Mobile Portrait ← **PRIMARY FOCUS** |
| sm | 576-767px | Mobile Landscape |
| md | 768-991px | Tablet |
| lg | 992-1199px | Desktop |
| xl | 1200-1535px | Large Desktop |
| 2xl | 1536px+ | XL Desktop |

**PRIORITAS:**
1. Mobile (375px-767px) - **FIRST!**
2. Desktop (992px+) - **SECOND**
3. Tablet (768px-991px) - **ADAPT**

---

## ⏰ CRON JOBS (3 jobs)

1. **tier-update.php**  
   Schedule: Monthly, 1st day, 01:00 AM  
   Function: Check maintenance, upgrade/downgrade tiers

2. **arpu-calculate.php**  
   Schedule: Monthly, 1st day, 02:00 AM  
   Function: Calculate ARPU, credit bonus to balances

3. **invoice-generate.php**  
   Schedule: Monthly, 1st day, 03:00 AM  
   Function: Generate recurring invoices (sewa)

---

## 🔗 FILE STRUCTURE

```
/
├─ /public/ (Document root)
│  ├─ index.php (Entry point)
│  ├─ .htaccess (URL rewriting)
│  ├─ /assets/ (CSS, JS, images)
│  └─ /demos/ (50 demo websites)
├─ /config/ (Config files)
├─ /core/ (Core classes)
├─ /app/
│  ├─ /controllers/
│  ├─ /models/ (85+ models)
│  └─ /views/
├─ /helpers/ (Utility functions)
├─ /cron/ (Scheduled jobs)
└─ /database/ (Schema, migrations, seeds)
```

---

## 🎯 MVP (MINIMUM VIABLE PRODUCT)

**Untuk launch cepat, fokus pada:**

### CRITICAL (Must Have):
✅ Batch 1-5: Database + Core + Public + Auth + Client  
✅ Batch 8: Commission auto-calculation  
✅ Batch 10-11: Admin Dashboard (user & order management)

**TOTAL MVP:** 8 batch = 6-8 weeks

### POST-LAUNCH (Can Add Later):
- Batch 6-7: Partner & SPV Dashboard
- Batch 9: Manager Dashboard
- Batch 12-13: Demo Request + Task Board
- Batch 14: 50 Demo Websites

**💡 START SIMPLE, SCALE LATER!**

---

## 💡 TIPS & BEST PRACTICES

### 1. FOLLOW THE SEQUENCE
✅ Complete Batch 1 before Batch 2  
✅ Test after each batch  
✅ Document as you go

### 2. USE VERSION CONTROL
✅ Git commit after each feature  
✅ Meaningful commit messages  
✅ Branch for each batch

### 3. CODE QUALITY
✅ Follow PSR standards (PHP)  
✅ Consistent naming  
✅ Add comments for complex logic  
✅ Don't repeat yourself (DRY)

### 4. SECURITY FIRST
✅ Never trust user input  
✅ Always validate + sanitize  
✅ Use prepared statements  
✅ Hash passwords (bcrypt)

### 5. PERFORMANCE
✅ Optimize database queries (indexes)  
✅ Minify CSS/JS (production)  
✅ Compress images (WebP, 80% quality)  
✅ Enable caching

### 6. USER EXPERIENCE
✅ Mobile-first design  
✅ Fast loading (<3s)  
✅ Clear error messages  
✅ Smooth animations (60fps)

---

## ⚠️ COMMON PITFALLS (HINDARI!)

❌ Skipping Batch 1-2 (Foundation is critical!)  
❌ Not testing after each batch  
❌ Hardcoding values (use config)  
❌ SQL injection (use prepared statements)  
❌ XSS vulnerabilities (escape output)  
❌ Ignoring mobile users (mobile-first!)  
❌ Over-engineering (keep it simple)  
❌ No backups (backup database daily!)  
❌ Weak passwords (enforce strong passwords)  
❌ No error handling (always handle errors)

---

## 🚀 DEPLOYMENT STEPS (8 steps)

1. **Prepare package:** ZIP all files + database dump + docs
2. **Upload to server:** cPanel → public_html → Extract
3. **Setup database:** Create DB → Import schema.sql → Update config
4. **Setup email:** Create email accounts → Update config → Test SMTP
5. **Setup SSL:** Install Let's Encrypt → Force HTTPS → Test
6. **Setup cron jobs:** Add 3 cron jobs → Test execution
7. **Final testing:** Test all features → Fix issues → Monitor 24h
8. **GO LIVE!** 🎉

---

## 📞 CONTACT INFO

**Project:** SITUNEO Digital Platform  
**Company:** PT SITUNEO DIGITAL SOLUSI INDONESIA

📧 Email: vins@situneo.my.id  
📱 WhatsApp: +62 831-7386-8915  
📞 Phone: 021-8880-7229

**Office:**  
Jl. Bekasi Timur IX Dalam No. 27  
Jakarta Timur 13450, Indonesia

**Legal:**  
NIB: 20250-9261-4570-4515-5453  
NPWP: 90.296.264.6-002.000

---

## ✅ READY TO START?

✅ Read all 3 documentation files  
✅ Setup development environment  
✅ Create project timeline  
✅ Assign team members  
✅ Start with Batch 1  
✅ Follow the sequence  
✅ Test after each batch  
✅ Deploy when ready

**REMEMBER:**
- Quality > Speed
- Test > Fix > Test again
- Document as you go
- Ask when stuck
- Stay focused
- You got this! 💪

---

**🎉 GOOD LUCK!**

*Generated: 2025*
