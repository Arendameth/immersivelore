# Immersive Lore

If you've worked with translating Project Zomboid mods before, the approach to translating this mod will be slightly different. This is mainly because of how the overall logic of this mod works. If this is your first time translating a mod, this shouldn't be an issue for you.

## Getting Started

To start, head to the main stories file, which is the one in English language. You'll find this in `EN/stories.json`.

Once you open the file, you'll be presented with the stories available for the mod in JSON format. Each story has 4 elements:

- `id`: This is a unique identifier for the story. It should remain the same across all translations.
- `title`: The title of the story. Should be accordingly translated.
- `content`: The actual content of the story. Should be accordingly translated.
- `rooms`: A list of rooms that the story may spawn in. This should remain the same at all times (DO NOT TRANSLATE THIS).
