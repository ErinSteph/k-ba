# K-ba~

K-ba is (currently) a single javascript file designed to give
[Kusaba X](http://kusabax.cultnet.net/) based imageboards advanced
features such as image hovers, reply backlinks, animated thumbnails 
and so on, without the compatibility problems that have plagued
such extensions in the past.

## Install~

Very simple.

1. Upload `k-ba.js` to `yourchan/lib/javascript/`
2. Add `<script type="text/javascript" src="{$cwebpath}lib/javascript/k-ba.js"></script>`
   above `</body>` in `/dwoo/templates/global_board_footer.tpl`, and rebuild your html files.
3. ?????
4. Hookers.

### Credits~

James Campos,
Nicolas Stepien,
and other contributors to 4chan X, who lay the foundations for things
like the backlinks, the gif animator, and the auto updater (when it's in).

Author of Rorichan X.
I still don't know who this is.
Rorichan X is modified copy of an old version of 4chan X that runs
on brchan, rorichan, xchan and ligadosaterra.
From it I took the backlinks, gif animator, and updater, and forked
more portable versions.
I found it on pastebin, uploaded by a guest, and the only credit was 
to James Campos. 
Please make yourself known :3

Jmyeom.
Some neat portability fixes for the backlinks, and I'm sure I'll
coerce more out of him before we're done here c:

Madchan's Admin.
I still don't know his name, but he wrote the lines that add "Replies:"
before backlinks. We had a thread flailing about like retards trying to
do that without modifying the templates for days. It's not even funny.


