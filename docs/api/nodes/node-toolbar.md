---
title: <NodeToolbar />
sidebar_position: 5
sidebar_class_name: new
---

import PropItems from '../../../src/components/Docs/PropItems'
import CodeViewer from '../../../src/components/CodeViewer';

The node toolbar plugin component renders a toolbar that is attached to a node. The toolbar does not scale with the viewport so that the content of the toolbar is always readable.

:::info
The `NodeToolbar` component is available in `reactflow` version **11.3** and higher.
:::

### Usage Example

<CodeViewer options={{ editorHeight: 500, editorWidthPercentage: 45, wrapContent: true }} activeFile="CustomNode.js" codePath="api-flows/NodeToolbar" applyStyles={false} additionalFiles={['CustomNode.js', 'TooltipNode.js', 'MultiSelectionToolbar.js']} />

### Default Behavior

Per default, the toolbar is connected to a node and visible only if the node is selected. If multiple nodes are selected, the toolbar is hidden again to prevent showing multiple toolbars at once. If you want to override this default behavior, you can set the `isVisible` prop by yourself.

### Prop Types

import options from '../../../docs-data/node-toolbar';

<PropItems props={options} />

### Typescript

The interface of the NodeToolbar Prop Types are exported as`NodeToolbarProps`.

### Npm Package

The NodeToolbar component is published under `@reactflow/node-toolbar` and can also be [installed and used separately](/docs/overview/packages/#node-toolbar).
