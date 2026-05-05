---
customLayout: ".demo/layouts/content.html"
theme: prompt-to-production
transition: slideLeft
---

<div class="label">The Teachable Moment</div>

# Crafting the prompt

<div class="divider"></div>

<div class="grid-2 flex-1">
  <div class="flex-col gap-sm">
    <div class="label label-muted" style="margin-bottom: 0.25rem;">What you voted for</div>
    <div class="list small">
      <div class="list-item"><span class="num">Category</span><span class="muted">___________________</span></div>
      <div class="list-item"><span class="num">Audience</span><span class="muted">___________________</span></div>
      <div class="list-item"><span class="num">Feature</span><span class="muted">___________________</span></div>
      <div class="list-item"><span class="num">Twist</span><span class="muted">___________________</span></div>
    </div>
  </div>
  <div class="flex-col gap-sm">
    <div class="label" style="margin-bottom: 0.25rem;">The actual prompt</div>
    <div class="codeblock small" style="flex: 1; line-height: 1.8;">Build a <span class="accent">{category}</span> app for <span class="accent">{audience}</span>.
The one thing they need to do: <span class="accent">{feature}</span>.
Fun twist: <span class="accent">{twist}</span>.

Keep it simple: two screens max, no auth, no backend.
Use hardcoded sample data as JSON.
Tech: React + Vite + Tailwind.</div>
  </div>
</div>

<div class="takeaway">Fill in the brackets live from the audience votes. That translation — that's the skill.</div>
