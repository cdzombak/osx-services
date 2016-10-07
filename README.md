# osx-services

Custom OS X services (and Applescripts) that make my life easier. Designed to be triggered via OS X's Services or via FastScripts.

## The Scripts/Services

### Archive nvALT Note

Moves the selected note in nvALT to the `Archive` subfolder in your notes directory.

### Copy Message Link

Copies a link to the currently-selected message in Mail.app.

### Copy Public Dropbox Link

Service-based version of [cdzombak/qs-public-dropbox-link](https://github.com/cdzombak/qs-public-dropbox-link).

### Generate QR Code

Generates a QR code from the selected text.

### Eject External Disks

Ejects the external USB disks typically attached to my laptop while at my desk at home. This can be triggered via `Shift-Control-U` to quickly unmount when I want my laptop to be portable again.

It opens `/Volumes` in Finder so I can verify when the disks have been unmounted as expected.

### OmniFocus Quick Open

Opens OmniFocus’s “Quick Open” dialog. Work best when run via FastScripts shortcut, because OS X doesn’t seem to want to grant ‘Automator Runner.app’ privileges for assistive access.

### Open Selected Text As URL

Opens the selected text as a URL in the system default application.

### Open URL

Asks for a URL and opens it in the system default application.

### Play Fax Sound

Pauses iTunes and Spotify if they’re running, then ensure volume isn’t muted and plays [this fax sound](fax_call_loop.wav).

Answer automated phone calls with this to get yourself removed from autodialer lists.

### Scale Images

Scales the selected images by a given amount (default 50%) and puts the results on the Desktop.

### Send to OmniFocus

Mail.app service for [rentzsch/OmniFocus Selected Mail Messages.applescript](https://gist.github.com/rentzsch/05d155147e894bd2730f).

## Requirements

I currently use these on OS X 10.10. They probably work on other similar OS X versions.

## License

MIT. See `LICENSE` included in this repo.

## Developer

[Chris Dzombak](https://www.dzombak.com)
