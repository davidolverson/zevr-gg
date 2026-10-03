# Hero network card art

Owner decision, 2026-09-30 (David): use the generated ZEVR hero asset pack
module images in the homepage hero cards as delivered, people included. The
people in these images are generated; they are not ZEVR talent, creators or
staff, and the page makes no claim that they are.

The one condition: **every Z is the canonical FORGED Z.** Each image was:

1. cropped to its scene, excluding the titles and figures baked into the
   generated card (no "+42%", no "ZEVR INVITATIONAL", no baked UI text);
2. had every generated Z and the generated "ZEVR" desk lettering painted out
   (OpenCV inpaint), including an out-of-focus one in the media background;
3. had `public/brand/ZEVR-SYMBOL-MASTER-REVERSE.svg`, rendered white at scale
   with its geometry untouched, composited where a mark stands: the
   competition stage screen and banner, the partnerships stage wall and a
   jacket, a media crew jacket, the talent headset. Lit signs carry a tinted
   glow drawn from the mark's own silhouette, behind it.

Sources: `ChatGPT Image Sep 30, 2026, 05_34_20 PM-3` (talent) through
`…05_34_25 PM-8` (partnerships). Do not replace these with art carrying a
non-canonical mark.

## Floating tiles (`tile-*.webp`)

Small screens around the network, matching the approved mock. Cropped from the
same pack (talent and creator side thumbnails, the partnerships stage screen),
inside their frames. `tile-stream` and `tile-field` had a generated Z on a
jacket; each was painted out and the canonical symbol composited in its place.
