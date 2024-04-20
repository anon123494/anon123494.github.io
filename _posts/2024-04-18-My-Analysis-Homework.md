---
layout: post
title: 'تمرین 2'
date: '2024-04-18'
author: Banned In Iran
katex: true
---

# همگرایی نقطه ای
ابتدا ثابت می کنیم که دنباله تابع
<span class="katex"><math><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo><mo>=</mo><mfrac><mn>1</mn><mrow><mi>n</mi><mi>x</mi><mo>+</mo><mn>1</mn></mrow></mfrac></mrow></math></span>
به تابع ثابت
<span class="katex"><math><mrow><mi>f</mi><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo><mo>=</mo><mn>0</mn></mrow></math></span>
همگرای نقطه است.

چون برای هر عدد حقیقی 
<span class="katex"><math><mrow><mi>x</mi><mo>&gt;</mo><mn>0</mn></mrow></math></span>
داریم

<span class="katex"><math display="block"><mrow><munder><mrow><mi>lim</mi><mo>⁡</mo></mrow><mrow><mi>n</mi><mo>→</mo><mo>+</mo><mi mathvariant="normal">∞</mi></mrow></munder><mi>n</mi><mi>x</mi><mo>+</mo><mn>1</mn><mo>=</mo><mo>+</mo><mi mathvariant="normal">∞</mi></mrow></math></span>

خواهیم داشت

<span class="katex"><math display="block"><mrow><munder><mrow><mi>lim</mi><mo>⁡</mo></mrow><mrow><mi>n</mi><mo>→</mo><mo>+</mo><mi mathvariant="normal">∞</mi></mrow></munder><mfrac><mn>1</mn><mrow><mi>n</mi><mi>x</mi><mo>+</mo><mn>1</mn></mrow></mfrac><mo>=</mo><mn>0</mn><mo>=</mo><mi>f</mi><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></math></span>
(تقسیم عدد  ثابت بر مثبت بی نهایت)
که همگرایی نقطه ای را ثابت می کند

# همگرایی یونیفورم نیست

برای اثبات یونیفورم نبودن همگرایی 
کافیست نشان دهیم برای یک 
<span class="katex"><math><mrow><mi>ϵ</mi><mo>&gt;</mo><mn>0</mn></mrow></math></span>
به ازای هر
<span class="katex"><math><mrow><mi>N</mi><mo>∈</mo><mi mathvariant="double-struck">N</mi></mrow></math></span>
وجود دارد 
<span class="katex"><math><mrow><mi>x</mi><mo>∈</mo><mo stretchy="false">(</mo><mn>0</mn><mo separator="true">,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></math></span>
به طوری که 

<span class="katex"><math display="block"><mrow><mrow><mo fence="true">∣</mo><msub><mi>f</mi><mi>N</mi></msub><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo><mo>−</mo><mi>f</mi><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo><mo fence="true">∣</mo></mrow><mo>=</mo><mrow><mo fence="true">∣</mo><mfrac><mn>1</mn><mrow><mi>N</mi><mi>x</mi><mo>+</mo><mn>1</mn></mrow></mfrac><mo>−</mo><mn>0</mn><mo fence="true">∣</mo></mrow><mo>=</mo><mfrac><mn>1</mn><mrow><mi>N</mi><mi>x</mi><mo>+</mo><mn>1</mn></mrow></mfrac><mo>≥</mo><mi>ϵ</mi></mrow></math></span> 

برای اثبات قرار می دهیم
<span class="katex"><math><mrow><mi>ϵ</mi><mo>=</mo><mfrac><mn>1</mn><mn>2</mn></mfrac></mrow></math></span>
.
حال برای هر عدد <span class="katex"><math><mrow><mi>N</mi></mrow></math></span>
قرار میدهیم
<span class="katex"><math><mrow><mi>x</mi><mo>=</mo><mfrac><mn>1</mn><mi>N</mi></mfrac></mrow></math></span>
که واضحا در دامنه ما است و برای آن 
داریم

<span class="katex"><math display="block"><mrow><msub><mi>f</mi><mi>N</mi></msub><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo><mo>=</mo><msub><mi>F</mi><mi>N</mi></msub><mo stretchy="false">(</mo><mfrac><mn>1</mn><mi>N</mi></mfrac><mo stretchy="false">)</mo><mo>=</mo><mfrac><mn>1</mn><mrow><mi>N</mi><mfrac><mn>1</mn><mi>N</mi></mfrac><mo>+</mo><mn>1</mn></mrow></mfrac><mo>=</mo><mfrac><mn>1</mn><mn>2</mn></mfrac><mo>≥</mo><mfrac><mn>1</mn><mn>2</mn></mfrac></mrow></math></span>

که این ثابت می کند همگرایی ما از نوع یونیفورم نیست
