# Channel Organization

A clean channel layout helps new members find information quickly and keeps conversations on topic. This template uses a consistent naming style: category headers with `||` brackets, and channel names prefixed with an emoji and `│` separator.

## Recommended Layout

```
|| HOME ||
├── ⚠️│rules
├── ⚠️│announcements
├── ⚠️│streams
├── ⚠️│about
├── ⚠️│welcome
├── ⚠️│tickets
└── ⚠️│goal

|| COMMUNITY ||
├── 🍉│intros
├── 🍓│lounge
├── 🍉│spam
├── 🍓│suggestions
├── 🍉│quote-book
├── 🍓│fanfics
├── 🍉│nsfw
└── 🍓│vent

|| Media ||
├── 📺│media
├── 📺│photography
├── 📺│art
├── 📺│fanart
├── 📺│memes
└── 📺│music
```

## Naming Style

| Element | Format | Example |
|---------|--------|---------|
| Category | `|| NAME ||` or emoji + name | `|| HOME ||`, `🍉 COMMUNITY` |
| Channel | `emoji│channel-name` | `⚠️│rules`, `🍓│lounge` |

Using the same emoji per category (or alternating within one) keeps the sidebar visually organized without cluttering channel names.

## Channel Details

### || HOME ||

| Channel | Purpose |
|---------|---------|
| `⚠️│rules` | Server rules ([rules/RULES.md](../rules/RULES.md)) |
| `⚠️│announcements` | Official news; staff-only posting |
| `⚠️│streams` | Stream announcements and go-live pings |
| `⚠️│about` | Server info, links, and FAQ |
| `⚠️│welcome` | Welcome messages and join notifications |
| `⚠️│tickets` | Support and report tickets |
| `⚠️│goal` | Server milestones and goals |

**Tips:** Lock all HOME channels so only staff can post (except `tickets` if using a ticket bot). Set `welcome` as the system messages channel.

### || COMMUNITY ||

| Channel | Purpose |
|---------|---------|
| `🍉│intros` | New member introductions |
| `🍓│lounge` | Main hangout and general chat |
| `🍉│spam` | Low-effort chat, commands, and off-topic |
| `🍓│suggestions` | Server feedback and ideas |
| `🍉│quote-book` | Funny or memorable quotes from the server |
| `🍓│fanfics` | Creative writing and fan content |
| `🍉│nsfw` | 18+ content (mark channel NSFW; see [rules/RULES.md](../rules/RULES.md)) |
| `🍓│vent` | Venting space (consider slowmode and clear boundaries) |

**Tips:** Use threads in `lounge` for long discussions. Keep `spam` as the catch-all so other channels stay on topic.

### || Media ||

| Channel | Purpose |
|---------|---------|
| `📺│media` | General media shares (videos, clips, links) |
| `📺│photography` | Photos and photography |
| `📺│art` | Original artwork |
| `📺│fanart` | Fan-made art |
| `📺│memes` | Memes and humor |
| `📺│music` | Music shares and recommendations |

**Tips:** Enable image/media-only mode on art and photography channels if you want to reduce text-only posts.

## Optional Add-ons

These aren't part of the core layout but work well alongside it:

```
|| STAFF (private) ||
├── ⚖️│mod-chat
├── ⚖️│mod-logs
└── ⚖️│reports

|| VOICE ||
├── 🔊│General
└── 🔊│AFK
```

Hide the staff category from @everyone. Point bot logs to `mod-logs`.

## Permission Quick Reference

| Channel | @everyone | Member | Moderator |
|---------|-----------|--------|-----------|
| `⚠️│rules` | View only | View only | View + manage |
| `⚠️│announcements` | View only | View only | Send messages |
| `🍓│lounge` | Deny send | Send messages | Full |
| `🍉│nsfw` | Hidden | View (18+) | Full |
| Staff channels | Hidden | Hidden | View + send |

## Onboarding Flow

1. New member joins → welcome message in `⚠️│welcome`.
2. Member reads `⚠️│rules` → assigns **Member** role via reaction, button, or verification bot.
3. Member posts in `🍉│intros`, then gains access to **COMMUNITY** and **Media** channels.

## Customization

- Swap `🍉` / `🍓` for emojis that match your server's theme.
- Rename categories (`|| HOME ||` → `|| INFO ||`) — keep the `||` style for consistency.
- Remove channels you don't need (`fanfics`, `quote-book`, etc.) without breaking the layout.
- Add voice or staff categories at the bottom so the main three stay grouped together.

---

**Last Updated:** June 2026
