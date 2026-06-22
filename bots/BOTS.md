# Recommended Bots

Bots extend moderation, logging, and utility features beyond Discord's built-in tools. Start with a small set and add more only when needed.

## Essential Bots

### Moderation & Logging

| Bot | Best For | Notes |
|-----|----------|-------|
| **[Dyno](https://dyno.gg/)** | Moderation commands, auto-mod, custom commands | Easy setup for new moderators |

### Tickets & Support

| Bot | Best For | Notes |
|-----|----------|-------|
| **[Ticket Tool](https://tickettool.xyz/)** | Support and report tickets | Panel-based setup |
| **[Claimontool](https://claimontool.com/)** | Staff applications and tickets | Lightweight option |

### Utility

| Bot | Best For | Notes |
|-----|----------|-------|
| **[Discohook](https://discohook.org/)** | Webhook-based embeds | Not a server bot; useful for announcements |
| **[Apollo](https://apollo.bot/)** | Events and scheduling | Good for community events |
| **[Statbot](https://statbot.net/)** | Server analytics | Member growth and activity stats |

## Recommended Setup Order

1. **Logging bot** — Connect `#mod-logs` for joins, leaves, message deletes, and bans.
2. **Reaction roles / verification** — Gate `#lounge` behind a **Member** role.
3. **Moderation commands** — `/warn`, `/mute`, `/kick`, `/ban` for staff.
4. **Ticket bot** — Route reports away from public chat.
5. **Optional:** Leveling, music, or custom welcome messages.

## Permissions Checklist

When inviting any bot:

- [ ] Grant only the permissions it needs (principle of least privilege).
- [ ] Place the bot's role **below** staff roles but **above** Member.
- [ ] Deny **Manage Server** and **Manage Roles** unless the bot requires them.
- [ ] Use a dedicated **Bot** role for consistent permission overrides.
- [ ] Review bot dashboards for data retention and privacy policies.

## AutoMod vs. Bots

Discord's built-in **AutoMod** (see [automod/AUTOMOD.md](../automod/AUTOMOD.md)) handles keyword filters, spam, and mention limits at the platform level. Use bots for:

- Custom commands and workflows
- Detailed logging and case management
- Tickets, leveling, and role menus

Avoid running overlapping filter rules in both AutoMod and a bot — duplicate filters increase false positives.

## Bots to Avoid

- Bots that request **Administrator** without a clear reason.
- Unverified or unknown bots from random invite links.
- Multiple bots doing the same job (e.g. three welcome bots).

---

**Last Updated:** June 2026
