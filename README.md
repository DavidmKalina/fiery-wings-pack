# Fiery Wings resource pack

A tiny Minecraft resource pack (26.3, pack format 97) used by the FieryWings plugin on my server.
It gives the "Fiery Winged Chestplate" its look: the normal netherite chestplate plus elytra wings
with a fire-coloured texture.

The server sends players the link to `fiery-wings.zip` when they join, so there's nothing to install
by hand.

- `assets/fierywings/equipment/fiery_wings.json`: the equipment look (netherite chestplate layers + wings)
- `assets/fierywings/textures/entity/equipment/wings/fiery_wings.png`: the fiery wing texture
- `assets/minecraft/textures/item/beetroot.png`, `textures/block/beetroots_stage0-3.png`: beetroots look like bananas (green while growing, yellow when ripe)
- `assets/minecraft/textures/item/beetroot_soup.png`: beetroot soup is a cheesecake gone wrong
- `assets/minecraft/lang/en_*.json`: renames them Banana, Banana Seeds, Bananas and Cumpot
- `assets/ghastbreath/`: for the GhastBreath plugin, a happy ghast that has had dragon's breath looks like a regular ghast. `textures/entity/equipment/happy_ghast_body/ghast_face.png` is the ghast's body laid out for the harness model (which sits exactly around the body), and `equipment/ghast_*_harness.json` draw each harness colour over it (`ghast_face.json` = no harness)
