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

## Libraries

### [Curl Http client](https://github.com/NathanielACollier/dotnetLib_nac.CurlHttpClient)
+ Provides high level http getJson, postJson very similar to what you can do with `System.Net.Http.HttpClient`.  Uses `Newtonsoft.jSON` and [CurlThin](https://github.com/stil/CurlThin) to make curl calls and interpret the results.
+ `libcurl` access is wrapped up inside a thin low level [http client](https://github.com/NathanielACollier/dotnetLib_nac.CurlHttpClient.LowLevel).

### [nac.Forms](https://github.com/NathanielACollier/dotnetLib_nac.Forms)
+ Uses the `Avalonia` library to make creating user interfaces quickly.

### [nac.Forms.Table](https://github.com/NathanielACollier/dotnetLib_nac.Forms.Table)
+ Uses the `Avalonia` library to make creating UI with Table displays quick.
