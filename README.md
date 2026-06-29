<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anis El Jijli - وسيط ألعاب معتمد 🎮</title>
    <style>
        :root {
            --bg-color: #0b0f19;
            --card-bg: #141a29;
            --primary-neon: #00d2ff;
            --accent-gold: #f59e0b;
            --text-main: #ffffff;
            --text-muted: #94a3b8;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            text-align: center;
            padding: 20px 10px;
            margin: 0;
        }

        .container {
            max-width: 480px;
            margin: 0 auto;
        }

        /* بروفايل المتجر */
        .profile-container {
            margin-top: 25px;
            margin-bottom: 25px;
        }

        .profile-img {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            border: 3px solid var(--primary-neon);
            box-shadow: 0 0 25px rgba(0, 210, 255, 0.35);
            object-fit: cover;
        }

        h1 { font-size: 26px; margin: 12px 0 5px 0; color: #fff; font-weight: 800; }
        
        .badge {
            display: inline-block;
            background: linear-gradient(45deg, #00d2ff, #0066ff);
            color: #fff;
            padding: 5px 14px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: bold;
            margin-bottom: 12px;
        }
        
        .bio { color: var(--text-muted); font-size: 15px; line-height: 1.6; margin: 0 auto 30px auto; max-width: 90%; }

        /* الأقسام */
        .section-title {
            font-size: 17px;
            color: var(--primary-neon);
            text-align: right;
            padding-right: 10px;
            margin-bottom: 15px;
            border-right: 3px solid var(--primary-neon);
            font-weight: bold;
        }

        .services-grid {
            background-color: var(--card-bg);
            border-radius: 16px;
            border: 1px solid #1e293b;
            padding: 15px;
            margin-bottom: 25px;
            text-align: right;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .service-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid #1e2942;
        }
        .service-item:last-child { border-bottom: none; }
        .service-name { font-weight: 600; font-size: 15px; display: flex; align-items: center; gap: 8px; }
        .service-price { color: var(--accent-gold); font-weight: bold; font-size: 14px; background: rgba(245, 158, 11, 0.1); padding: 3px 8px; border-radius: 6px; }

        /* أزرار الروابط */
        .link-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #141a29 0%, #1e293b 100%);
            color: white;
            text-decoration: none;
            padding: 16px;
            margin-bottom: 15px;
            border-radius: 14px;
            font-weight: bold;
            font-size: 16px;
            border: 1px solid #2e3d52;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .link-btn:hover {
            transform: translateY(-3px);
            border-color: var(--primary-neon);
            box-shadow: 0 8px 25px rgba(0, 210, 255, 0.25);
        }

        .btn-whatsapp {
            background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
            color: #fff;
            border: none;
        }
        .btn-whatsapp:hover {
            box-shadow: 0 8px 25px rgba(56, 239, 125, 0.35);
        }

        .btn-vouch {
            background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
            color: #000;
            border: none;
        }
        .btn-vouch:hover {
            box-shadow: 0 8px 25px rgba(245, 158, 11, 0.35);
        }

        /* قسم التقييمات */
        .reviews-box {
            background-color: var(--card-bg);
            border-radius: 16px;
            border: 1px solid #1e293b;
            padding: 20px;
            margin-top: 30px;
            text-align: center;
        }
        .reviews-box h3 { margin-top: 0; color: var(--accent-gold); font-size: 18px; }
        .placeholder-text { color: var(--text-muted); font-size: 14px; font-style: italic; }

    </style>
</head>
<body>

    <div class="container">
        
        <!-- بروفايل المتجر -->
        <div class="profile-container">
            <!-- ربط الصورة الشخصية المرفوعة بدقة عالية -->
            <img src="image.png" alt="Anis El Jijli" class="profile-img" onerror="this.src='https://via.placeholder.com/130/00d2ff/ffffff?text=Anis'">
            <h1>Anis El Jijli 🎮</h1>
            <span class="badge">وسيط ألعاب معتمد وموثوق 💯</span>
            <p class="bio">الوسيط المعتمد لشحن وبيع حسابات eFootball و Free Fire بأمان تام. نوفر أيضاً خدمات زيادة المتابعين وبيع الاشتراكات بأفضل الأسعار في السوق.</p>
        </div>

        <!-- قسم الخدمات والأسعار المتوفرة -->
        <div class="section-title">🛒 خدماتنا المتوفرة حالياً</div>
        <div class="services-grid">
            <div class="service-item">
                <span class="service-name">⚽ وساطة وتأمين حسابات eFootball</span>
                <span class="service-price">آمن 100%</span>
            </div>
            <div class="service-item">
                <span class="service-name">🔥 وساطة وتأمين حسابات Free Fire</span>
                <span class="service-price">ضمان تام</span>
            </div>
            <div class="service-item">
                <span class="service-name">📈 زيادة متابعين (جميع المنصات)</span>
                <span class="service-price">أسعار تنافسية</span>
            </div>
            <div class="service-item">
                <span class="service-name">💎 بيع الاشتراكات الرقمية المتنوعة</span>
                <span class="service-price">تسليم فوري</span>
            </div>
        </div>

        <!-- أزرار التواصل والروابط -->
        <div class="section-title">🔗 الروابط الرسمية والتواصل</div>
        
        <!-- رابط التوثيق -->
        <a href="https://www.facebook.com/share/p/17hBkMc95o/?mibextid=wwXIfr" class="link-btn btn-vouch" target="_blank">📜 إضغط هنا لرؤية منشور التوثيق والضمان</a>

        <!-- رابط الفيسبوك -->
        <a href="https://www.facebook.com/share/14fa29XJ8An/?mibextid=wwXIfr" class="link-btn" target="_blank">📱 تابع صفحتنا الرسمية على فيسبوك</a>
        
        <!-- رابط الواتساب المباشر برقمك المرفق -->
        <a href="https://wa.me/213797310724" class="link-btn btn-whatsapp" target="_blank">💬 تواصل معي مباشرة عبر الواتساب (0797310724)</a>

        <!-- مكان ربط سيستم التقييمات لاحقاً -->
        <div class="reviews-box">
            <h3>⭐ آراء وتقييمات زبائننا</h3>
            <p class="placeholder-text">ارفع هذا الملف على Netlify أولاً، ثم سنقوم بربط نظام التقييم بالنجوم الحي هنا مباشرة ⚡</p>
        </div>

    </div>

</body>
</html>
