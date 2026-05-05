---
customLayout: ".demo/layouts/content.html"
theme: prompt-to-production
transition: slideLeft
---

<div class="label label-red">Managing Cost</div>

# The Context Trap

<div class="divider" style="background: var(--p2p-red);"></div>

<div class="flex-col flex-1 gap-md" style="max-width: 90%;">
  <p style="font-size: 1.05rem;"><strong>Why Bolt.new gets expensive:</strong> your context grows with every change.</p>
  <div class="divider-full"></div>
  <div class="list">
    <div class="list-item"><div class="dot dot-red"></div><span><strong>The expanding context</strong> — To maintain consistency (like themes or UI elements), the LLM needs to track everything you’ve built so far.</span></div>
    <div class="list-item"><div class="dot dot-red"></div><span><strong>Input = Cost</strong> — As projects expand, input size balloons. 100k credits (~$0.30) per prompt for good output is acceptable.</span></div>
    <div class="list-item"><div class="dot dot-red"></div><span><strong>The tipping point</strong> — Paying 400k credits for a complex, buggy output becomes financially frustrating.</span></div>
  </div>
</div>