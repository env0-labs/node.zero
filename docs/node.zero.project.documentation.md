# node.zero — Project Documentation

## 🧭 Purpose
A playable command-line learning experience built on top of `env0.core`.

## 🔧 Key Concepts
- CLI simulation with learning UX
- Missions driven by command use
- Safe failure through sandboxed systems
- File-driven narrative triggers

## 📁 Custom Layer on Core
- New commands (e.g., `mission`, `objectives`)
- Narrative triggers from filesystem
- Mission framework: file/task/goal definitions

## 🌐 Fake Network Layer
- Nodes simulate remote systems
- `nmap`, `ssh`, `ping`, etc. all fake
- No real networking — illusion through state

## 🕹️ Game Flow
1. Boot
2. Login
3. First mission appears
4. Player explores tools
5. Tasks complete by using core commands

## 🎓 Learning Mechanics
- Tool discovery through narrative
- "Errors" are teaching moments
- No punishment — focus on system literacy

> This document describes how `node.zero` extends and personalizes the underlying terminal engine.
