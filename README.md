# OMNIWOLF v3.0  
**The Universal Consent-Driven Red Team Platform**  

*(Imagine a massive black wolf with glowing green eyes and cryptographic chains)*

### The tool that ended the “ethical vs blackhat” debate forever.

OMNIWOLF is the world’s first **fully legal, cryptographically-verified, multi-platform red team framework** that can assess **Windows, macOS, Linux, Android, and iOS** — but **refuses to run a single command without explicit, revocable, auditable consent**.

You scan a QR code → you sign consent with Ed25519 → you become part of an authorized security test.

No malware signatures.  
No persistence without permission.  
No data leaves the device without a signed consent hash.

### Features
- Ed25519 + SHA-384 cryptographic consent (military-grade)
- Real-time QR generation with embedded signed payload
- Auto-detects and serves platform-specific assessment agents
- Full HTTPS + self-signed cert + ngrok-ready
- One-click test termination & revocation
- Live dashboard with session control
- Memory-only execution — disappears on revoke
- Built for Microsoft BlueHat, Apple Security, Black Hat Arsenal

### Demo in 30 seconds
1. `python omniwolf.py`
2. Open `https://localhost:8443`
3. Click **GENERATE CONSENT QR**
4. Scan with any phone/laptop
5. Consent → instantly appears in dashboard
6. Download your platform agent → run → connected

### Why this exists
Because the future of offensive security isn’t malware.  
It’s **consent, transparency, and unstoppable power — all in one tool**.

Open source.  
100% ethical.  
100% legal.  
100% terrifying (for the right reasons).

### Author
**Black Wolf** — 2025  
The day offensive security grew up.

### License
MIT — Use it, break it, improve it.  
Just don’t remove the wolf.

