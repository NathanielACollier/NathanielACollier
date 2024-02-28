# Nathaniel's HomePage

## Applications

### [WebPad](https://github.com/NathanielACollier/WebPad)
+ Html editor with live preview.  Splits css,javascript, and html into seperate panes for easier editing.
  + I'm working on a port of this to avalonia [here](https://github.com/NathanielACollier/dotnetCoreAvaloniaWebPad).  It will use the forms library instead of xaml.
### [nacPDFEdit](https://github.com/NathanielACollier/nacPDFEditor)
+ Simple PDF Viewer with minor editing capability.  Not much here yet.  Written with avalonia via nac.Forms.
### [Clipboard Manager](https://github.com/NathanielACollier/repl_csharp_sln/tree/main/Utilities/WindowsOnly/WindowsClipboardManager)
+ Shows you what picture is currently on your clipboard.  A program to convert pictures into base64 str from the clipboard.
+ shows you what text is currently on your clipboard
+ Windows only
## [Git Repo Finder](https://github.com/NathanielACollier/repl_csharp_sln/tree/main/Utilities/GitRepoFinder)
+ Provides a way to manage and filter local git repos.
+ Generally people store their git repos in a common git repo, so this program can traverse down and list all git repos in that folder.  It gives you an open in file manager button to be able to quickly access git repos
## [nacBackup](https://github.com/NathanielACollier/nacBackup)
+ Written in WPF, runs on windows only right now
+ Provides a way to create sets of local folders.  Zips them up, with notes.  Provides a way to view past zips and display the notes you made
+ Has multiple use cases, was originally written to manage versions of files
## Libraries

### [Curl Http client](https://github.com/NathanielACollier/dotnetLib_nac.CurlHttpClient)
+ Provides high level http getJson, postJson very similar to what you can do with `System.Net.Http.HttpClient`.  Uses `Newtonsoft.jSON` and [CurlThin](https://github.com/stil/CurlThin) to make curl calls and interpret the results.
+ `libcurl` access is wrapped up inside a thin low level [http client](https://github.com/NathanielACollier/dotnetLib_nac.CurlHttpClient.LowLevel).

### [nac.Forms](https://github.com/NathanielACollier/dotnetLib_nac.Forms)
+ Uses the `Avalonia` library to make creating user interfaces quickly.
	+ [nac.wpf.forms](https://github.com/NathanielACollier/ncWPFFormsLib)
		+ Original project written in WPF.

#### Supporting Libraries
+ [nac.logging](https://github.com/NathanielACollier/dotnetLib_nac.Logging)
  + Simple event based logging library
+ [nac.WebServer](https://github.com/NathanielACollier/dotnetLib_nac.WebServer)
  + Provides a way to serve web requests simply.  Used in WebPad to implement the live server view.
+ [nac.CSSParsing](https://github.com/NathanielACollier/dotnetLib_nac.CSSParsing)
  + Provides css parsing into structure
+ [nac.json](https://github.com/NathanielACollier/dotnetLib_nac.json)
  + Makes working with json easier
+ [nc.http](https://github.com/NathanielACollier/dotnetLib_nac.http/)
  + Library to make working with http calls easier
