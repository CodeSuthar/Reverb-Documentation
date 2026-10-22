# Reverb Privacy Policy

**Effective date:** 23 October 2026
**Last updated:** 23 October 2026

This Privacy Policy explains what information the Reverb Discord music bot ("Reverb", "we", "us") accesses, stores and shares, and how you can contact us or ask us to delete your information. Reverb is operated by **The Reverb Team**.

Reverb is an independent project. It is not affiliated with, sponsored by or endorsed by Discord Inc.

## 1. Who we are and how to contact us

Reverb is operated by The Reverb Team. For privacy questions, requests, complaints or legal notices, you can use any of these:

- **Email:** mail@codesuthar.is-a.dev
- **Discord direct message:** @thatomnitrixguy
- **Support server ticket:** https://discord.gg/6UwVYHu2zu

## 2. Scope

This policy covers:

- the Reverb Discord bot, including its slash commands, prefix commands, buttons and the optional song-requests channel; and
- the Reverb documentation website at https://codesuthar.github.io/Reverb/ (see Section 9).

It does not cover Discord itself or other third-party services. Those have their own terms and privacy policies (see Section 6).

## 3. Information Reverb accesses, stores and processes

We try to separate what the bot only *sees while it runs* from what it *saves*.

### 3.1 Information accessed through Discord while Reverb runs

To work, Reverb receives certain information from Discord. Unless Section 3.2 says otherwise, this information is used only in the moment and held in the bot's memory.

- **Server (guild), channel and voice-channel IDs**, used to join voice channels, post player messages and apply settings.
- **User IDs, usernames and display names**, used to identify who ran a command and who requested a song (for example, "Requested by").
- **Role IDs and permissions**, used to check whether someone may use a command, for example DJ mode and the Manage Server permission.
- **Voice state**, meaning which voice channel you are in, so music is played where you are.
- **Message content.** Reverb reads message content only to detect and run prefix commands (such as `r!play`), and to read song requests typed in the dedicated song-requests channel, which Reverb then deletes to keep the channel tidy. Reverb does not save message content in its database. Reverb does not use message content to train machine-learning or AI models.
- **Commands and options you submit**, including search terms and links, which are used to find and play music.
- **Music queue and playback state**, such as the current track, queue, volume, loop and filters, held in memory while a player is active.

### 3.2 Information Reverb stores

Reverb saves the following in its database:

| What | Details | Purpose |
|---|---|---|
| **Server settings** | Server ID, custom command prefix, default volume, language setting | To remember your server's configuration |
| **DJ mode** | Server ID, whether DJ mode is on, and the IDs of roles and users given DJ permission | To enforce DJ restrictions |
| **Command whitelist** | Server ID, whether it is on, and the IDs of allowed channels, roles and users | To restrict where commands can be used |
| **Song-requests channel** | Server ID and the IDs of the channel, category, voice channel and player message | To keep the song-requests channel working |
| **24/7 mode** | Server ID and the IDs of the text and voice channels | To let the bot stay in a voice channel |
| **Playlists** | Your Discord user ID, playlist name, whether it is public or private, and the saved tracks (track identifiers and basic details such as title and link) | To let you save and reuse playlists |
| **Usage counter** | A single running total of songs played | To show basic statistics |

Discord IDs are identifiers that can relate to a person or server, so we treat them as personal information. Playlist names and the tracks you save are content you choose to create.

Reverb may also process technical and diagnostic information that is needed to operate, secure and troubleshoot the bot.

### 3.3 Information sent to you

Some commands send messages to you. For example, `grab` and listing your private playlists send a direct message (DM) to you. Reverb does this only when you run such a command.

### 3.4 Changes Reverb makes in Discord

If a server administrator uses customization commands, Reverb can change its own nickname, avatar, banner or bio **in that server**. These changes are made on Discord and are not stored as personal information about members.

### 3.5 What Reverb does not do

- Reverb does not sell your information.
- Reverb does not use it for advertising or profiling.
- Reverb does not process payments. There are no paid features at this time.
- Reverb does not contact you outside Discord using Discord data.

## 4. Why we use this information

We use the information above only to provide and maintain Reverb's music features: playing and controlling music, saving your settings and playlists, enforcing permissions and DJ rules, responding to your commands, keeping the bot reliable and secure, and answering your requests and reports.

