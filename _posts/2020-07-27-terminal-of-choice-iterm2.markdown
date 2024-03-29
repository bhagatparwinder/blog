---
layout: post
title:  "Terminal of Choice: iTerm2"
image: "/assets/social/iterm.png"
date:   2020-07-27 12:00:00 -0500
---

One of the critical tools or piece of software in a developers life is the terminal or command prompt. If you are on Windows, you probably use `cmd` or PowerShell. If you are on Linux, you have the choice of a plethora of shells. It is the same with Mac.

I have been a Mac user for about 12 years now. It gives me the power of Linux paired with the friendliness of Windows. I would say it is a happy middle for me. It's not perfect, but it does the job reasonably well!

The terminal shipped with Mac comes with `bash` shell by default. If you are using Catalina or above, it has been switched to `zsh` by default. I will deep dive into my shell customization in another post.

### Background

I started coding professionally around 2008. Coding for personal projects began in early 2004. So it's been a 16-year journey and counting. Here are a few terminal replacements I have used in the past few years:

1. [Cmder](https://cmder.net): To date, my favorite terminal on Windows.
2. [Hyper](https://hyper.is/#installation): It is a beautiful and extensible command-line interface built on open web standards. JavaScript developers will feel right at home.
3. [iTerm2](https://www.iterm2.com/downloads.html): Finally settled on iTerm 2.

I've been with iTerm2 for the last five years. I'm absolutely in love ❤️ with it because:

* Highly configurable and multi-profile support
* Split Panes
* Autocomplete
* Paste History
* Jump to Window shortcuts
* Inline Images and a Password Manager!
* Free 💰

### Downloads

* You can get iTerm2 [here](https://www.iterm2.com/downloads.html). Keep in mind that it is only available for Mac.
* Powerline Patched fonts are available [here](https://github.com/powerline/fonts)
* Cobalt2 Color Scheme is available [here](https://github.com/wesbos/Cobalt2-iterm)
* Direct link to my profile JSON is [here](https://gist.github.com/bhagatparwinder/200f769bd4418d977c43170b055a3edc)

### My Setup

Now comes the important part, my setup of iTerm2. I am going to share my extensions and settings for the terminal. You can use them; as you feel like. Below is how my terminal looks like:

![iTerm Screenshot](/blog/assets/iterm.png "iTerm2")

* Sync your iTerm2 preferences across multiple systems. Go to Preference. Select `General > Preferences` and check the box for `Load preferences from a custom folder or URL`. You can use a service like Dropbox or Google Drive.
* To make the title bar match the rest of the color scheme, select `Appearance > General > Theme > Minimal`.
* To have an unlimited amount of scroll back available in the terminal, select `Profiles > Terminal > Scrollback Buffer` and check `Unlimited scrollback`. I will attach my profile with this post so you can import it directly.

I make use of ligatures and anti-aliasing for my text. For fonts, I use powerline patched fonts, specifically Inconsolata. Download link above.

![iTerm Text Settings](/blog/assets/iterm2-text.png "iTerm Text Settings")

For colors, I use cobalt2. It is a theme created by Wes Bos. Download link above.

![iTerm Color Settings](/blog/assets/iterm2-color.png "iTerm Color Settings")

Here is my iTerm2 profile I promised. You might have to change the `Working Directory`. Direct link to my profile JSON is [here](https://gist.github.com/bhagatparwinder/200f769bd4418d977c43170b055a3edc). I keep it up to date. Happy Coding 👨🏼‍💻

```json
{
  "Set Local Environment Vars" : true,
  "Working Directory" : "\/Users\/Parwinder",
  "Prompt Before Closing 2" : 0,
  "Selected Text Color" : {
    "Green Component" : 0.70916998386383057,
    "Red Component" : 0.70916998386383057,
    "Blue Component" : 0.70916998386383057
  },
  "Rows" : 45,
  "Ansi 11 Color" : {
    "Green Component" : 0.78536456823348999,
    "Red Component" : 0.92833864688873291,
    "Blue Component" : 0.035555899143218994
  },
  "Use Italic Font" : true,
  "Foreground Color" : {
    "Green Component" : 1,
    "Red Component" : 1,
    "Blue Component" : 1
  },
  "Right Option Key Sends" : 0,
  "Character Encoding" : 4,
  "Selection Color" : {
    "Green Component" : 0.20615114271640778,
    "Red Component" : 0.09597768634557724,
    "Blue Component" : 0.31055498123168945
  },
  "Triggers" : [

  ],
  "Blend" : 0.30000001192092896,
  "Mouse Reporting" : true,
  "Ansi 4 Color" : {
    "Green Component" : 0.37805050611495972,
    "Red Component" : 0.079237513244152069,
    "Blue Component" : 0.82438474893569946
  },
  "Non-ASCII Anti Aliased" : true,
  "Sync Title" : false,
  "Disable Window Resizing" : true,
  "Close Sessions On End" : true,
  "Jobs to Ignore" : [
    "rlogin",
    "ssh",
    "slogin",
    "telnet"
  ],
  "Non-ASCII Ligatures" : true,
  "Scrollback Lines" : 0,
  "Scrollback in Alternate Screen" : true,
  "Scrollback With Status Bar" : false,
  "Hide After Opening" : false,
  "Flashing Bell" : false,
  "Cursor Guide Color" : {
    "Red Component" : 0.70213186740875244,
    "Color Space" : "sRGB",
    "Blue Component" : 1,
    "Alpha Component" : 0.25,
    "Green Component" : 0.9268307089805603
  },
  "BM Growl" : true,
  "Ansi 3 Color" : {
    "Green Component" : 0.89706093072891235,
    "Red Component" : 0.99814993143081665,
    "Blue Component" : 0.039139740169048309
  },
  "Link Color" : {
    "Red Component" : 0,
    "Color Space" : "sRGB",
    "Blue Component" : 0.73423302173614502,
    "Alpha Component" : 1,
    "Green Component" : 0.35916060209274292
  },
  "Shortcut" : "",
  "Background Image Location" : "",
  "Bold Color" : {
    "Green Component" : 0.98771905899047852,
    "Red Component" : 0.96919095516204834,
    "Blue Component" : 1
  },
  "Unlimited Scrollback" : true,
  "Custom Command" : "No",
  "Smart Selection Rules" : [
    {
      "notes" : "Word bounded by whitespace",
      "regex" : "\\S+",
      "precision" : "low"
    },
    {
      "notes" : "C++ namespace::identifier",
      "regex" : "([a-zA-Z0-9_]+::)+[a-zA-Z0-9_]+",
      "precision" : "normal"
    },
    {
      "notes" : "Paths",
      "regex" : "\\~?\/?([[:letter:][:number:]._-]+\/+)+[[:letter:][:number:]._-]+\/?",
      "precision" : "normal"
    },
    {
      "notes" : "Quoted string",
      "regex" : "@?\"(?:[^\"\\\\]|\\\\.)*\"",
      "precision" : "normal"
    },
    {
      "notes" : "Java\/Python include paths",
      "regex" : "([[:letter:][:number:]._]+\\.)+[[:letter:][:number:]._]+",
      "precision" : "normal"
    },
    {
      "notes" : "mailto URL",
      "regex" : "\\bmailto:([a-z0-9A-Z_]+@)?([a-zA-Z0-9\\-]+\\.)*[a-zA-Z0-9\\-]+\\b",
      "precision" : "normal"
    },
    {
      "notes" : "Obj-C selector",
      "regex" : "@selector\\([^)]+\\)",
      "precision" : "high"
    },
    {
      "notes" : "email address",
      "regex" : "\\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\\.[A-Za-z]{2,4}\\b",
      "precision" : "high"
    },
    {
      "notes" : "HTTP URL",
      "regex" : "https?:\/\/([a-z0-9A-Z]+(:[a-zA-Z0-9]+)?@)?[a-z0-9A-Z]+(\\.[a-z0-9A-Z]+)*((:[0-9]+)?)(\/[a-zA-Z0-9;\/\\.\\-_+%~?&@=#\\(\\)]*)?",
      "precision" : "very_high"
    },
    {
      "notes" : "SSH URL",
      "regex" : "\\bssh:([a-z0-9A-Z_]+@)?([a-zA-Z0-9\\-]+\\.)*[a-zA-Z0-9\\-]+\\b",
      "precision" : "very_high"
    },
    {
      "notes" : "Telnet URL",
      "regex" : "\\btelnet:([a-z0-9A-Z_]+@)?([a-zA-Z0-9\\-]+\\.)*[a-zA-Z0-9\\-]+\\b",
      "precision" : "very_high"
    }
  ],
  "Keyboard Map" : {
    "0xf700-0x260000" : {
      "Text" : "[1;6A",
      "Action" : 10
    },
    "0x37-0x40000" : {
      "Text" : "0x1f",
      "Action" : 11
    },
    "0x32-0x40000" : {
      "Text" : "0x00",
      "Action" : 11
    },
    "0xf709-0x20000" : {
      "Text" : "[17;2~",
      "Action" : 10
    },
    "0xf70c-0x20000" : {
      "Text" : "[20;2~",
      "Action" : 10
    },
    "0xf729-0x20000" : {
      "Text" : "[1;2H",
      "Action" : 10
    },
    "0xf72b-0x40000" : {
      "Text" : "[1;5F",
      "Action" : 10
    },
    "0xf705-0x20000" : {
      "Text" : "[1;2Q",
      "Action" : 10
    },
    "0xf703-0x260000" : {
      "Text" : "[1;6C",
      "Action" : 10
    },
    "0xf700-0x220000" : {
      "Text" : "[1;2A",
      "Action" : 10
    },
    "0xf701-0x280000" : {
      "Text" : "0x1b 0x1b 0x5b 0x42",
      "Action" : 11
    },
    "0x38-0x40000" : {
      "Text" : "0x7f",
      "Action" : 11
    },
    "0x33-0x40000" : {
      "Text" : "0x1b",
      "Action" : 11
    },
    "0xf703-0x220000" : {
      "Text" : "[1;2C",
      "Action" : 10
    },
    "0xf701-0x240000" : {
      "Text" : "[1;5B",
      "Action" : 10
    },
    "0xf70d-0x20000" : {
      "Text" : "[21;2~",
      "Action" : 10
    },
    "0xf702-0x260000" : {
      "Text" : "[1;6D",
      "Action" : 10
    },
    "0xf729-0x40000" : {
      "Text" : "[1;5H",
      "Action" : 10
    },
    "0xf706-0x20000" : {
      "Text" : "[1;2R",
      "Action" : 10
    },
    "0x34-0x40000" : {
      "Text" : "0x1c",
      "Action" : 11
    },
    "0xf700-0x280000" : {
      "Text" : "0x1b 0x1b 0x5b 0x41",
      "Action" : 11
    },
    "0x2d-0x40000" : {
      "Text" : "0x1f",
      "Action" : 11
    },
    "0xf70e-0x20000" : {
      "Text" : "[23;2~",
      "Action" : 10
    },
    "0xf702-0x220000" : {
      "Text" : "[1;2D",
      "Action" : 10
    },
    "0xf703-0x280000" : {
      "Text" : "0x1b 0x1b 0x5b 0x43",
      "Action" : 11
    },
    "0xf700-0x240000" : {
      "Text" : "[1;5A",
      "Action" : 10
    },
    "0xf707-0x20000" : {
      "Text" : "[1;2S",
      "Action" : 10
    },
    "0xf70a-0x20000" : {
      "Text" : "[18;2~",
      "Action" : 10
    },
    "0x35-0x40000" : {
      "Text" : "0x1d",
      "Action" : 11
    },
    "0xf70f-0x20000" : {
      "Text" : "[24;2~",
      "Action" : 10
    },
    "0xf703-0x240000" : {
      "Text" : "[1;5C",
      "Action" : 10
    },
    "0xf701-0x260000" : {
      "Text" : "[1;6B",
      "Action" : 10
    },
    "0xf702-0x280000" : {
      "Text" : "0x1b 0x1b 0x5b 0x44",
      "Action" : 11
    },
    "0xf72b-0x20000" : {
      "Text" : "[1;2F",
      "Action" : 10
    },
    "0x36-0x40000" : {
      "Text" : "0x1e",
      "Action" : 11
    },
    "0xf708-0x20000" : {
      "Text" : "[15;2~",
      "Action" : 10
    },
    "0xf701-0x220000" : {
      "Text" : "[1;2B",
      "Action" : 10
    },
    "0xf70b-0x20000" : {
      "Text" : "[19;2~",
      "Action" : 10
    },
    "0xf702-0x240000" : {
      "Text" : "[1;5D",
      "Action" : 10
    },
    "0xf704-0x20000" : {
      "Text" : "[1;2P",
      "Action" : 10
    }
  },
  "Log Directory" : "",
  "Use Canonical Parser" : false,
  "Ansi 14 Color" : {
    "Green Component" : 0.89121149225051699,
    "Red Component" : 0.41672572861338453,
    "Blue Component" : 0.97867441177368164
  },
  "Ansi 2 Color" : {
    "Green Component" : 0.87031603506787336,
    "Red Component" : 0.21895777543895642,
    "Blue Component" : 0.13008742736566298
  },
  "Background Image Is Tiled" : false,
  "Send Code When Idle" : false,
  "ASCII Anti Aliased" : true,
  "Tags" : [

  ],
  "Ansi 9 Color" : {
    "Green Component" : 0.052976857870817184,
    "Red Component" : 0.95708823204040527,
    "Blue Component" : 0.090362116694450378
  },
  "Use Bold Font" : true,
  "Silence Bell" : false,
  "Ansi 12 Color" : {
    "Green Component" : 0.3333333432674408,
    "Red Component" : 0.3333333432674408,
    "Blue Component" : 1
  },
  "Window Type" : 0,
  "Allow Title Reporting" : false,
  "Use Bright Bold" : true,
  "Cursor Text Color" : {
    "Green Component" : 1,
    "Red Component" : 0.99659550189971924,
    "Blue Component" : 0.9480862021446228
  },
  "Default Bookmark" : "No",
  "Cursor Color" : {
    "Green Component" : 0.79959547519683838,
    "Red Component" : 0.94297069311141968,
    "Blue Component" : 0.03614787757396698
  },
  "Disable Smcup Rmcup" : false,
  "Name" : "Default",
  "Blinking Cursor" : false,
  "Guid" : "59BB2A49-982B-40F8-9423-BAA42EB8F948",
  "Ansi 1 Color" : {
    "Green Component" : 0,
    "Red Component" : 1,
    "Blue Component" : 0
  },
  "Idle Code" : 0,
  "Ansi 10 Color" : {
    "Green Component" : 0.81519794464111328,
    "Red Component" : 0.23300750553607941,
    "Blue Component" : 0.11517760157585144
  },
  "Ansi 8 Color" : {
    "Green Component" : 0.33333333333333331,
    "Red Component" : 0.33333333333333331,
    "Blue Component" : 0.33333333333333331
  },
  "Badge Color" : {
    "Red Component" : 1,
    "Color Space" : "sRGB",
    "Blue Component" : 0,
    "Alpha Component" : 0.5,
    "Green Component" : 0.1491314172744751
  },
  "Automatically Log" : false,
  "Smart Cursor Color" : true,
  "Semantic History" : {
    "action" : "best editor",
    "text" : "",
    "editor" : "com.sublimetext.3"
  },
  "Ambiguous Double Width" : false,
  "Blur Radius" : 2,
  "Ansi 0 Color" : {
    "Green Component" : 0,
    "Red Component" : 0,
    "Blue Component" : 0
  },
  "Cursor Type" : 2,
  "Blur" : false,
  "Normal Font" : "InconsolataForPowerline 14",
  "Vertical Spacing" : 1,
  "Disable Printing" : false,
  "Ansi 7 Color" : {
    "Green Component" : 0.73333334922790527,
    "Red Component" : 0.73333334922790527,
    "Blue Component" : 0.73333334922790527
  },
  "Command" : "",
  "Terminal Type" : "xterm-256color",
  "Horizontal Spacing" : 1,
  "Option Key Sends" : 0,
  "Blink Allowed" : false,
  "Minimum Contrast" : 0,
  "Ansi 15 Color" : {
    "Green Component" : 1,
    "Red Component" : 1,
    "Blue Component" : 1
  },
  "Ansi 6 Color" : {
    "Green Component" : 0.73333334922790527,
    "Red Component" : 0,
    "Blue Component" : 0.73333334922790527
  },
  "Transparency" : 0.021613801892339839,
  "Initial Text" : "",
  "Background Color" : {
    "Green Component" : 0.15233974158763885,
    "Red Component" : 0.073702715337276459,
    "Blue Component" : 0.21839480102062225
  },
  "Screen" : -1,
  "Non Ascii Font" : "InconsolataForPowerline 12",
  "Ansi 13 Color" : {
    "Green Component" : 0.3333333432674408,
    "Red Component" : 1,
    "Blue Component" : 1
  },
  "Columns" : 120,
  "Visual Bell" : true,
  "ASCII Ligatures" : true,
  "Custom Directory" : "No",
  "Ansi 5 Color" : {
    "Green Component" : 0,
    "Red Component" : 1,
    "Blue Component" : 0.36536297202110291
  }
}
```
