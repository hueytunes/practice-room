# Practice Room

A sheet music practice app for piano. Open a MusicXML score, mark it up, and play it back with a piano that lights up the keys.

## What it does

- Opens MusicXML (.musicxml, .mxl), PDF, and photos of sheet music
- Plays MusicXML scores with a cursor that follows along, at any tempo from 25% to 150%
- Loops a range of measures, with an optional click track and count-in
- Mutes either hand so you can play that part yourself
- Shows a piano with the keys to press (teal for right hand, orange for left, rings for the next notes)
- Steps through the music one chord at a time with the arrow keys
- Lets you mark up any page with pen, highlighter, text, and finger numbers (Apple Pencil works too)

Your pieces and markings save in your browser on that device.

## Hosting on GitHub Pages

1. Create a new repository and upload `index.html`, `README.md`, and `.nojekyll`.
2. Go to Settings > Pages, pick "Deploy from a branch," choose `main` and `/ (root)`, and save.
3. After a minute, the app is live at `https://<your-username>.github.io/<repo-name>/`.

On iPad, open that link in Safari, tap Share, then "Add to Home Screen." Safari can clear saved data for websites you haven't opened in a while, and adding the app to your Home Screen protects your library from that.

## Reading notes from a PDF or photo

On this site, there are two ways to make a PDF or photo playable:

- **Your own API key:** tap Settings, paste an Anthropic API key (from console.anthropic.com), and the app can read notes and answer questions here. The key stays in your browser on that device, and usage is billed to your Anthropic account.
- **The Claude version:** read the notes in the Claude-hosted copy of the app, tap "Download MusicXML," and add that file here.
