---
customLayout: ".demo/layouts/content.html"
theme: prompt-to-production
transition: slideLeft
---

<div class="label">The Skill</div>

# The prompt is the skill

<div class="divider"></div>

<div class="grid-2 flex-1">
  <div class="flex-col gap-sm">
    <div class="label label-red" style="margin-bottom: 0.25rem;">Vague</div>
    <div class="codeblock" style="border-color: var(--p2p-red); color: var(--p2p-muted); flex: 1;">
"Build me a habit tracker app with a nice UI and some stats"
    </div>
  </div>
  <div class="flex-col gap-sm">
    <div class="label label-green" style="margin-bottom: 0.25rem;">Structured</div>
    <div class="codeblock" style="border-color: var(--p2p-green); flex: 1;">
"Build a React + Vite habit tracking app for busy professionals. Core entities: Habit (name, frequency, streak), DailyLog (date, completed). Screens: dashboard with today's habits, habit detail with 30-day history. Mobile-first. No auth in v1."
    </div>
  </div>
</div>

<div class="takeaway">The prompt is the skill. Not the generation — <strong>the prompt.</strong></div>
