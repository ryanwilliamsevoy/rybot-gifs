# RyBot reaction GIFs

The character is RyBot, a compact navy-and-white boxy robot. It has a dark screen face with glowing cyan eyes and a smile, a white sailor cap, an antenna tipped with a yellow lightning bolt, and a lightning bolt on its chest. It sits on a plain grey-teal background.
All GIFs are 340x340, 12 fps, loop forever, and are under 1.4 MB.

| File | Use it for |
|---|---|
| rybot_ref.png | Character reference / avatar (1024x1024) |
| rybot_bow.gif | Thanks / "cheers" / accepting praise |
| rybot_thumbsup.gif | Nice one / agreed / sounds good |
| rybot_mindblown.gif | Mind blown / "wait what" / impressive result |
| rybot_facepalm.gif | Something daft happened / known bug strikes again |
| rybot_onit.gif | "On it" / working on it / typing furiously |
| rybot_done.gif | Done / sorted / shipped (dusts hands + victory spin) |
| rybot_shrug.gif | No idea / out of my hands / "it is what it is" |
| rybot_celebrate.gif | Big win / release out / test passed |
| rybot_bencat.gif | bencat: for Ben Ludlam, new topic (RyBot + orange cat typing furiously) |

## Sending in Teams
- The proven route is the one the cat GIF already uses: `--body '<div><img src="https://PUBLIC_URL/rybot_x.gif" width="280"></div>'`. This needs the GIF hosted at a public https URL.
- `--image /path/rybot_x.gif` sends it as Graph hostedContents with contentType image/gif. This is untested. Graph may reject image/gif, or Teams may show only a still frame.
