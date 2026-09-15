# AI Reasoning Overview (Updated Sep 2026)

## Tren Utama Penalaran AI 2025–2026

1. **Test-Time Scaling** — Memberi lebih banyak compute saat inference (bukan hanya training).
2. **Tree / Graph of Thoughts + MCTS** — Pencarian berstruktur.
3. **Reflexion & Self-Refine** — Penalaran yang mengkritik dan memperbaiki diri.
4. **ReAct + Tool Use** — Penalaran saling terkait dengan aksi/tool.
5. **Efficient Reasoning** — Chain-of-Thought lebih pendek tapi tetap akurat.
6. **Reasoning Models** (DeepSeek-R1 style) — Model dilatih khusus untuk berpikir panjang dengan RL.

## Arsitektur Penalaran Penting

### Reasoning & Reflection
- Reflection (Generate → Critique → Refine)
- Reflexion (Verbal reflections in episodic memory)
- Chain-of-Verification (CoVe)
- Self-Discover
- Constitutional AI

### Sampling & Search
- Self-Consistency (Majority vote)
- Tree of Thoughts (Beam search over thoughts)
- LATS (MCTS with reward)
- Graph of Thoughts

### Tools & Actions
- ReAct (Thought → Action → Observation)
- Plan-Execute-Verify
- Tool Use + Planning

Sumber utama: all-agentic-architectures, Awesome-Agentic-Reasoning, awesome-reasoning-models-theory.
