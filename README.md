# Zero Point Tactics — playtest builds

**Android only for now.** This repository holds the playtest builds (APK files) and nothing else;
the game's source is private. Two minutes the first time, thirty seconds for every update after.

## Install the game

1. On your phone, open the always-latest link:

   **https://github.com/Williams-p/zpt-playtest/releases/latest/download/zpt-playtest.apk**

   (Or browse to the [Releases page](https://github.com/Williams-p/zpt-playtest/releases)
   and tap `zpt-playtest.apk` under the top entry. No account or sign-in is needed.)
2. Chrome may say *"This type of file can harm your device"* — tap **Download anyway**. It's
   about 100 MB.
3. Tap the finished download (or open it from your Downloads).
4. The first time, Android asks to **allow installs from this source** (Chrome). Allow it, then
   go back.
5. **Play Protect** may warn about an unknown developer. Tap **More details → Install anyway**.
   The build is signed with a developer test key, not a store key; that's all this warning means.
6. Tap **Install**, then **Open**. The app is called **ZPT Spike**.

## Updating

Same link, same taps. The new build installs **over** the old one and **your progress is kept**.
There's a fresh build most weeks, and Peter cuts one whenever there's something new to try; you
don't need to update unless he asks you to, or you want to check whether something you reported
has changed.

**Which build am I on?** Phone **Settings → Apps → ZPT Spike**. The version reads like
`0.1.0-2a45657bb` — that `abc1234` is the build's name. Put it in any report.

**Trial builds.** Entries marked *Pre-release* on the Releases page are flag-armed trial cuts
for a specific sitting, not the tester default. Install one only when Peter asks; the
always-latest link never points at one.

## Telling us things

Three ways, pick whatever is least effort in the moment:

- **The group chat.** Fastest. "That felt cheap" or "wait, what?" the moment it happens is the
  most useful thing you can send. A screenshot of the board is worth a paragraph.
- **A playtest report** (a one-minute form, works on the phone):
  **https://github.com/Williams-p/zpt-playtest/issues/new?template=playtest-feedback.yml**
  Use this for anything you'd want us to be able to find again — a bug, an unfair moment, a
  confusing screen. Paste screenshots straight into it. (Needs a free GitHub account.)
- **After a session**, if you have the patience: what confused you, what felt unfair, what felt
  great, and whether you'd play another mission right now. One line each.

There are no wrong answers. If the game didn't explain something, that's our bug.

## If something goes wrong

| What you see | What it means | What to do |
| --- | --- | --- |
| **"App not installed"** | The build on your phone was signed with a different key (for example a build Peter installed by cable) | Uninstall ZPT Spike (this loses progress), then install again |
| **"Can't install — newer version already installed"** | You have a newer build than the link is offering | Nothing to do; you're ahead |
| Play Protect says it **blocked** the install | Play Protect's "unknown developer" check | **More details → Install anyway**. If there's no such button, open the Play Store → your profile → Play Protect → settings gear → turn off *Improve harmful app detection* for the install, then turn it back on |
| The game opens to a black screen or closes at once | A broken build (it happens) | Tell us the version (Settings → Apps → ZPT Spike) and we'll cut a new one |
| Your saved squad / progress vanished | See "App not installed" above — it was probably an uninstall | Tell us; it's useful to know when it happens |

**Uninstalling:** long-press the ZPT Spike icon → App info → Uninstall. The saved profile goes
with it.

Thank you for doing this.
