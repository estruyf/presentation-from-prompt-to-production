---
theme: prompt-to-production
transition: slideLeft
---

<div class="label label-red">What Not To Do</div>

# What a bad prompt looks like

<div class="divider" style="background: var(--p2p-red);"></div>

<div class="codeblock" style="border-color: var(--p2p-amber); flex: none; margin-bottom: 0.5rem;">
"Make me an app where people can log their workouts and track progress over time. Should have a nice dashboard with charts and stats. Would be cool if friends can see each other's progress too. Maybe some kind of streak or badge system. Oh and it should work on mobile."
</div>

<div class="grid-4" style="flex: none;">
  <div class="flex-col gap-sm">
    <p class="small red" style="font-weight: 600;">No user defined</p>
    <p class="small muted">"people" — what people? That changes everything about the UI.</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small red" style="font-weight: 600;">Scope creep baked in</p>
    <p class="small muted">"friends", "badges", "streaks" — 3 features added with the word "maybe".</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small red" style="font-weight: 600;">No data model</p>
    <p class="small muted">What is a workout? The AI will guess — and you'll spend hours fixing it.</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small red" style="font-weight: 600;">"Nice" is not a spec</p>
    <p class="small muted">The AI has no reference for your taste. You will hate what it builds.</p>
  </div>
</div>
