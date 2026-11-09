# PDF Manager — local PDF workspace

## Open it without installing anything

1. Make sure the computer is connected to the internet so the browser can load the PDF libraries.
2. Double-click `index.html` and choose Chrome, Edge, or another modern browser if prompted.
3. Choose a PDF or drag one into the browser window.
4. Choose **ExtractaPDF** in the top bar to open the PDF extraction studio in a separate tab.

There is no installer, Node.js, server, or account required. The PDF libraries load from public CDNs; the PDF itself is read, rendered, and edited in your browser and is not uploaded. The selected PDF is kept temporarily in browser storage so it can be restored after a page refresh; it is cleared when a new browser session starts. The app needs an internet connection when opened so those libraries can load.

## Features

- Lazy page rendering to reduce unnecessary work on large or long PDFs.
- Pages automatically expand to the available viewer width, with compact margins and zoom controls up to 2400%; Ctrl+mouse-wheel zoom stays centered at the pointer, while ordinary wheel scrolling still navigates pages.
- Adaptive PDF canvas resolution keeps memory use bounded at extreme zoom levels.
- Pan mode for scrolling around zoomed pages by dragging, and marquee zoom to zoom into a selected page region.
- Pan and Zoom area controls have recognizable toolbar icons and keyboard-accessible labels.
- Search text across the PDF with **Ctrl+F**, highlighted matches, and previous/next result navigation.
- Open the bundled PDF extraction studio from the top bar for table-to-Excel extraction, PDF page tools, and review-comment extraction.
- Choose **Remove PDF** in the top bar to close the current document and clear its temporary browser-session copy.
- Save reusable image and PDF stamps in a local browser library. PDF stamps use the first page; placed stamps remain in the document if their library entry is deleted.
- Move and resize placed stamps using the Select tool; stamps are flattened into exported PDFs.
- Highlight, freehand, text, sticky note, rectangle, oval, line, arrow, and revision-cloud markup.
- Markup tools return to **Select** after placing an item, preventing repeated placements from accidental clicks.
- Expanded markup color palette with 20 presets and a custom color picker.
- Press **Delete** to remove the selected unlocked markup; locked markups are protected from keyboard deletion.
- Hold **Shift** while drawing a line or arrow to constrain it horizontally or vertically.
- Revision-cloud scallops scale with the page zoom; the radius is sized to the current page view when the cloud is drawn.
- Add text directly on the PDF; edit it in place with font family, size, bold, italic, underline, and color controls.
- Resize text boxes by dragging any corner handle; text wraps within the box and excess text is indicated with an ellipsis.
- Single-click an existing text box to select it; double-click to reopen its inline editor. Use **Ctrl+Enter** to apply text while typing.
- Edit existing text markups in place and adjust markup colors and properties; drag markups to move them and use selection handles to resize shapes.
- Lock any placed markup from its comment card to prevent moving or resizing it accidentally; unlock it at any time. Locked markups remain selectable and editable.
- Change an existing markup's color, line thickness, and page-relative width/height from its **Edit** properties; text boxes also expose text size. Text content and its font styling remain editable directly on the page.
- Comments list with page navigation, edit, delete, undo, and redo (also available with Ctrl+Z, Ctrl+Y, or Ctrl+Shift+Z).
- Save a marked copy as a flattened PDF. The original is unchanged.
- Exported markups remain upright and aligned on pages with 90°, 180°, or 270° page rotation.

To reposition a markup, choose **Select** and drag it. Text boxes can be moved by dragging inside them and resized with any corner handle. To resize a shape, drag one of its endpoint handles. Use **Lock** on its comment card to prevent accidental movement or resizing; use **Unlock** when you want to reposition it. Use **Edit** beside a comment to adjust the markup's appearance, size, and thickness. Width and height in the properties dialog are percentages of the page dimensions. Press **Delete** to remove the selected, unlocked markup. Hold **Shift** as you draw a line or arrow to snap it to horizontal or vertical. Draw revision clouds by dragging on the page. Choose **Pan** and drag to move around a zoomed page, or choose **Marquee** and drag a rectangle to zoom into that area.

Choose **Stamps** to add PNG, JPEG, WebP, GIF, or PDF files to the browser-local stamp library. Select **Use**, then click the page to place the stamp; choose **Select** to move or resize it. PDF stamps are rendered from their first page. Search with **Ctrl+F** or the search button, type a term, and use the arrows (or Enter / Shift+Enter) to move between highlighted results.

This is a focused local review tool, not a complete Acrobat replacement. Existing PDF comments/annotations, interactive forms, and digital signatures are not editable. Markups are flattened into page content when saved.
