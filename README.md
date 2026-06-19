# publicdomainjazz

Jazz standards that are in the public domain, initially starting with ABC notation. 

## What's here

Each song lives in `songs/<handle>/`:

- `<handle>.json` — metadata: title, composer, genre, description, versions, and fakebook page references (`lookup_refs`)
- `<handle>-<n>.abc` — ABC notation, one file per version

All songs are in the **US public domain**.

## Using the files

The ABC files can be rendered, transposed, and played by any ABC-capable tool — [abcjs](https://www.abcjs.net/), EasyABC, MuseScore (via import), and others.

The JSON metadata is plain data: parse it with any language. The `lookup_refs` field lists page references in common fakebooks and realbooks so you can cross-check a transcription against a printed source.
