# Agent and human copy-paste prompts — VikingSamurai

Source: https://github.com/FansFollow-me/VikingSamurai

## Hermes — Classic

```
Install VikingSamurai Classic pet:
git clone --depth 1 https://github.com/FansFollow-me/VikingSamurai.git /tmp/VikingSamurai
mkdir -p ~/.hermes/pets
rm -rf ~/.hermes/pets/vikingsamurai
cp -R /tmp/VikingSamurai/versions/classic ~/.hermes/pets/vikingsamurai
hermes pets select vikingsamurai
hermes pets scale 0.88
hermes pets doctor
```

## Hermes — Armor

```
Install VikingSamurai Armor pet:
git clone --depth 1 https://github.com/FansFollow-me/VikingSamurai.git /tmp/VikingSamurai
rm -rf ~/.hermes/pets/vikingsamurai-armor
cp -R /tmp/VikingSamurai/versions/armor ~/.hermes/pets/vikingsamurai-armor
hermes pets select vikingsamurai-armor
hermes pets scale 0.88
hermes pets doctor
```

## Hermes — both

```
Clone https://github.com/FansFollow-me/VikingSamurai and install versions/classic to ~/.hermes/pets/vikingsamurai and versions/armor to ~/.hermes/pets/vikingsamurai-armor. Select vikingsamurai, scale 0.88, run hermes pets doctor, paste the doctor output.
```

## Petdex install

```
npx -y petdex@latest install vikingsamurai
npx -y petdex@latest install vikingsamurai-armor
```

## Petdex submit (maintainers)

```
cd /path/to/VikingSamurai
npx -y petdex@latest login
npx -y petdex@latest submit ./submit/vikingsamurai
npx -y petdex@latest submit ./submit/vikingsamurai-armor
```

Never upload a lone spritesheet.webp or the live URL becomes /pets/spritesheet-N.

## Codex desktop

```
Copy VikingSamurai versions/classic to ~/.codex/pets/vikingsamurai and versions/armor to ~/.codex/pets/vikingsamurai-armor. Each folder needs pet.json + spritesheet.webp. Activate under Settings, Appearance, Pets.
```
