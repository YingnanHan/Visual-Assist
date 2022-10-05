# Release notes 2324

## Bug Fixes

• [VS2017+] Fix for intermittent cases in which completion listbox appears at incorrect screen coordinate after startup (regression). (case=139997)

• Fix for corrupt display of unicode characters that require utf16 surrogate pairs. (case=138734)

• Fix for completion listbox item not being properly entered into editor in some cases when `Insert _ after m and shift` setting is enabled (regression). (case=138729)

• [VS2019] Fix for enable/disable of built-in highlight current line setting. (case=138638)


# Release notes 2331


• **New!** Added support for Visual Studio 16.1 Preview 1, the first version of Visual Studio that requires extensions to load asynchronously.

Visual Assist is completely loaded if it responds to its commands in an editor window, or when notice appears in the status bar.

Visual Assist is not completely loaded if its toolbar begins with disabled icons, its tool windows are empty, or it fails to responds to its commands in an editor window.

• **New!** Added command to insert a file path into the active document (`Alt+X, T, P`). [Learn more](https://docs.wholetomato.com/default.asp?W854).


## Bug Fixes
• [VS2019] VA Step Filter now supports the new `load debug symbols in external process` feature. (case=132670)

• Fix for coloring, in dialogs and tool windows, of identifiers that contain non-ASCII characters. (case=118872)

• Fix for `Add Forward Declaration` producing invalid namespace in some circumstances. (case=137679)

• Fix for conflict with version of AvalonEdit assembly installed by NVidia NSight. (case=132900, case=137033)

• Fix for crash while debugging in some circumstances when the `Child Process Debugging Tool` extension is active. (case=137833)

• Fix for `Implement Virtual Methods` not being offered on specified base class if defined class is declared final. (case=119831)

• Fix for `Implement Virtual Methods` not being offered in some circumstances involving macros. (case=117943)

• Fix for incorrect VA Snippet placeholder handling in some circumstances (regression in 2301). (case=137542)

• [VS2010-VS2013] Fix for flicker of .exe installer when it downgrades to lower versions of .vsix to target IDE versions below VS2015. (case=138045)

• [pre-VS2010] Fix for crash at exit in some circumstances. (case=138040)

• [VC6 (officially unsupported)] Fix for failure of registration dialog to load. (case=137664)
