# אביהוא אליהו
מפתח Full-Stack ו-AI · מערכות SaaS מקצה לקצה: אפיון, פיתוח, סליקה, דיפלוי.

**סטאק:** Next.js · TypeScript · Supabase · Prisma · PostgreSQL · Python · Claude API · Inngest · Stripe · Railway/Vercel

---

## מקרי בוחן

### Salezy — ניתוח שיחות מכירה בעברית
הבעיה: מנהלי מכירות מקליטים שיחות ולא יודעים מה באמת קרה בהן.
מה נבנה: מערכת שמעלה הקלטה ומקבלת ניתוח מלא — פרופיל DISC של הלקוח, סקורקרד למשווק עם ציטוטים מהשיחה, ציר שלבים, תוכנית אימון שבועית וזיהוי מגמות לאורך היסטוריית השיחות.
איך: צינור אסינכרוני ב-Inngest (תמלול → ניתוח → סינתזה → ניקוד), ניתוח ב-Claude עם פלט מובנה ומאומת ב-Zod. RLS על כל טבלה, CSP ללא unsafe-inline, OTP מותאם, WCAG 2.1 AA.
סטאק: Next.js 16 · React 19 · Supabase · Inngest · OpenAI · Claude
🔗 https://salezy.vercel.app
קוד: https://github.com/tchvut1221-ops/salezy

### Freight Invoice Auditor — אודיט חשבוניות שילוח
הבעיה: יבואנים משלמים על חשבוניות הובלה ימית בלי יכולת לבדוק אם החיוב תואם את התעריף שסוכם.
מה נבנה: העלאת PDF, פרסור שורות החשבונית, התאמה מול הסכם התעריפים ב-Python, ודוח חריגות עם סכום החיסכון. נבדק על חשבונית אמיתית: 7 חריגות ו-567$ חיסכון בקריאה אחת.
סטאק: Next.js · Supabase · Inngest · Python
🔗 https://freight-auditor-six.vercel.app

### Yakir Academy — פלטפורמת LMS
הבעיה: מכירת קורסים דיגיטליים דורשת חנות, הרשאות גישה ווידאו מוגן — לא רק דף נחיתה.
מה נבנה: מערכת קורסים מלאה עם תשלום חד-פעמי, הרשאות ברמת השורה, ניהול שיעורים וצפייה מוגנת.
סטאק: Next.js 16 · Prisma · PostgreSQL · Railway

---

## פרויקטים נוספים

**Zchutcha** — פלטפורמה לנפגעי תאונות דרכים. תחום רגולטורי עם דרישות אבטחה ונגישות גבוהות; 70 תיקוני אבטחה ועיצוב לפני עלייה לאוויר. Next.js · Supabase · Inngest · Claude

**GovMatch (US)** — התאמת מענקים לפארמה וביוטק. אודיט אבטחה מלא, WCAG 2.1 AA, אנגלית.

**Master Business OS** — פלטפורמת קואוצ'ינג עסקי דו-לשונית (ערבית/אנגלית) לשוק המזרח-התיכון, RTL וערבית אמיתית, AI Plan Builder. Next.js 16 · Multi-tenant

**אוטומציות וסוכני AI** — בוטים, אינטגרציות Stripe, Resend, MetaApi ו-Voicenter, סנכרוני מערכות, בדיקות E2E בכל מסירה.

---

## כלים ותשתית
`WhisperX on Runpod` — עובד Serverless לתמלול ודיאריזציה.
🔗 https://github.com/tchvut1221-ops/runpod-whisperx-
🔗 https://github.com/tchvut1221-ops/runpod-worker-whisper-diarization

---

קודם של פרויקטי לקוחות נמצא בריפו פרטי. זמין להדגמה בפגישה.

📫 tchvut1221@gmail.com · 054-4837578
