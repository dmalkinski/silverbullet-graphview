# SilverBullet plug for showing a graph view of the documents

This plug aims to bring similar functionality as the Obsidian Graph view to
Silver Bullet.

## Installation

Open (`cmd+k`) your `PLUGS` note in SilverBullet and add this plug to the list:

```yaml
- github:dmalkinski/silverbullet-graphview/graphview.plug.json
```

Then run the `Plugs: Update` command and off you go!

## Usage

Run the `Show Graph` command to open up the graph view. Zoom and pan is
supported by scroll and pinch gestures with the mouse(pad).

## For offline development

To ease development of the visual part, the offline folder contains a copy of
the html and custom javascritpt. As well as a simple graph model.

```bash
$ cd offline
$ python -m http.server
```
