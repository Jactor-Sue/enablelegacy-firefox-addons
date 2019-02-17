# VimFx legacy usage

## Requires

- Firefox Version : 60.0.1 x64
- VimFx Version : 0.20.13

## Steps

1. Copy `enablelegacy.js` to `Aapplications` -> `Firefox.app` -> `Contents/Resources`
2. Copy `enablelegacy-prefs.js` to `Aapplications` -> `Firefox.app` -> `Contents/Resources/defaults/pref`
3. Copy `VimFx@akhodakivskiy.github.com` to `~/Library/Application Support/Firefox/Profiles/xxx.default/extensions/`
4. Open Firefox open tab with `about:config`, update options following:
   - `extensions.legacy.enable`: true
   - `xpinstall.signatures.required`: false
5. Restart firefox