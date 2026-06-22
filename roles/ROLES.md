# Role Structure Recommendations

A clear role hierarchy keeps permissions predictable and moderation straightforward. Use this as a starting point and adjust names, colors, and permissions to fit your community.

## Recommended Hierarchy

Roles are listed from highest to lowest. Place higher roles above lower ones in **Server Settings → Roles**.

| Role | Purpose | Key Permissions |
|------|---------|-----------------|
| **Owner** | Server owner (automatic) | Full access |
| **Admin** | Trusted leadership | Manage server, channels, roles, bans |
| **Moderator** | Day-to-day moderation | Kick, ban, timeout, manage messages, mute members |
| **Trial Mod** | New moderators in training | Timeout, manage messages (no ban/kick) |
| **Bot** | Bot accounts | Send messages, embed links, use external emojis |
| **VIP / Booster** | Supporters or Nitro boosters | Custom color, optional exclusive channels |
| **Member** | Verified community members | Standard channel access |
| **@everyone** | Default role | Base permissions only |

## Permission Guidelines

### Admins
- Manage Server, Manage Channels, Manage Roles
- Ban Members, Kick Members, Moderate Members
- Manage Messages, Manage Threads
- View Audit Log

### Mods
- Kick Members, Ban Members, Moderate Members
- Manage Messages, Manage Threads
- Mute Members (via timeout or Muted role)
- **Do not** grant Manage Server or Manage Roles unless necessary

### Member
- View Channels, Send Messages, Read Message History
- Add Reactions, Use External Emojis, Attach Files
- Connect & Speak in voice (if applicable)

## Optional Roles

| Role | When to Use |
|------|-------------|
| **Announcements Ping** | Opt-in @mention for announcements |
| **Events Ping** | Opt-in @mention for events |
| **NSFW Access** | Self-assign after reading NSFW rules (18+ channels) |
| **Developer / Creator** | Project team or content creators |
| **Muted Media** | Block image/embed attachments without full mute |

## Best Practices

- **Keep the list short.** Too many roles confuse members and complicate AutoMod exemptions.
- **Use role colors sparingly.** Reserve bright or distinct colors for staff and VIP roles.
- **Separate staff from perks.** Moderation roles should not double as cosmetic roles.
- **Audit regularly.** Review who holds Admin and Moderator roles every few months.
- **Document escalation.** Define who can warn, mute, kick, and ban in your mod handbook.

## Setup Checklist

1. Create roles in the order above (bottom to top in the role list).
2. Set **Display role members separately from online members** for staff roles if desired.
3. Lock channel permissions so only **Member** (and above) can post in lounge and community channels.
4. Assign the **Bot** role to all bots and place it below Moderator.
5. Create a **role-select** channel or use a bot for self-assignable ping roles.

---

**Last Updated:** June 2026
