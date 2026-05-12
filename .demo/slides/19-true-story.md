---
theme: prompt-to-production
transition: slideLeft
---

<div class="label label-red">True Story</div>

# It worked. Until I looked.

<div class="divider" style="background: var(--p2p-red);"></div>

<div class="grid-2 flex-1">
  <div class="card flex-col gap-sm">
    <div class="label label-muted">What happened</div>
    <div class="list small" style="margin-top: 0.25rem;">
      <div class="list-item"><div class="dot dot-muted"></div><span>Colleague from marketing, zero dev background</span></div>
      <div class="list-item"><div class="dot dot-muted"></div><span>Used Claude to build a food-ordering app</span></div>
      <div class="list-item"><div class="dot dot-muted"></div><span>App worked great — team loved it</span></div>
      <div class="list-item"><div class="dot dot-muted"></div><span>Deployed it to a public GitHub repo</span></div>
    </div>
  </div>
  <div class="card card-red flex-col gap-sm">
    <div class="label label-red">What I found</div>
    <div class="list small" style="margin-top: 0.25rem;">
      <div class="list-item"><div class="dot dot-red"></div><span>API keys in plain text</span></div>
      <div class="list-item"><div class="dot dot-red"></div><span>Bank account details hardcoded</span></div>
      <div class="list-item"><div class="dot dot-red"></div><span>Credentials visible to anyone on the internet</span></div>
      <div class="list-item"><div class="dot dot-red"></div><span>Zero .gitignore, zero .env, zero secrets management</span></div>
    </div>
  </div>
</div>

<div class="takeaway" style="background: var(--p2p-red-dim); border-color: var(--p2p-red);">AI can write code. It can't think about consequences.</div>
