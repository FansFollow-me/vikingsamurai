# Petdex submit rules (brand URLs)

## Wrong

Uploading bare `spritesheet.webp` from GitHub created:

- https://petdex.dev/pets/spritesheet-1
- https://petdex.dev/pets/spritesheet-7

## Right

```text
vikingsamurai/
├── pet.json              # "id": "vikingsamurai"
└── spritesheet.webp      # internal standard name
```

Folder or zip **base name** = brand slug. Ready packages: `/submit` in this repo.

## Slugs cannot be renamed

`petdex edit` cannot change slug. Withdraw bad entries, resubmit branded packages.

```bash
npx petdex login
npx petdex submit ./submit/vikingsamurai
npx petdex submit ./submit/vikingsamurai-armor
```
