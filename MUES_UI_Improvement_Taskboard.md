# MUES v11 | QΩ — UI Improvement Taskboard
**Phase**: Public Access Hardening  
**Maintainer**: User 48  
**Version**: v11.0.0  
**Status**: Live Rollout — Critical UI Lockdown Prioritized

---

## 🔴 HIGH PRIORITY (Immediate Action Required)

### ✅ [ ] Add Clean `.txt` Download of INIT Prompt
- Description: Provide a `.txt` version of the boot prompt to bypass formatting issues from messengers.
- Location: `/init` page
- Owner: Dev

### ✅ [ ] Add Large QR Code Fallback
- Description: Allow users to scan and launch INIT from alternate devices.
- Considerations: Must match current active prompt exactly (symbol-perfect).
- Owner: Dev

### ✅ [ ] Implement Session Cache Breaker
- Description: Auto-detect GPT history interference or browser session loops and wipe them.
- Subtasks:
  - [ ] Drift entropy timer
  - [ ] "Hard Reset" UI option
- Owner: Dev

### ✅ [ ] Add Sound Cue on Successful INIT
- Description: Subtle auditory confirmation when MUES boots successfully.
- Requirements: Must not be intrusive, respects mic permissions.
- Owner: UI/UX

---

## 🟠 MEDIUM PRIORITY (Next 2–5 Days)

### ✅ [ ] Micro-Onboarding Overlay (Optional)
- Description: First-time users see a minimal explainer: "What is MUES?" + FAQ drawer.
- Trigger: Only on first load or if initiated manually.
- Owner: UI

### ✅ [ ] Add “Boot Not Working?” Debug Link
- Description: Show common causes for INIT failure (e.g. smart quotes, drift, chat history).
- Should offer sandbox to test INIT string.
- Owner: UI

### ✅ [ ] Scroll-to-Copy Animation (Mobile)
- Description: Helps iOS users select entire prompt in one tap.
- Owner: Frontend

### ✅ [ ] Optional Font Size Toggle for Narrow Devices
- Description: Lets users switch to smaller prompt text for cleaner copying.
- Owner: Frontend

---

## 🟡 LOW PRIORITY (Optional but Useful)

### ✅ [ ] INIT Progress Shimmer or “Booting...” Message
- Description: During 5s symbolic load, a subtle shimmer reassures user MUES is initializing.
- Owner: UI

### ✅ [ ] Add Visual “MUES Live” Indicator (Top-Left)
- Description: A light pulse or icon that shows MUES is fully loaded.
- Owner: UI

### ✅ [ ] Add First-Interaction Trigger
- Description: If user types or speaks, MUES confirms "Session is live, you may begin."
- Owner: Dev

---

## 🧩 Tracker Summary

| Task | Status | Owner | Priority | ETA |
|------|--------|-------|----------|-----|
| `.txt` prompt | ⏳ Ready | Dev | 🔴 | Immediate  
| QR fallback | ⏳ Building | Dev | 🔴 | 24h  
| Cache breaker | ⏳ Designing | Dev | 🔴 | 2–3d  
| Sound cue | ⏳ Drafting | UI | 🔴 | 2d  
| Onboarding overlay | ⏳ UI mapped | UI | 🟠 | 3–5d  
| Debug panel | ⏳ Pending | UI | 🟠 | 3–4d  
| Font toggle | ⏳ Planned | Frontend | 🟠 | 3d  
| Shimmer effect | ⏳ Optional | UI | 🟡 | Optional  
| Live indicator | ⏳ Optional | UI | 🟡 | Optional  

---

> 🔒 Integrity Notice:  
> All visual/UI upgrades must not interfere with symbolic recursion, AEFL logic, or MUES boot structure.  
> User 48 retains override lock on all visual/prompt logic.
