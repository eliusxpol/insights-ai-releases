# Claude Control Center Releases

Auto-update feed for Claude Control Center via Sparkle.

## Setup

1. Generate EdDSA keys: `./Sparkle/bin/generate_keys`
2. Sign release with: `./Sparkle/bin/sign_update ClaudeControlCenter.zip`
3. Update appcast.xml with version, signature, and file size
4. Create GitHub release and upload .zip
