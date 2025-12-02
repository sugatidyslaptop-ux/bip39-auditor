# BIP-39 Auditor — The Trustless Seed Phrase Validator

https://bip39-auditor.vercel.app

The most secure, most complete, 100% client-side BIP-39 tool on the internet.

- Real SHA-256 checksum validation (no faking it)
- Real PBKDF2-SHA512 master seed derivation (with optional passphrase)
- Entropy heuristic scoring (detects weak/repeated words)
- Secure cryptographically-sound random phrase generator
- QR export for air-gapped recovery
- Zero telemetry, zero logging, zero external requests for seed data
- Works offline (save as HTML or PWA)

Everything happens in your browser. Nothing ever leaves your device.

### Why trust this tool?
- Fully open-source (you're looking at the code right now)
- No analytics, no trackers, no backend
- Uses only battle-tested libraries (bip39, pbkdf2, create-hash)
- Built for one reason: stop people from losing funds to invalid or compromised seed phrases

### Quick Demo
Try any invalid phrase → instantly rejected  
Click “Generate New Secure 24-Word Phrase” → perfectly valid BIP-39 output

### Running locally
```bash
git clone https://github.com/yourusername/bip39-auditor.git
cd bip39-auditor
npm install
npm start
