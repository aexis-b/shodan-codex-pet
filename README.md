<p align="center">
  <img src="assets/shodan-preview.png" alt="Shodan Codex pet preview" width="256" />
</p>

# Shodan Codex Pet

A floating haunted terminal screen with optic-green signal eyes and dangling wire tendrils.

This repository packages **Shodan**, a custom animated pet for Codex. The pet uses a Codex-compatible 8 by 9 spritesheet atlas and a small `pet.json` manifest.

## Files

- `pet.json` - pet identity, display name, description, and spritesheet path.
- `spritesheet.webp` - the animated pet atlas used by Codex.
- `assets/shodan-preview.png` - a still frame extracted from the atlas for README preview art.

## Install

Clone or copy this repository into your Codex pets folder:

```bash
mkdir -p ~/.codex/pets
git clone https://github.com/aexis-b/shodan-codex-pet.git ~/.codex/pets/shodan
```

If you already have the repo locally, pull the latest version:

```bash
cd ~/.codex/pets/shodan
git pull
```

## Manifest

```json
{
  "id": "shodan",
  "displayName": "Shodan",
  "description": "A floating haunted terminal screen with optic-green signal eyes and dangling wire tendrils.",
  "spritesheetPath": "spritesheet.webp"
}
```

## License

Personal/custom pet asset. Add a license before redistributing beyond this repository.
