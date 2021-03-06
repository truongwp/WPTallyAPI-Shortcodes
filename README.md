# WPTallyAPI-Shortcodes
`[wta]` Shortcode to obtain total plugins count and total plugins downloads count attached to a WordPress.org Username. 

NOTE: WPTallyAPI-Shortcodes plugin uses transients to cache the counts for `24 * HOUR_IN_SECONDS`.

## Shortcode
- `[wta]` shortcode accepts following parameters
    + `u=username` where username is your WP.org username.
    + `p=y` displays total plugins count in your account E.g 11
    + `d=y` displays total plugins downloads count in your account E.g 50,000

### Examples
- Plugins: `[wta u='mrahmadawais' p='y']`
- Plugin Downloads : `[wta u='mrahmadawais' d='y']`

### Screenshot
![](https://i.imgur.com/xcyQg9d.png)

## To do 
- [x] WTA shortcode
- [x] WTA plugin count
- [x] WTA plugin download count
- [x] WTA GitHub Updater & Better Documentation
- [ ] WTA Theme Count
- [ ] WTA Theme Download Count
- [ ] WTA Plugin and Theme Details

## Updates
You can use [GitHub Updater](https://github.com/afragen/github-updater) to receive updates for this plugin. 

## Changelog

## Version 0.0.5
- FIX: Minor change in default returned data.

## Version 0.0.4
- FIX: Main class check.

## Version 0.0.3
- Better documentation.
- GitHub Updater.

### Version 0.0.2
- Transients `24 * HOUR_IN_SECONDS`.
- Better error handling.

### Version 0.0.1
- First beta version.

## License
Copyright (C) 2016  Ahmad Awais

This program is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation; either version 2 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for
more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.


