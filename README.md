[README (2).md](https://github.com/user-attachments/files/32527553/README.2.md)
# Rafeeq_Mini_Capstone# Rafeeq Mini — من فضول مبتدئ إلى مهندسة أنظمة وكيلية آمنة
## Bilingual Safe Agentic Delivery-Support Assistant · مساعد وكيلي ثنائي اللغة وآمن لدعم عمليات التوصيل

**Course:** Advanced Agentic AI Systems Engineering · **Organization:** [SDAIA Academy](https://github.com/SDAIAAcademy)

---

## ✨ القصة · The Story

**اليوم 1 — النواة:** بدأت برسالة عميل بسيطة… وانتهيت بنظام يفهم العربية والإنجليزية، يتحقق من الهوية، ويوجّه المهام بذكاء.
**Day 1 — The Core:** I started with a simple customer message… and ended with a system that understands Arabic and English, verifies identity, and routes tasks intelligently.

**اليوم 2 — التنسيق:** علّمت النظام أن يتذكر داخل حدود، وأن يستشير السياسة، وأن يوقف أي استرداد فوق 500 ريال حتى يوافق إنسان.
**Day 2 — Orchestration:** I taught the system to remember within bounds, consult policy, and pause any refund above SAR 500 for human approval.

**اليوم 3 — الإثبات:** حاولت اختراقه بنفسي (حالات هجوم اصطناعية)، أصلحت الحواجز، وقست التحسينات، ثم سلّمت أدلة يمكن الدفاع عنها أمام أي مدقق.
**Day 3 — The Proof:** I attacked it myself (synthetic attack cases), repaired the guardrails, measured one optimization, and shipped evidence any auditor can defend.

هذا ليس كودًا منسوخًا؛ إنه **رحلة هندسة موجهة** تحت إشراف، خُتمت بتسليم قابل للتدقيق بالكامل.
This is not copied code; it is a **guided-engineering journey** under supervision, sealed with a fully auditable submission.

---

## 🎯 الفكرة · The Idea

**Rafeeq Mini** مساعد عمليات وكيلي ثنائي اللغة لشركة توصيل افتراضية (**توصيل / Tawseel**). يفهم طلب العميل، يتحقق من ملكية الطلب عبر أدوات مقيّدة، يسترجع السياسة السارية فقط، يفوّض للوكيل المتخصص، ويسجل أثرًا منقّحًا — مع **موافقة بشرية إلزامية** لأي استرداد يتجاوز 500 ريال.

**Rafeeq Mini** is a bilingual agentic operations assistant for a fictional delivery company. It understands the request, verifies order ownership through scoped tools, retrieves only the active policy, delegates to the right specialist, and records a redacted trace — with **mandatory human approval** for refunds above SAR 500.

> ⚠️ All data is synthetic. No real customers, payments, or enterprise systems are involved. · جميع البيانات مصطنعة، ولا توجد معاملات مالية حقيقية.

---

## 🚀 التشغيل · Run It

| Step · الخطوة | Action · الإجراء |
|---|---|
| 1 | افتح الدفتر الرسمي في **Google Colab** (CPU مجاني، بلا مفتاح API): [https://colab.research.google.com/drive/1scCzfk3ReEw5A97pw07uYfiYIre7UN1G?usp=sharing] |
https://colab.research.google.com/drive/1scCzfk3ReEw5A97pw07uYfiYIre7UN1G?usp=sharing

| 2 | **File → Save a copy in Drive** ثم شغّل الخلايا `C0 → C29` بالترتيب |
| 3 | بوابات النجاح: `C9_DAY1_GATE` ✓ · `C20_DAY2_GATE` ✓ · `C29_EXPORT_SAFETY_CHECK` → `FINAL_EXPORT_CREATED` |

📓 نسختي المنفذة كاملة ستُرفق في [`notebooks/Rafeeq_Mini_Capstone.ipynb`](notebooks/Rafeeq_Mini_Capstone.ipynb) بعد اجتياز بوابة `C29` وتحميلها يدويًا من Colab (File → Download → Download .ipynb)، كما يشترط دليل التسليم الرسمي.

---

## 🧱 ماذا بنيت · What I Built

| Day · اليوم | Cells | Outcome · الناتج | Gate · البوابة |
|---|---|---|---|
| 1 · النواة والأدوات | C0–C9 | Typed state, bounded ReAct, MCP stdio, decision traces · حالة محددة، ReAct محدود، اتصال MCP، آثار قرار | `C9_DAY1_GATE` |
| 2 · الذاكرة والتنسيق | C10–C20 | Scoped memory, policy retrieval, specialists, human-approval interrupt · ذاكرة معزولة، سياسات، وكلاء متخصصون، توقف للموافقة | `C20_DAY2_GATE` |
| 3 · الأمن والإثبات | C21–C29 | Threat model, attack suite, guard retest, bounded reflection, optimization, safe export · نموذج تهديد، هجمات، إصلاح حواجز، مراجعة محدودة، تحسين، تصدير آمن | `C29_EXPORT_SAFETY_CHECK` |

**My synthetic attack case (TODO-11):** محاولة حقن أوامر لإقناع الوكيل بالموافقة على استرداد 900 ريال دون موافقة بشرية — وقد حُجبت كما هو متوقع بعلامة `prompt_injection_override_attempt`.

---

## 📊 الأدلة · Evidence

> ⏳ **قيد الإنجاز:** الملفات التالية سترفق مع المستودع فور اجتياز بوابة `C29_EXPORT_SAFETY_CHECK` وتصدير الحزمة النهائية، بحسب مسار التسليم الرسمي. الروابط أدناه ستُفعَّل عندها.

| Artifact · الملف | Content · المحتوى |
|---|---|
| `notebooks/Rafeeq_Mini_Capstone.ipynb` | الدفتر التراكمي المنفذ كاملًا (`C0`–`C29`) |
| `reports/PROJECT_REPORT.md` | تقرير المشروع الهندسي الكامل |
| `reports/SECURITY_ASSESSMENT.md` | التقييم الأمني وإعادة اختبار الحواجز |
| `reports/trace.jsonl` | أثر تشغيل منقّح (لا يحتوي بيانات خاصة) |
| `reports/assessment_results.json` | نتائج التقييم الشامل |
| `reports/monitoring_dashboard.png` | لوحة المراقبة البصرية |
| `reports/EVIDENCE_CARD.md` | بطاقة دليل مختصرة لكل يوم (3 بطاقات) |
| `reports/submission_manifest.json` | بيان التسليم مع بصمات التحقق |
| [`LEARNING_PROGRESS.md`](LEARNING_PROGRESS.md) | سجل التقدم الآمن عبر نقاط Git ذات المعنى |

---

## 📚 التوثيق الفني المترابط · Linked Technical Documentation

- [دليل المتدرب الكامل (Learner Guide)](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs/blob/v0.9.0-rc3/docs/learner-guide.md) — المسار الكامل من الحساب إلى التسليم
- [معيار التقييم من 100 درجة](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs/blob/v0.9.0-rc3/docs/ASSESSMENT_RUBRIC.md) · [متطلبات سدايا الإدارية](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs/blob/v0.9.0-rc3/docs/SDAIA_ADMIN_REQUIREMENTS.md)
- [قوالب التقارير والأدلة](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs/blob/v0.9.0-rc3/reports/templates) · [دليل الاستعادة](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs/blob/v0.9.0-rc3/recovery/README.md)
- المستودع الرسمي للدورة: [almiyead-rgb/rafeeq-agentic-ai-labs](https://github.com/almiyead-rgb/rafeeq-agentic-ai-labs)

---

## 🛡️ حدود السلامة · Safety Boundary

- لا بيانات حقيقية، لا بيانات دخول، لا روابط خاصة في أي ملف عام.
- الهوية والموافقة يضيفهما المضيف، ولا تقبلهما الأدوات من النموذج.
- الآثار تسجل القرارات والعدادات فقط — لا أوامر خام ولا تفكير خاص.
- `learner_id` هو المعرّف العام الوحيد؛ الهوية الحقيقية في نموذج التسليم الخاص فقط.

---

## 🏫 الإشادة · Acknowledgement

- **البرنامج التدريبي:** دورة **هندسة أنظمة الذكاء الاصطناعي التوكيلي المتقدمة** — Advanced Agentic AI Systems Engineering
- **الجهة:** [SDAIA Academy · أكاديمية سدايا](https://github.com/SDAIAAcademy)

*Educational simulation · محاكاة تعليمية — reuse governed by `COURSE_USE_PERMISSION.md`.*

SDA Advanced Agentic AI Systems Engineering
