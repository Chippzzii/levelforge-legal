# LevelForge Usage Guide

This page explains the basic setup and usage after inviting LevelForge to your Discord server.

## 1. Invite the Bot

1. Open the official LevelForge invite link.
2. Select your Discord server.
3. Confirm the required permissions.
4. Finish the Discord authorization flow.

- Official invite link: [Add LevelForge](https://discord.com/oauth2/authorize?client_id=1501623866257051780)

## 2. Check Bot Permissions

After inviting LevelForge, verify that it can:

- Read messages in channels where XP should be tracked
- Send messages in channels where level-up or status messages should appear
- Use slash commands

If commands are missing, check Discord role permissions and channel overrides.

## 3. Run Basic Setup

Use the bot commands to configure your server:

- Set XP values per message
- Set cooldown to prevent spam farming
- Define level-up channel
- Configure ignored channels and ignored categories

If your server has many channels, start by setting ignore rules first.

## 4. How XP and Levels Work

In normal operation:

- Users receive XP for valid activity
- Cooldowns reduce abuse/spam XP farming
- Levels are calculated from stored XP
- Leaderboards are server-specific

LevelForge separates data by server (`guild_id`) so one server does not affect another.

## 5. Admin Actions

Server admins can typically:

- Adjust user XP
- Review level/rank data
- Tune configuration values

Use admin actions carefully and document major changes for your mod team.

## 6. Premium / Plan Notes

LevelForge may include plan states such as `FREE`, `VIP`, `TESTER`, or `LIFETIME`.

- Payment is not implemented yet.
- Premium-related behavior can be added later.
- Limits and feature access may depend on plan status.

## 7. Troubleshooting

If something does not work:

1. Re-check bot permissions and channel overrides.
2. Verify command permissions for your role.
3. Confirm cooldown/settings are not too strict.
4. Test in a dedicated channel.
5. Contact support.

- TODO: Support Discord URL (for example: `https://discord.gg/NsVbrUpM`)
- TODO: Support contact e-mail

## 8. Quick Checklist

- Bot invited successfully
- Required permissions granted
- XP/cooldown configured
- Level-up channel configured
- Ignore rules configured
- Basic command test successful

Last updated: 2026-05-07
