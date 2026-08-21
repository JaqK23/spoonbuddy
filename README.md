# SpoonBuddy

**A work timer with an energy budget.** It measures your day in *spoons* rather than
hours, because an hour of admin and an hour of knitting do not cost the same thing.

There is a Windows app and an Android app. They keep the same records and can sync
between each other, or work entirely on their own.

**[Read more, and see what it looks like →](https://jaqk23.github.io/spoonbuddy/)**

---

## Download

Everything is on the [releases page](../../releases).

| | |
| --- | --- |
| **Android** | [SpoonBuddy.apk](../../releases/latest/download/SpoonBuddy.apk) |
| **Windows** | [SpoonBuddy-windows.zip](../../releases/latest/download/SpoonBuddy-windows.zip) |

Those two links always point at the newest version, so they are safe to bookmark.
Each release also carries a copy named for its version — `SpoonBuddy-0.1.3.apk` —
if you want to know which build you have from the filename alone.

### Windows

Unzip it anywhere and run `start-spoonbuddy.vbs`. There is no installer and nothing
is written outside your own user folder.

Windows will probably warn you about a file downloaded from the internet. That is
expected for anything unsigned; choose **More info** and then **Run anyway** if you
are happy to.

### Android

This is currently a **sideloaded** app rather than a Play install, so you will need
to allow installing from your browser or files app when it asks.

---

## This is alpha software

It works, it is used daily, and it is not finished. Two things to know before you
rely on it:

**Your records live on your own device.** Nothing is sent anywhere unless you turn
on syncing and sign in. If you do not, the app never touches the network.

**Export your data before you replace the app.** Both apps have *Export my data* on
the Info screen. It writes one file you can keep anywhere and load back in later.
On Android especially — a newer copy can arrive as a separate app with an empty
history, and that file is how you carry your records across.

Found a problem? There is a **Send feedback** button in the app, or use the
[issues](../../issues) here.

---

## Privacy

[**The privacy policy is here.**](https://jaqk23.github.io/spoonbuddy/privacy.html)
The short version: your entries stay on your device, there is no analytics, no crash
reporting, no advertising and no third-party tracking of any kind.

To have synced data deleted, see the
[deletion section](https://jaqk23.github.io/spoonbuddy/privacy.html#delete).

---

## Where the code is

**This repository holds the releases and the website only.** The source lives in a
private repository.

## Licence

**SpoonBuddy is not open source.** See [LICENSE](LICENSE) — you may read this, and
you may not reuse it without asking. Asking is fine; the answer may well be yes.

That is a deliberate choice rather than an oversight. The Android app is going to
be paid, and there is nothing in here that the world is short of.

The bundled fonts carry their own licences, which travel inside the download:
[Lexend](https://github.com/googlefonts/lexend) and
[OpenDyslexic](https://opendyslexic.org/), both under the SIL Open Font License.
