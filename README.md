# OuterWatch
A smartwatch face (roughly) based off of Outer Wilds

Hey there, I recently played Outer Wilds (which is a very good game, please go play it if you haven't already) and I wanted to make a watch face, so I combined them and made an OW-inspired face!

These files were made in mind for a Samsung Galaxy Watch Active2, but can be adapted to any type

These files were made for use in Galaxy Watch Studio (GWS), but can be adapted for other programs.

In the SVG, there are two different faces; one designed in mind with a lower battery complication, and one with a lower sunrise/sunset time complication. I was originally planning on making it with a sunrise/sunset complication, but GWS doesn't support that, so I just did a battery complication.

There is also a color pallete which I used, based off of the in-game colors. There is also a different 24-hour hour "ring."

If you want 12-hour time, just change each number in the dial.

It should be noted that everything here is based off of a 30px square grid. You can find relative dimensions from that.

If you prepare the SVG, you're on your own, as quite frankly I can't be bothered to write a detailed description for the process. Just export each part to a png in the right size and you'll be fine (if you're using Inkscape, just scale everything up or down and you'll be fine!)

The font used is `Space Mono Regular`. It can be found [here on Google Fonts.](https://fonts.google.com/specimen/Space+Mono)

There are many different PNGs, but don't worry! It's simpler than it looks. The parts consist of:

- `OuterWilds.gwd` is the GWS file. This is the easiest if you want to get up and running

- `alignmentcross.png` is for decoration. The design is based off of alignment crosses(?), specifically from the Apollo(?) missions. I actually ended up using it for alignment of text, funny enough.
- `background.png` is pretty self-explanatory. It's entirely stationary, and has a pointer for the hour ring.
- `battbar.png` is the battery bar.
- `battbarblocker.png` masks the battery bar, because Samsung is weird and doesn't have progress bars built into GWS.
- `battbarcap.png` layers on top of `battbarblocker.png` to cover up the end.
- `batteryarrow.png` is an arrow that points to where the battery level is on the battery bar.
- `chroma.png` is a mask used for chromatic aberration. In GWS, I had three copies, one red, one green, and one blue, and had them all respond to the gyroscope in slightly more exaggerated ways.
- `datetime.png` is the line seperating the month/date from the weekday/year.
- `index.png` is the hour "ring." It rotates counterclockwise to appear as if the pointer (in `background.png`) is rotating clockwise.
- `index.svg` is the main SVG file. It's formatted in Inkscape's flavor of SVG.
- `index_plainsvg.svg` is a standard formatted SVG. I have not tested this or looked at it.
- `secondhand.png` is the second hand.
- `secondhandindex.png` is the second hand's index.
- `ship.png` is the ship from OW! I had it set to tilt and move slightly (around 25px in every direction) with the gyroscope's movement.
- `suns.png` is the outline for the sunrise/sunset complication. Sunrise on top, sunset on the bottom.
- `whole.png` is the overall watchface, for this GitHub repo. The battery arrow doesn't match up with the battery bar in this image but it's 01:20 so I frankly don't care.

Thanks for checking out my watch face, and best of luck to you!

P.S. I am not in any way affiliated with Mobius Interactive, Annapura, or anyone else.
