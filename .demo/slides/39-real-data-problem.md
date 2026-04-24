---
customLayout: ".demo/layouts/content.html"
theme: prompt-to-production
transition: slideLeft
---

<div class="label">Concrete Evidence</div>

# The real-world data problem

<div class="divider"></div>

<p class="muted small" style="margin-bottom: 0.5rem;">Same prompt. Same app. Three platforms. All three handled their own generated sample data fine. Then a real CSV was uploaded.</p>

<div class="grid-3 flex-1">
  <div class="card card-red flex-col gap-sm">
    <h3 class="accent small">Bolt.new</h3>
    <p class="small muted">Database error on first real post. Defaulted to "paste a URL" instead of file upload.</p>
  </div>
  <div class="card card-red flex-col gap-sm">
    <h3 class="accent small">Lovable</h3>
    <p class="small muted">Could not parse real CSV on first attempt. Required follow-up prompts to fix.</p>
  </div>
  <div class="card card-amber flex-col gap-sm">
    <h3 class="accent small">Replit</h3>
    <p class="small muted">Dumped raw API response to screen. Needed one more prompt — but it was fixable.</p>
  </div>
</div>

<div class="takeaway">These tools are trained to impress you in demos. Real-world messy data is where you find the seams.</div>
