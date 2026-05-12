---
theme: prompt-to-production
transition: slideLeft
---

<div class="label label-green">What To Do Instead</div>

# What a good prompt looks like

<div class="divider" style="background: var(--p2p-green);"></div>

<div class="codeblock" style="border-color: var(--p2p-green); flex: none; margin-bottom: 0.5rem;">
"Build a ride tracker for cyclists who currently log rides in a notebook. Data model: a Ride has a date, distance (km), duration (minutes), and route name. One screen to add a ride, one to view history as a list. No social features, no badges, no charts. Web only, desktop-first."
</div>

<div class="grid-4" style="flex: none;">
  <div class="flex-col gap-sm">
    <p class="small green" style="font-weight: 600;">Specific user</p>
    <p class="small muted">Intermediate weightlifters — the AI now knows the UI feel.</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small green" style="font-weight: 600;">Scope bounded</p>
    <p class="small muted">"No social features, no badges" — explicit non-goals stop scope creep.</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small green" style="font-weight: 600;">Data model defined</p>
    <p class="small muted">Workout → Exercises → Sets with reps and weight in kg. No guessing.</p>
  </div>
  <div class="flex-col gap-sm">
    <p class="small green" style="font-weight: 600;">Platform decided</p>
    <p class="small muted">"Web only, desktop-first" — one platform, one layout. No wasted work.</p>
  </div>
</div>