Where privacy law requires a legal basis, we rely on what is necessary to provide the bot you asked to use, our legitimate interest in running and securing it, and consent where you choose to use features such as saved playlists. Which laws apply depends on where you live; see Section 11.

## 5. Where information is stored and how it is protected

Reverb's database runs on infrastructure operated by The Reverb Team. The database is protected by access controls, and access is limited to The Reverb Team. We take reasonable steps to protect the information we store. No system is completely secure, and we cannot guarantee absolute security.

**Backups.** We back up the database monthly. Backups are kept for about one month, then removed (see Section 7).

If we become aware of unauthorised access to personal information, we will take steps to contain it and will notify Discord and affected people where required.

## 6. Third-party services and sharing

We do not sell personal information and we do not share it with advertisers or data brokers.

Reverb relies on third parties to work:

- **Discord.** Reverb runs on Discord. Discord processes your information under its own terms and privacy policy. We do not control Discord's systems, and we cannot delete information that Discord holds.
- **Music, audio and lyrics services.** To find and play tracks, and to show lyrics, Reverb sends search terms, links and track identifiers to independent third-party services. Reverb does not intentionally send your Discord user ID to these services. These services are not controlled by us and may keep information under their own policies.

Reverb does not store music files. We may disclose information if required by law or to protect rights, safety or the security of Reverb.

## 7. How long we keep information

- **Server settings, DJ, whitelist, song-requests and 24/7 records:** kept while Reverb is in your server. A cleanup runs every 31 days to delete settings and records for servers where Reverb is no longer present.
- **Playlists:** kept until you delete them or ask us to delete them.
- **Usage counter:** kept as an aggregate total that does not identify individuals.
- **Backups:** kept for about one month. Information deleted from the live database can therefore remain in a backup for up to about that long before the backup is removed.
- **Memory-only information** (queue, playback state, message text used to run a command) is not saved in the database and is discarded when no longer needed or when the bot restarts.

We may keep information longer where the law requires it.

## 8. Your choices and requests

You, or an administrator of your server, can contact us at any time to ask us to:

- tell you what we store about you or your server;
- correct information that is wrong; or
- delete information, such as your playlists or your server's settings.

You can also delete your own playlists using the playlist commands, and server administrators can remove the song-requests channel and settings with the bot's commands, or remove Reverb from the server at any time.

**How to make a request:** email mail@codesuthar.is-a.dev, message @thatomnitrixguy on Discord, or open a ticket in the support server (https://discord.gg/6UwVYHu2zu). Please include your Discord user ID (for personal data) or your server ID (for server settings). To protect people's information, we may ask you to confirm you are the person or a server administrator before acting. We will handle requests as promptly as we reasonably can.

We cannot delete information held by Discord or by independent third-party services; please contact them directly.

## 9. Website

The Reverb documentation website is hosted on GitHub Pages. We do not add analytics, advertising trackers or contact forms to the site. GitHub, as the host, may process technical information about visitors (such as IP addresses) under GitHub's own privacy statement.

<!-- CONFIRM BEFORE PUBLISHING: The repo's VitePress config shows no analytics, cookies, fonts or forms, but the published site and hosting settings were not inspected. Confirm in a browser's network tab before keeping this section as written. -->

## 10. Children

Reverb is intended for people who meet Discord's minimum age, which is **13**, or a higher age if the law where you live requires it. We do not knowingly collect information from anyone below that age. If you believe a child has provided information to Reverb, contact us and we will delete it.

## 11. Your rights under applicable law

Depending on where you live, privacy law may give you rights to access, correct, delete or object to the use of your information, or to complain to a regulator. You can exercise these by contacting us as described in Section 8. We will respond in line with the law that applies to us.

## 12. International use

Reverb's database runs on infrastructure operated by The Reverb Team. People use Reverb from many countries, and Discord and the third-party services described above may process information in other countries. By using Reverb you understand that your information may be handled in locations different from where you live.

## 13. Changes to this policy

We may update this policy as Reverb changes. We will update the "Last updated" date above and, for material changes, make reasonable efforts to tell users, for example in the support server. If Discord requires, we will resubmit changes for review. Continuing to use Reverb after an update means you accept it.

## 14. Contact and complaints

Questions, concerns or complaints about privacy:

- **Email:** mail@codesuthar.is-a.dev
- **Discord:** @thatomnitrixguy
- **Support server:** https://discord.gg/6UwVYHu2zu