# Getting Started

Follow this guide to launch your Discord community using the resources in this repository.

## Prerequisites

- A Discord account
- Permission to create or manage a server
- Optional: [Discord Developer Portal](https://discord.com/developers/applications) access if you plan to add custom bots

## Step 1: Create Your Server

1. Open Discord → **Add a Server** → **Create My Own** → **For a club or community**.
2. Name your server and upload an icon.
3. Skip Discord's default channels if you plan to follow [channels/CHANNELS.md](../channels/CHANNELS.md) instead.

## Step 2: Build Channel Structure

Use [channels/CHANNELS.md](../channels/CHANNELS.md) as your blueprint:

1. Create categories: **|| HOME ||**, **🍉 COMMUNITY**, and **|| Media ||**.
2. Add channels using the `emoji│channel-name` format (e.g. `⚠️│rules`, `🍓│lounge`).
3. Set permissions per channel (lock HOME channels, hide staff channels if added).

## Step 3: Configure Roles

Follow [roles/ROLES.md](../roles/ROLES.md):

1. Create **Admin**, **Moderator**, **Member**, **Muted**, and **Bot** roles.
2. Order roles correctly (higher staff above lower).
3. Set @everyone defaults: view HOME channels, deny send in lounge until verified.

## Step 4: Post Rules

Copy templates from [rules/RULES.md](../rules/RULES.md):

1. Paste the **Community** template into `#rules`.
2. Replace `{SERVER_NAME}` with your server name.
3. Add the **NSFW** template if you run 18+ channels.

## Step 5: Enable AutoMod

Configure Discord AutoMod using [automod/AUTOMOD.md](../automod/AUTOMOD.md):

1. Go to **Server Settings → AutoMod**.
2. Create rules for profanity, invites, spam, and mention abuse.
3. Import the wordlist, regexes, and allowed phrases from the guide.
4. Test in a private test server before going live.

## Step 6: Add Bots

See [bots/BOTS.md](../bots/BOTS.md) for recommendations:

1. Invite a logging bot → point logs to `#mod-logs`.
2. Set up verification or reaction roles for **Member** access.
3. Add a ticket bot for reports if needed.

## Step 7: Publish a Server Template (Optional)

Once configured, share your layout with [template/README.md](../template/README.md) so others can clone your setup.

## Step 8: Launch

1. Invite a small group of trusted members to test permissions.
2. Run through the member flow: join → rules → verify → chat.
3. Fix permission gaps before opening publicly.
4. Announce your server when ready.

## Next Steps

- Read [best-practices.md](best-practices.md) for growth and moderation tips.
- Review AutoMod false positives after the first week.
- Schedule a monthly audit of roles, bots, and channel permissions.

---

**Last Updated:** June 2026
