# PokeAlliance Sprites

Sprite assets from PokeAlliance (PokéTibia - OTCv8-based Pokémon MMO), exported from the client's `.spr` into individual PNGs.

Most files are sheets, not single frames. Dimensions are multiples of the 32×32 base tile, so animation sits inside the same image. An outfit at 256×192 is a 4×3 grid of 64×64 cells, and effects are tall strips of stacked frames.

| Folder | Files | Size | Common size |
| --- | --- | --- | --- |
| `itens` | 51,897 | 171 MB | 32×32 |
| `effects` | 2,887 | 242 MB | 96×672, 64×864 |
| `outfits` | 3,999 | 72 MB | 256×192 |
| `missiles` | 251 | 1.2 MB | 96×96 |

Names carry the sprite id from the `.dat`, zero-padded, so they sort the way you'd expect: `item_00100.png`, `outfit_0001.png`, `missile_001.png`.

Folders on GitHub cap at 1,000 files, split by id range (`itens/00000-00999/`, `effects/2000-2999/`). `missiles` stays flat at 251.

The PNGs are bare: `IHDR`, `IDAT`, `IEND` and nothing else.

---

Pokémon and all related names, characters, and assets are trademarks and copyrights of Nintendo, Creatures Inc., GAME FREAK inc., and The Pokémon Company. Engine assets derived from Tibia are property of CipSoft GmbH.
