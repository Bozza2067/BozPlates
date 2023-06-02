# BozPlates

I was inspired to make this script when I saw someone charging money to to this basic stuff. Enjoy my free version :P. Open source ftw!

FiveM Forum Post: https://forum.cfx.re/t/bozplates-customise-your-plate-textures-and-text-format/5110919

## Pattern string format

- 1 will lead to a random number from 0-9.
- A will lead to a random letter from A-Z.
- . will lead to a random letter or number, with 50% probability of being either.
- ^1 will lead to a literal 1 being emitted.
- ^A will lead to a literal A being emitted.
- Any other character will lead to said character being emitted.
- A string shorter than 8 characters will be padded on the right.
- A space bar will make a space in the string.

### Example:

- "F^AYUM11A" may produce FAYUM69C as an example.

## Custom plate textures

- To modify the plate textures, open the plates.ytd file in your favourite modding tool, for example OpenIV or CodeWalker. Replace the included textures with your new ones. Do not change the names. For best quality, use .dds texture format with DXT1 compression and mipmaps. (Exception: vehicle_generic_plate_font should use L8 compression with no mipmaps in order to function properly)
