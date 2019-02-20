# Steps to use legacy addons

## Mac

1. Copy `enablelegacy.js` to `Aapplications` -> `Firefox.app` -> `Contents/Resources`
2. Copy `enablelegacy-prefs.js` to `Aapplications` -> `Firefox.app` -> `Contents/Resources/defaults/pref/`
3. Copy `xxx@yyy.xpi` to `~/Library/Application Support/Firefox/Profiles/xxx.default/extensions/`
4. Open Firefox open tab with `about:config`, update options:
   - `extensions.legacy.enable`: true
   - `xpinstall.signatures.required`: false
5. Restart firefox

## Linux

1. Copy `enablelegacy.js` to Firefox home directory.
2. Copy `enablelegacy-prefs.js` to `/defaults/pref/` under Firefox home directory.
3. Copy `xxx@yyy.xpi` to `~/.mozilla/firefox/xxx.default/extensions/`
4. Open Firefox open tab with `about:config`, update options:
   - `extensions.legacy.enable`: true
   - `xpinstall.signatures.required`: false
5. Restart firefoX