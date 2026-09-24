# RAW GAME firmware 13.52 integration

Source: https://github.com/raw13g/raw13g.github.io
Live upstream: https://raw13g.github.io/
Snapshot: ef1670a8db0beb49b942dfacced6edbc5225f47c

Upstream runtime files were copied into this directory. The two HTML pages
now display the FCB Gaming Center name and logo; their scripts are unchanged.
The application cache includes the local FCB logo and updated file hashes.
Relative asset, worker, module, payload and application-cache URLs remain
inside `/1352/`. The FCB selector links here and remembers this choice.
Use `/?choose=1` to return to the firmware selector.

The upstream selector lists 13.02, 13.04, 13.50 and 13.52. The FCB entry is
labeled 13.52 as requested. The updated upstream includes GoldHEN (`goldhen.bin` and `payload2.bin`);
13.52 selects `goldhen.bin`. Snapshot includes the upstream AIO fix.
Other FCB firmware hosts retain their own files and behavior.

The source snapshot includes no standalone license. Upstream attribution and
embedded code notices are preserved; FCB claims no ownership of upstream work.

Static integration checks do not establish jailbreak success or stability.
Actual operation and offline caching must be verified on a PS4 with 13.52.
