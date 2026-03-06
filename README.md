# React Flow Pro Examples (v12)

A collection of 19 pro examples built with [React Flow](https://reactflow.dev/) v12 (`@xyflow/react`). Each example is a standalone project you can run independently.

## Examples

| Example | Description | Framework |
| --- | --- | --- |
| [ai-workflow-editor](./ai-workflow-editor-pro-example) | Build and visualize AI image generation workflows with drag-and-drop nodes, powered by Vercel AI SDK | Next.js |
| [workflow-editor](./workflow-editor-pro-example) | General-purpose workflow editor template with sidebar, custom nodes, and edge routing | Next.js |
| [auto-layout](./auto-layout-pro-example) | Automatically arrange nodes after adding items to your flow | Vite |
| [collaborative](./collaborative-pro-example) | Real-time collaborative flow editing with multiple users | Vite |
| [copy-paste](./copy-paste-pro-example) | Select multiple nodes and copy/paste them using keyboard shortcuts or toolbar buttons | Vite |
| [dynamic-layouting](./dynamic-layouting-pro-example) | Dynamically create child nodes by clicking on existing nodes with automatic layout | Vite |
| [editable-edge](./editable-edge-pro-example) | Freely routable, editable edges with freeform connection line drawing | Vite |
| [expand-collapse](./expand-collapse-pro-example) | Expand and collapse tree nodes by clicking, with the ability to add child nodes | Vite |
| [expand-collapse-d3](./expand-collapse-d3-pro-example) | Expand and collapse tree nodes using D3 for layout calculations | Vite |
| [force-layout](./force-layout-pro-example) | Force-directed graph layout where clicking the pane adds nodes attracted to others | Vite |
| [freehand-draw](./freehand-draw-pro-example) | Draw freehand lines on a canvas overlay that convert into resizable custom nodes | Vite |
| [helper-lines](./helper-lines-pro-example) | Snap-to-align helper lines that appear when dragging nodes near other node boundaries | Vite |
| [node-position-animation](./node-position-animation-pro-example) | Smoothly animate nodes between two predefined layouts with a toggle button | Vite |
| [parent-child-relation](./parent-child-relation-pro-example) | Dynamically attach and detach nodes to parent groups by dragging | Vite |
| [remove-attribution](./remove-attribution-pro-example) | Remove the default React Flow attribution using `proOptions` | Vite |
| [selection-grouping](./selection-grouping-pro-example) | Select multiple nodes with Shift+click and group/ungroup them dynamically | Vite |
| [server-side-image-creation](./server-side-image-creation-pro-example) | Generate server-side images of your flow, with live preview as you drag nodes | Vite |
| [shapes](./shapes-pro-example) | Resizable custom shape nodes for flowcharts and diagrams, with sidebar and interactive minimap | Vite |
| [undo-redo](./undo-redo-pro-example) | Full undo/redo history for node creation, connections, and graph edits | Vite |

## Getting Started

Each example is a standalone project. To run any example:

```bash
cd <example-folder>
npm install
npm run dev
```

## Tech Stack

- **React Flow v12** (`@xyflow/react`) — node-based UI framework
- **Vite** or **Next.js** — build tooling (see table above)
- **TypeScript** — all examples are written in TypeScript
- **Tailwind CSS** — styling (used in Next.js examples)

## License

Each example contains its own license file. Refer to the individual `LICENSE.md` files for details.
