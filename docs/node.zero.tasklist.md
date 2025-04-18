# node.zero — Tasklist

This file tracks planned or active work specific to the `node.zero` training layer.  
Tasks here focus on game structure, learning flow, simulated commands, and player progression.

---

## 🎯 Mission Framework

- [ ] Define mission schema (objectives, triggers, progress conditions)
- [ ] Load missions from JSON or file directory
- [ ] Track mission state per user or session
- [ ] Basic UI or CLI indicators for active mission

---

## 🧠 Learning UX

- [ ] Implement sandboxed `help` system (context-aware)
- [ ] Write narrative error messages for misused commands
- [ ] Unlock tool access progressively via missions
- [ ] Log player usage for potential replay/feedback loop

---

## 💻 Fake Commands (Game Layer Only)

- [ ] `mission` — show current objectives
- [ ] `objectives` — view checklist
- [ ] `hint` — optional learning assist
- [ ] `score` or `status` — player feedback / soft gamification

---

## 🧪 Testing & Behavior

- [ ] Run full CLI flow with no missions — confirm safe fallbacks
- [ ] Simulate a single mission and trigger file-based objective
- [ ] Handle corrupted mission files gracefully

---

## 🧼 Refactors (Later)

- [ ] Split mission logic into dedicated module
- [ ] Sync mission triggers to narrative manager
- [ ] Replace hardcoded command triggers with config-based hooks

---

> All engine-level tasks live in `env0.core/docs/env.core.tasklist.md`
