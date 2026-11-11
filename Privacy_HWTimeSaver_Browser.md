# HWTimeSaver Browser: Privacy Policy

Last updated: 11 November 2026

HWTimeSaver Browser is a browser extension for Hero Wars Alliance. It helps your guild with guild wars, the Global Championship and guild trainings, and can send game data to the HWTimeSaver service. This policy covers the Firefox and Chrome versions. HWTimeSaver is not affiliated with the makers of Hero Wars Alliance.

## Contact us:

[https://discord.gg/y4hsTBNn8N]

## What the extension reads

The extension runs on `hero-wars-alliance.com` pages and reads the game's own requests and answers. It keeps only these calls: your teams, your heroes, titans and talismans, the guild war and championship logs, your guild's trainings and member list, the Guild Clash registration and the Global Championship map, and your player ID from the game's requests. It does not read other websites or your browsing history.

## What is sent to our server, and when

All data goes over HTTPS to `open-api.hwtimesaver.com`.

| Data | When it is sent | Why |
|---|---|---|
| Discord user ID and API token | With each request, once you have entered them | To identify your account and check your access |
| A public device key, a device ID and a signature | When a browser is registered and with each request | To limit a token to registered browsers |
| Your heroes and titans: power, worn talisman, relic level | Only when you press **Import heroes** | To plan teams with your real heroes |
| Guild war and championship fights: replay ID, time, teams, talismans, relics, power, result | Only when you press **Feed the AI** | To feed your guild's database and train the AI and award Intel Points to your guild |
| Guild training fights: replay ID, time, teams, talismans, relics, power, result | Only when you press the **Guild trainings** button | To feed your guild's database and train the AI and award Intel Points to your guild |
| Arena fights from your arena battle log: replay ID, time, teams, talismans, relics, power, result | Only when you press **Sync Arena** | To feed your guild's database and train the AI and award Intel Points to your guild |
| Your own training fights from Beat Assistant: replay ID, time, training title, teams, talismans, relics, power, result | Only when you press the send button in **Beat Assistant** | To feed your guild's database and train the AI and award Intel Points to your guild. Unlike the fights above, they are stored with your Discord user ID, so you can have them deleted |
| The defense of the guild you fight against in the Global Championship or the Guild War: each building and position with its teams, talismans, relics and power (no player names) | Only when you press **Preload GC** or **Preload GW** in the Tactic Assistant app | To prepare your guild's attacks, like the bot's preload of screenshots |
| Guild Clash registration: the event, and for each member of your guild their game ID, name, whether they registered, lane, team power and boosters | Only when you press the **Guild Clash** button | To show your guild's registration on Discord |
| The text of a database search (hero names, power) and the talismans and relic levels you pick | Only when you press **Search** in the Database app | To find counters in your guild's database and from the AI, like the bot's /db command |
| A screenshot of the game tab | Only when you press **Beat** after taking a screenshot | The bot's screenshot readers tell the extension the type of the screen and its teams (heroes, power, talismans, relics). The screenshot is kept on our server to improve the readers; it is not posted anywhere |
| Global Championship map: both guilds' buildings and their state, defenders, attackers, teams, points and tries, the player names and game IDs of both guilds, the enemy guild's name, the officers' orders, and the changes since your last send | Only when you press the **Championship map** button | To show the war map on Discord |

**Screenshot** sends nothing to our server either: the button, or the screenshot shortcut (Alt+Shift+S, changeable in the options) in the game, copies the picture of the game to your clipboard, and does nothing on a tab without the game. The extension keeps the shortcut's last picture for at most 30 minutes, only in your browser's memory, so its popup can offer it for **Beat**, and it is only in your browser until you paste or save it, or press **Beat**.

**Confirm & assign** (Tactic Assistant) sends the tactic to our server as it is shown: for each position which Discord member takes it. The server stores it as your guild's tactic and posts it to your guild's numbers channel on Discord. Then the extension asks the game to give each member the orders (Global Championship) or target marks (Guild War) of the tactic, as the game's own screens do. Which Discord member is which player in the game is kept only in your browser.

**Training Team Post** sends nothing to our server: when you press its button, the extension asks the game to post the teams you picked from the championship map as your guild's trainings, with your own heroes or titans. Where you have the talisman the defender's hero wears, the extension first asks the game to put it on your hero, as the game's talisman screen does.

The extension does not send player names or guild names from war or training fights. The Guild Clash registration and the championship map contain the names and game IDs of players of your guild and, for the map, of the enemy guild, because that is what they show. The fights of **Feed the AI**, **Sync Arena** and **Guild trainings** are stored anonymously: without your Discord user ID, only with your main guild, so they count for your guild. Fights sent from **Beat Assistant** and imported heroes are stored with your Discord user ID and, where applicable, your main guild.

## What the Discord bot stores

When you use the bot's commands, we also store your Discord ID, your main guild and your Patreon tier. We keep only a hash of your API token, not the token itself.

## Server logs

Our server logs requests, including your Discord username, for security and abuse protection. It does not log your IP address. Logs are kept for [LOG RETENTION PERIOD]. Cloudflare also processes these requests, including your IP address, because it protects and forwards traffic to our server.

## What stays in your browser

Your settings, API token, fight records, fights and results not yet sent, your own training fights (shown in Beat Assistant, sent only when you press its send button), and a private device key are stored only in your browser. The private key cannot be exported. The API token is never passed to the game page. Removing the extension removes this data, except where your browser or its settings keep it.

## How we use the data

We use the data to provide team suggestions, manage access, award Intel Points, protect the service and train the AI models of HWTimeSaver. We do not sell it, use it for advertising or use it to determine creditworthiness.

The use of information received from Google APIs and the Chrome Web Store complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Who receives the data

- **Cloudflare**, which provides network and security services for our server.
- **Authorities**, if the law requires it.

We do not share it with anyone else unless the service is sold or merged, and then only with your explicit consent.

## How long we keep it

Hero data, account data and fights sent from Beat Assistant are kept until you ask us to delete them. The other fights and results are stored anonymously, without your Discord user ID, so we cannot tell which fights you sent and cannot delete them for you individually. For AI training, the results of the same fight are added up across all players: if one player sends a fight with 10 wins and 0 losses and another player sends the same fight with the same result, the AI learns 20:0. The AI models learn from these totals of all players, not from the data of a single player. Data that is deleted drops out of these totals within one day: the AI models are trained from scratch every day, so the next model no longer learns from it. Other players may have sent the same or nearly the same fight, for example a replay of your guild's war; their results stay in the totals and are still used.

## Your choices and rights

- Do not press **Import heroes** or the buttons that send data. Nothing in the table above is sent without its button. Without imported heroes, the Database app cannot suggest counters with your own heroes.
- Contact us to ask for a copy, correction or deletion of your data, or to object to its use.

If the GDPR applies to you, you may also complain to your data protection authority. We rely on the performance of the service you asked for and on our legitimate interest in security and in improving the AI. Where consent is the basis, you can withdraw it at any time.

## Children

The extension is not directed at children under 13.

## Changes

We will update this page when our data practices change, and will show significant changes in the extension before they take effect.
