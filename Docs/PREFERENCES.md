Clearinet is designed to allow easy customization via preferences. Eventually, you'll be able to override any
preference by typing `about:config` in the QuickExec box below the Web Exchanges list. For now, you can
type `prefs <show> nameofpref`  or `prefs set nameofpref newvalue`

Below is a list of some preferences, their defaults, and what they control

"app.ui.toolbar.lookupcuetext", "Search MDN..." => The "Search MDN..." cuetext in the toolbar.
"app.saz.warn_about_data_protection", true => Whether to warn the user about sharing SAZ files that may contain private information.
"app.ui.toolbar.lookupurl", "https://developer.mozilla.org/en-US/search?q=$W$" => The target of the lookup tool in the toolbar.
"app.high_resolution_clock", true => Whether the app should tell Windows to increase timer resolution for improved accuracy in timing scenarios.
"inspectors.headers.highlighted_names", "content-type,content-length,host" => change the color of more important headers

`app.paths.rulesscript` defaults to `Documents\Clearinet\Scripts\CustomRules.js`.
Scripting is optional: a missing file or empty path disables scripting without
preventing startup or shutdown. Clearinet does not install or generate a rules
script. You can supply your own file or override this preference with its path.
Invalid or unreadable scripts still report errors rather than being treated as
absent.