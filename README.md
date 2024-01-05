# Turn Off Windows Copilot

This repository contains a single Registration Entries file that disables Windows Copilot.

[Download `TurnOffWindowsCopilot.reg`](https://github.com/thankfulmachine/TurnOffWindowsCopilot/files/13839982/TurnOffWindowsCopilot.zip)
and open it to disable it.

You must restart your machine for the registry key to take effect.

## Explanation

The file, `TurnOffWindowsCopilot.reg`, should contain **only the following**:

```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\WindowsCopilot]
"TurnOffWindowsCopilot"=dword:00000001
```

The sets the above key in your Windows registry, disabling the `Windows + C`
keyboard shortcut and removes it as an option for the task bar.

## Reminders

Always check the contents of any .reg file in a plain text editor first.
If you see *anything else* in the file, do not import it into the Registry Editor.

The Registry Editor has broken machines before.
Hopefully, this change is simple enough for you to understand.

Still, use this capability at your own risk.

## Final Remarks

It's up to you to fight against the theft and commoditization of the arts by
companies who [train their systems on our works](https://cybernews.com/news/midjourney-ai-images-art-lawsuit-copyright/)
without our informed and explicit consent.

Changing our society to make activities like that illegal and consequential is *your responsibility*.

There is a unique path through your life's experiences that drives your creativity, allowing you to tell your story.

It's still yours. It's still important.

Don't let them take that away from you.
