auto-accepts and does discord quests for you.

accepts quests, watches videos (fakes it), spoofs playing a game, spoofs streaming, sends activity heartbeats. logs to console or a webhook.

only does one quest at a time. no nitro control quest support. this is intentional so you dont get flagged.

## setup

```
cd Vencord/src/userplugins
git clone https://github.com/xbz-seven/QuestHelper
cd ../..
pnpm build
pnpm inject
```

## settings

- `autoAcceptQuests` - auto accept new quests (default off)
- `logDestination` - Console / Webhook / Both
- `webhookUrl` - discord webhook url if using webhook logging

## how it works

listens for quest updates, auto-accepts if enabled, then spoofs whatever the quest needs. rate limited and retries on failure.

## disclaimer

for education. might break tos. dont blame me.
