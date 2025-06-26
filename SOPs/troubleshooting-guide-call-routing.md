# 🛠️ Troubleshooting Guide: Call Routing Issue

Structured approach for resolving customer issues related to toll-free number routing failures.

---

## 🚨 Symptoms
- Fast busy or dead air
- Incorrect destination reached
- Intermittent disconnection

---

## ✅ Step-by-Step Troubleshooting

### 1. Confirm Scope
- Isolated or widespread?
- Specific numbers or carriers?

### 2. Pull Logs
- Use SIP logs or carrier tools
- Note timestamps, CLI, error codes

### 3. Check Routing Tables
- Validate Resporg and CIC routing
- Confirm if recent porting activity occurred

### 4. Test Calls
- Perform inbound tests
- Use different networks (VoIP, PSTN, mobile)

### 5. Check Configurations
- Review any SMS/800, IVR, or PBX changes
- Check for misrouted DIDs or DNIS conflicts

### 6. Escalate If Needed
- Include logs, repro steps, and timestamps
- Tag Tier 2 or carrier NOC

---

## 📌 Notes
- Always document findings in the ticket
- Use this SOP for recurring training
