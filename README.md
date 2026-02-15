# .NET MAUI Day Gallery

Photo gallery for .NET MAUI Day events.

## Adding a new album

1. Create a folder named after the event (e.g., `london-2025`)
2. Drop image files (`.jpg`, `.jpeg`, `.png`, `.webp`) into the folder
3. Add an entry to `albums.json` with `id` (matching the folder name), `title`, and `date`

The website will pick up the new album on its next build/deploy.

