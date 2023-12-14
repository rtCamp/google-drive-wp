Embed Google Drive
=========================

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

Embed a link and preview of Google Drive Documents by pasting a shared document link into the editor.

**Requires at least:** 5.5

**Tested up to:** 6.4

**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)

**Requires PHP:** 8.0+

## Installation

1. Download the plugin from [here](https://wordpress.org/plugins/embed-google-drive/)
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/56588503/290548823-0a2faf19-c9c4-4ea9-bed0-52f28fd66e3a.png" />
2. Add the plugin from the WordPress admin panel.
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/56588503/290547568-462f110a-7bf0-4b2d-84fb-5e1d92226bdb.png" />
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/56588503/290549849-4742d951-b798-4d0d-b1ef-edfd5e13dbc5.png" />
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/56588503/290550134-147a5435-5458-4abf-bf74-4c6990da2da3.png" />
3. Activate the plugin through the 'Plugins' menu in WordPress
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/56588503/290550390-6ee9cac6-0b57-460d-bd53-68c4cf376f68.png" />
3. Paste a shared Google Drive document link into the WordPress editor.

## Development Notes

##### Please run following commands from the root directory.

1. Please verify your code is in compliance to the Coding Standards used in this Project.
2. Run `composer phpcs filename` or `composer phpcs` to check for PHPCS errors/warnings.

#### Building Plugin assets

- Run ```npm install``` from repositories root to install all required dependencies.
- To build a production version run `npm run build`.
- While developing the plugin run `npm run dev` to build assets on file changes.
- If any string is added/updated, run `npm run language` to update the language file. ( Assumes availability of `wp i18n` command. )

## Does this interest you?

<a href="https://rtcamp.com/"><img src="https://rtcamp.com/wp-content/uploads/sites/2/2019/04/github-banner@2x.png" alt="Join us at rtCamp, we specialize in providing high performance enterprise WordPress solutions"></a>
