---
layout: ~/layouts/MainLayout.astro
setup: |
    import Button from '../../components/Button.astro'
    import ContributorList from '../../components/ContributorList.astro'
    import PackageManagerTabs from '~/components/tabs/PackageManagerTabs.astro'
title: باشر بالبدأ
dir: rtl
---
#### ما هو أسترو؟

أسترو هو إطار عمل متكامل لإنشاء المواقع بشكل أسرع، لتركز على محتوى الموقع أكثر.

#### أهم المميزات

* **Component Islands (جُزر المكونات)**: هو أسلوب جديد في تصميم وتطوير صفحات الويب لإنشاء مواقع سريعة.

* **مبدأ Server-first API**: محتوى مُصير مسبقًا على جهة السيرفر، يصل لمستخدمي موقعك.

* **صفر-جافاسكربت افتراضيًا**: لا يضيف أسترو ملفات جافاسكربت تُبطئ تحميل صفحتك.

* **جاهز للنشر على الحافة**: تستطيع نشر موقعك على خدمات الحوسبة الحافية (edge runtime) مثل Deno أو Cloudflare.

* **قابلية التخصيص**: Tailwind, MDX, وغيرها الكثير... متاحة لتختار بينها وتدمجها مع موقعك.

* **محايد لإطارات عمل الواجهات**: استخدم أي أطار عمل تفضله React, Preact, Svelte, Vue, Solid, Lit وغيرها.

## جرب أسترو من على متصفحك

من خلال [astro.new](https://astro.new/) تستطيع اختيار قالب من بين عشرات القوالب المتوفرة لتبدا تجربتك. إلعب وجرب أسترو بشكل كامل من على متصفحك!

<div style="display: flex; flex-wrap: wrap; gap: 0.5rem;">
    <Button href="https://astro.new/basics?on=stackblitz">تجربة سريعة!</Button>
    <Button variant="outline" href="https://astro.new/">تفقد القوالب المتوفرة ←</Button>
</div>

## أبدأ مشروعك الاول مع أسترو

<PackageManagerTabs>
  <Fragment slot="npm">
  ```shell
  # أنشئ مشروع جديد عبر npm
  npm create astro@latest
  ```
  </Fragment>
  <Fragment slot="pnpm">
  ```shell
  # أنشئ مشروع جديد عبر pnpm
  pnpm create astro@latest
  ```
  </Fragment>
  <Fragment slot="yarn">
  ```shell
  # أنشئ مشروع جديد عبر yarn
  yarn create astro
  ```
  </Fragment>
</PackageManagerTabs>

تصفح الدليل [خطوات التثبيت](/ar/install/auto/) لتأخذ نظرة كاملة عن كيفية تثبيت أسترو خطوة بخطوة، عبر مُدير الحزم الذي تفضل استخدامه.


## تعلم أسترو

طَالع الأمثلة، لأهم المفاهيم الأساسية في أسترو

📚 [أنشئ أول صفحة](/ar/core-concepts/astro-pages/) في موقعك.

📚 أقرأ أكثر عن [هيكل تصميم مشاريع](/ar/core-concepts/project-structure/) أسترو.

📚 تعلم أكثر عن [file-based routing](/ar/core-concepts/routing/) في أسترو.

*... تفقد التوثيق الكامل للـ API التي يوفرها أسترو عبر خانة  **مراجع** أعلى الصفحة.*

## أبحر مع أسترو

🧰 أبدأ مشروعك القادم باستخدام إحدى [القوالب المبنية مسبقًا](https://astro.build/themes/).

🧰 
خصص موقعك، عبر عشرات الإضافات التي يوفرها أسترو ومجتمعه، [تصفح الإضافات](https://astro.build/integrations/).

🧰 ألهم نفسك وغذي بصرك عبر زيارة صفحة [معرض المشاريع](https://astro.build/showcase/) التي تمت عبر أسترو.

*... تفقد [دليل التعامل مع الإضافات](/ar/guides/integrations-guide/)*.

## انضم إلى المجتمع

انضم إلى مجتمع [أسترو على ديسكورد](https://astro.build/chat/) للمشاركة، والحصول على المساعدة من مجتمعنا النشط والودود.

💬 رحب، وعرف بنفسك على قناة `#introduce-yourself`!

💬 أطرح أسئلتك على فريق المساعدة في قناة `#support-threads`!

💬 شاركنا أعمالك التي صنعتها عبر أسترو على قناة `#showcase`!

## طالع أكثر

[مدونة أسترو](https://astro.build/blog/)

[سجل تغيرات أسترو](https://github.com/withastro/astro/blob/main/packages/astro/CHANGELOG.md)

[دليل الترقية بين الإصدارات](/ar/migrate/)

## المساهمة

أنت تُطالع هذا التوثيق بفضل كل هؤلاء الذين ساهموا، [انضم إلينا في GitHub!](https://github.com/withastro/docs)

<ContributorList githubRepo="withastro/docs" />
