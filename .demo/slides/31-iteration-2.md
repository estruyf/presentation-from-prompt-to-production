---
customLayout: ".demo/layouts/content.html"
theme: prompt-to-production
transition: slideLeft
---

<div class="label">Iteration 2 of 3</div>

# Fix a UX issue

<div class="divider"></div>

<div class="flex-col flex-1 gap-md mt-4">
  <div>
    <div class="label label-muted" style="margin-bottom: 0.3rem;">Prompt</div>
    <div class="codeblock">"The layout feels cramped and breaks on mobile devices. Fix the spacing on the main screen so items stack cleanly below 768px. Keep the desktop layout unchanged."</div>
  </div>
  <div>
    <div class="label label-muted" style="margin-bottom: 0.3rem;">What to narrate</div>
    <div class="list small">
      <div class="list-item"><div class="dot"></div><span>Does it understand responsive design or just apply class names?</span></div>
      <div class="list-item"><div class="dot"></div><span>Did it test on both breakpoints or just fix what it could see?</span></div>
      <div class="list-item"><div class="dot"></div><span>Did the fix introduce regressions elsewhere?</span></div>
      <div class="list-item"><div class="dot"></div><span>Would you approve this in a PR?</span></div>
    </div>
  </div>
</div>
