# Orbit for macOS

This repository distributes **app-only Orbit releases** for Intel and Apple silicon Macs running macOS 14 or later.

Orbit is a native workspace for multi-provider AI conversations and autonomous bots, with individual PIN profiles, shared provider connections, usage allowances, and configurable safety checks.

## Install or update

Download the application ZIP from [Releases](https://github.com/cporter202-cyber/orbit-updates/releases). Quit Orbit, unzip it, and place `Orbit.app` in your Applications folder. For an existing installation, replace only the application. Keep the existing workspace and Keychain records; do not import an old workspace transfer again.

Updater-enabled versions include **Check for Updates**. Updates use Sparkle with signed archives and a signed update feed. This prototype is locally signed and is not Apple-notarized; normal macOS opening and Keychain authorization prompts may apply.

## Your setup stays on your Mac

These releases contain application code and public resources. They do not include API keys, OAuth grants, PIN records, profiles, conversations, bots, workspace files, usage history, or encrypted transfers. App data and provider credentials remain separate from the application bundle.

Each release publishes only its application ZIP, `appcast.xml`, and `SHA256SUMS.txt`. The private update-signing key is not stored in this repository or in the app.
