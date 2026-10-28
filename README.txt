PANDA BROWSER — TABS, BOOKMARKS & PERSONALIZATION UPDATE

Features in this version:
- Multiple tabs: use + Tab to open another tab, and × Tab to close the current tab.
- Bookmarks: click ☆ to save the current page; click ★ to open saved bookmarks and manage them.
- Bookmarks bar: quick-access buttons below the toolbar; toggle it in ⚙ Personalize.
- Themes: Forest Green, Ocean Blue, Midnight Purple, Rose Pink, and Classic Dark.
- Preferences and bookmarks are saved in %LOCALAPPDATA%\PandaBrowser.
- Panda application icon and Home button.

To rebuild using your existing GitHub repository:
1. Extract this ZIP.
2. In your GitHub repository, replace Program.cs with the Program.cs in this folder.
3. Make sure panda.ico, panda.html, PandaBrowser.csproj, and .github/workflows/build-windows.yml are present.
4. Commit the change. GitHub Actions should build automatically.
5. When the run succeeds, download the PandaBrowser-Windows-x64 artifact, extract it, and keep all extracted files together.

Note: this is an early browser project built on Microsoft's WebView2 engine. The Windows WebView2 Runtime must be installed on the PC.
