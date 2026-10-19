This is my personal Vencord setup, for those that want a great starting point to build on, or skip configuring and simply acquire what I consider to be a proper collection and configuration of Vencord.

- I've purposely left out parts that I felt were too opinionated for the common person.  
- Also includes a short guide for applying local themes.

---

- **[Download Vencord](https://vencord.dev)** 
- **[Vencord GitHub](https://github.com/Vendicated/Vencord)** 
- **[Vencord Discord](https://discord.gg/xymWt9QRbp)**

---

### Apply My Vencord Settings

1. Open Discord Settings > Vencord > Backup & Restore
2. Import the Vencord settings export of your choosing from this repo *(if you already have a Vencord setup of your own, export it first so it isn't lost)*
3. Restart/Reload Discord


---

### Apply Local Themes

1. Download your desired theme's `.css` file
2. Open: Discord Settings > Vencord > Themes
3. Select 'Open Theme Folder'
4. Copy or move the theme's `.css` file into the folder
5. Back in Vencord's Themes settings, select 'Load Missing Themes'
6. Toggle on whichever themes you want
   
- If a theme isn't applying properly, try switching your Discord Nitro theme to the default dark theme

### Customize Theme Backgrounds

#### Change Image Background

- Most commonly themes will offer the ability to add/change background image

1. Open the theme's `.css` file and find its background image setting, word search for likely parameter names like:  `--app-bg`, `--bg`,  `--background-image`, `--bg-img`, ...etc...
2. Use your own custom image by replacing the image URL with your own.
   - Suggest getting your image URL via **[Imgur](https://imgur.com/upload)**. 
    Make sure your URL doesn't contain 'blob', if it does then you copied a invalid URL.

#### Transparent Background

- Some themes may support transparent backgrounds, such as **[Translucence](https://betterdiscord.app/theme/Translucence)**

1. You must have 'Enable Window Transparency' enabled, find it in: Discord Settings > Vencord >  Enable Window Transparency
2. The way you can make a theme's background transparent in it's  `.css` file can differ depending on the theme, but most likely you should replace the image URL used in it's image setting with `transparent;` or `none`. The theme may offer the ability via something like `transparent: true`. 

- You may likely need an external tool to apply blur to the transparent Discord window, I suggest **[MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone)** or the Windhawk mod 'Translucent Windows' by **[Undisputed00x](https://github.com/Undisputed00x)**
  - If you're on Win10, MicaForEveryone & Windhawk Translucent Windows aren't too compatible on it. 
     - I actually have a fork of MicaForEveryone that is optimized toward better Win10 compatibility, just make sure you read **[the repo](https://github.com/landnthrn/MicaForEveryone-win10-fork)**.  
     - Translucent Windows also has **[a more Win10 optimized version](https://github.com/Gameknight963/translucent-windows-for-win10)** by  **[Gameknight963](https://github.com/Gameknight963)**
- If you lose the ability to resize the Discord window when Vencord's 'Enable Window Transparency' feature is enabled, you can try a Windhawk mod 'Discord Transparency Resize Fix' by **[Gameknight963](https://github.com/Gameknight963)**

#### Find Themes:
- **[Better Discord Themes](https://betterdiscord.app/themes)**
 - Basically all Better Discord themes work on Vencord
#### Themes I Suggest Checking out:
- **[Discordia](https://github.com/ungiglio/DiscordDiscordia)**
- **[Translucence](https://betterdiscord.app/theme/Translucence)**
- **[Frosted Glass](https://betterdiscord.app/theme/Frosted%20Glass)**
- **[Wizard UI](https://betterdiscord.app/theme/WizardUI)**
- **[Fallout4 Terminal](https://github.com/PepeBigotes/Fallout4TerminalColorTheme)**
- **[Spotify Discord](https://betterdiscord.app/theme/Spotify%20Discord)**
- **[Discord Plus](https://betterdiscord.app/theme/Discord%2B)**
- **[Clear Vision](https://betterdiscord.app/theme/ClearVision)**
- **[Dark Matter](https://betterdiscord.app/theme/Dark%20Matter)**

---

### Credits

#### Vencord plugins in my setting exports
*GitHub source repo's couldn't be found for plenty of the plugins*

- AccountPanelServerProfile, by **[relitrix-archive](https://github.com/relitrix-archive)**
- **[AlwaysAnimate](https://github.com/jackmthws/Vencord/blob/main/src/plugins/alwaysAnimate/index.ts)**, by **[jackmthws](https://github.com/jackmthws)**
- **[AlwaysExpandRoles](https://github.com/chloecinders/Vencord/blob/main/src/plugins/alwaysExpandRoles/index.ts)**, by **[chloecinders](https://github.com/chloecinders)**
- **[AlwaysTrust](https://github.com/zt64/Vencord/blob/main/src/plugins/alwaysTrust/index.ts)**, by **[zt64](https://github.com/zt64)**
- BetterRoleContext, by **[Vendicated](https://github.com/Vendicated)**
- BetterRoleDot, by **[Vendicated](https://github.com/Vendicated)**
- **[BetterSessions](https://github.com/aamiaa/Vencord/blob/main/src/plugins/betterSessions/index.tsx)**, by **[aamiaa](https://github.com/aamiaa)**
- BetterSettings, by **[Kyuuhachi](https://github.com/Kyuuhachi)**
- BiggerStreamPreview, by **[philhk](https://github.com/philhk)**
- CallTimer, by **[Vendicated](https://github.com/Vendicated)**
- ClearURLs, by **[adryd325](https://github.com/adryd325)**
- CopyEmojiMarkdown, by **[vishnyanetchereshnya](https://github.com/vishnyanetchereshnya)**
- CopyFileContents, by **[Obsidianninja11](https://github.com/Obsidianninja11)**
- CopyUserURLs, by **[castdrian](https://github.com/castdrian)**
- CrashHandler, by **[Nuckyz](https://github.com/Nuckyz)**
- CustomIdle, by **[waresnew](https://github.com/waresnew)**
- DisableCallIdle, by **[Nuckyz](https://github.com/Nuckyz)**
- DontRoundMyTimestamps, by **[KontrollFreek](https://github.com/KontrollFreek)**
- EmoteCloner, by **[Vendicated](https://github.com/Vendicated)**
- FakeNitro, by **[ArjixWasTaken](https://github.com/ArjixWasTaken)**
- FakeProfileThemes, by **[rosalinadev](https://github.com/rosalinadev)**
- FavoriteEmojiFirst, by **[Syncxv](https://github.com/Syncxv)**
- FavoriteGifSearch, by **[Syncxv](https://github.com/Syncxv)**
- FixImagesQuality, by **[Nuckyz](https://github.com/Nuckyz)**
- FixSpotifyEmbeds, by **[Vendicated](https://github.com/Vendicated)**
- FixYoutubeEmbeds, by **[velzie](https://github.com/velzie)**
- FriendsSince, by **[sillyElv](https://github.com/sillyElv)**
- FullSearchContext, by **[Vendicated](https://github.com/Vendicated)**
- **[FullUserInChatbox](https://github.com/sadan4/Vencord/blob/main/src/plugins/fullUserInChatbox/index.tsx)**, by **[sadan4](https://github.com/sadan4)**
- GameActivityToggle, by **[Nuckyz](https://github.com/Nuckyz)**
- GifPaste, by **[Vendicated](https://github.com/Vendicated)**
- GreetStickerPicker, by **[Vendicated](https://github.com/Vendicated)**
- IgnoreActivities, by **[Nuckyz](https://github.com/Nuckyz)**
- ImplicitRelationships, by **[dolfies](https://github.com/dolfies)**
- MemberCount, by **[Vendicated](https://github.com/Vendicated)**
- MentionAvatars, by **[Vendicated](https://github.com/Vendicated)**
- MessageClickActions, by **[Vendicated](https://github.com/Vendicated)**
- MessageLogger, by **[rushiiMachine](https://github.com/rushiiMachine)**
- MutualGroupDMs, by **[aamiaa](https://github.com/aamiaa)**
- NewGuildSettings, by **[cunnyarc](https://github.com/cunnyarc)**
- NoF1, by **[Cynosphere](https://github.com/Cynosphere)**
- NSFWGateBypass, by **[Commandtechno](https://github.com/Commandtechno)**
- OpenInApp, by **[Vendicated](https://github.com/Vendicated)**
- PermissionsViewer, by **[Nuckyz](https://github.com/Nuckyz)**
- PinDMs, by **[Vendicated](https://github.com/Vendicated)**
- **[PreviewMessage](https://github.com/Syncxv/Vencord/blob/main/src/plugins/previewMessage/index.tsx)**, by **[Syncxv](https://github.com/Syncxv)**
- QuickMention, by **[kem0x](https://github.com/kem0x)**
- QuickReply, by **[fawni](https://github.com/fawni)**
- ReadAllNotificationsButton, by **[kem0x](https://github.com/kem0x)**
- RelationshipNotifier, by **[nickisnoobatcode](https://github.com/nickisnoobatcode)**
- ReplyTimestamp, by **[Kyuuhachi](https://github.com/Kyuuhachi)**
- ServerInfo, by **[Vendicated](https://github.com/Vendicated)**
- ShowAllMessageButtons, by **[Nuckyz](https://github.com/Nuckyz)**
- ShowConnections, by **[TheKodeToad](https://github.com/TheKodeToad)**
- ShowHiddenThings, by **[dolfies](https://github.com/dolfies)**
- SilentMessageToggle, by **[Nuckyz](https://github.com/Nuckyz)**
- SilentTyping, by **[Vendicated](https://github.com/Vendicated)**
- StickerPaste, by **[ImBonana](https://github.com/ImBonana)**
- SuperReactionTweaks, by **[jackmthws](https://github.com/jackmthws)**
- ThemeAttributes, by **[Vendicated](https://github.com/Vendicated)**
- Translate, by **[Vendicated](https://github.com/Vendicated)**
- TypingIndicator, by **[Nuckyz](https://github.com/Nuckyz)**
- **[TypingTweaks](https://github.com/zt64/Vencord/blob/main/src/plugins/typingTweaks/index.tsx)**, by **[zt64](https://github.com/zt64)**
- UserMessagesPronouns, by **[TymanWasTaken](https://github.com/TymanWasTaken)**
- UserVoiceShow, by **[Nuckyz](https://github.com/Nuckyz)**
- USRBG, by **[AutumnVN](https://github.com/AutumnVN)**
- ValidUser, by **[Vendicated](https://github.com/Vendicated)**
- VoiceChatDoubleClick, by **[Vendicated](https://github.com/Vendicated)**
- VencordToolbox, by **[Vendicated](https://github.com/Vendicated)**
- ViewIcons, by **[Vendicated](https://github.com/Vendicated)**
- ViewRaw, by **[12944qwerty](https://github.com/12944qwerty)**
- VoiceDownload, by **[puv](https://github.com/puv)**
- VoiceMessages, by **[Vendicated](https://github.com/Vendicated)**
- VolumeBooster, by **[Nuckyz](https://github.com/Nuckyz)**
- YoutubeAdblock, by **[Vendicated](https://github.com/Vendicated)**
- ExpressionCloner, by **[Vendicated](https://github.com/Vendicated)**
- CopyStickerLinks, by **[byeoon](https://github.com/byeoon)**
- ImageFilename, by **[fawni](https://github.com/fawni)**
- CustomCommands, by **[Vendicated](https://github.com/Vendicated)**
- CharacterCounter, by **[thororen1234](https://github.com/thororen1234)**
- PlainFolderIcon


---

## Found this useful?![[optical-illusion-rotating-head.gif|400]]<br>

[![[Follow Me 3-000000.svg|Follow Me <3|400]]](https://github.com/landnthrn)   
[![[Find More of my Creations on GitHub-311A82.svg|Find More of my Creations on GitHub|400]]](https://github.com/landnthrn?tab=repositories)  
[![[Gists-311A82.svg|Gists: landnthrn|400]]](https://gist.github.com/landnthrn)  
[![[Discord-311A82.svg|Discord: landn.thrn|400]]](https://discord.com/users/831735011588964392)  
[![[Buy Me a Coffee-311A82.svg|Buy Me a Coffee|400]]](https://buymeacoffee.com/landn.thrn/extras)  
[![[PayPal-311A82.svg|PayPal|400]]](https://www.paypal.com/donate/?hosted_button_id=K4PLHFVBH7X8C)

![](https://github-view-counter-1-0-0.vercel.app/api?username=landnthrn-my-vencord-setup&label=false&bgColor=20164C&color=6a5acd&iconColor=6a5acd)