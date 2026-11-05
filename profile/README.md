# AgentDrive

**Open-source bridge between AI chat agents and the Tesla Fleet API.**

AgentDrive lets an AI assistant check on and control your own Tesla through the official Tesla Fleet API, using swappable bot adapters (`grokbot`, `muse`, and a `template` for adding your own).

- 🔋 Vehicle status: battery, charging, locks, doors, tyre pressures, climate
- 🔑 Signed vehicle commands via Tesla virtual keys (flash lights, honk, lock/unlock, and more)
- 🩺 Health checks and token refresh
- 🔄 Self-updating from the public repo; your private config stays in `~/.agentdrive`
- 🌍 Works with Tesla Fleet API in North America, Europe and Asia-Pacific (China not supported)

### Everyday commands

Ask your agent to run these, or run them yourself:

```bash
agentdrive check    # Read-only status check (never wakes the car)
agentdrive update   # Update to the latest version, keeps your private config
```

**Links**
- Repository: https://github.com/agentdrive-dev/agentdrive
- Website: https://agentdrive-dev.github.io/agentdrive/ (full installation guide)
- Issues: https://github.com/agentdrive-dev/agentdrive/issues
- Contact: agentdrivedev@gmail.com

🙏 Thanks to [MuseDrive](https://github.com/ukhhh/musedrive) for the original idea.

> AgentDrive is an independent community project and is not affiliated with or endorsed by Tesla, Inc. Use at your own risk.
