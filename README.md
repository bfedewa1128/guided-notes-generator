# Guided Notes Generator

![Guided Notes Generator icon](assets/icon.png)

Guided Notes Generator helps teachers turn course content into student Guided Notes in minutes. You give Claude a sample of the Guided Notes format your courses already accept, plus the lesson (or a whole module) you want notes for. Claude builds notes that match your sample's layout and style, using only the content from the lesson you provided.

## What it does

1. Asks you to upload a sample Guided Notes file (an empty template or a completed example).
2. Asks you to upload the lesson or module content. If the content isn't in a readable format, you can extract the text first (for example with Llama Tools) and upload that.
3. Asks whether you want to stay within a certain page length.
4. Asks which file type you want: Word document, Google Doc, or PDF.
5. Creates the Guided Notes. When you upload a full module, each lesson gets its own separate document. If your sample was filled out, it can also offer an answer key.

## How to use it

After installing the plugin, ask Claude something like:

- "Make guided notes for this lesson."
- "Create guided notes for every lesson in this module."

Claude will walk you through the uploads and options above.

## Data and privacy

This plugin contains a single skill made of written instructions. It does not include any code, scripts, hooks, or MCP servers, and it does not send data to any remote server or third-party service. The files you upload stay in your Claude conversation and are handled under your existing Claude account settings. If you choose a Google Doc as the output, Claude uses the Google Drive connector you have already connected yourself.

## License

MIT. See [LICENSE](LICENSE).
