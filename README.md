# Export Illustrator to InDesign

CEP extension for Adobe Illustrator and Adobe InDesign. It exports text and selected graphics from Illustrator to XML, then creates an InDesign document from that XML.

This extension is not a fully automatic Illustrator-to-InDesign converter. It is a controlled transfer tool: the user decides which text and graphics should move to InDesign.

## Demo Video

Watch the full workflow demonstration on YouTube:

[Export Illustrator to InDesign - full workflow demo](https://youtu.be/BqgwwWCKz1w)

The video shows how the extension splits spread artboards, exports Illustrator text and selected graphics, and creates a clean InDesign document with correctly placed linked graphics.

## Usage Strategies

You can use the extension in three different ways, depending on the job.

### 1. Split Spread Artboards Only

Use `DESpreaded` when an Illustrator document contains two-page spreads made as single wide artboards.

The extension can split those wide spread artboards into separate left and right page artboards directly in Illustrator. This can be useful even if you do not plan to export anything to InDesign.

### 2. Export Graphics Only

Use the graphics export workflow when you want to create an InDesign document with correctly placed linked graphics, but without transferring text.

This creates a clean InDesign layout structure based on the Illustrator artboards and places only the selected artwork where it belongs. It is useful when the final text will be recreated, rewritten, or placed manually in InDesign.

### 3. Export Text And Graphics

Use the full workflow when you want to transfer both editable text and selected graphics from Illustrator to InDesign.

The extension exports Illustrator text frames to XML, exports selected artwork as linked PSD/EPS files, and then builds a new InDesign document from that data.

## Why Graphics Export Is Semi-Automatic

Many tools that open or convert PDF files in InDesign try to import graphics automatically. In real production files this often creates a serious cleanup problem: background elements, masks, decorative shapes, fragments, and other unwanted objects become imported InDesign content. The result is usually not a clean layout, but a document full of graphic "garbage" that must be deleted manually.

This extension takes a different approach. Graphics are exported semi-automatically: the user selects only the artwork that should become linked graphics in InDesign. This keeps the resulting InDesign document cleaner, more predictable, and easier to edit.

## Download Demo

Demo ZXP package:

[Download Illustrator_to_InDesign_demo.zxp](zxp/Illustrator_to_InDesign_demo.zxp)

The demo version limits Illustrator export to 10 text frames and 10 linked graphics.

`DESpreaded` is fully available in demo mode. It can split wide two-page spread artboards into separate left/right artboards directly in Illustrator, even without exporting to InDesign.

## Full Version

The full version removes the demo export limits. **$50 USD** - pay with PayPal.

| Demo | Full Version |
|------|--------------|
| Up to 10 exported text frames | No text export limit |
| Up to 10 exported linked graphics | No linked graphics export limit |
| `DESpreaded` fully available | `DESpreaded` fully available |

**[Buy Full Version - $50](https://sergeynt2006.github.io/Export-Illustrator-to-InDesign/purchase.html)** - PayPal payment. Download link sent by email within 24 hours.

## Main Features

- Export Illustrator text frames to XML.
- Export selected Illustrator artwork as linked PSD/EPS graphics.
- Import XML into a new InDesign document.
- Optional linked image import.
- Support for different Illustrator artboard sizes when creating InDesign pages.
- `DESpreaded` for splitting two-page spread artboards while preserving logical artboard order.
- Optional print area margins and `Facing Page` document setup transfer.

## Installation

1. Close Illustrator and InDesign.
2. Download the demo ZXP package.
3. Install the ZXP package with a compatible ZXP installer.
4. Start Illustrator or InDesign.
5. Open the panel from `Window > Extensions > Export Illustrator to InDesign`.

After updating extension files, restart the Adobe host application.

## Demo And Full Modes

The demo package shows a permanent `Demo mode` label and a bottom footer with `Demo version` / `Buy full version`.

The full package is distributed separately after purchase.
