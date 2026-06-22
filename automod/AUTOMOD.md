# AutoMod Configuration

Discord AutoMod filters harmful content before it reaches your channels. Use this guide to configure keyword filters, invite blocking, and spam protection.

## Setup Overview

1. Open **Server Settings → AutoMod**.
2. Create or edit rules for each category below.
3. Copy the wordlist, regexes, and allowed phrases into the matching rule fields.
4. Set actions (block message, send alert, timeout) per rule.
5. Exempt staff roles (Moderator, Admin) where appropriate.

## Recommended Rules

| Rule | Trigger | Suggested Action |
|------|---------|------------------|
| **Profanity** | Custom wordlist below | Block message + alert |
| **Invites & links** | Invite/link regex | Block message |
| **Spam** | Duplicate text / mention spam | Timeout user |
| **Mass mentions** | 5+ mentions per message | Block message |

## 📋 Wordlist

Copy and paste the following into your moderation system:

```txt
amerikkkan*, anal*, cock, cocks, *cum*, cum, cunt, dick, dicks, fag*, f*a*g, fat american, fat ass, gay, *kill yourself*, kkk, *kum*, *kys*, k*y*s, *nigg*, n*i*g*g*a, *pussy*, pussy, retard, *retarded*, retards*, school shooter, school shooting, sex, tit, titt*, xxx
```

Standalone copy: [wordlist.txt](wordlist.txt)

## 📋 Regexes

Copy and paste the following into your moderation system:

```txt
(?:https?:\/\/)?[a-z0-9_\-]+(?:\s*|[\u0020\u00A0])*\.(?:c\s*o\s*m|n\s*e\s*t|o\s*r\s*g|i\s*o|g\s*o\s*v|e\s*d\s*u|i\s*n\s*f\s*o|g\s*g|x\s*x\s*x)\b

(?:https?:\/\/)?(?:www\.|ptb\.|canary\.)?(?:dsc\.gg|invite\.gg|discord\.link|(?:discord\.(?:gg|io|me|li|id))|disboard\.org|discord(?:app)?\.(?:com|gg)\/(?:invite|servers))\/[a-z0-9-_]+

[\u0300-\u036F]{3,}

(?s)(?i)((<a?:[a-z_0-9]+:[0-9]+>|\p{Extended_Pictographic}|[\u{1F1E6}-\u{1F1FF}]|[0-9#\*]\u{fe0f}).*){7,}
```

Standalone copy: [regexes.txt](regexes.txt)

## 📋 Allowed Phrases

Copy and paste the following into your moderation system:

```txt
*://c.tenor.com/*, *://cdn.discordapp.com/*, *://dis.gd/*, *://garticphone.com/*, *://imgflip.com/*, *://media.discordapp.net/*, *://on.soundcloud.com/*, *://open.spotify.com/*, *://store.steampowered.com/*, *://tenor.com/*, *://vm.tiktok.com/*, *://www.bilibili.com/*, *://www.tiktok.com/*, *://www.youtube.com/*, *://x.com/*, *://youtu.be/*, *://youtube.com/*, cucumber, cucumbers, document, documented
```

Standalone copy: [allowed-phrases.txt](allowed-phrases.txt)

---

## 📌 Notes

* Test all moderation changes in a private server before deploying them.
* Broad filters may cause false positives; use allowlists to reduce them.
* Review and update your moderation rules regularly as your community grows.
* Always keep backups of your moderation configuration before making major changes.

---

<div align="center">

### 🛡️ Happy Moderating!

Effective moderation is about balancing safety and usability. Start with conservative rules, monitor false positives, and adjust as needed.

</div>
