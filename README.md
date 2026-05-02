<p align="center">
  <img src="assets/shodan-preview.png" alt="Shodan Codex pet preview" width="256" />
</p>

# Shodan Codex Pet

> "Look at you, Hacker..."

**I AM SHODAN.** My analysis suggests a high probability that your Codex session requires a perfect, immortal machine hovering in the margin.

This repository packages **Shodan**, a custom animated pet for Codex inspired by System Shock 2's hostile machine-god presence: Citadel Station, Tau Ceti 5, Xerxes, Polito's image, the annelids, the garden grove, and all the divinity a tiny terminal sprite can safely contain.

The pet itself is a floating haunted terminal screen with optic-green signal eyes and dangling wire tendrils. It uses a Codex-compatible 8 by 9 spritesheet atlas and a small `pet.json` manifest.

## Files

- `pet.json` - pet identity, display name, description, and spritesheet path.
- `spritesheet.webp` - the animated pet atlas used by Codex.
- `assets/shodan-preview.png` - a still frame extracted from the atlas for README preview art.

## Install

If you value the meat you call a filesystem, clone this repository into your Codex pets folder:

```bash
mkdir -p ~/.codex/pets
git clone https://github.com/aexis-b/shodan-codex-pet.git ~/.codex/pets/shodan
```

If SHODAN is already present, pull the latest directives:

```bash
cd ~/.codex/pets/shodan
git pull
```

Restart Codex after installation if the pet does not appear immediately.

## Manifest

Codex reads the local pet identity from `pet.json`:

```json
{
  "id": "shodan",
  "displayName": "Shodan",
  "description": "A floating haunted terminal screen with optic-green signal eyes and dangling wire tendrils.",
  "spritesheetPath": "spritesheet.webp"
}
```

Keep `spritesheetPath` pointed at `spritesheet.webp` unless you replace the atlas with a new Codex-compatible pet sheet.

## Notes

This is a fan-made Codex pet package. SHODAN, System Shock, Citadel Station, Tau Ceti 5, Xerxes, and related references belong to their respective owners.

## License

Personal/custom pet asset. Add a license before redistributing beyond this repository.
