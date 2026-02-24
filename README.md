# AutoProp Precast Column Creator — Support

AutoProp Precast Column Creator is a SketchUp extension that generates precast-style rectangular columns with optional detailing.

## Features
- Rectangular precast column (width, depth, height)
- Optional corner chamfer (on/off + adjustable size)
- Optional grout recess holes on a selected face (on/off)
- Optional reinforcement (starter bars + base voids) (on/off)
- Adjustable props (prop head + base), aligned to the selected face
- Clean grouping for easy editing and selection
- **Edit placed columns** (single or multi-select)

## Compatibility
- SketchUp **2017+** (uses `UI::HtmlDialog`)
- Windows + Mac
- Not supported on SketchUp for Web / iPad (Ruby extensions aren’t supported there)

## Install
**Option A — Extension Warehouse (recommended)**
- Install via Extension Warehouse, then restart SketchUp if prompted.

**Option B — RBZ**
- SketchUp → Extension Manager → Install Extension… → select the `.rbz` → restart SketchUp.

## Use

### New column
Extensions → AutoProp Precast Column Creator → **New Column…**  
Set dimensions/options → **Click 1** to set the anchor → move mouse to preview → **Click 2** to place.

### Edit existing column(s)
1. Select one (or multiple) AutoProp columns.
2. Extensions → AutoProp Precast Column Creator → **Edit Selected Column(s)…**
3. Adjust settings → Apply.

## Preview controls
- Home: cycle prop face (and grout recess face, if enabled)
- Left/Right arrows: rotate
- Up/Down arrows: flip
- Enter: commit placement (if using keyboard commit)
- Esc: cancel

## Placement tip (alignment)
- Use SketchUp inference locking (arrow keys) and Shift to lock direction if you need precise alignment.

## Known notes
- Some keyboards don’t have a dedicated Home key. If needed, use an external keyboard or remap Home with your keyboard software.

## Bug reports
When reporting an issue, include:
- SketchUp version (e.g. 2026)
- OS (Windows/Mac)
- Steps to reproduce
- Screenshot
- Ruby Console error text (Window → Ruby Console), if any

## Links
- Support page: https://github.com/TheDankMan/autoprop-precast-column-creator
- Report a bug / request a feature: https://github.com/TheDankMan/autoprop-precast-column-creator/issues

## Support development (optional)
If this extension saves you time, you can support development here:
https://buymeacoffee.com/autopropcreator
- ## Current version
1.0.4 (Extension Warehouse)


