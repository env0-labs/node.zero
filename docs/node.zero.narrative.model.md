# node.zero — Narrative Model (Draft)

## 🧠 Core Concept
Story lives in the filesystem. Files = messages, logs, objectives.

## 🗂️ Structure
- `~/missions/mission01.txt`
- `~/systems/errors.log`
- `~/users/README.txt`

## 🧠 Goal
Let players "discover" tasks through exploration, not hard-coded missions.

## 🧪 Trigger System
Opening or `cat`ting a file triggers an event.
Some files change based on player progress.

## 🎯 Example Flow
1. Player logs in
2. Finds `/objectives/start_here.txt`
3. That file mentions `nmap` to find other nodes
4. SSH into second node → reveals corrupted logs
