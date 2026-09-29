---
layout: page
title: Accessibility Statement
permalink: /accessibility/
---
{% comment %}
  Accessibility statement (הצהרת נגישות), English + Hebrew.
  Update "last reviewed" whenever the site is checked again.
{% endcomment %}
<div class="page-hero">
  <div class="page-hero-inner">
    <h1>Accessibility Statement</h1>
  </div>
</div>

<div class="section a11y-statement">
  <div class="about-body">
    <p>The Solav Biomechanical Interfaces Group (SoBIG) at the Technion wants this website to be usable by everyone, including people with disabilities. The site was built to meet the Israeli Standard <strong>IS 5568</strong>, which is based on the international <strong>WCAG 2.1</strong> guidelines at level <strong>AA</strong>, as required by the Equal Rights for Persons with Disabilities (Service Accessibility Adaptations) Regulations, 2013.</p>

    <h2 class="topic-subhead">What we did</h2>
    <ul>
      <li>Text and background colours meet the minimum contrast ratio of 4.5:1.</li>
      <li>All menus and links can be used with the keyboard, and keyboard focus is clearly visible.</li>
      <li>A “Skip to main content” link appears as the first item for keyboard and screen-reader users.</li>
      <li>Images have text descriptions; decorative images are hidden from screen readers.</li>
      <li>The moving background video on the home page can be paused, and stops automatically when your device asks for reduced motion.</li>
      <li>Pages work on phones and tablets and can be zoomed to 200% without losing content.</li>
      <li>Email addresses are clickable links, and every page shows our contact details.</li>
    </ul>

    <h2 class="topic-subhead">Known limitations</h2>
    <ul>
      <li>Some older news items include scanned magazine pages in Hebrew; their text is not fully available as page text.</li>
      <li>Research videos do not yet have captions; a short text description is given next to each video.</li>
      <li>Links to publishers, GitHub and other external websites lead to content we do not control.</li>
    </ul>

    <h2 class="topic-subhead">Contact for accessibility</h2>
    <p>If you find something on this site that is hard to use, or you need information in another format, please contact us and we will do our best to help:</p>
    <ul>
      <li>Accessibility contact: Prof. Dana Solav</li>
      <li>Email: {% include email.html address=site.email %}</li>
      <li>Phone: {% for p in site.phones %}{{ p.label }} <a href="tel:{{ p.number | remove: '-' }}">{{ p.number }}</a>{% unless forloop.last %}, {% endunless %}{% endfor %}</li>
  <li>Address: {{ site.address }}</li>
</ul>
<p>You can also contact the Technion Accessibility Coordinator:</p>
<ul>
  <li>Dikla Nachman</li>
  <li>Phone: <a href="tel:+972733781956">+972-73-378-1956</a></li>
  <li>Email: {% include email.html address="adminlogistic@technion.ac.il" %}</li>
</ul>
    <p class="a11y-date">This statement was last reviewed in September 2026.</p>
  </div>

  <hr class="divider" style="margin: 48px 0 40px;" />

  <div class="about-body" lang="he" dir="rtl">
    <h2 class="section-title">הצהרת נגישות</h2>
    <p>קבוצת המחקר Solav Biomechanical Interfaces Group (SoBIG) בטכניון רואה חשיבות רבה בכך שאתר זה יהיה נגיש לכלל המשתמשים, כולל אנשים עם מוגבלות. האתר הונגש בהתאם לתקן הישראלי <strong>ת״י 5568</strong>, המבוסס על הנחיות <strong>WCAG 2.1</strong> ברמה <strong>AA</strong>, כנדרש בתקנות שוויון זכויות לאנשים עם מוגבלות (התאמות נגישות לשירות), התשע״ג–2013.</p>

    <h3 class="topic-subhead">מה עשינו</h3>
    <ul>
      <li>ניגודיות הצבעים בין הטקסט לרקע עומדת ביחס המינימלי של 4.5:1.</li>
      <li>ניתן להפעיל את כל התפריטים והקישורים באמצעות המקלדת, והמיקוד מסומן בבירור.</li>
      <li>קישור „דילוג לתוכן הראשי” מופיע ראשון עבור משתמשי מקלדת וקוראי מסך.</li>
      <li>לתמונות יש תיאור טקסטואלי; תמונות עיצוביות מוסתרות מקוראי מסך.</li>
      <li>ניתן לעצור את וידאו הרקע בעמוד הבית, והוא נעצר אוטומטית כאשר המכשיר מבקש להפחית תנועה.</li>
      <li>האתר מותאם לטלפונים ולטאבלטים וניתן להגדילו עד 200% ללא אובדן תוכן.</li>
    </ul>

    <h3 class="topic-subhead">מגבלות ידועות</h3>
    <ul>
      <li>חלק מהידיעות הישנות כוללות סריקות של כתבות מעיתונים, שהטקסט שלהן אינו זמין במלואו כטקסט.</li>
      <li>לסרטוני המחקר עדיין אין כתוביות; לצד כל סרטון מופיע תיאור טקסטואלי קצר.</li>
      <li>קישורים לאתרים חיצוניים (הוצאות לאור, GitHub ועוד) מובילים לתוכן שאינו בשליטתנו.</li>
    </ul>

    <h3 class="topic-subhead">פנייה בנושא נגישות</h3>
    <p>נתקלתם בקושי בשימוש באתר, או שאתם זקוקים למידע בפורמט אחר? נשמח לעזור:</p>
    <ul>
      <li>אחראית נגישות: פרופ׳ דנה סולב</li>
      <li>דוא״ל: {% include email.html address=site.email %}</li>
      <li>טלפון: {% for p in site.phones %}<span dir="ltr">{{ p.number }}</span>{% unless forloop.last %}, {% endunless %}{% endfor %}</li>
  <li>כתובת: בניין ליידי דייוויס 103, קריית הטכניון, חיפה 3200003</li>
</ul>
<p>ניתן לפנות גם לרכזת הנגישות של הטכניון:</p>
<ul>
  <li>דקלה נחמן</li>
  <li>טלפון: <a href="tel:+972733781956" dir="ltr">073-378-1956</a></li>
  <li>דוא״ל: {% include email.html address="adminlogistic@technion.ac.il" %}</li>
</ul>
    <p class="a11y-date">ההצהרה עודכנה לאחרונה בספטמבר 2026.</p>
  </div>
</div>
