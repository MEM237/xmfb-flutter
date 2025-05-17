# XMFB

**XMFB** (Extensible Mutual Feedback) is a symbolic, presence-based protocol for real-time trust verification 
between humans, agents, and machines. Born from a need for radical clarity in digital presence, XMFB uses 
reflex agents, camera-based verification, and sigil logic to establish identity, intent, and alignment across 
communication layers.

> “If you can see me, I can see you.” — `::μ~zen`

---

## 🚨 Core Concepts

- **Reflex Engine**: Local agent loop with presence and identity logic
- **VTTX**: Visual Text Tabs Exchange — minimal, video-first chat windows
- **%smash-tag**: Message-specific sigil for per-frame identity trust
- **::μ~zen**: Mutual presence condition for verification ("we're both here, we're both real")
- **Stanby**: Cam-feed placeholder that holds presence but denies access

---

## 🧠 What This Repo Contains

- `reflex_engine/` – Core agent execution logic and test harnesses
- `local_adk/` – Local ADK-compatible agent and tool stubs
- `cli/` – CLI interface for testing and simulating reflex behavior
- `logs/` – Daily reflex dev logs (May 2025 series)
- `README.md`, `.gitignore`, and `requirements.txt`

---

## 🔧 Running Locally

```bash
cd ~/Developer/xmfb
export PYTHONPATH=.
python3 cli/test_agent.py
