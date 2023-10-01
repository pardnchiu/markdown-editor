# Markdown Editor

> A web-based Markdown editor with real-time preview designed for editing of md files online. 
> Through modular design, it is easy to integrate into websites for use.
> Must be used in conjunction with [PDExtension-js](https://github.com/pardnchiu/PDExtension-js).

![Markdown 簡易編輯器 (Web) - Pardn Chiu 邱敬幃](./image/preview.jpg)

## Feature

- Built using Html, Css / Sass and JavaScript.
- Rendered using [PDExtension](https://github.com/pardnchiu/PDExtension-js).
- Use [Font Awesome 6](https://fontawesome.com/v6/search) icons.
- Preview available [Here](https://pardnchiu.github.io/markdown-editor).

## Include

```Html
<script src="PDExtension.min.js" copyright="Pardn Ltd"></script>
<script src="PDMDEditor.min.js" copyright="Pardn Ltd"></script>
```

```Javascript
const editor = new MDEditor({
    id: "md-editor",
    style: {
        backgroundColor: "#0000ff1a", 
        color: "#0000ff", 
        placeholder: "Type here ...",
        placeholderColor: "#bfbfbf",
        showRow: 1
    }
});
const viewer = new MDViewer({ 
    id: "md-preview",
    pre: "" /* Default content. Displayed when the editor is empty. */
});

/* Add elements to the view. */
{DOM}.appendChild(editor.body);
{DOM}.appendChild(viewer.body);

/* Set the target viewer for the editor preview. */
editor.viewer = viewer; 

/* Initialize the editor and viewer. */
editor.init();
viewer.init();
```

## MDEditor
```Typescript
interface MDEditor {
    // Initialize the editor.
    init: (pre: string) => void;
    // Add heading.
    addHeading: (num: number) => void;
    // Add bold.
    addBold: () => void;
    // Add italic.
    addItalic: () => void;
    // Add strikethrough.
    addStrikethrough: () => void;
    // Add underline.
    addUnderline: () => void;
    // Add marker.
    addMarker: () => void;
    // Add blockquote.
    addBlockquote: () => void;
    // Add unordered list.
    addUl: () => void;
    // Add ordered list.
    addOl: () => void;
    // Add code block.
    addCode: () => void;
    // Add hyperlink.
    addLink: (title: string, href: string) => void;
    // Add image.
    addImage: (src: string, alt: string, title: string) => void;
    // Clear editor content.
    clear: () => void;
    // Output as Markdown file.
    downloadMd: () => void;
    // Output as HTML file.
    downloadHtml: () => void;
    // Open .md file.
    openfile: (file) => void;
};
```

## Contributor

- [Pardn Chiu 邱敬幃](https://linkedin.com/in/pardnchiu)

## License

This source code project is licensed under the GPL-3.0 license.

***

©️ 2023 [Pardn Chiu 邱敬幃](https://www.linkedin.com/in/pardnchiu)
