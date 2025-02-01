---
layout: post
title: Hay montañas de evidencia
mathjax: true
---
{% include mathjax.html %}

$\renewcommand{\hat}[1]{\widehat{#1}}$
$\renewcommand{\vec}[1]{\overrightarrow{#1}}$
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>EcuacionItinerario</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0px solid transparent;
  border-right: 0px solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0px solid transparent;
  border-bottom: 0px solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
	border:1px solid transparent;
  background-color: transparent;
  position: absolute;
	z-index:1;
	right:3%;
	top: 0;
	bottom: 0;
	margin: auto;
	padding: 7px 0;
	display: none;
	vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
	content: "X";
	display: block;
	width: 15px;
	height: 15px;
	text-align: center;
	color:#000;
	font-weight: normal;
	font-size: 12px;
	cursor: pointer;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
  background: inherit;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-bottom:10px;
  margin-top:0; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  font-size:36px;
  line-height:40px; }

h2.bp3-heading, .bp3-running-text h2{
  font-size:28px;
  line-height:32px; }

h3.bp3-heading, .bp3-running-text h3{
  font-size:22px;
  line-height:25px; }

h4.bp3-heading, .bp3-running-text h4{
  font-size:18px;
  line-height:21px; }

h5.bp3-heading, .bp3-running-text h5{
  font-size:16px;
  line-height:19px; }

h6.bp3-heading, .bp3-running-text h6{
  font-size:14px;
  line-height:16px; }
.bp3-ui-text{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none; }

.bp3-monospace-text{
  font-family:monospace;
  text-transform:none; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  font-size:14px;
  line-height:1.5; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15);
    margin:20px 0; }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  color:#106ba3;
  text-decoration:none; }
  a:hover{
    color:#106ba3;
    cursor:pointer;
    text-decoration:underline; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  font-size:smaller;
  padding:2px 5px; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  color:#182026;
  display:block;
  font-size:13px;
  line-height:1.4;
  margin:10px 0;
  padding:13px 15px 12px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit;
    font-size:inherit;
    padding:0; }

.bp3-running-text kbd, .bp3-key{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-family:inherit;
  font-size:12px;
  height:24px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  line-height:24px;
  min-width:24px;
  padding:3px 6px;
  vertical-align:middle; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  margin:0 0 10px;
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    font-size:40px;
    margin-right:20px;
    margin-top:0; }

.bp3-alert-contents{
  word-break:break-word; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  cursor:default;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  height:30px;
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-breadcrumbs > li{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }
    .bp3-breadcrumbs > li::after{
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 00-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 001.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      content:"";
      display:block;
      height:16px;
      margin:0 5px;
      width:16px; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    font-size:inherit;
    font-weight:inherit;
    vertical-align:baseline; }

.bp3-breadcrumbs-collapsed{
  background:#ced9e0;
  border:none;
  border-radius:3px;
  cursor:pointer;
  margin-right:2px;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    content:"";
    display:block;
    height:16px;
    width:16px; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    color:#182026;
    text-decoration:none; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  min-height:30px;
  min-width:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      background-color:#106ba3;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      background-color:#0e5a8a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      background-color:#0d8050;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      background-color:#0a6640;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      background-color:#bf7326;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      background-color:#a66321;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      background-color:#c23030;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      background-color:#a82a2a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-height:40px;
    min-width:40px;
    font-size:16px;
    padding:5px 15px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      margin:0;
      position:absolute; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button.bp3-minimal:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button.bp3-outlined{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    border:1px solid rgba(24, 32, 38, 0.2);
    -webkit-box-sizing:border-box;
            box-sizing:border-box; }
    .bp3-button.bp3-outlined:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-outlined:active, .bp3-button.bp3-outlined.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-outlined{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-outlined:hover, .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-outlined:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover, .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover, .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover, .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover, .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled:hover{
      border-color:rgba(92, 112, 128, 0.1); }
    .bp3-dark .bp3-button.bp3-outlined{
      border-color:rgba(255, 255, 255, 0.4); }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        border-color:rgba(255, 255, 255, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      border-color:rgba(16, 107, 163, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        border-color:rgba(16, 107, 163, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        border-color:rgba(72, 175, 240, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          border-color:rgba(72, 175, 240, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      border-color:rgba(13, 128, 80, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        border-color:rgba(13, 128, 80, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        border-color:rgba(61, 204, 145, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          border-color:rgba(61, 204, 145, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      border-color:rgba(191, 115, 38, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        border-color:rgba(191, 115, 38, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        border-color:rgba(255, 179, 102, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          border-color:rgba(255, 179, 102, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      border-color:rgba(194, 48, 48, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        border-color:rgba(194, 48, 48, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        border-color:rgba(255, 115, 115, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          border-color:rgba(255, 115, 115, 0.2); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    border-bottom-right-radius:0;
    border-top-right-radius:0;
    margin-right:-1px; }
  .bp3-button-group.bp3-minimal .bp3-button{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      height:100%;
      width:unset; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  font-size:14px;
  line-height:1.5;
  background-color:rgba(138, 155, 168, 0.15);
  border-radius:3px;
  padding:10px 12px 9px;
  position:relative;
  width:100%; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout .bp3-heading{
    line-height:20px;
    margin-bottom:5px;
    margin-top:0; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  opacity:0.9;
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  width:100%; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }

.bp3-dialog{
  background:#ebf1f5;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text;
  width:500px; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    background:#293742;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-dialog-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding-left:20px;
  padding-right:5px;
  z-index:30; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    background:#30404d;
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  margin:20px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-multistep-dialog-panels{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }

.bp3-multistep-dialog-left-panel{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column; }
  .bp3-dark .bp3-multistep-dialog-left-panel{
    background:#202b33; }

.bp3-multistep-dialog-right-panel{
  background-color:#f5f8fa;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  border-radius:0 0 6px 0;
  -webkit-box-flex:3;
      -ms-flex:3;
          flex:3;
  min-width:0; }
  .bp3-dark .bp3-multistep-dialog-right-panel{
    background-color:#293742;
    border-left:1px solid rgba(16, 22, 26, 0.4); }

.bp3-multistep-dialog-footer{
  background-color:#ffffff;
  border-radius:0 0 6px 0;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  padding:10px; }
  .bp3-dark .bp3-multistep-dialog-footer{
    background:#30404d;
    border-top:1px solid rgba(16, 22, 26, 0.4); }

.bp3-dialog-step-container{
  background-color:#f5f8fa;
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-dialog-step-container{
    background:#293742;
    border-bottom:1px solid rgba(16, 22, 26, 0.4); }
  .bp3-dialog-step-container.bp3-dialog-step-viewed{
    background-color:#ffffff; }
    .bp3-dark .bp3-dialog-step-container.bp3-dialog-step-viewed{
      background:#30404d; }

.bp3-dialog-step{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#f5f8fa;
  border-radius:6px;
  cursor:not-allowed;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:4px;
  padding:6px 14px; }
  .bp3-dark .bp3-dialog-step{
    background:#293742; }
  .bp3-dialog-step-viewed .bp3-dialog-step{
    background-color:#ffffff;
    cursor:pointer; }
    .bp3-dark .bp3-dialog-step-viewed .bp3-dialog-step{
      background:#30404d; }
  .bp3-dialog-step:hover{
    background-color:#f5f8fa; }
    .bp3-dark .bp3-dialog-step:hover{
      background:#293742; }

.bp3-dialog-step-icon{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:rgba(92, 112, 128, 0.6);
  border-radius:50%;
  color:#ffffff;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:25px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:25px; }
  .bp3-dark .bp3-dialog-step-icon{
    background-color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#2b95d6; }
  .bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#8a9ba8; }

.bp3-dialog-step-title{
  color:rgba(92, 112, 128, 0.6);
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  padding-left:10px; }
  .bp3-dark .bp3-dialog-step-title{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-title{
    color:#2b95d6; }
  .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
    color:#182026; }
    .bp3-dark .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
      color:#f5f8fa; }
.bp3-drawer{
  background:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    height:50%;
    left:0;
    right:0;
    top:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-bottom{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-left{
    bottom:0;
    left:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-right{
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    background:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-drawer-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding:5px;
  padding-left:20px;
  position:relative; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  overflow:auto; }

.bp3-drawer-footer{
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  padding:10px 20px;
  position:relative; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  cursor:text;
  display:inline-block;
  max-width:100%;
  position:relative;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    bottom:-3px;
    left:-3px;
    position:absolute;
    right:-3px;
    top:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  color:inherit;
  display:inherit;
  font:inherit;
  letter-spacing:inherit;
  max-width:inherit;
  min-width:inherit;
  position:relative;
  resize:none;
  text-transform:inherit;
  vertical-align:top; }

.bp3-editable-text-input{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0;
  white-space:pre-wrap;
  width:100%; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    left:0;
    position:absolute;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    border-radius:inherit;
    z-index:2; }
    .bp3-control-group .bp3-input:focus{
      border-radius:3px;
      z-index:14; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    border-radius:inherit;
    z-index:4; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-left-container,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group .bp3-select:focus-within{
    z-index:5; }
  .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:-1px; }
  .bp3-control-group:not(.bp3-vertical) > .bp3-divider:not(:first-child){
    margin-left:6px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    border-radius:0 3px 3px 0;
    margin-right:0; }
  .bp3-control-group > :only-child{
    border-radius:3px;
    margin-right:0; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group .bp3-numeric-input:not(:first-child) .bp3-input-group{
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-control-group.bp3-fill{
    width:100%; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      border-radius:3px 3px 0 0;
      margin-top:0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  cursor:pointer;
  display:block;
  margin-bottom:10px;
  position:relative;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    left:0;
    opacity:0;
    position:absolute;
    top:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    cursor:pointer;
    display:inline-block;
    font-size:16px;
    height:1em;
    margin-right:10px;
    margin-top:-3px;
    position:relative;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none;
    vertical-align:middle;
    width:1em; }
    .bp3-control .bp3-control-indicator::before{
      content:"";
      display:block;
      height:1em;
      width:1em; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    background:#d8e1e8;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-left:10px;
    margin-top:1px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 00-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0012 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:auto; }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      background:#ffffff;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      height:calc(1em - 4px);
      left:0;
      margin:2px;
      position:absolute;
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      width:calc(1em - 4px); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    font-size:0.7em;
    text-align:center; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    line-height:0;
    margin-left:0.5em;
    margin-right:1.2em;
    visibility:hidden; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    line-height:1em;
    margin-left:1.2em;
    margin-right:0.5em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    line-height:1em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    line-height:0;
    visibility:hidden; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      background:#202b33;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  cursor:pointer;
  display:inline-block;
  height:30px;
  position:relative; }
  .bp3-file-input input{
    margin:0;
    min-width:200px;
    opacity:0; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      background:rgba(206, 217, 224, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(92, 112, 128, 0.6);
        cursor:not-allowed;
        outline:none; }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        background:rgba(57, 75, 89, 0.5);
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          -webkit-box-shadow:none;
                  box-shadow:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:rgba(92, 112, 128, 0.6);
  left:0;
  padding-right:80px;
  position:absolute;
  right:0;
  top:0;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-file-upload-input::after{
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026;
    min-height:24px;
    min-width:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    border-radius:3px;
    content:"Browse";
    line-height:24px;
    margin:3px;
    position:absolute;
    right:0;
    text-align:center;
    top:0;
    width:70px; }
    .bp3-file-upload-input::after:hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-file-upload-input:active::after{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-large .bp3-file-upload-input{
    font-size:16px;
    height:40px;
    line-height:40px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-height:30px;
      min-width:30px;
      line-height:30px;
      margin:5px;
      width:85px; }
  .bp3-dark .bp3-file-upload-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        background-color:#30404d;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        background-color:#202b33;
        background-image:none;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:active::after{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    color:#5c7080;
    font-size:12px;
    margin-top:5px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      line-height:40px;
      margin:0 10px 0 0; }
    .bp3-form-group.bp3-inline label.bp3-label{
      line-height:30px;
      margin:0 10px 0 0; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-input-left-container:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-input-left-container:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-height:24px;
    min-width:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-icon{
    z-index:1; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon{
    color:#5c7080; }
    .bp3-input-group > .bp3-input-left-container > .bp3-icon:empty,
    .bp3-input-group > .bp3-icon:empty{
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-height:30px;
    min-width:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle; }
  .bp3-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-input.bp3-large{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-bottom:15px;
  margin-top:0; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    font-weight:400;
    vertical-align:top;
    width:100%; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  min-height:0;
  padding:0;
  width:30px; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  -moz-appearance:none;
  -webkit-appearance:none;
  border-radius:3px;
  height:30px;
  padding:0 25px 0 10px;
  width:100%; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  background:none;
  -webkit-box-shadow:none;
          box-shadow:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    background:rgba(167, 182, 194, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026;
    text-decoration:none; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    background:rgba(115, 134, 148, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      color:rgba(167, 182, 194, 0.6);
      cursor:not-allowed; }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  font-size:16px;
  height:40px;
  padding-right:35px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    background-color:#202b33;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  background-color:rgba(206, 217, 224, 0.5);
  -webkit-box-shadow:none;
          box-shadow:none;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  color:#5c7080;
  pointer-events:none;
  position:absolute;
  right:7px;
  top:7px; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  letter-spacing:normal;
  position:relative;
  vertical-align:middle; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    right:12px;
    top:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select option:disabled, .bp3-dark
  .bp3-select option:disabled{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:""; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    text-align:left;
    vertical-align:top; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td,
  .bp3-running-text table tfoot tr:first-child th,
  table.bp3-html-table tfoot tr:first-child th,
  .bp3-running-text table tfoot tr:first-child td,
  table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td,
  .bp3-dark .bp3-running-text table tfoot tr:first-child th,
  .bp3-running-text .bp3-dark table tfoot tr:first-child th,
  .bp3-dark table.bp3-html-table tfoot tr:first-child th,
  .bp3-dark .bp3-running-text table tfoot tr:first-child td,
  .bp3-running-text .bp3-dark table tfoot tr:first-child td,
  .bp3-dark table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-bottom:6px;
  padding-top:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td,
table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
  table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table{ }
  .bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
    background:rgba(92, 112, 128, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td,
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
      -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
              box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
    background-color:rgba(92, 112, 128, 0.3);
    cursor:pointer; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
    background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  padding-bottom:0;
  top:40px; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-left:0;
  margin-right:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  font-family:"Icons20";
  font-size:inherit;
  font-style:normal;
  font-weight:400;
  line-height:1; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:""; }

.bp3-icon-add-column-left::before{
  content:""; }

.bp3-icon-add-column-right::before{
  content:""; }

.bp3-icon-add-row-bottom::before{
  content:""; }

.bp3-icon-add-row-top::before{
  content:""; }

.bp3-icon-add-to-artifact::before{
  content:""; }

.bp3-icon-add-to-folder::before{
  content:""; }

.bp3-icon-airplane::before{
  content:""; }

.bp3-icon-align-center::before{
  content:""; }

.bp3-icon-align-justify::before{
  content:""; }

.bp3-icon-align-left::before{
  content:""; }

.bp3-icon-align-right::before{
  content:""; }

.bp3-icon-alignment-bottom::before{
  content:""; }

.bp3-icon-alignment-horizontal-center::before{
  content:""; }

.bp3-icon-alignment-left::before{
  content:""; }

.bp3-icon-alignment-right::before{
  content:""; }

.bp3-icon-alignment-top::before{
  content:""; }

.bp3-icon-alignment-vertical-center::before{
  content:""; }

.bp3-icon-annotation::before{
  content:""; }

.bp3-icon-application::before{
  content:""; }

.bp3-icon-applications::before{
  content:""; }

.bp3-icon-archive::before{
  content:""; }

.bp3-icon-arrow-bottom-left::before{
  content:"↙"; }

.bp3-icon-arrow-bottom-right::before{
  content:"↘"; }

.bp3-icon-arrow-down::before{
  content:"↓"; }

.bp3-icon-arrow-left::before{
  content:"←"; }

.bp3-icon-arrow-right::before{
  content:"→"; }

.bp3-icon-arrow-top-left::before{
  content:"↖"; }

.bp3-icon-arrow-top-right::before{
  content:"↗"; }

.bp3-icon-arrow-up::before{
  content:"↑"; }

.bp3-icon-arrows-horizontal::before{
  content:"↔"; }

.bp3-icon-arrows-vertical::before{
  content:"↕"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:""; }

.bp3-icon-badge::before{
  content:""; }

.bp3-icon-ban-circle::before{
  content:""; }

.bp3-icon-bank-account::before{
  content:""; }

.bp3-icon-barcode::before{
  content:""; }

.bp3-icon-blank::before{
  content:""; }

.bp3-icon-blocked-person::before{
  content:""; }

.bp3-icon-bold::before{
  content:""; }

.bp3-icon-book::before{
  content:""; }

.bp3-icon-bookmark::before{
  content:""; }

.bp3-icon-box::before{
  content:""; }

.bp3-icon-briefcase::before{
  content:""; }

.bp3-icon-bring-data::before{
  content:""; }

.bp3-icon-build::before{
  content:""; }

.bp3-icon-calculator::before{
  content:""; }

.bp3-icon-calendar::before{
  content:""; }

.bp3-icon-camera::before{
  content:""; }

.bp3-icon-caret-down::before{
  content:"⌄"; }

.bp3-icon-caret-left::before{
  content:"〈"; }

.bp3-icon-caret-right::before{
  content:"〉"; }

.bp3-icon-caret-up::before{
  content:"⌃"; }

.bp3-icon-cell-tower::before{
  content:""; }

.bp3-icon-changes::before{
  content:""; }

.bp3-icon-chart::before{
  content:""; }

.bp3-icon-chat::before{
  content:""; }

.bp3-icon-chevron-backward::before{
  content:""; }

.bp3-icon-chevron-down::before{
  content:""; }

.bp3-icon-chevron-forward::before{
  content:""; }

.bp3-icon-chevron-left::before{
  content:""; }

.bp3-icon-chevron-right::before{
  content:""; }

.bp3-icon-chevron-up::before{
  content:""; }

.bp3-icon-circle::before{
  content:""; }

.bp3-icon-circle-arrow-down::before{
  content:""; }

.bp3-icon-circle-arrow-left::before{
  content:""; }

.bp3-icon-circle-arrow-right::before{
  content:""; }

.bp3-icon-circle-arrow-up::before{
  content:""; }

.bp3-icon-citation::before{
  content:""; }

.bp3-icon-clean::before{
  content:""; }

.bp3-icon-clipboard::before{
  content:""; }

.bp3-icon-cloud::before{
  content:"☁"; }

.bp3-icon-cloud-download::before{
  content:""; }

.bp3-icon-cloud-upload::before{
  content:""; }

.bp3-icon-code::before{
  content:""; }

.bp3-icon-code-block::before{
  content:""; }

.bp3-icon-cog::before{
  content:""; }

.bp3-icon-collapse-all::before{
  content:""; }

.bp3-icon-column-layout::before{
  content:""; }

.bp3-icon-comment::before{
  content:""; }

.bp3-icon-comparison::before{
  content:""; }

.bp3-icon-compass::before{
  content:""; }

.bp3-icon-compressed::before{
  content:""; }

.bp3-icon-confirm::before{
  content:""; }

.bp3-icon-console::before{
  content:""; }

.bp3-icon-contrast::before{
  content:""; }

.bp3-icon-control::before{
  content:""; }

.bp3-icon-credit-card::before{
  content:""; }

.bp3-icon-cross::before{
  content:"✗"; }

.bp3-icon-crown::before{
  content:""; }

.bp3-icon-cube::before{
  content:""; }

.bp3-icon-cube-add::before{
  content:""; }

.bp3-icon-cube-remove::before{
  content:""; }

.bp3-icon-curved-range-chart::before{
  content:""; }

.bp3-icon-cut::before{
  content:""; }

.bp3-icon-dashboard::before{
  content:""; }

.bp3-icon-data-lineage::before{
  content:""; }

.bp3-icon-database::before{
  content:""; }

.bp3-icon-delete::before{
  content:""; }

.bp3-icon-delta::before{
  content:"Δ"; }

.bp3-icon-derive-column::before{
  content:""; }

.bp3-icon-desktop::before{
  content:""; }

.bp3-icon-diagnosis::before{
  content:""; }

.bp3-icon-diagram-tree::before{
  content:""; }

.bp3-icon-direction-left::before{
  content:""; }

.bp3-icon-direction-right::before{
  content:""; }

.bp3-icon-disable::before{
  content:""; }

.bp3-icon-document::before{
  content:""; }

.bp3-icon-document-open::before{
  content:""; }

.bp3-icon-document-share::before{
  content:""; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"•"; }

.bp3-icon-double-caret-horizontal::before{
  content:""; }

.bp3-icon-double-caret-vertical::before{
  content:""; }

.bp3-icon-double-chevron-down::before{
  content:""; }

.bp3-icon-double-chevron-left::before{
  content:""; }

.bp3-icon-double-chevron-right::before{
  content:""; }

.bp3-icon-double-chevron-up::before{
  content:""; }

.bp3-icon-doughnut-chart::before{
  content:""; }

.bp3-icon-download::before{
  content:""; }

.bp3-icon-drag-handle-horizontal::before{
  content:""; }

.bp3-icon-drag-handle-vertical::before{
  content:""; }

.bp3-icon-draw::before{
  content:""; }

.bp3-icon-drive-time::before{
  content:""; }

.bp3-icon-duplicate::before{
  content:""; }

.bp3-icon-edit::before{
  content:"✎"; }

.bp3-icon-eject::before{
  content:"⏏"; }

.bp3-icon-endorsed::before{
  content:""; }

.bp3-icon-envelope::before{
  content:"✉"; }

.bp3-icon-equals::before{
  content:""; }

.bp3-icon-eraser::before{
  content:""; }

.bp3-icon-error::before{
  content:""; }

.bp3-icon-euro::before{
  content:"€"; }

.bp3-icon-exchange::before{
  content:""; }

.bp3-icon-exclude-row::before{
  content:""; }

.bp3-icon-expand-all::before{
  content:""; }

.bp3-icon-export::before{
  content:""; }

.bp3-icon-eye-off::before{
  content:""; }

.bp3-icon-eye-on::before{
  content:""; }

.bp3-icon-eye-open::before{
  content:""; }

.bp3-icon-fast-backward::before{
  content:""; }

.bp3-icon-fast-forward::before{
  content:""; }

.bp3-icon-feed::before{
  content:""; }

.bp3-icon-feed-subscribed::before{
  content:""; }

.bp3-icon-film::before{
  content:""; }

.bp3-icon-filter::before{
  content:""; }

.bp3-icon-filter-keep::before{
  content:""; }

.bp3-icon-filter-list::before{
  content:""; }

.bp3-icon-filter-open::before{
  content:""; }

.bp3-icon-filter-remove::before{
  content:""; }

.bp3-icon-flag::before{
  content:"⚑"; }

.bp3-icon-flame::before{
  content:""; }

.bp3-icon-flash::before{
  content:""; }

.bp3-icon-floppy-disk::before{
  content:""; }

.bp3-icon-flow-branch::before{
  content:""; }

.bp3-icon-flow-end::before{
  content:""; }

.bp3-icon-flow-linear::before{
  content:""; }

.bp3-icon-flow-review::before{
  content:""; }

.bp3-icon-flow-review-branch::before{
  content:""; }

.bp3-icon-flows::before{
  content:""; }

.bp3-icon-folder-close::before{
  content:""; }

.bp3-icon-folder-new::before{
  content:""; }

.bp3-icon-folder-open::before{
  content:""; }

.bp3-icon-folder-shared::before{
  content:""; }

.bp3-icon-folder-shared-open::before{
  content:""; }

.bp3-icon-follower::before{
  content:""; }

.bp3-icon-following::before{
  content:""; }

.bp3-icon-font::before{
  content:""; }

.bp3-icon-fork::before{
  content:""; }

.bp3-icon-form::before{
  content:""; }

.bp3-icon-full-circle::before{
  content:""; }

.bp3-icon-full-stacked-chart::before{
  content:""; }

.bp3-icon-fullscreen::before{
  content:""; }

.bp3-icon-function::before{
  content:""; }

.bp3-icon-gantt-chart::before{
  content:""; }

.bp3-icon-geolocation::before{
  content:""; }

.bp3-icon-geosearch::before{
  content:""; }

.bp3-icon-git-branch::before{
  content:""; }

.bp3-icon-git-commit::before{
  content:""; }

.bp3-icon-git-merge::before{
  content:""; }

.bp3-icon-git-new-branch::before{
  content:""; }

.bp3-icon-git-pull::before{
  content:""; }

.bp3-icon-git-push::before{
  content:""; }

.bp3-icon-git-repo::before{
  content:""; }

.bp3-icon-glass::before{
  content:""; }

.bp3-icon-globe::before{
  content:""; }

.bp3-icon-globe-network::before{
  content:""; }

.bp3-icon-graph::before{
  content:""; }

.bp3-icon-graph-remove::before{
  content:""; }

.bp3-icon-greater-than::before{
  content:""; }

.bp3-icon-greater-than-or-equal-to::before{
  content:""; }

.bp3-icon-grid::before{
  content:""; }

.bp3-icon-grid-view::before{
  content:""; }

.bp3-icon-group-objects::before{
  content:""; }

.bp3-icon-grouped-bar-chart::before{
  content:""; }

.bp3-icon-hand::before{
  content:""; }

.bp3-icon-hand-down::before{
  content:""; }

.bp3-icon-hand-left::before{
  content:""; }

.bp3-icon-hand-right::before{
  content:""; }

.bp3-icon-hand-up::before{
  content:""; }

.bp3-icon-header::before{
  content:""; }

.bp3-icon-header-one::before{
  content:""; }

.bp3-icon-header-two::before{
  content:""; }

.bp3-icon-headset::before{
  content:""; }

.bp3-icon-heart::before{
  content:"♥"; }

.bp3-icon-heart-broken::before{
  content:""; }

.bp3-icon-heat-grid::before{
  content:""; }

.bp3-icon-heatmap::before{
  content:""; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:""; }

.bp3-icon-highlight::before{
  content:""; }

.bp3-icon-history::before{
  content:""; }

.bp3-icon-home::before{
  content:"⌂"; }

.bp3-icon-horizontal-bar-chart::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:""; }

.bp3-icon-horizontal-distribution::before{
  content:""; }

.bp3-icon-id-number::before{
  content:""; }

.bp3-icon-image-rotate-left::before{
  content:""; }

.bp3-icon-image-rotate-right::before{
  content:""; }

.bp3-icon-import::before{
  content:""; }

.bp3-icon-inbox::before{
  content:""; }

.bp3-icon-inbox-filtered::before{
  content:""; }

.bp3-icon-inbox-geo::before{
  content:""; }

.bp3-icon-inbox-search::before{
  content:""; }

.bp3-icon-inbox-update::before{
  content:""; }

.bp3-icon-info-sign::before{
  content:"ℹ"; }

.bp3-icon-inheritance::before{
  content:""; }

.bp3-icon-inner-join::before{
  content:""; }

.bp3-icon-insert::before{
  content:""; }

.bp3-icon-intersection::before{
  content:""; }

.bp3-icon-ip-address::before{
  content:""; }

.bp3-icon-issue::before{
  content:""; }

.bp3-icon-issue-closed::before{
  content:""; }

.bp3-icon-issue-new::before{
  content:""; }

.bp3-icon-italic::before{
  content:""; }

.bp3-icon-join-table::before{
  content:""; }

.bp3-icon-key::before{
  content:""; }

.bp3-icon-key-backspace::before{
  content:""; }

.bp3-icon-key-command::before{
  content:""; }

.bp3-icon-key-control::before{
  content:""; }

.bp3-icon-key-delete::before{
  content:""; }

.bp3-icon-key-enter::before{
  content:""; }

.bp3-icon-key-escape::before{
  content:""; }

.bp3-icon-key-option::before{
  content:""; }

.bp3-icon-key-shift::before{
  content:""; }

.bp3-icon-key-tab::before{
  content:""; }

.bp3-icon-known-vehicle::before{
  content:""; }

.bp3-icon-lab-test::before{
  content:""; }

.bp3-icon-label::before{
  content:""; }

.bp3-icon-layer::before{
  content:""; }

.bp3-icon-layers::before{
  content:""; }

.bp3-icon-layout::before{
  content:""; }

.bp3-icon-layout-auto::before{
  content:""; }

.bp3-icon-layout-balloon::before{
  content:""; }

.bp3-icon-layout-circle::before{
  content:""; }

.bp3-icon-layout-grid::before{
  content:""; }

.bp3-icon-layout-group-by::before{
  content:""; }

.bp3-icon-layout-hierarchy::before{
  content:""; }

.bp3-icon-layout-linear::before{
  content:""; }

.bp3-icon-layout-skew-grid::before{
  content:""; }

.bp3-icon-layout-sorted-clusters::before{
  content:""; }

.bp3-icon-learning::before{
  content:""; }

.bp3-icon-left-join::before{
  content:""; }

.bp3-icon-less-than::before{
  content:""; }

.bp3-icon-less-than-or-equal-to::before{
  content:""; }

.bp3-icon-lifesaver::before{
  content:""; }

.bp3-icon-lightbulb::before{
  content:""; }

.bp3-icon-link::before{
  content:""; }

.bp3-icon-list::before{
  content:"☰"; }

.bp3-icon-list-columns::before{
  content:""; }

.bp3-icon-list-detail-view::before{
  content:""; }

.bp3-icon-locate::before{
  content:""; }

.bp3-icon-lock::before{
  content:""; }

.bp3-icon-log-in::before{
  content:""; }

.bp3-icon-log-out::before{
  content:""; }

.bp3-icon-manual::before{
  content:""; }

.bp3-icon-manually-entered-data::before{
  content:""; }

.bp3-icon-map::before{
  content:""; }

.bp3-icon-map-create::before{
  content:""; }

.bp3-icon-map-marker::before{
  content:""; }

.bp3-icon-maximize::before{
  content:""; }

.bp3-icon-media::before{
  content:""; }

.bp3-icon-menu::before{
  content:""; }

.bp3-icon-menu-closed::before{
  content:""; }

.bp3-icon-menu-open::before{
  content:""; }

.bp3-icon-merge-columns::before{
  content:""; }

.bp3-icon-merge-links::before{
  content:""; }

.bp3-icon-minimize::before{
  content:""; }

.bp3-icon-minus::before{
  content:"−"; }

.bp3-icon-mobile-phone::before{
  content:""; }

.bp3-icon-mobile-video::before{
  content:""; }

.bp3-icon-moon::before{
  content:""; }

.bp3-icon-more::before{
  content:""; }

.bp3-icon-mountain::before{
  content:""; }

.bp3-icon-move::before{
  content:""; }

.bp3-icon-mugshot::before{
  content:""; }

.bp3-icon-multi-select::before{
  content:""; }

.bp3-icon-music::before{
  content:""; }

.bp3-icon-new-drawing::before{
  content:""; }

.bp3-icon-new-grid-item::before{
  content:""; }

.bp3-icon-new-layer::before{
  content:""; }

.bp3-icon-new-layers::before{
  content:""; }

.bp3-icon-new-link::before{
  content:""; }

.bp3-icon-new-object::before{
  content:""; }

.bp3-icon-new-person::before{
  content:""; }

.bp3-icon-new-prescription::before{
  content:""; }

.bp3-icon-new-text-box::before{
  content:""; }

.bp3-icon-ninja::before{
  content:""; }

.bp3-icon-not-equal-to::before{
  content:""; }

.bp3-icon-notifications::before{
  content:""; }

.bp3-icon-notifications-updated::before{
  content:""; }

.bp3-icon-numbered-list::before{
  content:""; }

.bp3-icon-numerical::before{
  content:""; }

.bp3-icon-office::before{
  content:""; }

.bp3-icon-offline::before{
  content:""; }

.bp3-icon-oil-field::before{
  content:""; }

.bp3-icon-one-column::before{
  content:""; }

.bp3-icon-outdated::before{
  content:""; }

.bp3-icon-page-layout::before{
  content:""; }

.bp3-icon-panel-stats::before{
  content:""; }

.bp3-icon-panel-table::before{
  content:""; }

.bp3-icon-paperclip::before{
  content:""; }

.bp3-icon-paragraph::before{
  content:""; }

.bp3-icon-path::before{
  content:""; }

.bp3-icon-path-search::before{
  content:""; }

.bp3-icon-pause::before{
  content:""; }

.bp3-icon-people::before{
  content:""; }

.bp3-icon-percentage::before{
  content:""; }

.bp3-icon-person::before{
  content:""; }

.bp3-icon-phone::before{
  content:"☎"; }

.bp3-icon-pie-chart::before{
  content:""; }

.bp3-icon-pin::before{
  content:""; }

.bp3-icon-pivot::before{
  content:""; }

.bp3-icon-pivot-table::before{
  content:""; }

.bp3-icon-play::before{
  content:""; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:""; }

.bp3-icon-power::before{
  content:""; }

.bp3-icon-predictive-analysis::before{
  content:""; }

.bp3-icon-prescription::before{
  content:""; }

.bp3-icon-presentation::before{
  content:""; }

.bp3-icon-print::before{
  content:"⎙"; }

.bp3-icon-projects::before{
  content:""; }

.bp3-icon-properties::before{
  content:""; }

.bp3-icon-property::before{
  content:""; }

.bp3-icon-publish-function::before{
  content:""; }

.bp3-icon-pulse::before{
  content:""; }

.bp3-icon-random::before{
  content:""; }

.bp3-icon-record::before{
  content:""; }

.bp3-icon-redo::before{
  content:""; }

.bp3-icon-refresh::before{
  content:""; }

.bp3-icon-regression-chart::before{
  content:""; }

.bp3-icon-remove::before{
  content:""; }

.bp3-icon-remove-column::before{
  content:""; }

.bp3-icon-remove-column-left::before{
  content:""; }

.bp3-icon-remove-column-right::before{
  content:""; }

.bp3-icon-remove-row-bottom::before{
  content:""; }

.bp3-icon-remove-row-top::before{
  content:""; }

.bp3-icon-repeat::before{
  content:""; }

.bp3-icon-reset::before{
  content:""; }

.bp3-icon-resolve::before{
  content:""; }

.bp3-icon-rig::before{
  content:""; }

.bp3-icon-right-join::before{
  content:""; }

.bp3-icon-ring::before{
  content:""; }

.bp3-icon-rotate-document::before{
  content:""; }

.bp3-icon-rotate-page::before{
  content:""; }

.bp3-icon-satellite::before{
  content:""; }

.bp3-icon-saved::before{
  content:""; }

.bp3-icon-scatter-plot::before{
  content:""; }

.bp3-icon-search::before{
  content:""; }

.bp3-icon-search-around::before{
  content:""; }

.bp3-icon-search-template::before{
  content:""; }

.bp3-icon-search-text::before{
  content:""; }

.bp3-icon-segmented-control::before{
  content:""; }

.bp3-icon-select::before{
  content:""; }

.bp3-icon-selection::before{
  content:"⦿"; }

.bp3-icon-send-to::before{
  content:""; }

.bp3-icon-send-to-graph::before{
  content:""; }

.bp3-icon-send-to-map::before{
  content:""; }

.bp3-icon-series-add::before{
  content:""; }

.bp3-icon-series-configuration::before{
  content:""; }

.bp3-icon-series-derived::before{
  content:""; }

.bp3-icon-series-filtered::before{
  content:""; }

.bp3-icon-series-search::before{
  content:""; }

.bp3-icon-settings::before{
  content:""; }

.bp3-icon-share::before{
  content:""; }

.bp3-icon-shield::before{
  content:""; }

.bp3-icon-shop::before{
  content:""; }

.bp3-icon-shopping-cart::before{
  content:""; }

.bp3-icon-signal-search::before{
  content:""; }

.bp3-icon-sim-card::before{
  content:""; }

.bp3-icon-slash::before{
  content:""; }

.bp3-icon-small-cross::before{
  content:""; }

.bp3-icon-small-minus::before{
  content:""; }

.bp3-icon-small-plus::before{
  content:""; }

.bp3-icon-small-tick::before{
  content:""; }

.bp3-icon-snowflake::before{
  content:""; }

.bp3-icon-social-media::before{
  content:""; }

.bp3-icon-sort::before{
  content:""; }

.bp3-icon-sort-alphabetical::before{
  content:""; }

.bp3-icon-sort-alphabetical-desc::before{
  content:""; }

.bp3-icon-sort-asc::before{
  content:""; }

.bp3-icon-sort-desc::before{
  content:""; }

.bp3-icon-sort-numerical::before{
  content:""; }

.bp3-icon-sort-numerical-desc::before{
  content:""; }

.bp3-icon-split-columns::before{
  content:""; }

.bp3-icon-square::before{
  content:""; }

.bp3-icon-stacked-chart::before{
  content:""; }

.bp3-icon-star::before{
  content:"★"; }

.bp3-icon-star-empty::before{
  content:"☆"; }

.bp3-icon-step-backward::before{
  content:""; }

.bp3-icon-step-chart::before{
  content:""; }

.bp3-icon-step-forward::before{
  content:""; }

.bp3-icon-stop::before{
  content:""; }

.bp3-icon-stopwatch::before{
  content:""; }

.bp3-icon-strikethrough::before{
  content:""; }

.bp3-icon-style::before{
  content:""; }

.bp3-icon-swap-horizontal::before{
  content:""; }

.bp3-icon-swap-vertical::before{
  content:""; }

.bp3-icon-symbol-circle::before{
  content:""; }

.bp3-icon-symbol-cross::before{
  content:""; }

.bp3-icon-symbol-diamond::before{
  content:""; }

.bp3-icon-symbol-square::before{
  content:""; }

.bp3-icon-symbol-triangle-down::before{
  content:""; }

.bp3-icon-symbol-triangle-up::before{
  content:""; }

.bp3-icon-tag::before{
  content:""; }

.bp3-icon-take-action::before{
  content:""; }

.bp3-icon-taxi::before{
  content:""; }

.bp3-icon-text-highlight::before{
  content:""; }

.bp3-icon-th::before{
  content:""; }

.bp3-icon-th-derived::before{
  content:""; }

.bp3-icon-th-disconnect::before{
  content:""; }

.bp3-icon-th-filtered::before{
  content:""; }

.bp3-icon-th-list::before{
  content:""; }

.bp3-icon-thumbs-down::before{
  content:""; }

.bp3-icon-thumbs-up::before{
  content:""; }

.bp3-icon-tick::before{
  content:"✓"; }

.bp3-icon-tick-circle::before{
  content:""; }

.bp3-icon-time::before{
  content:"⏲"; }

.bp3-icon-timeline-area-chart::before{
  content:""; }

.bp3-icon-timeline-bar-chart::before{
  content:""; }

.bp3-icon-timeline-events::before{
  content:""; }

.bp3-icon-timeline-line-chart::before{
  content:""; }

.bp3-icon-tint::before{
  content:""; }

.bp3-icon-torch::before{
  content:""; }

.bp3-icon-tractor::before{
  content:""; }

.bp3-icon-train::before{
  content:""; }

.bp3-icon-translate::before{
  content:""; }

.bp3-icon-trash::before{
  content:""; }

.bp3-icon-tree::before{
  content:""; }

.bp3-icon-trending-down::before{
  content:""; }

.bp3-icon-trending-up::before{
  content:""; }

.bp3-icon-truck::before{
  content:""; }

.bp3-icon-two-columns::before{
  content:""; }

.bp3-icon-unarchive::before{
  content:""; }

.bp3-icon-underline::before{
  content:"⎁"; }

.bp3-icon-undo::before{
  content:"⎌"; }

.bp3-icon-ungroup-objects::before{
  content:""; }

.bp3-icon-unknown-vehicle::before{
  content:""; }

.bp3-icon-unlock::before{
  content:""; }

.bp3-icon-unpin::before{
  content:""; }

.bp3-icon-unresolve::before{
  content:""; }

.bp3-icon-updated::before{
  content:""; }

.bp3-icon-upload::before{
  content:""; }

.bp3-icon-user::before{
  content:""; }

.bp3-icon-variable::before{
  content:""; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:""; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:""; }

.bp3-icon-vertical-distribution::before{
  content:""; }

.bp3-icon-video::before{
  content:""; }

.bp3-icon-volume-down::before{
  content:""; }

.bp3-icon-volume-off::before{
  content:""; }

.bp3-icon-volume-up::before{
  content:""; }

.bp3-icon-walk::before{
  content:""; }

.bp3-icon-warning-sign::before{
  content:""; }

.bp3-icon-waterfall-chart::before{
  content:""; }

.bp3-icon-widget::before{
  content:""; }

.bp3-icon-widget-button::before{
  content:""; }

.bp3-icon-widget-footer::before{
  content:""; }

.bp3-icon-widget-header::before{
  content:""; }

.bp3-icon-wrench::before{
  content:""; }

.bp3-icon-zoom-in::before{
  content:""; }

.bp3-icon-zoom-out::before{
  content:""; }

.bp3-icon-zoom-to-fit::before{
  content:""; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }
  .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{ }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  background:#ffffff;
  border-radius:3px;
  color:#182026;
  list-style:none;
  margin:0;
  min-width:180px;
  padding:5px;
  text-align:left; }

.bp3-menu-divider{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px; }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  color:inherit;
  line-height:20px;
  padding:5px 7px;
  text-decoration:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    color:#5c7080;
    margin-top:2px; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit !important;
    color:rgba(92, 112, 128, 0.6) !important;
    cursor:not-allowed !important;
    outline:none !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    font-size:16px;
    line-height:22px;
    padding:9px 7px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-right:10px;
      margin-top:1px; }

button.bp3-menu-item{
  background:none;
  border:none;
  text-align:left;
  width:100%; }
.bp3-menu-header{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px;
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    line-height:17px;
    margin:0;
    padding:10px 7px 0 1px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    font-size:18px;
    padding-bottom:5px;
    padding-top:15px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item{ }
  .bp3-dark .bp3-menu-item.bp3-intent-primary{
    color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-success{
    color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning{
    color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger{
    color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item::before,
  .bp3-dark .bp3-menu-item > .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item .bp3-menu-item-label{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
    background-color:rgba(138, 155, 168, 0.3); }
  .bp3-dark .bp3-menu-item.bp3-disabled{
    color:rgba(167, 182, 194, 0.6) !important; }
    .bp3-dark .bp3-menu-item.bp3-disabled::before,
    .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  background-color:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  height:50px;
  padding:0 15px;
  position:relative;
  width:100%;
  z-index:10; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    left:0;
    position:fixed;
    right:0;
    top:0; }

.bp3-navbar-heading{
  font-size:16px;
  margin-right:15px; }

.bp3-navbar-group{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px;
  margin:0 10px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:100%;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  text-align:center;
  width:100%; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  bottom:0;
  left:0;
  position:static;
  right:0;
  top:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    overflow:hidden;
    position:fixed; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    overflow:auto;
    position:fixed; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  bottom:0;
  left:0;
  position:fixed;
  right:0;
  top:0;
  opacity:1;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  z-index:20; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }
  .bp3-panel-stack-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-panel-stack2{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack2-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack2-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack2-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack2-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack2-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack2-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-view{
    background-color:#30404d; }
  .bp3-panel-stack2-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter, .bp3-panel-stack2-push .bp3-panel-stack2-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter-active, .bp3-panel-stack2-push .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter, .bp3-panel-stack2-pop .bp3-panel-stack2-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter-active, .bp3-panel-stack2-pop .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  border-radius:3px;
  display:inline-block;
  z-index:20; }
  .bp3-popover .bp3-popover-arrow{
    height:30px;
    position:absolute;
    width:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      height:20px;
      margin:5px;
      width:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-bottom:17px;
    margin-top:-17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-left:-17px;
    margin-right:17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover .bp3-popover-content{
    border-radius:3px;
    position:relative; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  border-radius:2px;
  content:"";
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg); }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  left:0;
  position:absolute;
  right:0;
  top:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  background:rgba(92, 112, 128, 0.2);
  border-radius:40px;
  display:block;
  height:8px;
  overflow:hidden;
  position:relative;
  width:100%; }
  .bp3-progress-bar .bp3-progress-meter{
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    border-radius:40px;
    height:100%;
    position:absolute;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:100%; }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  color:transparent !important;
  cursor:default;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  height:40px;
  min-width:150px;
  width:100%;
  cursor:default;
  outline:none;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    cursor:not-allowed;
    opacity:0.5; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  height:6px;
  left:0;
  right:0;
  top:5px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  height:16px;
  left:0;
  position:absolute;
  top:0;
  width:16px; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab;
    z-index:2; }
  .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    background:#bfccd6;
    -webkit-box-shadow:none;
            box-shadow:none;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    background:#5c7080;
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-slider-handle .bp3-slider-label{
    background:#394b59;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    color:#f5f8fa;
    margin-left:8px; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      background:#e1e8ed;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-bottom-right-radius:0;
    border-top-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    border-bottom-left-radius:0;
    border-top-left-radius:0;
    margin-left:8px; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  font-size:12px;
  line-height:1;
  padding:2px 5px;
  position:absolute;
  vertical-align:top; }

.bp3-slider.bp3-vertical{
  height:150px;
  min-width:40px;
  width:40px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    bottom:0;
    height:auto;
    left:5px;
    top:0;
    width:6px; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-left:0;
      margin-top:-8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      height:8px;
      margin-left:0;
      width:16px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-bottom-right-radius:3px;
      border-top-left-radius:0; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      border-bottom-left-radius:0;
      border-bottom-right-radius:0;
      border-top-left-radius:3px;
      margin-bottom:8px; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round;
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      padding:0 10px;
      width:100%; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        background-color:rgba(19, 124, 189, 0.2);
        -webkit-box-shadow:none;
                box-shadow:none; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      background-color:rgba(19, 124, 189, 0.2);
      border-radius:3px;
      bottom:0;
      height:auto;
      left:0;
      right:0;
      top:0; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  border:none;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  list-style:none;
  margin:0;
  padding:0;
  position:relative; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:#182026;
  cursor:pointer;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  font-size:14px;
  line-height:30px;
  max-width:100%;
  position:relative;
  vertical-align:top; }
  .bp3-tab a{
    color:inherit;
    display:block;
    text-decoration:none; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    background-color:transparent !important;
    -webkit-box-shadow:none !important;
            box-shadow:none !important; }
  .bp3-tab[aria-disabled="true"]{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    font-size:16px;
    line-height:40px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  left:0;
  pointer-events:none;
  position:absolute;
  top:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    background-color:#106ba3;
    bottom:0;
    height:3px;
    left:0;
    position:absolute;
    right:0; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#5c7080;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  color:#f5f8fa;
  font-size:12px;
  line-height:16px;
  max-width:100%;
  min-height:20px;
  min-width:20px;
  padding:2px 6px;
  position:relative; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-left:8px;
    padding-right:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    font-size:14px;
    line-height:20px;
    min-height:30px;
    min-width:30px;
    padding:5px 10px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-left:12px;
      padding-right:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  background:none;
  border:none;
  color:inherit;
  cursor:pointer;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin-bottom:-2px;
  margin-right:-6px !important;
  margin-top:-2px;
  opacity:0.5;
  padding:2px;
  padding-left:0; }
  .bp3-tag-remove:hover{
    background:none;
    opacity:0.8;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:0 5px 0 0; }
    .bp3-large .bp3-tag-remove:empty::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  line-height:inherit;
  min-height:30px;
  padding-left:5px;
  padding-right:0; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    color:#5c7080;
    margin-left:2px;
    margin-right:7px;
    margin-top:7px; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    margin-right:7px;
    margin-top:5px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:20px;
    width:80px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-left:5px;
      margin-top:10px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-height:30px;
      min-width:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:20px 0 0;
  max-width:500px;
  min-width:300px;
  pointer-events:all;
  position:relative !important; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-delay:50ms;
            transition-delay:50ms;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    color:#5c7080;
    margin:12px;
    margin-right:0; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    background-color:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  left:0;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none;
  right:0;
  z-index:40; }
  .bp3-toast-container.bp3-toast-container-in-portal{
    position:fixed; }
  .bp3-toast-container.bp3-toast-container-inline{
    position:absolute; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0; }
  .bp3-toast-container.bp3-toast-container-bottom{
    bottom:0;
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-exit-active ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    height:22px;
    position:absolute;
    width:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      height:14px;
      margin:4px;
      width:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-bottom:11px;
    margin-top:-11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-left:-11px;
    margin-right:11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  list-style:none;
  margin:0;
  padding-left:0; }

.bp3-tree-root{
  background-color:transparent;
  cursor:default;
  padding-left:0;
  position:relative; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:30px;
  padding-right:5px;
  width:100%; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  cursor:pointer;
  padding:7px;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:""; }

.bp3-tree-node-icon{
  margin-right:7px;
  position:relative; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  left:calc(50% - 250px);
  top:20vh;
  width:500px;
  z-index:21; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar .bp3-input{
    background-color:transparent;
    border-radius:0; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    background-color:transparent;
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MC45NzggNTAuOTc4IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MC45NzggNTAuOTc4OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+Cgk8Zz4KCQk8cGF0aCBzdHlsZT0iZmlsbDojMDEwMDAyOyIgZD0iTTQzLjUyLDcuNDU4QzM4LjcxMSwyLjY0OCwzMi4zMDcsMCwyNS40ODksMEMxOC42NywwLDEyLjI2NiwyLjY0OCw3LjQ1OCw3LjQ1OAoJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDAKCQkJYzYuODE2LDAsMTMuMjIxLTIuNjQ4LDE4LjAyOS03LjQ1OGM0LjgwOS00LjgwOSw3LjQ1Ny0xMS4yMTIsNy40NTctMTguMDNDNTAuOTc3LDE4LjY3LDQ4LjMyOCwxMi4yNjYsNDMuNTIsNy40NTh6CgkJCSBNNDIuMTA2LDQyLjEwNWMtNC40MzIsNC40MzEtMTAuMzMyLDYuODcyLTE2LjYxNSw2Ljg3MmgtMC4wMDJjLTYuMjg1LTAuMDAxLTEyLjE4Ny0yLjQ0MS0xNi42MTctNi44NzIKCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzIKCQkJYzQuNDMxLDQuNDMxLDYuODcxLDEwLjMzMiw2Ljg3MSwxNi42MTdDNDguOTc3LDMxLjc3Miw0Ni41MzYsMzcuNjc1LDQyLjEwNiw0Mi4xMDV6Ii8+CgkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik0yMy41NzgsMzIuMjE4Yy0wLjAyMy0xLjczNCwwLjE0My0zLjA1OSwwLjQ5Ni0zLjk3MmMwLjM1My0wLjkxMywxLjExLTEuOTk3LDIuMjcyLTMuMjUzCgkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUKCQkJYzAtMS4wOTYtMC4yNi0yLjA4OC0wLjc3OS0yLjk3OWMtMC41NjUtMC44NzktMS41MDEtMS4zMzYtMi44MDYtMS4zNjljLTEuODAyLDAuMDU3LTIuOTg1LDAuNjY3LTMuNTUsMS44MzIKCQkJYy0wLjMwMSwwLjUzNS0wLjUwMywxLjE0MS0wLjYwNywxLjgxNGMtMC4xMzksMC43MDctMC4yMDcsMS40MzItMC4yMDcsMi4xNzRoLTIuOTM3Yy0wLjA5MS0yLjIwOCwwLjQwNy00LjExNCwxLjQ5My01LjcxOQoJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQoJCQljMCwxLjE0Mi0wLjEzNywyLjExMS0wLjQxLDIuOTExYy0wLjMwOSwwLjg0NS0wLjczMSwxLjU5My0xLjI2OCwyLjI0M2MtMC40OTIsMC42NS0xLjA2OCwxLjMxOC0xLjczLDIuMDAyCgkJCWMtMC42NSwwLjY5Ny0xLjMxMywxLjQ3OS0xLjk4NywyLjM0NmMtMC4yMzksMC4zNzctMC40MjksMC43NzctMC41NjUsMS4xOTljLTAuMTYsMC45NTktMC4yMTcsMS45NTEtMC4xNzEsMi45NzkKCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}
.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}
.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}
.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-border-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0px;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-warn-color0);
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px 5px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FileDialog-Checkbox {
  margin-top: 35px;
  display: flex;
  flex-direction: row;
  align-items: end;
  width: 100%;
}

.jp-FileDialog-Checkbox > label {
  flex: 1 1 auto;
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
  overflow-x: auto;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
  outline: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .remote-caret {
  position: relative;
  border-left: 2px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .remote-caret > div {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -2px;
  font-size: 0.95em;
  background-color: rgb(250, 129, 0);
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 3;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .remote-caret.hide-name > div {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .remote-caret:hover > div {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
  margin: 8px 12px 0px 12px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: flex-start;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0px;
  padding-right: 2px;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 40px;
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent {
  width: 72px;
  background: var(--jp-brand-color1);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent:focus-visible {
  background-color: var(--jp-brand-color0);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent
  .jp-icon3 {
  fill: white;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileBrowser-filterBox {
  padding: 0px;
  flex: 0 0 auto;
  margin: 8px 12px 0px 12px;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing:focus-visible {
  border: 1px solid var(--jp-brand-color1);
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon:before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

body[data-format='mobile'] .jp-OutputArea-child {
  flex-direction: column;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-OutputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  margin-left: var(--jp-notebook-padding);
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

body[data-format='mobile'] .jp-InputArea {
  flex-direction: column;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
  overflow: hidden;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

body[data-format='mobile'] .jp-InputArea-editor {
  margin-left: var(--jp-notebook-padding);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-InputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

.jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
}

.jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-collapseHeadingButton {
  display: none;
}

.jp-MarkdownCell:hover .jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook-render * {
  contain: none !important;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
  float: left;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt:before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body div {
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.CodeMirror.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.CodeMirror-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Using table instead of flexbox so that we can use break-inside property */
/* CSS rules under this comment should not be required anymore after we move to the JupyterLab 4.0 CSS */


.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  min-width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-OutputArea-child {
  display: table;
  width: 100%;
}

.jp-OutputPrompt {
  display: table-cell;
  vertical-align: top;
  min-width: var(--jp-cell-prompt-width);
}

body[data-format='mobile'] .jp-OutputPrompt {
  display: table-row;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  display: table-row;
}

.jp-OutputArea-output.jp-OutputArea-executeResult {
  width: 100%;
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }

  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}
</style>

<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 id="El-comod%C3%ADn-de-la-f%C3%ADsica:-La-ecuaci%C3%B3n-itinerario">El comod&#237;n de la f&#237;sica: La ecuaci&#243;n itinerario<a class="anchor-link" href="#El-comod%C3%ADn-de-la-f%C3%ADsica:-La-ecuaci%C3%B3n-itinerario">;</a></h3><p>Supongamos que se observa una masa en movimiento dentro de la tierra. Ese movimiento estará regido por las leyes de movimiento de Newton. Asi nomas es la realidad. Así que si te interesa la física y la astrofísica, es recomendable que entiendas estas leyes y sus potenciales usos.</p>
<p>Estas leyes describen casos interesantes para la física, como es el campo de las orbitas clásicas, el lanzamiento de proyectiles, entre otros usos.</p>
<p>El origen de la ecuación itinerario:</p>
<p>Si describimos la posición de un punto en el tiempo usando una función, las fuerzas que actuan sobre ese cuerpo son proporcionales a la masa por su aceleración, es decir:</p>
$$
\vec{F} = m\vec{a}
$$<p>La clásica segunda ley de Newton. Si tenemos una partícula que acelera con $\vec{a}$ constante, podemos derivar su ecuación de movimiento recordando que $\displaystyle \vec{a} = \frac{d\vec{v}}{dt}$, integrando ambos lados con respecto al tiempo, obtenemos:</p>
$$
\int \frac{d\vec{v}}{dt} \, dt = \int \vec{a} \, dt \ \ \ \Rightarrow \ \ \ \vec{v}= \vec{v}_0 + \vec{a}t 
 \ \ \ \ \  $$<p>donde $\vec{v}_0$ es la velocidad inicial. Integrando nuevamente la velocidad para obtener la posición $\vec{x}$, tenemos:</p>
$$
\int \frac{d\vec{x}}{dt} \, dt = \int \vec{v} \, dt = \int (\vec{v}_0+\vec{a}t) \, dt \ \ \ \ \  
$$$$
\Rightarrow \ \ \ \vec{x} = \frac{1}{2} \vec{a}t^2 + \vec{v}_0t + \vec{x}_0 
$$<p>donde $x_0$ es la posición inicial. Por lo tanto, la ecuación de movimiento para una partícula uniformemente acelerada es:</p>
$$
\vec{x}(t) = \vec{x}_0 + \vec{v}_0 t + \frac{1}{2} \vec{a} t^2 \ \ \ \ \ 
$$<p>La ecuación de itinerario es la ecuación que indica la posición de un objeto en función del tiempo. Se usa para predecir la ubicación de un objeto en un tiempo cualquiera $t$. Por supuesto, como el vector posición $\vec{x}$ (a.k.a. \vec{r}) está definido como un vector, es un objeto que tiene a lo menos dos coordenadas. Si quisieramos utilizarlo para describir el movimiento en dos dimensiones (2D), por ende la descripción usual de</p>
$$
\vec{r}(x(t),y(t)) = x(t) \hat{i} + y(t) \hat{j},
$$<p>donde</p>
$$
x(t) = x_0 + v_x t + \frac{1}{2} a_x t^2, 
$$$$
y(t) = y_0 + v_y t + \frac{1}{2} a_y t^2, 
$$<p>Solo queda asumir qué valores necesitamos para las constantes $x_0,y_0$ (posiciones iniciales), $v_x, v_y$ la velocidad inicial, $a_x, a_y$ las aceleraciones, para poder describir el proceso físico de interés. El más clásico diria yo, es el lanzamiento de un proyectil.</p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 id="El-lanzamiento-de-proyectil">El lanzamiento de proyectil<a class="anchor-link" href="#El-lanzamiento-de-proyectil"></a></h3><p>El lanzamiento de un proyectil es un problema clásico de la física que se puede analizar utilizando las leyes del movimiento. La idea es utilizar la ecuación itinerario para simular la trayectoria de una masa lanzada con una velocidad inicial en una dirección específica.</p>
<p>Digamos, por ejemplo, que hay una pelota de fubtol en reposo sobre una superficie. El primer instinsto de un porcentaje preocupante de la población, sería patear la pelota, lanzandola quizá dónde. Perdimos la pelota, pero fuimos testigos del lanzamiento de un proyectil. Cualquier objeto que es lanzado y continúa en movimiento producto de su propia inercia es llamado &quot;un proyectil&quot;.</p>
<p>Si fijamos el origen de coordenadas cartesiano sobre el punto inicial de la pelota, tenemos que $x_0 = 0$ e $y_0 = 0$, sólo necesitamos saber la velocidad inicial $\vec{v}_0$ y el ángulo $\theta$ en el cual ha sido lanzada la pelota por la senda patada propinada por la falta de límites. podemos estimar la velocidad de la patada y usar la ecuación itinerario para saber dónde estará la pelota en cada instante de tiempo $t$</p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<img src="https://iwant2study.org/lookangejss/physicaleducation/ejss_model_projectileESSangleofrelease/projectile/Screenshot%202020-02-18%20at%203.46.53%20PM.png" width="250" height="150" />

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>

<span class="c1"># Crear la figura y el eje</span>
<span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">4</span><span class="p">,</span> <span class="mi">3</span><span class="p">))</span>

<span class="n">fz</span><span class="o">=</span><span class="mi">12</span>

<span class="c1"># Dibujar la fuerza resultante</span>
<span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="n">head_width</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">head_length</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">fc</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">2.5</span><span class="p">,</span> <span class="mf">1.5</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$\vec</span><span class="si">{v}</span><span class="s1">$&#39;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="o">+</span><span class="mi">5</span><span class="p">)</span>

<span class="c1"># Dibujar las componentes</span>
<span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="n">head_width</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">head_length</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">fc</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">1.35</span><span class="p">,</span> <span class="o">-</span><span class="mf">0.5</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$v_x \hat</span><span class="si">{i}</span><span class="s1"> = \vec</span><span class="si">{v}</span><span class="s1"> \cos(\theta)$&#39;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="p">)</span>

<span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="n">head_width</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">head_length</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">fc</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="o">-</span><span class="mf">0.7</span><span class="p">,</span> <span class="mf">1.8</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$v_y \hat</span><span class="si">{j}</span><span class="s1">$&#39;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="o">-</span><span class="mf">0.65</span><span class="p">,</span> <span class="mf">1.4</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$=$&#39;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="o">-</span><span class="mf">0.95</span><span class="p">,</span> <span class="mf">1.0</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$\vec</span><span class="si">{v}</span><span class="s1"> \sin(\theta)$&#39;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="p">)</span>

<span class="c1"># Dibujar las líneas punteadas para los componentes</span>
<span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">([</span><span class="mi">4</span><span class="p">,</span> <span class="mi">4</span><span class="p">],</span> <span class="p">[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">0</span><span class="p">],</span> <span class="s1">&#39;k--&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">([</span><span class="mi">4</span><span class="p">,</span> <span class="mi">0</span><span class="p">],</span> <span class="p">[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">3</span><span class="p">],</span> <span class="s1">&#39;k--&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">)</span>

<span class="c1"># Etiquetar el ángulo</span>
<span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">0.5</span><span class="p">,</span> <span class="mf">0.1</span><span class="p">,</span> <span class="sa">r</span><span class="s1">&#39;$\theta$&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="n">fz</span><span class="p">)</span>

<span class="c1"># Dibujar el semicírculo para enfatizar el ángulo theta</span>
<span class="n">theta</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linspace</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="n">np</span><span class="o">.</span><span class="n">arctan2</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">),</span> <span class="mi">100</span><span class="p">)</span>
<span class="n">x</span> <span class="o">=</span> <span class="mf">0.8</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">cos</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span>
<span class="n">y</span> <span class="o">=</span> <span class="mf">0.8</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="s1">&#39;k-&#39;</span><span class="p">)</span>

<span class="n">ax</span><span class="o">.</span><span class="n">set_aspect</span><span class="p">(</span><span class="s1">&#39;equal&#39;</span><span class="p">)</span>

<span class="c1"># Quitar los ejes</span>
<span class="n">ax</span><span class="o">.</span><span class="n">axis</span><span class="p">(</span><span class="s1">&#39;off&#39;</span><span class="p">)</span>

<span class="c1"># Mostrar el gráfico</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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"
class="
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>como en el eje x no existe la gravedad, no existe aceleración actuando sobre la pelota, por ende $a_x$ = 0, por otro lado, el eje y si hay aceleración de gravedad, por lo que la aceleración provocada en esta dimensión es la famosa constate de gravedad g, es decir, $a_y = g$. con esto, nuestras ecuaciones se reducen a:</p>
$$
x(t) = v_x \cos(\theta) \cdot t 
$$$$
y(t) = v_y \sin(\theta) \cdot t - \frac{1}{2} g t^2
$$<p>donde $x(t)$ y $y(t)$ son las posiciones horizontal y vertical del proyectil en el tiempo $t$. Y con eso ya estaríamos.</p>
<p>Ahora, podríamos usar los trucos de la física para poder determinar un modelo y predecir su trayectoria haciendo algunas observaciones. Para la trayectoria vertical en función de la coordenada $y(x)$, reordenamos el parámetro $t$ de las ecuaciones anteriores. De la ecuación para $x(t)$:</p>
$$
x(t) = v_x \cos(\theta) \cdot t \Rightarrow t(x) = \frac{x}{v_x \cos(\theta)}
$$<p>Sustituyendo esta expresión de $t$ en la ecuación para $y(t)$:</p>
$$
y = v_y \sin(\theta) \cdot \frac{x}{v_x \cos(\theta)} - \frac{1}{2} g \left( \frac{x}{v_x \cos(\theta)} \right)^2
$$<p>Simplificando, obtenemos la ecuación del itinerario del proyectil:</p>
$$
y(x) = \frac{v_y}{v_x} \tan(\theta) x - \frac{g x^2}{2 v_x^2 \cos^2(\theta)}
$$<p>Esta ecuación describe la trayectoria parabólica del proyectil en cualquier valor</p>
<p>Hemos derivado la ecuación del itinerario de un proyectil lanzado con una velocidad inicial (v_0) y un ángulo (\theta). Esta ecuación nos permite predecir la posición del proyectil en cualquier punto de su trayectoria.</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">matplotlib.animation</span> <span class="k">as</span> <span class="nn">animation</span>
<span class="kn">from</span> <span class="nn">IPython.display</span> <span class="kn">import</span> <span class="n">HTML</span>
<span class="c1"># Estilo de fondo oscuro</span>
<span class="n">plt</span><span class="o">.</span><span class="n">style</span><span class="o">.</span><span class="n">use</span><span class="p">(</span><span class="s1">&#39;dark_background&#39;</span><span class="p">)</span>

<span class="c1"># Constantes</span>
<span class="n">g</span> <span class="o">=</span> <span class="mf">9.81</span>  <span class="c1"># Aceleración de la gravedad (m/s^2)</span>
<span class="n">v0</span> <span class="o">=</span> <span class="mi">15</span>  <span class="c1"># Velocidad inicial (m/s)</span>
<span class="n">angles</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linspace</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span> <span class="mi">75</span><span class="p">,</span> <span class="mi">10</span><span class="p">)</span>  <span class="c1"># Ángulos de lanzamiento (grados)</span>
<span class="n">t_max</span> <span class="o">=</span> <span class="mi">2</span> <span class="o">*</span> <span class="n">v0</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angles</span><span class="p">))</span> <span class="o">/</span> <span class="n">g</span>  <span class="c1"># Tiempo máximo de vuelo para cada ángulo</span>
<span class="n">t</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linspace</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="n">t_max</span><span class="o">.</span><span class="n">max</span><span class="p">(),</span> <span class="n">num</span><span class="o">=</span><span class="mi">200</span><span class="p">)</span>  <span class="c1"># Vector de tiempo, aumentamos el número de puntos</span>

<span class="c1"># Configurar la figura y el eje</span>
<span class="c1">#fig = plt.figure(figsize=(3, 6))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">111</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlim</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="p">(</span><span class="n">v0</span><span class="o">**</span><span class="mi">2</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="mi">2</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angles</span><span class="p">))</span><span class="o">.</span><span class="n">max</span><span class="p">())</span> <span class="o">/</span> <span class="n">g</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylim</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="p">(</span><span class="n">v0</span><span class="o">**</span><span class="mi">2</span> <span class="o">*</span> <span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angles</span><span class="p">)))</span><span class="o">**</span><span class="mi">2</span><span class="p">)</span><span class="o">.</span><span class="n">max</span><span class="p">()</span> <span class="o">/</span> <span class="p">(</span><span class="mi">2</span> <span class="o">*</span> <span class="n">g</span><span class="p">))</span>

<span class="c1"># Función para calcular la trayectoria de un proyectil</span>
<span class="k">def</span> <span class="nf">trajectory</span><span class="p">(</span><span class="n">v0</span><span class="p">,</span> <span class="n">angle</span><span class="p">,</span> <span class="n">t</span><span class="p">):</span>
    <span class="n">theta</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angle</span><span class="p">)</span>
    <span class="n">x</span> <span class="o">=</span> <span class="n">v0</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">cos</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span> <span class="o">*</span> <span class="n">t</span>
    <span class="n">y</span> <span class="o">=</span> <span class="n">v0</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span> <span class="o">*</span> <span class="n">t</span> <span class="o">-</span> <span class="mf">0.5</span> <span class="o">*</span> <span class="n">g</span> <span class="o">*</span> <span class="n">t</span><span class="o">**</span><span class="mi">2</span>
    <span class="k">return</span> <span class="n">x</span><span class="p">,</span> <span class="n">y</span>

<span class="c1"># Función para calcular la trayectoria predicta</span>
<span class="k">def</span> <span class="nf">predicted_trajectory</span><span class="p">(</span><span class="n">v0</span><span class="p">,</span> <span class="n">angle</span><span class="p">,</span> <span class="n">x</span><span class="p">):</span>
    <span class="n">theta</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angle</span><span class="p">)</span>
    <span class="n">y</span> <span class="o">=</span> <span class="n">x</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">tan</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span> <span class="o">-</span> <span class="p">(</span><span class="n">g</span> <span class="o">*</span> <span class="n">x</span><span class="o">**</span><span class="mi">2</span><span class="p">)</span> <span class="o">/</span> <span class="p">(</span><span class="mi">2</span> <span class="o">*</span> <span class="n">v0</span><span class="o">**</span><span class="mi">2</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">cos</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span><span class="o">**</span><span class="mi">2</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">y</span>

<span class="c1"># Crear líneas para cada ángulo</span>
<span class="n">lines</span> <span class="o">=</span> <span class="p">[</span><span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">([],</span> <span class="p">[])[</span><span class="mi">0</span><span class="p">]</span> <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="n">angles</span><span class="p">]</span>
<span class="n">predicted_lines</span> <span class="o">=</span> <span class="p">[</span><span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">([],</span> <span class="p">[],</span> <span class="s1">&#39;--&#39;</span><span class="p">,</span> <span class="n">lw</span><span class="o">=</span><span class="mf">0.5</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span> <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="n">angles</span><span class="p">]</span>  <span class="c1"># Líneas predichas</span>

<span class="c1"># Crear listas para las flechas de velocidad y gravedad</span>
<span class="n">vel_arrows</span> <span class="o">=</span> <span class="p">[</span><span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;blue&#39;</span><span class="p">)</span> <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="n">angles</span><span class="p">]</span>
<span class="n">g_arrows</span> <span class="o">=</span> <span class="p">[</span><span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;green&#39;</span><span class="p">)</span> <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="n">angles</span><span class="p">]</span>
<span class="n">particles</span> <span class="o">=</span> <span class="p">[</span><span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">([],</span> <span class="p">[],</span> <span class="s1">&#39;ro&#39;</span><span class="p">,</span> <span class="n">markersize</span><span class="o">=</span><span class="mi">10</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span> <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="n">angles</span><span class="p">]</span>  <span class="c1"># Partículas más grandes</span>

<span class="c1"># Inicializar la animación</span>
<span class="k">def</span> <span class="nf">init</span><span class="p">():</span>
    <span class="k">for</span> <span class="n">line</span><span class="p">,</span> <span class="n">predicted_line</span><span class="p">,</span> <span class="n">vel_arrow</span><span class="p">,</span> <span class="n">g_arrow</span><span class="p">,</span> <span class="n">particle</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">lines</span><span class="p">,</span> <span class="n">predicted_lines</span><span class="p">,</span> <span class="n">vel_arrows</span><span class="p">,</span> <span class="n">g_arrows</span><span class="p">,</span> <span class="n">particles</span><span class="p">):</span>
        <span class="n">line</span><span class="o">.</span><span class="n">set_data</span><span class="p">([],</span> <span class="p">[])</span>
        <span class="n">predicted_line</span><span class="o">.</span><span class="n">set_data</span><span class="p">([],</span> <span class="p">[])</span>
        <span class="n">vel_arrow</span><span class="o">.</span><span class="n">set_visible</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
        <span class="n">g_arrow</span><span class="o">.</span><span class="n">set_visible</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
        <span class="n">particle</span><span class="o">.</span><span class="n">set_data</span><span class="p">([],</span> <span class="p">[])</span>
    <span class="k">return</span> <span class="n">lines</span> <span class="o">+</span> <span class="n">predicted_lines</span> <span class="o">+</span> <span class="n">vel_arrows</span> <span class="o">+</span> <span class="n">g_arrows</span> <span class="o">+</span> <span class="n">particles</span>

<span class="c1"># Función de actualización para la animación</span>
<span class="k">def</span> <span class="nf">update</span><span class="p">(</span><span class="n">frame</span><span class="p">):</span>
    <span class="k">for</span> <span class="n">line</span><span class="p">,</span> <span class="n">predicted_line</span><span class="p">,</span> <span class="n">vel_arrow</span><span class="p">,</span> <span class="n">g_arrow</span><span class="p">,</span> <span class="n">particle</span><span class="p">,</span> <span class="n">angle</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">lines</span><span class="p">,</span> <span class="n">predicted_lines</span><span class="p">,</span> <span class="n">vel_arrows</span><span class="p">,</span> <span class="n">g_arrows</span><span class="p">,</span> <span class="n">particles</span><span class="p">,</span> <span class="n">angles</span><span class="p">):</span>
        <span class="n">x</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">trajectory</span><span class="p">(</span><span class="n">v0</span><span class="p">,</span> <span class="n">angle</span><span class="p">,</span> <span class="n">t</span><span class="p">[:</span><span class="n">frame</span><span class="p">])</span>
        <span class="n">line</span><span class="o">.</span><span class="n">set_data</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>

        <span class="c1"># Calcular la trayectoria predicta completa</span>
        <span class="n">x_pred</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linspace</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="p">(</span><span class="n">v0</span><span class="o">**</span><span class="mi">2</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="mi">2</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angle</span><span class="p">)))</span> <span class="o">/</span> <span class="n">g</span><span class="p">,</span> <span class="n">num</span><span class="o">=</span><span class="mi">100</span><span class="p">)</span>
        <span class="n">y_pred</span> <span class="o">=</span> <span class="n">predicted_trajectory</span><span class="p">(</span><span class="n">v0</span><span class="p">,</span> <span class="n">angle</span><span class="p">,</span> <span class="n">x_pred</span><span class="p">)</span>
        <span class="n">predicted_line</span><span class="o">.</span><span class="n">set_data</span><span class="p">(</span><span class="n">x_pred</span><span class="p">,</span> <span class="n">y_pred</span><span class="p">)</span>

        <span class="c1"># Última posición</span>
        <span class="k">if</span> <span class="nb">len</span><span class="p">(</span><span class="n">x</span><span class="p">)</span> <span class="o">&gt;</span> <span class="mi">0</span> <span class="ow">and</span> <span class="nb">len</span><span class="p">(</span><span class="n">y</span><span class="p">)</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">:</span>
            <span class="n">x_pos</span><span class="p">,</span> <span class="n">y_pos</span> <span class="o">=</span> <span class="n">x</span><span class="p">[</span><span class="o">-</span><span class="mi">1</span><span class="p">],</span> <span class="n">y</span><span class="p">[</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span>

            <span class="c1"># Velocidades en x e y</span>
            <span class="n">theta</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">radians</span><span class="p">(</span><span class="n">angle</span><span class="p">)</span>
            <span class="n">v_x</span> <span class="o">=</span> <span class="n">v0</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">cos</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span>
            <span class="n">v_y</span> <span class="o">=</span> <span class="n">v0</span> <span class="o">*</span> <span class="n">np</span><span class="o">.</span><span class="n">sin</span><span class="p">(</span><span class="n">theta</span><span class="p">)</span> <span class="o">-</span> <span class="n">g</span> <span class="o">*</span> <span class="n">t</span><span class="p">[</span><span class="n">frame</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span>

            <span class="c1"># Remover las flechas anteriores</span>
            <span class="n">vel_arrow</span><span class="o">.</span><span class="n">remove</span><span class="p">()</span>
            <span class="n">g_arrow</span><span class="o">.</span><span class="n">remove</span><span class="p">()</span>
            <span class="c1"># Dibujar las nuevas flechas con tamaños aumentados</span>
            <span class="n">vel_arrow</span> <span class="o">=</span> <span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="n">x_pos</span><span class="p">,</span> <span class="n">y_pos</span><span class="p">,</span> <span class="n">v_x</span> <span class="o">*</span> <span class="mf">0.25</span><span class="p">,</span> <span class="n">v_y</span> <span class="o">*</span> <span class="mf">0.25</span><span class="p">,</span> <span class="n">head_width</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">head_length</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">fc</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">)</span>
            <span class="n">g_arrow</span> <span class="o">=</span> <span class="n">ax</span><span class="o">.</span><span class="n">arrow</span><span class="p">(</span><span class="n">x_pos</span><span class="p">,</span> <span class="n">y_pos</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="o">-</span><span class="mi">1</span><span class="p">,</span> <span class="n">head_width</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">head_length</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">fc</span><span class="o">=</span><span class="s1">&#39;white&#39;</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s1">&#39;white&#39;</span><span class="p">)</span>

            <span class="n">vel_arrows</span><span class="p">[</span><span class="n">lines</span><span class="o">.</span><span class="n">index</span><span class="p">(</span><span class="n">line</span><span class="p">)]</span> <span class="o">=</span> <span class="n">vel_arrow</span>
            <span class="n">g_arrows</span><span class="p">[</span><span class="n">lines</span><span class="o">.</span><span class="n">index</span><span class="p">(</span><span class="n">line</span><span class="p">)]</span> <span class="o">=</span> <span class="n">g_arrow</span>

            <span class="c1"># Actualizar la posición de la partícula</span>
            <span class="n">particle</span><span class="o">.</span><span class="n">set_data</span><span class="p">(</span><span class="n">x_pos</span><span class="p">,</span> <span class="n">y_pos</span><span class="p">)</span>

    <span class="k">return</span> <span class="n">lines</span> <span class="o">+</span> <span class="n">predicted_lines</span> <span class="o">+</span> <span class="n">vel_arrows</span> <span class="o">+</span> <span class="n">g_arrows</span> <span class="o">+</span> <span class="n">particles</span>

<span class="c1"># Crear la animación</span>
<span class="n">ani</span> <span class="o">=</span> <span class="n">animation</span><span class="o">.</span><span class="n">FuncAnimation</span><span class="p">(</span><span class="n">fig</span><span class="p">,</span> <span class="n">update</span><span class="p">,</span> <span class="n">frames</span><span class="o">=</span><span class="nb">len</span><span class="p">(</span><span class="n">t</span><span class="p">),</span> <span class="n">init_func</span><span class="o">=</span><span class="n">init</span><span class="p">,</span> <span class="n">blit</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">interval</span><span class="o">=</span><span class="mi">20</span><span class="p">)</span>

<span class="c1"># Mostrar la animación en el notebook</span>
<span class="n">HTML</span><span class="p">(</span><span class="n">ani</span><span class="o">.</span><span class="n">to_html5_video</span><span class="p">())</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
    



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<video width="300" height="600" controls autoplay loop>
  <source type="video/mp4" src="data:video/mp4;base64,AAAAIGZ0eXBNNFYgAAACAE00ViBpc29taXNvMmF2YzEAAAAIZnJlZQADRTRtZGF0AAACrwYF//+r
3EXpvebZSLeWLNgg2SPu73gyNjQgLSBjb3JlIDE2NCByMzEwOCAzMWUxOWY5IC0gSC4yNjQvTVBF
Ry00IEFWQyBjb2RlYyAtIENvcHlsZWZ0IDIwMDMtMjAyMyAtIGh0dHA6Ly93d3cudmlkZW9sYW4u
b3JnL3gyNjQuaHRtbCAtIG9wdGlvbnM6IGNhYmFjPTEgcmVmPTMgZGVibG9jaz0xOjA6MCBhbmFs
eXNlPTB4MzoweDExMyBtZT1oZXggc3VibWU9NyBwc3k9MSBwc3lfcmQ9MS4wMDowLjAwIG1peGVk
X3JlZj0xIG1lX3JhbmdlPTE2IGNocm9tYV9tZT0xIHRyZWxsaXM9MSA4eDhkY3Q9MSBjcW09MCBk
ZWFkem9uZT0yMSwxMSBmYXN0X3Bza2lwPTEgY2hyb21hX3FwX29mZnNldD0tMiB0aHJlYWRzPTE5
IGxvb2thaGVhZF90aHJlYWRzPTMgc2xpY2VkX3RocmVhZHM9MCBucj0wIGRlY2ltYXRlPTEgaW50
ZXJsYWNlZD0wIGJsdXJheV9jb21wYXQ9MCBjb25zdHJhaW5lZF9pbnRyYT0wIGJmcmFtZXM9MyBi
X3B5cmFtaWQ9MiBiX2FkYXB0PTEgYl9iaWFzPTAgZGlyZWN0PTEgd2VpZ2h0Yj0xIG9wZW5fZ29w
PTAgd2VpZ2h0cD0yIGtleWludD0yNTAga2V5aW50X21pbj0yNSBzY2VuZWN1dD00MCBpbnRyYV9y
ZWZyZXNoPTAgcmNfbG9va2FoZWFkPTQwIHJjPWNyZiBtYnRyZWU9MSBjcmY9MjMuMCBxY29tcD0w
LjYwIHFwbWluPTAgcXBtYXg9NjkgcXBzdGVwPTQgaXBfcmF0aW89MS40MCBhcT0xOjEuMDAAgAAA
NZlliIQAL//+9q78yyt0fpUuHVl7s1Hy6Ely/YgwfWgAjUmhiBC02242oCQAAAMCFBT/NPDEzDMA
2fAxtDE46gcVlIY1GfM+PMhy7BZEC/1Kf5H3yYVU7fifnJf5z3/ZnNYJFl+0ZGNlMHDa7jT50UrB
VLZ7VPn4EVowLIWVoPxEqFmCiFTPyujM8AW2bNs+zWq0Zri06NrKNgHdLq70IybYKhwpq1mXBVMt
a+2qnu6sFElSI2xzp6eyfa+WFMqa0OZgaakyZ1PnF/vdKPDYhd2YJ6A2TQEqM0jxDdQeN5NfF4ze
VsRO0tjsw6voX1ntVKN1AMNQu0Exu8L/oxaqW7LPzFLXoRuviqJDU8nqgxRPYH+AVWl1+8j7XTO/
4MjwQ3ul0Nxvst0fvt4Gjkwbk49v5HSRIhjZU/ePcBre3bg1L8QfeS0eidd+Gg2O1n42w6yxZSjI
Rvm1B+CICmZWm1fYSGRzHE5jImLZ/EOKzUzSsWzk5+76gORkFhFdryyH5A61qZn2g4/EAKsGQNi+
/HcziViErkEfIyK6Grbit6cgsFvKkMoqxKajwigvOvOTTYjEvgMD7JTBbEg+MaaVu7tm8N48Jcux
+Rxw/fiR5Qn0elDkfB8jcTbz29yVYYhyQ6x2cHn4c1BAqizaBDmgf2X+cZXzceBSra2MRvavOa2r
6GUXzEgxsal6cBpsHQ4NJLBGR1kMMEdYLgDQQV0IqZ6eaFd5sTvIA9tqMfl0rCZM3QS259yXUeXp
6aphpoNqLv2JyqcNsnBt+WEz7EUHPvs06ufzjBykurN0Tf+HfjuK80jUhCFFKrnEfm4MmxsZjIb5
UAwoKnNxgWVDDQy/dCM+L/rM5eKfy91yFgF2RzsCV6Bbw3M5ocGbDZTt95NEPYHwMtUJZurp8t36
oPus8ErMdirJTZqf1tqDyZzOyvg+lsOfk0Ggx5i/vxMGKXFeGE6fgry1VZjkSz3sv5mnfgtfB2vj
+UEb7i7eny872R857r+mWkpRfVAqmnl+JKC16DF1ojsDSXWujq7w5qGzwiptebP87ysrH2df1cZx
dajByFAYcjeDrcIJrKLykd9DB1ubgE0QpCam/+IRxLpFrI+7+PhGFojLwZaKnu9HUyN0FutHPoWL
+OymG4zMSeJfSsgl2/JaO+caTrnlo6PEodEOLu2ttUaABYZn0Z7tD4HdE372H62dh7j8pduKNplk
+tW1sSj0P/P2kyUof8Tr/kEBMEL2gcSNq/Pvxq9itavjhMHMhx/PnsUQMSzcLbdw0h3ES0yciGUd
eiHse8eBH4tSGZ+P6xAX0vNs+wSpPR4TjvL+F1TeDQnOYHI57OUfsH47vHDgtSdcuLM//uIBCI2H
ESO3HWyxVk2FmKyIHBVpQTOMi8opU0oJsuSIqIJ9Y9PS8eHRQ7H+RViPFWY4/2uNNwB+CkLrWFxk
EMfaBMTbj3zJ4IFbrl83rIO5Ia1cvV0hT9iX5psIDHfca6x5LRifd4I5dOlNDSXLd+UiO9Po5b2Z
Kj0LUDX0s/9Z6aYJ27Mqgv+tOx7Yzs2Uk/lrPsfR1I9a1cMvxEAIxXT55t6/KubMI6A05x2TxJmh
inPT6kH1NhUZEM1GCLbtopZuRIW4tckVHNeYZmrnYD34fM3Tdjdvumb15EeAHVKmq4ohX+zexVKH
wO+lnljMzUhb2iQlmLSQdNb23HkLaTEM8f9b9t5U0qpIvr8pmMqCm2Te2HXp6t58kRjOdYp/M2Zw
hvFZeO0nLjrARIrKv53O61v+4iIA7mjg7trejRcZsQ8YXDBDIoXW4Wd2YS06ZU1tWxPN7F7bIOxF
+DOM6nr9zFy7d871GzwDVb3joTxSTvKT4rWbUnrLe5TXiy2ys9KaIgQP19NAw4enMzux/OPhtkGx
+76kyEbR2HhOKHgMrVmndk6jnfhMXBIy8uTg/tGlwJaT6z17Epr3ZuI95VTywcytUGZeSXLDJGRW
zcI7sWHb60kLjYtdaB2eMjQj5e5JaGyjJ2XrmCXflCN6i1ljx3DX7MZF/AKcawohJdaeGN5DPmz2
PLZszgyUjoAiAdkPRC3dGAOn6yNO8rUECQT7q/Sc8KtXwwORkdaHKV/41GtdR0SXmd3vTgLKPAym
6wnC0P8A61DallgPZ+lGO4VMvt5QeH2Q/a75DBgH7BbjcHovFoek88ESoMlN1Wp/90Xh/4Bfz+Ox
47/2SFrD0pHsMp3TW4rbmYET7jIx2+P2h0BRKXjKoHc/uuM43BsiTTIPMskTa1yxFQQ3v6O5VnGn
3gHpz5Rqidb/LTBi/X+iAm+3d1uICmDqGLSjFvWerqzwaLrNOQ83U9n3BOhWPx40F75W17xUtCoS
xB3s+RDe+eQfwZLug6kVeOi4FjF3N2e5Y5eenx3WeKcIWbKBNvdenjwr6jnRWsfGnBGAuFBUlsf7
vtp8VR2BHkWMwOEuL4LXc1w2TjwYuWD+IC64p5C1DEp2DhRmOinT/npgBSOaIG4f1LsJhhD991V3
nJ+/MGYmYtIQnF5GfZbepcHgTbnsv+/9404RUVE7UJ4rVPpHF0r+Z4deKPDgjOZwv7Op/HgtjfP0
VTRMUxtQAPCbsmGiN9YLuyGNqI8y9E0jHJntdG5BSWcpm8iEghzQaREnGffx+NOm/asqNAaIs/nv
nWZ+MzeEL+yJp2Ey7zLzmDb17m0KYWsMHkfoswgrPc+mKX0iaokpDiix8RcDZfnDrsF93VXpX69v
vpqPI/R2xa9DmcYdisOnLM8bjom8PO59KEupFBeN4UzAU547P/SKDSOYqCy2b453p5EXMBmfIkxs
L5svVQbzO/CUTfBTK4+eYvjdaHTXMR7nUw7st83iu3VnNZvgvC6d98OyUQa6SNWhu3/Yg8dhKKWh
0TXyXelD9lUc4wBcGHuj/FtD65/m4BjRIWmTkMaBahKwJy+bRBvbAfc7UWndZ+b+CnhAC21ncilP
nwcFUNW+hy3PNJwAvHDEPghd1wRrxFsMg4nj6tLZNximljek2Tmye2n733RQe64upQbupDHzPPbJ
jNuDl0Gw1537VCDkqx/5T0B+1RYIINd7jD0B8R6VJNVzTBC/tTwPFAU04td8PUvwqZTUuLDyn05B
X/Y6jtZCI8eX23q4Va0ZZnohhKBo/w9y8PUipurt1ILQCXfv2vUv24ERjwEPVs7sqy7OEJytUYnn
5jdQO4l/D6gPzh1u4nMzYSCAitiDtjWxHxPGTocOKkr8EIlKq8Aty8lWrLV18PKzD5SNU34Hb9Ec
QBJc7TejJDPgDMP9EEfzBQWG616vcO5Ysl+PIqsN2sNY/cdMgfBWnL+OAluCOA2kdGMe/f/jc6M5
wK+7J5ALiTDLkRMb6hz+yYB24vZTpQcCd3v66kUU1q7d+PMToSnIHp6cKjRf6vT2e/CMXpgqk/pD
/jffxx8UgxkGstb28XPIty7yFeprHJ8a5OGJk3s6zfyPVpIuY/MTHccw1omCHH0Os17UDM3kCWHe
8itn4zf4uu8c2Iyf4lh5u++L+7+lUfyJ0Iyzv9qEcK4QKcNEMP+zAztW1qFX/twrYcWvEDbTlfzz
TjPaR2nVEQ0+oq1OMljcpikl9BiZa58XXLIl8PL1u2W37ukFuHdITB5LUbC6KmwxlakGUB+x83Cu
Oe4EjfC90FGEFL8xKDIvbed4nO94NSnVHCpoluQihOuzUIGs4g2go7UkhcWa1D28Oq+pbVJUFbhB
0VbiE7AIOirTwRuJF069PayERJrfLirBIyjjwcOfsWRCw92EJvRPb5ut6RZw8RyJVJeZsFQWChwf
IGDs0Fj9p1NXnLyw6cfABrh1QXtokKRieKQOk5/qvS3vxdKB6eUi/Hs1gew6zo8QJb7eOw372dLs
Gt3LxwO49CwEhjRzHdpX92CELgcmwr1IzvVRkhQfuEVxMI0tj/CX25Mr4K1NmY6Ld7b2XV4EmM7d
EnUc+c8NONMRmsyY3lD2i9kyJAwqIn0ub1bfV7wBr8GHmlRIwryxVrAzgDVqP3saC/K6pRlZTFEp
W9wCtu34ef7JOecnIsYVh0v3wlLeYtcmvp3XKVnoY5We/ZxTtIdpAokiIoNliut2JgfMIKAptW6t
RBfRAnjOfmMMI5wRUifO720maBuCjQZC+vzalKWt4D+6BrjXtRkCANhr0kqW/lONq9UDHRSaVAAe
P/p6wIRGodtLa0jSSDWnSlWX9MnfPHNcg+Q3c6PiGSAl2sJBhnkHNh5gNq6+dQ/kelRX6+JxP/QI
LCE0U1UObntVTt3P/3jLg6Ua+JoBl4dfKVatIp62aDHae2Q47xvASesEPYp6JgzNKOqtxw8K0u5a
R2T/2W8/u2cJW0MLDM4SBffwYCJhII3DogF49q5zmypNunYR3QjODWu7+9x30d/wMOpYCIA2K2jo
pg2jNDmBTSRpGVfxLNkBLcNHv21ajQy0HqK3lYnULwZgAdgDH/w1KFh2TE0cBysuPiT5W+///tM6
7MlMclSqeysEYdXw6Kn7mTyL5zji46yw3lqKvUlxyXE+chxPStxsbT2BHnOLDnUNuQtWCXxFmuBz
QSLBYdPkX5dB1JEVU5PsKWG3K5N5f7cNGivvOheuI2dy94pikxSY00gkoFCLdR8p3mBfjJlhJOw+
pGUdNwwfCqoTyF5kSI09TQz3/s2mCFtwS1rSdypRVWFJT0KQUZxug8YOjAHP1mGHfaZGvsiT8nUX
eqxRQ/0iABrYbd5H/lTQxp91jJKvCskDHFSo+6r7Ct9HFchbXOLDgY9Pf4c5aKE/3oFK6vqSggcT
w/1ajWCSjwYxYP/ZoaJshwEg+XK7GFdeyG3njVFyCp8T1mjU4XU0oCnIqq1x2niKk52cqqjIZEnU
5a2dOiXf7BjG2i0Vv4xcIQG6UYh8xOFYKAj9ZZqPBIS1/6hQ2NtSHE1iYljLQo854SOSjRDgnC9n
j8iFy8A4AfGMk7kTG9+3pj0AUb5at3D/SqP0waW6hnCY/Bbm8extmunGKIFa47yMbK7p5Yr+7/EK
YaSX1Apd7AFmFEFPed7f5mhYbi+H4ziRXP+/59lxVY5zE/cqOoRDKe6nrbQXru1Iojh+JY2gSHks
XrAwdWxVyIi7E/oJczDjI1wK5R6lIM3jE568rU7M2NkUBo8Y7+eCHf27xmC+sE3AJHZKXAEumnKO
/gh5AcnqiJ09R80LAVQXGzjESxwgfXuGiqN+Xz0YC9s4kuAulOsTBsnulT7/hYDLzHo7iR7SxxHL
zcLfQy8t6t9TAcLDwCP99Woaj6q30aqtszo1v7jmYHc1CdQAu32bMMhnLFZrVkoCVCbX1EBEjYvQ
KFg2pFTpJ7XyQcIhbODjMmCJamPlw+kjQmZ93mTKhGig/yAXJvBZ7X8fRx17Cobg547+Vjxju7al
4Y7Gk04ygRZk50u/BM116cbYhLAQN15M650xrl1ybiVUyzkjwOA6vvX8x5kKP3CKrF2S7h536oov
MKcfyZkZOgN05r1zHBgasn8pZ/HHxklqhoGfHfmrjDwVaCP3XGmju0mVcYBFmnWOllmPgz8HUhB2
rhTO15o9o6tx/1UjeTPhgzIBnW/dayhoKFLv/HFyDepiGA7LgXsTRZiWB/f8lzHR0ckbmv6Z1Vl2
6F8z7zYtE+A4nhfo+iOAjKXy5vbrtUy+KjJV/n4uFeNF6VzaH9oP/nQmdHIaTtaKYdjswksDK7nL
jqA4G2i/34eNSvYkWlZny/LdsbkRWRgeJFRVxA6LhS9JxrXNbiqeAXL2Q4E1ePyGyL1qQ4Kj9mjP
b/6ykKBcz7mSOdayZW+KPXZBlg3O6OBXF9EPaIE8qkuunGC22hiiXQ/YaIVlGUKTTR2Uuq7Y2jmB
fXkYwQoQ/IJN472W/YN6sjo+vlrkOwIdvaOsrxjdE4bYW4yJIyx5wpldoXsufnmysrEmZPzAZl6M
q1gkMyuETLdBheXh43a7trfbudWUw1+PKd51thqEnRdDdAyWAotbVq2f1rHP8qcr2wxXQwpU5qen
tSawRWtqSRfHEVyPo1rR+Ub9KMztiXhDWhEyZWn0eo4gGJM/cB/7+d3jmi/mCdN5H3XsqlIO5r+o
TN1rEx120WIfnUOmepIIG/Ra15Zl7qrQAQ4sn0r0xIeI8QRvzkiqS0L/3SWEl5Uy0j8+n/PJ7mM8
FMxg6armVi9B9HK8hEtddjUEf3SvvEorB9lMjPnCtd28/AyVsMdCuwzn2/03DHIUnE4/q4n+WYG+
dsZSnryh6qfFOCIenC11d2qVgD+9T8PvvrPBd6rxZvpFeAir9Vp85VDbwAgAAdl7hLNvYacZFjp7
CHzVjhHvD3dCVKCXXyxlAXI4sVHYClIsDswkfSG4LZBoc4gRsiRF/PZNa6ZFORbqdj4DfUHTTlju
RBYbmsbiCnh0m6rdA00Oy8GJS/BF/a19o/cj7tZwUrJt5V60ANk/UJs1rmDE0rtN5/EBvFS3MbJf
PR8yKHx6ZTInASSwwGXV1I3S49hMcFEPi7bEKg06pzR9qWJx/SqsE5CGCTHCq4kdoia5mWRGtIk2
KtB6QZ/Vq19TrSCru9vMXOUpJiuBtngEyheO4uRf2vkG0m8BJRnD4iQbft98Lgn2R2L2o1vm7ZES
v3/bKdVipQvJ8tiJ3dKmSsubUDCqHvv1FYnOGcckVrIOroZu8T9nn7NLkvbNgSvCL2uVeSavJLz1
hU46AdBGcnKamztru/YNGUtz6yz7gji0L/O8+TtK0Cz5zIYGKIPsD6VYO6oHTILI3aBnEFI9bqw1
0PVqfDPSEYRSyDMPrA3jXMa4j1L19QPSdbb1IthAMGKe7jaFufDKbrwCDyLYBZSKzNaTwCQGV3hz
EgNNcgePoBb6rft/HWohbVIH/snBOCLc9S4vUex3VnfXxV6HEGTEWNbHLWjIunCzMsbo2cxQtK14
olgOZRlK/yf5LAaqB2VkIncekgdka8T5h36S0TmadnfefqFHLFag9PLLUTCkyZNiw5uI+KqYzn/s
lMBxaLAPUeEi2C7Bckz60fpKlk5ivnZeQRAgC9DxKXSJQfNvA7U0i7+3BO4TQN0dvWXfoS61KTI6
7UU9t+nEG5uNk0toGSwrqrvs9beP24XqfF/db1Z5kePxGBy1eICR8FPkLVFAhxVplUl3QsmE8DB8
lO232Rkw4qSL5DQR4PEUY4Y9m61Y++jLOnkGbV5FRH/1ddg8qRSUgKsj5uuzChEDKRaFY7QG+4gx
Ofa/sFKfFEE4kD8E5S9eUlRJqJLpnezTlwKsW5GV/802qQpNFB8ccsX09ZROK3DpFvLauimr+ZEl
yHttjYBfNPz0FPMH70nx4mJ80zkJHehsfu1FG1HSPFSMtXX1yq3f21/xr4F5EV9GXHeQKd5KUKuW
DmypB9qn4gwd4hlEGs/0E7jUTDDiUmHjFz2pm5wfQOcyXP1rGLzzLaCYB43FRTI4rurpmI8fVH2d
9Qicf+etmwZ3Si6xMA4pY7l2DiOHpJ8yLKOpMQKcaiJQaNW2q1c3OLOmtT2EHiXpe3zGoQGbxMqy
WI4wqtnBwpdoh+gX/iMsCpiV4cmArRjGuynTw9br3rXB/YsN59A4oaOOKN81t/8d4hYSrMJh0+js
yTaKgvCMeJx+PBIe/SfzKsYqjbOQH9IP35tDh5AuSgYo0KTD785TCWEv/NquagYB8NO3mGnf+UeF
101P//CJ4OyDpI7u6Hxqseq0ArX+pVL/7ueTDLPTLpJaQXluPWBM7g0ONbVupeuJIFTkK1Fqw5mS
Ivj6mdEWUgdGV+aMP8jPitCoi+Xn5DZGGHOdwBkvX1F9JjVlJHcq7OaEK4fHO+OvP5kczfX1q1pF
/+AnDt1pUz6e5P8Vwas6FQ2gm4Zcl/BnwhWXG37GzJJ7yWwjYAVOCkPLTWVsV4F0Mmm+JCLEVJYz
4xZGqhWIWCFcE4jTXnLUEejTSQ26sy/hldyO8+yy4OfXwoTL/C6GvE2QMnAlfHQ9QJqAnoxQFtTb
G6fNJFsYBXRPpBqXfZOLeglWTePpBEth8JIpdDuxiH3iJlIvXSXfSV0M3Qn45aQdzDZPG217KM9o
wyY7dbbdgnLE25zRZbxeKs3MXOwxijqtiLymU1eATh/LGdBXok/IDMelr8inq60abRfjNQh5+p6T
46kBPFJzpbOuHYJZxoutd2bO8maLOtnZJDTttGljaMp3mNcWsnt6R1hJ3yzrBtehP1UJiF2+9DMV
W9aI+Scoy90l6oZmk4ltq9wg/KjK1ownbjPq4HFgIVmIH1c5Wa/mU+jYMQ65iSy0Ch5+PStq9Eml
ywcR6TQm4Z8/JL2oMGsofKMOg3XGDr4dgPMba/LxECQL75hSLIkEPiWiDwhuCs26p443GVL/Qmfu
lZUpKt+xZPVINDqC5b5MHh7Lm1T0unQ5u84lS/7suXehdh7rRal3T37Wc78e5KKkTw7WaV8DQtqY
ECvYTmw7F9GTRHqn9Y7a4eqzLdRsymCEQX2HiRZpHRYetVFEH3EK3HZIVsNNLx7aKmqfOERJV3an
d1wEixcI1BpPMOpz3cMFkFT7l4dBkHRFcRXHWHks4r8z3MP2/6TT9P0DeJZh9sxadUg51i11tygT
F7pf1aNmHPSxUejLrDja2G1NHj17CP1O5QlVhRGBeAtiiPEd/escMxQutcM/6c1i9P23zuBtA/iH
w/yaSa/o50ATrBU5wspEiv7L7f/fuJjTvtZt6GKPSc6D2KgctSN2pffOJS12IEfi+UleYo+9PHB3
fwRlSUnj/UXmKi9Nq22Zjr0ZNrh6VKxpI3ZljRzcdTquhqVysFyCMIJqIc6kEuzVf6SnfdhVJTxa
epWarc01i8Qfcj10eiz3gLWyhaelEBqlRV3TTpY78ZMwHO2e8Mb64TJc/X/r2WVPjb9nKOR47A59
EGHRE+/kMCPplUnN7IY+59Se14JSHNNlVgHtcu4eavRTt+LsFdKDbGh3kmSxQ+/zOOJ9Qs3nz6/L
be/IlPRYC+kAnUrZcwOXC/BgdN6LZwGNpSAQOLJIXs3MuZQPtPrrsk80Shg5gbmqO7X9s3v2cNux
W6/iYh9JtFSwRfRiQcxNGj6jjWMWyhbWt6QbtZ60SPSpeDIwCvx8rXKbWsvf8MaW7GbZCbtLvhVN
qiMiZYLWK84vs6+YajT0iWZmmwnbeV91pQVwVgAZfvUZm3qc6Z21vyXbxZkfagT78VYznR7Tjqax
5QlpzqywxH3DpuHZvgDpx4ALXbjMUOxnxQEv8L5J4E2tfVfMb6E2xrPOMk2R7DGGtD+ymNZAnG0/
Xgb8BMLJEX70quSblJUcvxJcH3L5D8pQhRsJILzpxi/ZPhRUSCxKKlAuA++VKps14Iiny/9mnZMa
nAPp8blkGq0X+O27t09UEMy+LlFHE7bpSqsBVZozSZIs01HeXpVHWTmjPXRYbayauT2GHuS2CHEP
s45zZmRh2o87hp/Ytjj5h09DKM4AvsnYfLGUTigO+OwD8bfrHvG3bbZO9BNpHoR36VWjTL3hrrcy
fJu0wJVXZKS1noi7yaFbIQlLPY/OzstXTNa5JhE9ZuN9EhXiPgU/gABGwNw6WVpBI15EIVDIWUxP
VYEbpukuBaIqHTASupRKcbBu7MHKFPrUZqvQGGulFTG4YDm5e+MYSwxBA7qtXRg0CIYqmh6szazP
RK2NkBpqtnQoK6VgTaKaeg+1tzLPXaravjfPuDaUULRME8J/OQYkFIKZ9iE6ITy8GaYTltpL0m1p
xQYlzB3LMUDKK89Fvvb0ZORhbtxqG4adGUkdLuQQ9uIG38xLcxwd6ArEYN6zS9kCGktu8ZhJU9Pz
PDe2/DfeyArbHoJtuGHa/tdckzPBcc9i2EHyRvHQWZFumwjR1DTVm+b3kZv9WFg/tO/u9oe1xd3z
B4HSasgzo9XJLIBLaPdKWUGGv0+zSNsqZdASMDpEi1YgdV/n3bs9IWR+oXMget8LtOhLLArjANs1
kIyzQUPfDSRlT2ZMX1p7Ntk751/tqXUbPhQDP89Z1+JWLqNeHcen57sLcC+PGYgDSIheh1MY344Y
2UWr8JHZNjtPbxB9KHPpvA0a6Al3jbRhmPdyLLzn6f9AYj7RMzLkrOgA53hJrVX+pd3/wThRZ495
jKtAEjvs/Hca0usAr5m0BQUC+wd+XwQ+0k3ymQh1GYF9BRNWLr+ur3twApjmOhhKYPY4xmD6gWO7
E2XYzJ/mvPUvmoXkJ6/cwsc4jHDz5jkcx3lv/2Pu/LSGqlIyV81y8uDrhApA7LVh42A1XIM7KtEC
l/s1i5dRSErZRXZgr4/O/zfqNj0GFgyhzsvdWATMBZFwmKmv/vMP5Yc9UgdX5Egg6kXqX1TdxbJ/
lo6X9P378COZFzL4REuQvi2j4467JqUicbrVuxRRavel7tskbGlHGR0byX1a8yHF/WWoP3XQ19uj
4Jor5Mjtrn+cw06444rX17mibmOkmQVrjhLTzrjyD4y4hI3P3FnoDHICkT7BtSNsu90OwUAKoNwr
71E9tfmfe0IUvllgX2GQDs4+lkDVtkLbcSVD0mNHG6KxW0AxkrssX6CPajYPDZ+WnoVfKFkkGeQc
S7DMUdeZAOe9P5UDJw2zaQ1Jr72eDcqdPdeVU2NVHEZVXGoff2Zw+er7OGIbzVqOYA5x6hbqqhSc
0hw95WG7lXdU+EZbt85+ExsIuKGTp/QAhq4fxGkUeZiOTMZp7b0vEPWcxUiK/fu/vLErpOaXXkhT
BoxTKGBpR7gMjkl6T/hIiOFBPkXq1IjKYBHaK8FCRrGppHj5vtrBRyuXzn9GcXM9NLBwlXPv21iN
qCbnk6K91bcx+a+IpIogfCpEX2M9ktxO5CKSVqGohRWtoRUxCM7RQbEc31kVkiORsl3/Za4GZ2LE
NsyCgs9y9EB+W+ri8IMt1I4jpUMDoQDw7GX2DcXf7nOkFoYmnnKo1jQ8w23hDt61q8F3oHCMbDyE
a/jLMHGZ8Jx+YoVELXbAxTtGTct/Lcrh/KyVFB8MRUohpGZpB5hhn12j+PpkNCFevI9AZDxsiGpD
7OZ3cyMCE5MHl8kRqEkLsyHhTDk/dQb1TIWVMhADYJikf2KpCCp8SDOg/HKXmXgUsxGxeFnGPBVi
VcSq0e13CtLOveh8PvgHJOZ2LBPPUW95gYWTEYrrq9V5BtGGb5/y2rciBKRfAwVlswBGfF0TgIw8
SwYwKGi+5iTpfz/scfcJ8JImRoWG9Umsy95zwO83LsGe2j6uG5VN2vithip1cUxjEItPZu+j6hfE
Kb1ig3qW0lfkh0DAAzfHiS+TaCvF8UXvcjmU+sER5x0MKBAa7li3cv/keWkXgQ07TsZFrauw94Us
MTdLEYa/HWSZhvl2OUkg69qcWFCeWHipwceoV5DOgdNQpYolHYvt7pfRpVDwuujhLOZW6DAuqwWv
4gfCevCFKuxovQ8JwtTT7qa/2okYw7GeOn8GY9gniBf1+FSaWAUNaw0FrZAryNvSDaoY1PcSssRa
GbrX2Y5alw1jEppP4ojGwfWCQIFe9M2xe4t/K7vThbBf0ADv1p5c4isRb595KfJ7T/XiRY2mgSo5
4pQL6zfjU0bVN6gesVJDkZxJzBR71fKeK6mQzVRpzq+ry5dJ2CDQyCxkLk0/ItrLKmhAcGQZlLwB
dt5v0Beq92FUIWFxjECaKCyrRuWwZqS5F20rEJcxYrW1gEYjzHqtodLxjnu7ySE6KETMUj1w1qsn
Uul7gyIEVp0dBOkFpaAOA+amFluQnOyOID7yeXJ61XPEXu056VWn0aoynn+ANeq+gTdKiKCwKyHw
1c7+iS7XkH2NY33NrDb5tGiVyLPZ3bZnJ/hqOdEeSPQbuf2UphGN7QiaKUOnBiK5fCW06Y4zB6MR
L4fffuUp5lg6AmoxYc1RVoy0lE3lnI4SJJ38J/LxJUeVJuA3IOtl3Sw6NjIblwIK7FwIvvwZJB8L
bhkYJU3gYhbHyshpmthdLeyjRSbCLu+jxkyB8ohE9PdQkjX+iQsOY+Mplz+ly8w+mfyRZ/X+8YYy
Q59G0LJMfSDb9x9b7jFm6fHe/9X/YvzI0AYsMUrM5ViS0KbS3+LZIj4H+PEnxJHpmT8cZeM9/Fj6
wKQTZSyyZu9MbdRA3ucHDJGzDEZHxW/IOW4cMcAtPcQO2rTydbbSP506EF0ryslkR31jgFZLtwat
7bckIWQFsqpjxaABdK+kadLKJbwkA0Gdbjjju4rUVmDS5ZtmkCXcxyeUBlRr7BUwMCuVfbjaMVAg
rxReQAXTTu6MBJ/mB3D4e6KmOh/QvUV4MH03vWgZIULwUr9S+3+PrU/QqvAQuXu5bcM5pAqOlSQl
s8bn/lWCnrQx+7+zah08kfdlnsUdQk4RpGCghircKD+bzVaxEaLGJ4Q653z4UAFCkpiTPX1gIDvg
hYX55k+I9P86vXUc5cHBRJ6VnWJbhlgNdIwSwCn7hbBCY4GFiDP73foAwF896l9aQTA6kHgO2yEP
e71lsRdYHNSkKpQ0LPreI15j4bLtv8mIkFhHzF6vyhN1ORWGlJuklyzx35ezuJUpac+KSlH2LRFD
p8IT9G3odAboslA06qJp6cB5ZSHG6wWl/MwdzvAra+Z+p/zIDiwiuWZOP43Q8wV1mw9+kYfHvEhI
j68BKAb89QGe5aLaqLwldaPYLkbfAnm0AuuzziEXHCYv09/+dcU+JxYtkmJ1hQirtxCqfXx3TZsB
db3j6//LIyIM/2+25v+3Ld2X4m/E193+4cqJX6bt2QAtoNW4o5PpLbScx0X+k4QOMs40mz8S7QXj
8OaonivBJDpOu9n7pYUzKPhyKI40qyIlSNxw6/mfrtYu3lT4zXVPVvUj3L3fBpF0i4MA9L62gLFF
vbiS2Y7MB4la3Vh6GR80pYvvB4NkrXSpYGGWYfqqB+ee0in/lv5n1OX/4KhOeeT0QZCypEbZ+bZt
WLawEm1OQUYPF32A94p5zvwvP/M0D18vYdV5kEQptjX1W9/yuKYCR3T6fK2yBsDlBF1/r73J1zb5
i3OPBI3e8bI5R9Jydtg4xDd3INytG566nGTNw09LsHGLSkjdDqJOxwbz6yRUT2JkgLy0S/osJtnd
HeQS2E1sMcYZFTEV0KqfE0JD+0k9nMe+lMpqWY1XzMJpAqKq7lEpbPVLDSqRSsZubcVjkRRCykvE
kIeOrfdsqsHh9Ep4n5SpeH9dELSQWUhBJ2uuI1i9Ojqyfn/l9HSY+Jkoe9Ss11QrTsIP5/2QDdHf
Y0b6sj+fed20YNB8UOAtMss34rZ0BLnZ8TGWO5pCpALCq//b2LXGr2IPYmePqt0zzlCU501UYKRU
YfPFDr+e33XMp9VP13qPhGY3weUzIX9Us6hZxlhkGo/IQ7I0d8v4MNrFMbWInM4Fep4KidZ4kw/x
qbgvSgYWbF18pMn3DfHtZXiYC6y+mxi4AQBHS+EyBJGBL9vsTv1lYXGH2dld6W6VAAKpfhwMRCvL
eFHwpNlFNRchWxws0rid+fQAAD5fdICDHCihl1474DUDXn3eRjO9vzXHgA2A1rl+dOAVaGRw7uWl
6fBrPcJrXA+6AQT9sc9hGUR71oa8wMk+BmMPBXzbe2GOp8goTdtTn4BMk2xEGyiYtBcYqInfbAmK
uq6qg/gnnC4wwFWc1mwnqPRp+jJ8/rXcyOxKkPz/7hU01bo0E3QcFtDgaUBSsajbfbMPK6mpsS1z
T0m7Sg6lR6ISsDU1M2Yx+RMIewlYrFhkUgVAHXTQ15GMCNrR7u+aRD4bvcdVULcSlIfIe9MHhRwV
BPMRyza+EtKI6OGX16AgXLyIcSCu76J2+EqIPBHnL05Y0b1X4qggJOhryBaOceKmyywz5Hg/PXXE
uKWpwTnQBeSmTgbGSSBOASC7TeA63TkOJVntTye74KTBZFCWwGpIHwVZ9fOoCTV3GeygqEU4MixG
8ds6YyKglrqrNc88gnZGjjeO1siQ2NzUdl0oIwe+0Bvy0rxkelXw4giaS4WLbOGk65W8zWKBwJVc
ze3f5c7bo85JfD2+sFH3LU2pzn8wB6DzU/R3ayLA4le1idwZpzvW73WNTJp3LEscadVyg6Du1nd+
30oMLNpfQHQ7pNoZOwH5ca/tVQdd2JYTEzFX2zrL9AL2hZwQVCRORhTaUwHp6xwhxdxFZom/SMvV
L3fKw1eSmaY6/LH2f4EHebLxm2PdIh0N0poUujwjs6ejaGXzPpO7aGUbHp4YKqNIBm0EQfyhYGER
ukL9G3z/6RrSYKczF75Uuxp4xZ/YjopluLkoHIbZHAuf6UV0uXAkELnNQT0EJSF9TzlsOvxdd+YJ
kBP+fN0TQxXY4hIdpmk/bo8d5iA7qJo9e+9+ju0ET5d4l0HCQadkURSjfXIT4wRRvZDIhOYrdJio
J0f0Xdb3S4KJfpuhJ11UtdzSIYzrmO5pu1Yt9/4/s4vuBP8dgghDDpPwoIO79W+I7vqG4uryQk8e
QdcTH8dcrAaA6l8hwU5o8baq2DL1peXChQR6Qr7Ez1aOfk9DDnK1HxapaTkedS+mN4NZqbDVH7Z4
R0shkcvzm8eL4Cp1ruEGz6HlND1QGHKnKuwhiTxECzZHDOOtpmSHo6BvAJBT87+GYUQ2aa3OE8KG
aZWIE9Npcr8MThd6TAJvgX4h+imNBE+SiL2a/9Q7TErk/bpXHpzoMe719LR9GOPvWXVbCY8fjFWg
vThRkNETmSI9jcCcNhty2vE6ZQoPvds3OUbHYNdD3fSrJpdODd73b5kfP/u79qGlYXzEpuCVYjya
y7PmIIwOmJzm7tTkXgR0eMHwELZb0tfP0m4G+lrwBUoygfYL2Cdc+bjsE8fw07Wen2mPUwSehiDF
2k2FYjvx2VpRgBvUAY9eby4qjwa4AJoD91GlLoh0B9b9K3YNDvHjaSkW9wZ9TvDWt4avNFTgNyP5
8GXmp8yJm+szo5YgruK8gpIUihk1s2fplfpQ2fyJ/L2hqw/MB4kfD0ufi8OyO6syzO4gBPYnqoY3
yGpOhvc5QRG7hx/XFJ0LLVIEWad2zZVZTP2obBHDCz4+CVo8SahOYFaFsW5Gc6cYKOI3TxvsCIpb
ksAESrlWHw6eDEkj/1Z6ihaDLqzfNRdhCKSxIIZCYP4ThXx+D54dGaHmrzf34/0PaBOG0UnnQUn7
JVW4AqaCLlY3Ehpr8A7raAo5hN72bU1y6SM2R1xTA7aCdyjtyInxMcHTZWnDpHetDOKDpUcCNn1a
DVw5BvtH0sfRWn3iLh5IbxPJqIPK00DXSzQ9RRSEyxIwnVgsxgYripcbx5DRKmaBURQXCzU5j/dG
mOoGD0FmhH/mVaNc/XaEF0pESYfsIcWzf0pDbzYXe8FyNoCX3sQiQN8cH897zxsM6tLfq1ZPT9Nu
CwCjLfHop6TMxcNcZBAMjG9QsUeiLFL+xMBShIW4tLNgAFw4GDAW64Lit5PUIcjxoYOJ5H2fvDIl
sTTC7tCKwB6WCldNcbRVCU2E5v0bKd+jSyTERl1/H1kCgE24y6e2zL+mX602gPUiKNZuWxBK2Md+
z7JdqmiLZvbgZqNkfsfx7Qu3zkCWhnbgyH/GOU8IcYzdI9+7boFFHcnTQzmJJNttzFb6c0zt4xR8
Bpu7mzvuhN/j53pZMC84Pmld5ys1eEj5N8kIUzfth3m7MvX6UXm3Iw3OAY/kqh9gC1Q3kimYUKog
m0f7WM2dLEZZBo6bg78r4iJn12OVz0pX8tMgJ2ipNWRXtrlGSpbOfZgHgJqZRJUm9HuBDlWTjTvL
S08rWg4mKtCsQ3Ao4sAPnI2AMajvE0ABXqS+NF4W29raKJfqh3m5aHDnO6pXctAQtMqnxFSi5R4s
AQ8pAfvQFfsBotlv9lQUprTTXnerh2AGrHk/Ni/9EyS3gZOiK9Lk/JbDqYoUZFDcj9mqhG4zCiFp
7wKV8OlrettXjuZ2iwFoQPfMCzm52SbzXq7kv5ZKHD91trr17zy0KM2RG3SLl3HqZflvExHEUb8C
ZrPYOR0k8eXW4zF8RQh2odVM+0qHbN51khMFtIQzj9MpwY4qhjba8cOeOVa+NPNuIg2d6V7G5QNY
yy3OZWlhiOQ23sxizYlLDhMpYafpL7wzX92zGYNwNHkRCVmjcOZ1VQen9vOW4d6yPeEpS9V20ctw
roVYxXwqGr61ck/WXxORpiXMQf0VEioHBI0WrIYpWk8XqGvmd/cO5L60NpDJuqK90ZLNBbaN+amM
HUQVNRiwUgUdHXLyBbGh1iDBMgVWW+pGoRZAJjHWijASpPV451rTIn+FfSs9LvUms7cvhxNeO6/C
v7Q/045LjHo67XhIhv9dgSKwiwkNkLvtbVMtHHvHWrmtsGQJrqmaJKiUIAD7CIIM/bWacxlQ+YQQ
a83YHXVjUvIRXAt97l5F1uriw7By5W5LkjB7kR6hUnjiZrK8p99MnRzTkrK0S2gDbceP5hhzb42x
/yQHWjT3HLQOROTiCjE434Oui1ORlnLUMcbIAy8oXrxozTgveAXG4hlf3WVNnQRvDe6QClEzF61X
PrwVXH/hIkfFFMUWe1Wr2SWjMSlojK+QFHNe7P+EqiaYyXGiWNmJfvHzRNoO+WN2/zjQWjfNiNZf
1VUwnPA1IhaBYQZb4Irx6BCeV+UfjJOta1iNJdYuit/Rn3JXeKukhfMLVy35rAfrKlagnOFfuVZF
xjPxyCgczw74XSe6uDHZ2MZRluC+Jk4O5nB9r5zDph7bohGdIbmvEZG5Dz6UzDzqFerrAQURJxGq
GvM4M+tXBc1qQPde7jUvmL5/7P6oGT800YJWjQ9Ib2XPO5NvW3yI/60pHU7LxHt7DKEYeZu/qB1q
XuELKRJRD0kxQPJ3AofvlJ3nxJ932k8VZvVJctjOzHvhFq+BUzV71VgCJ+n9FTFP978kDnLU3yEc
pLX4/jD9ocYKENPEwarX1Ske2zfO3UjtzWjdhLL517bn41XzVAyJe3TJRHz7CVJti6qaREUCtTwk
ZLkShYm9ORv5RXzSthYUUGBfFYYJ0phHkW2ekANI05/QfUKwX3u01mdCVZ3ClhcQUGTLF4EjnfZa
kUY7qVUgulPiOAqpyJmDj7CLuLaSk/2D63xxTUHIMneGcCJDsWjKeAYf7bUlCIWcz4X5TZH6zeI3
Jgq0kI0oB8BDUAh2U3zmShT0556t68Ykk18NuvpgioYseh3m7Me2ghQTb/JESnYCvlmSVlCingSx
7QJQdUYBhI8/SYZNNYWmWu5wvx58tQOiFc6jzb0hpcWxvsEyIpbKchjHuDoY5rVcREAGfVOnW6au
V2ad4My8Um1RkUYiPuWL/lw1gdte+BdxMVVsEogFn3hwyRsPxz9JfQVscq2AKeyd7dnJZwWeUihk
GY0ctQ1xWRovG2byNqcMBnZK2Q9HWaGv0BMohFPtVqpllvJL5HhW1m3IwRTV1//krl/S4Eq0b2I1
ak7iJDxybhxs/oXTiMobcOmyXrf4Je7VXBQ7mO3AO49l3STOzTVai3lcdeQBhsXgJMcEpk1chsz4
Kd35/aRqvxLYT4w7IO8BfH1nE8TbqXpGcHDh12Q3KyQmitMKWQhVLC7j/j/4DBXupG0z/236UUfK
BNLKDzu8NusOhc6moBo/9NBnZoq26uQuU7dDqNW6VmgRFtTLolXlmgntq2xgGpxHWPwEgbqCy6bV
LQkqdzabYe+GN5RD2yQemlPa4bAnGDw/uaA0OjkUgDfbWF3s8e2Jn+IgT7M4XbFaS7X2spCfnwyv
yr6HDs89K3MqjX34u2ghMubqc4SPtsujCiO4UEbiKpSmi+yfy3NmrMT0u/d3JEweprwhDqT90NFu
Cn0H0y7ac41Kcmpdy+UTYR6HAmxOk2F/bSwvb5qEL7USN8rRg+9SlDKY5MMnrEu/0r0nq50qtmI+
8gSMe6jUaoBZXjK+cM+lod1r3jih8SxtI2ihmlWJDdzki+LDWpOm+CkWsI3jM3bgSD6c81r6r+C+
eXpWji5ON+pH/TuIHY9WMmoXwTutT6MvJH542q+oQBb5P8U+qqwtOE/dZxq+Tu/ez1InU69yKvR3
P+qRT1Y+15V4isB6L+MPeBs6ET6ca1rSnwJK6lB5Jc2yMbkwn5OJFde776/0CBbGXzpsCWQKar/N
egrj+fQ6mztc9Xulh15U1hud2bEcgD9X+QJEO+jhr2seuj7+a/9WR7WOlTmqdKRSLy483IB2kDPa
bNaGfXE0PcYBOocsOBjuWbudGslJijHs8A0VPAs83gufksah2eC10hBA1h1oukcodWbrdYYmcTsr
3VvAyJtwyMFhr9c7RygqxK/as4dHFLkrFJ5FACWaSRbXAI44AAADAAAJKQAACYtBmiRsQr/+OEAA
eVnQcB+jVPG/0OU6H3BxPviTvFe2qwXcGzNAUVPd1NUdnV5uKzvch1J5GDaBkXYdbyJiF7o10HjW
sumNuLmIZp4WVeAJSWgs3lfsMHGf5hjJXDeiCswnwqBZSk93Ov3gA3pT3T6jGB8WMTocsnR3w2AV
VDXfMQgbubWV/P4rnZpZ83xYS1/B0CfGyB321fNgZAQE9dZ8Mf+PzWHGJVCPQHCqdF/vyEkqbIwv
/Ny2VEAcnfiXO3S8awtA40oFv9q+AfUiHktK6mLIKFSBIjVOYvcDTVJIRqAnyesdnKRCmSle+F5N
4zCwJTQuExvoQi4Y7AxpA7yFiz89FYi/B4jQeSS2zKCjJFJojUsHkF8+7Ks+V95goD6TKJGdZimB
UQIDOLuW+AZOo/V9N/LvA2ciwW8VPIvsB8HOZN0sKNkPMsP7cYzKny895pmTLsURW9suaWgG2hl5
vUklR/D0AH2wYV310ktA7stvTZvgMw/QCnMtsLeShr4U/wV9fKJUDrUfmeNfpDnqb2mh38KC9w3M
tBRkOEEst1L9BkAPnm3pu2MsW7DSuSyxfrHyrpYzB5ExKgc4c9tGohHD0b9AyIDReIADGJTTxSGi
5rz625yZi0+uLnhC2rTM/XLcviQeUMlaXWCmT40KMfCtZSREmiETbFxEMX12rbENZpDVCCqHs9BI
p3XyVfJqTq1MV7SJ+rn6Y27jaYfs2uqzHfYKMFENS+6R9xsbqbzHCnW8sRGplBzrlWBNtFOSqc68
49cOVbPlP6LLgPdK1FfDglHliuxtcGVclgRaIb1m81/OZV7cWvs/wdgusmqtgO51w2KhqIJNzjSE
ssceyR8p6MNx5c+u//AE7AIiBIDaTQm8Uks3yw1WllMOX8RiB1kDh+HoYHgTWKvKbK1jMy+S4Fpt
JHVqzZMFdz7pEtnztfqbWySBxgWCPVpBo5zB4HD2kz6FokdoSKAzRgGluE7Cq+ptyDIGGxapOMbX
st0aL8A6nydD4ZXRHXfCZV9pEIZt62VQMR9KU8IpUxzmHUz5KL3zTMaV8fTElyvm6jfcF3ntyM0b
4UCiP5pqI3Lbl9CVUBHd1nviqOoe1gWeJSJ3tpreURGy3ZOgdDk/Etgjz4458IGyZKesSk/Git3y
yQAVbayGEZaWoX8z8zWs9teV3Lq7G1OBWd1oBacGlVlENOiNR2QShiq98wUebRDjloTIQYDtAR2d
aS4csqHv5aOC1azvLNksslaKlupGbNiiKH1hiwYfKPrquBnJeumg7trtT6ORh17LLU4yKmieSFep
vaPsfcH6hP/u5XUxmGho+iYmf3+4ERtd0hGdcnTMhxFcCJvFSzsuC2UdNGImWzHWGvMWEQZXOSQg
uu/2bPWYC0N2AVmuKj2KzMb6XGPJ+3/pZ96tejBh4LRtfqpl3XengTd/y8nQut5ZEaD1+fzxPrxh
WZ4GdEVXpUdZOyFxeulVpnvdRmBTpc5KPpSHYpDkO7DZP4Psh91CoW2lLTYKzftZq/wwKWJM+HBb
MNwantA1Ik1FqZG0lqpRmKq9M02XK4eD3t+tbSs99k7ZwdfJhwsTYObTA87UYiCF6VBs8ewmUIYU
S9RQJi4/TqLq0XJrzLLZ9LjpxFS0d8MzDsTlSEomvJOworrRv5Gv/8ljUdJ44sfQV79d1o7/N1y3
0fQFsQOMNxSPPus3uIAplBhb3YvD8L/itCGn+9N3B1oPaUe0DGc3Vl0hFHsaHHFupjhyTgbeN0SO
3NFfD6DQFEE4ErLW/bhHu+ocmF/XEF6T82zcKcPLaDWh5TP0GeOhKO+YsyuoScV01+gR9zjKcEIv
j+ANpXn7ImS3WC8X8vU/Si0iItKMzkxKOCmwEf74gr5nQpHdQ3JjYH4PhDqL9/1h27SQeh/VMyBY
uaVEt7hdnO8pnJUDGQl00ED7F3UovHI+XE/JjEWxAVRiYAE0Vg5iRULz717UB3OYmE3c9uwSo27v
umKm346C1zPFTxORInTdtVzHUqY6M3R31gpeGinNx8ki/SRhyYch5QutpUn8XYFZZk9Z/OWcCRbl
E7B1IqI6kmi2e5IdJx5lmLO2Stput9nv6xRUG9bQ5NlUBtu9VQ6L49FaoHaY2rfdBg685ONxXvVX
cpngme2IenQ58H3kOQGAT+OXhUuFBhclqZxmgA6Xhh7TDz6R9mFuAxUT1JofETGP5kVrKwkV6ELp
+0Pf68aLILu2u1ZU+BzGG6qrrXL1pjMarqoucbLB0XHXuDQgZL05HgINRA+Om89KIPNzWRd3V2/P
QSUy7gERxaVHXGtwpJWzK/j2BJD53NDxOrHBYw5GmVpaZghWdJsk7IqT73UOg1l4R01ojQW/INZp
0ojp+EK2Ap9t9AQLr1WACzubpwMfRUsMw0a7jFrI+TrHOrglvq6Y4XBbdM9fCm0Pcrzbndq+/ONl
7R0+5xu/6XNxS4cLRUarTtMtrnCk/cbf2800WiP6fW9y1rID0+P5Y2FtgHYqxOAwvV17/2p6b6Xh
RIP0XMrJjze9IOStJ2gyLsbkNGjpLOokWLLaEA2whzfSMSZ00cFmAEpflqjAgMSvoEB2oyaud1sV
YWBYyvnF6ayZph6NUAxw69Ytga52Ob5bFQDrt5bG+lQxGL8x2q7jiMYV7Hl+shpTpKyOUxSeyZLU
lCc/FFjI6qVO2lvRTallVzyC4Tu1lG2ynR+s2I4I26FsjdFNvn3ydpfpC1BLTyjQp6cqRAymZHgu
EYy0qqjh8ZNze845tDJM15mpmyokrFFYHVKfnS8GQMNulEaKrR2xF6qrTTXAidbhuGUF2b8bh9p1
uBNlzYOQqmUl8NHAczLe44kXI3yoPm5G08kPF4B9nJjkR7cFqHFSt2NazI9bGtA8cLwlpaUJsVvd
u5M2ueMfV3zuUDr7sV2IANhGubui/cS8JF7dirhhczfv1mWYztTXXuZzfEhUeYcIT3/xrpfVVQyd
xTol1GXFRJAvHg5zvfDG1wIqJOh0ZJ3q4vmWNMbP16+ncfjK2CwtdRD82LgLg7NEKXo92CQehmOK
T/dU1dgEmwAVjBT6Pc5b0+smJeWpCYIbSDcGNiuw29U+CLIhtHkhCs607HDrdnIpG9nc4o1pzpUg
8/8S+VAk4B+UuBRI05kyPg7k8nlOBUcFFdv3ofVXkPOb3/ULf/7rsJr/BnRhkm92EKVM/NN41ErS
AQNWq9S8d04D9ikMKJeFWIPw3nPswYeNyxupV5nLrL1h1JIj/pqQAAADmkGeQniEfwAKY8qUMFL8
ndlXsCpTlSHgQLUqPYd05WQAdxfwq6tSsJf4d946AUOcIGaS+2tnsuwbRPOIfO40FS0kDA6H9B70
gwaf0KZ5bPoS25in1n8kQlgEAj03EIAJkBNKreZo7U7jhpKcCNQ+PttlXZD49SHZE2aeGv5ZmtWy
RZSX7U4mL8HKlWsVKwZkN0bmetwnHIMMt/+v/JtwIvX/8mAQPpaGp219LHGX7GKf2uReGH8ygF5H
ymxteb45BrDtEHUSfrPWHJRczR3Wf17oe3XXDy9dtkni50QVccYUXLRXvCtDzCH803G7Ex+ueXeU
4fte427uqll2DMQg7vffFTFVJq5woGPnaKXiaI7xtYZp7MSz7RnKETh6E7GNlOd5ZJRSIFMkXe3H
AjSWfzye3nFuUiD9qIIBX6iJy+WWV4PTRrOWxSANldDuhVzgg8LT12nVQJW/3PssaHH/yGvQHELX
y0GXRTVje0pbcNThhGn0jZvFy9YMpCjrLh6qmL3oWHgRXK1A6eVB6CVAuvD80iVuS48kCXuh7p+B
IZ1mWS3nA3Dw4UOESDRPW00YT4uimRXRqDuGRhiuTFXFFV5XOwkXu9ndS11BpyONsxFSuNozThRq
RUQSC7nukq4zFmP0IA8CU8o9jlkjNoOa49tOKzTgBrkTGutmDDgIGeHEFMEzE6yo4XBwnCYIBkxZ
X0w3bX1mi+/9PVOIiz8qLpbPcV4Q/OcoS7QEKRupbmuL0rBsoud87bJEyvddPe5YiQS26wXixF06
LuBxueF882iFhBxiS8OUHEFHk05t/gTSXkn7bSvoA0GwDdA8xKBxnC/sKW7GYMzXY7PYJKgYb8Rp
tV6OQ0i32M7sIEWiWon2XIPfAIy2QE9QRyLDwulxZoDEUE7hbsJGT5jBj+RYURMpYqtXM5Qvxrw2
4dqYBLscV6u4zbLETa+IZ1KY5MsUT1XbRWueaUa9Ha96XqIF9EotN6ipdQxmUKfBop8YDMpciGXb
nt+MYQc+KAbPlIqmSUr/2nICYpOvvWggVEt9g+oous5r598a/5TfaaqOlm7dKGk1RArT8Z02RIRw
R8bkAbjRfZySeahKBQTWtH3WNsaVtkxhhWZY9bB21EB9KhLd6l4QPN8J7e1rKX7k+PLdRPYhuQHN
tCmob69UIbXobZqFyJay3CXIlXZC1Faem9A+kI300XKSsoJkG1nwdRA9UHyWxWNABpTCwVkAAAIO
AZ5hdEf/ABBWBVTcgGty9Gi56Asob0jijIfbJAAhug/BltOfEG8WENEWe5KrXujB6G7XFiz8JNoe
5qt5WYzKxj1czKUt5TBAqUbAK/yIMJeN0AoaK7AOj1kSSLvqAaJPlGRT1sUBIG26zM72D9WB0YVd
78iNfF7HTxf20fcxikcQ7C597dq65SGC34+eX2s7R/E16kW04GS++3EOtq3tMb0NOsNLZOm6DK3H
01ZEJHGkB+v1KFV1mNGHSFtIbs0bz/mqLICrDA0xBIhpWsROyc2x/V2a0gqtBIjyyCxSX7+Wc+vy
bbc6VSLB2f4G2uhDtfXsemPZf7SQQitTf2iW1bT+dtg/PXzpifsTEpFJKBqi2LACkeAOsnCI49aP
1O8jhfDkIwm3fm7wZhOJKXBa5OaF4SJNE4QEfpHwLdLjNx8Qh3iuiS+yWq3pzPsn89IwRxFmZDcN
BfHe789b8ATcf8jnI367EFp4PJzkSIOsMz6Lo5QIAk2j4EpbRq7stLcfzTFKigkC5WIQrHm0cH/r
/ir9EkH30o7kvprCW53Xaffy0uuLTEJhxh81sZN/HNlTKsFJDSC4EIxqTOisNRMuViu1d+Ybwvmj
eyadzxXiTxl67wLCkQK9NeqhfVXFQ/ZacrrLZfQWTkB2mPD42lTXccfN1bCmCvSUP3JHsh7ywE9f
76+AuIrfzDKoX49YgAAAAXwBnmNqR/8AEF+RQvip3dIJ/S6rNe7zwAhToXuvlEe8K22nyKP5zhXk
DOFIvC/kgk4U87wE3WpvnbhIdoW7/DPIE6LbdHFGFWN5tPnu6CNedlXuU4jo+FSpleRgc+QsbzPy
bLOllYAAAxQ+H0V2+DfuU7DHCs6UrEbCvKzYJInqonxvmCnGtESstXdOtM9bbLrvW/lIgFxmiAPw
UE5q1Bzm55XKHRrcuawQWMCeAJZx7I2El2oRf1y6FjkQ/BdRBaZrAHtEY9Z78MkqjxSKwiWiZz5v
l2GmOvkAdMwSh7Fg7OEF6qWHmopqzc8jJhfe5skQc3/9cZ/Wee2IJUFHDWT/K4D587GtaM7Tsy8H
/CIYf34eSMNeTaYODWyhxsvzVqcXdR0cHN5sZUrGjoce+fxS0BP+nPTepHVfSiXmc4EiAJOWqkm1
+2abJCt0HuE+P9uK53B/RAnqTPzJX4flUT90gZnlnRh37ndUkXxJCcJQxolel2BgEDkhP9XvQQAA
BExBmmVJqEFomUwIV//+OEADI7PuUXdAQCn9qo7SWu4YNpHwjUnyWmPMuYK5FgrNbhYPtl2zE2En
uidc8tIIYvdYDv+Uph0n/rlpDrBftocSk0MlmiFQQ3ZoJ5MLgLCrMt3HEAYhf6Q/paRo3qmuYAjd
tuyPrBY1w97mpxQ/9vVn6iduk+mQTJG/7CCs3rkrV8/hzxM3mfjKgM7iZjK5oewL61HxEgbAkBSA
YzInvQ3DXhmRyT0bY/VgHta39hMnzUyafaHTwJ8rQlSxS1tjBfxNLrO9OxocGe5dTxJCPLethUn2
ln5Sly/OhNLRHP70M3dOqVrTVoI1WV0e2iwB3Yak1c8UEQ8xVJOGneYXQ/P2FozK2ijeKJeNOjgd
m0YlAVgsOSUb3y2EMp6UNY4wYbzW6GlOX7Hali6CMl9a1S8VK5CxEpfmhen3qYJdxtBKeyR7V+xe
BRmZP9Y0uppfTbHmetAPPcespA5+RYVv8JSWdu86Yakar8Govk+PVzyaBWv6suYWkaJogpxZ4/QU
tRuJOmp7Li/RvGp6zUXjQA8auzmcpxxClipI1W1umj60kYNbUz8h1bWEz3omOhaAipYdQbvdfI+S
/O9wP3wScBx53ro3mgnCyMJCtLca9LOrEElQdE0Aq9db6jeiPUETy1EcxalqMqvwK5AKK+7ppi0D
XBmG7TWC5LH5PlcooL1OxEhah1iUBNk/dmb/iyY0yHktbem5VuT7dxLHW7SeVtVQXDzIlPFETBPh
gyCLxD1SULd9Pw7oDhqFVFo5qb35+QKBrOwtrOIGQmtC8NYt+JHzWA0eEyw1brZksWPlfSXavwao
Lkh+QHTxrI5JreTdY77ZQJLRHEv2o3AvJ1hUk1PFD+GFbc7BBF845PLQPjQGk4r8GAZdScmigRFk
497Ry+h454DyfA36WD3aRURa27oXsZ4ZiQr1gT8n8wLySCKVzRKyqkS9JGe+QOwY6kpOYQf/rCWj
sN+EY6RQd7+1j9SiNyMZLxgBu0hoWYCu4PxIHBAcCk1Ft+g6bGwcnvdUuwXejUwG9hJJZzxuxBkh
FmLh61TEyMXEv0CXoT4Ki6QXWKUz6Fh3u3pyxTN9Uhmt0+lce0BBjTeBEA0g5u28ov1P1LDIP4c2
037FiOO0/GvH9kLG9mPGGfL2ubpY6ntAXewPtoSgDHlYpdBtXxL5E3czonTTg5p+HZC9JP/qJLw/
HfaLtTQzvYSrpuGxUSSzBTU1hZvURhO0ETogyYDSNIH9YeDNMNpAJLbGtQFvNEnN3oSPmD3/0rsh
SAKlZy4QVgCLbLz36AnOiA752WVfhMOcGZZe974uk3sffeYYdddUykerIlVylD28GTceddaYmcM/
SaqRGpBwCynOD6LJ3e2WL5abozmV6QXbsrh1+vLPpAlYn/n9//hz+MuyACo+mZWYiqNgTt0OwsBw
BFquwnQN81+FPcqkCrIdVDAHwQAABkdBmodJ4QpSZTBREsK//jhAAAGRdWdAA7ItmiNHyc/+B2kw
WCit6ccVdFXVc40iVS2FoSPugnIM5GiMthPMnsF2VVe5fT0vlGa0hXwMv69HiXCT/HzZUQ4YToWq
sgModSYSJy8kWZBbQhqWl8BROKRGHuHU34HC9wch1IhakFgR3LYvN1WbBhNGX8kkn5XAOWaXLFP9
q3rgCgz2O9IStFQbULLNHoluamDUVke9D8GGVRE6CtV+oO+FfZiqToxYi0NOhU7G53DBapKZgsyz
nfYNOqQ/Ds11ocFw0T9bxoCuqyww2rWaNIbnlpcAOOdYBxu5iIIkN7t3CfsSTs60dm6EvYgeg6KG
IcqxSVNd8dWzkCJTahNUkkke1lHtHSpljEdX2l6e02gcyNJirTp8VxIvbQz2VDjZ15unz6CtQWkd
RV7DIsZ7Tn+9HfsSyHDU1TB5TOt7naEz9ZH80jkzfeWdrH8uc4IMDnxwfZ0OwTA7xzLKyC3wj5Mf
oqee2zEA+LB6thgB1c9INSbmGwfFOeeSW4x/3Tb28mfgV3sajV9fQMXEjiIOP6NH3YMmC/+hvX2q
lHCwQxfQk9wR6fcY60WvtXMmrz5Ja5IdNh2W/L/kXAdCu8h1yh/MDXvaPajaNMoS9iD7HObwia+K
YQVwUBBfQHCca+rDrl1qJR+SimPDwJ5aSpqPZ4GBBfiu5NTgsoYKQi6BdHoSSgYKLbx3Unuixu6M
KWDnXNu+V5Ra9524uwKf6bpy2GQZ3yAR5/ADFIcNIEyP0df6AuR5nuhGUfxvhTz8iG8uSEVawYIr
8p4Cr77rvl34a7n2Kn0ATam3/9thVQNI35XsgyPbR1UFRM39sT4N4ZAEaWv3ZYQMa6Ao63t2+yaz
t/QUHiJj8Q6fKOHvW4O05aCp0OxMiWCELNtedBO6SCCx7wYKlGkS0pyXtCkYwFL6XUPcr2/90ila
0anGS8Nes5uw9oG9aXDXcPJ50d0X+lRTHpv/Foy53KS4jB73lYq1nWM8o82UsIWpTkFOCe0t3JiD
KfM0yV0RV43OeW2QjIlOOheBNjQBcoG1r22OQ0GGFhsvOJx0E69UccDCBjCQ5UZxllFuwm6tR5cn
WpGvqF1WE/wpCrCJ2+nccl8NmVC4uJcVeM1l7uZPse7+GWP/WDqAD31+br+N/7EfQUS55pkDJy4L
HoqS31bhTn5lO/uzMHY/6qoDdu6FhW4b95G2Je5Kgc2Z5h0mrf+AUm2ASLi94fRC1CYRyPcVwbTm
Qpn+5Sp7KLkF40eeFQNWT/arwMwBhrqM2EZiaPNtDaR8TfebYXEPHZxGjIE0YqBvsqTmEvUrnm6r
EtngLJgXFCV0ax/wZH/7fRGPkqi0obYX1lLKxD4o4O1NulOOPEsSowGf/HFJPtYSmO+eaonAZElE
ZTE277bQbY5RpHib3tUR64UbUR/HblQppRaTs/lMtf58YQghPAkx9MwBpXyK3nHkwEmPWT0nP3Uq
n+bn8i1vL0j0Csva4Xh1uMonrjL9pE6pt7cdv6DfH2+1PCypMQ5WVJ9kyudG80SI88UCHTjEWKGn
TADZxN7rMHefiNNvbhyY1A63MTRmvgS6IRVI/bmGKJJsscC2wg+qOy44MxK5ASxvKyYulgWoC4nP
JUyzpqmVwW7PjTWoKEdQ7HyLhjrVEIkT8Ze9lEByV+Uw3a7wxbH/FQPJBlJgkI+SFaw7mA6hUNZb
W0CWQVDdU5QM8booLsptDNBNiLonA2X3TJdF9LvSdZzLX/cKioaKBaYl+nSJtiITGcdL/6lT4F5h
URId4Krxk6ui8m/g6L2vnwUylOhahkdGJolm/zkhwSjmW8Y/bluyjo1zeMlyfUZX2VUYfDs+0pBm
jyoXtc81kYGJFD+4YED9lmavdlMcZFN85s/8PtPApk5d/IFjiBsJP974/tSeThMrp0HP6hgVisDf
sDZMV09xlrilTYdNYl3LKN54YxgzQc6euPxb97N7x0AL5XFqSgCYjO9Nkz0HQ+lYqcZb/9BfcyCz
zdMoX1pECX/qE8dXZNzo2pOkUhEqmiua7//D552ss/IdgJEASZh6fFUIAQ7s2qEuJJ1VZCbDy1Hy
oD32YoI5BedPHJafRBh3u2Mj40+WOPIYVcz7cDE4ypy9EwAAAa0BnqZqR/8AADTTyVQAXQAp+bfy
KMfx8r770iftbq5eeOHzhFpRMuicy3OigGN7K0mHLXdvqkB/giiYdjelrgkeyYlVFtbgIblIpmkg
DrPDXPFezXIrNJpq8NLgXxOY8jSt5LDkweamSPNlYU/jXHtbF2ZrcC32s7FXUfnLWWR0z5bMWVDb
1Oo813AS7xu/AKTnsp/X9Xwko+lWpvezO7ixLZjAKYyE8DG0GdbohhzQpTRJpb06uPxEzsFU2pC1
WIib36RJ9EJWVjKdt6jq3E7N8bbwwPlX1Mi0x8LupfBKCYlJQRjwmtmbTxR0Xj+W9+cyNDaWCs0Q
1tXX7p9P4imE9Ejv/1FkOfFkE2iOR+bokqc+24j9sjQQLxRnxEeDjomzHsf3BfX0eKHluxV4at8L
AMGTmuMhgRMc69ze5aOROVKoShAn6X1XsOFh+4/91BKuWaCfX5TgUoxft5Iq21LwlVInjRKQwOBM
SvivTxuegUuxZEznprIZ5cHFcLTry1P0W+HOgYsPj+mjdVgAB0+51xvDgehcYQKRTMPeyL9KU1Ww
G8kLU93TTADFz/kAAAYhQZqpSeEOiZTBRMK//jhAAAKNis6ACdvN/ev24kHs7dVXzF93czIrCis8
SqAAYendikHs2OMqe4Ddd2nr5ouL1IKgv3Cr4Gn86MDWbMZl/Sau6Yl4Y0yJBPIfPw7hSqOkzDsm
8/9L4wWwBLYW/7g6hpw8teMBxLNGHc1rQ4MfJVig+vrRHCPhBkRJnJG3SMfSkzP5Gk/wZtLehq98
FE2ZCFayWViUXk+1E84JGmiSiEhkULmFgbxrInxnf1wjKAH97ZhXoyJ1RlQHA+NzcI+esV5l5uU+
YDUw3NqfwtEwEEpbK7mzWHfiurumJKtHoTur4hSAZRynOLOdFyuhjT6xrrQslx3psE2LKJwDYg4Z
X44QZSon/rESEBJFHyvnOW3UIWxwdHrNt/G6Bw8n/jd1wn+kpxzrd47/d92RMJQScQB4zhmwBX+v
0OMlQIXUCpwl6QrR8AqHoehpwDLyqcQg38cabCgfxwY8InKebzw0CD6VQbYgI9GJEr4rNNWCAdFb
Wm8f9fV29aHSE8XUziKOQl4aEwzhfpQ/0r9Hb8NTKIEcXyPfOWAWFc3K29bYcI5Vp0Pmhv1c/rlN
hCYX1uH6eUXtVIaxF/hh+Y1GhliEtbOCWAQ1nrUFuuzCJT7tJ4+U34dqmSVuXMiL7gp/pVBUWRs0
uiP9ucdxB4uV9G/q/SfPRRpOL8Ivt+gCCvlFms1v3RumfHqt5FGBI8IT3IlJWss6ZIS3p8hZxP+y
SqbRvRsfVtuQAbIEA5p7JRJw2C801aNdruWtkXjIaXzmmdDeAEyPa7iT/zxd5FWD1QJSoddra5nR
z5gQtbOwF5dtxLeHOHcfqnyT5h0d38BPcAMhvrnWcqdjTphkY+/09hEgLZn5Mjg4AZFnO3wSfEvt
QBSwYPpv0gOBF8g9YCqAz/eQKGUfKmoZp9u0V5ksOw/IhvQCQDUbXT+F1Zd4OIO38wRe/a5NymBw
Q/POVTA03wt8jsercBf2D3VIAgzg+BVfqtsMWiDDOLW/Cnz0kyE1uZqzsDrrUAHiQ8wTggeSBQmq
o5SKBO8Io5GOr9LclCaybBYJdNhFAOrgrQSB+RJg7Z2/N+ZcQiEB0zekHLssE+kZisimfKBqizDs
pPm0u2cFQvlgqFnB3kFQtqVM8J2M9fi+x9Q/q0q8bVoCglNDdAEtSIgGz93NlqvGKs8Y5NzizpP5
szGkpHApembZOyDJiHchY1417zQzFSDZdiJdLkMKABy4NbO59Bjy7BogCs5Ue/zw2Kg6+egHbE+6
yt1UROwSPwvL1cOu/2Y/nO3YZ47gKKWlcPmzVBNuVBch3lewzlfeEIN/ZSqYxOgZFha84OSUFcPi
HoH9jav5KhiWJUkxoGT8CLhG7Xfz+wmif97x2HgXqseqeSVNxhr4ki3y7E47z4/d0oMcAtqVBhmJ
7xDuBmUlSOB6ItSrqBAGVoxLM1oBtbDiFo/su9KOS2jB03kBHm4T3NGh1wjlAZICzdnIBoYWNAEz
iWKzmm376RvDNNOn0PhleSW2tVGyzv67Rams9AUfPjgRaS1yjooEUZHA6215fZx1F9LYCM6gqFzx
Pv6wem03b8q0OVXDl1QyNde29gHWRpirL7Z/lXCZedxQeSrmTb0g1LfOFMXjS7U4CmcMgrUNOljJ
p1sMVaaBhYOTsJLTmKx5d4xDBQfzk1ZBP/Ji5YkxIZMtF1+A0UBj8KmKgO52CO/hX5B6dM4RTlMz
KocfblR7M6Mf2pVFNjmjcJVL2fkARy56mwKsPCKTKVEHncy0rYOOGxQOUYhD/Xuqhemb0Ysf20vr
fwCqD1z48k3vtneZgFc5/zsXcTlNZahGUrGRZbrnlWTaok8hZa7gLf3g/3KGYm14XowVLFvxDu+U
Wtcacg73FyuPFSQE/fLT9xrfijSbK3qR9JqsCyHqksMlR5U0Rz/EeaDSCy1HXRlm5IhkOGljuIsS
9UiCPjtYMt3rUnq76eIdwSzlDxHDONF62aDDbbUzvaB3WTkVgT+OAQIJ57f9Lh/JYgThqJbrSZM/
44q69feDds/Ita2voyHfmmcxaAJVKHeeTunB3MxSyFkh5SZgZqwVoiap51ZMAAABowGeyGpH/wAA
VSdcEg9rVOJxdckeBjo/8AADZauxLiLvW/Dn2sbA1k8mLlMig8QYyYv+BPObUHKKnc+gCj5lN2gY
qsKvOgu7SzeYwf5/4cqlamfZrLiLs7u8QCgTjVYcNBSzGTT3Hp8G5cXFkOOksG21BKYuKS/ABThz
Fb6ddehJY7Q7FCP7d8EfbsK01q6VUxOxwFzUyd8x8VmQWXHlfeE+jnt3eo73gTEp5gf4gwPfkcpy
jRU6uf5xaX7Y9eCGsClzoSm2U0LRC9nupitASzfazoqoVi+pTY7HVIO+UIhjBfK0k8KkhNTjkKxR
knt35Gn7qRKoTyLuk2hs2TkiUFXUbCkgqBwunWyGf2p+AfPeXadjtvoYko9pQ3tj3VAwf50NlYKw
TcF5QPuzRqTpVVjKpKkkDuPa77o7NJC/747U6qHGYvjKF0bmXnC66XUNZZcpMQ6lJy0p0ysZKBIa
taWlQK0V6LIGuNo+mHXWc/OMU3ADo17u8qf1cCWc+qrthbQRsfNxJPrx8CwUAYziN1YlMddO3wVq
cpRfP6R+dMG0EaTwAAAGskGay0nhDyZTBTwr//44QAAEFFSugA/FccfSfODjg5N654WkCyUQVQl5
/3dSdnx4Ov8eODVQnmFSCqQh9O9oAx5ijF8QF3P/Uu7G+gjjyBUPAF6xV0JYATGM6SSbF2IOeKmw
drCgBbI/+y0pjb+KsPX/7vhbNO59aeGJ73EIij6wO1oERQJ0t7v7q8jhyBC24fY8Xbtd9bCXd27A
GvX72wTmt4y481Q//FsifTZMTjHIpIj4xEjryR68uN0diciJCpVurRavzgtmSVcOoGx3ufVTzkpn
BjH8KXtxsc0d69NN4/tR8ZUUlyP9tA6CJC3AgYAJj7YfHNpO0A/BnsSGMkMmBd0iqjLB9A0q7cgI
IeX/+hsns+fuhiXUFksALTxIwIt0oDzMXLCh75uE8uNvehY8VclHghdwXhznEhTMQQ/S166p/2p7
DtJ7IibDpUS4lHayZRhxQKJEvWQipme+ZMQEi79QeomiWfx4k0VbDmMq58+Nz5jDjz0VhbtcW3oz
D/H34PbKF8V7gLY4lXcTe+f+5TnycALQWBuA6iH8ndP60F/Nx0u/0CO0qiUeWJ19zElXiJQPgTiU
Fzfgs9/yhLUCR78WA+be3j8upMcb3XNDyaWJYz1iK7TGl9maZHphIdwxbtsVLqk4+CIdOABGxjGF
LfszcXimWRScCwgPnrCQ76e881wKtiEgwehlMZcrUXaLBjV8JLEfSSOTd2uFG68nhL1eSbXfMXLP
DYs80nuOjJBLrBv8Ysb1fGcYm/u8ZhaT7jS2GZHKeFHNzLJoijo5sqW5rlMLOdopthx+lIW3bQrj
6sqRo0Ss6k2XzBTqozvw2lzDX9W/8LUQSr2N6j7YI7yOZFJuH0qVsWukqsYuWP9RgV3y61j3wnML
V7cYYgoxqbVt2HOl1w8/hbFlffEXwPgnoPrfAMvAhQUooKfatueWsm+TwEcUnnYbwWluHSrnFxDs
2CwcgYLi6Vo5pAIB3H2zyc5L5QUWv6YXwHAeXqDTUEDvu6nwOaQCN7W1AP423WGbMLtw8MfvpSiB
oBmfWkumEA0fIMVYBaa3qXcUTNGo9cPXGpGoPoS9+Rf6bTlOAGvbfLeR/JfBL9j4HxJ2U3mqZE1A
waGAsaKyuL0CycYGsVoSwlY2djFi/vkycE612Dlotac+f2khZKVFucVzEM8mwDF3QhH7KRRJy5F8
W3nAD//0oCrSRc3l1GBmWWWSstmTT+zN5y9IGT3EljIIc/B+IEkSVp5Hw82/VBf75b6ip3LShVF8
sbz4DzVOuhEpsvUTa5P+WFTA59f/WF2stbfqmvaZJIikK/4ys6E/94e39YTkUbwWGDltPVl+eElS
2YgIEb1IUUcmQEmDYMjpAPFRRlfzaOgUbbfy210GI0x6V5lKNtKxeYqZ1Wvgnn1nx+pQUkdmPnHX
h+gILKxVN04cbOyh7LCIE1xIG7LUDE8hoOqJlDwrkGGwM3PgKsjavKg9vaSMBtwv6Gd5A1wRfXrk
rAVSrFIO/veWwbOeg4cIfctPvDWg8nfSftC8lVEpT6DyYxXBySbKRjV51W3Qli4s9Y9vMZ6G7snS
0VMaZH8qbc70jfNBrHk/MV7YRq0gvVJFFpyCEv+OYvZP4X9m82D/ZHWFssjKeNeFDeBWizrbqeNZ
Biet9kcf1nw+L3uPWerukrHGKoP0m0yXA3+A9R93EU2Osd/WWKe9G6sQQm2sqRWMEGcgrN8RRCKS
J0prkOJsk8qqEQRvUfAH5CMeQMC93a3U7nms58G/IWbauQnzIpyh/1WpyIpeTqYuOVtY/YCGx++n
uYMTglxNrKBm5izexgXlU8vfA0T/bOyKIaSDpMQIsFEro5R5lonUYQJeXJ77ktMn1B7PM8JqqfdR
4NaPKX35VVZyJkUGF7joyVpSphyo2rii7d98yrImdn7X1k3Ziiqye+lEm8PXgFZ4fFYoP5y92edM
5U+RNovMyn/IygFkuPnAugyGLXAqXAQcGq4eLPk0AeeRKDlP8+AdqBsUbVtzB/U5BhfIJW2krymY
oC9nlV9YYxtc3LMMorZrRGlGmT1uhH5DZPmu0VjwnYXaHid1d8rYmAeUcznEoiQomgwaFbyN3AwF
4UJ5Cd4F0mJPHhFb9ZC6cF7xrRdHFhLpzS4PwvbgWUQCN7QMgl+l8FEVVb3xrz0e8Diavg8cpvHL
Ie5A2WDKU+bEY/edPng8ZlcPIzqazJShxXs2PyHbUuv4EPRNB9uEOKpTOMYsk8+sKcS3m4xh8EWC
vfnCEKkTfVtBYjgDuccp4e/8oT8AAAGmAZ7qakf/AACK/FKKz8nnlt19VsG3LgBB3UaiiNXwFkn2
t7qECzGJtNCs4zg3CRhrn/gXCVHK5cxz+gIEHdGEWnuqDjYzVPI/NygXFTZhQD8T43DRNVZhhtky
mxwkHyby6VryQqtRYrbS4avR5TfT6qH2VBrrwYC8QMnyeeubj7veERPAbS1Q0xWqOZ/aCVc3C9tp
64JYD8q/JJPSKl3UNpiK5teeI8ONeXIt8RqUTMcSA+O0VcPecCM1AxWvjfxK0nvw0tH7LU6xeA+W
57KKSOKLTatnJG4+KmrNA4LyM6PQ78b84k/B8Pd9MsHvkO+qO3AwNWZ0paDvIZ5MHTid8GtqY01a
/yQ5EssHHg/VzfqfOEi2mdHT2EiyFrI8aJvfky/iB3mtn5biuBG9JPyp+I5GxGnQeefJTUW8XmpG
em/PVfCChILz4gaEUqa/nTOFVWQjzcIENbLJNOz+gP9ExetKecPKh18sNfWIrygVTn15HwBwGlOV
7NiEP4PUFsqaKdnhZdVJV7k8octgAwwMF6YH/P7rdjlHcYpRYo2MPVhi8oQvXiwAAAS6QZrsSeEP
JlMCFf/+OEAABBLRSJTYxFjrL6ADV1fwbkGV8PhV2GNyI30GvXqME5aYJI1N/TfHj3ZI5EJax0fh
Tq7bsn/Nb1WkIHdouTncJmwen2Jk2VS0bXvscH/kjhj1z/owiHOBmpUOnZjtNlS8UPKxOGnipH0i
1Ti5gzigAL63nOzWuNUCySHPmwwSd4/n2GE7oAQxJ4pTI1/aIsoHaRhV4m7MJZQsYlZv4XdTXD/Y
aikVmwZxtyTQJz97Z3uCLVNYJpeQAUxWVuhB83/P//PIKr2xZTBawd6NlyqzaqijPDmU30Pd6/kw
qgR+4Pl3l1fbqDUeAyHsRBI9C7IWTE6tBOxfK/U36KT/LSOLp5aLk6Au0e3Pec1VYhLZYty9hLgd
hiL/dYxz5M22u/Zu5ErRW7wd9x1Zu3PEpiYwlUcC9YEMw4e+OK4GH2V3oMsVPvAULLcbOpLIUYJC
m5HUQCBezILMAkYohtc5wGhtvsXmY4CTebqLtcDU4hckQlsH6SzoJvnRzfOEGqXv+df9Wyvp31tB
K23/ePRGlDdLlcgPee6q7EdesuFEsPV8VJCroGhVL4C9a6oaMF11WaPOiP1buE/ZhZPRU+5oKlNa
Cq9yrK3uPpgYuoDLkzMUKVx5zt0bBBi9hbP4Grrc1NuhEXYWEmHsc0rD0XtMW588AzKZA7TCuu8e
qsWDCvSocud1Np5U01dPwbKfiamK0iqqjmJTJhnIQhtZqM8kqFZe1W38pRsRTk3UUXAn0CVfbIYa
v84A/cuKMw3vnA1DC1D582ZqoBPUlQ6HYVD04Y3z8rJIpz9OrnHXjkNlw4Eg8RxsX/u4sKihLBcn
ILsbGnV+HECECiDxKe6DIkGzev/YnxXF3dXAcnU1xDuRu/0DIz1WokuWm1eID3PfZEEGWIUqyd+F
sfBdTbxfzTdH65VfxW81B/BYWTXJkT8FPwXyqsY9q7Nfi1cDP/vLFusHeooow8f2o/jSOLiAU756
hHC4JwDYea9dT8+PLSaGNIxHmSmB1sGn45r3XoT23VTRIQ/paTjCRhrYdlojY8H5WzbdW2bQAhja
U4yfjumVGhQ6TId9p/NhzS377FbsRm9+uhfk6VM7M+myTYs4zfMJo5SZXfHjHe3+Yoeu0dw4Bs80
IB62dYLFf+Lli8g4zBdeTkQi/Bup5xNMOXmTDr5ceWHPKq0nKJdPbwAgvHb2KgS3s8iw8iXeNzho
6K3OBg0VmsxKFEHUJzJ58FLy7RIJ6g6bFYi08UjZn1EEn2FRjRfPKqh+8nBPtaSF0VsPy/td+Nu6
gClf0caoX0rS28HO1v/kjOuqsWhalnoe9mD8R7qWb7laxGTM5TPK3WLp720EBktP16jq9od0/nLt
tl6sp6ASQiQH39RkqM2U6h1vsV4gh5yahT6oJoqkUjtwAWdyKT3A6cQQwJh7yPtcSR7jA+PvYB/i
XECDKuxujkjFHoLVfD0k47I1uoxr0z4LCyfc+N7bSOxo0D1mpH/Et97Bn0gAlPV4+iIYAf6qfcbz
p9rljaJG7ENWxsWdEC4UUd3R/vdGiVqjpY97iyNwYIRcElmQ+Tbjwgxn0ZI9rxFhQv3zcrukHk1A
LZX7Ti3EgAAABSNBmw1J4Q8mUwIV//44QAAGu5oFCX6B0AE48sfAxy41Djw+Nuuutee/hv/YTlSd
Y5vX09kJgWlNPBeRMBfjGdjuMZk/5b5RR+Jt8KRHCV7VTJXrUQa2glP3IQQnScAJcUz3gSxEGR+j
VdtX42EkBsxvwazdUTw1wTSibcFfME+ZqTHQ0IPO8xb353Cj8/F5AOElCmpyZJa5HFrwnU1oQJzK
FPIsC3v7pn+cPoxK2BVs8oZSyhA0uksoY9DeKptRlO1AD2FA7p4jSvgSOVIg4QEPAydbV6mkrvwr
SOQ92Z76f4B3cZiFYrqW19Q1PLzeJDzfrmDVvDUT4SV7o4wXWk9d/LhenxUUs9VGmm/mEGFfSEGm
6njsduJYKUwF2I7svdfxfHCJ/DgYeEw3xsH7IeSenuFYi4w62BAUhfZbZeDQ7AUAu4rdicarp9ua
n7+ZoQVn7SLoIjPlLXF+059wjibWLuTWsGKjvozG5g6ileCCONqqnoqJm49hifPITnX1I+wZLrzc
Dk47hPrr7UIHB0zUnL2G26xf03Qe9S/njC54xPpy5YVdoUbA6NUAqE8vyEToGbNDzgv3VdHlk5eh
UhrDNls4dw/NRUd1OeuS2n/VsiuDVktQFJZIKhc9K8upUgGRiOdy/Jk8zlqnwhab2wgoGlYUGTO6
QTN/AU4DioqG9QfOgV+Nac3ywBToFBzN4dqzkfyz+ZkoB15y3+XZaJiuZytQRdGMHfqcRzTXJG6Q
DcQFbVzhfQHVKWmW9jr+GnM6NXOhMKBLlHoL4ZZrixxeCZHqro8s1VUAy6n9tOosKNBeSSC3otSJ
SL5SVL/l405gzWKrmscsOzySRM/Y/ycN2o4cdPwCJwOOBppaGufrCd3oFGOPBXmK+EFG2PefC+e4
v16VqKGJqQg3y/Bqa9mHalUE4hVjasXcpz8tOF9JjSfI9erqLCsijhDRl7jC6S9zrsHPsJlq0wZr
Lh3XCmfTrirR4isX9SvJihBL+gWPqUwwYnzmevOZ+gxOCIP0/UI7vUhuxbi1W44oN+hPz47e3A8I
EXPTwLDxgKQ3YlsXK9CU4QV9YSfV1dpAMEGconkG9ck6022VDMXancjNDgtEbK0SV8/92vz2B9p1
n4hcFcc9idqO0NajzjXIZRZGq1PMf3Xw1F3W01fQtv85mZMUmeMNnbmeMUpuMI4pSi3R7GnojRZA
NaYCKbhP0zfuWaq4pvxjeE6+9cW90Yc4uWFR7S7YMnZ7CAschkWF98Rhm5IYBM07CFE8+UcWnEAG
d4haQwN+S6zUE4LZpdifEODV7938xtOxxPZtdRtqcnrBRshUQEbJW1Fkjw3tYhOMXGXG/4LuPJk6
KHIkllbO6jA7g53oz8qPu3zm1o6nOUoaLsFKBjYQDtD63M45RBNT0+z459bc/nZL0CFRSkqI1TZt
joSoNfh7vJ7R9LfJ6YRoOHgEOvfTNK7+Clsayt9XuUAMcem9hbT2CFrQqDHziIma9t1xXW0aE7fe
YwEmqsZMRfRTF1JByVKERDCgXLC1I7n0k9jqMMAMDEEZvq2rx8dAo1UKm7cWo9+xoVwnG6JnbZBP
KJndt9sAkielVuKwOWWY987r2jHnoY8A93gZzY3iO3MgYHKFIQy4kpGAPExiwDcptcAxYBdRWbnv
2VUy1u/GIeFJnFZmw8QAPyh8NJKTTxWHjUe2rU0aI6pdLoJ052a6hziQR2FTwdfRj/brPSvAJ4iw
c3kn5zqRZT4sCoo41HSBAAAFD0GbLknhDyZTAhX//jhAAAa7w689AoJ7sBgBCh+cBuYbMIP0nyX8
rznp+UK/tJKnrhBQopf7N2meK2NIf9AIYEOi+RbC2clU4LYINmlQcHJS9ai7VjkSwxqkuj6o+l9I
2HnJLQ5VUukUzqaXyoj6QB+VSiBknG5z/prKPMooSu21EFbPmTdZ2PTZrVapGSpyk4CK3eNPEAvm
W7lFKb+n/nILoapf7XJwpqwJG687pSRA7+aG24GSqOTTrGZPVRKsGA8rE6MErBgFOs6tsaIx0j6J
s8x+90A1V+NuY/HiDFMWTzy3r597hQSgWVvaCJQQqUw5k1MCY1OaE7e86mWnxitp6OiDKEfZSg2S
FYg23dlRW4r277COXThI+dkmR1S/AWESXF6unBFdlXJiUFDijA2FsYLeUQy4j8n9FVY7tksd0cWI
h+UU16v0emifJUY80odQ4+hMuPEye6MCQMhNEjAh6GeSu4gZPFRkx+2FUAe7jjxjzPPipXSuS+aI
INh/l73QQbcYx/HKqj21VGr07Zuiuev2noQ6fuJARTq+AEY3jvp16dUpjqZ0Dou65xcBWglqPLm4
MAEud+cipjq6FjWD8ltCYXZ4IArQXdBaITAPFvtnsG9XeidTWFXzy9ynXDh7wRLO9I/MBN7RKIch
SqYSJQCdgi/gOTdFlkw4dhd6hayZMB6gMRFi7+q+oxBlnU3plwkkKB/lH+ejQSA4fAbCPnBNDQ/Y
k+OwVHQyQQc++OIUJWG1PZhZXvZXgVKGd0WRzlUvecNNzFZhAKF8z3YNqNpQpoPuZ5+3FOyUFita
AoSeZWyDw1gUbXdldwwIaKfwGWLe56KaDWRL5Ve9nf57bmLGyn0pW8eW/d3gKADQ4VHsSqjgnAcC
8ks3qv79Y86hdXwyXynZ+qGTksKfaBM5q6RyM1e/j3WhZWD0sdQCXfLlEFrkmGjp8yqbCzZynqlC
bfKg/QFZ0EzjJ5wLzftGUgbguHGt43gt+42m7fumqM2UfoljaTenDtOrWA7hDHLFhjjWcux2cKc1
56xmZIvPgoy/mUYsW5Dq3IOu9Sj6L2MJpav3lirD2Ck517/Qx89Yl9xrY21n5ea8t1Ombj2uUqgb
JFzs2uSkQI2HNhVt2W6jltQPjkYXg8J4Zu7jw6Ns68JTrlgN66K6rE9lAWyNm0eAEi24YJ3DNCdf
wOXtyJpG4RuVnQlVOsrPLdV9+TAYqzLY7k9KXURI1oKVXS04+EvQD/m4rEZz8o5ouabhIkTL94o9
314HhcVTo075ytLQdOcvAaXrG8foNpGgmKlD3pKO1K4LBcJkPKg874SMW+8R3Ev9Hwxh5d7JdAnC
4hLjlmZdYR3jxrgUzlGASYekt+fdsCsqVA4XeyF4Wr/Q/rTAatB+rfUfkXQjCTFoEs7xsOgbaAoF
LuvCYwAlb6HeH5x98XQzCWuC3iLxWdpBIeZMB/P2+GFvLtrZYG6LTalqxllldpbMjAWs0IBSyYqw
pG+q7QN/RO7jYP/6mi24ZiOn7Uw7TRWvWav8dHGwXZ1RsF21uobDRJ466lWuXiO/A576Yur+cXDa
qtXPxM+0ImKNGPc1X01cVaLG4wFHj8ZIwjeLcS7HPQ7BlmrEQqQWOkt+FPGz0wW3yXKneFesojFS
M0ZHForDBSrTQNa5IKQK4FCtlBvCRKUCL4YqDdLbRQvI9iZLWSzNzby+rnM0ph69yPXwypTTwaYJ
9dFBAAAFrkGbT0nhDyZTAhX//jhAAAsNrEgBuvOjI2BR1B2HqGW+2liARKUq+8hLpwnN8TMuhZOp
ZRQR1qm3ohIhQlD7iy+YzsYhWUK/N0b74tKeBnhM3uJ0ht4uSTp8X3LfEr3P0qH4kxAYwOL3xokl
evPUu/rYLKWxJmH/ndAEFh4SkEtVi2iIa8sknB6mjE7vUER8DAywGn5iFA2InoSGsV3bPECrPYIV
h3A0KpjrOIPPS4TbLgtcjC9rYHCqX0CLCKedWHLw7wqZ6KR3WC+3DDmt3m86si2InKNF14x5JfU6
6K9+e7HphBm8RPndstRD92F8HGu5xh6eccS4j5xPRD3cOI7KtlPf9tfuFsI4WJPjunXslShqjbW1
kCZ2QqWmZMmsoQIzfsn5Kkx2/bN38wCNZ2F6TQ4SOAJIRSaiHBhArxEQ0UYuRzmdMRzED6++guvt
XlNiXqPuWH4wew1PKLYxNuW9jKRPlwjAi4hUS5EeIlsY/rbJqHB97DpqB+PZBlQtYkW+h0xbYMst
13f00IA9UO6HKIwwzxr7KcpQwksR6vDPpeJpuxUuoiE8YbzJDj/SRHtDFWkQVd6SbqTfl9fSTfZY
DGWLtU6qa0ZkrQ3F6wlxp8YiUkvrGYeB0b8tS20DsUt/IeuzDaFwjbduoMaKlg7ossRzqrgNA2w1
bYJrk6Z/gEy8vai+QMnmqkqjGpjvFIL6jDCzm+7sP/aINLwAcojVn9p9Q4wBQCmMxmXOai//478n
TVO8VsdDzW6NgeN4+KCZB37xqJxEYqlkgnf2l4LZKVtI/Ku++JablC6grTw1jxeCnSG2dknB7R1t
iiLtrzOywsMmR0WS6xzyayK4rXgUCLS/CnCKzLyFjbqwtLZRsFJONdy44AVYtxFtQaQVGw/Kl+BG
1EAD0e7MCupuTmxAFKZK/NsdXyJJykOIH4yGflNdTIlJ/bII2cWtl1a+xBmLq056XwnTzILf+SDI
mjd8qNn6/4kafKd22C4cxiTExIVXBnAnwSHEC674+IR2Wo+QAOcKw5e3knF68+OoYgQFVsOdI01h
QCxn59YqvjMGyifGT1lRw1lMpQu76M7STRbFl7t11MBcHuhmRf0Z6J7rf/pyaWnYrHYJzzd7U70I
sldx6XNWUYa96sIE1R6rrmLNsJGIRrBsSaN6O0xN3jkXQJBxx47U3RjU+Qwy5gV1XYZV4gk0hL1Q
nXNEvLBkNp0+fb+FjaK4ZdloBUtWiQmGmDH8XuEIO5gzcl8VQBM4xP0c1fOIvgaJURKE7iNib72L
tksqsttOO31QnVzV+LhvGY2cC5QXVA3BZ26zJ0q/oevjLTVRt1g4EHpKJckVggcOkdSZiNCIZtMh
YaMjwNRN0XNIv71jUNoF1kxLCAveMTnu/GpbD8blB9W0tuW2i3jmZwyYDNJjZ2wwOewlgvz6kEK2
ZZzRSKAcNs9Zup6+HZ4APd2DhG2NbYi5J4uTZEB8oNioshP+bRjfqXmyyFpKxuqxaWxdkv3/zMeO
LlgrRwEBVBlsKqNn80yr0NEaRLVHOmoio/9fjWwl9/vyBgPvf5e1N399kDl0Q/n8GX9AMBoxn3vW
x+YlObOFZFas8/0tUgZtA5cKqYxDIE/38Uzivzt1IeRpU4xti1e+y5CZq8thuM1ToBZaEky2yesY
nuXUU9fTcs+fxxmfhxArs+mZhfLDJEQYhjC5552gjcbltjpwQy88xstBBxIjjcbHlFCpdtGVG5Ay
5MDqLo+/F4RbRkGz4UD2uQaFYKu9/O3RV6HHknXrj+/X2AFXDg5ESszBvMBNvbR+Tbkm9Wl8mdI9
Fp6Z46f0Tu9Jo++bI1JEibedq8Q0O51D6qoI/dSTZ0iFtMW6rlvHgKMSXO/wnzaBUylh+doX4ZG9
M9POaGPEzlmnNlIPH/lDgxq8ZrYNA48gpjozDgZ1g0cD5RKBAAAGAEGbcEnhDyZTAhX//jhAAAsa
97BYcriAE1EqYNyrKfAWVhihX6uBxHyNWEAsgv/Y+yEWfmDVk+lkZeLy87ceG2ECbIu+jMmXcUIU
EtkUN1EZJzG/euTz1chyVmMqQ9iCEMX7Hza9Af3Sxc6UnMlkpbp1ciwOqQDxtaIMlJXWyQwTSDUI
iX0RceQHb/BuutUn+mw706CqlEbn7ruKZCtMP4RUtG/O8T+9bkqkYgmGEGnry31Yq0GVkKFHSUa5
m85J5+18B7THuITRoSNPu/+U+ZfhmgW98usO3td1ScI/wkifVPvW8xmXLtFkIem8yXvk9gDthlPp
h8UmCg1Zwt/1euFAKvELBxXuUjOPwt2HU6L9lTj3uW265LOdj5/m9cjGtzLLJ+rTrqtZVWH3ZNNC
Ac8kt6HSK3dUV4dSGTxnSg/RUVV14lSPjOilM/gd+QsmMruFPqym/T6JSLe3GIdFLLryIyRFmR8D
qi1vw6kSETuW+IiI3eH7o7T5oBNmOp5AY/ePTth3kis1kJEHZEjp9QmrJP1LUhnsfGDPyA6IUkmh
n18g76s0k2Fv/ItGK9nqD53YW8Dj6BzNjhpaKYcZVdMxD5w3E7X0Llgd4zBCzcQUy/GR2Pq166fp
IjIZ3W9iJmaB9RdxpNdp8iNZvtNvaCXnLYy5oZzgR6cqO9XfVJJbBF/KtPfXnkDpI90qDxkI5Mq5
rkETe7072Ncy+JVLCfAwmPIh8e5Dd7EvLE5GH1uOJOlnA2Bn+lb6Ww5Xc/y6rq0G8HLefdFFzZBT
pwV17LrlJSABlihd0G/U1rT9szP6MmsTM2D2TW7HRsoZO6KBeBgMY4XLlhJXS/RGTTa6YLq7cNOf
UvPw7cvNZuahQgQiM5iFaVUhLVY2KxCPSS4YPgBlQJVr747cYIpr4AvWi/jY1J3oN25WUo3myd4R
bANsUVOhFoBN/YoAxcbbn+mIlrIwXIukNchbNDuMJbNPB0dvfMGowoj0mDLKKuWNP5i05Zu+jM+w
77CmWgzrgJnl30dzVv36L+aI2eUET8dVW5QFI+VzLH1Y4m0dfUl/ascxWgAjG8oCLdMjeAkpeKCk
gtqRJBQBaqmIDzU2GT+89KBB7gBFTn9wDsZnvUZnXoYmjFyz8S5qXvn1HVL8yvko3FNgaHCt7t3W
5GbZXEEZpHj7fHvU0zvlWQQGZy0irvXel4eneoYgOyB8eOpJwN5db794J3jXRwNoaInVoJNPvZYp
Ow4cfwn/30gVeCEde8OXEkSTU5M3wS8zLTDxMo/XZAKvb/d2iu2Q80BDU8MJ6KfpmAm2g9j6vnXD
UVaYiEx/nCK0GCRVmJ8paebS6pAbdVy+z2HbP/dsNvZd/bLG7LRHvTVc8B5LJpkICrfSZmgX6hMM
0/MgA0okbpUAzYG6+ihm4+rcoh9X1yZlJG/JpMy0Gf210nc7rxJ78Ey1AFudiXQu2rxEoKVfAp7C
5u8uk9y10a7TKj5wBDFH6vBvH7usoK/PVe7NITPwIrvuJgqcqASZgdKj4w9UAfS0rvf72AS1BUuA
P9am1LNzo9NQpK5KJnnJwuf5qBGFzoAMlHS7w8RGP968w/Lqd/1sXEgvXKCR5OcReWN1wENyOgdj
Vy2IO2Se598z2F1Oi+auVRVKRdWDaYxFkCR5Qe27JbtM3UZ6xGwuVlHlyPQGvnM5kFIXMzGlpkeo
r0NRsDRjJxQbCa8EyHBKePS7tJ4lUWjq4Vj+gE0AiwJJsB0rqZmCtD0AmxdcSwbwte4bMUomPGQa
qiKIDJ1N4N7Zg0Ug/dHTyKndfNPrW3OaTPdyEs3UoE9afzX7XgYg54IuwJ0gJFWUYAHVDYeyv1eS
vRv7rPau+qsLYAaNfBcqwz2gex8toDhGSp/IWRfFfuW4WERMpSsCOj8R9vhIPVVh1EKJQAw0ha5+
BI5nA9KkoLxpOmaTKkrRYRsEDvmwX7ZB+8mJ129LQlm3VEGc84e0lamt3VR0ACi3ceXpWp0eVJzC
wyw2/LISmmOe+Q5FzvgWI8FYVJCh1WTITVUU0WnUWFgfkhfezwAABjpBm5FJ4Q8mUwIV//44QAAL
DNM4rQoANVuBhS/hkfvgUM1cOnModYzKCR11+GQb4DyoE0TrL88tPBgcja7X2Dko/Gk+59wnmC3N
OhqKFRMxGQuZSgTGuTGmNdh21Zbb2jP9qUm9p9/fJCfyvFtcNzUF99Sjl+/AWECUvCSQ5qMWDayu
cZXcdAWInC02dXe7Fjp6RejthVqMmQsfmKKnfqcxMY7xegL7QxVwckT8ByXKXoWVn1cmOfMO4fmr
7dmms1tljdX2LMYAhY0vNPzBaNcsy9zl6kMjC8Dj5jT6huS1JJjGkk7j5RKt1yzSi61MkOGBuBMg
OqIyQ+sKzD2wWlcMqa8sN1U8JvCODcTcnjbxNTSWtyW89QtufW7NvmB4Sxokir3KgnBd8JUqEt2M
+9KWe+to/8fRRSQjQjhvZtu01KMBWSrg80pR/XgVkLvmWGyJcqSfHRHiymT9JKl3aM/uLQ0GR/Hk
sp9+9tS9ttPt2VhqSNAFoBZuEYB84lG4fniLMliVmKQ1pntH22uoRZjFGlgiQYoVQWdFfh4DzYUN
9g6yGZD3bbkGaQmQqflXFgWOBbreW8RPYJa1/zXoMRkoN/ZctTMlVJN2xCXp1TqJhXcn/3HpPcmV
6TA0ncinWXgpHmBqEEl9A4htdttt6gmxsuMGAGKUJY9nNg7w6u1xGekDGDiS3yiLOSlT8s8xrIOZ
iVryFDCM2TdkoFwoOGC9CB7YmuQPg1LG53V6vEO6Li959+EW3Fn5aMOdSS2ucla6++ncCLSkuXzz
PKk6gxoBKAAGEH6pQq2gankwruxY2QQqOEsqEIJOh67tfbXe+R2hm2U9TrBRKvBDCcUj9rzrcGZx
7t1uwo9kBhRCfUrQ9p6Rpu5pd3xcVXgnEsbIPT9oLoJ4v7vKh+ngNuKFXv3R4y4FutdcnWTa5dDV
EgL8MMuuCoqisIly4L+uqiVGVQZzUcs31PBPKH2lkYCeu2+Iy2dCmO8L5dCVRskkBkszx1sbgmGW
bNuKgGBotsuuWLLNa4hjyqMgSlbv/PBfhkOncz0wR30SK/fKV5qFGd2ERbc+Y8Mxa8UwIkZ2Olpc
nuIo51BnMspOht6gtF/KfCKaLnzmiOl6cboMtYuhnOW33QHRlfwyRICYEeJQv2+qGWyIzYWkcuL3
XrZ/fuXdfU4j3WBHVP0iLwGNw1vKIqf0PA1oOjKFqyHxNAcRwtWriIyw1QfRIhk1RrY/fFMy572U
DMiqpRPVEGuYiNyLCsB45FPDU97EhztfVH9/7HjyiUy76AaJMen2IWPjNmxMoya/Z1ufOXAxeFAf
huIOizP4dYEBw57BarAcrTDBd0EYJ7JjnjcyHC0fgHoTiCknhCJRwCWvi+hH13BcZBWv2yKHGi/5
znnfETjcJtGcP4MZuxS3O8HAIW/JYurVHdG6qp1WYqT94rBr7768ZiHczXBuCGTwBgMElrWoG0Mv
WxyTaNuTm6vscZzAgbMsp3LzBYDbeBE8xue84To9lMXOIXc3jCgI07zRUJMJPA7qQC4HW/XRKwrh
V6vo9YDmamFy0BcLT2ZsvigT4nn9LUKPmT8PYwP341KazR21J6V8wNCiWK/wyZvPhreIdmaLQ3ho
mfhqOBNASm4EpQUbz9cA79BTU+t7XA9f0zdZprM2WrX9Kcw7gVa/N7kUFMTK3jJbw6ngjJwhGI8I
9RQbsjdwRffTk+5AE0/GpVmeSGC0xw/t3dJQhlSPHdIKAZP4b90e1c/wJLeKy9DdR+B+tjF9B/MQ
+jjUzlgTfiHKsW48QYpGkiwqxSGmveAE5PVj7Zw9I8Sgwyko9+WsMxwUe1w7zPusLwO/TyOIwRLP
7yB42MFVjSXnoV+AMFdQx3ot4hbpwGNut1ON46jSqwpQhR4hYTe8MF2Z2PentIwGoI3u8mLVeLTF
ecYIHN9C5+t6KEDtdH+tLcLwyXvKe+HzctyXDMFC4kFBwUJM+I+A0kiwF2SigvQ6JqlX/sgkDgW7
9Z/RzY/4jpHINWCQ0vnL1vfz6rnnRMaze5R5rG6LskjWVoiGmewqipYjMGhsh8g1QSfPZVsJpbID
gaKf3zwfJ0mj+CHf9eXXWYGOeQVa5yReKwnpfkBv9l0L01RQk3v4AAAGKkGbsknhDyZTAhf//oyw
AAShIJcACY8qpqB+MYs//XLESfNeXNZXtFwMtk3rZxW15TN/9gTgwIMDYjaqonyUUx7sAEnp+P3v
RS4DpM83aeilh2WaP3ZDfM2XbPmSgt+DV3NNMmOpyIfwthjbTggXHu/pgVw05vR5QOvyx9i01NIu
9Yy8mUALFEFco0v8NiOFsO1DlH7Qq+iGNUWbyyX609JODaUlAalTP7ieYAQcFsx6kkf3jHPj9FhC
Bbfuf44kiyDoISQzYoEwVRxoYYjxNdsZXSchvRjmMIs/Q8/2fw+PJzLS1SA5r+EU3t2W+C7eTaL4
e905Ldtj6AAPTsZ06NF2DttB5Bp3SbyNxfMsYepL7MmtDF+ul4uqEEAEjkDHURpmPLfEH89vvXu4
oUccrxU5DaCMMnCEu1Y1gp7vxBxiYM66Kjjns5cKT5XTBcpvz71N9fJ1XBkVQxnxfOZNgMf9Qfj/
veC7glsVeddRTvahiJh0TT2at9SlKZCqshXsMN+ssHRbaE/RLumCqkWgr3TSI6jZSULsPifHLR29
VnDXFIXrOMNukGRxNStEfuih4SaQfaaSKYS4MX9+RZaAHmpQJNdd1VT5hi7cmHo1zl3R2iiRFxgJ
/+ObZPFntaG/c08J0yrJnBjta055k3qwP4gSRxCAFZ1hLAIUl22HrCitWMc+GJEl9LKjfYRNYie2
fvRx9JRD9yWlaZqvPqVQ4fuma465vlo5tEJ5kBRVZoEE6r0n96nHkuUlwNvMUwkUzIOUOGVVQ3YJ
8IQkC+IkFBAgF/yTcp/nolawPp3IZRFVKcr+6LFO+vi5gBsV6YIDcJG6LG5+gk0OV3J4TQEiWPfW
COf4REN79UWC+z1x86sTQL5qV2gHMQOjPCXZ/4kQw8E0qltdKUFs2v1UJW6WWD2RF4D/FS5gvsgr
V99+d7AvQF56p/Vcxa7vt6kNI1ojBbe1Aa0S7RMxHz7LikQk1qUMPH6ZhWT7WrqQT+p3x1aQEQb7
ANxqRWM6HEac6cTu2dSdt2HtCwYbgP8H8LOuPuXVJBiJVBukzrYn/lXKhcudVmVBadffhDtNgWnH
DxIqPg/GAHgXzqK5guIlqtm0a7ciMWHNzlLvZ5sCZ1GyapWXYAMW3nyrRbg0i6vSA6rGx9s2UeeG
16XbgUsXAtwLaIJ1dvRUp7QYGXJdZQODkxiHcJckEN3hrCZqA8qo12GDG9YKxX2GAB9e/Kh0nQUO
4Up2HXuwxXtyhwHEt94r8gA+/U2uvgz62mrS97StZ1OehoIvt+f0NuGT5av3zMNvhH7qNVGiutHT
w93dMejXW+Idp9cESOwySQdyTxsx56wkKO+mEwlyEVHkFpzGv7oHRBesWkjJGQfKjQUKynsvqX4O
YR6uw8Y04nuybHDEfYqLG6y/F29D++ew6EfQ8ZDophWNqnJs2nY2f4zMCPux+ugovtl4MynafPmg
XkamuJ5+JkMNeDA394vI2oB8rXG8m1iIgm/S705ld1jPMzEhyLR6lbHK3eac0QQJgl15E0NK1a8h
k+au+Bw8Txhrjli0PwcnDaO8lO5Ia9X9bHSxFwcNmtaf9SEXd7QR42fiXxq4VZHIGtn/RTwsCNZX
cQA3xU63nNGn+HS0HRf0HvUCE+3OliMizFfHo41HnG0lUEAwdnqrCsp7qR3ceKBhJWa8fZgJsLjY
RRnZdVo8V3stN2ftFkEsPIvp90tsG0hmMAUfiz3/LPWWFd36WuFcJIzoL5LAyuV0ThW9rP96HDxO
libfHulzoeT2MUkE4x7YIXxIjv1kzkWtfsDu66UHRE22ML7zEsoxtmGPxGVucDMJIcdgynJatLb7
uwA6AhJAGrHae58T11y05+z+VWqFSiKLRI3RGfUqyGyKjYqnfJpEKifw6TQFUkFqT3WO8lftum2V
qxDNUJQEhjMopgGzfTD35GP6P8F7DjfDDiowVDyailkpAhWnuWPA+b1mlaDJBagjhEcnCQNOaMyR
7MmIm54GsXgLwcU9qFsRvFsJ1X36gX6k2ZOqGFqV0QECQ9gY7L1RYrAoQTxiA63LvAiuaL3GzsGF
gOw68EcK9fjFT3eJ+jP84tR4HsuFY+ih8QAACFZBm9RJ4Q8mUwURPCv//jhAABzvL2AC6CqawXFo
wpIgZJCM6XG+0Lo1MaH14SrBjAXbgJ+ZnhxWpRNxYHECMDfMIlTwW+hJgMxH25yfEi5HDq0qTYUg
ZJ1OF8T1PVjF01ClibiU3PZvExA0ixrhnlll82lYVrBQLSsH2eV4oiftaxQp7xpr20ubxv1hBZra
rrg7rODZeyofmIVeNBmqIgLUlOn97rwINoMJbVBPVkhlWfwlYmZDs7eswbPpg01Z84qXNKYFr+8L
A85dcU9NbdZOmXDfIdp/TQf8Zbcmta8M6hJIrwzNb+fOC7bP0qpDZ3UH7HXY6C1p8kkZFYSAEISO
U3GBQXWF8WFvrZD/i1GDwlf0+0uHoNoiX/HcxSZ2LdEOEf+xZkrBMQitZfl/af2UuoOD0M1pZVZ+
tfqO4Yzm5JQfthhCzD+057vqqokt4bWGAiMiD/Clony59G4rClhX1xr8nbsyRroEvmfZcFzuORX+
sVzfg7HQfl5ivpQoIkY2Yn9tcm7TBUw6sXZgzIQxAaV0z0z99602KrF6JTH4zVKwt3ZHWSirBeL3
NyaUXXrgPlK/rHxPv1AkGOyCjaXraUJKFwudr9jVc384IANu0OKaWkWXqv5VGUPB3+yfuGsHP854
QaAJ271HG1AtqbwSq18+BvDr4CWEsa4WztSLpxOyoDheH8H2btw+BgPqpUDvWCRVrFFi/L6e+RNS
ZU2nflBDHqD0Xh5T8AvE6B/53BVgq5Hw+4Ktpzd4WlvIHaZjcccmFLrEubl6SGyxmTMIBjRUrKPS
tPfg5eD8+UZvEA1YnMhdlGj+uEOdANVrEz3MbNyzUd3yGMezImYDxvgWhainXfihatmPdErHAGDG
45k/vY9K9R+A0JmxGXQmft7eTWOqbYBG2WcXQ3SzLPMbWIicO+ztMqQczlhyLFpFd+l6t0jCRFhy
TXMMBdd8NQm7Nw6EH0w5+//uG6BAtEkGL7bmHsxT3SXSNm1Y1JglPmIokfKzZULQKiKZqeeEFXg6
jrmK76b8kXT3enzfE9GiGK+aSgeG5AKj9jZM5ng4Egbiv2xH/r6l1XoIfr5vmotma1Cr9Slrnz4Q
RAStXJQ3x8BBVdoavEwzzCddhiKS+dbTVY4B7OBuZZuKKagY6AGvxRIjSvyOrnTOr0iILlxII4JF
SzlBdQEUkqxSoHYO3OFdLfNpZQ3W4UWvQgD9G7vEi3nBuV873oDxgAxHHjveeCsL4rWK6Gfemkuc
AZuyPQpJWRhE642CHyOzFDzkn9YAKzwORd1zHtKZlh0WdMzjjFw9uEeCS3qsV1LXNSHsCJ/x6h1n
KNpydqRmyNsRuw9n0zjzO4tOIXqEUeUYCjkM0flylzH6qKy4tThhGRjvuu5llIa5sd0fBTFtsApq
zZgceQgGNUWb7kRljnYwU1zwlTt8dYIiwGjFXyOuSBcn/VuHHH6lFMAnP+5naEEanw2CN5wDjo0b
ycjbHYilPgSY8r4KHpRGGwpQVc9W8ZPt4TBwYU8fK1SlL+lf0mIHybnr8IsQFmFJIkXOalrNqvAM
DeX1951U1lCBfVCLxZHcyLU05OLCiZMfZWEfP2JTpYW2ciBRyseSZFiM2nln2BsbfBkePHT0o/P5
w9MrM9/ZDwAVAkbe9yjQt7281+l0gB9o0xKRI9zKgJjZDNZxGqK3iGYrSdc9tsVD/Kf5Vj0ee4ft
e85ie5I9uLAvLh1CxH11pVz47ti95hcf9FZIzXmQvJic7eUGILV6xb4/5ya4mQSiL5VvrrP9yxrq
KHS6bfnx+jJe8K5scSeBvtEU1jGSkX6HavppT0aCNb6KEh9OzAHmnBUtSXSHsD+ZDae4qeP4VPNP
5haOfbo7AAAbVFYZ6rcdPAex+S1TAnWF+TKwUDz2NbwcRJJTnZCoeGAcztHilm3sK2K/sZgqD2VP
roLOGtSjuhYd7gnCA3dlF40wvVGZXxmqqoOwwsgQcX5XY5tjHzPE5Al+2zcrVR2C5tFhfMpZAT+a
7ajSmzSG464c7kMqZCkaz0bkLLCM0W1CytAnl4iP+pBlZmLzPkYYCp2ivnvxPMw9WB/LPownZU6j
yluVD8w/z8ZmA15kmCMh9XiPEFR57gaEYriyunYpkPFdH9dbgLLr512czvVsbid6SeQdN0q+ISnH
dxkkt0+XI5sT62mnLW0+GnHf299C2eAdDyuik+vXz3S3P3N36gpVukp41jy1xvuOzUY1I0iBhjv5
6uZaxtBFoZWKt9lwTEd8d9tIPbTM5VVd/xpMJui9NtEAy8VtHJPNjU/HsLn/QQDfPM3x1kjfcvxD
Ohjz6EJEKb78FqJZZPEBcvaSaQj0bqv9Yh8KBRB2exAQIEssZpuRI4Rbv8JPLZ8Y1F64aYn5eIUL
hG5EenY8e1/PzH3pjjI07F25kUtAK6DqEv7m5u4E3lF17wA92XE8KYztWHxspEjstAMzKpKyu/oV
6eJSG9jGv/BNVRGTpX83mN3Pne0y5JqwAoQLqP+ovxgTg5M8b24++3jehv1jXwrlH+FmOwfEsxDl
4J101eAoS5MiFl9JbbfvtdQcmn84Kz0VmIeTykxvAsx4bpWJwtFFTI9Fl3tWlEMyhbLLcS+lGqO5
Zwg/Em1/FONEtRtIZagnzuCKh3eOUzr1QdvjtBmP/dLzWudX+5OQ5xDEJO/FVSV5ApQIThkICODy
jG2IdCQVkyKVNjlP6Fl1Xufg+rqxjxPLrDieHAVvxY3OU1+Qn/VHKeolzUGMAOhQf3ULTVil8yNu
/AF6osXQwtNMR/U3sJLHG5uZJw6Isc80bfCyjsk/IaGJULNungcJEpdhjLvKBEkr+9vZHVeAAAAC
VQGf82pH/wACWja3nkh5VTAA/S8trYHSMHqdfCfBXGBdSp2bgJXdxNuh/Lis9McnLVpCPzO8mTeE
hdoQ5sG93tNTD6ph0hha4w87qqLIQDbcJKjTKsnECXyFQ+R0vP4zoK9j+7b8wMKzl8pz1Phb9w6M
YyScbr+DRXfC4cnXZfRzz3GGFYuSzKBmTJg9Ct46f0nNmWVPZx8zDp0J9vY48fh9SB9d1agw9hUH
E9k5qnb+LlPV/z+WKvHnYGkBhI0HUf06Hm7NEEbi0u3RHv1qQ7FkvSAPZdwXSPugWXHE6DnQVkOE
FWrIoSNn4VLlWKwC1PBDKMa3tIa9MUR4pwAXw19dfdM4ZOAcbz8ytW2c5h37L1pNJWZLMZo3lT4c
jyaGc1WOX3VL+GaIDNqVhpjtYP22FxZO09xSslzgLx4Q6tw1De+m3RrVnhPjeG2lJWk+MFCQwiwV
S4VruKkoq4WBPAMI7o4yK7DHaTU/eurNd/OmgAru6nP0vZdHUCoiXkiPr8HEDY6dfAF37QMqYVf0
VNAr29E0AQmUaY2mIEQ24OAW0BqU1bZ7KoYKklR5bItGKhnVAGqVtUp81MlyUKudBlfSB6+zYApa
wUcxrDKlQmxCxXVlAPQMCdVRbWjSXq4Mo0nt6DIWnciIDf1BZmc1LkDLr6nFWeHyBDT61zvcpBVY
F1rQTke/NYs855NCk19lUV74XNnbYljy2gIwEEqJnFpgxmWX1aH+ABlV8xGRHPw4EP8nrlfEmTj9
OZuTdMntjWiOAyqnU2UrIrLVkV6G6mRtZQ0GgAAACExBm/ZJ4Q8mUwU8K//+OEAAHPdn/m1kwAmH
Vj0mNvAU7Sb7UvVqnjUC0vxAMKn9FCNQA879C1aMiflC9DJbe/K4a4OHQOR/HMFo/TOySUj/LkHf
E7GJ5FVNpXFu/EDaiQ4JcqzJ06cP/42X+xcrKsDP0dOT0CKFc2rOa8SSqDwc1uxfT8aWGvsYp926
tnTTwb+g9Qscxj4MVbQ/2BQdXpwWswiJMRiQP4oPM+hHZWdUeh8d/lmlVk5OeJ4QmSy4tebw/rZq
CUErAQerCE0QCgjJW5v1xauE7RfMVi53M1ZntYV6FJLcBA7UETmawr4HbggIel7Rr5cSvFDNwgFv
UND/3ma/plItCpk7qfS7JNdGdme8Ahkk2DymoTwiQnkOv91zO/alOTLJovvD445wVNfLhdJXwuU9
yxwsN6vJSrWY1RA1/6RyKOKlvuK7f3ENKHjYZ/LsgcFLoRiGJgDzJDw7C/yI8uxXdLS1gmCIcdlr
l6lLMecKx20kOzf0SOJMJVByhjNZ4+92hMbt6rbqLHnq9VgbGtlck4zqxJiIDFdpFoIaUJrG4v7y
2iCvifbHhI+0GO5ZPBctFumxpUJVMCbzsvj2Zbx3fvviuMiA3uvJil7GHt2oo3mjznuBuvshqohn
eoR/tv8auL7T3Q5qZuMZdYgJAoTaZVcCLEC+yvLV9tajpBwNzbgF5j6Wknp220Ckf7Qo5/KhkQYC
yMCTdrm1nqNfJgEjQrCvKhTEanIsEpARJFyfjEmXiYtWa6cimi3snZ/Xew04rfgtgCFE4irpl702
kP2bF215Z6Rz3A9NxNhL0DqMqkr9z7GNsrRTp6wFcDvr3+N0H2aZxElRhwogFiUVRBsa5NweXOH1
wGwcAV+7K0lh+au12f8t7kHLp74Ko3GR9xdoKu5JsylJhX95XDbElrD9xkIdb+bN1HYdtkncWVIc
SWURWPUGg6h6jl/7N3E0tqu9qEqD9H0WW8CdH1LfgnDa/Il1SujjrwlG3+PfSTy2K8xFPWC8Sttt
jFqyLiO9/w9a6sKKVWhbevT7STUXp27wNClt+L1JECY6fXs/xo1dDLne4Ny9sJ7ERMVcbZx3LIGt
aWl6wrM0v+RH1qKDF+nj06alFMmHPVrWIrUdNQtnSCh1kELrfF+Mxc0EupgsaTrWvzFq8ppZomyv
2mJQo6B3kPyNoLqY8HXwZo+1D3ibJCs8ZhJzSY8AI+Vx39Hg6xs/E9tcGY3fMULGmO43nnks/V42
nwzpH0jprMhf/6l/0E2cCVwuVBj2kKjsJao4yJTnlS47x3BA4tC1b+eC9vjEhgErKBXlS9cP97VI
QqlDhmHY+mtf1KbcBfMHtxQ8xtilsatPHINMJW7Gc7xwww99Sos1YxieQ6/fu7wJtY+mYsU8GFin
YMfWBHTf+pQnqWlXhjEu8ThqVE3xzVN2+bSAA1nQUKmNbPnnLWvvIx9gXZAzjC+jYpTwWCsvpux2
39v58TobOrsK2EbyGoO3+kluk1e13PqU9AfVe6LWREhaMaUgkbRMX8iwZy0BdapTp8OMruEfi8DW
B/kZ54rYlRXWoI0h3MAWi0knlbWvZq0ZYdu0AJH8JmMoajgurIEGH2BiUO1JJcGbCjJQnwfJKKS8
8yJE2U1peuwcX+tEpmBq/83hq06qUQ8LdxGbW+FSrv28SIzCN7Q0smwfMoKmvlzln2h30WxhWUgM
NEgHufPkOxOpvp+VZ5tPSvYEXkqY7TrtcoBZdLfyVAzyeBhbduHHyjmSp0/v2GkuRhUR7DyrqXtE
nAON63oqGWv5HC77gDt4cC2+iDuozmhZCrjZSELzyzZCePe7AO2JVquQjrzXo10F1LhuOHR/wGvd
b3Vs+mYiQ1TtmziuN7+FI0URs66JOrSJn0xLUdRvn/uKnHUTvN8qdkiyoswpqxuojkFTyXFuu1K1
ThM26FvKu5t9VBJCfROjIFkBj+jfwO3aFL3DJh6c1JQAXz49sqe1bjgFZ6VCjPK1h5IUh3fPDOB+
EPXFhYdID5GTYUW6JSm2gBS9MHEjxfbKEsbVeC/qLW1m05EIiva3igqipIgn0FU2aBHlsmdZBOdP
PUeTPZQflex8JBtOlqX47gpbmGExEgUcDvBl7hGFNhJtYmjNUjCSTaiuALhh4JJJg9E3TMNfrIub
njRQvsNjDOxAHNW8C7ZpvqLaG1BdjB3pACfvwXKl2N0x5CAKLH1NbV66PcobvoLDLiEYccVgSMZm
pKkeAdXJxrT5sFfuVWS8O+Dx8DEGTt88y+09fKGhRehtvpPbMHPR31Fo1gKlFdfinAj56MyG3JuB
oWvJCDN63lICelyk+oet2IDMiTUDtFYeruM6o8QbbDYsX96WbyCtxk2Ony/obuLG/cJbWtdHJthN
y5wF2AOiDarVTpmE2b5SFQ9RgMAzeitz7Trtby4l6zvKa93genJxqun2YK+ELV0d1Ln3jkmq04PN
Gq+NsF6fKzFu1SjBOvkkSVbqbQmU1UVdMI+R9OLV/teDklrUcX3txtAxeSSsWsw4Qg3FA817YsVw
k4JIdb+F4gr/DL8C/YqHEDMS0h/VL8a3c9C0ahhnTq3St2tRLeNgN2/8U4kFMeKxWTiCamBGftN3
HeiuqfrbQp4OJxpcQ7AZhoeKhdMndt4w10e69CEeqr9FveuRJYWvWkfI4lWU/c+ATz9dqNHe+ULI
3o1LwxO2qM6cRrw8mnbKzLPEphU0kXHi2Pj3oOcaF+ocQgawHuT849TTsK9iijL6YBe+s7/qEFFQ
f4XEa2XPgpFx7oAF6tY26SGH2abq6UlUsmnEP7ZH8LbLXKyOnqrXF7NoymTcaSEAAAIsAZ4Vakf/
AAPJAMQDDiIASTUba2r2AhIw71M4mdh9WBwqKjUrKtQYuBUosX3GHAyOStBMZwD5KJ8hC/Gpqfs1
umtm0vTs35zbG5otHaCUh66MEA5GxKSSWqgegYQ2iv8JQh3kSf3Rx0cXvBKhv2QADd2tU6WDr43O
s7S3K84n+2hrGzrbagghqUk9P36+YwD+avHEuQhBI2lX+sa4PlfDbOkb+3a0wVL+22zCq91PtGfH
hUaw/AnjxkoH096ugnfTKI0PCIkQ8ljiJlGDQ4pw/WjT9U90N/Kk/zasXuXKWkgqHHeWHTTp0woK
4zuYrSSsmaYc0khNMoYioFwWmpH8fQxQiXFgZ5Yo3BHGyy6Faxxag+fmycYk6FXk6fzgka/5EIP3
nTP6mWNVOMCPKG2uujxz/MQGgu1bkkuuNiNCnhfgVS+6Bu7m1ObPQiD+HhGbbEaVeoFlmxp7k+M3
tscAlUafWZJXATth4qjT3wuC88+1IdVGvGMelgODvAxpP0VKs+730HMe3m3/aUZ+Dera/whMhKEw
Wzk+WwvpyI3atBHYx4aMojHOgdu4nHzY0EMLlGAh7xFVQHImPH4QFtNEkZM5uhlShA9Km1Ha3rOu
PmGi0kp26F6Y7Se5jScT1N+M+FZVW4Q+7LuGayCycQggJMWJOKhEv3YkFFTEZTJSrqyOlw91iidh
K+aH5oFgDNofuQ8IWwoeqCa5RBkM0HK8OXKZnygOJ4hGrc9agAAACH9BmhhJ4Q8mUwU8K//+OEAA
L+Hp/dJYwAg+KuMVQa7FWvv3HKELq1RS/5u7YurEOTPUXAvhsqvTamLm/A3jaFDUNMrRIyO89tW9
f1enUDVieZi/gB/OeILS5Ntu4KjCO/5t7lyHTsSLsp2F/o0zvcc/ArGERQTgkYaCr4TWC+jMoPXn
r5yZrQMoG7jJnArQtpzrn5JjeCzBdB4TVQ+iDOZmkfEqo9L2BrB7RoKMmWwygQWOH5mm5MewlqWW
qGG9UEI6NGL75CANr6+TynPWfSxQdSm4xPxg3IE835/BCFVmbLakGZXivja0MrQitp3jQDF7+I06
iPNY0c22cEj6oFo173E/dQANa/M4Cfr6Z3YcmoCPI/NnBc4ITNJgJ3PjMFlrAV93TmXeRcCTWtLT
C/kG9WCDhcC9aq3mxMzREGONp6gJx5uiaJABlXZVPHZ4s0DZMUM8nY3r1S82b8A++CjA2r6mVegc
IXanqDzwQ+WXqma9HAWJcLg3iGvKw0qyKLa0PH7cS4jkhQgWqC+dsI7O272g0lRIxgkJXRdl0QMU
NH841AQpJo1SBcMucpaqEqTV4ZDHMWKYmSJjeGe144sgFYsg/zulGxHxe+LxfkCRHACU8ZGVsdCm
24e8mAz7PW92jd0FXQD3KabYLj9OW6Md821iMjtZu1to4mLoxcS5RwbbQpbhsH66L00S9cHz2kDD
K+zY7DG6lNCVjpaUxCL9gFYnv3ZBqNnEzn3JzzDjhtHJeYfCQ7vEEChIau/s1rwMLKoticYi+AA0
dWhTps+oix9X722X6Kg4dMTI0ObBpgMEzWKaXYSpFXqGl7xIROP4r+wysuUDKjg+NAnHIg9m6Abn
FpPjfDPZ7GbpYHqbUBKE18di04/G3+gteKw+j3GV0pltrKGUeGoyTfl4/FxZ+PQk8/l6ZobBA3Sl
VupBNDQNeq8Zwk/tlTaMYkwpLlfNIV0J4UgkE8h20ikVOrau0RFugpFfi6GPMBXfukAUVDOSN5Yd
hGkuUzs6NB3IflqebnF0faiHr42cjUtkyqrWJve6k71gk1yMJ9Eo1SvUCqGlgwJlCdKzBuZyuXGw
HVMEWCazqMRASyBVbfcw7KZY/qoZ8WK48JLsDMOtjMd6CTfFEX6CYtTXSkNTkSuSRmpaL5RfBp+v
m6bjcAPCYE/Q5XWQWdP6xTOEkGRXhJH27mCiuw7GZ2w4t0lV/bsuqp1olZfCR8oZItQSHRJOhK4p
3McbTlXkVLVV9vA5f+ZyviA27F32I2PsFLP0RRiZsTdQ8WpStdeIvE11snMCOLcTOf/ZBRO4Bw0x
b+FNZQPLkpJujKhtYIu7h0k54B3DthN1HAVa3qt0NadTBLYYg4X4pm3wfHjysaxgdmL1dPLtL3Wi
WuYkwGpK94LmRgbySwghRFu66ErnQ55Ui0s5BDoOLHiFiZ4Kwth4B9Nm9q6Zg6lUBuJvP3cz/MFj
NIJrcxD48AASdK80dzRcOn/0kN+YsmNRep9oWPzwaI76906G/mSTRo0D9+ydSzpsW8Z39iBYA2a8
Jq2gTocTQABv89KVyql9MA13SdsG4poR8BqD18ri+iWUyf+XSTSuYNSmASStqdI/kZpMerPecTPc
brH5hVQpxIKCp8yXU/VrszcpdiNgptXjc5yNIWhCdXnj21599joxwA5BWoSb0fQkr5ovDOTUCJGy
tSuDT3hhuCC/7xIyhqNmZ0kQgGBtCwl4whQ0c/0kzqWE9pOmxApWYxIppVqW4GgAOx/pAVEyC0Ow
aRLxdlAOhCmALsN7OxVqxW+6eWz6kpFrBwuvtZsE/UrHWHvm9ji1lYblvlspYPLCELLjcQeriUa5
0tqgwMBy9etn/DjoSv92I+41FizL9IGnn9pNAyiCEkVTU0cs8eY43jT0zc8rpMRmOVFlKHbM4Iby
Uq9s7B2LcbEuTLH5hUIURfSeMV2ru01ynf8Fyk1cYHwApsfJbLyOhvsoftAHZk7CqzcTKZogyRDr
QbTEnXrq7ay/4VJQe0UVd1BM8BTiNFUzl4QsibqZ8xWZj3c2qJQxqdicXLVFMRYp1SbNGPGipi6H
iWX7R9NXurlSyPBWPJe3Yn+XCXGW79vP0Quext+fBS9xsoKuc2I1K/3Tgfp6pg+ObD/UfY5RwFWA
Bx58uHSmokieDk5ekTwhIyCZf5myONwdt+PxfInyY5iRDy4tXzRwGz4CfzWOzwGeaSxeICtXnDOw
j2J1rXifhr9Yha0Y3flJhLZGMwcXa9XqxxyS1X/aYIDKuotSyjbRU/zqpbUsGG6zqvNdG48QPOii
BVsCGbHisLfULnxw/b7svfRCK2Clds2nCDyTtnqbo59h8f/eERk1eg/887TbY6Ht0KAEg6dP1T6T
aiKitehtMLC+Qa2G24Ot0D08XiBaeMyy6e7XNx14Jwwt7vpILUjPtGcv+QMRXjFuNLLvLBiTSYon
Qq9SXf1kfbD6eqGFd8BtRRseUrVPhjoShsl0ELInUHEVYlKUo96zPxH2qMjb8OtKak5t4d1Ojb+a
29MMHVo1X8CEUfcM3GG+eSvXjtbmiq6jxpNgoZx93ceTfw02kmKcZqq3/Lg55eVwa75B9wJzkCjK
son7c20avmIxaWXPvgchF5ucC6w6+sEd04EoKYgydKEmuCU1YJllMT1m8HQXXC8mH9Mm3wgPCcQs
eTcaXRj04mXALspUvPQ9Kd6A8j0vKke8RiV1LxJMp8ynZ7nfrJfrqNJfmjciOHLHs4OXSH8aVe4O
VDMr3YQFwXarqh7ZdNvSVshEyvW71ku3xtguF+llfKPUTJi2/sYnJhT4GCuG7Qs3rlCxGUaNnbJV
aAoo0/Qb1eCaVVqDVbqaHwubo38UANu1DdqWIHJ6vaf7xyxLei9XRwlpQOqP9mFtGqEAAAIhAZ43
akf/AAZKbCoAN12XIxcjGAkzvK/aEllPfKTCF6OBAVw740YACDRwA51bNGQp4zYeRUOYh+j6uWvy
II2/GaS7c/jQaJpIlr65MC9DPODB25NPth4/P9jnOU2rj3vlPChSwQxE8rTusFS8vI0relRikBIN
gh7dXX1Tsr5yQEkIeUGNkX8AcaYpuuPuebfZAnivBQ/fut9IgA/63dr+hCMWXldv6J0FHfox5hec
Jrs5jla6TGDuRvPK18dTOoWLNbbmObt1O5YhaZA/4ZjekVMIrMrdKqTPR9fEgEivARdcvk5mXXVB
njiLapt6COiyJUb3Z5b9z+t2CUV42xpdsUgylb1ZpKF45ECdD+EThuykLP9/irs1idX16B8hj4+2
aKm9A/xxouNnvrkfOW8sNa7Dg6P0ai1OrPvh6qMEn8v5HDOSE/ZPkcahb+DbsEtGH+UP4K7iQ1D4
IAeJrR5wwR1KXwl5MxtKTKHlf6Eek+eR+uKQbxpGJ1BV2E6S3INkiHCwU+YSCsRDyQ/5zDshhmNm
tZ8FDEi7E9+0gGdQa9kTFjvU2yKGtaskNIazy/OeQlUECo/wTKJXBRm8GeFeJn/OeBi09In4rTYC
5jFTGsYMshFsQ7GKJfufLy/lZ5XLk+6BgxRdXsiWk6GPOG7dNZXwfWWJ7OkjvzL4cRFxBCmW3ge9
Q8iCY15BGSwS6D3PUpbBQVBYEz/WB6d3TsP/60EAAAesQZo6SeEPJlMFPCv//jhAAE2VopE4eACA
r2nk6dhPCax63rfIq9XiuNr1QjnYwJiT3Aje8Xxij28Ly/8gR4UIgb0YcyMClVd0YIFPGQIOETK9
QXSep8sno6oqDkIISVwGyqxjyJq8vlAFQcS4tD7Gjj0Ym3+4JwxFVscrMH7kj9k6sfNf5I/y/gC0
Wv2PsPnWHG1jwtpJU+6w2lR1XltQAWcUtRag05zsXy3Mde+9oxqtCQzTHw6XADHUPxGvXjrZLDZo
8tm9AqpOUEEGQfbRRTio7zaqYQiAzdEoxakyb1piTdLLmNVlcsF1xq+0NvYgPpnVD7WvzQnHgzCw
dc7qI0S9fpL3rsswe54DSlqG5VOEmsUWdc8zPhPBT9LMgrfU+Mwh8Z7BfnzsQA9h+a9INncuvnOD
JNVuLkUTXbmqymIlFRgta1j7LzfKhD0X29dE7+OjT4Uctm1zXtVkiyJEcvUCzY6OTO2Tji0vAOg4
x/QROZcFVr0r/3mdVpWsPK7e3woJlTqQ7fOwam+Xa4LxJZZJWniCJ9R143cyRH786cLnmgh9Zjph
vVzoh47qFiCn6vCll5AIBk5ieElChOstkzHCXo4UIFw6tuh/LEhwMFXJJipoR6k3N/aE8Ei9n85b
U5BRSZ8gmFl16fK+Y/o9DWRn0EKhNXHZoqmd6pCaSCqqVQYBBmWc27wJ8B0w6Hsg9ProHUQJ4a4+
Q+TKP9l9KSKrm9hGY2SGWd44xHSW09VrMz1YHXS3ejyOgYWp3cREEdr5B/FJMHgk2qn1PH4zhD0x
G4CVJwG0JI/4xJQ4uq9NAnfaQvxsqe2Bv9HNKno6x8Zi6uXyKhaFsGdhL6reJm1glfE5ltoAPNPO
7Hk+17qPWko3fzMIcK1YSOMNoVq0FQAk9xDh1BC4GTHW1A5mo2kSE5Ag/zUA5aHtq6FEIW+ulX2A
0OpAiWocRfpQVvuMbVX5u2J2aFb1tMLSobSn9Aiq1hm2K66A7xcxBl4hNU9sAQNT8UCIOCLp9qAv
IvCOM6LC/Tn8/diAOd/FStD7NClzitXHzfccKMGIwD+xS8g1KP90L6PN76nF+I32k3wzofp73DEb
7liPr6a8G+4eU6WepOn4vbtNdJ7jWdTA5+dZ4rE3blV7zKsLnsBIOGlhZu8bh9vlbDxoCVxuJOON
QdqUp3ytp/UFdbwmazvy3ykmQma+q9r28i5IzcwjSLRqT29eUsx1aDafCXlhlFpM8iGV83CEnGvm
bFBnQOg8hM2PRreewrLrn0qhYk/R7aK90cANn+aqTKlflAN8D3p1XXQ34c/iUHqbewEKO/Svqgfn
B0+BNSRlybIpNqTJEGolHVvzS/YBnJK6iWr/0nplDl/10hWWYcaFU+qadTHql2sZgNXMGPIpkyKg
6QSfhUYK8xRCqGtQLQhJwVrO5HMu/P50qv5IY2qvx28lnXQrIuP9dmZBrbPKPDZJ9Z9O5p7TKeMs
DP8AL/7afpm4d8RUdoHk5HEYz3L0voINV5Mk9phSmCqa6A0jltvSuriR42yRLMbfw5J7ZxyvUCEF
QCFs47YKNuBr/T4Hpom4RqJoIj5ciGgs7lKaOA7AySjauKjETXR5JlQTPRhiyX+F428LgBJljzAT
PbnEpwkYHgdFMpR201qhvqS2UaV62c4HuIxyFLa70tnTMEzhq9F6I0yCvv8vmj0nHSElEmqfNtu7
TPfFBJyvDtk6RKPGQAI0SUYwQOcf7XdiNHO1FmLGsylu/FXjruyJpHDUJqOHRU+BFqkQ8Aa1Aocm
t3JXlVqCtcXvd45BBos0BvlH7nzeobKRZXCNIVadqR/nomEz4YaIXTDbPRCZMOjBDCESqLbZ3WI4
SRxU8ICKctoY3Viyda8N5zb56w0IaYbEusN42VlS+FjC1gy0WFHqwIOBce0C/Ay2GNPmu3BLp0IE
uXOwFHlIei4rj0SwjP6PnJwkmZRFHabXWuNitLJUgB0QZq1zxPUOjuvsiPPnxUKvGK/MqyHAHk2/
i0vHXiQCKSwgSbvjKUTwTOkwF9YCt7/zV1FbvoGAxIC89bQcVQ0l4GtAs32CH8GvOIoi3gw/Q4SL
GMjctFIYXuMAR9G/JQXfKg+HI/vAfqOxfcPjjACFSLQjoEN5jRwrAMy5jZusfxIsPLoY3lPZCpRP
m8mLXurY6rmudh7+uw8hiuJoKTSddc7UM9qZKxXmjkzwy9Geyq9yZ1fjdK3sdyrKDrBVhcyOSfZ+
XyyuFYngDV/hbPWwV7PI+AsaW3perziQjmAwztuoo9s1Ks8SwBa8xO171H9UtaVuHl6CG0++U5lK
4T+xdqFwqhq2npW4oC7aW5XMhaBB25w2GD/YqQPZzffGlasLNP4AsAL2s18TNtEKAtNGeYMhrL+G
EaWMnm6n/7Fy7GvBuKO8Or21o9CjqQcPRaiRNYQ6QPSKhoZM/8vOxUQWLCXhzGj5imLsMloIo5xQ
ZDIC6am56DMnmldMs8/za7V7+hkll0Di1EqbNPSrLm2I5jrSvJwjywOnSI8kI+udgWQhUxRe6bVf
VZdaVMH11qZfWfab6IEx0EdV7QsBhStNzjA4KEtf6zFL3Z4v5ajrgImZkIn6SxaMESc0euPxfN7z
z2wAAAIwAZ5Zakf/AAo+a/Wx43/YACFCq8pydlwv+vLWv1LRWOMsvULr4l4VwYHMhYNOMcOF8j8z
78tWSt37DY2lNP7CSMJZKYjacxto1XjkOnz1wgZhbsxbzpzUlLUEgdduRVhGO4nEher6EqFxaUmC
KyoXi7HugmFJi5FTUUYTeL5mw5f7F2sXgNhU7bqNwJDUHquH0qUlcAljDx6zF4ZK9gU05ILkvcYX
2GdDV9vyT6w5zmJxNlHWLxmSsmNjJRXHdK/qcjWDGaURZKBdvgyCFp0FH9YpoKKwF97gUROd6yIG
W/xtta1kG0kWPM2u0CSIpsR55QbNPINydyV1mFR0Xt5h97yyzfzQ0dL0nx9Pwg0xbbWR/6ihwx0F
b6ExMYW51ZYSsNz2E4pAa8mHyBjlQISHUk0IJqDSv0k9bBUz8L8PxVKxa0nygCrvGT4vjKKfa16B
zVS/61rcOAwFPNIkBWj3UqZqVGa8eP+eH7j1xzSssWGzT1+OnC1OvlWC6EnO0if4vQZVX7fwOFCd
n+rpOAO6/n6Ui0o4aFu2e5xIuJKJ68ES2bi+Jm5ErslCQaIx2fPAqM0Duv0yO2It0KGi0Z2aPrY8
xzIbL9TSOyVrEKc6MjDYkPRNGRBY7j/qIF66gevXDTdBsWA0HvwAJGwCUpdGxZLy0oMiRIc9VtU1
VCDEUMi/QbLJtujdlJ3iODbMl5X6fdGroh0OguGe3mxYtPUfrJdmRJhSzvbX88NtShWSI1cAAAYT
QZpbSeEPJlMCF//+jLAAFCVivcmuNgBa0B8nsaZN2yFAcB2QqHYrw90XVliLBNSL6bAWpUVHBZzV
H0O4tlDQgfV6Mv09nv9HT7pMqPQ49q476PBXnZRuYyZYv25I/OivcNqj5gWGgWYXXl2+f3EmY5zx
WEc8a1DjwE/cAP7LY94bbFjSl0vTR4VWTD4gzcbix0MFt16YXSq0DIiyVXSXnGdb7zfjGGXJ2Xy3
gh/r9Dnr/3wqVatzNVJuTzuOsE7cnjbRJcVsY/H+aZ0C8wm0zSbsVdROt8hZ6KG46qHasBzNKdre
dxF3aQOQLhN6XpE4XREKRAZgO++3CHA643/AZQVWLigS1ZwMBpvPjjo9Nh9VGsVbWbGYHSZc9iqC
jAErUfKXzPAh7rLcR12LQ/+jI1cFYJ6x4QTm65+svw7x2REiRu6ELHPE4IRqY17K7MfbCR6k/u0P
mDDr3vf9mwG7uQbSWD90AVtJuMVCltd+atABxIWpo2UOvKlSp7An3Vq77W8OV49kZ7DJm2aj73uM
3cg52vK+bNghiQsUbRYT44XyfZNPA1bUY6miZMloQWqilFUlMz2mACqNYtOb3sGhXJVnrEX7bs7/
VSxUCaPxkT0En/unj14J8Qry8UU8KcTYImcO1UVU8QqwEwYgUqDUFm+ir9Rrsy33M+GkULsrycfc
KBhQrpQvFf1ElmETcKQn7uCClAcNkSQFSdBR/yp2rTDPcjSe/+FEVxl7NGgl2ruES/DdoqF5eUYd
6Kz8OYyeHacxRSdmcGTVZ+SbAj/8vPGO3r5MkmfAWgIvVb5kxNRY1EE21n0wm0LATIs9ejh5elXg
H8ldNDI8u4I8SdNQ/bKw/m4GfIaI0f6MCe+hSAVRL9yMXVEsBB7B8WpCE3UQ9KR29hPx1rqK1iqw
ifxmG8Gny4DTTGs/OnxbcvAx8L4FcjTQ+3eb6bwta1UmsNhEFaDU4ArA323Uh/2N5L+zFe/+sM08
vY4+mfgOcRPM/vOuJyYl2mwNd+JYygoxwXT+zCHWmowZ6em1LHliR1J1Z1pRhJbcmpaBdmwzWWFs
cCoAXyd/EaiikHeA3ivi7afot4AviGNsjNgJBvaJKNZEqsIR6NJ5g2vt+0NUbi89djZAHW5MJwjs
JFC519akbo+xSqlWWDF4AoJrtBPF+xWjHt12uNui6ouzuZmRDNYb2V9CvVzidg3ozRC5E5MuQG9c
09IaMRIllzOF+QJlKxNVb+WhwXft1o7UDvfDFeqDme2ef26Clsf6lF6vW2axPKye6vgCATWBLuPL
WsynrrA6l8S3CAJ53DGtOH7NIcgKioo6vWtbzzOfP03N9sRebd8ILpN6zeQVJO5zlTZ21yrn6O4V
v8KaW0ht1xp/XTdKblhPAfAvknbsxRxsbdEWEWdCbWKAo3kRjISPQ1o6sKBjEWu6KncmPdbA1nUP
Hh6xOoxy4Rl7hmcByPw/PAK7SjrF2ZPOB8mQAPuRMjcKwwWdiE3liDIsBev21wfAxr7pimH9sCXE
JZZc6UB1l6iA8AvtXtIBgmAnZx92wPOQvZzYNcypwArtI9fVFMOU/tqWqEBpghEFAUzbTydlI73o
Bpj7jvLL3NDyyho9PKjdQKwHQmnBM+FRPyv211WAj+EKhQ90esf8p4YXP1iLISYeZi6I3FdH9KW2
4hDbyuBHI8FdGBjt3D9DPImQmwQ37NbZWUCWeC6yYynJx3Jz9Dw9ytweYkFL0mnx9g5iOhQCWW3C
IN0siWdD3XdNYt70gSIOsKFgYBK5ABrjppgqwQ/8FtuXyJiTaaWPHzj9khOu+pV+U25Ol1qNjYcc
28wbs0Sy7PhGO8pIPXViNH1yQw1cCnaSwDoTmv5I9OYQ6KS4NxUpMbzPRYCMQ9cqRKS0L/Az6jQb
LyTC01WDhZdcI4unDle9CyTWp7U9cQ2ngewOUyILWwEG9on6B9Nxa2sM3geQ5gH4ttJFBZNaFu+d
gsRIFSTkno5OS4x012zdrR99DDSLc7CaNrDIVnc5/CKdUxStBX1Pkxu14fH896cTmuSZ73sOPa6o
cxOTlPoyDxG2LxUxrJbVRgAAB+JBmn1J4Q8mUwURPC///oywACAD3IAWs9b4Fl3fyDyv0ovD7ich
W5XuVu4gFh7By2zFGxJyccPuXZKe7pmGoIxxUP3XXwaYeUHhRFE6HeFo6HdKjHgXW2d16rX1yvSV
zZu0s0h/hOS1eIK/pTi0E8Iea3v880VRxn/BZ8DCq/0Nf+KK530cyYh3Ndd5enKtR5ynTfE6i0zC
XWCSkXVZWznkXAxbCJbUvooAsBj2bue+YVBwZdqtAlfU5nWFKfUIx3O+h+Jt/LoHOvC1bW1V9L3f
9BQwcSEbF6XBqctBuZt+ao2wFv9VU2Y/a8JJU+0xebN+ClB6ZecXQjRWwCksj+f2L0BdzWwBSKLy
8jlStj/TDYOZ7wUFRHcGvCan//E91ONDIH26OAevkFOsUt4te9fQKET+AGJYKFlanrlJhg5ms3yt
IcTQxBJ3/S2B2cWcHL73i8jYBvPGCuDOVNzcCSC8cpdGq7Lhfh5WdwGExqKsQLvV7by8K1+iMcBA
kHr9II/pgzaH7Rb3MO4IDjGcuMQuHzczVqFd/oPg7Lh3WWOLq2zIFL1p1sPjV+6mV80vXPKkCU/9
KlvlkV9N86348+Q1lPgLiwAYCrNDluyxZP4EZZKiMcLfA9jMzwqKSk4j3rmuBb7pEaXNYWZDs20D
UYR67OoFZ7S0/npD45LMwoC+zmq/R+MiTgy5V3hL/76PieaY1lvjdBBEUzQtRcQvnT2RgwX8NMk/
fthiCs5Fu6h7NdBZTHbeOJBCA5NrUVUPVyaMlPfOdeUi8MotVy3g8lcJrbBb6SPYthYC34uWz710
kY7PuNd5t9M5TvpljtqvkvuOPAioM56v4XpF0IW8UvgHAslnberTIK37QaMRmNaNCjMgwWSP4CGw
aLnFfPGgHKw27ebdmHu+fBwHhh6LkSi+X+6k1JjwHdOIs7ZOtSHfE9bwU0v+HdJiAPQxXzo3su8j
cz1Ji3PS3//RGXh90dGcvteVhFC+dHPK8z8daKkLuZRFs7chFdf9IwUhpnIkfmGmjU4zfxMKl4bY
ajwRhtg8XtKSsfM3bFxqmCcmR+pQkqYMGIWxmwdWrc7JUQarbLxlbXDIKBKG8GNm0tjVJUa60YLf
32K8aMia5FtMruDIqNXsGjtn0wzX1CJkPOzJv/MF7GQWyPu2EcM/nPjeVPUZOGXE59uuqFcpgxIo
zjMuk20nwNp+kYdthb10NnafB3yYvwq6IlAbFLTQ2eoNVww4PPlFRP98clQn0bmzeOPQKg5Xhyw3
SxUDL8TIXYvwEbbXELyOIDEuto7+liVoWYuQHl2jVmBp8+u+VZgJ8I3Zu1Ep2X/ec1gYyTW6Y04q
T8P2PiVORwv4ZQc85kHB9V1MNRdVxLIxKrtYxL8zDrjjZQVsj4yokDhzo8mFjFfeiaajYANt3vuC
iqElf5Hne0BelIgv/9rh+odBl3jdvmrwFSf22x5Ho4HFZOtm96LcS2+rl0eR2u+2Gi5SPVfnpVtC
eXJmz11OgWvR3t8Zm0V+vd3N/gRF+P5iEd2ft1cHcQFaVo6CNLloKXUT2RY6mBdYD6Y2vdn3JOD6
xu6rnXFz1QTHZUXUabSfFK+bECZpt/IYCrqS83uWjptETpwDNRBxcMnIM+UocQfPzOsSqKb3liuP
NYokZRgksA4PX2uuYYmc5ji7yxIWF02yyaR4pWXZhGE4dTerwRj/I17a1V14wFdSBKElNIfb9O7X
Vx1Lde/7cWNJsDCPAOBbFk/l48kyrmU2sWT43z+VOB3NzeLcSrItuaWSeKGPW3/O0ib/elg2fVlT
5Mcnih5jdGCyl76u6BishuSXiU+ynJ1SLw7kk3YqzDlKjIOQ0na/2RiuhUFGO0jcHo77UEoZuO6P
GCeuDUXC4LLkrbF18H56gRi4TcvvQ4byrVIpgrSIK+x+E7E/UuLhkedt3b6cDG5F/n/9kJeWkSfF
krEtmm3qsWcT91DdWOE+mnnomUeBtSI7xaxHGgSY6OqzDRKVCTB1L0tqOh23UkpAe02hLcoiYYqM
EGSpg1YiOI5LTToM6uEPUjuL+v5sFFUXuA2Xkv9bKAjTECB0iYMHd9oCMBourzQ+2uOLiYexzSeA
ohEKknGO4v2Lr+8D/CLJLZi7PJlK8G4p+KcA2pv0CnubSl3RAt0aZTjkrafuJQFPh5LtQPze6hpN
L6vBdp6KO6Sk+fSc+yNah/7bEPL6MIBI5ap3HCc77U3YgUoNbTcuLTKOUZDm2/ga2PaTxzZ/MAr7
9t2Y1mKXe/lQu4tNayt+EaNfxgXnKt8bnzqE+0z3u5ejryWTiVYx6g0A/nx7XajaIWwJniSuXTah
Sf7LJzFGDDsxlvX7DD+Mytf18Dn4pckmVV3uriW4g8n789qHJppsaQDkeYfvi6vbkZZuExM8Mi8w
2Ijg6aozuuBTaHpi/9uYxRIRzfFcPJBU4eofeX/rFaYIx3mN/jc/VELbQ3XDklYdS8FmB12iftLI
X1oorrvu25H46/cP9ZnA+S4CfrlkYYG4zrgDabMFXOZ54GjHBcYezqm7+J0UYIxKPNkgAMjM7tEY
olg2hGYje+0dOmjIykEX62GL7XujzVbfaLT8yC9O+wMvbl1BipsjyU5j2jp6XpmSQ/ockG3rfYpF
f7nGLoBks+EGhtKNKMyAcQpymnFqMNrV916JLBf8rqeiPeX0oqc2oL8G/QAAAg4BnpxqR/8AECWj
JE3nogi7GHdQAEi8oaRu9RGEBoMT2qNWasKetYZKgzeRgVDYstKxtJGWsKomV0lHAsPq7PpRFx5A
axBNIgHKNLrIzlmlByQI/SdKjoRWbYOUKGkrP1z5dJ4QewT/OaqF/VFkNMD1Pe5KjK4K+v8N4MoV
/ztmLR+syDBXc8gPDH8ASdGP/FE0IVpajz/QQJVKRS/wmeOcCUcdiort7MSYcc9BYWBqc0aV0slb
Fnc6BwWsBbaWHKRmCulqKYXsE888PqyCuoM75YNMW4YuExRrCyZeA8g5iyXddKWAoatCMnZMiI4/
1Flo/eWDp4OYKR3gQo0hONa5zJapdqK7Tep/TBZVP9d+5usKv92tLNgQlGVDCZ6fMtbjWYchU78A
XxrajEm5fAN7MIh5scJ7rqBRYiUqIud0NrryNKeCBzXJwXKb0W7U3zRzFN6bwSLUnVqqa7u2GGbt
QKSBNX1Nf9rEKr4WcjnMUzoESejGg/bGD8Uurgy7WPlMDDgoen5xSZOOM0w1Qyl6ee5I6eVIrN5p
gEYKh4zzDlnCFiWBivhaUiooDO1WAoqaJz2tlJ+sOz2vA8tVLGAECGrTVyzglsr+zwFbC6LOQaaN
vdH6jsfghKgfPCKfLAavWO8DCW2HfkYeziIl8STenRTBxtBc+ubBfwsnKl/m+SvLV5MTqXWHt3ta
T6WRAAAIEkGan0nhDyZTBTwv//6MsAAgBvtn8AJ3SjCJjVWarBpg8r+PAHfPyzMLIGU+1saJHM9p
DbRfYrYxfA3ySq0Bmn6UEzqwuLAY6pNZmNpi0eXsDn0Snebh7rE0AJJu53ZbXN0na4c//O1KPyVE
QYo2wGsIT5HEv8yFCGV7jCNtTR5gr56DNWUUEkDkOwK482ir/2Y5hgYMqvcONtFC0pl86sgh8JNw
I7hyLaodRO58wyWwnxVS3KlvGYFHMCUeL7GeHjqGNtSI+HOqMBZ0SVcAVpuKcl1wk67VeVJl6lzI
CkqJmrNVrBkBEwa0Ao9ZkwF6+FQyW5l1Ggkm627G2imVkX2ycVclT0n81elmlsGD11oA/Dspfp74
UsjJyU9Vda9yQ/mmN/enhbNuBLo5Xr3U6hdYugNlTHpwqQQ1Pc1Tl4mtN/QhixuLWTuRc/cD7/Ym
6gwSxW3tzoyvb2yxQoCVUGtCBJ3YZq95Lkk3cGTRnzeCRUwAD929PSZI6qam7Izb6y5UVpYEq7yV
zk+PlYRw7K2gz3q2Hpu/3KzJiqrmF2A5RyJsM9gjwgoQfd/5caDllDNoyl+pTwMsIshIx3AE4wWz
dneIXvScdO9fDBH++DAPdWSBf7j/yQQv6n9QpB5vLDdojJ6gpQJN+nhxf6VPi1nLzXGjSZi9s5Hj
oP4mrCz5L+OOvcc63MJJ3+wEVnubPD69loHkpTlT2G9P9iNAFhBCYv9yg6hRqn4gz1iLOW7Uvo8o
izyM7tfktDZCsVKzJLQkm44IzmQrVp+Oa92G6JeY7fldcOgnNAf2FXguKM/UdkAOwr/kyGAtExqK
ZY6tYPv5YCnLzhW7x+/2T0kEh5RBOeklx2DCTQDsJLRAzxnWKgldYnW1otSd4GHdxiQnf3a5maj8
V7/GDJnftVQvopHOpsehFj4Pux+DE3PHfQvS4HEcXu0sqD/5oskhZDnJpu6Df7S00GzFi0BmITsd
uwG74FYK5KVfj+Z0Vi6iF0fNK5ssdvHDfQtn07jqo55gQTNBB1fPViLfPxQXTy7zNtIidKRqK67h
lDPolTAdnzLc75W11RE5fEX1sNCoMtnztD/R+apO4L5KGSTd2dgkRemE6YYgurHlpwYBHvxHyyPD
1bw6kRZ/2wxNOEhB3Xq1+cC5gTUBL49MBGxNdrY5CbQkBeOTSB1UcDmZclzJBenoA88J923x7z+j
AvUAlgFKmHxzrTRvuzNhcrENhXHTEZFEa02MHeW9gMtydCfJr4WUGWWJ8DBGU0lX1hKVI7Aok2UF
yzjVroOgbYBjZJwJ45iOHki6bdSBM/r4tb9/RkrDgyH8J5Lbx5l4JrYUzAqlxkZbmEqGY3bbiIyH
vroECPjbXaCnLJoiE5/LTfOnvvsSB+6uXwLtJkJ2Faq59zQLTWAMJKZC7LVGMfg6KnXfSAt9vEld
adorqPCHOQQJmT4B9rMUNx+Xgt1ZUQDxTrVU7R1qVRB0c9MpxJDCYjGGGsQTVz73wiUVBXgBdRia
qUo4azjDySGZbBP/I+XMONr250y0iVeK7V5SCaAxuzHxxhNoRxWSOEXbxmNbxJa4MBprEQVTmzBp
jtFisu9MvFsZ0O9qCBkJp4MEn8FuwTUNwWk6PVv3UbVtVmpS2HokdFXuiEbsRB4SMHyUudiTj2yv
gSQuOFk1VpyRQHjlvPh8oBLt3ld5KS2ncApBcTPQNDZZpgsHwHMwwHxO79VXkf7/YVuAxlEeoZdn
Hwy1RMRhLsaTDc4s4yoCe6cy/3J3g1RZy2Hhah+/RLu6XsyqItvDxe7yXpniiULeIzLtcVqUDY5s
Wua+WCMxl9mj9OpiMhaLEMJId9giupVkiG9wjDdOqnHGNYsKGY+rNzdky9NSZ6oC+xmHgcvPrPR2
fjMiJQQ9VNrq/O0wKtfTJP5D5vjHcbmdfwTUY89dEzrnhKQCEiIEY8NPw0m7h7ooJJPq8GuPc3a5
m0KsmOtHDLxBmY5vEk5OvQyCTf/F/azKaB/jtl72hJRUZo8Im2dtmUGVsNvPzJRaYpcPRqld4lC3
8LaBN417+hr8iwPdx3tzOWMd24DP7EFxsxYqaqv7k/svQMDwc2b6plh6G+46U1rvoBnB6RJPbmW5
k6HTJ4WurGs0d0m5tf9TKNEA/VKALovwjYXkADXQ7uOUw3gh8ELdtCh3WQslMITpe3eNrEjfzOS/
Vu0Vkt/76d7CemZtLwGROiVuOZyH/ioemIaAWeCbNkmdfrfjGkyZQ2K8/y3lPpzfOzZbVh4H2+Cj
EC47f62JQ3/+K5x/OT1mK+KuepvDnICKPUFzUbEphf1Kb68EkVWlR+3gq8djHgF+Pgg6uJuoeK1A
CO7yZOGU5Q5tO7td9VESgVlmTPrgSwXsfEfp3LuEprIWsKpruWKRYMqlGJ6K765vYaa5wcHe0xQh
FQ4MgVdlrwmJiJnG4FJv7c2MGCzA3hZA1N9M04o13MXyXKzNHpCaxkdtUu0yR/fUdV/8FfDlRJIZ
qU79qqG3nnLuNtxkoxjGenu8NMJ+WXf/iXjWLwKKbbVouSPTTJ6+QLY9w0/H/5K+KjhuI3+wIu0o
rJhngMP/CgPwsmnnsycI8lLcNrdIHvxRKL0CeAIVerjSow/uX3QVaLjA9M5UG7FVK/patnF9Wfba
VzRgx0tPUU3xspEvXV7ypAlLC5XGZQ8xJk2wZa8XxtJO1XewiXWjuc0PB+VYb+QF5rd1F+IoYF1a
wZ6aObrrou+PBtIBlsjn+FaQ+P8sAAAChQGevmpH/wAQYPjxpnPUbgAAe+4cyJ6QOj/V9E4UvzOt
msOVgzn0GZppkI1JIrWETNNOseObJI1/tWQzMnZOt2itZnrSY/6ks3Zq0sEIIEP3pk8GO7MSMATe
QWn/MYNpsbPVeIY3SKPL1VA9Vd4lStpJjI9nR0N6JBSRuwSeEkjM3DUFr4hh3N8cUxVvlIb//aSR
Q89yfOsz0i1+UrW5wZ/qXt4jHT4vgfS0N4Bpd0k/uqI4s+p590tMVqASJQiH6+uI/J9hAgThej/+
wS7JmzxN+X94X95j1gz+4tZg/TRqKm+BbP/7TvrKj1gJeBj4g4sBgQT6Md7jqKAfCuST54BZvqEi
cKbjwImE+n0PQjZn5wxKomgKGhdZw2dlekuwXj6vBJ9bgL6xs9zuZw3w9eLMbg/QT6BdQiqHA3A+
g5P1n/nHT8JE/ZZzhOY/ue92ur6lHqeXXxOR2QCAg3g/yqWg0D95g0wcRimOsB1hpYof5mMhhF8w
3BX2vJ6ulCfElszttxEYxR822Mx4pm/G/8EXZiGzWFBPBqZYQ3Q42o1bwFK3ILkMZybIrCHaWdsA
QTjM0qeu0+NHskxQ5P59/1HxqDAgI0kcoRT3E3mBdUOW6tog78S5n6HVNyDx0CpMEWVnwJaxj2U3
AiAbyuqLtNb3WCBrWqenHQFjg6zJ24MBkVAtd8VCDwDWpk0usAiRnv4pPZ9YyGXpeSIqETLhzm5f
bcsa2R/nsH2sP5HjzCX2C7IyQs6ROr+UgWsiA08WxsoWGA6xluJYVDKH0e2NYQ/3IeAC2jUzLfjL
PzScTuF0VnoWsX2Ko0gbM+8+WU52jQNTdcFunVcOBVL17Y4/wQdadh/pfAAAB05BmqFJ4Q8mUwU8
L//+jLAAM893bACBcof2cSpZQvZvlqifMAzlHG+C0gLnHfdsJv+oMDXiSqi31LmrSB8XlHdrG8/e
AmBuRQtouO4e4b+YJM2RC8PcF2Ff/tR+vjL6dWyVWJQGOX+4dU9yV439Qm3eZPn2aQhIGkNikKty
oG1Zufr2Bi3T1XkFCAOWLPLN+dOADF7eFbjxY4bLxdyRfYaNQDVC0G1MqT5pWVCj0LbCLBiVB/js
wn1QUjoADt1J5X+oyQsWJMEL4OkyxoPOo0YVtx5PJibexd9qkIUsOtiotFWgNzFN1/n7KlF/4Krp
HH6pYY3QTZ2xgkCgfAJU+gVK2P+PbwaxS3tQTxRkYk8hOqtIiyD1CAyCkgIVU5QfdERwpceL3r+4
SEltfTB0qVdGha+C++IX/YlBKSLFI5bty1h3iiWOAQYU0+NpkAkI5c2WpTUa9y/KgmPX3IxI96YN
eozMngqXncgTJDPwN1JjyhOYsSTH3UF7ntwvHss/+u0fyRWaDwRodUYOcUiVcvH7vdkx+PxHM1N8
c6v6I9/FI1XkRE9Dm8dswLK6+IfkbxjPgCE+9eKnqnQVGL3r52zi6uPxcIFV6XEdTYlcsdOscqCf
0QjJ2JqGRXx5pXkc2FGv/MW4Az5HUlSzWjDstYtNW3N2d5MFs8/AyWmTKyfC+O52c70++dUPNMYz
YxJv0qw5ojz6KunmIAx7FRGhX1QYFMJqSAAG8d7vtj5yE14EzfG3e+JltiLBv1CsIWuKSOf6B0T5
NH3sf68mfnGABYynaUBY9rO97a2VtymiTC0sqf5n26mFEdZ5p8kDfj2Wwd7/e6LmXp5L8tsaKeLZ
dlQZL4gz0LpyywhbPkhxgYqWU0tfQTStzoH3skKy+/mkbbKTUKmc73WeGo1MIZS15oS2ABddKRI3
JM4hK7hnA428jBgK9zCZAoJ40sqPdhnVbtvkPqurPhUonrMs1TxV5EazWtlK4ATd2BgSFrvbdWeB
e0kAzeW8O3YLyaBCB3Kz/JXNxiKWC2JLQX1YqQlCVHEYNCC2W+6fvntUAJdvC6VyLmSERV0XfDHD
8IdLeKtqsGgurQGnC4B5P3lGlwVYgqaHUUspNa3J/DgxrQgh0e+qyUxxNF/nKbsQK6GlOhnC/sOv
kQqBp1ToMurkFuGbdagR1fu/S22S1LUXRi3P+Vrx6tyeftXOlT579fSOpGN9NU0ZhAT2rYUnoRrz
mlUEYSJfa0hqP62cKYr+Xj6Z7afGXWbxiQBbA0jCyf5ULtD6l9rLS8kurydBoAesSutUPPgQsyEP
8XJVpNAtTlxYwHI06u7rdjZtpRmi7olFvgYl4O8dG37ysfpp77DUde7YfZVyQ1s/0cOuaW/1vRXm
GsUo8U48qyet1K/CgHQ9KwMrXuT+cVM6uMGUUQ8JaAEFz4kbs8uh8XE2/4DwWe4mxtWtluufCWQa
3JTA/gZRuHpRWrjlmpO8Vl77BqLTq4wE58zl+o9bLuN+WBkzJrlSYmPc3SwYBvV06+S5dRcbhF0h
SCXgHHlSk3hj0QL6AsxFPFmgYEm4amXt2Y+L7HrSFd/2rGjX0K8GvQBIqCgM77RmOT5em8NgNVmJ
uwHRzD7qTKqbkGOahxW/JulNRa+OYbCuXgdbT1r2wzcE8FmHo43y06ikHhD0/GM9MCe8f/0Zo5sb
dOUq5BZbxZ7lbdaxq4A8OOihi+57UnQPbpEcuw0iOjlNxcnjF7WXzEaClLQzq8ujJQYlcj57uta0
d+k37j4jrjinGeeShWkncGwj6g4T2JuK4liYrv0w0jiL0mdE6XHDONPenIhaCj+PfWoTQs0CEP74
ljfph8+gK6DYKdnuME3ioEIK7TF4s/W9u0X73825ywKPw/b5KIYkW4UGAfVun6FzygvPwKgxY7IF
WllyFMiyK/FTYRHJAWpWoxPG3P799mR4uiB0XBnvphM8ffDDyk1QTtVcb5wGBLOvbFo8jkFx5PNJ
q+PtXrPjS0CFErNPtOuT5ZLTM5GlVCJmwCP42U4D47s3B27xl8sGkwt2vbUOGJ1d0cimKPMvqu20
MgkbIIldP9+PIVetDYnWQcOddClBNXiMyfSSCko6m0UHBJ3ZBla1o1iqfHmYPXobjSqgq91Wn2uW
3jDMyYZjbyPTVjZa2jA71CRDrbSA1PrOroxdLnmqnE86Joead7Xzd0ykOcEjmEqwsvsgJRox+Dnv
KLllIL3ZOfR1txTRhtX+sqWp1QM91MalW2WQ525AkeHapUBzVCjFdrqLKG+61CFfU7LrDmtCrpG8
900H5Bnu/ve5ZybPgUnk0tqvb0PTiuHSAGCOkq5U3wvaRkEdZ0RgC3UWvgbtwDaD7y86wcOBqyn2
sU5SpPtn15ma3/36TBC1ItQv57UFQPvNM06RNcIWnklUQajufoIMncwqfffgMsFVNtjihVHwl1PD
9rd700v44FgeRgXTgpa7UpfulGaLa5gm1oxryTHWKURf+cxxAAACDQGewGpH/wAbCSsl0ADif3n/
8iygqJihbk/CiEL/zHe2jYzeHnsb+8Db0MREatQk+ZWKJ/CmrwF7WCX1ttz4CvHjy3Ka0d7oWxzL
SQ91uO4otP+i7xA/KnYyHNixtPA3SFRsemlWHmIlNuOahcWPNsaKowGPcIzGAQg1ad6mEG9QFq6P
K7LH7eNiByBv6/K/bA3TMgyMPvaSRUott/hvrp0wRDHVdCRxRBQngCV4PgxEb1yvO6jwg5tIWLt4
pVonk0VTf+c8xSY2OLa0SZR5MDZcRvx7EkGgM7OF15dkN9chvRF61fJAa4cvgo9DwocOj7pV0ivA
k5X7faJ6pOcjUUzqLe43el59h9wiiK3HEiR16fg7jIg/tejXpJVuQBsxjDa1KXobIiHtncSAC5ef
WKmQpVUGAxNG8qUPjDvrfkMtPLp4czDJ0i0mhn+6XL/BWTUHLMdxRx8Tl1kCRiAH05CiS8f+YOGz
oSWDYH/GPjoZl2+pPUGx48QBSP/pTYg4+zBhzl0RSU9KumfGHbcUVt7JsAhRckj5qRUD5ssJZ5EW
OBaoKxOPfWkRSXWmA8HGbDoULDjf2FKa8Xa9pNcm6xfer31nD704SZjDiSNHNFKjqaLnH/QCFo0h
L8NAZy3thaiNXI7SFG4kVcqlmFZ0BOSVuV/8i0P1dKUa6pwuRhIAbNZfa+27qqf5WegOyAAABy5B
msNJ4Q8mUwU8L//+jLAANAuW+nLO9uwAg5tLozhay9qIRJz5k9JDadviQi7anW43lMWyVtM7qs+D
NL/6QwMFtNaCx8qCq2Ch/xyDclk3/PbUVpRNxHXuHK6OPlvvp90Q1ifpkV/YFOKXbPuaItT6/tO0
FmHMY6ZXg8lqQv62BsLE8JHunL79A0Gnx2yAdp6NH7hJ/kV0VVXjxMa0ebwMjvQkf7RPvujMgPJI
ZANP2udRBJMaMMslVXBBIVPNpEoZHpU0aJZK0BOCjShXMo98eXh8/GbE1q7GCOpZMj7fWfOJazq4
9Z8+1iETuuRdO+oH1Q+K2J+vC1f81yEK85rI3EEs0csF9oUQy+zNKrokFFrRsCoJyzy/Z+rSeagn
J7oKIHTSKtm4hEdB4wUzKL88Nj053HHW/LAxgnhQQXS45Uy1nC0Ik3xS1KkRoMIK4Z3Hd8jhTZOb
Btdk+iQZg/JrOkuEBHk3DCy6yTmKv1C0ChDWGEoJXRDcGFmHcnRAK2/PKZ1XCcT1wK4uRULsqfp3
I/+vFnNzGcuM/9BrHuob/NW2MYS/SWsTlydd6xLvK90ImrF3JK70dRI4GxxK2HCnHOl7AyfWCZJ+
810r+X2tNDQRW2GPnUvUmrQM4Em+Gq/FJJ5CnqcWU0VlEoApnANSpUezJq3bnFjLO7VwVD8Epv18
epZIrbkg2kAlHkG/ZwTliMzFIFcAtCBOE3+2453+q4za5yIkVQlOeO5v7wrH91F1Kf91UcBim+E/
7ixdJNBNKDVjCd+b/7qXIV5u03/5fYQZzqpuHbS3/U7HRQ6gSETLW6MLwF1wXpMVYZqmw2gOg8MQ
otff1LdnndZhwv0T5NZOgatYxFyjSvTzDGerzJRlUuj2GlRz8hcUjBEZwrgYXY2yJC4n3Lxu75uW
U3ohphsbS1vt2eUjIl5zfCiT4+R1DUhw+t4NHLDTDYsIaaEXrsgsswnALH8sLhRFQD7MKJg1oD6s
RpuZnVewx4WDqpFN04KfyaiLaOh0jxlmdm67qyMXkeaC10djV9VxG9B6edJTTk1b56GcjqHgLYV+
c+mSHbAVVxGMsqmFt+QWL2P/xql5gjBMFlmzINRX9u4M09iHyA1gsjT6gGqjQL20b4JpdagAzYYg
qqSX99iSXbswzhbRAQtbaaJl5e0ABdC3vh/NA0bTQwK1B5HEbWjzsOeAQHrjp9Pr7y/T5I9L4tnA
WI6UBDi/SedoXL05DerajDHj/mv/ntUeH0vqSEyDtVNriXeygor8xwgH1lfsrWqisUnqopSTZg4m
OQeYSbs8i0FV2siJAJ7J52iqxGTZz3JR8j3s4JDzLkkZLPEDlRMko0rhtWdSt+tMToYbhOBHeNqq
EL6lvm2a1Ay6+9i6hSvGMYvFzHnY8CI4Xy8RUncLubbfWZKhfR0ZeGcmPnBIl1UGy9U4D4X1l5Ey
cUkAFKlKPyIe2bwYZwDMYYgTaTtX8J/N1IAwYViuefD/8eDmS7V02MUWoAsj7OSFwK3tasFQum7a
pCdmYMNsaWorNMpHDYWIzJ5s/yeCDecUDYNfp5sT4GZFO5/wiY68dNNIgGgNVjbGONH0I07ISllP
iUorDoEN/Rd4yC8nRFdlhC30QviK0hQG+tev6TBZ4wnE99h5j8l65eVZ+XyQTNSK6DTlMlQHN05w
jRMdSoNvnMa58Jwbg0dwqjQwNv3TjtkGiTz25PyvlZ+GiQWemjmCg3jUrjJrnXz3T03skj2WFUC3
XD4LbGU7Twz5zZm2bvVYDyXxJZPQ9/bdVaxunnr286bq3/4rMH0urIbYENQ+zoJeEAyXJo+rPavX
NAC9LbQI3xPC/jr3V9b+f/KA0/c0BXVJ1IPukO8Req6WmMQqkxKB3jvmBoQsGOPrT1igU47f5iU0
fOarPz/BwoYCY8yagQqI90D+wgdUOvQUF5c6uOST4OeU1kcFF4NQ/O6ITARA9h7QVOluOzM3PKoJ
++pOu4btdU5ryVFuTQrYK0gn+SPJt70idme9JmSwEmX3SoPYaS4rPA1AZDg5P17yE5ADTmKqp4jn
chFpOwyu9t91I5/dOQirWM/lsCQy8WGHnLLLK9jnvlMk2BLAWUxhkz1y7qo7xHxiPb6+I9krn7fS
SgxtLgirpdvDBcq3sH5L98E8S2QxS1i4Crcu73c9MesAkpBZ+DnOrToHU87jm0oo9JIeKoRVeADk
aTeN54JKrsrdKsn/ftTkDqhzVq55iWPtey7S917Ccw0d/8In1Y4/iVjY6WgdbKIv1ZAeIJaaEZGJ
1Ty2ucTpjg/G2F84cphzP/QnKlmgwX72UlycT6k+9Q0hlYe6Yta0LPh1dBPJ6pewKDW1myjZ+vyU
a2bxILo/ZNCsToFAUyphqlPMCEiXHEBMwQKBlu1WtPM+OEgxLYrSKcSbA5PO/HVGREKXVly95hKu
UFxVbtUh1zLTV52HvQAAAmEBnuJqR/8AGw8bRk7KFS2e621EDBIAH3AJKKSM4/Q03IHtruewmKhW
zgxvjCU09uato8s9YUnNx+o3nP8qtm1mUnZ0Cy7FDL/88fBg2POhab90iR0Ibnt+kesTCM0BdeyD
PGge4EgTg9GTOSx36BwD7CmjW/bkIPeYKqksoKoyTtyJIqMYizkFZ3rDu6soYCqXo+tJ3CVB8sw2
rXKY5dWidXTYJ8oZs3nfK4BWPuLo/OR7f2a0gwF6mX87MxRONgyJIdIYVNIpoxGGoc/k/z8IsaPL
iCwenTAD0mKXUevhJwm4V8L7xAYDE/ldPShfdmfi96EPVjXhJcJL5y4E24/66+5lgDefd9U9C9TM
v5nUbIbtfLm5zwLdRGgr6o+msqxwLA7cjJ/Rg+dpBUilLEchAN+TOqFdAQ0wtbKmM/Nr25AswSCB
BvWrGjbAF86AQaX+veMNo/KvX47gyf4vsOh0UBJp5p4iqM6kXLPgDXoeRB0Qslnk2EhopOXqLwkN
tcDWs7QFq89djaUcUtnJfgii/TTmJT7ZFsdxB20vLoYP+gYRcv2RbTH2zIWmlXbKv4PJETQA+NSc
Et7iCKPIAFFR1peSnv7rfCd65R97TAZkCkYEXRhnAhvRAvViao0MMdLMPSwOcnOkn4AKqH6srY0H
qCOCQOvHr0+uj/Yr6WakG1zVo83mBz++eQyajBq+y0udcOlj4ker7Na2w2Kg18OHwQ5V6wl9sIzc
Ih9+eRgxPL3vpYp8cAqXq2uOQ7gUtktbbWhX0Z8EYELELE2WC+MDWVlvNiTNxGrQHWLVZxZIk8gA
AAgNQZrlSeEPJlMFPC///oywAFUO4SqsbYATLvDls6Z75kA71U6a7BwvgjlRbzSdzS8020MrAd7W
yDp3oYiQGMoJKBTCRtN4NN9noMK5je0M7DV6RbNMGXLzLf0cQeIG63Lh2zl4869KBmirwSCD5jed
uNfsjYllUecgDuzTsM94BlR4R92tPUUAtPpOsjXCAqCuaihtJx1XQN4oouKdN5opO4CuQv+xSVPF
l3oVyIDOGJVcUdaotRTrQdZANSndniIaOi2GGV8ttl/Mt1VmBqrjhXAyFF6sHYQSOwUWOP4vDhzy
BnofGYM84NucfSDAAjxqkEZdAkrrSzKx+EZV8nHqHm7t2PgnHL3IO2P/87fY3XQ6zPZJDbMQ/uKV
q4q9q8DHA25JWZb0TOjsPxEe+fLYDJBCFyzOux5IFK0OuNUa2k58fHaUe0YLdOdAglLEXhPAHboL
ctNjUdoce3cm69azN1Ow3m59dcCN5RK12aDIH1+Seo9TeJnBIpNkspgXPg4+smPQJJkAMWmzNP1l
osUYrx/+mR2Np3e1F0eUAiANjqOVXD19Vh2tTY71OHx4R8iiIIpZZYqhX3Qf+Z3fkHUNsCg4exuM
A79LhTAJiwvfhsa0CmDi39PClXSga3fOVVyXGGK1jMTwDQjK2sMJzuZEqGBq/40/uRzqBzphA6Za
ovc1mriPbnsFW2oYJtEHLYn1q4V3HvfgtJYJJ2QQFIEbglUwx381XTR4THH4AQBXmudwOBJhUOr0
UeCwHZLD4UpaRhNJBVFJz5wT2XG2B5j/Yr6bdWZjw/OSkU+30Tf7UTB+X8uUasLi0+bryXrEaUEA
DdiVA8tZvM+AU+lSfLVBzvOuz2+nEeUkK19Y2xJmbC2mmgfyacPWiyDL5xa0iWd3US4SsDVGEcab
2S7H8XoFR/mMtRfN3XnViE0d0vnUFCb4gbsgGMKn7+Kfed48BTOkfgLUS5AibjTzVyGJpDQ6Kw0t
Gs6eHP6LS9Hd8RzMtGsRr05CcK67HuM9PsPpRHkrAPgnYpEv/WXqB6L+UVH2LV8fdzqxGtCXsoXD
5A++DdznUNbqVKHswM/UlpCPeqibFaM/iDTQmfwmlvhA3Ha8Lm3LKHa4//cGqMeB34b1tlaQAbNj
CzJaAbq5QUmS5Jl02/yzkcsUOgCffjx/GS501Ycc2w8hMs0fmz9wEYgZFS4ZTsm8iNf6GFCUA3Bz
juFIca8sccOSPnlAWAAvuSpfffCr29Jz7OPM9oFBQWVAO2t/3dkLEy/GSB8FY226MX+InZ9dlHUo
+bK8Dh17xpJGyfeiF9UapfNv4qOP5eYTtOj+bL46DlhBoosCLqnQTTbc0YBZpbE1R4Md0M78JC3F
ldAom+qJUNJL98VY/xLNtNFwCt6488/40nxZHnHw3w9kd/I+GDl9sHmjZOXqcIbh81UYLeGkcCWT
UJfCkIQkiVl//48CeVEoUT8Kv8lC2xoXxGE8qelyNtMJs2026VSUrK+plZXyrDRuxmPfCHa51QNI
WhtaN5UfAOXZUgM5zRMUvK/Pc8S+6/SE+OLiadlWJPOsjb9WZxamxuoAqgT/PHRM3CmzTMoLfTqL
xv4yVvdLsjjeK7GbjeRA5dM3nyviRgMovd5T+klV96ceRI94x98ypXE84+T3JsG1jGEPCL0zv/x5
Qx9nvUsKbv+gHlz+J6Kzw74rfesClo3/O62X/Vl2aC7BYtdERaatuwsmRdoq5gVxvdASDQ7QvsuM
dnxD/jx6Zjc2oZRKH1+OKBSoEHdtvKqeDhw/jxcihTNymzsj9zKcbWcp48dfbj22cRHq4JE/Gxjz
SnWFv5mzde9JKWXHks3/TNwoUV7cOGxifyHGVu+qGNo/WykJV9wD313dYb44RLSCIdhrBPdcNtY6
vPRHKkHIygOUCApffrfyMZzMPdFVbqHTKEkv9S7nx1gp0IZGWxIikBnb4AXqAAtJOxSDv52gg+VD
/6EkhQMesoMepKH11e7mnhOvtAGv3LwSD+QxkZs1zOuu9ro0u3HQpe9fnWx8ie47d/h/Nzh7iVJW
m+HzmmYVPAb61xb8JYupoUt2M6I0I1O5NRHWeiygvip+RXwjiWhRHfR8rBD+8DE0DrLQqt7AM/iq
rKJnZJv0IeZeNoG1fN3YkVZ0eqFijW0YDmjjAh2DRWUzHDoKgPfHOjY41mFsKdL7Cga4vFzhXrDx
mLYhMCImElZul8pm0D7bVajoo5LLvEu56SfE+5WH7vzdqwfFVQr/EfI+xvCLBLxwbeZgM/nIPf3/
iGiATjm7pI8KPDg9Kgu83/k3A8uRd8eK5QvVv/VNFfsxCgezywLyHCVhitoPohq5wDy6PROPATwJ
ceMggc3IQTMIjC8khYiHeCZKH2iz/5byG+qJqmnO9uhT72W6OS6FR1WjjMX79oLNk9THz1jB22nE
i6kxu/LCsw7QbWHxPIiMW3rzHW9iHr0vynllKRDvqoNjRxJAvE/p4UrkEUmII3HxbGkOikBb8LFn
2EQcLraTq1VZULqb4cWgvgGFOUmJsPlZ5GoDFNBcb4dSJJunn60GU6NFiBBvVnKtOXF8fwV8S1tk
a+627VzANQV9AW/sYZ/xf0oZ8fyOdGtix8thbfpH0sQoDmavBoJWb1U/cZth0HzuKfoZUwH9ucx2
PFyYCMdMZZvZmfslGWpmBTtD5VGRm6XSVaUXVm7XLKGrawWheDbMVKOWwqLbE6/IOdrdPnxZFWz5
Bu3P4K3oTzffcyjxAAACMgGfBGpH/wAsWPPMjx1F0AC2I1FsTtSPw9V8ufo1jomlDAW2YjsY4qU+
lKvqAB4FJIK9t4yJhrxwVbY1EfRkPDDvcBpJy+jI/zU+JcEZ4DYJ17/SFy2UX26AAo7NjUV3+NPd
OfZzmK+8NhPn5LOJbkqNEJIi0oT3TSl84NPVA+v1+Q8aKoXGCUj51MO5ht9kgIrN+AXupuxsrWot
sW0bQZRowxYcHM08p4BDAe2fOWduXzBhMQbwT7DN5JwO3BD5hVGytUwoFeBG24cnj7A2GgT1sTS/
K/SVkHqf3RGbnkW7ZNjFrqa7AO8ZnRsfi+X/KeYWtlFZBuvbeGioRnzka1pQ27R6gncz74Hf9OpC
9t1zBrrquG1VVm/AE8cwHqMspWa4Iaiv9pbHM4l4D9wUrU7eQyu3CGRHw79h9uhNmrYJs+2DCMKv
prSRexK+ESuJ5uIYs7/sJjXdbrn4VguTxV8g82VJfq9zJ5C+TffY1eMca38MRBdrq360U3DEPddi
f7Qvt9azZpD74Q3TrVQwrnkL12koWBj+hk4xxQZ3B3BbVJHtHA/KCG+ZYzoXNNWPj+JO1LLV3S45
TznCbStI0Cc6rDsXiC3crWiX25xg5PC4Vc40I3/ZHEDvXGohY8XN3qPTLQ/dgj9ps9cakfkXNJ4l
iGQM/9pMYZvUYRGSfm1tn8wcIY+jwQ0nd0Ts7S+37uXXhZFOZBvDnwnK5VUEw1fumtlQnAsc8BQS
jv++iofVA1kAAAf6QZsHSeEPJlMFPC///oywAFSgpyqx97pet2AEwtD61gMQQXr5Zho9srP3zcGD
5VmmSVLmxS/ec41ecES0mbu3lK+eo+hn7AAODfdOoSqnWYqm+JTQhdO11hNwfh0YP8ukGeaweuqU
2byllcYSnxnZVWU0b4jhDCKsb986Q5U/rZYHEL3TT3H0xy4GZncApek5euKtxvpLHZsoV1h6DXAY
Lsd5Fai398RthxkkllLHj5Wkgl3FY6x8H0kq/YWOkKDkLK4O/dyoWxDJn4oqWrIk1kdxgBtT3REq
kgs1PKvgmWa1j+5Ax/vIUOOI9T1SDn9QpMj10rIa7QTKQQxj2jq3YKWp+se4HkA1vPimc2SVck7j
mQPYAK7XBsP7uHVekdiLH3vNJ6qjzIvxnyvuzcfskHvs6/1/PmBSgTLGyFPzQKAVMUnzluHrjFIF
ybY9UHzRxHcrV6eF9cpxER5ROxvbo73Be6vmmmQiOhVl3Q49niVGojC6TBKl7+97uDctnJZF0crq
xefrvb8MdJkCa2ZnU+qTpL4ybnvMjzA0CBMJd/nDUbykYAdZ/jMRM4dONwbIaDG0cW3xCzEzKEMQ
oZWzCNvDm492taPnvN8B9RKBcHTCu/ccQT7CAZ4I8guXkfU3OrmYVeeQlscnaLmk84Wv0U4yOkJI
Z/mXUACD/qjZetbgWXvXsOECDbKurLYurCgIMpqUC7xlGxMwdJgiWlYT3likbxIkwvQCz0vWMKPP
oci9eYvvni49V7LcC8GXajrbKdo3bVJj9t8qWPMsF/1tz5LGnnsa61e3RxkRUapnHReb1s0quYui
KZode688HsfJZMu+WfW+Tz3lVx4pjeWMTaQ5b/TehRrZIXuT97ShNg9EW222zlyQVkTHJeullbMi
+bay1JYdH7dt/SLSvNk3NuKRpfLjP2Fy6yGabhMDuhemSBKanOqe6p1zDlXKbwcmCAgD53jcLdh0
mN/ZF3clKEn1ngInietqz/sB38sFCa2Iuon7pKvukeB+G+1sEeLWl8lbGtbWzDyIIIAL4ugLTddd
bwdW29CAmMkkxEjQ2OA6R5a/2RNhxNavYuuHiwrTup5k+S5YAEWHIxaqXkg2BnI1ZKRfBSwO4+4y
zmSirqwruVqNR94EJTXISL5p1GCdXFTbf0W+KFXLoD+zQcqozue9gesf0yqDP43KX0eBtSI+rKHl
NVPjjTHvhznpbsQA3hkRclDZ48/BZ+VedzzjtzbqeIq3OluvMfK+W633/rX+fQHbaLFtHnacOqzU
kQ0t/vT9bBWQUXqW3BMNIive7fT27eKZC3fk3ZslPuOhk+acXXIekamgQsHKfdbcUYaHypP9zUtS
MvCLI7QzekLsjFCC6qpyExU51+1yKlEsEa4GgJ7Vxlq/6gWjY/41liKRvWuwcaiKUsNjlw/ZZmAA
9xfb36VII+z6uqPWBp+jLTCLTZM2zJIgUDwgc0qpDhHOAzr3jW52yKTg0LmNkdlAdVwR08RFEVTc
SaX0dfY0Lmfje1nsxxQaUHwrIa8mIPpKKumhkW99Yb6rVB+dej/ZPgR22psBBv+/Dtcb6LEH7NuQ
skbg8B1ubZy2pWU7i0GRtPatqZrKLvRZM1vE0IGC8WWCY73xkQx+8YRrPAFCl8BIyvoPdOjQ/3lH
gj4eS6cPHDAP2fJWRcPKeV4t2bqDSC7FZR06paL3C/3a7cHzZHX34IxkKCE4b6xnldz0wFyFTIy5
DO0BwRtx+1UYcPPhJUChUfo/85E3Ao2n+g7kbBTQqmPjHasHQuOIT8He6gaAlbu7NgK4kyv0sJy5
AbFOD/4m2kWOQxdjGDxNlPVvi+d0G4k1Y64bXqObe5zrlhiVwPDYWIO0j1gSp50mBdGyjO5hzm16
hKMj5pl2Yns709n8TLhfQc8ZwIIlYxUJktFQGmgEcG9ncqtHNawPNQA9bdL52cub+0ELR7BgNFF3
Njfhai2NCEoQxy3mEC2rjSkBqiADtB3ICk7H+hG7fV5cpyBqThkazUQYSX5m/3h3/VH1ARIzQkzg
Hg8oG2um3x6wjkCm+PtJe+9idNMGPUQ60kts5A3LANsM4yhLnYGMGkHJ/D3ZCWfGDAk0MrPlT8dE
WodkjjiIHzIsSiIHZ1MhPoSdjQvmESy8XYUjNSrXmjBX0a50m6dWJBeMOkkI0TsHRkYv/dQBa4ng
zml2I86i/nQKQsZPz43iYpmqlNzf4ySkADH4mInONogZWZ9gHMNWzqKm7VZpSVoLwnRi5yVCO6pj
VGl+1LbeIf8BPGAtfXzcrgLuPC1qyZfqSKZ3QfvFK9JHnWm69fCx/huV2Auu2QXfoCKB2dXtqE0D
z7oZ+kfs52Vkyd8Oy5YrlBflHxvKUe9/a4/l7mB0jvisrB6TxjfiUlcAXpajCvBHXP+IIEzaJU+z
rwDYLFdh3yHtsppuAsX+IQWPTcquTk49EK20eOJomuMI9eIadtBHiLtn2zTvYBPx9fC/RdPN7z/s
oSYCYXsmuqLizo5u8FmpqJcW8kLCpJAkMGZ9ByCBzeAnGMFPYrvKE56soxn89oyz9q0PV+JwG1HV
Vs+Mi7sX4CfxPR1uNsG/QLN7IItfHX5YYUax04CiN0nLqmDhUtJwa5T7rMwASowi96hpnnl2Qw7L
m7daTc2xJquhn8tjjOlZdjr26ilTiutMkz6bw5v4bJwukiDswi3O5E2Hg8tK5Tzemfxwn0knrYOL
0IEAAAJfAZ8makf/ACxj1KHROFYmYa1gAbSVZrIDRG257piHmHsvVarVfSk/W7zCVrg1lpot0q9R
aZXiH7FjK16pTRiSeYiVOxWbY+JtuLDLEdQ0HLC+CodYvxzINwZSdkkUY+Lqq/3MzV75Sw6+vMqi
O+LwafqoG6H7UlqimlMcrVx0JVLKAQnDA+Kmo3qNcupAJziWe/jTFQMErsSRQX6dYDHKSJr6nn4J
W0qkzH0sI8I/nw1ZjtdLiU4baLUR227vgdW1o4P7Qx2fRxBc8htDFbiSx2NiZ+ais8aa+qETE4iA
MGJ62HmE7mvWKbKxv5I8EA+o+xsDhuK90+2HWswEPwe/HBuaMa9jNN9RflK0aKAfEjP5dPZlWr8d
ejqFOz+WqYmI2J0LA9pZ0x+AdDRKfrtqMS/JuiTfjX1EsVI5yMNp74/aUQpTBUgRtIsG5ZAcqDZV
MTC2QN/qGKjgt56y0tEfLcvW05cYlkzb93M2adZlrIS8T1FSBbeJH7vDz6mLtlImu1gfZATHwLdK
1rRSpHbKevPe81vT+AL622fvrWxo56b1ENe3NkFrxBCXt0aV0ZVch0W3aAT4XErbyQYl7mHhyRVz
rjAhv3KJ0EnU9PrRh3R9fsXoQcLArNIT17p5Lm9QBMAkDafyz/zK588XrQLDeZANFfn2e6t6z/ZQ
cf8Sz6xC3+x73yDmQTV+Q660zUOuLAn+P0j462OWh9UEmPl5pdqucE0cEllkmTmf/OkfAptkwjIR
FxBv9AXAO7eOv9IpKlck1U+isiCfRI+darVZTMZVaeQ4FVlK3V3jlDBBBQAACfFBmytJ4Q8mUwIX
//6MsACI3tvpfNVRgAbRIbioEJW8jdppDQG6VGh9HYuZnAiMGUEk1kqMbzKi2RHzel8F8MjAgBEv
h3nHybl9hI2UlQSHa1iOkweoaUB40J9FmajroYB/TZtMlVFzA68fAHNjJxJEti1On+RntYEr1UZq
mz/XBucDJ/p23/J1g3sJmZx3NkBl0vwI6AUKGW5brecQVgRCgpXQ5vGxges+kGApEUl7m/5nK2yL
csuj8PoOKNphfOUCRc2KMtA4zOKNXW1aPxc+/RkzpS4lYKfkMprYivbvjR/E+kOqb5a5W2q28Nf3
eSmUJQ4sp81qu6sJ5RmBq4a8Ogj4+iEKiwDfztFbEMK79739QSSEvGWFIXrRHYVwewNcIiBZbSJN
tOU9SKus1SAYt/hglXXRzqeZOV1H6duyOLlOBFuLJvBihqWaPCwrV2tHAWP4Bvs4YzePIvHvHfyf
/efTY7TYk2FUgggnJem4mVh6fyopgqqKaosdkSxnqyGMYvsdDmgyWKci2ojLsNada72L09MwLyv4
b4bBEK3mI8tphSPjnRSDLDJNkspgXI9wIUE6kaXyWS4Yjs8wTzwVB7/2KVzl+wXcO6UMUhbLzWGV
kPoYy+tDYtoT6P0Wtlz86aHj5xeow3irvLM0QW2Sq65rkyPmkhUdoHK0LNGpHzfGMsENTJAE0+dG
XWtjrn3XCXSg3KcdnhG1WGBCRJ7ejN7IUPcD4TztjV6KL1Ffupm4689wAiqJOihtHbsyiQsaCGDX
yQbTqpm+uFQm/jB6DQwBd0/6Uoysj3qAF04HGdi1kooYzQI8wxft5QdoJvOW1kKqQwNhBym/tclL
AAdeaC6rsATbM+bg9XtKBuCvvyd8rqydfpWInRkRdjtOyX+ibym4KljFXixzqvi2Uim1FhnnFMsE
ERIr7qYpcFKqLSDhH+XTga5+2xJU2LQEqw5e2vPmPraXRnavO/sHKQDPUKCEKwzpV+9CKwfUcb+f
9uFisYf8EpXq2Ux4k7F/zuoHOnmAIYBVlZKjG0FSLbUMjCsjyfKQtWCxYfwNzUZKOB848QEGWtkf
sR+1btIf1HDItqBXvkZpo5QRQgjfuDSCZYiAnhHurgFUft4ZxwkjO8PyeKLK7SIpBnqjtAO46CZc
RPr3zy7f+i3ZfSxqrVm9SM6B8rOJKycOZhjUIc5EmZQPhdNK9V3+VjVTmcbtlE1mflWbh1TjNc/b
4q0gtupgxEvp0uGAkqEr9ugNZZs2tKUhxy2blzejrN3WLd35XrMauW3U+6lDpnbAqIBNSSkGEjwK
t07m68nccidSflWXEjAOm89iz8xrJf45z1f073uvC/78bihLmifOOamw5rGObw869B78y8F5x63M
yE2L0zkBlleCgrCPTsB2Wrz+EF/MzTl11FHmi56wKvLvBqAWHfPhddB/YpY49/1nBrMaQdJizlim
P6vP/1w3XpKgLpbNryDvYWLuLHrSDboOy1fLa/yI6wJWdAexYfzjJRjNpPJXXFKgvhm5bGqsO5OJ
Fyosy7g92PEnRPLs9BKIV/CHmAnSZXuctxWoaJqC5oruVVSN1HIGxIuMbCBU6JATf+SUdM91JZ+f
nN2XRihkBYVghhDjyKdQGcRgIhOZnrzVQyBdh4B279mNH0MSVqNgZAdLlncI/D4CoeVA8MrRCGtI
1xBdM5/ERRTbZrWwZgZEhgdIpX/7Brypx1GnTAqnVnW8hxzU4/RMMLXhCfw1RHiiB7ITJiR4g5y8
Uvi+Ns2dazW7KPblYEccpDJ5H4J3sNFWmmiaz4UUK/nSP5H55WwDSQTD5GakAXBlT0X2+TUT0a+x
TlY9vuOJQsGMMP0Es94JPQa5UAwysFiPwcMQh6OZG9XEM2m1eSl4AQKeqosazk+88kMNemuxIct4
3rPRMuSanYRE4OoNEfkBA393a+xmy5PYMJf/LYs0LhtqxkraR8dW1P+I7x9u2etw1nmjH+MnIEHi
UNLKqVwhq3Rwe4Ro+PA6ZvNmI2XOpG0SCsy6n//AWeBbnXPX5nABvFzmGSVA7mFyfSzemsTob2XO
HSMeYpCPCgah8YxeqqYMI7wdYZ52FZVuumw1UkeXSXBd8VXLO1ToCQIR44b1VLbTh2caaWGBUYEm
w9c3C6GyCtesKaAS5TFzDcdWEr7Ov31FsK4UoIQeQLknME4i/o6B46y6IGQgMacdzztuwgMwMm3h
hD58m4tNdE0717sB8cA8oArAhj4OeFx2VxyKm0CuzPBYxhVB4rqn6sYr33AEaryWAUCWe/obmvRR
TT086pRsInsb7orEfjVrh9Qkg11SWf7T1oVyCDm+CLn5NPxMhOJhiOMcn6cuknkYlaSZTz8c6tOL
mFurYnpveJg7JwkJajUFiOBW7Xfi11Tg6sdlSI5ke2kSdJvB8fbFxYRKmomGq+b9yLCyAMLwPXU1
zeUBVYS/19++c/EjOn6ildzSyntLf/cgKovrGdrOZPZNMncjnTViQRJtKYC1LmtKX8nCKzZJ1QBj
uYwC5j4JCd4/6woorVF7gxXEti0isSrkgdfe0hfaQMnXXLF5C7bNMTMVHvpkEg94Kr6s6Cn9bynA
YEB0HnerjiFrqmzDVczqRVmbzXjJ0QCJkiBLXaWSA+o7b6zuKSOP3eh9dm44qW+sqnEQAF1sb+eR
T/MZrJ/VXg98E6NMBkoR1V5VQMaqhmYZrRQxd50Ms4Upy7I8DC09i2zA3bIV5/6dNSR+kYIiPb2Q
fj/WrC3qqv1BGl2ZDdGRCifJps1imGEoZtal0/jWCvPVvbhx+HtEjEVXJ28HOOdfZImBOlrPBM+E
++YKigykeoHK2mSKHgnHbJmRbapQljDN/F4f7F3jTlLiIHXdYRzJUHCY5LQGnmRrSvidtzwLG8B7
0wD/FeTNgQhJ6XYsVu3b1ZpLrHTK+cYUgfHZc8qDwii2qSoDm3WugC2bs2NZoDLP1TE4YeZaea0B
YrjUzOc6xWtZF3fXZXXR5mL4vBOkz9wG5ZDrilwRHsOZGqvClUPJrUIocQmHIMpKlIOqzPzuAAlI
erDXq6uRq/nlJEjvVBmSVlpV7SEqxPdI9XOI/uGT7Y8jHf0yW+j7hKP2DoVF4el/R8Dnd9BaSuJ2
qLFd91j333iRqa5wLIy7OR5n+AAcekcS/f3DtVx2KbFjYIlD1GZr0HDEYZwld0sp3UNJIW5MreoF
Gw+hi9vZPwhvRP16+yaN+o00UhUDky/DsN7YmhJtzt8Z9ZR/RLNKA2g0NorYqno/hw2o1+N36CSc
0pE/XrsdSCwpyONXyZNb8kQQuMuqCbKAz2Cui9Qhk82GruMU3yDdVlnOzMpC1VgDT5o1bY0LRtH9
xMy3BbXQWWeeC/O+yvf/DvPgccB+rQdnVbBaAAAD50GfSUURPCP/ACuylQou5WLvPu9ABdEhOd+o
xzp9lsXL9fqOKSd8+CIyy1Z+IYDeUwI4EzZzJW+DVQjrnvnPCMpW/RLRDrZElz8ubmJyvvMLKnFP
+08hybsrCpVlRNOj2K4nlB9ESY3WJKBMZrXKV9dCMu6DDnozA0YrF9JLZRw9EBshC81vXZuHQ5RH
Xni1MjuZSgoWlNRJFSW7RX4Ie61E4JOHE6WttfpzzPXb/lJHnwNTowgatSQaxFReHkZ66H6S12XB
3fVCGbpVT0mbxbam3jhKeqKiJ7xWdKpQ7NCEc7k3CLxmwylUguxpQ51qgPAnqB28wsk2onYpQUWU
p/nofhHV3MtSD8El5CpM7IaUiBzckCtr5zsFldUsyUC5yQg+mV3QDKpT3GNRaKg0CJMFzxYv+rr0
LM3XWPcsFAI5cgJzkSTol2nnf0WXM2SYIBFbd+QbJ4R/KxPWv+K/1pn7AoMDzYxQTbHyu3yxucjE
J4Ez0EoNBiqC2PW7/D2Odk0+iSuvFS4zMb9viQ3vYreYEQ3Evdi44sTE/QEyr/76NmzbImeZzYPB
WeHpnt8t38VOqyeQ3zulHWMhvrpJL62C0odmhgQ4OnG7TPTE8peMOjw8Fp8QS/X2/db6ljX9HGZh
RMSSJNcyokOtUVs54BPvQskY0NUrqv28pBmjw9nRbT051XIZ7GEbcioUjPTzD/u3Crd83XOjy7fp
PruB4e015eGEjFDEqZjUYnz47A0g1QF9ubkYMYMw/LHfXA/iwFHdRWQInr8wO7okhJYOKcNsbVDq
17EdiGFEWYgyJYh5kg7Hs0Y6gfwXTM/YoGwpCVnqVaVGopxXC/3MoaWMhj8rEBD6t1hxqYSek8A5
F1rPrMrCwK+eTbddoi4Ra0ciqzQLcO4uIKed8Z1pjzbkC6LEVqoA5LnMnr86g6iOnp4n18WB0/Cc
DtMjPIHHzHtIENotaQHMR0hwizoHeIwfFFg1UnSUn7GvL0IFPuk28rZogU/UT2iLP8HKZ0kPumlM
PG3zpIeHSjVFabcBeyOFLNcsUX1Iy8wqvhuK2eK6Gm15tku+M96Z51sWeSGUcQH8/voe+Hwxz2LE
H6Bx4vh6teDb2Yt4avbEcP3N/421QMW++aFcmWB7pngYTH5WNhk+e+sCjqC1kdyQVB2RHQXHatti
z9lquYQZ6KI7cFluzTk0SXeOa+9buw7JZDEaMcCMEuzufPNRxXbRMrYn6BvhC6pZfTzowal+wfqw
IJVJ+fOnkJZVEZUMLbtF7wkGAGY0ExE0/niQSF3XQdJBSiBwc9EGhL6DSgx4C0eITbpsX/j6liUF
2YfriAAAArMBn2h0R/8ART3HKDJsAI1xg64S8akuagdp6GC0oOrJS+9xlQZcqOvBZ16EZzDBLmig
id5AJYTxv9LTk72phX/LQRnczAn3VTRxB/qvkwRuDhUHQpCNsNBT4ylhmDAewjysF5wBI8Zduwxb
kPNFLkv2veHuNa02U3y5TuDogQ82pkTRTY/vMnySfg7TOT0edYEhF8q2+nGMu+J4kWFOM8hA9BwI
PuJ9sEmlUp11hEN34FCYEh+tXdAu5KZ/lOQJJ6bvaDPFvqGbnz8/fmEp2R6AYy6oTo8Ju43wT7pi
hLV/51kIgsnimeMWdjlPEZFarVeBKo/0lFVP5J9735w9KekWkyenQUN3uPbRdjcPVkDEsamzyOde
Qv4SO74jMhmqFZXblyFfdxhCYuubb1TZtC1qzjq6MUn9Gndk/A0xOG2z7LsJQ/1e4SsrTfY/v7DV
BBuFWU84bWY5xXjOjhy9NmHzHM5a+CDUAwrYbajJhrejLkW8FL3dzzpUiVMk6rGsQu/YpMTy8tZw
hh+BdGL8RKcXgpnYw60NgKXlUpy4QeldaQhXcIzbdzB74lvUk97+2KhwTcXZMcu2IfJVqDOKRjg7
JAg4CEClXAWw/nBXnpZ3EUqTzaQK/Y7KswSiOO6qt1qorAvLT7EcekgDzSCheplJ7Kq8uLwSjFMK
mJ+CvbfZcJ2R099NhAx80t6E7BU1OhA5MX1exRLpKIdmRp05HD38AGr9aye64kvbnD4jYOMYSquC
9SwNmP66dnL9xeVVyWaFTDVQemH25syxDqr4bnR+WJUYNFfBTCaCGN8W6VFcRDA3AOIV0IPA0sVS
QRQ9pjnL1/NIVG2IjFRbxN8GF0tJvcthRTf6U6lz10/C+aCjdJyrYBt+9STOaeyUyQzycYE80H/G
0Mkq4twVAFh66JCln98ZAAACwgGfampH/wBFXbJ1YYAG0/ihPx0M8HKSTqs8YNWSRwVhvFW0GzJu
rtU6lB3MIqtUOx2Pc9ORSt4fNK6l7JHfK9mFoqkoPxK1bCSIrAZ1iqV3ikrUoGM89p704BeyDR0w
EKH5hznQrpTi07Xz9iXgsIllAec6tiNqWpBHADEiAoSbb92uPugZqzVt/CYa2wGXbu1Mwh5rrKBz
Hf4iSjYa5wVyslOd43Cx0oUjtKYVfROyKIFjDBmCPf8WmwXVYOQ+UCHYeB7/FywKpRzrGRTNRodc
AQ5YlAomvRCAT793qk6GH7sNSSp9RH3tqe68Ya5+1WM5/cpP7l41okCM7n/bHd3+JyL7X9Coeoe4
UIanfuSxNg0RhDrmLqEoOfC2Wbjc8wSF9CsFqMtDRbGlQs7V0Fj2XTGR2VFLIK1cG12K4qgia2UU
70XdInZ2P9SVbZwjFIHa4HMsVZ4WjQeauwOkc/tuGgK+5G07v+5kRILnme/9Zq0Oubzhe4bi2zFn
Il+rqaepiOOeJU1w1Hv+rmOkDDxVyX7rEX7ACr6rKpA8N8d6Aj/KA390jeSmvMB+quk0cvtzFXyz
JrhgsFpru6Z9HIa3Sf/yNBFLjqaznaZtXpLFLtIYSo2YP0LJJ+HxGb0ug0PO7fgQPgItdbUIFfk9
twYl62MtuLfnzrDQdorFTu+sLru/I19soUKEc0x3McVJv5zHoXXtU+lEgU2pwSH4J9UqD8s+kXgr
M3ZwUW6VKDIl1eOSMCB3NDs+KyG2X7YIG/RCgNf9RCadR3OVeBXbLIxkHvopbTXofYUNCBJegarr
qHC5MAE0vexxXNvJtxL2D4sIHdazrZVtIgaFgoOHajtISJJ5v7g4RTRniZmMjtblZcVmL+/C3gxa
uFLmbKCoNAVzTnb4eXv2qg6S/e+7Gpg1de5TI7kboJvuYahvnDeVG5MAAAc5QZttSahBaJlMFPC/
/oywAN8K5A88QgA2gVP1UAJPoXP9GS5JqLITrqDyVL9UW5YchtjtzBxkA5w99ZNi4awymrfyLhhk
j9iTpEtoesS82DpafMb+Y9lFVRtHUqowhO3T8s4N/lD7t4RIeu4iIVQkJrCnDE97SE/EjPD4X5Nr
8LArMxnZptvIuNKxyNkFmH7KTMmSj9Twz8XAFq4qV+dUJTvONGR5Vf1yltwS0wZqAnhvZa3hl75g
p1ecg1tVQM5qWqeuXNYc9guuqnWzZrkvN/gBT8Ut8GqbRKI6pvwpe0NMLNCbEh3zGTv/1RdfaPzQ
jkzitu5qOjGlB1/Owg44qYVPxzd6kpO0SAUmzvZZe7E3WjET707Qyq6K1eK+YK7zR+AfXHopdNbI
kq/ShSqo90N+kDnhdLlM0vvQNFAiDNUxgIp5iYhanGr7HofltOnkDButJsmiqEqGRsxGj2qakFAP
GIjxJbsiah2p44ltU+ncFcrV/msDH/3mxBr3SckTs3GVI9B4MCwe7mVLy64IofgeU70fIi3+WEKg
3kZXBUdXJciWH/fU0pj3O9ARgUgrAAhWVxKOjlcFFMqfkpc8f3U9N1+0zDmRmthLmZjCTD6F1vB8
VYALrDxgZ5yamVR02KNDAjr1axOEqlAFxJyMq3HMBDtCgZlTl8zmZfTNIeHoE/fQNvxE29YKsH1A
BLxtvs2+2SqDFpThIKslXauA5Pu29vbxptTlvYz/l4ynH64DPyMhlvJHPzGMrZfGUuBMK7M4NlOh
rIj77N0l105SCbNaGRTDLJ89+aCUzdzQutKFQ+c+NjlsutzZL1oTNjG/wsbXYebDTIzF0r/A9njz
1hyBaeQK3xTZj6MKUbEtulE8pxhK1DLV9Kq37CDDIF/1K1fukL6h1fD7/2W++cSl+Z38nXt9aoBw
kmuZLTdB0Uxp/f3srLwuiYVCxPIRXGwO2BTqY2tEHvPPqrQ4EVCRtQmSY6yKuCl71HKf54xdBEDe
dwgOBhlwSAOkuOVL0ZdzousLPRvifFLvQguzoV/weMMCPQBj6erC9s2z8nqbVwjQW6vp0FUjCtkK
KLfQ0DDdNky2fi2ZzUEQn1WRVRpXZRqxzJjXMZHOkSftFNHCvMuGAxCMacW+eYdovDuRFDLtWcps
FVu2PShOfF2i5JUHQpDCyX7lLpW9dPWhIn+d8dQfXzbOL0jaCFujnFEhPYUREij3dODd/HRuMb4Q
f+WmClTbaEzyUQA95zgHDlNfC6m0k6UlgcG7P+i7jIRyEmdm0jUlr+ol/HT4Y8cWgVAJ39+UhMRa
YWnRmfAkr9VFJR8rpoAiYXjRWkw8WRYmExeQIExYnRd3gR1w3jq8l2MN6eQvFdOxRLB5hynKkJtQ
2jN0Aw8T6pcNdkV86HUOHbOkjDQo/bajwkEPnmSx9USlSgrLl3AgaNt5jRab+7P5snpaOHvMZxH/
MuKtBhadq72RUBfzdDVmpWSk1d/Vugo1jFbkRiRmm03M5w9cCmKYSDTtp4V92YroKqvSsrc99o/+
rSdQGI6vwLsowgKReVjlplZE1ViSVxJGn/XZKJf0Hvc9BYzMVvLzMeQwdfWqnrjg++JIY4CAR0be
VxpL6fRx7F11CUNegX6TAKHYG0wYd0YkKuyfkc2zRbrT8s+d6SUgsHoVW4VlcY1i/53MEXMKboBF
ECX2gpU2flKr3x+D32w2WPrJs4S8aLq4SwwQlURpQBqnvJ5XnyPxHjCm7DGyUl84GC4CG47x8d89
VEqa/5G1Ndmt+Kf/21/3I2hGeecA6t1UDQA4MVk9Bt/F0WzTgCNESSvqMMIpsuvBIYGopxlLGW6n
Uo8SDHIBFXcdiCxtMMR7GRhTYVcA5ejiYhFWeS1wrIf5vqwYBxzTyh5zCsEPAAtEMLJNVcG5nb2U
7EQvxvAdV6Ij6S9nO3wQeTXfWKJC/Vs1wKaqmmeVJGQpkqqVfms9LSXnPkk10A2YPwVKIXIXfm5R
6H76UJPDxse2sXY81i0nLuj1LrapzpI9FcCVznB/SIkLIaTTesnakck7CZ1CepyHr2y6NN/JD0w3
aa7IjrAr+3+YDPhY/26HsHd4lSOMx1LoUECDiDgAadSik6O4P1JAg1E94Ucu5GlwYQysfZxhpOTl
rWKEfqlGafKDL2fg590sik9wk0XcfdsbLAl+caaCADq6BNJy0H4tvU33/5Fj8nh+y0iX+HOIX3Sy
Tk13nUnu3t09G0srHmFlE2SzA2NFVhPOvRafGiy9JlEc6vr6VYSrgYZtZ4Dd7VZU0nXKTK+SUIKi
f9aaydtKxxegPdZPHXsMCXdVf+y0hOF3dQeSWdnb9KLbGJrWN7n6re3hvC3SW+Oufj1LzWcd6Dtk
azyPZJCgehVtC5fJkiHTvTQ2apj4EZiE2M6nvavixgSXrYD75J5Zr70Etiuxh0fP9ebVPERQ14t+
eMOcJT0B+7AdSZzGgAAAAlgBn4xqR/8Ab8gWUb37eAC5PWHOTqDA7momOx8IxO6GQCbVcf5AbFUS
PSwJjmZkeLtVeLxbUDx7OGN0j4zbtyjo+ltqePrWD+cq5UihXxWA7ASdOhkSBqCG/obOYw6MBTg4
OBcszw7NDrHmvHHDZv5aSUt0BaPCzVKwv9CWdZLxZpaSb8VJWyB/3CwQrbDfoorLPUBtSr4TDeOl
bU5qanWNBEZhD2Rl2Y9Opsb1m2n3TWVKOOBZUkSZF7pJBxTvipdl4sFBvxl6j24fPngbpK9rnY1/
+fFtekewKQ0lQ2jtZb8IyIaOlOZI1YxmEEBFaAHkBXiY9nAVux+spCUU5c7QNPobj9jF+49x+fb2
dRmp8tseUbInnOOfdmxKfOUuYZPlyxmN7O2QqNOHLSNlGWPE3feOBmVh+Gcs1314pDeXtlUGBfll
D+QHwNKUxUEs7Z98DPQQ7dkR5yydS5dtRrsN8+0pR16EUOsnr5Bc4MUDnFFe5yWovtba1VAj74sJ
FDDn71wO9ZmxBYgIj+h/xNjfch9aANFj0yvXGNusa0QMJz4xjxX4tyF27MROT7Eio4LCnfuAfrxq
cqe3cOjCmTNYYHdjm2W/MawJBzWyqwnnLNAXFn6/XaHFrdmCwtHFJSldlPJhIiMgtHBS1rf7docA
Ia0WbCYcevsc8oK8Cwik6z9fTSs9RG6VAIEmyU8dyoJl92V6wElYJWn3bkwihVEbbFWZxW1d4S1b
pFDwoKJ0nZfPuXf6d4lbO0axa8oXBPY9mOc2ZYm0iZEQWXxkKkXetdNMhc3e2k0AAAhMQZuQSeEK
UmUwIX/+jLABbcdtgCJDSdoGnInsB7se6hUbNGLEzu1Ow5834AKumj9I5HmAwbMerEWgbJx1qn9k
ERBC2CgJrFi4g43iji190jHhISraf8oYzkvsIRnFkMNYZP7nxrcG+2ope1zocXQBDaHvvwGpDaEc
u4n2pOV+pYxS0ZlRND4/RFgn4f6QewT0epirqeso7q7eliTiD+SJoeUrySvso+Wxp+r7809krQs8
ydhjLashfFZ8iZTcLzI0YRLW8PlUK/fUACnM3nlA0YqvAmVp1k4oQBIaCIsSxeXg6UB5Yp+pLj/g
uFGFRnLbBxcbRpmTvumj4Fq8k18XqOGz6K+ZDF0PC3mUVm/KwFKF8VSCAhjR9oYzlh3wH2arvQxd
LxoStWnF2n1TVMp2DX4MvWe3g7L5jxr8+/OKtmK2Eym8g4nDFi6JblCCMwxbyX66c76+fD89/iAf
MBLDf2P6JyVnObyGoqB5xsiJD3zhR60I7S2qVDQEWU6MuefONqPIdLN7TyQyyTWjAuZbFdVMlxCq
5gPA9odxL/8W3iTdBc8966FizNT9rs2nEJyng73sd9r/md3otD5AiKIBwUn2qtiDGcZi2ni4XpwD
YRIhIaDTFMg5lpocvKYvbP4JhPygIPmossQcD1+IDietZrhi/PkYsDbmdv0jcLtYPCX7RxP4mjUY
RBOJwWfdVldVXKsxGvcm7UHwUOE9FjuhR+76TLqQd79re97QEP0ElZ7kKAygWj1642gK0faXRCNW
XteRTtij/pDXrVV653ECsIfFizRz9vOn4wIeeBmtGE+b4sBBqY5CqNc/jGxu9i+xGrRDeDD/EGLK
ZVqf1aGlTixE/J1boNq5h/FpKuA2V+99MjdfcWZwPKwWExQUeDkwFHwkdC5j7xMRcGMRlhb7pim+
tTgOMH8Urz/Ma8m0fIk4EVba1DR+OGeRRJIkhR2znOTnPrBoI1z+yV4yojFyrq9Cmxdq67MtuHYL
yi4y3f9AngDCmWaLDYZYLOh/nkOa3ljx1bC2Pdj2XlsePsHtSyL5wRoA7/IfcqzttdkxiPWJEECt
90P/Q8yWXDq+Da9arIzL/EaVbhwWIu7f3UsENkehOaSF7RbXRjnUzLFQ8nOTY06rzOqMgZ5OaY/2
Xla/kFteTTduVVFpR3XgTUMAaBo5EAnUMFdjNb1TX+8rxR6OjvtOQT7NudLfKrvojpvnB/dqNiX/
FjeDXIRIoYz9cU2BogtHDnpfBOkf1N50z7rSm65JgqY9DbhdRd7avt/cZaknjxmR0oWL6AT275O8
mk82SGsX6VnIOUppqjFxySwug+XXAiuvKGyGyLrz5UkyvSHpmd9yfwvpDZq2PNaOUfGGaH4/O9lk
MDXskauxT5MKAQgWB577GJzdUPVb5IJr4AzYWtWC7jk++bxBzZmPTDXEhnk2KGHlSGT4l3O7ApgC
mGGdnO9gr8UuiX0gd+MeuXCg7/4tYYOb1rpcP97rj2vfb8YMpqH/sGo734HPpUqEZ77R9MA6eP7k
kgAmLGYUzrpEFWQ5wWacmjHMocfwE9vy5Mk9FOTq+bbHi/Mk3f1z/Pann2E6s04LiGTvACklG2qx
PYxea6PTGFY8ejzkYscPZjbv7qtSU8rq3bVSZD0my8prxV/7QqKhlBabsxJBDX7ReVD0UJXYIOt6
kT3Ba9ApueVw3zUUwP0vnLvLt5vxC2AgHsg50sTJii1a2ptv5YTtn5vYQ5r7A8CcYKoZi5i1V9sh
uSDsTD0VGRZ4fuJp2VcW9ebEyQkfHj32huO4h8/kuHCuc+fnEYygXA+gvBoeI40FNqQoZhdcTwTC
GYI8jMx17hV9YOpFSWV4ddOaztZmbZ4NnZ7ku5O/lGjnFn4xK3271mzsuAZsHOOpN6YoTQNnNQDl
NOXRQeKVv/0Gp4V2aVdeFgTcHaz/U2TkFUqgERtnKsC/+iZlA8rqrxiuNyx8y0qjq658EtJFCoPf
FwTH5I9Qjbban96216c8RNAyeJXEEj1ipRWCuRDv3d3GDHELn8nmPk/dFKouztbM/Tm3aadVWWKO
XSULFeNnlasFfRI2LhtsY+jchVf0lB8hoavjjMykVeNDs0kDcDGLyRMdFZe3WJOLl5Ny1cBrY4PT
E63KfZuORGMo50iXsVQwSbyPZ2HNm63SVXd9/mo0Ushqzt/UAkHQRduTZqPr5+zFMAZ/y2jR3p/Z
HDyKmMvkaajl84ryE2ed7uujJ/w9cBPvK/PCOJQy+KnNhHT1mwE9dyOAH3W8R0i88qhGtrxHclkO
HNnrwStiD0AskdIPfbs0n6uS33fZyRtARk8kbtg6K28QwSrjHqV446reOKTurY0E4O3XMTHZ2y2Z
QT0ZRhbGK/hxTHnHtiWxoc+gnNIYvSz8Jz/3dxM82BIc2SHbHK5G4AIyi2t1r5ZhTwgjfSPeh2Ki
bMgzUUHusOcEwXvlrBeEezFGKBcsauHitSgzuAPw96gNkNUA7K6QLftMm/9mP3VGLpcDi0WrEAwv
iTXWY752YASfGW5RgpUTMy3k6vRw/6eBtLmGUIHhhHD/gvCbAcJieVr6MM1hjcwLDL1zREOgOIZT
8E7KdmV/L3sDcYZvc+4id6Dmr7aULNliEfGqMEc4cW1Hw7VKMXqEJMW0yvYq1NIKK1eCAoCdhimS
HcgOEgJzLXGssRECGiNipJmMh8T12U7mPj+igVv3+Vfze17gWuWpyIXjgYaLaASiBgBQXqZLoMUN
FiiPnpB3lp2DcGaKWWoj82CHfToEmg1MI87r4hc7EC0EwtJ6+hJ3G0wBaIqWqOMmOlUL8mkp2vAf
sphviB8bW9aBAAADE0GfrkU0TCP/AHQiQEsffnugBJlRozUK8vy7q/WIhR8NUClr2EBnBPuyHxRf
OGWTpir+8FQbYv3W02m86SEvP6evgM1zeWsXVfpdOcUHH+qJHUf9CdJn84oMSwkZ5Xj6wRPU826V
NG3lpom1S/jqOagTSk2uU6R9OZauy1UbDDXtnop+1XnOT0gqqxzYo3o5rmalLPrIlUiYcFO+OyK3
cMk87FDBgTsmD0Ig9RzX4hCUclHziMpHNBV4OSU1lT4XfmNylE17Qk9oThvt7f9CvROrGeBvglQ+
LSw0TrXNzW99rKPmpfLXaBAzwZOQcB/DU85vJhSD260Se3p969lgb+TZ6WOBTSfyiWM65RElmie+
gCtgIvR1h74Ov7+H3eXOvh8pIFLVgy5ebDei5fTgBAI6sShrKGs7k0gYsqGJ35ATXJRnfybDg42Z
4YJye995W75+02j1v07eTMWvYArmmbX1zOZZWK888A/NS+cp4ukAw6KBfvICK953DEWgI8PMPo1L
faPG9OKVouVJcdLJ/ch5jHZWvlZRr7hVkcdE+mOkWoPbMf1lDUo6/k3dWYde1bvxcP4NxEo+7WRx
LuwCp4eDNOofQ92wPqxnQsUzZnAcGiwNkwPA1eOkacTdvSWEMWth/8ZEU4wipfVYAucuKIQZzvp2
QqT2AWk2aPVVeoDze6qWk1vKcBtHYrMz28EHojNVX7JG9hVUZM25Eswqw+M0bOqwEEf2rf9QzeO6
xW73fWwJ0cRdxA3Cwz1rvtfzpcZizbyF51mdJ6EwcEc3tIOai6g0uVwk7wyRyo7wqHN7Ns8zshCG
PtcOTTrIRHSCo/WYQMoVtlq9faccgsTJxlWdqFg9KJ2DNhfsfD1T8TNFWEBCta1zJRaxD1DZ7G0c
ReZ7XaatQ5UxAuyO80qvoOmD4/vyMhG9C4gismYh+f6/4FZKCQAZJcoVpK0a9Mgar6dGaJnN31ik
o7Ze+rDuI1cEreYUWj53RQ6w2f/3Z8HIL00zKVnFV17h8hyLDsGpo83ll0QAxzzeFNhHb36wYKXP
qhcAAAI3AZ/Pakf/ALpmphffPGgACHYJUMy4T1+fwH6H32ijZMvKr/3n8HsTwFtSC6TLwiH2I4kD
EnlKL5uwszMCUngsGQrxZxWTUTk5z3LCHd4LA5cXgdNHVc72ZEJ/Aazhji3L9YL/r3cODmMu/HNu
C1PjHN+WIhQkJJyQqWTECHd/EevzN1tIZ/aVaCQaT4D2ucx1VVovDnsyTjqnESFeivKEnU/S/yho
FSiINBNj568vT1F/EpIA8gE3rLVY4h/zFp0LaaW9IM2xBoP6YXL3bvD9o2awCh9TqOKXTaT6siqZ
6NmijWawwfLqlomz2QyG8v1tj95YBzyK9yrtPVGAbHVrwauAGdBpsZNPV/j0B77LkUFH9eVtkYeL
+4lQUJWrMiRMs1QswwYm1CS9xkYm7u5cOdJEqKwWvanmnRlTAIwoneafr96pEmh2tFufGTrx+R9H
WQCJKTQ0w5gbC3mT89pnfX6KO/qdO0wDFVW1eR3dGqCKqL+eqwFHxIaz8PhIYYpZwBBI26v8cx3C
Wtwlm3SqX4kUQsbXzW6Hytszeu+jrkb1JJg8GgWp2+ekEK1EPk7g7b+Y94JUhPc6RpdPiYDzSSMk
ycdA911KM7YK5Y5U4VjLGn2qhSA5IkKi1K0mT0zssP7vG31yoewjgPcS1YZDee4H8L2LcWZAzNQy
tcEwBxeW1dpHLuIqkWsqkl3Wv6b/N49wpUkN+QkvDE1BkPbYu0dyk4gSSDAfW8il8BW2qnbGloNF
l4aAAAAGTUGb0kmoQWiZTBTwv/6MsAONKmeFfWhkLN48ACdkctBgANqtPXc05smdEapVegXeSJeA
KD6oGIATSTznDWbllRq9pjO+hPZfmSceg2HC1Fw4oPMNiP/uAkoCcRnWyD7ZfAH2yFRsyattmUVr
rlt0LZo2AEwkqUBa2kSWe8NXkgQf0Ccev0geWrqjXpJY6yhwnNk6ZCqeRO9AZLspxwwlmHN1fbM9
JS2HVzcS+IiknTONnV5aHHR3mxXd+vO2qquTg26fPJORfU3KZ172fIh7R+nk+xghpKHYGUAc9Ngq
Hwvha2XkPL2ogutob/YgTMYks328qf7Fk+ZssrS6mFA3uDECjkCC54xD4wFChxGO7I6dWo+UkwYr
yuKoUleaXTd0ekbKlQqDCtHVphhi36i+PjNVWX2PLFugXwoCnbo+ntUdFbNRpqfBNbFVhfJ1xkYn
olwycC1YXU2mF3WoxfzzfsI0j7n53l1T/7nwHlqf6A1tL9dYwoUWrrjplYFZA2iFSZrWmStE5x12
EBD3u7D1rw1EKng+AuuMLlWq5O2nM9YGTm/a8dtOy04OODIlvtvOcLhC3NMPThVTk7OBad0S7gaX
9kAwEcFT3d2m2rnJ9tdRdlC9R2CG9WUJjCg+ae3q6uWq5qEXeVZYJSgjX6I7Yd5dqkd9SiPDwwBa
IstMxUpnlh24kcCDUBJldT1uorgnRHvm3xSrPG2ngwqqMqmlGH6LRX5sDMKGLRrigRR8qTrUHwH9
NcTVNDRPTgdtTMkEjfFwU0q0Zp/qJJwMhMSZ7FWC/Bqlnch/iEdEf1ED62xA5Cx3nfVMAVJulkU3
DisRLWxXaopXX8q8HFN64G86FLWW54dOQdhyCj0lY6ZKIYYeDROfWCsZaMOHW+7jgFXwP27b9W3c
mgtTqHvBsDTspeTKdPj2PozWnxJCEgKJkEoaSkoNFjvE9ptssF6AiMZDVZdAMBIeQdS/37WN+4fY
m503arpf6cJrkmXh2LqAXaPaA+Q3evnvnXYjySnn6lu2BWZPI0R2udR6JtTYOCb1moim+AzGBrpF
tGyknotUTT9WuTDfYJkNgfYJJyJ8I38OxQpheSabeMmVM/OKQzaPF0YUEeoGHRcGBQUfaBOC6N1/
Zae7KIq0+wlvqdn6yVY4pqQ04NwAyB1ISHwXTfKaUs36UuVfEK5Z5jxqnsFeDgDe3Vq9CpHqswbM
emJ+3HXIF4XArZALcwdsEM4fr5BnxW/Epg0E/jbbfM8P3/KFmiy8qQKz1b9WZAy8qi/fu6KBrgXM
+Mk/rg5BnGi9/jtRzafbWGWUj6LmwSbUFTrCsEUZC+fdf4tiQxMHHEvB8GNPBACjTwOH8mEr3bJb
KLAxEU+XdF3Q/pOSTR6GuNeiRN8W702DXNfBXd9+XDGpBipaTsQ7wnctQlEYo9FBmssJ6zbXknfc
cjd3q0i2lDpozF6XepIh4Vh9VwlhV9knmx4YTOmrROpyFHPLF0TH2jUQ8Tv2eq/rrBt3LjyezSfq
dW65ZAQc24l1e+d8eFmnSKbm3QgyJGp0oRoZo0k7Y2EN9VcQtpjMBum/rOoy7VmRtvnKfLT6vLNH
cq42Jxi+k9qIUHpFxyN2Xe5cPsOED3FODgbSbVvnDom859/hl672/ohN+JFXUqk3ObrCMCdRkcnn
QTtHtFqxwJRPTZ0SNdhSzHX0+ZOYbRKa+GEHnmJxcXWfTNA30NmczXPqhj+6KLvdq6pPFzFkc1KJ
3vGAn9rRB1Aaf2pO97pshGSoSCEM2h5x2A8MumfTsD/dXtqjzx6jIPwEW27+6paLGiByGjerh9/w
FVKVrh6MKT8ZnfV3NdFcEffd89IXbPZbnizMB5WZYPT/Mq2xhNKKSIzIWMgrubduQSE7w6LAZN7U
ORT1EcqGQCqWz5ctoQiG6W9SBblVk7feU02OLK0FaihqVVINKQLiLAphFxh49utfgo9bQAMKQBNW
Ct6SEISZJXHmynWrxV8Q9hjJmaLrlgHkzOxOxPsKaaOl1bZWqADMYhNc/Qg4SlIYC5zTsS094bUU
iS8E3pzY/c+YgyXQ8w/OAjXisYW7yC1zodU4/ZhoKs1NjQYtFzePcxwYnmk/jYhr/09JcwNh8fL8
nE+kK/JjYwJnFKiJQi3AcjevYa/pwkzAAAACPQGf8WpH/wC5rgNGrpscAECmKI1+4lBDn7BWTeJP
gs0gFLTR4O0XbIei4PT+vFVEb38tceqYJ+BNCkeF1MPjLdB6CGwD7rtna2jLJa+dLHfBSW2WQvXU
tIlLG8axSjpPhjIKKKQt8jmTOUlanka77cknSaeByJTw0wrT72N6OL8ppQobqtp1Z/R1iaSHt3na
E6NXEQ9RbtLSgB30Lsj+62fX1R0PQ9g5uPO1Ve0egCciZVZhbxaO7ocM0Y7rF3Fw3mBdrrToPQEi
Y+PbEEpYRegU8xNffXT1P6OimZ8+B7HHIsd/as6IYrwl3XCzaeyz3cm45MQL3kWw4UldFftsUk/Q
SjMAUojjYxUtnNLc4jTXgNN8T9HePSlTx3fwkK0M1U4kfee75pHh9zIcNDGmxm9c1osGVcqAJL1R
OLZkmeYJ/CBnOxgAgDjp5KQGapW83u7yHGKCOTQB5onjNIDgLQvIi32s+KmZQKC41pWjW0vGCbZM
ykYOd8570iCoiEsxVg3x4ga+oTVThH9XHH18IRqnuYsIjR+TWAQefJvy32ZQXdnoasJ7/Ff5ZusV
raXb4/sc73pWs/dKS7Z68NFU/spcQiGbF1adAGMaKeCdQlfy1oTmqAiifECPXUX6OkDRU9EOWsHK
QJQhucmSKZAjL9iTGB/UzaekKhE76NtFbBjwE0BOzFpR60lilmrtVfdcFpfwHUrH26JcsiwktuSE
Jx/Y1Zslh5yClisaoIxhadSOVo4zvKbrmpTVyj53qwAAB3BBm/RJ4QpSZTBSwv/+jLABbbBcaqDA
BzgtwhJBRFE+aBmplBE50AWMO/4lljywhaK5w/amFpUaCE4ZrW90z0ifX850mfdCjJd9ra/RqU43
wUSA+D/MvQGCDn4UlU9f3KgpxbhpYz6vV2JjhmfmpDWgEaKVwoE5HI/iakcA0j59kBgYTuCrqJ9X
3buUrv+EPfJf9qUZN01A82SSND1hBHgzmLxXnw+eFlnlNlhQ/qEx1JIT7r8LDS5qgxtZ8eGlfGUG
K/yCVq7YUR520HCCi1QQsFwmdJ0MFdzqlvbQ1o/SgHamQus+Xd2NBmY/d8/LYIBUH476AvRZHrxE
iPFSpNS5g4PjMSuYWD+Cigf6T5WNsReEEA5fHZiq92vmCALsqHQKJljWtSaCl2HVpNuKaHMttfgP
mcdwgNJd6ai1mrvFrx8q6Cj14Pq6/SnVdBHoFG9/9azXke4VWCDWFTX1dMoJBd8/orgYIV1WJEH1
cSwjAW/hVuvLOeyYbBzQczvkZTndJm2Ygt02y4oKWKsauGOLUQGsXirHWiUT5+72z9G7I9cxw5q0
7z+lecS6ifLs+nG0vMuBRqMesiHvsOs8qlCj0PIdVYPvCYRjKINUzQcqvsaFWNQJpKKlVdwqxJ5B
FxHyUXMlVdVWuhu2tQ6vRNOIlqiXNNgF0NMcg/fnPsN1XkmWey2+trvgP5+K4hlgNR087hMWayLM
fkhyCjQGbSVJ3mGyJzNCk/cJ+/qirOoWamUCB7KqT1k/xezMLHfXZe8o8B+onksHbtz+wnOUfxfk
uvg0wpsy7bxsIMVb7WzrF4e13xX0yHp/qp6/Lhp1IeerBuoFPqgB2JytY52O7FWG0u73G6qHBsgz
WL1M9/OLqYjMGxYSRrznqTH/HxgGvvXEUk8lbBwVimX5QjgazDtuDmhAQ5G878JzjJ5/mGVHx53r
6tTtyOV7qSPmWAbgivEUOFnrRJY1/ejll3xUHnwYIGQijxuuxdZGTaUUnG+hWGchayR+/ZbsFOgB
FrCY21uaiotpbSBkqqbRDZZIDSjK7arsdrBQOrtxbm6RL9WPeKROWpeOqcqgC8u4iW/FLhpf+Fdk
7NuR3FuF31nEih7jMayqnpJdGdx692Upzb4CHKEGt58cqx6YdGX1YBnEWjhJjd2jlEMZ9a0+cmBm
znZSztoywI6slXvblgetCC6IN5pfn6aPDNh2HqgHhcToguKO8WbbTgh4iTm2wZ6kjZzIfTbz+WUD
/PTuGE4VrtCYrj6W0fxZDh8Yo5aTav4yXGDqM1MrkhpDJ/ivEquxZUbLXTmssstUgAP4Par9l1rF
2d8REhRji0vX9xNUuKqkK64fIzf8u+oUraRW9CCLd+lDDh9Zlq94USPQ4gburX1sd9nRUYvmETEJ
YWWHrm48cFY8wWa7RtoQtj9HT6qwaWHxKCf7AJGmxCnZOzTgaXB5cb0EaWUftT2O8APTflikc2Sv
ElWdBCUFBtTZ7yTJjoSwCBIIOvOEQXTYpTnF3V5fKQr5PZnlap7FPqpvS8/F6Okd62enqywvpYnv
dNwDOkp+gUhYHIYdDOHhcbNnjpm0nffLC0fJd8K95ZDMY8xRX6bdrjm+Jt5E8adhUct8fxu32+82
Rkkmv5TyScBlpcOgVBHf8OQF0dU3n0x/H7t41RFZaX6xclSo7HnV+enRdDCV0f7SlqOQ1uBsPd9d
PuaCVIrhKSHzZ282J/uDALbMFMsb5rMyCtpzhWyxIpbiIzJ5bRTw3YcJZwSM2KJsZEtLJaLwt3qd
mVwtvIIh47jXzEP8E/Ht9MepC9rviwriT6LqieDHZjDvl1pZQyaMHhcKhUzi1MeHb9sBv44TkR1g
E/hPeykCoXvSv2CP8TdpvfRDZg1AHMFgszjTgn+xXb0dVyONiImjgSd+cIAxjub12bLQ0DqNqaJM
ZNimMEAFfdQ+Xhpi9EPsi20Oro7QTIa1GuMTnXN9SpDj9UMqJG/k1Fgcb12lHPxKV88TBbmuZH/o
h5TECaySPrru1aUbhvycIXbToY+jAo1dyHOWk67ea3j6NWOwBqgUZbUMJLPxe4kB8d2NBUExNqXA
WZLESX5zFRiGhvcBaS03L8bZVlzX8JxcBKnRSotPkZqTaZoDFzSw/3+O+N3qYTZTtK+7CnYzuDUC
omBmPCEMkLHcbkkRxJiFJ45lVMuGKk7nXAyyVFwiWtX+V9kaFOqS+uJJPMp95YOgHJdRlaaQs/6g
ILL7ou4naHRbptVxoNmORaz+XJqCA4L7CLNyGZp9cRlawyBDsgW2EVPozeZ5N/Ydw0nyYZjDTer1
uwaegjR7pPcvP72OgdlSEmgLX3ovMryhpmBHEO/jUl0KnjEHT/6qKEUGbjrx0lDIlhNZnzOhN61J
e+9ylByYFUhRO3+nWsA9KC8TTFcE5YdXkuRYz+xwC9dzYyia7rq1AWdK+TdoltdO7bhM8huRIzbz
tgTeNnr8ySmn0/VcqYu3BRRWJ74U6rfGVHWlxU75G+p4iki/JQUJQDQQ3meSgNN9sSTsGIlDz5qT
BAAAAl4BnhNqR/8BLfj9u5h74ATAN3ciXbuYbYNLAeSClIgZGiG834gwfW2x2FEuhIWzmR+E1SKh
aAg56efyOazfKjyWGX3RSEp6X9gDiRCzNjCl432MD8NRX64icS5ocGqIvtYoMPiQfiAc29YWoV2f
vLcZNKXPu/6hrpKqgE4+/CsVYNZZClDsYmLZAaNadFX+fAC7urGLeyxBkPDuaRfSqKdnZIL+zCZN
7hcx2/t69vmuC7smQ8nsICiQ4Gf/MstSFq3x0KjABeEu6zAeDUIhRqn9VNhPxDCFUJ6vV8+gziMH
5JCGxKN1+NCaANO6so5u0TGjxlDxPDL21ztS7E/Mr58B+iGdBjG+XdIkpIkk7Vary/6fqPle7OYw
7vZj0FmUIPr8hqIv5LnUxhiBe/VMGpmVP5i3Yxfw8KBJgFPuNEm+O9wSOo3rKMHwFkV7S12+cCpt
Hcg37Om6PlQr1t4FFvFbw7r0zLYqW7kyFV6mEz2HncTaXMGMvMaao/EkIbcApDYwj1obtBKPIUAo
/oFCIs721h+MqYyQH/pCU2VfDALbtiJ83ryEOdPA5akPUp+Tge0XttXVAzxdCF7LwUTM8Uwyd6YG
y1dIQVuezO3CTJ3m084Ctqy99R4QpkHcWXrRT34LH+ULu5FLL8gchgJ6K3hCYyiADbCqurdfcxPM
P++dvQbvIzUXP9zPlZBLNhZS7DWutwznnuY+qxRJSenLOXygWQidNRr8Lh+pnGMEmjLN1owcUxb4
N/TapdgTD/5ICtAIglv486faqt3JL/sMES7rAg4zl1k5NKWLiadLbkAAAAbJQZoWSeEOiZTBRML/
/oywAlDQPjOzYAbpCOQG/skLJDUaBjALcnDx3u36d60RguNuao+N2xaS9EqralGfQczEJWqaelov
YAZMitK2c7tOzCr9WpvnKM9Vwii18cgMTVByTB7aYqVdtnp4o8JrRiHcMUMZ4HY13rtqcviVw5Au
qrt80zDQJ0Vr3/En76JDJWs3MfiIUKR4UfBYY8BMcpNiVCetuI9Q3Hu6okNfRlhfmMcwLo2UfDCp
kGQ16Tx+nuf0D445E2bSkDWJhX266ZRmGIvq0kIRTgLC8kr8fZEdVJZFFiAEaE9dBnI1JXnu5H17
2lZ/q8C5JP4dl73Hj3HIzWhHiO273Sz3BPP23DqPBDbvoTKmlmKIlGf9Xwg7gUmBIwL8d2FylWRf
AOmO16Vp6qocdbO88x4GhbA/GndLOaW/BAlFGZLwEcE7GfgTuXEl6iN9aPZzrUKY51mq4IePeUZI
GyMAuyoNFSuepAYKV5ZdBpumAC+/8Czh8jN82jzUNAnFdMAVWWuNbSfCLZdiw+hmB4EOzW6Axhb6
BTClY0OnXqfjnm6Xhs9Ldqqlmo7Y9cl8WGW9tax2RIKxZu6LSKv3ycoF3pblZuI3QcS9onnAwf/u
N1QYo4/7e3UySOP8DHxhsq+MKaiShre+yQnZG5kZuToVylnzpQ0fJyXx3A1Vt9GqJnoI/8Na9TkS
TGfh+9k0er2eZNP5Wuo13bXD5sbiix1JxHPAhUHtikFcbQRCVbPRbZ7s7RfyCghWjYB7TN8Bib7e
/HPXpnAW3MFibm7famzUAJ/wzQ6BvG7gdYHaYCeXWw2EJex0OyatkGVNTdxJqX3oWES1Y4QhnQon
iXRLs4fHSB3+21pDBdsovDgNycRklV/EmwrZXJfY/lKD8mJ1hwJPY8yLIAgdyvCsHr8jocH7R3ko
IYMFxUkKEUpJ6RvF9aoAGodP6aMQaUVMCfZy1YT1qvFRFywq/YtsbEQaZkCfk5QFQkn2QK+Fh2Pk
rRyTRjqiPZD+r+W5CkU2il/AIfNgGmTJRqMVvnzH7FA/gcAaFpAUPG5ajcnnf+I6mNOFPYbtec0x
4GaBQ+XQZNPX89mUJx27oyO72nIQ5GqdlqLVgYwb9+lqxT0KrkV7+l4grLOqXqSqzrJMA4QMzCIw
eZuWCv3jCQ9YqnHDx6Avhw3KPn/gTLOpxQ0yYhKg1xhA/QIZeJnOF2+fBQIU9YJQToGEsjTv8QQ9
lY31lRL9O4D/S8zJvS6Eop7Lh6FBw+j66n+sDB3oWMpcZl3BM+Jm7Ve8kWjhiDNqzrBxNppy680c
nT8x6YYIeP4GLeJ7bldUzMDLGYTkXBF5HtakSrRAqiA6ygX/USeszwvmHmlR7/8AOfpjRmlGm+PV
l1WovcQwpNwWkXIiJ7qDy2MrbfOWJJpwhWC16Yw8/hwF3RYUZJFI6YmTLSWVEM8lFYi4EApkKNlg
FxAXsBcx2QMB/VaLsLp22UqHrf8HzVfRVKA+k2/2Z98SApSmpzOnTmF+AVVqSFJXluc/XGfocqkw
FaLIxwvi13i4CGWaKIDYKPV5iQA8qdjrb83k4RjLqY6ZFL0wEXMVOdRAxi8h62qNmsOUeiU9sW6x
QiBBe3tmyr4h7s8xX4nitIiN07Pgvn/+WlpFMV8PxZt0FntNDZtsKGj07c1LFNnC41LCcm0X4Ly5
qu80stFVI5s0uxuwvfLSHcgKgLYBLV2uigHjQTzwb7JxsKRcrhr7HMIPvgOE1r7c1ul7Zt2BgS5R
xY6Rqx0TabinB7hRUiwz13dX9zp0WsVXJ8G4UmGPktulYdLPb3zfZXszjJkFIribzdTLVjkoG53j
nRW0BRLdyNiAEgF7MYOO4ue/JU95A/cgoGorbim5Ll8hrUwOTI1ik0imM5SF1d4MDiGmnfg/ClRB
ZOw2NnLd0hwTgg6raQg8YD9dS9/7/Vmeqe5BVFU6EzxU6u/5TwAk+gjXKCAJPt1oBSXKeu1iDOa6
J2YGwy8IzxJo+KzJUDEujnD42D68Nzx4xUvoKWpG8bVHqtM6xDvDoa/fZVrEluRyWAq7s8VXJzFe
c+gs0NyIBsOmjKAcvF5ZjvXewgwwnkUwcblbmCMS/h2x8gRaOfTViWKNpuA6C7dOw8jKNHavtZrU
GvdEZb3wtDXLAt5kJ2oaeM2D52xB6LLnb8Pi6RhSpSTchBB/phIafEfUmD65FSDxbmBHc3v61esb
k43jyW5o3NLUhxRvhYtp2ee1+2BfHTyxcFI4KShs4+BFJCAo7Z+0ZZgGjtx5a5yYNqwVcdnpdtNm
rGZxLMp0rLtFDrydnhuhAAACbgGeNWpH/wEtftHtID5BRDJlAwsABEFtcHWCNCcY3tmFMtXwEVng
RDMZBUXObjlva22S+o3D5Oi8rBXQiAIg32e4s6Yuvp+g/wSIH34tZu/UikSohs80Kobbeth3qkZn
1zlEUN+GIxQhSF+LoebRjfBp7Nn7lI78yqB9u7vSNOvW7xS1zL/w7mSPQWIzJfFrV5LVAEInvuBt
sN4muiE+due8kF+McHNZrk1LxMHpk+SHSKJyF+LfpLxjUthgJ94/XqM8EcihJeexa56au/CBcqrI
+DVA8oQ9FzU4KbrIQP/dloMvNPmmIjf1rA2U3LC6UzHr0C0tX1VP7zm950qy7LrRKYjtBWcwJjMd
lbjxpKwlEpMJwrD74Qpo4fhqBhzv/LlTgCbkWpmStpqOp71VrtImWzEtsh7DfIvHepVRbWepcMAa
KyafdGX4nMbrbUSOAviSqAmUvCbLTPaESE3OkZy//OZa7GwUE7RguC+NHglz9W9BMHnt0yr3nwkd
NL6YEPcXMtI9l9jGekNfxAumM2E2VX/+RWfGh/+sGk+CKOWQOYQP2EqeEK75AmI2yfGNNgZLU2no
C/0crCV1WuE+i1uAibwY/kDlygv6AaXOkM9ua0kFLZDd98SCwwwCBINjeBTuDVZO2dvnGz9zxjGc
cCjrASQZsDs/1EGDvg1YIC2twQzLfXMU4nLQKcO47IRHwG+qNDRA6guTRHAxDp0/0Kws8qsl8TuK
/5vJRyUqqxlbx7k9CnVkOFSd+m2bjcudIB7ll6F7eMY6Qziyaya4PNZQM5inojIvxMxBf/YhNaHR
4JbRxzliCEyELU+FrPgAAAl2QZo6SeEPJlMCF//+jLACUBClu19AC3jaRlJ6PG0wZglpEXbwchsP
y0abPDp16kDuK1kXrFdrIABEXq1s5+BCv0w/Ge1UAxsQ9BgXi28j4jSmbP//uVc5rdBOgG+GZu3b
DF37zMXuhzu2ecdcgPkEQScf52O+23nI+udY11Mjug5Sdx5/TtL/Uz+r4V/4UdRu3CMIApbtoxPZ
dtFTYlXnVs5nf6KPZTy+JwThtbU2lupZ8A3cSiI3TrAj/RHtnHnBmD/Umdx+UPx5oIj667dDW4Iq
vhbS8gbnMgknNV3FgvEn04hBrgPZcPjiFTpEgBEiIkTUY5y/iwqWtCR+/wvBYI5VZS3z4dR0gfsC
SD3yE1r0drCTqFmamb9ubTFpk9Mci0BsC+TQXDr+0qktu9RebWzN15r5QVoKV09rCypG00ywfYEW
98peMjMDNwXvt0d5MEZ2texy9l9uITMRmNicG/uDJ1z3yQGTGqu7R0ps1QsGPmY4HT4kNmesV/QA
GxlS/QO3aLqdM6CFEl75cyP8jDKkvgxi5Tbr8jJxbXbb8iioBkEB+Hgbg0DpXrQCWxfjFZx/ztFI
PMXw0GeFvLsGikYfI18tEafPRhLdGHvMRG3yAgLHNMX8AS6R7uylrusFrdBDTTxXBxyyoS7zo7Xr
DlLfoHtwfmfwgcM1FvWLogZizr/xQAd/cLHJbgvn6/FvtiXU9fU5/o7h4ewRRvbg++N6c/IrDGph
+K0kWHz3f1/whuGR3oriO5dzYMYvfb7OXcdKyb2GdtRujqPhwpZrNO+Uu9sMk4Na2tPoJ3vVvlaV
wKSK1B/t5OBf0+YofPMhkU3jHgJPGsqmS/55LsfCifamCBXKUCcZ5IjbDplKqQfMGIucTC0f+U9m
1EwxElE0Etz5XreTF39ED5z0tA4fEdvy3Di3P2NcR+1ACVg4c8mnQIJrAq7Izk2N8jwySNr+Fseq
fRXcHVceOWHFp+1OMySh2jLS8BHIh+oGOFMoq+CAJwXazrv5V2nU7hYtUYNipEmWb7Ga3yltcdTg
/LsmtznoqY+QPkzZV4LBJhDpAEw4W9W3OW6om1AGsuelNExgbaqmwzgdpeDtAzspATXFTOnRRjIN
ZUdM/SB40ocS573AhxPoBFz+63mNC0Po5xvZMvM6pVzaYx89CYLAaB0/z330GmgWi78+5NNFlej/
JzaEdg+ohMNX3aLbDnsLRI1wggO1WVzae8lFG4A08FgsZF49/R4izivlknW/wU156mbzAcs5Q38i
WOMdlBMsuaLnclyVweyZ6YbdOGRuH67E/qGcyYwhibhz19e96Ecgnvk1skDtZ/tEUgOm/ePFNxUb
PTqrOPlecoy2IbDuudKGbHEFDC3GDwFQ27anasCfm4PKYMkZK4D/b1McGewTWVZmoZqrPpAq27Qb
D0o5P8YdbjM9yEVt/Dxfw3sV0f5qWMpvZn+tvQNWTJ7sSDA1GSmYyML1P0junNymSXHAM+1L3opR
hYS+AoWgvqzV0JW7DeiCJSqV6Aob62Fa/rmibGBl8K3T5cp/jWUI9lqigARvokwv4VViKOWVpKlo
I2qZRQiiq0+Hxs2LtEHYdJ+F4pc+Dk2Zi4giQ/WdvammgekS0OWh9mdbjzoFrslxHQCoE2klouki
bpOmwNo+/OdUWstxXKDhimOSM9zH9ukHVBRB2DRq/3IuU2fFKXHuwNSvli26kZex2AO0kixYvkLg
SdvoBiRUwWCBScIyM2Hb93JI46UJjTP8vITemvzDqGp6iZh0xAoXd5CHczJBmpnhRufChHZtxUDA
6k1Htz3nADNpFXRIEq1cuzq9Q9aPfHJdv4ZSw6r792mfqcScvaNZGA4xkMe7RoqN+6YsCsFBo7py
y+GYp63sVkETN3gI8XAdHys5swoHX1pVxfQWNBHt9fUm4IeXqoL9x+X7SSrw0lv+BdpbkDXYtr3a
ngJs0ayApbWUvXbq8s8xWZ7Bat3Cl9uH4JHzt402bQ5hyNw4bngK9DFePaV5vmEycz6yca7GMvxm
LSdCjRGktMxdGzfaw4VWgNbFSr30TKGojMmihqYjPxxj0Jme0xBU+6VPPkDIIuJD33WBvfaFZHZ8
I1xIsdggc9vazYCcdU3ykQtGO42yzWbBeY/4+g3YZXaIuHsEgUxbhfBwzp2xtkZmPRK/wrx7RTDz
/GbkZaZV5SAcOo5Y0rT+n+jnHvBXVK6YB0shp5C0Cdr0xPgeF+oFGZwODgDjBrBDXdq49vBZW2lU
uiX+d5jdfakPKRtmm7Ie/swkyySAekvI2rXHcggyADvj6IMzoI+Ya635qos2heRj2GJ991w+Xa7W
C6erPZuj0c/hXOUh0+uwFnDuTmpELO9lff7/9n8qZbi1yB7qdAt3RZGXKB7aDYfxvoOIYU30gTot
vpcunBkS99CLy2X0F/ZSJWffKw1NbUIsz8Czn4kdhIB6OzAVsa7Ii4H2mDW2HRzvkGIwc2RALDly
Yuw4yrUdRQfrvaylZfWejdWxpl13pDjfoarQeBhHnXWt5tidFWVeXfOLG1pfmV9Ye3fB/+Bgf4Dw
kjGE3ClYfUK1RCJ6PrLKVS++nRljseczJabaIBKvRaE3w033zvL4P9PjCiP3GosMIxKtHzIL5wq/
clrOwc8TbzJ2RT1jUi9FiWhu5ulQ8WjEdnHcTnf5NpAbcrRKIugfqntUtCHX7cIjmwvg1iD7H+xj
1FJR1nDSkWEnp1SvS/LRtsE/Zc03DN/8ocGH87ec45Q9f9I6CtTNXalwySFalDdURML0nZ7fmVM/
YAUd3H8n1UCkQzvcWhsiyzGqg9Xnp07HoqL87VUQH82iXdwPc1Q1kGg8oEW//XuWi5+qE36Q2Twr
E8d/GrsK0o4FEqlyIK1bw2B6DrlAIGTsP3ITbR7wxDYYktq+roYiuMYa6dGC3ZcL1cYHDsR3Te8K
aOWqT6edX3Pav5lhS8B+kp4CyqRQjEBXmS7fg+pkC98ztLODJ3wf3zKgxb3kyd93xa++ZJagHISz
SwTblQGjK4OpjUQi0C9ia0vYWVG3XtrdE+sEIfS5mkWvfM9ZmYTPkWtkJKdPt0RzyAMkWNWZcA6b
pOauaPzQQ7WqDS8r2xPCGZF1ZPSjA2XMM7T3aATgz1xJJX2upiWT+0ISQ3fIifW7CifWlckCXfXD
k4GvcLQsv8U+yHRLSZuosdBhcvEaG5a3Vk+Z5kTAU80TbtIWriXSwF0mGMJVwQAAA6NBnlhFETwj
/wC+0jauGVnbO+Ekj4AJZGHAN+0gWBgP6MYv7Q42/687usIik4i40xjQky4k9dsLt7x0Vv9/lJDY
4chdgx9NVxxm8d3TaaUCJ3EzzA8wL42skXnvewqGxHG/av3PR7ziUM+clRy7AQCpfNFFoPGaOW2a
gQrCmNkaWjivjotYI0w5rHbIZuBY/8cVkBs5mBkl1bRQ8Lrpf7pzkedyYTRXXsaRYoH6/H68lWPU
5TkF5Way36rT3qs9HUIJ+1IfGvk82kFbpy+EPMY8qS9NKCf4DDpzfuAnOw7rKjEo91Rc9csJ26AC
/8kA5pyvMpT+pyg81fnrwDnOGuNh20fVmoPHPSKZPVv2MWFEupgolXe3riTrELKe2R/bezVeRXTY
PvauPy3x0/zFFMg4srFi6Eb/N2ymGQxfDbUPpcc7K2kAHo6ld7l2bfuX9Kh9x1azllEWUE9+r5g0
VuzynEH0ncYgM9XYoKtJkoufgyxgs0a8UEg493OJfmR48ccRDJtrFCnQ8UG2T6kiFT1csJfQLA73
c2KWF8jN8LpafMvhS9CzI5KQDFT0LQpiIYi/mn8qYHRHo85d2rbqVyu/ilYJwFn4+fLNxE2pwNYf
mNbM6IodIRzUKFN2BSWdxqzij5ZiS17BFwg08OCg2HALNIQdHiuv4qv4Oko7jMngGjF/ngznDhGf
DaOe6x4lWKvI4V55LGZF89iY8CnQ9qYUCWJZx+PFEOPdiFQ/R0W3YxIufpeW06k2nKo+cwi7nciu
wN0Q/tVIta9RBV4gpcPonsSNzhE1eCBAkZl4SQ0nRVBUbMok0ftEWVxcNz/IFodf7PonIeY4/Z1Z
kpCei7L3irCokEQpZ6/zy9s2y7I+KJ+4gWJgUTvz19LixqMXu0PcBEDTaFzxMe7rLzIqKvPt+5OY
bu1cZOoGEwPDHFQpVOiJCnMUKc2dbvqaU8x9kB6oJNIssvi6E96GEnl33njC2Mp3N4cVZRr31Pe9
TkBYB7BVdC7UlaI83q+IUU3qYPUWDzjgjxv/chuDSqT/jVgYHEaEBj3xAoFg21kjNoECI9bZ4v5p
2LFBTpBD7Of6o+5DU6u9DK8QDVChsvx99MBNXRHXKeMQNy+Jg6l1pdVOFc3ZqTTPondB3fXhp+KS
+0+QTpf3bi2G2cf95g22sDaz+iTqvHfxDBk2QOwc38dpmoD1KN+OwCXSArOqe+2lgmfmMFFuG6dC
Hi+5mtTlSWJRIE35AAACQgGed3RH/wEtVnXdAAK6Pg41nO1VGY1yFFrxExOjyJNTOpAM+o42zxtb
4Xxz0j9kOayrdTuQvIOeuo75MjUeL9sJoLyOdugxzlLzBcX4FyVaRQ5qodoqQEojM/0nQRzntS5P
34vMvrFllPywcnPgcXV3dUaaFrqKuD37vNYmLYdlsQzzf9YwtsdRQbxNotcrfw8r1j5TDdT6Rczc
E6QX12m4c4g/7CL1IqZ7rSRUxvBHTndf8oIFmXIuwWpOtVfPFex3U3Emj99chTEQOv8Gu+Yx3WG3
SwkI6nmv3B7/eY/A1eGKLNSUQ9MlcnQfJX41VrgC86r0v1Re0NamjgAPYmGOEjUTuwxAdFj66MQA
RQMxBlB1U3xcZrLdTFki0U6jnhPb0xVC/7Jyb68AFfI0bNvGYOOfU+aAlwi0jkxYHruQk890/Abe
xRcfsuE8dwGEspHqwwanW6VCXSI1iphCuJpiKcEdDuZk6lRPacuPF65BLzYxehgiO3LUk/PutW4A
4ytBHF9+uB/dOOxEJxgM8KB8n6u1vGNtFtGZ3+h5U6IYeNFhDnBjJhloSHMKRL8NIOZNi+amkH3u
/3cv6ww35z8PzMJX0OsO4qMKZyAJwlkkN4vZajd0c8tDdsmlgKJWEY3FtiSUnB8jYf8INKx6VsYH
LibaBI4kiLCtedmAID38f5xfG7RMU+17OseefgvTw1Byxm4uDVa52Z3skC9y/DztIS1CrBkuDfKm
Xcg6FAwGh16l04v9ltAssoxG65XzG9lKAAACsQGeeWpH/wEspgDZmiAC2mhHQvAr8fr/+K7cdZID
737cKEgPTI2UcVMybwv6qy2qmqap85ZIx5Wev+EBMBulr0W8EEGO5rEtWEB1ch78y1EgCpecmB+h
YgyPllMcgoYXFKec8x9mNyShQrqAIDRWg7wnLfgcHD8GLslbifeSsb99/ak7VYevCZElK5UzjhfT
fxkrdZODc0dRI+vVRetVMMZRKg/q/U7JY0Hvw50RLstyoi51a1Spi1+z0HgW7qE5ZmrsBIKKhVhX
GGkkwI9myd1IZGH01XOwcVLzBUWihDZeiIzVvJhc+Rd+e7E3r//TDF8WP3NDDZloa/XvhG22TTM/
9qD59MbBs96I1f5Y/9JKMne8rCqyW5sCR0/oSUN0vSH1Lm5+6/ibaxRy8R6SvR9yY810ZfIooy7b
yQ2ARYBaEYtnWwqdAC54IG2HOMZWhziedrFp5tb1wDMgEQkDSbBoPzxH3WfKNBF/l3jJ1ahcbL4e
cdwgwQSizONBw/ZzRzm9gJagYywihvmMx2fuHZ4v2UwNgSZPo5QQlbNGoxSXzRfkx2efCiLXS4kK
PBWCPsvYGG9BOe+DSQ3FtzgTfRMDjWzVPBsGD85aWI2IU9owrEQ2ydZq+8J6kaCjPcTJm9XmOA6z
Po1x0NvmG3JLrzctz79m2Rs2cHtcVky5z06U31Ala8KJ5WHzydMzjRWxpeD/Q21IB9O6iLXyuYHE
3ttczK2hLuTmKI1KLBDL7tVpjEmlVXQ8kMNDR3OyjanFYw/a4oIW/uFW2Mlpv+OK0od9UO2MCPYH
bvXbZHsA5n1DaHOFlX1284902l/45vNA3dQC/89O/0iZocNNldT2/5ltTlV3jOy61UDlEAyKnYMf
iK2XbQEi5depilLja9oEvVzPWlH/FK8iF4U/9tIYppGBAAAHKUGafEmoQWiZTBTwv/6MsAOkH5bA
CaZNL+riN3KG0h93eBmJmxVFg7PtDTiYxha+AvsN/1VCqkJQrtxpQSIkY5G+OQjrP53V2wePOJHR
uVCjQB/vj8eiCrUQiElJYMg9txgiwdBEA69WDzmk+KrxhQFiu2ECFObm1vjHIHHJ7CBj2FZuPxkJ
Y5+mBpEBkpn8bO0d/9GXZ2B8znVyhGwdeiJCdVgKGp9pBYdGwq7y8ls2mhYVVdBvVsAqZ+2RGhfD
jGJjSg4EGe4Q6glA48KV+7ChYUoHU6ubkJIh6zA7sBwSfzY2fNzIqH39/HalECvb1Wz3IEPX0570
FMIxPo506gIyW80frT7yPVorP9vUiAC8kXrvcI1Xycu602mwasRBDVksqIoYi/4sGI3B6+diCQ1/
ZcWV7Jm6JYswZ24SFOPNK2FYIq+dB0LgmBxP8EiTCVldiKpMTRJgxb+TOEVYHwpQb9jNuR30GsGe
Jtb3yZWRTe7+gp8CFzVOMUeO4V+onWYjOF6CCiXjZ83TqHYBn9a1VltyUfwmv8qzVFkMpfpepvs+
T+U2q5QXNGWUDGmFa42YeWUtbGQ+FT96dqu/b4cg/Q3hBXsU4zAGESmGPpqy+fm+LHE0jCRMSjjw
RCNBn5prB+4+z4CHTejZkWYs9/HpyT74ZR1TbDD0ZmRPjvox99T4G1+TtVIiSipYOeRLZubdQw9F
q7zFBqWCpHG7gE4dlbbwxdFz9WUiWus8ULMEy4gCF19uogguVwp/ntZu6uEK6ZbR83rhrS0sFwBy
mJtvjDUO+rQvBuXzRFnYop/uhxMwJjKYPO6YQoouI6SmA8pv3zAXSaN47YR4ahGGm2DqDlh3cfGD
oMYKhMkFlZJItSSTI+ce9ewJUzVIOq+/vlupadn+bTyDXl0ZLT2RW6iaAYHLDTq2mMhD/7Zn3Jkn
Oa6vT3I+d9p7N23EC88gQ+cNanowfx4SJXgS4OHRl9/P3CIcBZvD63qt6dMLP9Qf6n/UYsrBDwG/
VAH0AZ5ubrGbeXvHPLdttGg5WWH9Xxa/YC0zAzKCW8mBexzsKk4B90M98ifZTFhvFanm6QW7X3Kh
3zB2/KZIk6iEt07iDAWM0okKbMVWkiq/yDuD18DNLezXJMwJ7C8UTnLHOiwTftO67ALCofXJKwzr
K3iA8vIbt5kGXKgdJeBlnGQc6wSNOWCBb0u6DRoX2VIwFA/f3Q6Jn07DUKynFgrqlunAvZYYr08p
SAwXby1REZtjrTPAeFL9NlrkGrkQUJwxN1DbtC9fx6RW7X0CdPMeI0AmcwDDNgaQ7pbSxlXo9+Ih
Y65GHY7j1viZcydIv6sDtuOVkNWfNnmcjlB1OxaptrKrY4N8NkydPZw1oq3DnQmW+XxgMkjw1Bsp
CGjCBk6VcgOSCqSoVNdd1s4OmEdl4Pl5yEByJxU6oGnTaACmbnYhLNaN6e7an81oipxfVkI4N/wt
gBIZh1q8jEgfhBMRPgSIhQaqwo0uAaL2oN0pIf8nxO/zcbobhyo1NAwf+W2PEEMQf0xWCzrZ6muF
75Z/Lh1lhdOr9c30cP7OGQAQifCzzbRBmM4YFwQze1/hcBZZfVLgHGiCziQRJcHbSBMK3tqNszw/
WF3C59cAxBn5GSoLstzZVEqOiaBsyRqIpMWryH9q2h7BXc455sGfgOpmmSuE5GEhB3P7trJL8Ucm
9nTkiA8sGvwk40fe3oTgpEBX7REFXyc7qdQfJy2PXZGYSGNBtYh2+QdmhDs4raCL7DJkbs6rMz6s
mUUOByNsDdC6/qBnNMzwYObt8Nsvb0BBdBDBSMiuG5xrFL/ZkVAdeyaA3bNW1zPu7PnLdjNeyCJc
WLXhSlsrbvjAbx79hxwLcq6jUEtaVkzUm03ZV9Rll9ZolGXKSdtH8A5+/g+Sm0LFMA0xV66rh34i
TA99sKjok6zuoa7yRDYLj0DddR3dVPPW7nCSTF4Uw4GCy0SIYPjeoUuZhjHL/aw4XR4fOxZ6PMrG
hQ1DGlS63Lr8G9behdVz38148AOzDcSn1KiBYQ9+LfrvdKaZFfXLxgymdP1dbGkbmtO+6yF49kUb
suZMIAvHt2fRIfmJZqnL4MACOxfEESmS9TfkvN0BM3Y6r83pBCPdeUA2lGuQaEMqLduY1s/4bRkn
7wRWa6hM+cW+htJRhbgf7m6Fg6DmB3cKpcnDRmTjL25F99ZT2Y24hbAo05cMe+Zmup1M1r+pe2l1
aPNIDdf4j+llv0KTdcJW6cXaxQU3fqGjJoB3DrwUfL+uQD+keMQVS5fdI8gLHLI/jy8siGqTDjBW
7Afs9GO1tbLh/aD9OM7HAL9g1nI/hQipkjy7bT7SRJSiptVN+4RUnE9xC4w53KYVc/u+fb9HZTxh
gNwt2jEc/uFT/XVrZLf+RXWrD3eAomCUjfx8McPXRJW5N2ws91S8URzhT+/M/gAAAosBnptqR/8B
24B9/rT308AH8/OnQSinKbWxP6raHikzrq/7mMYWzwupo5SD859A4GJJmmrx4kf52hQt0HsZt5B0
XjT5z+MOc2CNYwkR86S/FXfMefOm4EjOaqHVg/pghOrbMNM8A8Ub+Y6cgVLptxzY79mLLlatUDz8
CWyQaYMI5stPQ8142XuDK2UwPkVFqhvbTvdo8kmH5t94Iw0wLQcyKgoUw7rb26ZShEcwEamBGRuQ
A0NU+odHioycPPzOpi/5pQ1mRqdMo/oalrRDrKuIwv1nw1ZozhKS3f+NQ4Afxm52Jx+ONeRXQrIX
TpKY41E1wtRoOErJRkplKGzx7MfWHN9gWrORdGFrFyOOuqodi6bp6tMFoJTDxa9tvvpDCIY1vjvf
bSDozyIUxpZfqOy7urTrdSB8uTIgSr5KNT8sofK0SbrAtV0Gq7FSGXI1Gm/5eq5EsDL+yIJEi1cI
6D2HZS6PvooCobhbaaIR5ZUoJnmiEJtc8epJLazsehDFfkBjIs400a4SKmNEAzW++T6fLzRfl7ho
QtHI1IQ6kVGl9Hu58qPDtz/WX/qZiy6XcXDgrQAWYwN6v7zLNXtdT+UAG1Vo6bW4dhgVR98k5GnZ
AkROTXFodIDdFGbi/Dgl1YU4C/93+cjFPNuQyqs79UNf0OPDfD2+S11VpcRgWAex4utRv/9tQjwV
si2SdkN3Ql24wYmICywS9R9q1ZweokVfHuoDWuoxlXvW41ZO30JTkPUcm5/ic9l3x5NE38904EMv
rrM00Q+nEyAfPvCTDVPOiAeGUO78hFNNg/EaCS/b7SsqlDNt5XyoxN8EeDidONl983JXQV/LDOo5
d7kxqUdWyyAwKHACZPHnG+0AAAbcQZqeSeEKUmUwUsL//oywA6QftoACYh0pXn/2U/8+/aAHjKlI
4crdA1fLocBfXYjieL1t5i/f9p6Kv39c6P6+LDIOddOB+Edi+aNX29I+sYNozJXHSAFdgWKk2vX/
S/dZw34tRWJ0LahWdNS11w+H2XWrTyUZtL1WqTqeCtdbfEefJAgmOsxzeG6tdvKvF723IN9BdNUG
Ujjt5Kae1fLmV+zQHZpCUurmCMx+rqA116vWhUmEm/ViKs4wqvEKSdv1d8ViVzQfu+/cM2ROJETs
hJN+4hovtSIuTdes9J/rYfPziDBFjTQKmZM2bq35w5owpElOryMtv3ryFDvZKXb7fa2qYCzlARS+
GhbW2yo3MGce6rjeg06KLeMk2bO+nI1rg0Y0EedwP/2kuKHY6PnUjXxCajqaRqT0KWDmSyY6oD2B
7C5AoNZX9y+dk356So1ouKjpz4k8AidyRWi20+zm5x9zYrLhliVTQSubZUZLOe6bPJp9hr+BMlgY
Nkr6KJiF5BK/kMyFoZEBVVc11EpswBR28QSK0nDvwtcL53EFaODrRTl867jRDaTjtWxWFLCjEETB
Zsq8oTHBM0jiTCIieI4Ejw2QRxjdLs+M7pqJ95VC7iAa9zO9NhfZ65eDLYgv8fEhTyrmwbT1vp3u
aH4tBsT9Fn/++gQuspXgU3eiVSKOG6JnlGdOIzE8IyFtBhNkpo6e2pg5smcVHr0OLsbvYR07xb3W
ShdW5olVHq2gVi6oS1pkly9Ghp2Eup85Bo7rM52g+O11pNr5BYUOeisfcM+Ffzn+wLvYbsoLOl/8
ru75e65TyGVsL5+6kNtHyOkyhgVbFTCj6bYB45rfU5W6uPAaQTSaFwMQOUOsoAi66mmBG6JTBncv
TscdFebfHc63K6ncnnDKE/vqDm3csMtFO0yLpoTYb4mL3jswDIjRZOmqnjGMCNrg74gpcBVCakJN
EdFgqhaIVz2JY/H6X0cjvCY+1PI29JoYsrGD/Hc0aCsxZUFc4+6Az2UNnyRRewPEJKTW1M+FUbYT
l3g3QmGSaH4o7XA4SSx0VWrJC+fIDZnGjeOGi6+s3m3laQuYwBAoXXK3zjuE3qgkPkhYS2GbYaBo
0U7anvUwwUWeiVc0mgxQC5LIo/fSIwS0nYbaTv72PvEDZkeJPOLpBFwFw037j5lWMBt1oK89nKFL
ECcCPcj+Av++7HvsmG/2TK031PsnRctyoNabQ92SQz1aIIOPYKkyuDQeU9R4YGSROdPqv3gZA28D
AnQvqxT7h2kbaTpsT0EFREPFiYgEyNWYI24D34YLyWsM0s5BikYj1/4l3WlDGuFpVmp/8pb9ZG9b
ZlEJjP20idS/GbwIJhXaHkYSZPK7edw8rZxFR8JeXgv2nnN8obYvgBPHeNPAvJHTu+BIergIJwlD
xA4nFu2hzqbEW82L7kBAX2hI5lC6ihTIMo0ByzRM8uirjp42bkgxMMc6FQdjV/laOaLRyssaBXHK
8oE33+HLGiFubsbGfV30ekqZiWl2iY7VPFmZfjppx6kdMnRq+QAmPmSymkaOZVQIjmhJIP8iaFGH
N5OSIKKw2aRGmMNyv2fXU1nUbhFOK/CJ9oXX/l39/0rLn+733fmT+ve6l92pP30NloW4DS7DBzeK
8nrKQ5Ki21JQKDiCetp8RYfOA/bcZ6P8JL2tJVPjDkD572O3K8zfQwdQXzEibpHeuC/ZS7Ne8hLF
mhp5aY8b04pBmutfo1cXPJB/ZI6v/igMyiOdAnlv6fmQFpdmP8cHgOz8qrUM57zXJRESUJBfiDOA
pGU3iQg3xLZnCn+Rhojp017drJqmYgS5xND4lWrjvUGhDM9DGP6/jtfdRyNAngyIE0F8c1MrHo1D
Y/mq6L0iiIrVUQHEdeb8Tk+42+QWIiRz8cE6BnH9BmFHtpt01Jh6Qaq6kSHxqFBI0aX/YsvPK89y
/pB7AEWsSSIP2GPU2XuwwopMdnpBwipcuys+pkKSkpSnJYuNFUzsH3Rt64Oy1i/JkHTF/z+I27Lp
nBR8p6nEHv+Y1/IGS58O+qPhtv38dqD1X5wzGl7BJr8mzsmcABaeTcfHa73rAhkz8vVG+PA/fFcR
xt8GTIg8yHP0gCG1EGqGHX/NNPAPBeoewQwnXLxoy0+J++wF+dLHLIFCxsoB5HyGvoSHJEi03XVB
F1xFSZtBWxaFO8CunAZmotYXhhNcdMQfA6nOJviGDgBUo35jio5JriDuvgRmVloWbF/XSmFl2T6Y
RbIJ14RUdNbelEBPKQqQGEXNhqy19Dsx9fl5nxr1J2Qs2rKdPfB8g+rExRA8oIWvpcATzAIGY8gh
ka3mIcyDCWVJYQAAAtQBnr1qR/8B3KIEAENaP2Gz9/g3A2gCUsJ9WRn+v8kZ3TWufGwMkMAmX1EV
JmI93rBc3rZiTRI2dFYvfIk8zRCJobWwxRlT9goQfB3gaksASQZbl3iphe+HR5PVs7ucowzp3GQW
pxBKeRz4O67chl/HzPS4+RZ0ewK0G30R0dMivjvnJDCdI/eSvsRNCNc6acg04M6tti5S7taX2zPd
JzHZeSmH7gbcHvc+6zd68SO7B/fYKzXUIoh03o0MnIb3+H4hFcwZzRKn+kBUPBfJ7Mq4W6lrujJL
Rv1yw5+RrFBJb6aMECvn3xrGSzK9e9AEzHnPiz4CxVJKt+eYBNR0iAzNK/OWZirSNFeF4AAfi+Zj
FSt/RNlYV3IveyWZ8Nv+Gzimy1Fe+ofFQqU+fnIm+Pc9yxriOHiEQD4eIOzYfYlBbN/2lDFoyufo
QzJkYMIMlm3ff6i0+OKswmGNmErOHxfqWuMT/omT4oVhtCuUYo3KhGLgY3nMjSdoHKJU0SRX8vQp
KQXrIms8R7mVsmqkmUjLGKxmqXRhM0zXVoJET9ig1XIGLtkzaXR1YjRefOkT9HU+JJ/Nij+MA8Bo
onwFiAcoJCWi6z7NpD+sESL+0H+C6e8VJmfpYeiXcxGi9U6bpvcpkhEop4WIQZSVu//IZKJE+q3S
wh3iIwutNiEkuy12FjiUEGRTE/z+MDXdIChnxh8G66OR3f3D0bENFc/m8gZyWa3XOt8Hhj3RD4D0
M+hHnNbwZXdwYZPxCwOQZtsms2FviuT9l7eRYHmGkMmm1AgqjofHeqzT48FMuadRFcuxFqUkWhrV
iQbocqp5+JEeXZ0FTvtat+5lxRywyNizIYvIxH+2oI1VCdCdzJPiPaxXh05g2YSgYJk5wNe41hhI
tYFef0MY4ZPhpbp6neXgmemm/GHdxDQS3FwW2T4a7ODLuL/blNXs8U0bLbgEwDPF2ykCmFP5AAAJ
REGaoknhDomUwIX//oywA6dknlbYAWuKjGdnvChUNbcTWgKNHGB7wa4m1DPAr+bjD6zCPDrTi+9F
sKwqGMm0V4uLbIytn5QTO5Iwe5bbddp6gNFj5leJR1deO+3hnXBDUJnAISxUOeTB1rpJ3RBfpUl3
AVkBZ4HzFSnqu1i8b2FmuzboFwcgHHka4+d4uo1YqImsFY5UAOvRPzFxyS9VHg4f2V+/c72QeIAA
6341FW7CJWjcHUXOIltPECgsvUtYfZH+Jw0QnUkSaDkXxOVx7bvrT4VwkqnA17h94iEleZcxUU7E
oNxovzjlQDspr1gfKzViSd3DZoblfih0cKgNryxiFN7yr89siwi7nNtIJKovuMsIlijWs7LEhlfm
vmbkP/Y94HjKqsdKpTaqT/6MlUP8c5uC4wNXQfqDoRqnvh0W8jjEAiEU6n6VTXoqyMvTHgrldnYo
zoVAKG2CX10Unkr0pjdmTl0NNmXtNLm0XLweubmT5FwHK9EOk38Nzi02SJwEu963nzYf/MtDPU8q
UMduiGiBZky4WML60SKzDAto/i8MJognlK0ASU/gfQWT+nJEAd+tpZUnBuZ8uNcevDBpwTSYPxE0
2rDtgkTYqFsHpdA7/DAFLmaf4m+RL1SZuC84bx6GrE5JEcINSgRnuNy0pokeKlcp+6QBe7jrMUo5
DHQCWIWgYghMfXhGXhRL6gKbPJz5OxGLbWHUY5r2VTyiI+mlG1EmUAPUGCtMB8bdRqbefoWq5E1+
sYuj5OKXiBkrHoPT9+zYzoj02D4tWLBD9FoMISNzcDHYdxpEr0h7QbyMAgBGnoY/WPkLLxdBrLcz
YhLazSCAHiRh93Uv7gpMn1mtVGuSfQZmwOelaplWXqgtZIdfmcb6YoWLTwR3AJx84oaptjzrhwrc
kzs5UAqcpzZgZb++0i6V4wU5e+B2nE9lHSZlYkIU122MSf46cCgzfmp6ezkh3h/SmZCGBiVcMSQy
1zUx7nxd0T+NneNMR/AajWpH9oSV05P4OxJ+ZCRppJiR1cMy4vMUuZrlfeVqjk4TbCoyBlTslqys
TWVIwGJCdu3xVpGmOYwaE9Sd1m0Cmd76GOWmYqhpJnJxXOD21zLvQgw4XkFcc4ZRWuBhfaFnk0PT
UEVyB+ni36YjGiikA5T/g/RtiJdzTGhfLQc2Uhj3y9ELWkdk5u/h76Hp0k1m07HSairK9jUUnn8I
jcZE/+I1LIlroFxStrZi3f+tEMf8eu/guoxtUuyNGZ2/P9AWm/OcpVmk4JmrUZxXXla0WFq/R3/K
oDXhJJk7rP7fb7YKO9ePhM/OZd92NzqKkXQBVt4taPHlwBu3xDYn9Bp6IJNHN62ovxQi3zgkUz9S
OWcxcN2kpw3ZuuUwhbLT2xyemi2XEN/H3Q5Bfk+WZ1xDOx+GqgAwSA5NVVwRXAOsP3Srvq662rf6
G90QCYARWi6bmn1hxdZTZnZgSp7VnNolUcDWuRuQhV7RAOZrb59CxwwgcO/l5pxjze76mVoB6fBP
7oZz7y8kasl5o4TY+4xiv95uRpdt+YXGoWHEgVxqFIcLkTcc2LMml96IQJoGBam3vGVD1COYMHp2
Bh8Vepvp/EIn2EftqeJlew+8U7bkB6jP3KKr/Js6EfNk+U0xEw6ro75qxy6L7zWvJhSuwuCwKLIX
d26JrjRQmGGjWVhf/uRL+vFVxao5/1V1fUYbEXRe700lZfyBQw3emXrmVOnjg9nhvhXAfz+ovklK
zDDuSDjiE0rxu+KooaX0uL+ZQMmTfHMaXyA1EA59mLLwb/uyuNCb2fcel3dNPi5zECId2KzH0TdK
XtEcu40jqAFoI6ELzAcFpPVryMTEI39MtyS4huR9dkb9VDsjeWUyqH6cdNlG8Scrw8swSe5f0N/p
0BwUzlwpAh/zfqs+VxKW/XpWXj091joL6dMm4seUnObHajbhnoiWRJoWLvhSc9N5APbkRUhsVL4M
SeDFBMW9URlVahVDA9iVwushO2XGs7B+IM87BPiY0Em00DCnw8vyiHCQewQaxi3wfJNu2GpKOXE2
sYyOaa6SYchAo9Y8p3IQ2sichnsC9l4hglgtsLfnqOBMBmyAK0D8b8UjQvGe0hh8dz1Hk17/1XE9
LieSHcS59UC0ZZuasThGYsP/V3Q0wRoJcjzVbN4OqlBnDKI6Tqt/Z95IxuEo2/T8pN2KC1ymKy7t
QA2qSxljrH++88gIJ/+E4hUI/FYqhp3qICjEaeB3IX+CbC80VCVSXd0u1TGkNJ3F2DRsllVWthqh
azpcyRL6+5hOfFbLMkBZAcMkrJAVzoxCuLAU0fr7DnVeCIiqfyP4PwagI0fbMR7ExszzIvgjcDc2
i10kEK6iG6lNP0jEzMDhL0PQHyjJ0E81kILIYRzgjsY60zw/eT3uYEFU3tvwxykgfjADS9x2+5CG
/sGQetDpN3zZvIX+0GiTd8KOdtbtkFYzru3BItf/UPLNiZhno+32+YCABNKmNQpTrhRNFM+7IiPb
Qwq8hcubVaGsG9WntPrihYcl2X/Ly2Mpt0ito4adAkxqSSgza19LiBaF4tziJMYZUXwPaIjmns6t
Bhly8jWtyzqPSiAzer15dTN8kjKKR0Kdve6NO/oyuePT/REGlTM3UiJxL4/mUwmfF+N4GX6SS3LZ
ysqU5a0oqKJcG3M0prp2vYKqvcXYAtye8TIwtQ5R2shGURqlhXdCRSZOY8lnfgWVcQkof2NzvQ2t
nAVLY29xGc7Qe0Bar5CJmqpKFulaVoGBkKExWTlGlqDu6mgjrKMqZotYueTugTEqtHP2pU5r5gXR
l42TjAyn0e1N/x9V76oOo5IjDFn8B/7SlVK1JzKP0/9n1cFi8sU91N4PERAVgwBb7DmeHvjq3kVd
vNqBroHLGfEuPWOzlkF7TXhVoaUBYUUctMlW7/sKkhJInjoRc2Haz2tblgRfZRUZc580+ATQc3lE
8B7ztyoE9D0xeVjYr+6MSzsPSzFk/y56cpQ1wlrCJ+WSPRhxvUoYocF9N7XZhuiUTq0Aar+O5Z6R
VbOPH/+Vy5228reuXCS+tZPZvfT3cYPMPphhKIgvQokp4+Mi39qJO9C5nQGddhz2Sc4zPs+MnFAo
yNYWSerPjCJOL5AX/G7DQcsvQOeTOfevEObtk/C2prWhzkeIAAADw0GewEUVPCP/ASsbkTgGiAEp
x6+I+9jxygPjAM27XZochjqQMN0QwdlrcHF8b7a4rKXhP7IHHZy9nFW0nngZ4vhosNUr1LY1Wvlb
82xOOWN20qexpSF3EtjZoGhEL+3EyD/JXM+M64730pfrQmk6VbDzyZvkeLgu/8Wa4YlkEW/52M4m
8XI9q6bMl9RltS9WIxkF/YSrZ4+rfDU8/IBiyhUnr0rR12mEDNl0/C0pgQE7vu+GDzNfBgkPz9r4
FClqKj4OLkyhRTPDrqp1BflMZ4E8b8F2ab5DpfPliXvX2pabbx4+vnVBDka18bdpTQ9sQD6UxY7N
DwgcN3Zu384t0bgDF+oyEV9gubTMlxMwc5qh4UcFPFb6x89rahm2Dv96gOQlOQn8MVGp0eK69JsO
IfTldtr+7wLK8bb8ma4JMuXYDQaY5g4Ae3yJm+NOCfYZkcEXT+LhTT3SjJ0ESnS5l+eL5lRBWOna
He0nelZeW/OAfJydoavTwitQlh3ftJJqg/Z6/ljCvM7lpD1Ntvfwvg4+KEaHnk7dw7WEEAI2jICa
tLDyHPHjsNm/ObcVKuYPytKQ4ZWIWbJgSoebjPy4sXAIkS0mLOy/y025EWRC8wj0kQNrcGgsuFP/
HjVrySkHkYNcqprWY/k2K4ysQ1VapP1fv4EA+b7D277c/4e5jGBbYBQeCHwybHSCyHGmwSvFPdP0
6hExyUtnIFnxLrHakPq0jeS8gFjl2G2TwSzevltjp3+GJtubSfF1Ndg5aRbf9H3HXWt/0pFz3VjM
snVFY8C2wkMITHI/dXpxUBlLh47lz83I8GKvbe9Yivr6fQS2Wi1g9eML8iF+TvQnqf4BI9ZZUO5b
tlfenEMc1+cMAlHVMiu433yhtuUsoAo5pMiRjpyQfoQAvtD4YUC3cEZTvt2TdRmEQi2oHDBSWDGq
rMyiq0JVhN81hpvpwmQr4SkBt6/EYpHw7j91QqHdta4zzxCXtRmsYBNVfLM1H1fcrfMALrP4jF6T
R3k3K5CPTf71cO9yPb7Qlm8zMYawM0CbZFu0hQ1Tj+3cuYmAQEqQIlSd7rTaXMY0CJTtRNqUH+xf
uhCxXAb8MCWIOSJ3c3jze5HuQ/VosOAv9CEgILPLKbF7PD/Uxn5bmJjdaCsMtgMtYJeJH/8FqkIi
U60ESyqUsP9Ghtww/mVkC3rZLAAzzrPb1dEGplfQa1Je6qznjAv6gOKxDAuwviiSiNR6LF/vM3xk
N6AeKeRTFTaGjgwYfB22ZNcaZMROcQ0mtzPxTYjTfIXYEQAAArYBnv90R/8B3KIEAEIUXmhF9Jnl
tmMAgapl0oMDdPaMAGLJ4VETwWVp0mZh95rhVaPZ/G9gsNnKb1OvvEV5ZFYWjSpnzD+daY/cLM8m
EJASzG7gBBYmxaISjyJ1bUlMqAek8H/155fu5NWfkdm9fDQ1+RJQOadgROl/2BuJHauUjMhdWR2C
medSMF6HvWuemy5IqLnwJoDFIhE8GMPT9bnZHyaSt4q+iwryYsXqy3QfAOenTv52ZQn6LziaN70y
dklQkeiXJ1u8mwVKLqNxisgygzZfsWfV2jbd7qr94+5NkbCmFl9aoeryWYcUMqEEt68Kv9X9o1S7
1jstHHxLPkLhq3yEjJ6H9wJvxoYgFy3zlwy16mEVqCWDaSg2WCkicDMBJAHMZjGdecmmq1ho3Dw5
VJbEsePMILcPV6RkeWXgT3+nCl8rV4zmermW8HWemgXRs89Y2Fpo/EMAT/8pnXQnyz8C5+WHjirN
tOZJaFgiyBhy8FXT/iAzRg1ZYFDoOFTfW8o6uMj5csAb4zRhBTPEETS6NgMZCxCv2vuXOxje4Ecv
3NfjETbUzohznNj2p4/tD7l9m82UMUiSAI2tTE7DHcJFd8uQIq41xq+iL/5LxklVFyOEkA6+oB6r
2uGASFIDofED8XnKriBaGFWMMN4l9oqHrV+on0ti3q9lgBw3hgwhKXXO/rzJ7/PVjSVMldBR8L9b
iy172asZmgWerGRqIZ/DHqoYWe4ytWJgOQJWuaAsL0pqxa3x1md0fNG9owQkl7LLmJyk0nUDIi5Z
df/b+x6z/5QO9ooIw+ijuBsNr83bh44Sc/g8Wod68AkWOTWwnwDXHRwcF2/wUsSeyWc2rSepzT/X
FhFL12TNBr5SzW8dxDtZhtGaM+JeM+5WPWSh5nT2poqtedtazTAhOKdoZZfdLfeAAAACZQGe4WpH
/wHW6KrpsABsoOeXi7rxKLy7W9wqbfOYXRkp1l6+Mqx1uUvchkyIzfBvVe1IHKfIPyRRXRKLUu6H
0FiV5xunyZTeMZFr/Ra1GqnDgzYlREUcwdqUB+n3R9xbcZWDmzpet1A7GXXPEQuj+Fi1owdJBUjT
umxCeaRzJNv4RKG/cnyvk9EOigDGttF6w9hlEQMuNECBLF27MsYu/Lg35a9xL9NuBWfgdNHws28J
bZXM9Uy8Bg1/GKoxguyS0jHQoi7Lust6TwK6SHQL+U0zR80qGBw5gMAng6jc2i/atiyNO4kG3A98
ictujpx7WOhctIFF5BbLM+s/N77WLff1REPh9FVeV7zMhVOCP4xAmxJCCqN3IWvOrL8IFhgHTOXw
XvFnqGNKjc8YLdEEvmcHSHWu9cx/HJSVqjrVUAErPIo1ABslTsqDeYLIX7NY5ERIgy9CMYH5udtH
EcNJuWkmfG13HsONFAED+5ye1z8amVZJCEMHDqlGUWvaixHZIXaT9TM8oLnkFnhrSmnxDkWTsFg3
Id+Y2Ez+MOJt9iVZ9L2SkbhlaPKUK5EeEbq/jkWztq732I/ZfRRJN+kbOWqu4vrwb/4zThVwRIJX
1GsaoSgwCW05a12M4Wo8eCDtxxhbyGCpXREPGSPRHJ9+uAWGlKzICSiTFJB78tdxsVMHncCJQRpb
Gaxh/2vpTGK3NrorjvLeGu3USMEe8oB7BcyAQvJoFzIJRaH6H++fPstZ4BnjKL2Irckb0ExTx5Bv
6wzGj2VNWGiDVMyWVwJ1w/bMh7XEs6dS4Tz6iFen3nNGAFFqFOEAAAjgQZrmSahBaJlMCF///oyw
A6V4lzOAC4ubsrH54BAyX87c6cqarygrXo/A65kt9Jy1hC2S7iCiYtP9qPTEHoot8gRY9RsfMwck
p2RpGXqcaNrcO0L2Prv9Aq5eXppl+N1DxqiuJLsS5SAUSxvSHuPAyQC4BJBNaLM4ATK1nIlZyWdZ
w+rYmKuI8ZFEBPFyrlmnaxCOD1xQMoXuZ8iZbInve15FBKBqRVTFfKeLeLd091HmFHc0vezoJNxB
sC6So8VOUUUUw7nJw9wYYGAZKDI2n4gNs48WZjS8Ixn/t0el4GoA5gGZ97veBEFpbu7+J1S4Ka4V
Bc23+T07xO2S895c8sMMyjiGteQzcAQIn4sR4MYZXQVK5vlD/LrppyYmF23uP1LxrTMJM7VnU555
+QNDkI2999kQ/uGKBHVpbEXA+7wZXXHr/tQbe8pNKWXhD0eWYT5C7TH5yS/jH9P/6+hp0C1NUvax
aoaqZjMu8HzdjsvX0SpeQ3SbRfiT/BHTnQlGgokQSxNfih6FNxqJuxaL5pEJOSY+N8WkQXPZAKh7
puLpnkx/yybcPzRBFo9D4CQ6V5tIShYAahQ37N6nRZYPKRPwriJOVm06lRZCylP6EASA9wkJM5HS
2SstT2KtWxoomAhVOQq3TAs0SRIaeM4b5V4Jn1dhKii8XtKd740r2KZT2zVnBqlZkTRlFauyPsUy
2y8I+y0w9MSWyhUJBvfPJn/xcW9VZYwzelESluK8DDh+kte1Q/5/wFHJrKjLzjell9cqHOw/CJJq
sej43Y73Ja5564MHWMXXtu0M52ftmQX0nimzQ7iVprMO9CsthpOErCxXx4Xwnp900boz+8yhwR1M
Ac+r8cCruHD9mpsyPN50pPRgT0DRQCI5tASHuT1SggL002fWwwFdjCcalwLHj3orMUxNJVHZDS3s
QNL/Q1KssLZ9Ao9jSd6t2P4xk50VMHGUT5bw3dHjJhAubJ92MPD+zugjvWnelGXKH/NdRPFh1uAf
kQ52pbCzdH+P3HCleKA6YHj5z4YD9InEox6e67FWGYhAO8KXAeNhHx8RyQ3pf0M37m+6yJfSvl2W
2GghVNkANO3Bccz3NgFUSu/R8ERe+ZUHpHMbDFPyxMB58eAKg7gNhqTZyUAeCBflt1iPyWaX2RSV
gIcl6H28vmBgMXb1eirsQA17eYeJZ5EGuoW3wEi0HWC07OSmOlvZMq2TszSg/8mmRuZ0eE2aZP0T
YOd5+gbqC1DoZkuodfW+L1nrDqJJ61w2uMXuisInBSJQSATD35MxBQcwTbBaIQ2bCdZBvgGcKS3z
d3tjHQltkZ0RtaAQuImPr47VPjSet4VoPDZrLug0uhRnBNEGatYcIEnNrLfCmZI33sb2CiiyX/rk
O1BUEHiVgQJgaQarQNR6yGOrFhMLcJ3z/uwYI+JW3smamifuJSQ7XUD0jvmds9GSQmCRGoIe+Ulc
ls892W7GKVijocDHGhRqGYsCcbUcYI9pO4fW6fvFNc9JW4sVJnaqK6OPCEStfxQ1nubflrHQQH4b
7va5j6ON8WCB8nalyHu1++QzJc5aqladfMvvS32EelcGnKCcUJ6Iy44nMwHVXkCur0HWqd/heLgB
y7/AWWKwj3g1uE8R1nyB1foF4FtuRM6lPp5CEQLE7vy+jwMvHn3NaUdFhdQYjmtIQP5tlyh7Ygz5
RAItaQKTvPv9Kb1UL2c33gIaSrkNUkz2WJMQq1AraDZpBgTfwFTrnupD//xXt4keTIIbsZFa7uH6
8Lkhzwb8EcAXg9kEQX///2byuCwRx6XDx5DxunyRZCXbHq3xNqNYksARIsduUmZZ7PL7DmFAlAyl
5eT+euJ1QtEFoptumczP1VqyQL5muBDtKpAS+sYsSd5xuTeZYEjqkYKcKN1L7Geqib/d7csbymSC
DzjX+bPVIwYlupGjwCazaTIIzlrHrDpZLOow+eFXm1KB8sGZ+d7jrZqubU1nMLP0oqpa/kQpgDaC
hBaaXNQw3Gj7RmyoEWKSdLy+mzhIy2t7euBDrO2bCc2uoyL1W3GwTBPZtDUR+n2o1ALyePNnWED+
NyEU0W46RIAVISFrlA/i4BafXKu41SiuFXNdj/o5nKZC27MxBi6lt659Di84/Icsf1Mx/jdAIwo/
opnbxc/RMcxYX0K2ns1zL+gCWrIShNWElcy7jTStPlttX/b5MTqwm8MM5dnN2/eUP1oSrMk8CUq4
Y5W6trIe8QT102VQZcOpSvbnGS5BmiHlq/FABfqbLjrTCxm7bjuoSQcYIXts1fdyCgEgKJnE3+lW
8LteIOxsObXbT3ufpCQW2vysFTuz8MSFXu/j8gKC/vNThhm323HJUZTvHguCkNyEN8vWLJDR6sMY
CdKY4MY9nsWYq0SsGpvBSADn2XIQF9O88QRNpGw1X7rgnCDn8Dr7vb75Vck27BgTbIsI/dZAwF/j
ZbyHKq39qq2b3DKZuNY9kpeH/SC9ukmLnc2Eh2cmRTaD8aLdYsbOhJMCo76eTaUF1NBr+A900ivm
Agd+XbviHFqEjOeySySheiln0iIlj6raht/jLSAUcl61i3Q+24aKjEhaXkfdHiSX29Vo8Tfz7+I2
B/QgQzVezh3/3lxrJCS9kS3P0Qvl4KIO77FrFAG0oSUvcBbCYjeklHlTYdHSNthRLzwiOxBV8yj/
CykPhxcxj5/DH3BfOlUsrEhIfjfgM97YLfozLVzmv0jLzuzXVrNGcrExk/qQbmW2HnWRVX20aZQJ
Lg3Morvzn2u5f7PMoBY3UdES93BMMLC3rscdh7+c9PPFL415X8GUBfIVJPr9FWDHgn8wDDKSspmd
Y59TJQsePLcVKm9euBD/aMmgoiSXKX6Y0CSm2JxWtaeGwFBVoSGEiRdyvMz+AOlpea4ywBvvxjhV
pxBnfQcSgBxBzPfNeBfdZjTSLrs6A4406Yim6fgqZ0t3XueZtXK9qVkjgk2Wf8IIcZydDKVBT397
ImSRAZ2bBoYfQAPM4ooUHxptBHSg8UqPwgp/r9n+Rr7R8AAAA5ZBnwRFESwj/wEutdIAE4xUEcqb
S8Uat6lR3ZVg3lnVLt9P6dSc4En7kAKGC25ZaMCkMvT6i2rlyp6/apLSUGGVGvQG5vItyDbMSGs8
mAAF+UFX5g5nsvGwHsM45FaW3nD1JXuXZyYDaVTkeeHRKZeNWC1zZFNFGSY/Nt/4bnXOA1nHxvt2
Du/7UYXoH21B3I2QKimrBfZqlFXvQNPFMz4bRtmZoB0P+4knILIjoNEjcqkNy8GH/tVkTV+DbIln
qyI+4jmKQbLQQvknE6Lfx1bST0Yi1uFfN54RDeD3ZjsTON2FUIWUr+T89ARTCgx3XQ1RE61gZ0us
eHI/UZLErotfgNpNyIsFaO2B+vkg6jaERkvRHu4Y2aRxVHSmfNH4H///yypijdit8xc85cj7+kce
eez0xUJ/k4uWctS9ke4qBN2wbFLQr/r0q/K704tffdP3lWr5BBmR0PrPVxA/4g+hZndx82QPd2g9
dzWaLJ7NAAIR9ZPY7GUzviiU7HWAt7McvKDS9TyqKdMxXQDVQJV7rABZsZ6rHUK8FfjzMy8exkfA
UdzHu32vVl0mENmKrsQfvWP90tVIOU0GG6vF+rSg3kK1KPTQVKSvbCFMW45s2VIqIB6IDtEXxftb
MS27sZbw2SdSi4iQmR+G89XGxzBdbcw8T4hiVzaE5/q2+FAut45mGdnHMdQLrYJ+qzQaXV18eP+H
lrARyANxBn6yf3AHt5UooWaS5Q7dku8dlatheBOS5XhRAL9a1MUo3oqtBaR+EXuZFrm4Lk3XB8p7
mFbevH5/WJWP9GpqSJMpWkYv25Z/r4LVCxstaLZW3DHsdjKXaY76RS54+2gOlmEomDFsJdoeuv0K
dx4pv6/J9ZmG0LDQInhrTD/fElt+VWdXpBqvlFd+kaT0M4zOUETabWMEUNQ51xzNH87jw0NwsiW0
Y14M7mkbeyojaHGZOc4Os/esQ5aiOMDnmXhxakV8xe0lwHxaVGjOJ4yytAehd2NG1VsYLxgMnapE
eD3F9UIG3/GNZVgba040HA3BwVJHltT8nlBKlGrN5eYr0j4hw33NY3/ggtfsz4/1pdFnL5Hl0Q5p
UhOX3OBw4ooB3sFDY2BKFc78F9kprsR3gQS4fY/Gmui0PgUaCh3qLznh8ObAAPycKb9T8zmDlWiA
GZCHQB6g9Sfzbj8Ny4FboWifp/hBTVspFoG4AT/ZZ/G3hhfV7crYoFWVwIEAAAI5AZ8jdEf/Adyi
BABC/c4ftv1BNyzsaPb17KX9CxAgU34TFbN7Vdyqqwy6GUKrQs6KU7hOxxIn65OClxtN15HO1ZcV
s3w9w8p/k1zkIE6Fwf+aYG+TJOvNfsuX6oaSEpBWUIogAp20QBU2Buy0zeLeo4cCeGLPfyqwR1ye
YCk8KJwqkhXwBolFNGiBtMJe3cLUkGS/lom0NVQs6+/4y6hikbvxh1cvgVgC2XJ+nVOn5Peo1BSb
TD4V1Fd8IyT8XFZsTtW+i/boC/NugJiQEq72iOvtOLn2cQhPyRaruNmoXUmiyE/7BiY7Rzd54rMN
SVYvcIjCt/2LVe4fKrQwJSLq4yl7l1AYjeB2EGHo+N856Ifzwx8uM/Rc/u2qeX79tjnIFZoiOdG9
0dJWz+Sv+1g1okOIOGvnNzO/hfJwRGbiEUNFawgZFbC8RVy285+iZTDS7DMwtmIL4BmeqWvt4eYl
3dDh3lCXAVK32VyPUzkdx7H2QnJmUYCVnv4rr8sY6BwHEzt7SFBVq3Vv3q537HqvH+/4vt+rmciO
gx1pNV1lhXxPSOMDbLl817zZGLxWAeTPUdmZXZnVbrBIVCioEnHgNfL1aL37XbyP1k45khKw/woU
l+WTX6IoVgLKVt6S9dwBnKRW2cNn2Yf5e8U4nohlvdapnS32ngYjOTjSy2ybxx3ec69CQH9Ej5n6
g16QGA2tR9YBKQe6oIorFhNYn3KBCQppzpfrqMhsKqrN+VvzcEEESEysjxnYz8EAAAIQAZ8lakf/
AS4+vnRAAXSvGlgLADssOQUPI2epLcu82X+RVki9/302QyuAV1ITvH0zg2gSxcLYa4l06CEo2Dwn
EToQB6StARZOcTLt15ypMcZfZRr1xO01fWYeGEAbQfyd+1Wrz9kPFU3vxXNz37VRRq6FCT5ZjCMg
Fm18OrkTlquK5c1xr5PArX+NYR5LJyv5nHRmM7X/2sO+mrLH28telIcOpEvjM8xw8ejBOGJ375wf
iwkq5wlnIWdygzo3JzFuyMGIv3clHtt9rBNzr1giPzTLsQjH3K7htBk3PVyH+WHI+nd3O4vHr+7N
wtY+BCvqx9TkTZXjqzZaLqImJDk3PMG4LlQNDjhlk0LGYZuZ8P81p0gyDIJxATjd5bhI1fsirDtS
PI9mIz7SjBTNatwoQpp4+SQTfQYZM6wcvdKSXjQorkktELnr9DBKXP1NTnbDNKZKqo64KGAiwARO
1ANQsriGmYV2s9cO99bHbWovqedhbqkZfNfH9GIWoIRtWbo2u0orxUDu48TGDBrLViW+Q+1jhyZF
jrpsiEUGmrS9ZtmNULdvnoq0HoJhHgdZBUO/V1T4CBLi6fdXyaDBc9VZ1j7S6mSBtxVtEzeWmuQT
Iv6lIZZT0PkFo7SR+MAKLs3FG6XFc+SUzNcN7otMqfR6dOKh82MB5WYmajSUjUYasqA5P5YlH7EU
M0lHt34X3ac/AAAGhEGbKEmoQWyZTBRML//+jLADpYuNtgBMse1ngAxoixz9ThYdIWLeSWU8Nx52
kB71zlOsuwcIqCQIjXn3id+VDm65LHZ/K7ndVFkn6KfLGEl1vpHp7G1U9y4r+cgdmMGnFwnq3cvX
JUb363mRf4tBwHChVxKxn5MZ9/7cASOIa6ATxZnd431f+MYZrxXM9/gUB0/P65FTIbw57jLGaUWs
amXGLTsKgWcFOSXHxtDEux5Zms8LDWosLDRHF7YbP+NZraE3j2dBiuAGAo8T9bEqiaYsOGD2/xHA
4hvjupSmbHgrW/TmfgWB/2TS+Yp/32Jmm46B4ZVbEQZAjBWciA1cN3kgYRV4yx5MWDtzaI5M3oRt
Egv9hZ8qfFsX7OfCGXByQgrVVccytIEVierkRDsuBDJIAcUDpzEwOmISl4T27E0rUAXnlSw3vwEI
Ar+80rzBE7Y9My1obGaztrB0njIccWhLBHJNR5b4FigRCiMPexEKntk6eMr5X8MDt9drMC7Qthk8
m1BBIj6IUqq2tMNUzChGKa5KX/VjjNTU3LdP78Z0yhnvgDrP8S6mOc8MeXq/gEjCeuXyq5OEF4mq
f32kg9VGaqCN7HcOs0ux9sGMe/acf+e6cb5f/TBm3y6VCW7iM3I760uuu0JSoc3k3CgzHNTsgHiZ
yQepWli8ZHaFjGVr7NbzfpEMJ7cJUf5t3fj92ithcC0F225sFCaxScwVZbT3+T8zsQUf3VRgk+49
ZheE6wpC8NImVxco0Q1Jm7hmRsvrcBSt8Tn2ak4/QpNulkNIXvvISxfezN4s6dTjI5Y6538jlg0o
WFgV4l1MNZJcIg3UdtthuIjoJ6OG9SHNeq4IyiQ/HF2W723qA7eMxn3LY2twTdLtGfW7XCDjuwwB
dhn/E6e7R9p30cfyeKVgKCSGWDbXj+cJBB15xMZu+Q5Bs7Sx+fb0lQWzUJPljYSLqi8yEf2XQqZq
XgPuyaiR0J4BOAHth5dOfgZOm4M0sSNGArmBaVqvPERFolJ8df1BBgMkkFpSV3jHA68lG5suQrYv
c0KpAG9jWF3zppYMdjjl4LAITKrqQ7wgRWCo8eYAmTXWQSBKcFSw8vYrLK/zdpzpI4yKm9VvDsYk
5BOzaCSk4OrJDHYbyoF96h8/En7b4kE60HZh3tn2mRWqA0i/ROFjhHZQkIeUxIMmZBtPztqVUzki
m5AyAMLezjW2VgIYiSjg2YxsmOeHFofJEeM8kxyyRyvHpUub+Wu8cCjmZYkyfqdFhwP7jMzJpHL0
IycaG1HFqntjOgjc+CNHmtbwS5VYm7UwemJFQWkSwT9zNwO2PK0U0M39me9pCh3pWQlGpTTGfxSw
eudl/sLQmcZQsQoQYr1wHTGWzPXxI9WcPM8L/ZwKRmE7iflqe4kgE0lvQz/qINeD/Ua+Mgy2aQI1
DONTtEhWRlXeNplJgbmz5QlFcq2iW3ClOsVVqJ5983T+2A+UKq34ivwUyBuJjv6vJHUpH/+wPaXn
zaKxZvMMhAtKDNfaEotK7DnpZJtZMoj3LjhrGb7XxrABZyyGLxBNOsHosqsuRlR+jlE7RKATLwmU
2lLS45ZEYbj5A1LBuffTXVt+8uSAZGOE6l2ta5hXL8KA6x4A+oVCCF+twqGAMUvgkrn9kOEczKrz
a4GB+hOJabN55a77gKax8vGbwi4gl6xpzgh4rcczWQh5U8aOpzaupFO0JanBddkwqPT+AprzGBcN
pvCLaKECBUXLaNwStRi1B/jv58D+9/Xb9shPYoFhrsjhH7qfLakLFCFdHRlBt9lnvwaI0MrpQGGi
ptz8d7rWB1qAY3JITl64v8ZA/xYHhqP83b5rEs004MdFFlgT9otW44rInttX/i6jYMdAhmsrlFng
UutgimWiv+GZe/1gjB5pVRrnfTqF3pat0VmNE4LiRlAF6r4CoTvgL/v3P/HjuAst9HZehHTwS3/v
nW+F62jHC744e25C3HGPokkRK6OVj9TpPUdReQ5SSyx3VB3EPttK8zv+6RdtuMSw9SE1KVEyYr1K
TlehfLKeOqYHScC2ldF2lcw1qQ+tg0HFA7GsF7segsDKrHAVbhZlPYh2oF1SHKXrRDrMzjD6JKP0
B9puN7cAV8YZcPJeY4lSjYtWvvtby894hAVnxonfRkE6CNLq88Pi+JV4kTjRXI7xph3wWMtuJ2yr
4OU/EOeS8BPmkLjcKH2xrdPvJOpKjvX4yPZnwQAAAlsBn0dqR/8BJR+L21YAJap4zXF6yTN5PUeV
pJW/nUBkbk1pPg67cVo7I9i3oILTo+9YHl+48QTMwCvetLhOyZU/XPAKEPdSWnETk/MHdUV5tvRh
q/5Bwewuv4m7ZbyKL6Y7EIiNxK0eevBwTHKQ5v25yJWTc+pV44LMJJSPvmf/BezkiLt3qnAFBevO
uYfmh2NU+V/1kSA2bOe7ueTOCv6kLMSfit/TNLke6AKu0rKl5733kx0BepMtjtpmkoFkBsAm8c2+
HwKTMZuYuc4B/46QQvlM66mdvEAE4aCKUOQGAE3vvevoBv4DG0Jal/g8W4X21JPlc8LdaCBtVa3z
fEF8h8rITUN1vRlObBUe6GU7GgN+Zys6IWnIP4rPcvXuf4FFF4jVMy4MW+olMIn2RBo5/LDwuYD8
Yjhdq7m7MbPWDWd67iTRIr2sfub9pq1aEJiel3DRAW3i+llQx7sSkt7B0FN6fDtZ0ZTa90jEpAyf
P3ZenYTtn+uqHru7IxNNEjrx4sEwzq9asc3lYBmFyHv49f9e0Agx92Fh5kZZ4hYfH0d7JtxYQc8H
mOgSba2E0JliqtdzL/V0uuA+73Tgs4Cy7EWjlrA4thvySOsWWLC7Xt1iwdoGtc9U2UpLDGkL48uk
Dtd+4oyt9eRx97tB0MEn885XKkjrR6w+LYHaGSfbOcOQxGMT0dZH07KHKVXai9glGI7SEpxn9fBy
6oBCZwhpT6BB2PxyHNPV+hQJ+QkV2JAAR//WY/NYwBK7sPsekeeJ4hGChIPqEm0pEwmDR105pXN8
KAwNGoAkVsAAAAYGQZtKSeEKUmUwUsL//oywA6WLfLgBMrQubSO/mfqZSL8DNwLox6qLmsvRzn54
/lZgoZAcEiqZamwglUP0y5ZvV7hfk3etZj2ybdBHWa7tzXDDlLwmMT2Jss9qE3FNZSN4opPXdflp
maqNP4k1H/+CivKAWCtp1ZIDlusKsRM0eIBFus//BvUO46spNvhbU2ZsAHMx/DnUORvLMI1RfQTB
h1qIZWeUFyRjcOPVP+FJqDFOoGkT3v5Jzzq4tjvPUAh/CEwea7+JR0lM9kTk8zdsnT7r4PB9g4H3
o7tKWs9Nj06wvGii1o4i5GoGXpsT7x+1ZO/uXwc4YraufXFMpXs3N2bh7SFUfPypBm6vVkW/vSfS
ulSt/X0N5KlIJxEIw7NEzvll+Sb2RVdbJmSDrwZJIN+d/5eqg3/OemmOB3qSQG1aMF4QyLnUP/Qs
Oc4mMb6czfPgiYACLrFKFc3ilmsKbS15YW/+Ws8cLYPVwl8CNOcyMF92KCtwxHf1ZbuqY91Xug8L
LPQxGBial2exKc42dasyoCz7aoeL4Ic+LRlEbDq4jG1UwRq2aY0gTHKJfelp1GRMip763INX3lqC
opRa5K1/glRTIxvI0l+oxBUt606QWkBEE8820ufjG9gzje9vbuP5yJlslx/mLVoZeOGGQMdb/oIk
J4lxw63/d6eCju8O+6FH0vTQeteD5STWKWlR7zHvjIHp2K7tBPTe6usI8T5LxMKwV+/ihjKfE/0B
51TW3zgBmsf4cRbOKV6vBQm0dJajTiiW2kiMaJD8V2ICVrejLud+qbG8fnSSrz5gtbQpACJ8tIyg
e2JjJpejBDIfxtuMrdJxfgr27T73o5z7FFv6oiBzHEpQj062rFp/EWOYYbDMDwgqzNZV85Nnctlo
DZce1olhkae0qY2XTuY7o4rYOr6I/ZUB2rwdKFivekbZYXYBHwqv0sbcJb9bH9Lzfn8Tqgy9gUfH
hGAxdyqgwVqfUKsWjuhJdUDF3S3ZggfoXMsqli2lxOFyX2tM+QkKr5S2ggZ/tBpM7b51vGFsfrM3
FCHclj9QkLo6z2w0ovCrSq4q3YMk8iJqPWf3EVS7/DcLeUMBtFRvHs8yQyZaQo3OSH3SUhScMCaA
DQI3MoEGQpCDTnHEl7pHC/kspB/LqBLR+gN5Y3a+4C6lH/IRGzLr082mRGF3uLoqBxzv0HSaTIsy
KAv6bczrWdnGNMSRsev6cQ2VUzRzpQUmmnSLYrBqkAjyn/xOZn5sdHUp7cx5nDUpwADryEhglqJX
+e7qpgf1lzDL6X+qnGtWcUQT+lZSB4ZqwairZwHZmFfUx/NoEEowu71JsY4XUYVU8zFo9dP+nIPQ
aO+AsiGr+lHnIRa1AAELmyu8mC/Zvu0A8gajfRqfCNBSsos2LIvXaBVCCjIxV5bKkakeUqyff92v
HwcHPAnfoueR7WkNrv/KJV4Vw6ZvcT8PpVsERqOKnsp0SS1o4ZW8g/xtdyZnpZ/nRaJnb6y5yf7u
O+ZuJq9Op0IbheBG48DQPGdckkdIyeQc+ZqnA4S7g8Ezgcfw6su4SeTjEwj21ipbYLL/6bkdLLe7
JGLhfrbsUweef4efaZoRQSNigokWL04ptzuyQ8nnyhkSFT9/Jc+5F3YhoLi904W2UqgpW/A3iKc0
2HMcJdLSyz6rLKt2ri05eXdo/LrvaopNxH02ay89nuQgI9NrjN8Z6wEy6iyhN1x4VNjYNN4PtNrZ
Eg2lD8qVS/ekoaQQvM/TD8K8jqJsoUCRX7GB3efxQgEUgouUAEPbFw9l5Ofq7T70lGFvVao7wzT/
t6f+5JHtQv//ACinS/pGhq358o3hBQvBr8aH/acDCnHK0+JaJtvBm5rUDuLurd/Kt7KjlucIkwol
UHGZe12QWqEhRZSoCfEEPRrDgnngJSU0grn/vQM6VxP0VgJsHhZ5gEgYNbzuFXNiscdadHDC5zGh
MAwHYWnoEwqq93MxaS9Y1fIcwlrPCRYDZ3oeJap2nxs1YhLS8Q17CCJgjv+IWk46GqNRyO5iyoGg
hdvYrvuHo0GrYO27KNr/AAACIQGfaWpH/wEt92wWnU4AFujJxMwL92Wb3P54DPduAh07LXzN5KDS
3BVFe/BpOQQiwQpreRgc1XEIos6YWN6qScpmeQGHBSMGAf7mKlZUOIMre2nVdSWmMuqaqZlfpzsv
pFz2qP1fp9ZRaQTNjNf66GUKu18yXOdeWkOiXxFh3EzCajQoo5otfQlYTqbJRXJ9YD4+3U2UpfVQ
auMbmy0gkQjh1xsox++MNVCXb0nZAT/HtM0RdGvFI6h70HyNB/LtemHoogikuULFA/JQ3winCxDf
mdFiLvp8s29WRZ8wukkZrn55ROMAVVn2S0XbZ/7rzeSA9yYOKBHAI0cXx6sJH+s5BIQ478RYj8QH
S8o+VUy9d5dWQFK7bYA9U3PY79JrTCHN9qxnD4gg1eqhLBhFWOi3+JtULyHiNOvpCfjN9/NQ1ETd
Q5QG3Iyis8CXDEJ3Xthaq+uKIeurKYRVkfSzZy0dF5kULsmFKc4TQF5VrejpnjRoAm/wacyUXBa6
0o2xZX6uogzPFqSDPEYzTvGp4jxoJamQ7bkUVtB/D5eUbjPBomJSWFXG3puqBQZVYwTXxxG7w1OM
t55xEqcUeksoNvqSnNAJVp/72D7Y6N71MI77SRO/XXOIIecwOgIhBkZG2qRzE+CfEjhLnbBbhyBp
2PYvDBwsaCVqR7P+layQ39xYE8XZ8LSeHJ34yAklRHX24e7IB/75HRAD3uoRBwNpKhQXAAAGZ0Gb
bEnhDomUwUTCv/44QA4NkDoASl/KEx1f66zIPS0MMbtgGVuFgRLE4x75trlJ8joxbx1aAUGXcNOX
iV2TGK7DNJXrLBug4YCHXF16SjzGUX4fVxzHYFzieVd/LhH4+Nnta/ORy5bLNKEnvoKm4R1pDkjt
nIhpQiTTHmwDGP8s4urETbjR1Lf4EpJyYXeGl3l4j/e9+19K7bTY6Q2EY4pDXuMfrwCNNJngA47N
BpctKRpGtwW1FNTnlM1PNqrZAb9UXQ3JJ9NURkBcCQcjUpAOhpS6ePGJ0BM9FQBv/AugS6EGEuVy
Br5qW1UG0ecbG6CUH3CQLpnajFo7ys19PxTFhj8fVKazdzn1oFUTXMFEEsy0at+kHrovwg/Uipq4
tUmbZHPbFPdkKZ+VDgNZxE0RuG4NuStiJdxXD5IHSLAXkuncHmzAL3mO9jm7Gx2m/qlB5UCvbM/k
7brzusKJbEp8FSxbGK82Xxt8Fv3DWHIAPiF8X0cJcwSjbiJxT06G2on4KpSXEPo7JbLOklv/N7Ef
cl4fZn3TAEHV1yZ4vCXU6T8ZJ6C2T0x6IWOPeeX8MEQZ55YTBzmBzPNRa+IRe2LdC8tykCkmTrdW
Kn0qncX0hPvVrQlG2AasnXbCZTOWEYPHxUL9N95u7MzpIxdhHEVw/Rr8RX+9HLQkuxFieD/xL9pj
TI56cxHaJGkzSqHvZAlSMt4ib4UdakNvYy+/WsbV3f7/hCm7fTdcG80V903SBPN0C/jjPBHd3Ma9
RtoqdSIBWKGlT30u4upOoIXEqbX+Wcy6KXYaEDRlYLrBtL6MO9yOA7bG+9brHFGxqh3ePzOVTkEz
JiKmfw+y64dtKJL6pr3SmgJDlqK/XraxxarKF7rR/Px7PzZhubGZ2RKn5aaM6bKmvWRdd9XSPwu3
XNV/BheYrPL8RamScDDuwMbf6y1WxO6zGGmO6TuogrwAejZxBoKKcbStOxS1wcEFagPeBrnOT/Py
61OlSpP/rKNZpB6SSMpzBjrhJvZZXmebKVT3DkOzBVERp7tALkgOhHOqt+G72DfNmkm/Ppq/qXcK
JdHaaZARlLKAmb3l+r/RMM7+wTL87yEt6dCET+eKgLUi/CUcacUf5vOQEcd2C5dd7HyP6atnFe1n
O8pj4OzBxnkPLsmgrCaLtrY9SjsnW+//9jIvMI+1Oj8adSjbV+/OvPpKSy4D1fUBLeLAQOxFp8vr
kQi6ftW2Hyp22fdMCZDy6mGED/naq/x5+hxPlkILAUejBfc/aE7b9PCKuX5Na9LX+0x84wUAIPn+
kGab9Hv9qnHiiGIDYYBc8mkZ8aVjBBXjNSx1gNDKRqEj491hTwzbMzdIH83XY1rdcT54i5L2Y/bn
I2PV6X4XDdoQmvzL9UT1/sCf71ZUpErrke6my1BktkLgAFUWjw+hW0LI0KBxTNaMg+S5VuJYjfHd
C0622Niwj1bNpbEs3Z8J4eaLm23BeljLQU0y73kMydHjhqsS+YpsFplU4S7GjNM4Vo1V5sc1aJZB
+9LYYsB+Y+aAC7q0dfwLBP3JB4SGWRvdfpJPLy04RLZlrQGx+UlvOwckV6mY/lclFCPMtBfDArr+
d4chtLV6omMuTqtEFEh7+PAMQ5uHS+OsRqCwxzkgivBF20ptlBaT91s4Za/o2b++uj+gu7QH+Top
Q1goA8tsudMesRe7bMnLDJrzJlg87xf6jQ6+taQgvcd3Q9yBfVbsPBrGc13vd8jU+5R9AeQzOC6N
5OjjINUmSbfFzkteg7C6bW4i2yzQEqtaJgyaILQL/kMeRaF/tXk9UQxh9tP1X+eZHavJMvl8CeZG
8enLTWkX3Hx10Xyxb+tffHM+ucNrRWo3R35ayAwwYW7uySFnDyU/d5K0F1ia5mc5LO+iNub7gCZp
Rz2erdlEDAnwIeUrwovk2AvvguO1YSiP0Xsa0OWDv8nxAnjlfW6W1YOiyGWOij2DkDYV5loZ/J0i
SdQYcxoe4E9Ix8ZouwojqsubXY37uEihu+VII9/pAacJN2rtuDnxC6RnK6d4IY2Ert0Ue1UagdKh
WgK5rSDWd5N8BMgcKnbAYeidrW4bhvYZcELxfb+FO3VllReGPiuFDX/C7mAJaEwgCsOAziIDycX/
5QzwOuv//s86EWqFORHaZ7SAqXLNi8jz9EzryIY7/G+F8P24QcqlKSQAAAKEAZ+Lakf/AS3MuEDT
wAmlNPmDM4BMhl4Z8HzY0+lIrbwH3AEEx3k4cGgHgI8XJnnO5T698Ft+9MXNHyJtQ1KDyM1MuqbB
z47VfHJtHY89c4IzJSKYoVeZu4NTMWcmCePTVXrYBUkdN0vhA1ET63tklk9mclR5TYmIwngMz9jk
d/xCKtz131HnHXSfWJ/rGXvglArFJooaq0N+v3mASYi//iJ+qLUERqkOtOL3BGngGV8/AfnqaxYd
JPOhKUOZ88xKPB6t1vKY4wAgBUpxpbQhDaidEJuAWLrzqU3kHbYWgGJgGWIXSw1xuDcBKTrM1mrq
Vn45iCjSRsPRzPwUTl7vfAFifb6////+otFAk3sEDPrY6dYcUq9jgFcJ0uTQ8xb3cIFkhbmUgaEs
oUCbvC6wcfGc5Hczms206hqGCL8Gty+pBbkSn5gkWXXcYwF7ZEcntnpSv6kwX66AUfmg9edbU5u5
1FO4eWxqWJN7TaqDy4++yUyMRD85Q1/5aGfJSeFmCunbIvlOGFILkdyusdXb0CAUoHaOGRhmAWWF
q+2vbjH56rwmtnv0CrIwiME6mMigCgCVY5EIxdsdaInJ6ELlvW1xq9W1TNBLBKrh7zmK8Q4ousQo
ZRdNAFx+RbF5N53tiUsPM5utYvKUATp14GsYR07jZilb/kmfoiDVVvbhG7sQsRxRa/E0hgGgLWL8
56YW+kY1cA/pYV6sTUJ3Jpkhf1KvdfcQQfbXegE7+A4Mq1l7rH3w95bc71DphO9pk6RoBjMJQqWd
6Kc2vrRwGmaCyi0+pHglkzLoRpo1ALyzCTbKU8/0Psv1r6bBjebSX4fwBTYOyFhgWSvGVs7XAUQH
+0OyU1gAAAafQZuOSeEPJlMFPCv//jhADhYS7+gA+ox0LpAwQUZyIPHjzYlURhvECAHJUbmHWz8G
F1wfqMJqSkFv9QPT0K0NQ7FtH1lfWVOXE+w2eAa69hM2rJzkB/CTg4OV81+4wubjwsmiPj91i5T7
F0vhiM4g33i6Mm/1So0diLJFAu8lDI0WQTKFjSucM9hAgdUjt0+Zx4CT0mmKgu530zU4j9wpoWWC
yMlhruF0D5u1NIAB9eK3itK8SWyygHFvecqhYFviwDKiy4An6y2PG+fihv1jvwzy7oGkXawjTvJz
J+jCEbjx70DYkBTeNQILJ6idiPnd41OvGy4X+wgCFd5vb5pExmJb0otL6B4LF5C53Gr+zEYTyVRM
1iOW+8fMt2zLOKrU5PtyFyrW3ImAu3/sh8RfTky0CegyDYvZED3ok1qWfzjir9OfA1fP4Z60WhN6
FlOSV5bxY4k6CziBu7b/hGlQ+0J4QbOx3+v23fWLZuVIIuuIg2C9rUu5XhBtWUWP/loUl6cuGUgm
1kFDa+vhegSxOLs61tRHv1EeR75ASGtNaltLhdh8y6S3qghHmoIGl2kEtVGjzKPidm4dxAwMuaEc
Tchg0DttqLH1j6amNKfoUCSjlaIcwEdNzRyKbFzYSGH3mdZV1Hwp3jjexv+zYZ1eLDA8ZjaroR+x
CKcPznWpEYVQa6aIG643dRrSjCBlrpV1KIogcSkFvEjNuJCSoVjLAFDKdVVceskb5XIXR0hU7auJ
OSzGb76d1ue1qESLdAG9NDf7l7GO1dz6BvqiwCXONKNn4ieIzFz4WyYXk5pVhg+Vidh3ukqfUupx
RFg2fhqwHjVlgO2nFJnVnSQnep92a81Qyth3WP3YZtTU+5SEgU76ZibT90WNbiZdHIOLMqK9Pmgz
GzBt/ePciMzXEy1QyH3SGQR3HEkNzusnzSPbgHznKCKMINNHxtb4E0nHBEhEz6mLB91LrKHJ/xLw
cDD3eHbfx/E9McwaqIYS2sX+YFnJREf88+Q2oHKt0kl9v3ovA57bWk0Baw57PIV4M8OoYx90Z7/U
Yxb2rAFfXi4ZaYlHjubwtGvZA/4td977h08mx49a8edaCaHfc3InLu2/xb4AzMDbiWnBI5JeYEtT
4S/zYCCYbVfQ+iLkR/piWHvZK1l/TKzdxc4f8qK+QGW7fE//7wmuQQ0bJBJ/TMCuyuPQqJ7fvJaS
45mSOlbcxc+APpJAzRF8LGrumO3T1+iQbBoLwztoMAsPP10xaDjDZRlXyQmgkQ9fXFDc+ODUc/n2
SpHwEqEBjTtybXxJqxNJrc9kFnLtJyXoObG0oSdQX4DQY4qOOrQtUu0vV+gsRJEG72m21/EcnYxM
qFWI0Oh7jXxpSWPhfLnoy2eERFckTnHivKQfOJxgXi5I3nEhsLa2iXtJoiH5Kzruz/r9+TLGhw0g
GTJEaqtKS37wV1lj7OSEDNZN37favRjGp57XVBiq58mr3troyPmB9ogS10+EqUYV4G6La+/juz1k
Vk7NPKTyB4XvX9drIC6iz7S6/Aojt2Ln/3iE+ClOF5Znvtblh4MyDiKvOGnlW3lzrPAzbHRR+AJM
lwv/sBg7ydn2u2bjaZQNYDrYG8sC+Oq129odt2urCXGDKsfmsEI0Cr27xF75qhhJNzFvO+HZw6L+
kQNvI79mZhOgL0fg/fFRzHUTzFfLHhR1KNgGzFjF0CnNTTQC9LYB8RPS1BtNXJR6UcZuDSU3xwC0
pyyIf4oNg+WUPu+32wDUNVaxv7+6G8sxeawQy/bIBgrAGDzHFRavc+U4y3mHst/JuRgIzC4hUOVL
W41N7NNLb5GZUPpNwFOkF+Yo/Ifi3xjAAEAvein62EwA1I5+WIvS76nRfv8iWYagJMfygDCGYjVY
XrAQcJTxA3u07pyb1Lfv1TxDFduI8k8XWoFL5QqdpR2cxCWo0gUBFrF6HoWG2+tdGWPNlfZ19dio
E6lqoMaMUYbcFvgxo0XCfE3rlNP6PiItQJHZg2lKet2Gj+Yzj2DiaC1nf0uoFNeHR9PzEngrihBe
/AEXRAd2dXam+0fCmFnrFH09M7lR3dj6G7wg/3lbsTH5+bu1A+dkOs84RxsEJwzZzaPE8QIo+XPu
Tex62hdzmJwfRj23v1wWIFRfScSV3JcUAkPj1jWIzh6Ihv/TCYnxgpsTQMopoqIIZp3icFduBLCX
EVa6ANXUxaCdgdaiU1CpbApP6rNHaTOZujDLnNi0lbyEy3G3wceL+4JhqUYSi04edfn/AAACiAGf
rWpH/wEuEP99Phv+0FwB3gBJBvnEpjWj6SNB61DGl60+ASdV6da5+j3DEEEglYi/JuQ5/fF3yc87
FzfKnio2XEC4sfxl9ha7gxI7kAvAMlQoVvs+lYg/MjPpuM74YRJavksem2q1fAo7sbnUECL9y6AL
OmDRhB5sLqrtWVgAGbz9k+HFVfNznVqH/8BXdPQPUBHQfbXRQF0Mm5TQZMV0pepyl+xV6Lzj6dRx
TA0DXj4/y0E+qkdU5imZLgcx56Kl3olakh32ChH1QqUoeQ11ojyk6MmtSPWJxxGtwd08GRP72R1k
NUV6dIW7KBc1koNQGXs1ousqHnmkAKtKdzz6OZ3OIX3FjcSJ9xUN71e2MPL38qWdSMHEzQAs4eh+
ErxAwQYCzC3lNLYuaArjasZ4qzIzMCpBegve25VXM80NPm+eYsAgPbYRuholZMDQx2sRu7J+Os7R
+EXJBNYbEM4nbqHkNjGaREQVoXcgmpkVO5JN8SJLkVQIzCEcF56a5lqIiKCo4d7G8tXbS9rdNtDk
JDsDbwa5bq/S7XYDcpzICXIetrGJJl3nJpWTiryVxMDFLHv9V6sCiluD7DIbAtbc6U1U986nX5sV
RXj5BGlbjmKTCNBlFMEI1tOwIfswJou3aInJ6KomrKeZIhoypzIesPdkkg1RR6PrQOS0tNyDstp7
XZCC+hrcsRxSG8ZuZ+v149s58AU5Y37Q3SXZmx8eGk9y2NezIm3UomIwTFX3DdgeXDzSf0SXVoZ4
R/at7hoobG5nmKK2ePDYim2FjloNLhwnWEdQ1eL10qKvvv+0VvjIFYFb19owweT7QJQNioxcUNJk
KUQPAKDgp2ph9ffON59o0OAr4QAABQRBm69J4Q8mUwIX//6MsAOjpIIAGvpkmp7m5ZY9fgkIzQ8i
oltdD0YlVReWb7tTCMM1Rfqe7XOjRhqATx9u7FjaYf99SeNpz+yEnA+qoAi4UMx9h/DvQplV4DhD
5eottvCXrlarJbR+jVgcEOHXH9QBRrAmu6X0ortZIo40tlAAiWUmznuvvZJkLkuNgf8Ff0OrZ+iB
wzCP2Ygd9DNZvMb5O/QBy4hEMuScnKub+eWHXSpz3S8uqiQFEdNCVWA3vnu5aENWeU/QtMnky8fP
hIqcERDbDlPwMFwD4UxAkLnhrWE1PmO7IdVukjptvtW9RaKCo/D0GdMDoIPRCYX8fwOqN5BIcDoB
XrAfYOJ/aI5mVBZi1TqgMAam1xPaDi2CutfMIKUQD+UuVcHKU2vR/c3SsI6dTD+nwpbTNAwqCfR9
q3vJGipG4C0jxNaAQLyDYLShm2Vc8DKvITvsZwJNhABpcMiNRs5B1TpkPnBVmVQ60lEwitKKwXmY
8rFF4RgQb47+yUoQq85ZD9FvhY+cuOm3nFHmDmAt7QXW+O8RvUZ/YWOi5kvOVlWy6OsWhiNCHaO6
nxZKemfQPL0CXG20diByFZa2dAEoHIPVgjQahRPAbGsh3uhcHbYPzUTsBZ6MmolNZMuo/KOpU9hI
WpA8wDHGuUrzSp3IEpM2YIar79HR+e7s6oEvS95ToeJzWGvXDeQTTul6V0INeal8/p55BZZSWCce
2oEKR/pUhNIK4RCoaRnHxCWUsvkAtuvPg3sVAtrc8pH8GmJg+S/OrTh1smtvBPyl/R5piqZjSU07
SRrlGrO62vnE65TN+u+uOQs4bImuT2JCOJSa9fnK7MIo2LOlSgcDTzQYqoEdSEXFZ8QK5hZTJYJn
+KPXUZJDOxZdfg5NfhwViLce1Yz3ab3FXigtbX0t7q/OFrxxj9FnfwWTDYK4xmHyzv3vIaBYbStX
Ea1dcC3i6tQ0KY1VZ5Rt8L+THJuxIp99CnZP9VKXNTy4F09JwibqOu9Vqxo/GIL4ZjmGkpMTfDn8
Sr+6LkVSG7I2jZ6VM5yp13omguMBK70LnzEzQuoXJowFKAeqlRVs6r+ZIR5z9kRwpxJp9gAokPU5
6A941cCCt+mG/oz9RU/9dymZnolvZJPqcNzhU1+WEx3u3PUp8fzFek+StXJwhu9KIfv/bG2V12B+
d4sPwdhSqDxDeZbzlYglhbcLMizlQe3eI52EvsiKAg9m3UGe5jEuieuRNP4pwQFoO7Gq8FukqiQw
N/nfcZtb95Z/62ywCS6EZlM3VNgL7QIHDpg4QUuZqk0tjcqrMXPn1F1S8erRi34RrdlQJev2cwT7
Io1pHh8MGwt7Uu6dZuYY4QoNax7UEa1R5dvf78qY08KsXSJj+Asb9v74n2uIduusp8GXz8tvdag1
gbPwNlCmRb++tdUanVlngZTWgOgItLFCYtLtVh3gmggDme6JJI3YN0HO17UNsCZtKW3ceafJZGd9
LTIPhRJj8FwE3nVfdkMqF3bPs1jjRaxOcsXacr/ZSEabj7w1j2Jkir0qAhtOEUaT4glJdWSu0Vc9
2pX1L1GaA3N5z03RQ0au9oIidZ029jcLSCZKCgWmTZXF3JjOJ9djWkV/zYfTz3rRZrBIgiMm9nFV
Rqd5TWXgAUEyJd6HGuKMs5s5Kldn2L6Dxhsiu7IbwTwtnudZUeWIrdccW2H5POK8Vgu2ccEAAAbC
QZvSSeEPJlMCF//+jLADo/Ki4AObCJVodt8sH2Q+NjnlTVgQOz77fCEMDljJErq+jsP6a2TKj/YW
RtSVkpydMCmKBtR+Ecg8Xc5APl1WNGKxJuwOFNuGRtJVqT6Rndq+LqPjN7KT4XeAnEV+n9FkXpGI
mZGdscJqQBPtjXL3Oj54tnH1q9th6lH6Df29cumpAB5rX/QXsmFnHif+QjPeez2uJKXQBMgKZomU
j+2w5Pg7xlz1qSuA2MPrQKX9YfQXUM1NVQeNbZF2d6Kkvlpz/30fBfN9SHwcEfVf+Ob14hgxcucm
ieGY4ci2VHfaggsHZjhCl7fZBXuwoXSWAPoEcvH+iA/k9sjg9PhrHjaxOaG2SWGr2Ng8GUBs2wqe
QmGWnmGChBHZ0x+T5xuHH1qioOC/IrkPZdiolUY9vGP/JDPkYp2tt/C3OwB83MsKyeK8TLvKecfb
cytXYZGYytPv/Ek5Twe41m0s3koB/SuiE71aUDq6PyACdrYiIB6CrHn/iqo3vLB6hB8fdir5p6Rq
/EsPLpCFJeNiBkAf1ktjyyJqTERZvl9sRXzdZWCcJ6/epBCiCwSRib9yG22+z/fNFJdDdF6wzOLR
EPaPLXFrAPdCYFj8k+sO4ZcCKMANr07wU+KyYzHzEYHiftImZfQkxqguUgjq/Vnwtxw+uk8vZBIb
Wt0zv6dG52Vj8SenCAxCXrezjIg4vbaseR+reKc1YNfuC0Bx6S+ad70oLERTovriUVqHfmmE4fCB
TxBn23V0ccObgaf04J1AxhmaAmhb/jC+zwHLYLyL15CWNVO3+SMJJfTToN3KXMbIMMs+y6cSo8hr
W4F68ywf6/yaR133V85t+41o0D5/d+/5ZiXv7YLE7uZoDlEfZ6TsGy4tRu7m7TOvyXKX1nQul7Gu
6P6qz7B1zDNbdNsdeqqSuESVA9rxOrc1oZ+wwvfbQrUjvZb8zWt/6M9ig69u0+c1tfe3iWzoSbWL
8AXQ1janAjMmuwapWyPIwzC5Z89sEXO3eUIin/d7PLloK1SJfox2EF3HxEfwmMm3uUoCk6KRcaiJ
bo7Hvbxvat3TzPbjNojltg+bGtB+mIqTHat/1qZnFiwQ9mX6sszukSLn5TDXNxFCFhYX6r0MxN+g
D0ta1Ko0YujlTgHm16FKu7JRafEQTBu/PuxDCM+pzIo9zdI/aajVSxEFjWUkKtdc+eNQL4qWbDP4
dDqkMRopGHmUflvoxESdeNAt4L71q9sdiIO8rv+KNi41+UwurAdn2Ngdwosh8Xb1bct67K4rkWf7
VJPTYqM4pwRmNsrbWbE31iGF/bExMcjbQkGP/Kn8j31fO2Owhhu5pvTt4jrQtyhmwXw5Oglt+ysO
YhvZ8drG+XYW/G/53ove4pWZVdQVpQPppvvp5ionSWmMOe0Vps/a61n5wBqWG321gDvXr3NEcLiT
tvoMk4ALJuK3AUOYMsJd1vHIZyTBf02MbE6LQJDGH/ji6TYKqebJt9L/RbKwuy+X+fPmrEstCayZ
FjeDufl59puj/xPzSmsnftzBM+dyPV6Ptd0pSYxYpRaqN7xWL9bJJdhFgJYGuQfl/bkVweoV5ZdF
b3fYUTVZn3BNOn1R+Zgs7qT90N0L6ldrKukNRkoXNdLlam3WczMV9MypzCWfbMIZSNpjt2WYCuIs
4sA0/kW6xmA/6k09ck+vPwhqBE3vazVTxfZYY/6efLnGsVjoYeRtNqo4h0DhyPhoZ+DVu5FH2JcC
Se+92QGEg/bqmNiO+/dXO4kj9ivfVymSNO1m5xeBqYLiNJCM+M+hJtbVrNaxYL5x3ddPTg6OCWyA
ljAl17iekJC9R7PocQTbzco4bTLdjnfpB20h2lYE1kv0vpAsRzuZD+QcxNDKhPxAUVv4UQiMxIWM
G3a78aqqLyINBqShGRagd4tAahzd6Fsc6+esLMSPCwH2na8tnQwLcMFG3NRAMoccYhEkT15l3f/H
CN+pemvjUlSiMl9zGgQnpJ/e/KwJ/8OgOBTUOtxiWxMQMEePxPQoFXY0vo2pANIMN7e2n7jeRJ/7
8cWlz8nUihoVAiPfZCweb6JIrFqR2rqSVyjQ6RCy4z+of9jxxDh7iX9nM9zmIPLLtXUTfCEF/cwY
GkeVlx3nsBM1m0fSI9taVOlVeTWmi/9wghd/SjjAJ0fEQC34Z/FuFh1E/n+bW1ga3K3CXiXcur/y
JpMEEbvSeaLZrZHMhggHykEWV2KFUzsLhGru23vGe+yl3CyoVG4qmzsng6Sa/XJYd8CljLBUGF3K
4Wl+iijlcizOQhW1fvxM+kh0iDgAAAMFQZ/wRRE8I/8Av2zlS0xFvnFxZYqgBNPaULScJypxacAy
fWlykQlAUupUPvgdw8Gp2waGkqTZnkLCR6w1+EE7cNyitA4ltushmvC477kpedicwduDTVyjUMJH
2GiW0yDsCS6z5/BpHWMmCS1q0I+lHtelydPXcSE9iCZRbzwE5qQofC1JJikM2L74lV3yO7+t4YU5
CEgxBQYrPs5j8BBa4TfB7EA2cnPKis3ZIsgIOAstIYKRcPXfW+lkMJsGcP6CfTiIr6b4x0hqY5tq
eTLVb7byWZ1p7y378CVgyvgURh/KX0RFDZ7/PHqFwGx7gZ2p4K8+Io5j7uT4tUGsGOH0rNG00Bnn
bDu73vefPER0/SKYHa+0WdZrH/3nsUtuZeSyV4hEPVU/stRwGT6o/EOwD5NDlfY6CXUhVJ5wm6lr
km+6+E6JkGf05nzfh6UHpEyMae+Eqdutb7qrsANp1qndUzrXptuNE2tj/saka247IiJs8ims/8v0
j/EQVE81u7Tyj9U1lbSAkCLuOQ70z9ne/pQ1RwtaG18LFpajNRciWcwM4o87K2eysUdh3VJiO9u5
TXPejUpRWbhQq6H/+/DCLqulWae44pTXqnkjZOcI8CeEgNgJV3nJyUgPMdl+0AfPBU+f0hOrIFP2
5tJ1O5ezE47e+UtThyCjqoK0X7+85uyKAP/A4lRh1OU/829wut4VMA7ZlymuFLqRdP/t1NZNll1o
5t4rRRvxTaVr6u+/Fojhjz2lYlgYipwApHwIRc0a7PEFT9YpxgW0eqJl3n1nFTmKAg82kQSKvszh
qSYqCX+63LhsDZwuPvMyDJes10ApJDTPEcSySX4vycGNY/sMkX+qiau5pNWkiy5kASiTgoBPz/3I
qJKr9edBvnwBBYpkYchcuM379fJspfwaIvnqUpHTg52ezt52jFzJeQ5qhiCdzaP/IfWOTBKRf7j7
7qXSJeatnF9aJ1sww3w4fvG1LR0fToRJqutQr8MVWyLLc6+RMSZoTWOZUnYUV+m+8MK/4RN6EUgA
AAKJAZ4Rakf/Adx8mAD4JNwiG22XAiG8igytLUiXUxALDPyFbu8EL8b7in67unIUZs30cWhBTVJ4
MdGZeE0vz3xpYzGeWI1+PVLgvtQG4eVnG2hD6U3jzhaH63fLCcb617sRjxM8FJ9EiceeYHvPzxeG
4KPaUc6h1o8ZtSbrk/M9xSPSkdT1NtzgwdE5sRI5+4sQ7JjsAFC6lgQMKVw8XNuS6VFRVLssW416
xJNR/+fHKrGphevzHLDfet0YLJxgKO6s4M67d/fygM7R1TX5w5X0YNXOY0zfGxjdVmdwqucGlRPe
pYSDkhrEiD29hXN6t++p5ELD9lPMjbGjm2X5d+9Gbg186+nTwcJUkGli9EdGEx9gvHacF66uAobr
r4noW/rmmKNSDYMWqvBhtQzL+tTZdrnw4LYLDNBrvpxv7vXAp3RUrEaCqkMwzHvZu4GAff8SSgLD
Tn9vwHng6rOmshyBGIFX2c1gp7MoSbMsnec7iLlPAZLXoitJhbWLuBC6toud+qbAafqw6fMaNlfD
4AOs3lDC3vHTXnozfT6S0uEx0nxshzB89404cN37s7kRL9cZxVqQvKmnBUgdiVKlXnye9WFjSu6G
mYoRRO2xMuWebhEczo6+Hf5Z4jxE8k8saSUqLL9I74h0tLPEArouOSezBHlJLcpKK12Ov5fyqLs/
+lg6UaShl2OQKhpB0TgquM5PBqgCGzV06KdcZ85MZYAlRS1PgWnE2+6K7fUF+dUIA1sYLZ0frbqR
hWrtnRqROuYvtJThcDr3EOlcMpwpQJ7Y4t9nildHqMiF/SkRrEIJ8nuDCsZpaRGC6kfsAE3faek/
hNiFJDuLd7oUfEGsjvTWxXlicgzVdIIEJQAACBBBmhVJqEFomUwIX//+jLADqap37EOvlQAQ/JEf
SdhoJtXrCjif4rX2/ps6T3w8T/ePSejX+EMPhoFDzQww+h7BA8JQyexLamfH1DUlX+ROrxqIy1Y3
uhP2nTe0aaouP44uSNPII8wxqUDticI/k5wZKszFbN+6xpy63WhzxEIgrGhfPPk1aLUT+a3rWEXs
tD3zqLJ2/VWlNO7a2c6FRIdTfUlgcdOJLZttV9/yXdXxMfYSbvnS7l+s3gURg4M17fwFpSou6ui4
X61CZxbPc7ZTC2lClGc2VHrz0cROroAOTFP5JbQgGN8gZW2LwoqdNttvSoplMCQqw/cV3eJnxEw3
BQ1aN6LCKSoXSGZJ6IHtoPeKwxa29lCh/viia2Pyn43j+zZnBeqNaU1MvAOj0R4wiXJiBghXZH26
w+CaJbB1VBI3Z7yvk+qtUJTXE8RcsZgV/NECYWS9oD8csPzjQk6FKzFvGDk/nUskShgFkYTQCUEb
3I/3ZfdvSDen0uU5iiWfFD3hV5kCkJsQbso7qXcoAUzXhvHtrNLrgliCysc77tQ8mONYjSVLuocT
Hl+tokKWx0GgriVZtZ45oWR+GFPLX2sIfzu8tWIEj7SuWlMiFbz8GfSqLG/oMxH1P5KAG53pa5xF
ZTmygcq7BRZ9QANhpwbINIEE01KOD3bl6ougitXcd81ZSBtkmxT7xfnoA1XYvcC+HqsWzPSZaBN0
oWa3EciukNu7Gwk/3JD9JV+uNBM7vhUrA3mdBMFv1F59D/iYgu59zd4D4ou4LCnkLo5Izirdr70t
sJ3JHtAybwa4hixUqR3oHRqTxXK1/HF0Dr4Y/5DmsIskQhe/6pKJpWl2CqTPyC4Bhca8unWbjD7u
ovhBHBspne+cNCxDoeYZELaBVvQ8ZfVrSyAMXUn8S1PRxoq2rybKePkGYCOQhfi8QfHZAcjpqfyO
lrtDYgPqJ4aTElZcFNylmZIMhGow/MBjVI1MKcC5Elzfc0PQ2fKMSzDioVPlAH7rz53oT+N8tb8Z
U8QpckEmqPSQYydNvLuvgc4lx/R7MarFVrf7vQbVhMlBz9sE2fFzg9YrrrtJCosXQ0309qS70WXQ
BZl0QlPhuRoOplHq93LmjSu9k55SQSsfJxKXzHprnj00GYr3Hd/L4/ijoz906z5oq6F+ZyDEKr4u
nhpNnLUSDikrdkMY5r+NCt560wpCRxA0FpU+O5MtT8bTqGyxlEDGR0nrNM7i/nO2oyk5Ny+gWqkI
bJ+hg8rJHz3HhQFq0Rfyb5BsSFSkCLK0ORdC2KWuP7oooNTYh9zfBWE3NxjahupIh+qtawW/P3Mg
JW1WFQ0zrPQFErIGvPM+iVZHSTjDcXD94I0LdmW7uE49q2BDmhBCMrb8Ui7vSHH9tEldwmwuiaJ/
BicH7N0k8/XcZl+QADYu8rqeItNAO+g1UVGG2zjbEt2j7f1KU4UQkhyGWkcPzHsX4AZ1oumcl024
XJ7jhZboSeheDcIyzrYuvZjO2+GGnEF2ZlWI6r+/WkmX+HU/0y/SU17PJ+QFsXXfVNwaPWaWWR8F
XdBY7O6CB3tyWfpvwKNKhXXGutJILD6rncsVRbXumnT6Drj0eSzTUl54kcnmXi2UBl03HlkKjVeH
CZ+ne5EEYQinq/5mKBHi8bHJvdy5BbzHCyPKRrNXNrLXboEmde+80empfd7Ty2U8Cf2kTBERqo55
K3BncAc4CoSQVvi00ftVO0CAraGo9Cs1biokNAMUt5OliNkpnCfHismJDRaJmVZkNJPISDZHUq1U
GANgnjYbh6TDC/J/1vSYSsIQOYF7PypWpTfqaJhugudbWLcNlSFhwU/DPj5dGIPjEIHeNLHa+4uy
tfqzq/WcB3AzMlFRsu2en+2uOJC3j1c63JPlQPVDLXlCqtMux0mikR33t0dV/a5VwNDfirLmLxxI
bNQkZ1Rib7qc0EYU65xgqAOYCKMgk62kfJ1/RWVHicIKKQuXP7HdgZszHr55Wxxdh2muzyB5Pprs
Pb9+bCRYrfV38A6gulaBADmMNqiPEyaCnweDaKxHklwZOAFbP+CIcGkjYnZ4eFpGMabdpDpibDuW
lWjslsL+RCX3hhAoSNcZqKyKf9glIduonz3MuiEwXpZAEH/d1tlMJawvbRMYWRach3IiksM35G2E
bcRyTSYg7RkxAFwphVoIMLC06fbiLlH5pHl8EfwFAAH6nntFpx9RWQ6UsPu93FUEPZ3gVRTN/HCR
f0IvDzwpmf7MPp4uF8YXBnb6otlG1J68LlWYK8ytksgUYOJXDQTVApOM1Iwc3dwgo+G7eKEdK5ju
Nm0kV2QnA2r5EjwDybjJzRUITWosE+uuCJKk2+8yMzvf9flTZp+YFKSlQznQ7/cJF8O24djHL5OT
vV0vc9tfjLZqhxowIQ5H2sUiOHFwa68wOsIMxs4PNmcZsQCo9yWCquSa1UjwIUIogURYVG1bI1H/
2H6CzVKMqhhANf3cOsu8Oia395T5syIc1eGABO2laM2g4T1XruwVV5tqy08TCF0E3ZerZorndRDY
L5ylQvkJeMsnX69wHqjwRhNR9UylKW7dACJRtloiLbn130QDsCub7NcI47cZSwg+ny0KhekeXeRA
iwb21Wcx+6Iq4smS7jQoTdDymLjZxbCYlMctEveEPQmvd5BZkQ+Pj1zHVmv+ezHZV0EqaedF/HNz
ETQzQqHn1hulIGGA+kjT1mXWpFsL/0CAPPavCHb3QmypT8ee1Da+gsAAAANpQZ4zRREsI/8BLq02
AE04IKbM5p5WhOZ9iEDV+lP3qDUSvKxpQXEFZOyA5jQkiK+V7cBOyOYsWhJaj2BRhdoS9ZC5SCLv
qZ0NF2Ra65jMnw99QEd2dDAapXEkxcKeJxa7e8hSU8qeqt93IIAiBYns6CarPwQtGnLRyyHHHxbB
f80vSVqFtMxrLRh1+a/79DFjv4t2vvCUJTz+qJx0v/kJ9VzlyxbWJBMNKArfa0gK7NWGLPj+1BGA
FQek9z2KNXnPqDmvtCb+8ulNz8byxpsZtCvFyRNPpGc9ZbukBuoIlXHaswlySwlZJYR1JZ6jFPUe
qEIImnyg5oEafVpdo1QwwOW1KZ/8prC9tfOpDTVcqA4k9XoxwMrsKMl1v9QmgGSjBrMVHlX/yVFp
8rP7i38q16rQxCtiQUP02H4OeKnRL2eU84buV/Y5zORrV2su23pJrJxdMcWUaNiz9XK2G+RrUg1o
DxcVudpC1k4hcyesUVGd+c5npxqWdV1axILGVFIsZLF/rzvTjHkd54f+JfSyZZHqkA754yal+hf+
EOU7Ca7ThUfO3KAK5UwzSZmoW2nvPwteaXyqnLTrA8k41Y1SvUYvG7zcP0qgf2uZMdEHUd6dbfua
Dzz/BIjdCi0Iysyi3YpsablnsfOXpQtfBRo/XDoOC1pnqbCvTYNTj2igvNLFGUplmwz4L6dMoWzw
RDMgPXaA33uxH5geyrNKPuIq6tmE6abVjA7EQNtDV67BYUFYCm/Br6cXlnhOm/eVyS1fGz78BMvE
HM/i2fl/VVv42/99E2zg6dgfiWnT8h9FUvvJ8bwaZjCuaOqcom68YH0jBkTvMvC88HL/eXDVmLSS
TjPhASgakw/oOxSYZc+fDRdHC/MRg1IhfeJBXdvgfYfUYnhwVHXYnvJoBrLU8ZK0l+IvqBYlFgnB
kgulpjtaqhyolF2UW48a9Bn6v+WiLBV2WNs1/YlkT2SRTDNJ7VYG8vYAlJVTloSxcRILO8H4nJrW
7JylG+z9NIn7BmicwjCDM4+Ws/wgI62Br+UYz6KYbKksm+K0ipGH5gguKdOwCHWMY9dRxWCcVIMI
U9kc24x8uc1vfcC175ZGKyIDjkEBZV/AONTijC0fddN7S0l2yvAV+BwWQF18D2CpMEfawK9Rg6dk
fwNwB2XwAAAC3QGeVGpH/wHcmrwARBX/F+IL0Rj7ltoVOdhSwvSYzWtsfalrneJwsCkh6N5GkHed
Jv8y178U3L0IOp1ou/9aVby92dpud2vOOoUkpad/+mSmucgmnlprusTHv9eglrFecTikXQlmfXRS
FbjaIpTDzE6VBYzyVt0OuQgLYSsKcsKtrtQVtSLLB99i2svsXg1ro2+9DlmBI6XNNPM00RTYipz/
WCgiS8fivT2PNMhKFaz/uqG2ehsNe+R0H4WJGW4Stld7vmnzRzt+3Q9vYSNW0MULUF410U443oqz
DprX0E6SxU4cPcsmXK5PySbCBZeHJy5n20YLrexK7DNYX10FGcmjyMwo+rUuiSEqnzzMSZbc/u+W
+OHCQThWcjV9k5AnBUNsZWl7BkhSBoaTw2fl/aq6RcMJ1Wx1+3gTaU3pEYpGAEfQlSjXyzpbjY4i
ZRs6qCqU/Dzrh4XFoe8mV6ZZNAYmSwuyNmpZiLHfL67ET0EBaA2UPOQejlmAGLYCpR4AYqGGMZRl
9VgLkH39DOC087jhTXAb6G+6jJB8gjoLwNHkBAgkCJZpyCVyDlBOF7R9vDAHIBT02VFEOiikW2nZ
UXU4kK7ZKBpMLiifg9frazvZCegx1ZauaKUsmOGJcHqLLVyMCtzPW/BvbvWpOljIEWt/TzNpMOID
ILwN1nZRrW0HMIHOV31zqxPk+FX9QEuMfHMJMgvhtBK+QEAT0F+0OFN14BUbI2XFylEvFXjzKWAc
UPJTtCqCFAJTZhpLMvlR0wBSPKcchO7VyMBRS6N1/DTC+LnNRotZ7mNveztAlptc9AMNlcoy2zeO
bPYE32mVgZBg4g7aY88St1Q6BuqwFNfeM5rKffpzRnunSOoTg2YqXKi92xOwAj1bQTtLl5J3/UFE
9vYDReMgApKLv0XvzszsrxzbUbSgP0lT6lYIy3CGxV76wbVBJaNzZOq0/2xN9D86EXLlBkxGJKPR
4vkAAAdfQZpXSahBbJlMFEwv//6MsAOjfguAEH5VBZT5jlWBCtPsKN0ZbDJgli6aeBaoLeGsVMJU
g/rGW9PwznCCquamZc7buUpCzqr+g520e3dYy30277IxyWAWA54zdqZm0KJDDoskBjRVsPTCXO9d
qTt3Phdg+SMlA7KNveATfrlY5qTSOjNfb1n37Ksy5UHWWsOpd705p/GQbEwrkkGSZ672nksUCda3
Nt7uk4l/Ch1HhvyYPgT5vODfQAJf2GB8C5o3YGzPUQr2JAcpK477vMMBuqPToFVh0YLmjMrPqcXC
RlsqTRPUGEwpBG6kHTZgr3omcpccIG6yXs6/S8gI/dJeqnX83waZSkXLr9QPhH8ppcE381mDySax
prw3E2MwkdcwWffU3hIUmBFoyQ+bPXxX8VikxAZlyLXCe65vXchPh74TMeItbovQDarwcRjvpOrF
DPtbzDZX88WZtPRfQaKAiT5K2MIrkVm+RpBaMAERCrS9SLwQgeKsJkPgrvm1eO8RkhV4LZ/0ThAG
PGfcZDIaz1PwkT7VSZRj4lqV5henB5RRHoe5V6A48YM+2G84EAOYuXRa0Elkc/REeEIU3GZauHrK
8PkyUrp3Eorw9PzkRtagyrUM55mqt0RSfXsyp0eCqjbLsQrlHX3rRCgKJm6DtTdcZE0+oKoKdKrQ
rxd4FEAkdC/OhUvSjbmcPBxyJwDsuNv8y9YW8MRV3Hz7N4RkGKYuL41HHnFx3RJ33YpSw8sGb/jY
e3zb2yHlyZ8IPXA1nEjJgy0/Qy6siTpw7wPy+qSr3pr9K7ybLABMiPVMjarY28t9uf4vZXlrbwnH
C+bi0D9vAf4xS/wPcqQtP3ojQlJc8l9xvTEFOdilG4hNYyXnUwhTM6arTwXD+PrnhC6oq87d190R
pSN48vCGNAu6mtAQ2Y8tkyO/iT7aFa303KxwjCYXQJYMh/9ptBPnGzIwAc56p77cq/OWBbe28Oke
ssIY7ee+/HoY4TQl3cSwCnLxjSjIfaUJ/vm/1/x/8xQmEpg2A/wFP3ZpgrtyCvwfysvCkHElujdh
Qb50tKxT7rJhWHKWVvAS7Ctaxb/n9/9NpX1NFyCUs/MpiXf3sdJcsHIvte01Bld2VZ3MD6b3Q72E
/fSz96l3L7bS+YQuiYX5JNTf+FOkR99lonOTb9vNxSp3xiXA6DRDpxECqyBZqhEQG7o12nNtAFBd
RdGTc70t+qxeIUAAdTXKCAmEWc02R1sB4b/GyyxBabyRNRhfIcgIwWuF7L385KG8YnrDCB2OPKHv
mxp1yQn7T13K99JBBh44AzhpZUVXzNfjx1pkkodQf1gQh924zRY/jBH/kU0az9OQqdUZhERcMxLS
0dujr18OjPveCoUbLPAUj7zqeAzvXs1rGrcb0SndOmmpd9UBxl6q4F6UAr879mEJ9ThbvWd60KrT
zC2fAwztVplptvwoVNMFc6b5Gzsyv3uwxdJVGWLIIg+HwDMIULgh6TNb6NJpyCTrtGNljvgBlXsk
mUWJpnTsLGte1XOjWr3Oi9BieS53L3f7LI9GQ6B4krhnXsl/kodIbNy6kULHuq5KyZafBVz5SzUf
98yZp84hh6MR9/h9PQQdn/Ja5tJ5cJYwIXovE3y7WQpxf9NGLBJyL6WwXMtZY/rv7OrfHHI5JmMn
15cyoazB4QzMWNfHOXvd0c0EZRSC+CXxjlkxIIEUufsAPSqUbJqt2q83qQlmSWSYpbZEQXV5BVVO
zSIDijET+oGMrkeXfEfE9saJGeeNozF+1Uz8h5DoWxuLqoxjumcPKzKBAPZUiDcY0a0ASgs7a/8a
RdTCw+NYkgtIXs8GGPTv/WktFF+LjA4ru0R9hAjyhE5YJ52zGuAD6BMI0uxe7ym04e24/4MBQnBJ
3iWXAkgQi/e1Nxwubjx7xUcFYZE8tfs0QE9+zibE7GXWWAmx2MG/M0H9r7M73EUOWQWkS0EnFEr3
fmy7sCCycaCmHG02mgEHfDtLsD7EYSmenRY82Qs7K4XwsAieP8cYny1GbyVtDa7CkJJhzkL2i2Qn
CxDjC9ekg569l2N95rnlZCbDyakT1Bdc72kx73jQfILpZJP51nQnWc7jPbVzOvitddpXAvN7d+Zz
gc8l/y4Pv5U5ZxZ1pdZL0Tbm/ufY64JW1Zppgz7qPvQ1uM5TDQ+0982BoKjfihhlOwFBOcHu9vDV
9n+nFPakQ10XL3pv4diNsqNm7wWMKVdIE3cjZuNPdMaL9eJ/sAjdhZKQf2kXN3JPVXTdgRQrOZ6v
5ktlvhoIesSEnyTnADAQm3hvuDkjRaJbyF87vweX3VLLHfXpMnA4suBXWDqYA0tN2IvH3/wThw0I
ww4+GTrDI/isyQEwQNDzrgmQ8MKhLmI4UPvha3JC9eEc1F8acKw40pjj9tr1VjuJnupuV85MFn9p
KLjZ0Ti8i0LxddIF83LxxdHC14n+OJphbs2YaXwohrVJcv/Jnkfwcpg8gQsKKTk3bTB6t4ALTIS5
bT0T104vRQGet8WsAAACPgGedmpH/wEhkqlFSKzeYQATbx92VwKW5+hIuzc6VwkBNW4hjbXIp107
OarKWfD0sow49vIqm5PHV91Kou2q4VlVPUYtyOo+7sAL6zF1MbZntQgh5Mz/m0BBLN6EfBXtNK7l
tIWIBJJFcVKXb7/So/2N38zpnBinHUUru2fuHXta+MwZMLJkd4hHyM+7VmMPcJUBUDhuNudyEwnM
r+0WE24rrivKbLcMeV8pU3fwSQ5FGNBAX95QhusaJv7II+6jj47LVE3q/lF1VlNdks8sXWKKtH0Q
aj8TiBf54PEeB51cCY5IbUNjgRHYqlmc6NLwRCXiuEI8xQRz03/RD6oHMz1TPW6UGQXgtolOHASX
VlT/M/QcrmshrNFE3pP6v/MeHtY4Xh9eOlMR1scjQL/0wwCyLpN2dJmM2JaQOtwsdssp5Y9dEHhd
BTNUYdVK66nsyBINV8hNAr49MmAdcKCw4RANyNRo8y6BZ97jB6Xlv+0pa5O7YNh92dwY1HK5xFBc
7DwRGQomvH9SLwNAoqom+FWW3XwSBcXHduohYvrYHBeuGV7tBW1Fp1fiP4Igg46fsJY44yGOW5l0
cFUcvT8I1bIG7l0cfKunUUYOuThuYj6OlavyXxqv8TosISw9Fc5mrqce/g5puh3B8ro/VJ3HEzUE
Yxw+RGP3DzH/rhOXcRx7c1C9Sm5xLgoyyFfdDpjoX9Yru/xtOsfizWJl0pLmKaq2gamL1tAtjO7u
1+K4sCnIAx2cnZZejaRiOSkOIH8AAAXmQZp5SeEKUmUwUsL//oywA6MeAHOSzcALJdtoxswCQYxl
T22ES21YCeIDkHHY6POdbzPLtNqYtoX74vrRgusVnmW197U1xaWYXMj/tPRxOo+NOGUtnmnfRAR8
EYHOVjYW1ivG0OTtvOQbfX2D4W4Ly44UVlgg2ykoytn8vAB9A8uowD78eRrV+xYd92sornJt6wnz
aTSzfZiKnWeZyaeSZei3R80xKUEBrs4hvCSX2mAT0a2axRK4CcJ16iFfLq5/RaLCPPZC5lUqTJlm
3ZpyBE3rpKewXaTtALHpSj9aUxZb7pRvN5FOod1VjOxlQZb5WTZtoHyxz+v2Aoiv9/wbwH2rsmJB
1WO43DAQnmd0Uma4BT3ZXHMm8ONAZkTZ++hAhIomzS3vbEfzPAP8flOtpeQL+so//hBvti9S623Q
FzzGQ3R+AifVmskZ91oAPab6Lq5j+ByZ0MS9i1Gg4DVr5zECOGam1upPPnuAVtizsOolQ5SmEayF
CratMr+kVl+R6nI9l7qUh1uRAQmEgcdWVkYs2zZ0ePpm7YmzbPG+touh/OIMr2KMpuIKgoADPO9+
nlDRUpj86CB9w2AqyGi13zH2MdqJ/KuPp1THRrJxQ28ldmDp0O9ws4oyCufC4syyrH2k1JY00Lfc
n/UASj0oOg9+xhGVrinMFTqvJDEwiQX7ejjOiFfwLbRslIuH3Jjhr1gmMQYPkfBBXbsdsWn3TXHe
inwOtFVDOscHHKQzjBh4swnAJ6lpQapeo0Xxc+PKHOeqIX6hpoAL9T8tes7z+f3e4W0n80bYvKFE
a0p+7ASf8xAnqOJpnoD4HCVayG5lZX/RIYtPTouup96uNe2+Qv8T6vtOSwUiypdUWuZAXiUkVudN
qUbAt0jI9PTJTTU+i8vkRiTxm1GAtILe8dNCBMF/WvGjRalWllblAifv3S8li0a9CM28f5j1oET5
Pt/O2MtCoRkNqDFFvrFfiUhnssygRJozd16Oi7JG1ITfwl93ZFo1JrtTY8K09nTuJE+XrKDQnUlk
xLsqxYzz2QgUvAmykuuV7eRmfm5JdppKZSaLYkjcfUED8KmnefztbCf6DrSgGd/RQzeIOBjirM1+
Z/PBIIfwChFLOA3dSotA6bRb1s/tTW08a5Q9XT1HCbpO5y1wATejbzqiF4wgdU3oBiDeGvS6kSIi
todaU9nx2hsRXvrYKcUJBPc3WeG/lNsYfxFwx8TX32oiIxPAeN5e59MmatWv8vykK8d/xpRHzHOB
YiWgzbr71yhuF9iMjGNX+kKdlPlf3syEonQVdChcqtxJSxfxSGHFxSPZNeDDRDcaZzvyFRlwailV
sNe9sx69yRWiP7zj5Vj2z62XZxk4dG5t5a37OPs/jRTJ12mFDAfGU9HiEvJQ95K1IRl4Kt/recZc
IRIY4zytzR/zvtYbDK7/YlpgI5VbzGkSiOzOgXCn3T4Cf8U7UZbYzlWTfWIO2rYUqubCEMbXfQIK
SQgiS4uHRmdu3nv4BCF/IwrwzuUOQy+jGlP4SmGsrpk8US4I5yI7WEiFuyEyrJVAHAgKYrHucDrZ
MfWF/9obF2mJXYZnxWecGAao7c3Zc65ggAoSO4RMwdhfVKsBrz9NtkOCAGVdMmh8zfylwtg0/7ZH
Qjx0fZp7ymugFIGVyQx3+0IWGxRedyNMt+onRsP2+9FOFKM9DFus8fwWFq+w3b0LPoEXt6dA4uHK
2mK6RXz7WfvvQuGx3ITNwGN7fIVHbm9L1UXO+KrygPB/0jtEct0dcWcVOmwnAfNWVoeKi1Rq38a8
xkBGAe3qz/KAmTmMqPyvl3n2JqGoxYrexYP2uSWx6TcxwEE42ja6tCe7jMQi48W0KyUtJJAYlzjB
1kMCJ6ZgFUzjwgZqn6S4HaG9ImumVrfbfuTvXiP3dmSQhq7wTXZjRrzDxEMQUj7V+LZHbWygIZ8s
U09zVe3ocVTywD0EZLKYiO5M3zE7QW61446xcfJQULTbuLf0ppCtUnY4NxEF3JTEfU0uOQAAAgUB
nphqR/8B2aWNAu7QtqmwAeaAYrqFrHZ9QjEQaAEYe0tgR2UsBYBzGVQ7dlidOD323nOpXjjfPqCY
IYzW6drrsxwBKzjG2pgzK5cM5O1GjNeuP1JjgpvZqWgAzdrotI/06tfO8Z3K8wwfvFj7K0gRI6sS
4EpVCBaYjSk8xRSsPuyFbF1bUyAP0p2qZCM1lpRig15Gz9W8QlJ8MH/EIrwnz4ocEu1iuvY/OaiW
6ZZjmb+8UwKQEd2EEcPbDd4HejyvQ60mPA9x1Qd9g7femReolSdNEq9/g84w/drQ7U0c6T7fg81y
/GETjMojKN5RYk/+5bolFPaN0kyFL36uXatvJOV11VBm91/gZLGYl9MvkxcU+R9xTJkVrsNxNJUe
sDoDOOHuzKD2r7In7QqwFuhVkaJ8LplCIzoFmximCH3jnBWy9cL+SXmEeIfz+OtTO2iNp7jzRzry
ZwmCDASKoGhmwZY5JjYU74XruEF2vOfa5oHjQ25eorcjkVreo1+SAxJVD+aYVRZ77eEiI9am78DS
yGwcRgYNW3CYjZvziyzy8d746fOJSCVwH0Bv18/pR20upvYgABE5fACKL1HIC6vORpSVuqB5AOpx
fwyupuRNOchuhIwLn+vPydgR25owToiy3PEMOVE4+jxzugpKYhsl23kW9+aCZiYc0QO2Pwrc6GWd
iT+AAAAFxUGam0nhDomUwUTC//6MsAOlfUDQ2wA1m9nKBGOx/IwLbCLBGjyIIRfgQOGrpqTTGkXa
51hkNN0FfMFS4vxfydsw1NmutQ5+9FGYs7RnTeN48mxsJrBvDy+6dO2ljXvcJiS2cZpx1L7INfT6
0pdPQ57z4qe2N95etKuio02gU/034mnsT89A858MsIS21RBKmi2zxGIG9izRxKXoxs6a84uw0oq+
ihOk2MpKNwM/NbOp9FEJ1h4NzMZfpBHG/h16AUX+vsnhfhw+zchI7g6CXiZhVbAJUsP90/Wo7o9e
brymEHTrHuKAyftZAl4ttVItQw9653u13OzhHTW23j74LzAmF4F7O/d/i8O++CQNrGLpFbbKsKzV
JZU3LhnY3hcjxQ86h9EJkiu3Mx+4MJh3RZtGfPuH3g+5oKGPR4ysC9ZKyG6I8erbYDL+DWBR+Lym
uUpWYyGLiqHWpainn0faxN7vicaLH8cMi/TOXrEJH3J5lCDSLYqOP/taHV3zemOhL7a7OM3kF19S
UCyAF4Art/0bWojj6X8eatmMRWPZgZJcBEQ5VGthLg3+ZdB0YO1wiRvIWbMx8pgA0l/BLST1lrZ2
ArHZ+Ms9168Xnp1V6Fz1240ei9rw1wVnZT1ppOwoVM74TIfC82MyuZuIM7VOI3oluuAkoeX6ZW7E
+vZv91qw32BzrI+iWhbccIVyEy+hp5l+K/F3lMdE7CfJs8+/kV8AOgDfZLSCe/P/3dTMw5zEUzB3
FA+XNk9trSRYBtzDP9QkxfGMExFsKAffy5gDXXkaFkvjQJgQiu+0MElokCK36A1K/27i6/U9hrSJ
aUQakjuIP7yolZW5OX8MZBpH6voj5u5RZBXQKUQnJl3p3xqMxF2L2huNlXLJgWrsFYZMVH3olteq
N5W5BD3q8yKGXui37XpQifwAVCQmdnhsKAF5mwY+HbLCqIx7kCCfmj6nqx8nIIkLmZ6gU/h1o285
JaOfGtMDdCFeDTPQ5nD49OkiohkVfrq8NFeHaWBLqhWSM7RgFk6vmWx38v0rkz39Jte+uw9ZrO5N
QBjdRtzJYnCtS6v1abkjppG9i/t+xMbO6mKIezBjXGW4L27lx/W8nNKO6ZKgw829ylG9P+PpHV1b
5GETU9YlR0AfMxPozJfeIoMNbaBKX0Fos4UOULYyYvju4XlAJRxt+tBaksTzdC6Cv3y6Q7Y6y/kj
AFy7k9k8FAohNB4OBOozzcmsLMbGCFabMx8Rv/hG+/Ixb/aPhHzinTO5gm+j8pPdzy/q4QXFGPCo
/44lHwI4i/C4I6hwjbZH1nYuLa1mf9v2fLP6W48eB7FG6wignCKAdThzErMzec1y9DZahtwd6Aax
AKoCAWdXqQ6GO3CLYdF5iGnaoLslmvwlooedK2ri3AH5ZG/DCRUXEUmByI8K1lbJDm/rHP3NudVk
tn36AiNCjUINS8iSqQQn/mBw2AkH3cxZu2Kkc/KrDEdB2iLDi+Y9CF/1bacmDU8O2wIgzJSg+/XN
LPZFZ7JdtydGc1FlUSIhps/3LGPA1vP5ul6JtZqzcfgBi8Ts4gM0mLXo2ewaohtrkqKLqnw0w57f
PYHa4Tv7qOxGcyjukfH7rGwWMt/PJ8WaUyHiSwVd974dAVZiByJ2GgvlGB0kmuoRirTuLMJu5JqN
wqQVaT0RHTWVXk/uUzt7/qg3xQRMNP8UvtGfzhoQWg7OaGs/08Fk+Y2QADHxDiAs/H9nTuEzuqpP
k4kMGlzHuPQDOuChNCT+8riCnl1wT8fpEmNdnu9rKpB8G9QoLsBtNCLTBnTHvhXaC+2YtDtAP7ey
p+I080l7XMZH3+b9yvPUtySJBT3vzcE47gbjE2gYN0VogYOLad+WmBztItmNbwP5yOxs7t2T3lKj
Y/gWhvEE3AcRIE+81VAxtUnPw600fNNJ10T4LWMJtoOQTyUvcg6dXWOACjsAGF/uGHXGUMEyHReO
BKkAAAIgAZ66akf/AdoV7W+uq4LfXsDLlUK7m8ZYueRVvhNpdW0wAaChqIAynKML79GuhMyS1xcf
xCgD71No8a+rRtZIf7DUblTrY1mBoDTdmMV5lGQIYdnGPHE1yBOg5gyin6UHB0OMivhN8Jl32dA+
F6tyTFGtk2tHiZNbmXyKyf6VJ3ztmXdj7Bj205K7qEWTlxO18SOMYhIGGVmky6RMUkDynIN6LRNP
bC/UTslYV+JqFV5y7AJK0cU+rcrK44OhnJgyYy0BdMJXwJk7zNUP46/gNPkyEZrW4YRV1MFZxalJ
unIvi4j/wSHSV7V0ii9ucn+fyJUXkF18+y8DLIawPgHp+3U/GyONi4QCYofT3shrl19o1Km6jA1w
4Z7ShUGGKaABezoZAt4Wnb9PCuxeZYEDJDcXrQaFi3GNWEZdE9D4WK5aMy6ny80ea97sJfwNDqTN
s5z0OwmfxPujcEkbTsYw4GVPPzkXNSu9sFk77qIAFSeIYbDJwzVlfE2tuwQERNMPF3A1CHsyl9Rm
HtRQm4tPIB1+hROEOMuyf4izeZ2Ouwt0FD1ahqT4G93ooA6b+YFhwKcTWfF20Ut3ASMEiIhyNp2m
8AW8HQuWSnDI3XMT6EOkw+rV6meNxrm4/W5VvgAyJ3+3uy6uY6kiN8GIWD31Dr9sujtJCy+WHnwB
oYIR/idCu2WbVs+jXrh6fBlA0dyHmZn86V+PB9XDLnVc5NkEQAAABiBBmr1J4Q8mUwU8L//+jLAD
o7+yHwAOC6EtqiIoe30MpcpV5q1hFJw9ghxkRXQzVn6C59cSwaE/8d1EeFs+zwnjE+tS6E+iuYxh
DMnPemoe3Iw75MkA+4whuRiC2lI96TxgPEWhfa8uOXe9AJvBbJFVAdVt5Uxfut20nRAZQVr9t9tj
l2zMer+ld6fCLXC5IEOipeeQzI6885yjJ4Cu1Dz1ssHnH9NrowpxrjY0CSRa5uKNnm9hoz8uXedf
RsZRe+tM2w4DiAAbAkH7xq1aRGHYm6el21NDVFdpYj8/4M/6x8LD7CFUcOSFwqdSDtidOpKHAvrE
WsuFR0GLAxvdKNw8+OKlSYDPt9bFIz7nHmmXp2GmQ35ytVCbtaDP16iJeiKf3DPKauiZSZ1b8CFp
kZUBDv9HjHUJTkJFt4JDEo7Du6La9CP9NEIZXMo+YlKCNgC+wa+XlBmDGyeIl9gg99ITN6JUQhUV
VAdTUts4Zzmesjddog4gKQSvaM0KY0yPzl9czYj481W7orKihQBrE97NEg54Sse7E1hJ0NXF5Rb2
8TXQWxC8heoQ2yNltEbEpPy4wqNEG38ZLIBFNmRlLc+IffV9/cME9urjGnsEB9tl+OAJTu5mZIs3
cEKqzGD6fW0291eg+lY4CilZmFOalcRY2daq7lUOqtPyOyB7lqtCC7cxqdD6LncB5JuuMWUSvh8U
ivYa/oLDb7mu+JLO7FQtycRca69FGDDjtDKqjBYCQX/7/oI/Cg65czS16B6dalopP0LzVWux3Ymd
stU9ELN03dWrgGdR0moKekAsNd3MHaJVQMsCtpKp54iptZWueBpJhG4dDZ+v0AB97hv8NulSRSns
wx64OYDJ+SiqtYm8qO7N9e29ua8MyEq+dG6IJQQEmLPGl53b23XTqWJ7KbFzBP5mPVO761RFh3Rr
9IVhlYLhkIIDwHXn/oIS9//ZjcSzajGAL1Hbj1UmhJ5ksSVQneR3s2dSvxpJ6UoSbpGVVl115QLJ
SQq3EHh/NNqDFLiHV2w/cGjBOqmKwyrQl7N15w9dtX1Xr1EY+hfVq12nIg6Hn21hl2myd+bNsT+/
+3HoF4s7hYnBiduxHuhe9V7a70cqwkGQl0tl9yIFqgMX//yAb5nbgdkSbIlACKdsRFr1hC65m28N
j6v7OOJGV/7ZJ3sSuRFybwHHgB2+tv76uTqE0Y7NxX6oVOUCeo6jKqb6PGC24PsGewxBF/TA6IV6
vqVqbEwd0uUA524m2eStsVYc4cdMljA+7k3Pw0NYD2KS5F1SyWv/yVGaj3KfSlxheBdE9bfTQ4QC
akLSxJ0F8FDEpP5jWxqK+Mqg5BH58dEa1MXdBk/zhMT0246EFSoTuSZWjejEg6R2a7if/EhIrrrN
EM0hkC4vgYi+rG9jDBl7+EzV4oQLlT5IbR72LNDzQ4WIVOuiMiO5Z+HKOwi8Hi7u5OfmFc3OVnBu
dcJOMKoqIup/55jDST6j+zGadxwlX8geixhmRxpiw76uF49TpKkIy3WXQ/mEI5A7kMCCGNS6pOs6
m2OkJkO+lR0AYWWQKjOQ8WXY0VPPxk72wwexEqPRNmlVDh0LTY/iOnNCzELmj/adYPQh0HGQIBV0
XiMoFhaboCalSu7qi2AwReSDRPW52TJtnaM9uojah3z6WPsSq+G22TvNF2tSwTT8gep9AZ5tFMiK
kKC0zEQccDlygmcsImiKMI99kCcqpej35n93eD16cmX/wNRNDveB8c0cKiZ+vhdnNjw4pto9wGIr
RQN1+f7/dMekT57qgHUexGho8bX5pTMwQ3riDFlbwvNjoQGFEVOfLzwKZK4PJgImNyKp4/kjZcn+
KW+hVcFxAmlqsXYCA+XBznX3tJdGnST//IqPR61xEMEnCH1rRX59bFdInC6cMltvM8s/BR8NbqDk
3mSATBJC5PLLQr78n8PqWv1pCoc9HNCmLqJXwR8eAzbdUjfX++q4HMrO9/SXfLx61O9o7srFXpt6
AgkRdqzgk08RElv0ogD8Hs9KrfJ/ULPIty1NDHC7UG9kfvrD4ruUiPglV361+h0ub+Oky2Zj60UT
WtFYnZ84adpzlV1PdQAAAg0BntxqR/8B2pqJVsJwnibrqh6ACHynfAEKoI5HJWgm0jK3PMl1IbmM
A+0fBHlGtQJ9PaaU4DBOalZFPbwqee3E23hdhK5RCnrRsyh2wF9wdXwgcu//ss0+Oc3l+MujE/LQ
fO5/HmZlTG82MXKVaLnYJVcRoOLU48rLVrKto9nJMwm5Z7w22aLs6h0lBNQGIhb6dbhjmjqVj1Cd
MtgQon28+zOClvcLnL00bW+dzpnxhyv9AEHhIiMSeX4wIORdhCQLXKU+V/I0Mk6zNi5+XVOM61jY
d01ISYqirtGLDm6TSj9GUpwMzuf1Vl5QxOeB7E1mBAG3ZM5h6D051V+IZ1ijcOHhVVeK8/eD73u/
Gl2iFpyeZFuFh4pr/szHL5hVmz3DMgU1sqRoZHd7cDKjCVE56EOb6yYXnvYKJCLWpn8GxIZOBtTZ
l6E0iKMzlRQPMCfvQO/akffSG2QbDdrbjfPHidMnD77wlYaK3l1LUthwp19sXbzJ4gQFvgbU8n8i
Zkf358LjjOGW6nCkOaetbDgld1+EcRetvUJKk5c5U5Qo3mirzjzmZDRdFDRURx0wqMbTgAq3+smK
I1UIHh/sMr26veN4tJndVr/NibyUIuEh44aE9XcvkSuyGblcWWa0cxotzePWg7tLNb/0IFu517oF
xKHHxTJSvWViorCxuGNO2v0qmFnmQE1zp3xm34EAAAcJQZrASeEPJlMCF//+jLADoxT4KQQAHG1H
pfOp/sB8P5EnQJzMlEBNaf8cJLUHvan174/3zbPCeSzhy1VILWBKK+YCrZ9rYC9kOsDnylBt/yXl
kH/b9EL7oCioxv8UAdmTXt+DOfkObt0YQI/pLaoYPotJ9mA/Ged7Q9oUih0Rw8wznO55uzLnA40v
J7Nfw/NkY2nEDodSvaOB/BD0Z7l9F9TJgHuHDDBhW77Olq1OIxS7zd4l3Pf5gC883HSKMniyjJRO
87K4zOsQsd4daxwbjLm/5Gb+rZ/XqNT9winQjrez3khUXHn2qhYmD1xqYAgwXwEMRzcqkZNzqdiy
TTnCrCGEJwA9TMNG0+/Os49seC75eqbEh7zDwmq2To2ZqlxnyCj+rnk8DKVTY6IktmROjr2UBMt+
x35WeNqwDlo3K3RZfyP1Uk7nUclD76RSFVBi7/c64phK5zvk9GlryE8ty3PFSSCNtCv1ymlxJEuU
eARpONWLoOhMaDuTe0YjMS++UiKvBGjbCI71kk7mGA69kwgD3e/uXfr1HxYwVmAUJhI52ltZPxX7
EgHA72/SyzaPMNKKH6vqx51U30qPXfpY0BXJshNry2cf/331404RsLAoDDNuwnQaIjZpGFgHLKpp
qmszRIA819ndJ2LrSXEBMZNRoISlFdVfwtJO9bZ2XPOowxyEiBQ1dHu7XbK4oVTju3zulgTiMV4v
9b3bvIUmCOobYiB072rNxV6UxY/qjAih92Dn+mIEriuqc6fXXn1wwiXYCnYb1HnNEWHgP946Rpof
YMsyhx4JUKL+l6MCrTokQADrTQSsc6ENFMnQGQGSSCbkO4FeGYTIiabV1HXQ47SLpSym6xw4BQD/
TaA9/bpNfTv+vLP1Pdj7uHehsWqquFgE4kq1vWpEglbkux3qRgmytA1IzBW0Rpfc3w3Gjr/Maheo
NtC7pJd42rqqeB3fqkcEDno30NeJunIknoG+6s5L2xTlYeUZm+vjgAgGCiHZ9SGsUWqii6iO1CDJ
ivvamCChFthSEee1IBSjuXHLYhpyHnzZqjMK/Q+QvUMPAypn6v+rSOZ6jNpNfT+zZdd1Dgn29b5f
zmu2eClbalfPDDYqAPD0ItiRXL9UqgVHfyxnGAdWcdPljwVYPAITPi+6Yc/YiSyQFFoIinsOk7ZU
58lYVBDKATYdPSMZf5MrFUaYQlh2/rPbxrBZY/iYIWZ9vkbN8Tfs4Cg8Y7kmmt7jLNlKkO5V5oZR
EHquWaloIty1Ln1cXR4Bf2mC2wlaQvqtO4sDLF+Kpxndw0z9fPHbexkgtJf9Y3lR8G7qJhWXxkWU
LNnHLQIBiKOLYcpM9evzFQPktCvgOvjrJhgcC5Pw4gTBeneXklF2SnHn4/Egy6dFjw8roS9JtEi7
84Zc7dkXiDRcN3W5e2bJZPCmm6nCXUsD/LxzqQsrgv0iOxTs3jes5n/WwJ4rdw0mzwnuY5UXxlKu
fgpTEDqQau0k+xSEe5Iekxl5Ds9MUw2Yawlhu/HlclBk95TubxMOB9epVaa+yaGznoAxDAe9VxC+
RD/O4gQAU899Auu5bxji3cwb6xt/iLTI4UWDxmxLZDnjQkoPR9xlJwIBC+/fu1ktitjguzBohaL+
9CawlOTzfYPqx0nMrUOBTYsYvSInJJX3NAx53QBSvzBMYSuVdoIam4vG8rnsVvd4p7ickR22LDf0
hrocIMG+pRKirEreRNLmTsXvhumwZJM/clvU2dQ9KL1a/YBrdPGZ6+uallxw38TYfLsd9ez0Mnw7
WZbTjODmsKbrP3R0Tw3AHtn9ZgI3plj4tncct0I2toHyMAiG1NUEVOu5yjRBHwK8sOggEbqs5We6
MtzlX56qMijfPG1EfEAAA4wTeYGQ9uyNIDcHO+DO+VCDoJUFdD4X8KCdBVkheDfQpy9wWITUei/M
esM5BflTGnBKXALNP31OtRMRRVMuB3rdsaBelkLDUpQe6+TaqYP/7pujN8N9edVkcJRC1+mGnN6o
Kwbk9tVgU42uwl+JZrcHq0XLursuHpE942nFPs+MboKL0DRnaL+1tq6/6TcxODgRhW7uv3K0f37I
zqdiVTAWle5U5r5ZvATaQnLIwwKG0IV4rSCIAlaANDkO9CFPr1tSQbweQXcKWL1RG2wews1iizvH
doC7Q/sLimAsjj+Ivt8n3yQR9y553HILyvHeRKNJY3dNdUJNbxh/4nZgMJe/pDBiwBAlEhBsmk/B
j3QRdsz3B4S5ofb1bESIuv+SupkZrS5Jfvzeh4QUKIh8WZ+myb60daHYbGBalhLw14NwtZ0aKBVy
OklHZOPsjRkfSrZAv4AvoBVkEv0QDUWy6Z/lYjzSRRmjsJtldglVFwMynI3tVHEFhF0K5Y1xuyfV
NxqlzfZm3WUokAAAAsBBnv5FETwj/wC8/csLTPJABdHUVHi7a2UNj5z30Gds7cNBPXw66y6rax/E
flTc5/8tTYCNXIcQHpnQEOvGFlnG9keHDxYGiVFZ/A4CZSlUP9fGWAedNc1TaqWEiakDbJ5QuBG9
rbPn0occT9MFfHvp0b06wXrAoQvik2JUDq5Q0ele1i6bXd20RNaFgBb4di2QD/8qjybbFi2T3KPF
y18I7MwxArzXkUQIyhmzGJyP8clTbTDMexeu2Np+ZU9F4m+vsrcEAtNlspiLKANvmGKf3c1sSz35
pqgzegT30xvJ5ZXZHOdu83BAJkUkL9DI50dsPoZLC7kPO+btVMsIhIRbipkSfmDCYBPT7HL45hBW
Vr/0dDtIjj9fC/1pBngPvAsHa28tQ7pi/6MbBhcLIcyh9Ii4lXwX3BZhPHR2kuua2zOtQ8P7bYIr
AzPUroMQofuxDrWHMl3CxZDIEcxexU1BeOYx3A1ADUrp9fP1xeE75KFA00+BdN+Vv8KfZuqJX8Hd
YPUuaCX2PCK2pfAAEBBnv6+TlTOoGI4lhWedhhXG31CYBL1xnDJ1ayv3hVdBWMGzocLTWhk7KJ8K
Xr2Sg9+gssbUWbtsCTJpQG919mNgAL1WfiycR6yyJS6jwZvWZOjh5FFD52ef8uLzC3wUc+3OLcHn
1VJKaHV91Hx6OZ58CGbbBUA3aON+0EBBPhnklysToViZhj+T0sdfn0c5OgK/i8PiB4grUTYK5EdZ
L5AuhptL7DrIhyOGixKC4HPKlXcctn38ro6fLfGlXi0dU35KKhARC0Lzcj/JYepggcihcFx70ZRD
1YSMThYc1HbFGrgFKDFXOqseefZzpwVV6QOHnOfyvWWHXcgybhel6IZMPe2oVn8E00iWEsczW+Xw
JdEw8SiLQlLlMURm+nJ7YKP2QhCJnopCrbM6Pxz9WY0ClwAAAlEBnx9qR/8B2slWNahWaXvCLGOj
hi0vSAFVaN/i1xhJteWttqacGVCbEKwxL6ZHwC12YNxBAtSVnd5oO5tq6qJ8d1V6GAZcpgihgxFN
bS6x53wAV1/eSsUbvmITG2B2IprgbH1CiIQGnbmv/tSSrM/9HhRwFiYaCNkY3/NSzLOpmxEguDsG
o6/1Pe7I9XthZyeeo8jrnOfD5JSyjibPfauLWP6SjpmDDsAbuz0A7UbudUmuGZxqHD2yLJxMI+su
jB2QONRZYghTXVIYqhC26hJqRofes61HWkVUN2Fxp3LG+DAlPODOvhwQlRiBaRExjVBLhMYu8EUX
t2tN64OWjvShHQ8qMXxmdwrg3H+G9BmJqYcWX39a2EtZNSAorogEgEoenQnX7GmhjWD2UHaXoGFG
++NyDHB6aF+3mlCZCsmKf9wsWeEfzB+NQ0mrrpWaZ1M/Yzo5RzkHDziKX0FMCuPAjeZa7IdrpDqa
BeGVcap7kWpGxO/VBHYQM2U9im3L0st5N4ymQ31nzeeqEZMzJ+ND7ZAk54n+i+39SeJjIDWgLv+z
GMNlaNpGvksKv0yi9VDyzAxH6X+5gF0BxsKgiVSX4atanMGR34rcBCAqIGdHtROFGr6PwpoUgaoE
t+Tn4hvQuwFvQ3j4yt+INV3yGCMRrAnRIwtawfjUMWn9UtjPqtWuHvF5LBwAeUHggj5D6QVc7akL
76lAzIi9PeJSdo7hKy2VRUrWhJ4Mm4RoqneoS053a5RQFgkCnn2JEnb7RECnYKolRs9a0pA6bUBf
+7CFsQAABlBBmwJJqEFomUwU8K/+OEAOEY1KqgB0juStCT7dR7D5FuWAEc83J9BvoWYBz8HfJCY6
2c5Yp0R14mSu2it/G8H0w9SPH+FHVHfbu5dN1yCsZ4KBLus4gE51WmpkDRjN9D8GJYtT80r6tCPf
GcDVB4G5WCVrOXCfpDlo+tOtt94Ic4sPghPCcUCttqnY35IAHD7MGRHGcGyo/mEH0EiVg3S9kNK1
raGVyDkpb5b4F70gsEQSqhriNImBlbtd3YrEp83ST+L8BbylljLLJje2znyD12GHkoGSfEgqpx84
gryxYyBRrnA2GctVwnsBoD/Hu8WVvmdA40nT5MtrH0cJ6NCAqRteq04K9IPlKjFj8cDS52LBZoo+
ZGDtONNg6EaQl74h1bOGSv31znAlCFEmu2ClwOpdfIJaZpajEeeaxhp61MatB4Bhk3CwFRpzwV7o
Wi6cv2N3WPJsr2ROeIuOY8trW7ETaE9h6w7yly6DVAFQIAaCyWahsH+9i9e61+TJAkrEqTYLwex/
mxFVq0y3TAdCRSG9rqGxaTIR22DI7OxtnmgNCqKyqxZ2FnMaGUGTEoKhBjj8mgLPTiEMpYZje65+
/phw7IWBP+iQLg8yOohPL548yhaim1w/hbDskWaxqgMkibVsLQgiCpfH6VQSx8t8wHhPS4UTKCIe
yo2q7/8fPTGG719OT4P/0nRezwsxrKond+AuoX78GiIagfHRwOaNJiNGw6KCM2XZch5vKOYSULxD
Ud8zYfOOr55fiRlJqzOFv3HHFbAYcn+d1JcshnC01ia9Fn9HSGyHDm+j8JvkvKXMJE9Iy7mN1408
3YwffHl4Hy18S3Hc4PJ8QRKwiqs4N15k+v/nO2zcbJQz3b8n/ZMwyQpIpn4tc0PH9cXmfSroZSIi
gHAAb+tU+RjGgbcqNxOlFPBpI+56x6+aXGpUOghYJlY4hjaFe/ujtAfJrR4gxCLRys+KHz0t46dC
rFU00j6E/d3dEtplup8pqwAUccghHXoDEXf58LHMRlfo1fLrg8GOggZnwhddC4PmHLtjuIjLSmiB
wk/45bimd3mfw1ngb6B5K/9qQc8glVXW3ROWOaGhyRikQbiHXqxyp+1mPFO+VRmdFYEh6jRFW619
605ukeUvvY10beB/WgQEDg3deeSzHj2zq5kl4gEgEKNEgffbdGuEPGqhHuYfwj1kq3WgGJNu7qD+
ZhBF7HAlzs/OFJyiShM2qMqoQnvKIP6b8052zexXIz3yhZKebsbcN9En94cUEHdPDaUmNHrDQuM8
dg7uHsJgJlyKz6taYr+MqA4uZ24OwgpBqc0v05o+aP4SZjYdW8l91tfWXBTYuwbeP7Sz/m7H87QG
FH5AoZPY4OoxlFeWQZ6FOFn2l7GgzhWZqqfuXwVTcUTalQ6HBz0+Ov9ZApamaboTQAhRUKmBqLId
+rwAv2rDgjmWgOqO7FaIpp0v8OOXFQPyhK5TNtu3SZWy/kumUI2ncdTqIDHSMjbL36V3HWJRHjce
4ppCdkzJmDPoh4ILnuXFbfPrmWwzylNuhyqrLwgozGmJHC7TiwhWHIF8l9ULMfeEUC5/tBchRtar
0XLOrXED+OKiro1HvVX6BX3dF0oR8wOF6yI1bVtm7q9ZRDEVaIkL635wx5No2DWNObfewJRTihWJ
oYmG9wqH5sTn97vlrpXlVOteTxSRLVowoDp2T0UYu7mr8aj3NqrQMLKX9iBF2PmUlH5BZSsCQOTf
b5o/KCZ7jy+GgE5fyERSS2D/J1siRifcHwE1kGJLhScahnsKjmGFAHrLtSwlTEUfr0TyjxMgDofN
R2G8ZgDk92b+OptKq6Xqzbq/ifqEscouDt/JNQiz7wtPp4TuyJNQcym3ISbVNqS+RtgTA+zwfekx
l9JQBynnNyQfeHCVUtMjc6gkidOZvLgp4MvLOjRnSSLdX64HhM/PVFPiviCFk/91YIDRMOFb8tV7
oAcwDjW3edAWbkoT3I0KmZji/XpMb4i7vlNn278w9PRHoT2z5mTlTnSL0pckaEUdNygyH5RHOB4+
Ad9ophOozDQyz44cbQmbuEudHRj7cFJa/riwE0cj75A+vNpVqN4n6QMGGWbRJJfmdu0N+6qGA98V
bohE1/r1jF0W523FMDAqGfb+P4ZAtSLpJWSNgAAAAlIBnyFqR/8BKloPy5fXnaYdgACFsaa0VRHX
YWqyj0yIvqVRXsIf9dcKWMaCA/POXJvLHHlq+vVjs4x6frGF2bQbq2DHky38YnuHuve/iKHuOpYx
i/+CWiJSvJ6K/+FbRsf8BS4gos0Bo/y0fn4C/HXfDXhHlZTnrKPj4FsR+jBfwuw578SiJvQFHEg6
oYQvv1fal6OnzGFGa/odS+28THab0MXN6gSreSULF+zJdtJ7Y9uM/c98grSW7SuV7LnZhkp6DSXe
LS6Hras0l55jRRmKfevgPX5U0XyViQAnLVv8akpw7eJkabBu80u/zemYFVQ8Ml+ACs6HGf9h48Qk
g7oQmUdOdxlY/wXZ1prN2VGCHVYgbbxjQ13lPxCoHGs5FW4tZJuAqFWBuJZVgiNx66jePvTBUr0o
TmFL0tvC08SZB1kI15UHoWNTC1Owp/JTz/p1NQlRnmYJicVQfViRzAKugh6QNrcmtg7hRRVltSEc
hUIWwpFudbnZaMX2t8uCi8sDLu4KyNQuUd8R8kKup+oyIRW7m+ogCJn34hDQ07+M47yb2Ek+jjlv
J5hCS2M0W+pdmxC7+vQihRI6S6gmJcoRzkNAxlkwLclgbXt5UKoOaYTUHz1TgNVxJTe3WVcvlK4G
QPUgDBidhGPFObcOhl0WXhf1Hcy3V3SEPY4qbJXupMBnDg3sAe5Ujb09Rmy1cNR+S2PKykqoCKWX
skCFDmfSu8V6VSJCLjWQ6aVyKjJikaGh99NFnW1gxl/Z5jKSf1c513GmvJG6UBpjkYaqQ3ZaWsEA
AAZGQZskSeEKUmUwUsK//jhADhZVGMAbQ4YSMjvJ5JmKEnfFHAMjog4dHVCVbkreb8tz5fx1B6+S
ZPjT66I3xo6Frqp/v/WaAY1gbbNVwVGUIes2b6whCo/Rf/WJGU/a/YDpw1DC/xW1T3jX5FE59DAN
qBi+iIrFM6AQrGlD5BTCgAjTFGdTpdsNoya9Hi8HH3MJshWH8M8Esv4EmG8URkY2VJkvAbzxaoUA
9ErWMXUY2Sh8klmk1O+D56HBnjV6gR49Js94uEv2vfhfH7FwlcrYpCIOQBaKHkqdc38Hi2PXOLd8
9Q67WExHLVddumwpNyA9mI/GET8/TCPwCdl0M91yeWH6I53vFIGSK4mkfPntKEWsD2buoWGfuSZL
XI5F/Rd2fGDR/x9SEb7PXntYwo+Dwm/y6KVa72hLip4xgxBxBfodO1FeDlaVIqot2uQ0LibAypMp
349UtHa0rbGiBJdBQY3rfEZby8XSnZQb4V1447bElyY/7n+kFmb5cQXu2+1PFsuuxrrAqxxhRp+i
QmmvVsO4PCe/LhGDzsTTXRmXYw87HYRbFMIERQLaDDV54m/sWDiL0uoK5+7Mn6W+NZxmVfzwM5+q
5TcNdtImwLmGVer1Bpam7TwWS8+J3YwiU7wZ5gTChBfMiBYohB9sLjnRJHskKoHUtLQzxN5YDHG3
G/5xDr00C7K+VxsuvHvuz/go5sxI4fabdyJjC/BiQPay3YBmM4En+ZHgR2Yfan3zqbq5OshogEyL
zWEG4tBvObl82blLlrdVTdRTo4nZ6SHPbxvmzgRIOixwy1FSchCm9t0XGKUurIrk6GFkWEzj6AW2
d8uMxrlsAUZVBJoD4sMq+dotOb5u0EFe9OPhGLtQRmhPu1mJPT0BjhYDckXcQeYlpU2+M0+OfhwO
YSbWJfTOS3ClIJTLzLLyYz5ujnduHnCuGKdSu/ivjD5IUe7AWnQjoTopdpa0N986efZDv5qRArL+
dpjTnTpnYvHwq7XEBn6aaPxtlXeOwwivxWwDHdtt8SYb3wuOM+yvU4YGrK3kG9ufKp5C20Hor2pg
/qiJPwaSMDbgdfGt+p0VPFAH87kd5GKbB4hbzIt5z5TKOx6phfWfkAhy7amkR4cNCLN6NxzQpJBT
80jfH0qmuPDsgWEUidGyJFA8InKSggLbeIAGHj1DESqzEpv0x/EfDkz6N2slSFaoam2zXW1qRxdW
X8+FqAogju45OkaXbXmY7sn5l+d7k63WoibX3rf3oF9hyhw0scaFT47UiP+NwLFMjDGzyIBqq4fB
pFBTi+PlTPKxtbTq2U44ODDUWrWaSieINBz3uGJZ5KCIEf+mGxLpuzG7LSVqW1mKNW8Zdv6HEKBB
yiFk6sZDc3X8TNEtxIWjWpdFKC0B7hmgb59x6BtYreNtFLyjdkXNL0aKBB4gS+3Hzvy7p+lhz7II
F/w0AVyoud3oPTvbIMNRxfiE1BHL36+2lJI6UUtXLhySH0UmWsp80eK59OVde9BgamWz25dbf0KV
FDthvv+zcR8suLR2bZsKdRL/uFzEcicAwWXbwL8V8HUs1Jx1GuSRQZSZ9DN2WXU4hcNksg8Dw2EX
L/+GLPa22KsfCdfwCZaDXq9W0Ylubvv6JhOiVQ3iL8QlydSQuRTInHITxAhDcUT9UWJ0gqjJI8Zg
iD4kQLR6fQGuTL1FMSyOXuL6ROSFAsSodBeYrp/2zeOUcpdCBPb8Xw07mkWUNsETZ5GI0cfnZvLx
MeXzMJsENzZx/tgrhwSPF0PabL8Vge19cuVnfcCiuDPAqpmp61xgVQhksMuvLHirclZV+2N9QRIx
lZkHeRiNsZXlbMHeZBFkcslQwMQiWlLPREG/pAwJd54V1QXjOlTNsyz4dYxPKtm7jfarlzPnisVu
HWX0/17Ilh4OxwktSzgrH2zZOYgc6OoTyCq5Q6z45mgp+xKElAwGtPwAiRA2fZWuq9RbekX6ZHT2
NLng2FlonLk5dpngHg+yQJXxg4NYKkA3LKD6eCVnA4hpS9zksTLwMVb9HNFaWC6aDSmO+AeuQ+tO
4y2HYyUXjMNI/KeVj7Unr9oL6/45/RMBoXCcigaGzxgTwjakgTwmzwlti5b1zu6GiGn27yObyVXU
Iik57yBxznwkvcYWWQAAAkUBn0NqR/8B231YbwYAHrF+aEKRH3OYv02fKEdRGfdAM8Qkxkdmw5jG
+wXxkeQLVIjvgZw3QF2nq3YVjgMa7wIDRwVm7/oMDkcQ7eVFsT0bOtSa0kS0raR9zdkEd0jx8NmJ
NDCExk3m5pANQtIUO2uIuyS63mv+uyqNX4lcr18EwzD8x6/nQmg9rQHHLraWwiMsVgm0DCHtBihD
K3MlQKSTCMRZVQ6501P8MON0qRumt0TAYrPPFpDpA+u5scT7dxbv2iC8UzkyORSnpUjho0y/pXXe
M8lzgiZ1hN6ZcIaVF7Tslu1iqcd0PcuA+PxWFSRvF1ajH13wvuRj8b92PEGCffJ65Lkr6XstCaP6
VvL9sUbM2w7hXcwR9njCr2xN+Y10TPjKRYNDFTtk3LV2W2My31taNABvP27rDJ4v/JT7eHBheUgi
lcqlqG2/eDdJm0dMleW6+0QrAgEFCF2dSyuEpAUlBv0wMNDTTd4df9pbeHAEydV8sJoVo6ozzGYE
dQJAZ8HcQlADBkJxZNtZQQZpOOivZhIU2THjUWILHgg+ScoP+a7gfQ4GICPFMKoiCxuxInDODerb
S0EllKRLFXGXA13kyFNCxN7SPaYTY3oM/n2iBKpuVstrymHj7rBuECq5M/2+LOclWdgViIbvy1CQ
out5xyUcoQZz27IJqBmNG6PmitKqSVzZyKMl85q++UNK+s/30knEbeCbCqIdhviZE/7lIZnVJb9X
q5vI6OKrdsZQfmpbNhCIcfOwF51BWx0K17l7wQAABiNBm0ZJ4Q6JlMFEwr/+OEAOFlUYwBpXzrGA
7XyqJR4FzJerxnY25Lmqwsp2oDbcke7awnRxr95df6ZJ11KaDtO8Z/8wtFoP648p9HRkgCk07q3b
lWBdZpkWt2x5KDQrWN2liwNx6qLE7mVM5RDhn//DTiY7Fs4dyPGXdwkchGAAnGEjAl4Tv5kHcLAQ
V3Iv2Gp1VDwTQ+ibVX++5ncylkBn6NcILZGXtlr2H/YtIV7COnfYrijMx4RdeR/Muf8AKS/fOZjN
Nk1HpAlDz7nuW8s2eX56CwlpLbSvY6nYtRFaT8lkZDwywoKHLQasdlTLuHlJZDB2j2IYNsITB/Q6
TNyFb3roqox9Ab2RCCS185sy8AipK77GGo1Zo5x2Qnar1rvrjoizQImo7+hX2vgwpIiQnjja9PfA
5dUYTvyVRNb/bf/X6eUbo93+rmYmtNo7uEa9lonK+pl5dbsRiMDcBpxPT7yjJSoJEDwZ0DHrdKGw
LodMmbZ5kX0eR+0Mzid0kD5afEjQBWY2ol5Ccdrp/liDs+yk1sJIf8omyMKAZibQevbBEcnlSjpp
49ImNw3Pg+ETaBeMbBVdfpgulZbgMrQ1QSzHYzL1/f1x/W6EjZ1wmkSOxcs13nOgvcRA/o0jbqqs
ZsCaXYMwLO4xTod9ZgguDysW+QjpEVSSJ5H3wwopO59XoKxx1tdNf4q+peaNF2H8NRZS1aZYLs2V
KJg8ezlwDqGsR1W98Wa23ShXSzLlw8QAZHRriprFI6svVE7j/JSI6ahFyG1O+Rdqv7xpi6AMLPhn
PudDASEgU2dWd46Bl7T5EKWamh+hAOkOYthP8KvbLlneYd1Spj9eCgPknHUB5Nlb6km3rceJ4YSH
8oPvEFoAOf877pJum5UFfJFwG5hF7EQSTB0eJ4ZCzWMXSyjEdqqvCaCT9A/gluaz4AGtpCBlEs0d
21uXJtnMw083CIZIb1L1/T+NdjkHSEoI4kcWRcHGeO0NK0WsdXz4DSge6gYUfqE1F/zenHfCdeso
tPtR17IN1RmCNunYnpUyz/44Dk3iXJa0WRiVA/Sn2Gk7v4DSSbKEYEVOM3U7dpfkGAnlWael7reh
pCmJiMpQILkV9111VZ8inF1Inp5Vr1Se+ZcfiIm/wyOlkCkl9n94QcPyyuOf3JQItelnsBCvqBvL
p1w4yI2xrNVoiCE4Qkr7MBx2GpoVcvhRXpGgQFcqFjLsJhh4zD+hQAqz7VLrdnvyDhPVIu83n6K2
hyKuVFc75vvR5A4jtnNcTcNQhutPWT85Np/E87KJz7GgTjigU6pAnwlFbXg/9pDrh6cGM4Xsm4pC
UvS2oCGhOJ5knvYI7sPu48vCpTDp6/0DQ31vF01adGXq+HDFW4U0tTzjPg3HgxRXjm0pbPZKBndL
z+cpU7j0Hsfol1geGNPrAqzac/EyGFod4wrdbKcB81uy7A1ip2Vts2kfEEkAobQ+f/SXOuasiyNK
B1mYkJeQNd27vlXdx7iQZ+XUARzRJPw4MLNO4+2nQXKCrDjqZi5YUiUaZdjwA+1orNXVVbMT7AHB
JQDrJoOSMH5T4aSnnCWU/g9gB45HlMJDLs0ZQ+UOAa4GkA0F8UiiTtp/HkiYVtvfPoqtJrslLR0C
idSMmhiwBohmc3QbIR0VIlnWJ25HAzJQl2G4rRx8mWGneQl5rVMkIh+xriB+jeLpEuQWLjSNYrbO
0xmZcTIRN/u0lrqjAFPML92RPYrQ3hfkAVG+PXgfAcfk/WluuCFXvEp9dKcFYzE6JhTT3wThrigr
eXNxRVjYnF1a5yKUi5LGDn1mO4SjhdiESEGt3ZXhmZhgXTkwGbRXQePcGB3oaWeDdilT/R38xOj+
pP7z3tQYFrUQZiGzAGJbV973J/3oRTG+/dcmgEXMT6jd7hZM3DkoJNySrUI2xeuPWJKKiBjzoShf
NYMO501T+q13ZBhbwdSksE1dqttACpxwCn8KYOe8tGcRXVCEe5NBTjOsTrmptHGd2bWdAMcTlUbi
LIh5bQqiMS7dhMgOonC6H9njQDqa3P/CtW1Ku+b+XVu1K6Wmo65QaWH6CLIZ3NZcrA/6Q/eqj+H3
ShIkjD5fTQAAAicBn2VqR/8B23oQx3Q88AHwFHI1T9OrT/H/CA731yrAX3islEeo9iQVPh6nIqXr
fIWdjdNW/DK11xL3XR3NFt2yrGFdvcEdBGJQ3AefzACDCEQZlWdCS1VuPsmIqqfIMICKfeqV/R2g
+mulW3f9KE21sCG9yzCbbiOQj1hmRrGJWQ4+PJQNNyxrm+pB5SUT9HekiYR30qSfE6oTVwbveKiT
gKejHRLE2Iofwq9te8Ip42OwW61DPIrrXbd0Xjo8GwnOOA0GwNMHy/b4YO9hhMKIPdYvvR69PXUC
z5DDwdJA3yvrvMzUlVv0Zsb5FVhTWqW22z6rvQ4OIwzVaWOW0Ygs1AbsmzHFoOgOQeQCQZXJf4eB
EhMDp/gYrhbGPBy+dBIBG3zZpA2yOsj7WR6LFZR0ZgKDmQNrgHKYFJLSH0MR/gu6lclUabHg92QN
N+85KzLnMjelaw61YFpzkgrK7SAmDXR8eQjApQFbK0bzYTEq/D1zsQO7SmX/JPNj9YEnP7P3002X
glXqUH8V/7cvSkOBuLUBuPF+9n5JVnLEKIMxTkQYbs3erJwhiFaq5zldVaK31vMDe9fKYyCNniQ9
GyCQMLF6NxyumdWr69Kj0ku2HUQ6rqfwHk47YX+LwJ1YkpR0VPxSijGbaB3eW9UTJiQE6ZOBdT8B
fHwFYSVazAxFVDCvhY+ip5X/YAg2ClOEMtdn9l116zlAduJv2sBrV/OmkwXcZ7uuVQAABSdBm2dJ
4Q8mUwIX//6MsAONFVJyAABm8uPM5Ub5nTkufvF+RyWKdR+i3YjhLZkR50dw1n+OXHCr0RdNdZhB
DQhw6r2jOiY5VpfNsVp0w5wrPFqAP82gyYPwM7nL/SjhrREtoo6ptiBucp6QJFqtgiOncFUboNfY
/bhYK4O2bDR2RuDbz/iq7/M0UexSzwCzSSnsQOtZxLxeridC8bOJ01OEo51IioMRMFYf1tMCUZNk
GcPTuhuXcb+S8yvBtRd5dOG2EUZ+XHYHxuH/cYthy1uKYRQlT3K42LIdumZRjcS0E3ss8Ss9mlPp
FzsKfcZUloSxF8qmw5MOTvkF9JGT7r5q1/szt4/bkqcLFHaReA3Y6FOb1PxeH4qC4HYT+MLnCBR1
CAwuYdIwllHyU0exGjMZUMvSRxh7G3XPsAxvOTDtWKBFBTFYYKCy4PjbjWmMJLunn8aYdyJoaFjM
+JgA2Cip1fFki193VGlvYESQecjKAyurTh3wRV+UZ1sx3lFT6LsrbCrL9XVIegX38N+3qSi/zYoU
7CXKQvZGbjZqJKEZWxqLnZM/PrZQ0Ux6M101JDWaKMnqeRf7OoDf8MmCAY+cOKABj/ryTN8YC2D+
WrojvySYC55ZgSO2oRxExuWHBlLXoKtdQvWiapGBNZumBgKhloVliDNa+kx4D7IbgM6ZqIta78Bl
K6SrdI9JEWWG06OFFWWVtLXjgcrvO1rD3BRXgH4KBUL1zCX5BRtuRXio1NwbCSeHRWiQg1oq40Bq
/QT0uk7E4VWm/zDV9mB3tI1RyPnCxwAiCy0tUq2iJoKEbCb0xkDaWXaQmF42ahuXI6O0fm3CKDPW
xFA2W6BVh7Juw7NNHEyPm4IK0BuzcM1z2HtOuuRa1h2leRfM77HmIUR9Jl0ASWxooY7anMGySPD0
rxpEzK1CYuQNFZx96Daot40pkBogZnpJEkhO3LbygkuP4JSGdCO4GLK0/Sc2mlsejx1x3+UAVyzm
dWcx+ASUQNwguuEVJpNGDvw4d1RyYvZPy2SqR/JOR0s6E8HECvspsM0V6nVdmCmWECFDUKqBNnJa
DpCi6pyoYrj6G5R0Fh6Jve+P4r5jpJQdjKOlqkUwt2VTGoiUIsydB0lfsmIjDmQ4hdR8Ot5962+Z
mZ2xnN3xmKvtIuCxNbPwu+x8zefvh/9VBvAQz6jknfXsceQHg2xp9GNvNZweBYEGHtl5DaYmKtjk
/QZOHdiMgV9FItUsHS7msPG3K4RT/ncWKsRietwscYdskmXBV56jtEdWbh0KxQ815/2Go9UqvUAH
wsb/3L1CKDhVYA4Hb0yzFiDSTqiqCL8jowvSJTzP/FtaGJyMVj2Rls44yIQQPtrhSltea7axyDXy
kAD8MnAoqlUUUWEjA7OhdVQxU2ao+AUX0egSO6wWGkwzLyIqLCioJrNbkrDlNv7DtD/5qCeouug1
kYcBtSeoVE/lR6t/jRnmbo/jJ5NALL+i7wDb3MfbRhw02dCiV/Gs6+KdjCr5u3lNQULGVasiBN8C
WIRXgHLOVkAGZctl4bXsUz3MAdvcSSu2eiW36y1igW13y66p7y1i2DxWRWktPRY0E5doxk+m2xqU
aR2dnffhFxrQf8tAF1ZwzBsbEdUOZfNlxM5dXk82F5K4T4VKmrTBFePqrakd/6141h4A+Mykc7n+
ktATy9weufs2v5T6kf5FDyyrm98/iboaaJSBfBJp89aaCKyjfR8URkxmEuzzo7IIMvXAe4qAFOFZ
HOddYQAABkJBm4lJ4Q8mUwURPC///oywA6QWwABvNrzS76QRO4FPclc3BtmLSm6m4P5HX0+y5Z3a
qpyNlKe4byuOG7R98+iokV/AHhLzzEdNcmSqCw7zasoWVFMOT5STB8scC0QGP6ON+kk+mTA8oz6/
0bOTJrT5YDjcXgFBjSpNtYecnExhUwxUXP8YqWa5B0MpRNKqIHAHktzcX4hBRaJ+DqDtvF175SZq
6H9MEpacVzn1wWoYbIDszYLdouiJNdQp0X9s5UHPx8vwWb/dJFUL+nMaFoz4NoCgi3r8iZbcpLWF
UWbUgtyaNvzY41/IGM+V7Ps0dnVIh4I0YTVlUiqRoEktaf39Wm1qQc6Akf/BzSDBXVuqQVs6+YWX
1ZfISeDhd25JG/ORoGFCrH6X2gFI8sc7Jx4mEBqgGm8mxv8QEpD7XRFo+71OOL+kirZXgUHtepEl
eNQgRbB3ikZxczTb4fobEqq09YatOK5lhFVi2eVkWt668NCIpQzGqMDlqwk4jQFgkC8UlrQtL1ph
/Q2BZbbDWUOaj1YKduJusTlp7BjkAeIRA0hny2jD/RwY3svuFaRLzjKstEZgMYkFf0+298DduryH
lcgBnv5S3tPYfIMAiMKacELPWoqsRIfO3DR6Q/EL/OGzqvdtvhVzyK3dgXzupSEGHn+FXJOPhHLw
ugbEK+lFE/1Pt/diPAED7ut6fdlFct6pXnJww3Vwe+sEWM14XJ4pMHzH4yK+rx4a3Kc0ZV5F3o1W
f8TEENO1z2HsPzreSkLdxJxEGwykMnGUCBbePFU6jaw/A5F74/1PntcRVNfYFYBkjQAsh/niuENa
vHT5byoYVomgLgreA3E+vz1TcNAKkR0zjS5lkDWMAYbxgdPFtZm4MaQIqIUMeuZICZvs8tjJJztr
+oRL72l7pHAITRT5PNSMDL+W1jhTFP/KjgvcKhRuvJ4vpS9ECEjZORDFgq7j5w33XhUTu3A29IXe
ix6VQpML3G1dJSDbcxKGz0zhNb/o7pSziKDeW9NXZXJSD/YAq4Awt8ftHJwvuaK2hU0zaeb/+Gno
QQAVi7KSh6jIeqPqmPb+FKqqUf95q4GUUJATzD1X4F2Y1R9HgxOQThQt/6pj4b2rJuLdc1HeNtUd
oeEEYEhp+AjsasD8vJouAQ5/m9sCob1uAFQZ7xVx3UrTYkYc+dPG/nC4nvA2amjKgGAt98ol5jjh
tUgXZ/d2DqeLJ2Wm0tS43hyDrBgafJ98LAC2THoWBoNQ9hIpV2rEtHB0Q4i+lxeTUeEHL03CKh8y
IcvUA5bbDLFW6omk7n0Hti05I0mR/GK5ZRACWJNxqv1qubdacOvqxy5a6eJbuU94LGvRPKoWm9Ig
XDQmM7iUwE9t4FDfbthgGiUAaSpVMPIR+PGzBPyQGAlxnKR3CfkALuIcy+EIbeRalZVD2Uz+MBcp
DaNT0LJ24T/T6iFPvyB3mB1a5J5nebtbpTRgybh4B5rbxAvkBbMSyKnIocntHAoQqlSaj/7ZnLJ1
EJQT6wt14E0l1/NZ1DH0ZG0GpcpsKYgN0pOEk3DlYQx0sMwbWs0yhPVkyKZyWHIxcBBTWk1amML8
AQdCnHvp5lwi8umbJ8sh6hoZqvltQX74zgKFfPtEuFKcLE7M9GUU4NhSLV+XDWse9SPTCG5KjSA3
UmCdGPNrSdSskBSV8ZY0LpFn/fy+CW8hKO8g5cYWuL9u6LBOBtfdODDRfHpsYhDX+KbJcmDCd2gy
T1dOMCeS2T3VWCGeuBX0fqaR0XIyN9vjP72EfzcjT/3lscR1WO+k6baDJQyjFgCb0gQxsX36AHgn
+SzbKtzaFY7VBr4/fvEoesJhH6u9Crd0B+iuOhpNvjxjBlES3LOyIpWE+ZXyUHFPMucbG6mVQdnY
dDMZOvRF+LOAtrqLrx0z4l0tjWXlaRldi58aquV4EjzYxVUmZ7dd6BS0PiexMsoK405/SY3Qn98j
YCOME6beK4vPy/aXZUKfoFQEIOOJmj6vdHeGMfoLWQGTTjepN4lJZwmewLAyNTojfZUR9cOc7uoI
07bDYDZxaxpP9oLgoqXtDHMDWrsEFQKwT3qOaeqpm1wZyCYOKUPkmA2ZwguntClAyibWinCFQMnC
gV53Kvz/m+4IHTEgKY4AAAJJAZ+oakf/Ac8RxqMAIEZG8pdrBZWdjgdb/oKSzUqq2mNeHQAb/lSl
ylQK8So76e+bjWiA18cg8Hbf1HuRCRl2AfmHzAH5OK89Dw7fPGdA/rsak4mkVGboFKCUVKP1q8C8
f2zlM6Ot/1W1y+8dpUzoxqJNre8gIpIZBxu69aDkPw/yNjEE3EefjHux+mxwuL1iPV+kRV/ICR0J
QMUnAu/bwlO+4gNApP7adUeTLZUyZECPikA42RVWcB1ja+a+AOTcQAl9x84cvxWbJhv2gGXxjf/K
fy/N7B47n6mXeUCPeglfrAwUoSywrUddWLsP7P/WS24kp9qJSNAy7MSziRTCv/55KZ6T6zzMAOnB
lin0i2k9vAoGUPxaxmGpPP9VO9R4pMN/6hOzDLTWobuAgKHtIZDos8Xjl48KoccsX0adezpnii9a
/ctWovCw8biNByr5goaGCmQPaImS5VWlRicKWxs7++CliPWHlmwisWqvMLFjLLkceV9CIO4kZIMq
fJLkMexkZ4Og7ziarN1ckslr8tp++s+IYNp856LHhSp9puo9e8DzNyC9pPkBzO8VhDzKc++QVMOL
mZo4kfU3XudXwie21jjokhJzMmQ84/fah/zC12pTgrhFQicRy8UrlZ3QG6qOm5H9m1Yxb8ovZJOA
h94MRLtmYO4ET48zRHc0ztH3nex5QQ5he/XT7BzIgh8pjw2Ut0R9NF7hn0IFIcqdR8o+szHk+Ejk
5VKnCAD8K26gAY5/QL3Mrn7BX1cibJqEgBG96DLBAPQgAAAHmEGbrEnhDyZTAhf//oywA6QWwABy
wVCii63cjaV8H06rvb5gWJc8KXafxL0KOtqhHdaVtrTjT5EzlazWNv9gx5uxxwoUu7Ix/MkWbW+n
z4DaXGjDMvFcfiL01QJo1kdbdea3FinqVSmZTPwbz4Fuw/bJXAgXsaCjasMiuCl9Ks0a2NpgkmOl
TRaysj+JFc++T4N8liFgDSIR9ekG1/gDokZevcvdoqY78cBAjzUhVpycy8M8PsbTAjmfGXqEVVkw
uWJG82ha0pglvcPbSYVjAGKHwRHWvpY6Ttas7E/rDyOZSAzqiVSMM9dh+twzgKYmEooQYybmV8b/
ACecP+zP9SmpYbybzcYvWRoEob2aEoIGePFqIjTmu5sltFtDioi6nUQFfEI0Y6X7I8mp5/3cTesk
HSj5m3dLl9+maWKzhrrJUWJrjNbaDBBGyjbav6t3fhUGAaSwUCnUTwhhfWVCr/mnn270kAHvSRV7
sgAwtTL570W+7087yJY4RihvJUfoVhhcYl5141bMjxssrVlu6VLXqenK5alccKLOVigC9UTq/guh
ll12pAsBIcrzJqBM6m3Ej/nZWxw5K9L9r8AnU8Pnf1T8slMO4ZpIcs0wqUQilvIbaG1MPzBEpq3N
vDBNuReL0WT8xA+sd56vEgUZUxXQvGEGAi9u4143GYvUvSCiX6r0x1f+e+y7VUy5Nxs4loi+DKex
QzVD89oF18Y+BKAPKynUCeBu/GxA0iqB8nvptZQeQXIdwe4+ttFjh9XQfFXCTZDAg5itEX2fYslc
ktEqMSE3lFOVruTuVsksPN7RLh7s14q2bEz//fzIzbXPrYFOafA2bDG6GVOWoxMRFySR0OQvDahv
dcRxUXbPEnNPs5/XkRSk6sQfpSvceZo//4Z8Bw1c5A3W+6/GnbtzjUiFD9ocJLoPbaFocEhaHTxA
xWoNLXKjkHuCzFiwCUuZ7ft/b9ElR5r4D2IFYqJDVkoF0w5Kwy/tM5sI7GtWVE+35CIL9p3FcMlr
DU9wPSD+wyDRdtf0v/Ua/nuvDOpcG93HS0UQJvm28L4H19go3qPSZmy0DG0KF+JAlFtk5Kz48UeE
HKaqZf+4nEfCayWhy++Yymhnd9/IcSwvVZ1YYiN9e3lFU1jzKB6z7rDtAazC2aDB+Q67jsMXku6g
6QCgIjuvvy1TJ+GK7mCfdtxg5MQclYjy5j96j6JZ6Hk4mAK5WUCtp8Ey/MF8N43s9nsT9O5mMJAo
E8TRzBhAlizfhvs4ZrGA3FZsU1aAMrBi6jMPWTgCNgJ3dSWa3xXpAEUv3rPfrTS2umUiUx0TvvLR
NWaowHxDeoTLX1lpPltj/+yhzeU6/onuzPfMEQ0jaUDOpV7BhebJOQeCWJOFbe4pOblantgTJrZ6
PpNYzxo3FNilZ2qq7igrhlYBzHQDuIfGfFtKQ0toN6VqBKm4FRJUAHmd4holFztZ4XVet07Isndu
Wlnfdxj+gJB136dPvwCUKlfaHVew/R6QnouxDb5W7QOR/dHtgmaqxRxKJgNGMc98unfaVIy770Sd
XIZ38/HJXNq4lgsCpfVHhgr3kajUv9m/bPbdsxrHpXEy3jANaeLKJd+pcDZbmKOoqo+lzfqkE7iR
jw07wzniHX4Z0azfzA7AHILMTBovbVFa0S5XEg8wmDCOJRbGRWYK46vqoHj85DjEhRu72pZTf5DN
sA+rnwwvyhUMWpalA8Tq/xO16PKnTuiyx0HhXos6/s0VbTXIqg/sRqGjDCSE4E5gzCglnWpUSkaz
1SEth/te2wT3pkTicdSSJWyEo94n4guGlwPoF2aovJn/JJmBZx0YIJVkqKCyHPIYbjci9EGPOV+U
pkCkm8YbxicYM0YpBjBR88pKhbvuyaf1/E7iqAqXhCvqMT8rjLMOkttS97RT9t9uJvdO8+6zR+ts
fgVH68CY9SbE1PzANiur621BUY2EEJczX3UgY4Q6SAdshsiL1THLFFPEC1IMf4KvVYnzaNC25c5R
lpi0bSaDGgAe0hYZxmKIPUZw0bbQqbDFTdoy1NdS75snohwCqlVriWquosHOOOgUxb1fuPACXjWR
Szxq4PdpPxbUhDSNrw+sXhTDWOj81asZrHeLXlAffDFWR6EuSGypYwVXr2znp1P8Cp3Ws759ROna
8eOOgA6C5rzhqjLA2cuL3nf/dLrmQ/ManU8VLGy11REHiDSDE2OCJfpOWRWasIaNUZw7bVgVBB0v
cgB6zvykAP7CoybnfBiVqqG2Ocml7Go/HeoF5v3WEYdkZmoYhwgZLrDYMRkDvX5TWrCf0FQgeDlg
dkb5OPb914d0qhGhuCbz/jAodZ7EVjJke5lHuV/oOOOZUehmQ9L77zCaEm1G9asT0BaWE4fNvltA
DK4fjxotOcQzWTvE/0F9IkQmFApwLwHxtYpHlXlmIM0JL0CYH1s2aNLCOm6TmkOte3wJm9Eo+dAl
EhQmKqD8iSKvlbEiWsbpforxMjHsKASMHTD44SmM+6x1rw2SnFJNbfO+1wjK9oooXIZa69PKcqXW
ARDiSHDtXGR8LKT2Kgw3TRbFDHJtTRSV7z35ERZ+ZR+Znt9oWvDQRehKZQAAA0FBn8pFETwj/wEt
449Rl/ABCQFpTNPLMJYaUN/ol8sYSsqwhyS4dUuuPkxxCHrZN1bN/vYSrFnrkdaaDCvjrnTi5lyw
wNvvOsqz4bYv5atRRJcsPHQyYqPOgvae4oHbwqlAHVdLJnskxHucqFas/ZxG8bGQJD7MyX187V8G
9dA/oGeUEFoCsY3rOLvVWURntezojNQxbgccBitgf94b70L6Y5bPItO9EJGM7s1TLmW1v80onny6
j1wnwwgXW6ZK8XMKqP9A35vlk3rIElqZCoGcgWmX2GzftLObczVNgpPCXWs9X1aa3K0/d9DGqzyg
3xOu+c2Iq6n3VQyejMkMH/bZlpdXPJGVTAKKY9AgxamA6MebdmXc2gl3K2nZjfpxFtdXeMKmxjg+
LSAJgXPFah7IxLVr60UCNsnYAmXNzGaGClcHCnbUcQ88KLeax8iqAc5eRcq3o5SmKQ8RaColPSNh
DfJlge8+jLlGVKckQwKzT2ryK+aKlH8zx5dFRcWHIsAAtNXJbopsvvvAuv6GBXlubUrnBJ/6F8pf
6WLhc8tk1mPj1xcUfGnxIrBntXMK+rfM2K8qopV4i++oeCEyw4G+R3TGUrJbgPu4HyZENYCBC+4s
zj0ox05MSgmflDEOMP89NmN8SDKiEvXPQj8Df86FJy9ctEuXVINSjctf23UanYzb4zFEf2v8RZ+K
JFIyLEd6Pcc1vFU6nDOqC+8bsonw7fA1TT5T6jlfp1rxNiv8fbqvwgRzCCmVlxm4joabVQW8nCVr
412S2JdNlyLX4Iv5msBa4qX9Swoz7u3VvyMqogEa9kJj4KiDq7M3sogzp7BXG0+xcbccnVj9NgJp
OJ+IWZJso5MmqM65Mw4l76fqQenMZHj8ETOlI9sJdgt/A5FRNh2ojb6LTyBUeX7yMTKDAZ6v1/n2
Zb942kApvZW7mjPtpAOzbey1GWhY1khUXBo/xWTGXPhT0TD/Ruq2b3PA62BHMNufZUusPGvoSXoZ
LFwp4XkBmDWFxiBc1lnAAZk+sbiQVq8RauOADSjsPLUASBCS/zmNoa53gnDyJYItLTKnHWdOb30q
vDMhuQ6aIcChnzUYZxeVi+Q/CYEGdiAqYAAAAoMBn+tqR/8B2slUPdauG9iOfC3sYAIF55anslJ+
hM8q2DTY+F9Ly4CscnIvKKc/wg2Il4zWJ5sniaOkeTJ/JlDcf8Yig/zBGKjVK5a8HKlmAKJCrq3g
3vn/C6s47wRj8yVDM+4Ym500kE+20M+WsxQn2GBAHbwGF8T0ibT+TKUBlnFhuIcGh2vDHUtvGDAE
M+WUp4MkffUr+nZ8Uu0aXNwxSdDYJDAPnJrKx6mYmRbv2obU0h5FFR0k7kM8DkLCKgmhYrOPnrYq
Cg6tatRPW81LY3S5ralRZgFH+151E9wJbAdkhADpQ5/JLfpIXAirMZxztJ6aUVKCG/QZy99+9pQw
+fQzi41dmu9hciSbi6426lo2WhAOGTwFn/P7F41DxI7VpOri0IJOE2MxssBj5vpMRbrt0Z0Mb+Lj
TlyPRB8ddnc3Mx/9AX0kAe34gbAsP/z/reOx3NaB1zhWpkn8Qjq9ceJTWHlsE5EhtfIF+6BuFWhS
gAQSOajhJwtrrRB+uLmDmnBJT85OqHLWlnuuwNKLuDhvNrBugDlSOxngrEgAqh1O8zzLfdO6GLX+
IEVc2Pqf4QMJBliGf8vkiYWLhHhHo0Fk4zZG/J8a4UkD7nGDcTrmhhDRRws/bSXakgWsrx7RI/gS
94SElwE+Ni6jrPBYLoHgCdvFTuFrlvF84xZGrgx1UjfOzPoYEtIWYvGH7e7gJTj5rCq+UqKNowrA
RrlygGitlSynAq12Z8Z//J2UbIAeVDawEWfqIAdsHWYEEXI5oph98z+WvAoM4yQods8yU7isNAl2
IKrfaVE6lRKNbjK8l4LiNNBN5mE33SssiY+kV6g+7o1W3TZSVLXNvCaMoA1oAAAHDEGb7kmoQWiZ
TBTwv/6MsAOkFsAAjpf3R8bx76xIgsWNVoRMPfo1973NKVTO22IeyG+b7vSO9AS8yuaBn8E683t8
cEA3i/sKbirCzdDYszQnj24dXBFtyclj1HWiQn2LnXcChZRSYLezjP9EMlrRWr7ptwBRN6utXiCU
Mp0AlGAlNQLl0Ulv64TaXUyrWlqvsTDUP/NChAG6FFROpb0qfwI1l19R6MOHohPSLOQe5ZPWDPNk
71NfvTb4EX1ir9WjmBT9yNO/dfHPdjz6IJcVM2BEKcIYhzW2TndSTHdeDxVm014SG5LmBBexVzvc
DjCx7hv/Xd02n1r89RocUdXz8sFdXuiDDeGVRvC0D1wkf4nGtmOP1ul7xjOlV6HHGhXyVIbXrTt0
lgQwCu+l4PRwG7wKQtrMIBEJkx2/lkuAAj2cWsZpyRIzxJIxtziHtjHGyIsV9sd8uIeUXXKvEJHi
OV/2F9DyJwWlYsCdWV0Hfiob05KvjSK6zw6nj/UFIvXoxKTwP5k14Haul171+g04xGzhAEHX5Xiv
b+1AMuEDrBf8/NZFKAnrIArFCbGO4Syq/k3qTsHSVj333KcwM9C0EIlD3ST5PP/gHLCPpLNWxcUW
7zemgYbivs6gcM+oef1937J7DHjeGAJ98IJD1rejWCLe5R/i7kK50ehy3MkAKRR7rQtLMEhz8LNh
wiF9hBedtnKJ/OzUckFcx9caa8EAq9QIPyNdQl6c87tR8bXGdGH6MW+pomqL9DoQSQ3aFqcznXhd
PDc6Giu4B/Vfw6KyTCo2fJI2jznW9pI+3TcDHyC/crM45g2dAqYobRnaSWT7AzFJ5zOu9g7shmuC
oYQtJayYzDDH44d7KtFLDH0ysoEa77MNz8UVf6krDS7yqz0JMjzwu4EKH5vHggh7LvcLiSDrLtA5
XtSLg2NyFPeuBlxOoR4p2QLZh7eqzcMlf16CBxExe8egycdP/cqbRY8w6iIhh+RP6owh+1X5iLni
S6IAkZLEoJG4D7CDHiWMY8aCjTBG0lvSr/fqRgu3bJp4SNg3Ihp02IrXbdDSsP4Fn+pyNltMAPEU
85V333oxpYZaw9eAJ1jnpSgswRJ01QYH+G7IguALOQud/qwBXqXM0Kyo/WDAx9VxhtFJ29Y3z01Y
Hg6IC2iAi02ggjPl3HWaOqPx8ZGzBYjsY1V6EnmBZO7VuWz9lhDaa2EPge/k2Ctlq8Hmuk2O2nfe
OUydZZFks0w0ab8TplOY3av0nklqaHBYdVY50/cMJoJ0S5+eErpoIZ5GkB1mwlFPuNCuRyzHdB9u
ugHeZ6QaytEOY+Oi3LzGxA1FHGzPNm4jyBwEHzlsW5fe05rWd5YeJUsSD2tNQ8u9v+GH7i3Fuaeb
Lv1bL2v0obmkqoNasCA7PrrO8q/qQx5fFpae8wPkp5+5BUyjQrw+rwulIpD+ivluh+uBdM+UMPws
8mljdRfiANBZYwrWmjm/4vAgTm9ttInAFgp5xZz5OH5qV338G57frXPGjW6GBQLt+UUfKh+x5ord
Vtpj5Efh47V+X2sHnx5NMKx/QgO7S/B0G3BA6wHqPNz2pQoDUX6nmQPZZc31d9Md2mGXfZlgcP9d
Cf3rrIZVk5Oht0RE76SRhQBVcYG16yY4c9YlwWJeVz7YDxVGIbh/MJ8gomX5StgNeSQcTIByGb9O
peFUNjFdXtxID/DZK7qeB1pVsz2xTcUtaRAwikXc4JeD/aZJEZI03Qce3yp++IpW+3agYTZdn+Ki
LJbLpUrEEEA442qjuVOf23ObuQUFBTVK/rO28/49uD+YAeTjjFB/7EhBKhXzFxQUEg175/OaSZNi
8N+XEC1WT4R+ykfxc3njgQCkZjyeUNnSaR92TKTC9j49B8SpCf1CEgPTYTkkasf656wJtbr5v7Fo
QG2IUM+QUn6rLpMj7adaSulhzLUl37btiWI8FLJ4TvIkqP7ABH1sdRV8FXhzeNouex7H04eG3stg
4qokaN+E0nE04q67KZJOtya6EI+ASsTiUPz8eRLcY3j67j+NImxiqGpFslciU46OthyAflX94D6q
Hx6z30QD3YfJeDJEHXE6GpSSnc+mECKIQjpws8xXjWi/aQO7q3gh9V86DaGM0G+BMuU6LjUy3VuP
dqKntl/Sd7tluP0JmERKezqQU39oX5zQGWO3MdlSwczUPL+/WZodMs0k1fjiKezNp6oknF+tQIAV
DdPL4/qtwje0IXwpS+ZKCQsPIEXgKLQ+yxJKKVsyqA1zUpx6VN7aLZZCU4RkH3SYeYdAs7mYAc/i
zuU1/d/ojrstQRnmwqDbz0/vLw7pFHdya7egigxcpZlue/Rd567tdFfs6VQIXYJUvsW/chRnZWh0
32Lkhdsh9K9t8vSBuhNKig2sC3S9yw/mb5FrN00AAAJeAZ4Nakf/Ac+agF6ewv5YO//AANqAP8x8
E0TumsvQdyGkEZjWul41gX52iu3cJaB3t4yReeC7Ky2mNP1VsH/sPaUjTHQbDIZ3koRYwz/WBpsa
LVsKYeurqqcudZrJhos5T0xBqxxl9cdGmHgRT8vpzjwTm+wYWVQt4RBKKdpaAttEnfAQvD5KNkdR
zsT69Nz4Skn0UK2+B0LpLrAWvqvb32UdnRyS4vUrQcTPffoEB0PTThEibpC92XB9XkP+Ijx7Aj9e
Jr+Q9ckudf47iRamyVLrfY0HREq5YjrOKg0vvyWlKa8WIKYLYEkyznaLXu82oIwdSum0ju5pKGen
kZOFSVRptMw+skYBRK//F7aP0k+2E5Z/HCabcQKcM31OJMin8/IWNX0OO2lPh7AH6jrqhwV2HdVd
9SMYj/rNXP1ac2g+hsHd1cL6fsQq6MF3M93dSHO41PNRxtpM46fjxtTPCVIlMn5Lb41u0hxDzbA9
uQYsj85DkIpxvEZj+71bpVwHezjBQ+V+JFVpGcqGhfQ68fjZDISGYcivz7GMCBecn/34BB5DmDdP
2/L2bQUUSjxgnQ+SJU6wKpODM6lpSMOXInBGkMANeSkEjKgfhQgFliLYEhRkueRpfh9f5x+fJidu
mzZNHtQaJ7E4roh2j5wvYCy8IH6fMpZINwDSL9LRDiCdLKzmACjh8lYFmEJLOUAgido7Jm024rN5
5GOXgA0mHSfU7DA9iVoSdGwPbXNBF1W8vZyyil7cmR9HoP8c72V/rcuIW/26S/E7nv/eHA4YH+xf
AQKEHBra5HdT/ruhAAAGD0GaEEnhClJlMFLC//6MsAOkFsAAnbtLWd/a5UccrA6TPElMJ7HdXQMp
R6C/85iliA7+Gz5134bbV72CQPcG3iecx0AzILS4TzBpDQmCt7nXiL3WOfh4xm+k8P0uIau70Q/P
s3kmYGlRrKR0Z5O8u7N8VpKFPY0He+egRtJLWw24g093NkL330jlrSaL+oDaw4+VaYDQc7OFUzkE
t2Wwzy/2IekC1ew1mO3rVf2stC7gp8/rZJzCa/43uweGncOMQ2+0ObnIScOJaNOvi4E+uZtrIpZz
tp58FtakVdTwh1Z7OkBT1rwdMO34mb1QDPs8d3IpmXTDlyxT972XiZqygsRFyF9u/KY4lGYmipzc
PHAtM4D0T5dsnGABfmF8Wa9e9Y4hq7WAXTMOBamoJa9vmtnar99Xc7T98uWPE2yqpkLkjKw6LX/Z
TcP9jwSEMlFYvt65tzVgtCgUL9wB98D5oKunP04yTIGeNTNgrAPc3qo0I1FUw1GrSq6FUiDci8aV
wuXEmlC3qd2KdIBebK8eQu4Jrr+bn/dZKB3/yX04I8rM2zJVF/KLkTrdvll6x9jhHLDTJTeSAMjH
HlMxjD9vlhWu8HPE/WVuNjJgv3gV7B50EDtFFedamui+M4EtcJaF8JOXLFanwoV07FOA8lcpdja4
Kx9WsRBicLkJydWMm0PcmiiFBaJ6NLkGfnggkPyOrhNM9XlTAEsg9bVxx/NFH3BoqV15EJLkpBmb
DRczqYaJ6dqbH22ipiJcLDEVqayP/b/LrdXW7d41QlgxNFGAoZuVIK2xhIHR8qwaEJklUfL4/S6F
Sn30L5zDJCjHuDGjCkvTAVdbyGaabFBxE9LAkVqPEn9Ii7AYvE7roLSKYzkgGDlgt/jrRI7aaBm9
U2OtPuwi8IO8mABjt3V/gXJr77Crd2o/OZrUDMoLMdK0JfKear28MFWYQh1nEKWwHq3MildHd1zl
RXswIuqUBdUAeSOOb4ZP0BIgupk3+jMUmBaMjreLF61Yfy6AEqheZO00Jrqk6u6L19GWBrmMN9HW
13NyBn+m7sMg/fAhy9hMO2+0Q8apKljqNQBPIIYnr+tHku1qldply3Mxtkcc7Pw/sXD9Kf31nLZ1
GWQy9nYVDtoFu+qzMSXUeVldCYxJdZIGftWaNqZUYeUkuGhjsdRtXiIQ4J0ycF5DFK+Z6nm3EJOX
5nx21vIDq24Sg5W2sIQ+h5yL48vgwisCyoS7MpBLvNaxVzudIY2WDlGfJ/iko5STdjc6mTT9xVd4
ZwfT6e5cqa5CAUiM8ASao3Y/Mgq3wo+eDdRbLOFnxpC/0lxsvwGaqTEquES5rPpJ76mCOr7bjGDJ
oZ/IIpAlro7fAnuHvKnzAKBQogXLiYr+olZT4whOgd+VkJkmZxWgtO36Xu1NFodkEVWE4MgCEhZZ
HJVC0rUV/oK2eHDYNWrKczfqm55552PbO4ZOdjnzcIgcKHtfZgHOev7Vk95IJPu3c55q9Iqr+tUR
zb0j2YCkCYgckZcLlbZvE6GWenyHwMXevSmDbAeyvQgA/UsCjgVuJxt/ie6fSDXNg2Fo6FXjfphP
cJD0vMiEphjn1PVw34GaYJ0Pal7YGtbjr20g1bNi09k2MM5kasUrVT0bJMfdGVG7YTrDBIFNysMl
dDrn6J12gDA3837MA0H+2R58egUa4k+jL8YzEIKl/a8Ut5tAhibuRjlESjpWlHR00a56Aoglj+9i
UWy1UEhuEUDrBwn/B8Etp+xsPDfxaT/01rWbCI0YoyToRrBQztUrEahlsWGQZF5bq+XrgujmF5EY
m97loqcfO9hPARLB2E7TfPv9fKrPhjNBcadaogScVGeztEY+aMSJgrBtK7PuEYEgzUHkskQeYoTk
SrCKOgyuJOqzkut6pE2NjMVMjbJytdSIQ6lTS1jmN8EBOvJxbpNmOF5/cKSz5G6nfSF+EYjGySI1
FGDIQmLunq/m7JunyO+q8i4XiyKPkRnXCusVl3gjB2giQ00Jf8EVSLv+ctRhd0p3FpfdoeWlSaBs
vft0GQXNwfhjaU57R/DZNnGfXGOcbn/qe5SYuQAAAlABni9qR/8B23ysiTAAJPmrd19OVH7O3r2S
jiMgB9qte9335jBBe5M5eXtgupNF8Fzzj6aKBt4c8JbiyqxTKHHxEk7sP0YXDev/ZiJcCGJTSeSX
XMajf6/VFThsXLVq9AvpVjMvQ7eNPHLvpL8fAh61OF1GtnLJdE9FE8hDQTp9BO4aTjGTXNYACHoB
vhd1SJJUDs74LWrbDIK+4PEPpbHOSUlPBDk9G3Kyr7f0x0tdBwz/+7Iwnm9HKAmHDXPlpUzPk8da
2XE+rKZI4XyOAHfGzniAJ0Oar1CYMsgmxQdWzKp1gdkV13Mb0m1xZYZSy03gEnlPp4DR7ph+JZdr
nyVI3dJAJA1l1FH6qwPkYRmL8qaj1fV8rbIWAfeJtUkNgoC/McDnTcTEpeLE5OFcQukC8llXx3zo
M0gJrVETxPRLsclB02ynmqYcQXd3iFOxs9ZcE46B+lEHoCRNHpTDBzNJB6stqW7J7u0Z5hqfaYYS
H5sXyhZ7PX08DPvOIIYSaHG4WUxNKIxGPchYvwNpIO+FK8NDfsrWteNykRCvJkirPsq7vBhDg0Ea
Er9FQ/5o3mo78UlddElP+Wt+kI9i0+WzS1Il/0Vk3hICY7Qml6lPRsHioxjKi+Y5OB9sGj4UpAle
LdojPes+0PRcyqtC8vIVcWYU40Bbnr80HiXla1qVPu3UltNo1DRtQeNcS3uiu+05cM6dHmveZh+X
iFuIu/iYZp9reQbJzTOBNcqK5F5EJUNa5RS5XHHCbgwMGS+ZjH8t0QveCjjhWQth8kyEQM+AAAAG
QEGaMknhDomUwUTC//6MsAOPcAK/AA28VxIPokA7F++QRNrrwEzV5v2JdYsJ1lXxedH8R6MxinTY
BTBcHr4hfi4N+ZgWvoKV8rakm6NnSxZhx0sarUVUxouvQkZI1Mc59IX7aaWkwUd+ujiY32E7jIkR
N9zxpgu94XlI2jNLiYyj8awIEbGwrbeFV25V6OgTaFibnlsd1RXt1RSyGh3/a9JbXzY/S6UzOTjl
0/CsZothlpXrvBwlstKBwwxxxj/TNyeEs4XeYpk3L+b7x5zceHVL4OeEN9CLCFmZ5Dhh9bNPvcay
dHQDuX34kng0/oPvk4C7znFXaubzgQQcIRYhA08QaoYNeLPm25Aki+DxBWggEwxTliwA4A8bjKf6
n3iDMW48NU9WUaZQ0DnLsxVvwC8QZ8iiy23i9q955wPeXLavkeGtEwgrsCNv6pXhdl12ElImkyvI
f/nIZEGwr1S9l5rSJmdw5frNJEkI9zfLLueWWSDgbXpTv4pC88e5Mr9ze/ku5iOhvHgmtNIPnEgh
wUWos6RDtz6gzA+/u7U6jIbvYOUjRbkLrcUgpKrM00dML9xyzSfineRaphcHoab8cJS4PYryMZxH
KS2K0UfydWTQPL7E/8l35JbSDXvJzV8/J52j/yX5hPtdNTEOIYBiZuQnqzfySxM9uYLn4UpP4qoF
X8R3ipnbxiHP+QaLx6xwqOF4ZlQzwORDA89EoFJKWFZYLPD32VGuCzxHvdxepCS2HVVzKz4O85n7
18B/R9X0cLOMMNOasfFbhH/xYSMi6Qg6nNT1dPdSmAWwGPuiM92Z2+p7Dv0dlnjcWahf81s7/O01
mGEolthDoaSRPBVjC+rtujtyiUeBIEgSSShabE5mclr9h/dZSRyN3jKBRbAVZKXk+6PdFPMmncQj
bxKlltCTQ0qxRONRmy9t5X1XQ2vje3Tn1PktO0/CtmB0QnqhOi0jAGPx4I6/RJX46wtuo2oOLw8U
QxXDxR1+VlzqtxlzQKdSongNLAiMUqrO1YIrNEo9v7uKvWYtdL3imRm1npImUTyTQuSpJAxm1t/t
viKlv6d1A4UqW7l1zj3VRi3IfbzX9f3g9UI1/QKKRSAZLAPR9NcdT7TeiIrbOMAbK5ryj6JGrpbg
DjFGVanajFTEqDsjJA1ZYNI0Gw1eeRgyU3M6Oxb9qqj0J0Fj/0A7hng/ZyOkhHs86W7bj8LNDB4v
K7ViyLMygYQKuGkv8Jxy1fIUTYNLn882H/Yq8/X0ToUFwkOnKzB684uvXdKPVk6YjSLVwzSMAQ9h
AgHb2GiKXVmngJhGV5rlG/aMacdIouKhoTnyfNRhZhVUNHLYQgR8iaHacwLpFV4foJKNy3s6bfTy
4mvKIfiiwRnydmG+71D1nXW9BVVLA8YVKeytOyeTstmNxyEXGf7hamuNuGtyCnGsASG9+PgNz+yP
ph+f4aObMILjAompLbQNr7slsa6AWEDjyX6lAG1TyLojAPaSSe4XwofNIJXiwRICoar22oTjY+R3
7q/nEbuJN3LPpkT2WCq5NOxBcY+BKLiydeC6BSUsrcbkH9XOTdvoBJxQyzGibUAMm5ohfURH6JDG
MMDWWdhxEDqRrKUQhhje0Pq5lQoHmu6/gDMkH5nIx2JvyZTZEzvenB2IOXzz1Tjln7KDb84CBdR+
GpGoGt45LB8rxSW+ELwuNcu54qo/WFZoAsZsAYtXocEApf6Y0xcAWTXIMpqdIILm5gMW7YjQrRXZ
fDcBhGUJaq5/RY57OCrtfM4x15KHI4XELfuhCUHm9PC7Rm2JnjJrfUE+n8l8bvfkHPf8u2JhJkGh
uSW273zIxPNCRTow3xgrsktWv6g9AqX5ZFJl0A1gJYgl1mMYYM86gjGyyK68ciX9sLF8CoLNarM+
I3D5K7VOBCIGLI5UCB72UF4NxHMKxtTg/x5ISSCDhxOoLuQ7B2+Wk0A5zRB5uelzAMswdanCo4cp
er8FW3MAJVXMClnCetRbm4wkLCDhkgdWPuZfaATj8m7mfNwin/YkaKTqjLrvrvfld4FYXxwIo8rv
hGOct4BzlYBpdtbZqHt+dw6OKYpnVInu3Lc31ICgqEi3ZLvUJ6uf6of1mW9ViL0HpAQe6/a6JNBs
cj7170wAAAJLAZ5Rakf/AcogdrP0czrZyng0QAazBK5WfUxCvsJi6CcVRUa0Vn1R/E6DUL6c+cdC
CystIsRc9BnZmni5g2bvn2Tj+3JMLT/yURBKBFklVBmx5Gh49JQenWIe01YK8ezlMmfyxZ8+VTm3
S3R7SfTTx6Ma91eQNSh2BCmlziIAg6AbzTDxsQqPwvJnUyFdv0VcfA6Jfis4PKQMwX4QMZggGbBE
pFjC0opeXhZq7BCZ97S9sZMYg6wvWMAwog37aSyNE9xous+Sf6m1yP82BJjpTDRS9yzj36Ywas3e
d1HdrA590dtLBASY4gdwUfs3LyZOT/BwLTJCa9C+W/wW/xnG94VnOQx2VIdk6zj2Vc/lQcBHAFed
rIuzTcsYaKoaU7AhXY+wQHVp0xmxZ7nN8NFL91WCBHqAhe2uzWL6gnesqxN/Qado9GaFrMX4V6Fr
0etXmaSiJ2t9sFJqalTU2LqepZRCSaoVhdgbcMX95d0mmwVCGetwdvtvu8BL40heYIm0GjtgjO7a
ia3wBU99qL+oJ/IqxfEtfEKsCuvZOgbYql/wRO3zHpiCuab+eM/7m9aUFDddKrDjYdpIbqKcw8ai
VToclu3AmCiIZxAjOR1qmaLdY7Ev/OhWOZ2kxpC/XA3Cc2UtwIuzi7EhKBOMaw7D9ghyel91VYkJ
do6e92aDVe+zxrCrskceFJaSrfeNnw2wmN1rKff1RGzqso/EJWsnZT3/y/p2k6O3jRS4FP7tvEOR
sIGoLJvfiz8HAU01ClAeZi5eDWB9n/yjIIkAAAaFQZpUSeEPJlMFPC///oywA49IE3oAFRQSOq3E
0JUQ2JzfesrhDUPqatd9M5B3DRDAAOkPAq8k6O1kInjjWlvwBh4zzHDk8QJrkbq1BsK6+9KusVIp
PicbQmhy550yg7ilcShA6RZTvSR3jXLODKwTHhLJXQYocFSkTS1S3pQ8H2q9asYvD2Yilnz0OkGr
ss5RmrkgYTZfoHmx7//kxpe5jKkneLGoqvVbw4SVisX4vwc1wzoCJBhG5TdX/wqOIQQ2t1RmloXH
eot/hWXyqr54MekksG5qBysg/op+R94hjM4z3AP+/7zq4AZ6oVzQM0DWVmUHMHJhEE1k24S0GZik
ADPAERiWBNQSXCJk2mCYnAVEyCrmbch6j4IKzqknG0dNpx28mkviTtUK5DDl2TQu+7Vyy7ngdWpQ
4lMxhw18hgGiYJJ/DxIT/ahGHdcWi/hR18HrN+1hHURfb5pCtYJugml1rXJoEe6l+K9oqjEn1YBl
OWbMPwZkxvl+x0pYPz7Ogel3jwWMWxIQCKDM0BPMuLPiTAnfW1v/w4nDBybPymfdA3WyKbnEO+Or
i0lkJZzKJM83DV+LWizIVGdXTsosWoKtB9y0hZlbECb4O+3oQraeSYQmUuPhSazCsV4v/Sk/cFRa
/QcdTx932awIMTnNDVVS3nOjhfR5ucGZytICIIAk/eIEA+UlEp7f+X/VyMSouCF+CzJu/TYsPsQU
GUcIqREmtSPS9NR0GgREYj1AanqoEkHBep42LJhYHolyDZnEnSOf/2CXxKLfdes48yhW5gUOMRoj
XiABNLHuUCkW5mF7VyTU+EDMRsu9mjToI7njdpAnOBviTUfVvRRGyuZDfRWvMIbA6kmLesutmPOL
jal8HNtManMqQmrWUajZa+nj2Jy9mLm6T42nJ5WjnvMRA6xDiqtYGmstcTNvpqjJ7ytV36vMQ+T+
fCeaqeEfFF/qh5O6ygU86eu9yTdO6aPhRecmBsgNg8ZIcQt5tPrzJUveaoeg4JLwdzOMyjFMlqJK
wwzTsV601c294QMBqmyR+J6LhHLhlt94VZX7DBEM80Tl6jk1ZdmWwC4Nt4BQzEjkHUfFqWywMs+Q
VMrODAPtQRsD/aFE3ill/TkNpt6dJZ6XR124yoEXmcbqJYVkDsbzXke4O40jRyExYyVjPCWF/lzg
HAfQv/cHzFm1pl0yit/cYJU8GPNPntaz+T995cTgpUOBD/gCwls83qipK/4Zn5UYVA8jiBj6LtkA
OWoAfq9oX5u1LAKjj8VJx64QUHoTJHa1L1NS2UHE4knzFwNNQRplTNSXjEgdVpMv9XcqFZhJmcKg
XoAYWtMu/K2wfxhMzRM1bLyhZnMf/tgKZFXITMVKmxugvw6tvo9v0MtoQoiP3NgC4TXWlwSzYTu6
F22UaxTI9OenAwrCxEMham+5I2w0Z+7MhB4l58zoB2untB3YlZNNBwb7Xm2VAqCv58bxwNN0eGU5
xSGxQerEVvjsnOf7MG6zTsgU1xPBmWVLHsvsavK6dT1yq70nKzO0h7qVf79ViBpJ0lvY2eQA9sp0
1f1XLolT8P9nLf+4GZ8c33AEMv9QR7S2Lak3qVJ8NM/7D4EfjeNmRQ+ukuMew+5TPlppqyn3uZYk
v4Ye+tSqgyXok6jv45WNUJ00FFU//9sDo2GSh25LERAOetIt+cCoSdy6MdV4dAkqyk4FFJBHytVl
xSQ6Xg2pGSyIHQnBoAd754a1cLNwWl2CMiDmdfIyRRfxx5Ryuhnc4ehhre5XCaIphQckm/4I374v
e7MVb23JutoA4oTqytOhrdA1JOnUBKpFV3HM2IgUflNqNlbbL38p08VYdy36hoV77jB2CmIrGRMA
QWU51V8sefrgvnNtXALMozuOtK2potLuEAKKD4K9SiX7sLtPIMacKEzokDXHq0kff7vDBq/Wbe1p
5c/Gadcx4MUYt68K+Df0wC5GffwIF1i+RsdC4KqQ+cFuIUo948yPr7wdc+aDPTko2nywIxAlikbo
RYiTcdZtw1hes0ZN+Qx11xX+TWXNFjsdxn6GA8h5I33MrSdXFTkScWLQ14pKHRT6flrA9caTNcgR
i1m1Syk2hhKyO2kGuzWMWB+el+WA7Yj+TI/XZ9Vu1WyqOQHjLfRT2K/V06JnePZ9e/pYT1Jpu+Wz
y7pIgTb09GVrGmw55+PkN4smuww5/RZtWnLRcb4nihCrZy+QVeK7LWKlydh0wAAAAk8BnnNqR/8B
xFlvako6JjUawAPjCw5RyRe8Ixkp7g6GzJOTaMYiH/xX8t6/om+Tyze2RZVbI1KmXI2hyeAom6ZV
CcuY5ItiaCihZuyWWAX9PxHeo17E5XLptSkTOGnjujMefzUsWR4uEsjGowfKzFgJRxrMyOf/tyC5
R2kA3hrUyggQ0ktLkpkLBPwoLf3C9WT2B7mWMO0jzhnEQpFQwr7VcFLiE6m5Twt9OpBpgOryFm+7
3hc/l5kVl7GSx9zTHlYJaCINi+21i1z47LvOMsI85tM1lOoTA8WoN9TBBYCqm2TWmOzxWAw4g1tP
EBnEkFJQEuoTSYTSWcAuIfmrCynZWkt0TiuEWXmXmdUpWgqLoAdZfLypgOKmXNyKWH2Zy+yieaFj
re5zk+ZuwOjwIEzSgCCKCMx4T4z13fg5qEHT3dkYcnS8y+NUMVlb18ucuJMrJYPHrA2mugUmiMCn
3fbVEa7BT/WTQVVtsOkjYC8dV6tgVGojGpyMCUJAt6XKmCIb7zpooB50Ihye8s+onWmJ8JnDfeV5
Udt81M6YM8z76+frMtXHmKa5I+rjspaSqUlUwQ3R8YWTJkMoTAwlf68PbWiN0ZrW87cra8pFAR5o
QJsN7ivVf3kEdV11XZ5i07ePb74t/ymdYQslb5SWWE5qzcQeIXrRzU26zqU4Gl2hlw1pZEMAh0GH
Yyg3e2fUD1wYPGv6fCwIENVXSExXg1aWEJdaNvOlyswUSJmTkBl/WIh0wX6z1ADwNX4OP9wLdVnu
sSVMtLsKONopgERwYl4AAAZzQZp2SeEPJlMFPCv//jhADcDnqSVAG1PBsh7qsWgia9+7QyVnT3wu
0UY2z4bQrkXYOjoq8VtfSKLo7lowoV/MPJ6DWoqOYYgeVjSnKjt1nnPA8YCT04DEfZOT9b50+VTC
fnYz7OWnF4IkVFgoXCF0ePUmqiDUrMapWRLIBqP4TDAdOaKzwOvSneUWhFCwTnZU1dI7+BkrMvP8
KNtykbQdZwiNFaNbY/QtNUVjWtVLbAfmKi5cRTs/Fi7A3lIBPI1fGG0ADb3EolcYn6GNRyiWL8+u
lLuJ9VSJYjQ1haXJNGGIOy6mXR2krSft8wHlEAKfg28MnL0OrJMy7ifytoN5j5BSQfrnBAIdSMIH
FxgVxWan4JQ0byO3mKmvt3aNA5e5OJUzaGcKhEV1cxH6UMmCWgoWSCmcbRPYiTtM21f/uILFDRS0
uub+o8TJR/S/UwVitx98TwFzUNOm82lLSq3aCwtW14SkpNjyp3Royl6OLiqslYO3z3aG2rhOcbBy
dWX5kR8Gc0BueVzaI+atKbjW1ZzmMX6wSYkBF+IhP2mdckZbrXtCVq5viZXqC+2goNTaRoPNjHC7
lxvDuiF8ajTUqDawHG+89jSotIg1QomFHB5d+huZ2Qowy4MpiqEVTya2ZOVTDvDnPDjKajetGgBW
NKNdvPz9cAnercm7VMo9yQ5Dc5nL8ji7OOuT3jbi26lAK997+vVmSiTxSQZJGES4aGUZFNRoGbrd
Olu7L/u4siH8GFPG75XQ6e7VutAxKeSCejZROt/Lr/FTJa3DSFj6tVlQOAXnrH0w7pWc0PcJf1Ik
UMzEzC4pCn0mCH3A+6PjELWRC5wLZeJhfKU2HEBjbc1FXIK3ybbjNY4rJDH3PgPMFWKso+cJFVf2
shVkBQHxb+yioMnZXS217IqsEsX3+mvU3VVzQ1jinSdygU6xXv13LhzGFcEjMXXh0GgAHOVOANeI
5SlMg6qG7ZmGak9Gp9w/fGbONAnCkFwhKhCsAf3CzufDHTkudq65zCh41D3KpbSqjK5IvPg/fYip
9ta6XGurY2kzhMQXVEEgQAxMR15IosPnryWW+JpG/XaYyX1FonOYIgg6J3hk/45Ynf7tkU+xsDan
UkNWtNvIW6rPgQU34Sf1RSMsxUL9eWjffl9Erb5gqxNZRJGU5kkV2MoVnrpQJeGJ7e9MWDs844Ba
e8FV2GT6460HbAcnWKGK7M3T5cDejrgS/a6ZJq7GzIbqcTWcAYzOLOgbXQu4I3nsIp+UBAwWWubq
KJG8Go7Q+y+Nj/kQCcDOMHLYBJzkrvGGhWR8J9a4OljjzKF7Ys9Xr90AaPeDkdFQGaVvLtKlpHDh
Gm7noHz4EDHnU8/BMPppj/lpSsK17JHNMaO/MBy+YvEr0dyTXcpQbiLJMlGKo54Li4CnQ9vMZhDR
9jktJc1gDr/ALpMR0SrhZRAGnaN24+sSeZcV43RYqLI97lvdoYeRMws12SGlBuUR4miAlhTyE1Ds
P0d5s+XieKgskdOoDVChSYct2jT7FoWaFdaUjq+dYxov7omhU+2GabiwuEaKcXNrHkt8knzYIoGW
ApmUDGBSoVG13JMe2UsTkejGKnpIwPO7aAp9R3/tB78dJ4FVhn1ZzKM3MEyqwYFDUPhBW6eBeceg
T53w0i8eXSiGtoqnZvVWTfMfAmGEuouYWiyH/qXzmIp1kLNpXzZJwqEpllhanSO8Eliecn0AmshN
2/NTvCIuftsIvg2v7GIK+DN0x+C0skqjXcali6CZO9mPboLcEE0k/P+yqaxivXVsLP+GR179blqL
Q67LZwrWYr6jMATJ2Qj9DEecSnFTcQc4uzmzYCYQCKDfrDy8L5SWrOl9mMPEzGXNVggure0N5pIO
XMPF65pWEMhPHLa4sYPYJGxFQTABVxm8DW9BMfjCal+lkfm6u9WM+UfYMDkIioz12XTvaLlal0aT
+sCmCGMxtk5mEOpywD4heMJBGYxugI4iWzNcgR/1afRAd2pbrVgDaeiuTdX/HP1b+//GGYAcSLu9
qfwefIRkq0+fiJf/m2TzT6/vjO8PP3JfHLLSaqG09IwjM2qo0QzNkmT+zInoIHi9CyZLCZtJmMso
RP0KVTYtu7G3/qVP//iYCo9HwvC3GBFodT423534LjXTD3PmHKkOgAAbJUft8kkYNuutBo9OxF+t
HOfobwb/NQzy1O6mkRERtQAAAlgBnpVqR/8Bz+oNABEHRPiVDxa7VnvKeZklRC2oNiAl1HFRfIuN
9qS2kHFTjrP8CHpjSWGmg53Uhyz2Ndvg7Yx9OqXer/JZSNVGwYYFaZCxFyKdcar/9zyUkG1UiQ2w
UfQzac+wByhbG7s6JPJtPJICTRAZePOZPHVgDcGYTNd/MTUB7G+Io9TsyHPvFwne0kcZNdPqg0jK
MBjNs+ynL+SxLuz1RnytnkPM1c3TQ7uCzxEPNYfR2LUesIMr5kEJRPq50Fw/pUA5isN8y8j70BNy
MeiFrP3cfXMsBDn6xueNHmOSBTRnnuSzVDWXapv6BXFEQk3i9rFfTgiHm2u7s6y5lUZNjek3Mh1L
Ni/sUzeRz9rFTO/BSCI0AclxfIutBz1jJFXS+mmAdH6YWhqqQJPYj4mMnATutHDswVsKboooUXj3
OYx0PhqEBZKVYxGfxz2nP/Y6djjPP49BoGxeQaQWOUALkUq72A0hg6dLpZbO9gzCUncnU8UeFMVh
P+dEHdOJd3JrX9HX5omftIUFyRPoJZtUrMuXznJBn7Owpi6N5Qr2mNpQbJ4u20xn6FReXorcOW0g
eBhphamgqtsqZQoA/AxgPJq2R5rpktUmEHgQ+zUVhOBaDKf27by+yKsXPxnmSLo0O7SeY+KnBI6W
XyYxE4MsEd4WdUaAQYqyP7jheXb+mahy+ZJtxLmmFNkUqiJ5+eexueIBwsmD6KknQP0tIxvAPqV5
8a2OvYv2FomUHi+N8deyCns5Pz4/EDQkqSpFeyUmibpUXLjtqteURShC47k++Cj8B/gAAAbcQZqY
SeEPJlMFPCv//jhADcDm5OVAG35wHvq1W8FdG+9ZHd5GOywwCwaS2dKQAW2ehASxnw49VGQvPXyO
sUCbrsXqAmKbR0Toj4qqv7Dm5tESjmPk/hdCnQVxc83oqwj1xSrB++2psVu1WSopI+MGzIP292dw
azPVLpBjmLb1GiIhRHXU0tVqg8+JzFdtBAd8WwMV/IV/uPczK6aOu3iyoFnvPd3u2q9Rj6cwWWP4
+mhzSQknD6nouju7Vgf2/C0pGSHBmYWgnnaIFuH/jVSpFLzcrSMO/h2FwBwAn2pQcG8k8vNNf6Ww
9QokCvBm1PqH1xwQqHv1XhaO4vvjtq610EW7pindyCB+uzhaMK6uacaBw+nLiUclllyNwCT9pKVl
S3EcjpCuj4pFyHLRVCnNsSnGPFNyrB//9u/kTbBvt20+yYzKCgqlGLEW6mNQBOw6C5cRIlSw84/X
O9VjgOn90IRs93vF0SxhY0RfUejvuYb52t1yrjVA5CTm11fVtEpdjEcql27IVmygJWcSdq4sTb/L
aTAf6kLDd2WL7qeGzsw2OugXjMFxoTBliyR7LvE38B54Tpt+OQShxoZqlncdEx4il/jTu9Ov+Q+r
ZjxpHUx/ZtYxHFEiUliADD6AfTxHFcKOhZm4YHj6wUcAyqpwsECKoTZUjf4J1fmqIJlim8nCYkWy
B+wpSVR2xo6IScaaeBYucD//Q/2VM9o0dETz59pu13XCZK2G2QO/c8rXCRsp5ckQDHDrT5firYBW
iiC/uFDCXWPuSq6gCP9MYiLWfczaV1GhHzzE4oYgbAobMhwIOJv02+xCJz2teEa+mMHS0kLFuG4Y
3WuRdyOYiBWK7GYrdVVXwzLbpqh4ArobBHkBygxJnC6FjRo1oRJnqn8cGRqS9lTWnMka6YihqZWa
zf2JrgYm1HHHzpEdsERGVMZrUNkQPTimttnvJiI3L1yj+c2IoRqeFySEZad0cFHEguPMe63tgdcB
1sYFNnmu1wDKHYXEXSdlo6tzXc9VR2jrj/EhyLU8hv4UgtLEYvQ0yIKtXTbWB3CNaSHH6WTfED0T
PxJCsBmcLOB584NZp65Jyf8jyg07TPYrEhv/UvWbDOGScYnZFAe6HpRA4yIdUnwdfrxoBNVvNjYM
7MPTGolq4ocUKiNWVOSM119kQqEW5yIDKSCrifoEwFoyLLOfhiJoy1LC7z5ihKfczoYI7Yw+yFyo
pffKMzIZk0SyKhLY/I+R9xOq27NoTvDYsN+RwduUSPPRbcnUK2q2XmKf5J0fTkwrpKAcqBytKYms
2A2hRfQdlxxm/jGiHJ5MoBw1Ab0hUFcKmBl9RxV5j8mRkt+SmdmoYVe3APmHLoYD8bC+fsS6nt6I
HaUtY6P+LeTtH6cOJ3sFVO8YjYXzlSdR0D/I1OE9HPsMt3S/pj630Rq3IfDTugf3JATTnhEv4QVU
1BkST93svDXo2pELtKcthE4il2h90S7boXz4d12tCZGPCjv6rqAM2DhLO7DBNY5L17u3lZV3GIs/
BwJGQSZZNc1IhPbj91ySieR6Jqd+A3RfADBrIwhTHFimMf4cxN1IYaN8vMWkmpTHinQwlr/fIe0N
mc4vz72QSISg5qzJiIwgcSiz5yhR82pACZIDgUt0riqJVrfzLDKI5veMGxcf2NXrKyRcsWeqDli+
hkNklTikeZWL7p5sBGQUj9Ra+xJipeu+w12Kdtgwvrj5+VtjfSUNQ2WpnnMEmQTOmZiQJud2qp0Z
tiXrlmDHNoGzHIGPHeattMMurdXIYeiqMKkXSQCnVu1P12O9jLZ5SPBZJS1vgjGpzUh0ia8GOUWk
1F/yLyJ27F1/87It5U/sGkKRZaAvP+kWyfYLNhU0V5ZopvfA685vyShwBe1ogZwDGf8uuUffyy9x
3SSOeAo8fltBjer5AUVdJXNnA82eR2bY1ff0uR/3TVyhBpZb+BCcjBC6kBFifpxdWyzdPd+PuF4Y
5uPl+Q+N85Stb/a7KXQAdydzZ3asI4tooJhkFi3avEFjolCk60RekkBngOi6rvvucnEriQBdcpqB
jpZO3eBfzD3zjSdCC9U5sOU2Y6fcaAauoBXAhtk/x7bGEnJziNKHpNxGrs+HUIkzqt9c0u/4Zjtk
9rJpE3btTB7KQ5jonJOtfkQf1TCmmIzSrZYbBSzGBrs3Vs8A7kUxGoVTtqAc1t5bteIauE/NFX3g
TyhIApkv+PmS2m2oiIq2NlOvydIrq3rlctJxgGzW7hpEx0+TNkyZeEY+bRl/+tlLg+dnbhqGr0+v
e3PvW4NODYWdm1/QbJLDWqf2u08kG5j6S7WhDSlD5B4LCH9dUdeTRPhNuwAAAmsBnrdqR/8Bz88F
Xnd3BTWT8s2IeIe3gBAVOeXjDu0HLqZEYEyMHyclH55MErzcU+47IrcHDs4yJ/hR5vcZybs9NK9T
UqlyegwcowgK+UaDTZGkkPYuBrx3TAlxvc7IO8JJaEVPYX7DefoVuoquHNHV6VfEUkkyUGnnVNxS
cuMC1LWlfSbRO5+us6DDEPoyRJ2JOr5aMYwRkhEz5sduAVm/D5MdnNxDODNymBWthliBGhibiYGL
/PhOjtl/aHbgQSco9tDmqRdPO5d4fiLT7xdnFWPwXMWTAIpduTV9X9VC6pFkzu9Hranw0XNbw3QK
6pWHL15TtCd+znOx3HuX2W91InyHDf5F+Nj4Eef3LXVTYPpfBo65qdYjUJBnzXrWJdMtOoS91lj7
qm7qYU8duwO0t/bjmKl3lNix3d7rkhsFo3TUkijM+K1gs4MkmzuYzXGbKvcibEaXzcuWiD8rjNfB
YyrdgSCuQu16bKDyJX/PnMiDC/y32+bUfCgIGU9RAUvqzO6P4D/3wNSSBT4Oxn4q1Fz3J7P8ZYD0
+1Mo1wGk1Hs8xTEe1id3zr1glUX89vSsEtr1XUEtO2YpOpwHtq1O4LcK6IgWul5bJM5DrQLzglEp
RRT4p5vkvBixQiPrvyHxOMIpJjUanOPN9HcAazAYqgAV8eAn0fOZWY6uKvXMqPBIPy8YWyPH/ydQ
XhEhWWt36aNlpLmoLP/0ktBsAnn9N8bnBL+vg/cEIz01/lZS8VWJf/+QmXF9h6vi9VtRQz7z8cMd
SlQxS9VOjCVEJ6gmxZSiwmTJW7Fi92766PsSTpk24dfkhZLUwhmnAAAF5UGauknhDyZTBTwr//44
QAip9WbFHYv/KbpTACsQex1YW39/CR4HsaiFUtgdjNItaNNPjoSKTo3VsfN95Ztt5VaPXsEPDxuQ
WMOnQHJnzeeyhaK213BFdfvCzast1D5H7eIxvDuz0s1jB/BiTq4mXvnK2h5G0C1OXqtq3JRsLtrO
zqT/baI3Bn+z9gQEC+piRF1JljMsVLV+Ib8Ne6E1iWRZ08q1skw6iyO7H9QEVekEWuFAXofbTkgn
nsuKmNB5a0H3wPuGbD3uDA0+x9HghsUnLhK61IjtP6EfaR7lOzsYpfGQv00E8UvkeRzrHtGU1wEf
SL09kvgCzHZDBSBRW8lLtbqDaP2sCgFWLhVmF/u3jDTBfgvR/BkOyjkMCzS5uvYuwrA8wDWg7nR6
8O9u/bUaCsYl3Tk1NPYQLHZBjNwVV/oHgGVlsMfW9ntPr6tvFvaAhF0kuY9Am6tnAtRBEMYS1DQL
wDEUH5UspsCCY2917eXmGxxiXgNEaPGUQW1WXwt+iiLUEf0l8tuTZfqqKQ8qqSsOf2bJB70W8fJ2
b7TDBxM2sbZSPaKiwVyIMZ45AhJa89poJeF8Z3WTYpHdJSCE3H0nRpbL2nKzfi3zFhbQwb6Ps2y6
tEAqqS4smb6aOMlA2rqsJ6557VDOvQ4/SNnlqEE5LCqJ83ai+PeT0EKSrfYzFwo6logR6YKACecK
Cucp3+5Uha1ichhPBX6Ir7NQgrriR7uMzkiBEEcsj5X/dZJQXgJ2PkgvpfRP6apZ/FOmt9/lIz+J
wOc8KOd0EvUAMaRpeQzoA3OpmxcZp+u8re4HBqkuJXEGpXOlhaeUx99IwF0a4aad+032f+k1uht8
EeJZOR+vtC0k2Ej0lKtqYQX9A2elsJwu8KMBwvgCYvMCqAJdz+j9DurFMQS1nNRiiMb16CGGWnTg
GL29aIk0X90CuCoV9qTNCyUwG9pw2z7OCsOiRYRkaY0puplKrnvILqhTNxiKP6ewfJlzG3aGIRb0
hcVUpFBGrrOg//a14/ksI4FQx7Cxwyh3UyhQvLL66gGAci4lQdgbjesU7Wdyb38Tv8lZi2Cl7+XB
BUv08Z7fSa63WETeSN7L7VJqWyND+xZt50cZut1bSkkU/1WLjhXbCvYvgqFScgUJjladyqyW9nYa
Hx+v5loFasSaGhnUbSKaKsOkaweMmB8nj68XC4J13buIC7sRW6erCZSbpwaJOQP5ULFUPYlvkjmQ
7ecmZU3fB3VaBzRlOWFuXul8XxKWqp52kiPoCEeek6LmJWiY/5ekEN7lx7Ygk96xMMWc1Eyk3Fg7
z3pqDyg5b+lLzWtx0GHUER21dfopRWuGb039EvXuXfX45IWua6cwKGkM8vtk8BoHMIrQNRPQzL7a
nyY70FpFDUz6uSbBUglGCu+WFW9MpWwVUEDn6fvUTpUv9Pg+3bUwLuFp/2LL2AUJNpPnw5ZkqXAj
pMz8DOKNlDBcRM8r1iTZ4aqm38Gxy0pGNskCLTKsuj1ZQ8/5pJN1KmFnRzneRC5RIYCJYSQbHCpM
KoWUM1S706F678TnPiuD26OgSWMnjWpZo9xZpInSarBWy2yWGHzp7HAeDquTonUwEn3SXFwiW902
iKIJ3itsKE6o5a0FLbjZHxVEDUbPnpp/wAqP0Hsm9PC4ORo2niM8w0eS7HSfLOqk79wLq4RDjr9O
rFom9LXvl3HqA+Ha94KKq6VZlm2UXvcb5bEEkK/HV6trCQ7mC4BSQVxoTRNKcTMkqKJrAYgOJmJP
mAAX9w52rmwMdMP8eadSUSU+jRDaVKilozeyqjLMZoiK6Sc7rdfpU2iJ9CMELK5k1zsxtiPQYmR9
lAukCFKrQKBb4h4gEKNK/XuoYW71wHeiYqc2J0JVQ+GdpuayR6JMel3FSebCsaVaypmgirnGHBye
KkC8QyGMumDeGhE5DKHe8uDGiX30t53GkdqmUUzxDRdkJ62Y+IWJqq5jRp09q5GEieXKknKeca7W
DyM+8M+CtV/Bk3rWCQAAAiwBntlqR/8BHRtbY6xkIlqsAAz8zhbICyst07fZ38dL72WBbqJ343rd
Gc9ghT/9pOsykFY5+T/bJnv8GKT2Ln7Jl6ymF7KR0pfxLsefuY44Nx8z+pafFH01r7KLMldu49+M
ndeU+Z+aOMPbcnB/glBN+YY1Ax39E1ow5yXSh1XF65FydxuQlZgOpWkA7ErxV+ue3+oCDI5XEnnx
yZwDGYN9Y/svK02b5lJ9cgRYmfTjhCkaJtAi4kgGt4hFw92HONGStjAv7eOgUkFEpdCgP5k2vnHz
vR2Sv+y+sw92z01UDycIjal0Sy+hT/6dDwTLB8Co9kvQmkic8fH6IKOuHw6jrtrG5gWmrxx5b+oa
WbxmiWECoz0rN00ruQUxARYjZUwD5BsY7IA4aCZRL3iLj20nQ/yslXha6wDpkiqQ8/VgXb85RDef
cgJiz/3HQJgBgJsEr0Y7lWQOSV6nbAhaSTCKfL7WVsNsvR2gmr2TdmT1TD2/vIUr5QgRJTpma1QT
4wtAfkJwyMKEaTumg1+kxSnqLquhQYHZwrOkPpDsIFgLVyJg6Dv1PLdb0jA1StZOVSJYG9CtbS1U
PmywCRLsb4PU2ve91SeERSxLNFbkSXVhrOLurMZlK0ITfzGudbnWI06sPhGEwlPXKvjSmAz+Wl6F
tte64P+F1CAOm4k+PGi7+6bXEZqWvNDz2LDI9fV+JaPYXNwqT7a+qH+hq1L4vC6kEVRg+gSDGTm7
QZmBAAAFLkGa3EnhDyZTBTwr//44QAhl8oTUFF2ThJgEfK29NfiO8uOPXDOvKuR/Sph3qcSpkz6z
p8HfAFIn4xhnGM/XVfvgnWKqOYhUOc+q8xOtbbMvITY3fdQ+vqzH7A6srZQ7mu1aTqjdQUT3FORX
PXFg/AcnszzLYzEPeV3xFq9tpIBbQEkws2PP6ITk4Jla/DothCWlpobczeFsGBfsBoBNMlMoeOyO
99zeumwNf/BaO0LLJn/1Ri5oF+CVOaeK3Z6JVwuP0DnxvEgj7iLGqu4b2qCYU2JA2GHKnNSIFQd4
rnA8Ok9DOWCL0hiBsI51tyjVC07ugdRT3wbOe8OcQTmiu0rKntowUqzK34V6bN2Z4/14XYvc4Yp0
AK3MwVdY9JxNwLXfhBPVvzmlXA+E2oelOydxO+SmW/21rd5+/XzNlbmAPLgAPFu3/mkRK729iy3z
4fBglcbKGfDIbjk8vzCh8mvbiiKsF6Tu7uO65lJX55PFrE8loKKGG4WI2SFwxlvicx5l5MZ/cWp6
/MWfmP7kIKtdJgQEj7S1JkkeVvEX6U9qZeq2AyypGRQVrFh9XB6bnWIuhAXhqPH2m2NEQJEsgYbd
U/zIygB0GLTHN1X5+41Ta8aEl4E9yKDJbXANd0Yruxrjf//hqP5gqc0ya7mKrZ2xgitXPnCb+ucA
PeDXgnc6a7MMAb72MVMQghpLqowJPZiM3lQ9fv8jd8xabwfPnkXM7/9UlTFyX0Lmy1/CBli4kioM
YwcR8ZxZ55j4a87VqzoN/d9MMnlSCusWUXZTOmT+voLojmO93/xjukoIXI94/Oa1RTczXEEynRgg
Cr4HIyjGs1Udav/gZJYONrSuvlxFiBrpxAMc68h8FZfFV6KXzRslMKVCVD9JTN85CDKdssHhYroE
Hk1JLAYd1t/LTq3PyOS604xhr4Twv76/7ECtKNYDey5KizsBUgCjKMf2P0HjgV8y1SkReBcJuDgd
cdDg4soi3yYe/7olge++mprU4iZmUCNmgJ3KkfZ5u6Zb9N9dIrwR8SuzdCu0co9zfafhGNJ0yYjO
VKRlfqpMBPDzGpeCtgFmDPQ5Co5rYCM3Esj2GTiH8dZ2L7+3ELa4io4H/y/cxLUozDlxJKIIQOI5
w9NxYS1ZlZ0j7DLmStFzk6HPBX8+nH72VwXbp/YT8DbKHeAZlb6EMexafNEOdUNbMuJ8vVcqrmw7
BQuuZUA6K7u/UN1BLW6zO583DRdK491b2Mf0YVWgGetKbmMGYqx30P2RSrPH78IO4OUDfhX6C6bt
CcWEcG7nlWugbQmY8W2SNGGzL0dsQCVYA4VdvAe0nIRbDv/u/SODZhz9V4rboIQMQKx3z/seVudt
eP2DmrrukQ/IdH4lI25bYwHdQjsfFMgcxk0ln+6fv46EwS/FTEqEjitpmwMnqlZmfpEVHwXQHRQK
r+HKqX+Jcef4NpzD9j9LIO762zipl97EPB0XahJJ+UHTfXajNo7VmzrV0WUOmlmP//JJWy3uvgDE
bnJattccpr767yXfByWyc7xy+nclaaFf3/aZeQcZPefnJLd7eLbzfm851NSkR6+HHdGAw3Y6tij9
9wxquJLxLRD0yTF45HHqG6t1hK64kMNXJlbmirR0V+WBQXheepGXk77pJgmwBQ2oB9P0HSW0v/l6
L5W77cwx6imsg5UJ34kxhqO64XpewItM3zUhTsUwTGQKjkOWtnevBdKmbkZT7+kFN4Ov20E/Fra3
UT2/ki2Yf9yDFmQBPcID6nrHEFVI8AAAAdsBnvtqR/8BHOVgNzyLDI6b8AAhslbTiGwtmtT9TUxF
XuvuIUGmXuHfMzZKlTS1g0RRUMxvvkqKBKmXxCMe6sBHe/9hxSL82xVeI6JcYXFaIsDhcch5LY89
DhdARqfXHIRBi5gnqELeBD3vAZkoI+Q80xOfPiIjU0leWhginRo2OVUtocCKDaHPezVSBro1xaEl
dVPQOTt+EFkGVoq9ewNktNgWN8jl1217QbFwO25b2WjgFsC8Rpf4dTGZzpEjagfsZZ5pMaEcFVzK
ayQn5QxPAPdy3HqSF/tdzStXyvuujBDJ1OM2UrvjbEbgvDPjEacoO1e6fHznjFyeqMaOV1UK/9CI
9hK/i/yOYfUJ+Rt7HC0U+3Ob/UJ+IurI4YsFqe3ezNBSOpuob9Vfw1zK3HUKlxnDIT54D+YTFMBH
GjqPURt+o/B4414wsItcE2wDBdVyBkGmaQfDyxc/pX+FkYX0/Nra/9cfCBHh7CpfDm0LFkLsEnnI
fpWGZYeYy5Pnn/DMCC2a1qh5R0NdvxLarA5mBo6Jg8Pc9DJPxNZ0dM3i+9WPcjdcTEf+DsBxBVbc
+zcJ1tcGD40oiEhAuRe7jRkE9440rPgmBOUnw93VMeZxcu6C1uO7Xa4jry0hAAAEVUGa/UnhDyZT
Ahf//oywAi/Or3gUCbAIghM2VyCJ8lZR636l6asDMlDvE/EGntzNbvBM1tHkcmzjE1ziV94EHrUp
Eeq00WU2L091f13JW1cBICFVrJoz/axuysf/l41JKy6Zu2Q5j9Oiz77QJBxRCtD13odJow6Fjcm5
3Ob3FC45JPukw7YdpbtSfgTh3f7KoUC0mOtCxTdRVpdiK6CuHyNVcHmHqANFHx++J0TSwrMGOTwx
0LiYxqvb/R8KJtWzJYpPvhVpI0RwYdNqiM6bjL9oDyzYZCA803NMYjq8Grh7zzfL+Y4gIRPwub4y
IxAYUTpm4iEz0Q9AiLZOR3sWgML1B+TBnt0z/Dp9BhjTf3EFw+2Hek8GPvt+Jloru4Lz1ZSoOu9F
D+asP9p8eHHoA1rl0opdL0YC0jmUQqE/fYWuNo9TGYI9ZnhhQrIMM8Dhh/yPyAMm6pZS94I6YmdW
X5MNkaI7de2VkYqxy+cKpi3yX62Xkh491FClT/Gv2Pl/+JBY64Zrnk5gCRnLnfFkmOojb8p4BbWu
UA7jJVMhvdcdurHDhoyOt7Bxp6lJ3jR061pjMauMdfOWXTUcPlmgBqoXM8RNclXCbR1+YfeMGQYp
liZdI7D0MnkT3RcATj2/2/GruvD7+ndGuHE527pVCbfEJZpwh5yvCDTiMw89ZiDBq6Hx/IClSK/D
bv3cXoeb3j0qgzRRgRFUY1QuhKqK6E3zSa4DiD/XD5bp624htO1SBB2afm1i3Ps+y5RrhMH6nhB7
pKfm6mlNm8b7aMJ4rLjeIXBJQNd0HHVdTpoiuiDslB5Vla25vUVRdVRsDc6xWOG1bwr+TPsJtPW1
OyYCeaw183yeFXKQzqTRZCgQZJV0L2WGg4Sz2vEh+hxsnIBTSacgceKhnanR3ZAQrNsNIi9Jsvcl
GOsCkZ29yu7/iL2C4Soph4SP01C3OZ7Vk2Fu2hNLuib6VsNnYKxz5TZiEeB/rnSFr2HuFoivkoLk
6qf5mo+3eet4iQf8yHXwCfjcMmPT2lojVXzPjtozp03vlw6gfLhnrA+TX0zS17Bi5mBT4FMkCxfM
sDJYshqCyPUkWxg9uFG2uQQoMIvFIMcUgUU8QVi30p9qlK79S9dH9W+QaorJltocsP4XM7ZAJbLA
LHeapunl5l+X9oTiBKxgE95CcE/mk9ZWS/K51HFeqOXW1f2sfjaYrUpZLVZWrIfpVBBIW9G8QZUm
FRSu08ocLDmHT9yrtGfoJtIh5km8o6RIfKs5zDAsCX6Yt474DTCzVN7+UJyIHTL6R0xq5ZvhPbdn
dYBTsJjeeQ9Wz2nW9SmZS0VNseLonqq4nZSu0Gy3HNf5qcTbFoNTyiKJMbUcRd2OV6mI7XjURMWF
2X57uLxPW0A4AhU5XPqWyC/S34BHWqx+Rvm90yMobo1QCL/DX4oeYyTS127G7+uxrixt7Jb1FJ1H
oFDZ2KPKKqqAiSTmC6zQt4T5AAAFdUGbH0nhDyZTBRE8L//+jLACMD/bAJpRFN7wFfmPyyzCBkKi
wrD5XofOU2+qjc5/5l4Ail0VIiTJHcw227iKgcUOktqsVKyi8/Tm/45IGUJcR+4om2c6yKLeVhRW
7zfRClfwqJbAF0zyQsHsUb+P2bC434nqDACqGlRbicEtE7r4+TWpizUkH0L2Ji+pae3DsOxsE1X9
4C7nv6uLRLUF5Xht4fk/zE6Jdu3vXWTMxlDHCX9I18gMdXjGsDyC7i5GxSTPNmeJSNCCu44e0rbc
cTP67vg58dXbbqU4H4QnBNHo6wcfIF552f+oMz4tZvjMT6VaXZYwKLYvFe8jq3NOw8OoD0WLr337
Jd+kO/9MCi6fpcV+K27192qNn2+ymQb+lLJkcFtvYtlh9RcbhseN3cC/WjMcOB2DPaIf3+rFb9fE
oewIbsnft/7DidwC5ZX6aQZx4bolJ0pnr9oIb6KRDQ9vSO9ryFLwqE5abbhQExzJclU3SsWGKnre
d+xhq/IPss/Cql6jljqC1Q3gn5z7P9sfRifCgVOPWDx4r/hXzpf8OGZM+jk4ptD5VybXuN2oGyZp
VYfRElWJBfP0CXLotgbIMrVuMHqL+kNLASv9jUVcPTuZxubhKAWDQHOVmhq5md/8UVTNYGBpoF4J
yotv3/DTSH0iCvMJysABgZ4PpRVb4Tc+aq1ENJrrQejoUE4qBHjYM2KJLUst3ZtpTfELL/MmsFbe
d9sZpmQ09Nlups0xmkIOtzF13DKLlgU1NtDHFYBGYkFJk66ArdugogHgpJRn6HwvCpFTICUHDMLL
fDfPXI9vnOFvebHuVFZFAGNhGFpKUMFWA9puWQVE7yp6AkQ82jTB7MzHdXfP9C/nCsenJdti+iBJ
YO9Tz5KAcTCA0taIeB0ne2PJc0hINfy2p8KVsvUySJz3o2zQMNpIyG14lOUkjX/iA9w0DrQ5tC3c
MjC2kHFxZ79LIxX0G2QLcWxO5cD/zwOh38xUbQOY4zNQwNmkHJGM6rsHsZCuPLnB5qY278qgHAv6
QtreJLSmrpbZQmb2paw3dvPLjhwQz7VPgkw3sHMDu0ZyJ1QQkWoLm+bVS4VdZIdKuvMXOCAO+9Ml
GxKhnd3S3l+PRuvFdN9Bz5e6XLeRgrlFDvtXHRx5kRgZy+3BknRR9trifGqgwJOpu4xqLwbM0sOx
++BC9WZfIRcbHfgIJuAEiLtrRhIY2jk149cR93zCHhl2wlwvnBmtzhwJZjHXm1avrynMZHQ92fn2
6T7SNed959Vtv4s/p3XppsjKh5TWdP16Amtz7HHuF4eI/KUDOQ3YlksU1qR++CJNVwIUrSKp8kmo
ZR/WH19Yi6/yQgoyFbX2L/2nv4Uo18kKGq/aHDzR6NP+TPRc1t8KxuDnjeTmxZBrvwMPU0+zEc/z
cubabXtpmZn4gARRtZZjcsezrrerB6SXvEqi6kjZPV6g65Wpna+c0YQ579VBr0+g3RB6uKKBsbWD
jHnEGg26WRvl/YTLDNnKEo2fqID94sblccY1A7k7pBxAB+ldp8QkFYfVyPrcTJWHFjrahwuKsVgq
iRtE7597nHVKdx5rrXNiMiTepvRniXM0NG0uTkfosEjBc9aCWOgIgCnX474kGXZ/I3FzAfzFbt5w
DGdEKvVlDbqrG6WC7Kz5+5HERIEn/UKURkITyMzQa0GxPOlRieOdclDplh5Zlf3ZyMUAXGIk2kvX
aibA79kNeQhaj5Zaw4hY7qdyssc8L9O7BekElatQ14H3wtH7q/SaWe4eYxKYjA29gUMLaFChl6j1
mrL75MvSYqMLP1CnNv0LeMYOampJwEsVm+bh4n0ySBsbj+/UX8/jWsNGwK4qoZqwyiz0AAACLQGf
PmpH/wEdoBUAE1MtLaReuU2DWINcn7x3K/LIcRE66svPbQled1QdwmOqUhjk6Mqp5WG0S0WnbjfV
v9b6Et2+k4uK+ys878ALMn2PkBKAmVGYWjxUZjEk385qw7v44aq5ar9xou/FdR8YAf6Mi2SZqw0M
mKeUPaEQGRnWR7pvWeoKyvXvAD/vn7oosXE+9Dw4wSjKsOl/8gF9gxcRwprWIJlKk0TQZDad680A
4E3xQHKfMetJUqavjKAYSMGAJL9igKTbsquu5TZ1YlBdyvoUEOZoPOyUYWg6oh4gws/MI1/AlhBY
tgnxG1O47C4qL9m8EJcqclKBCLZbw5/OKrl4dGNuiiA/2I/k3W/ynsdB7PIvo5mAXecyqWGbPgj8
Yw3+L5xYnydz+S1T62BZwcOhzHiiDc84UCVV70V2FJibRxSCOuhm0l2w6ciFO9WfONOqLqFlp9ac
gnqNQf0VJMsDV6gSh1m6t34gvj+5yIry16d/dq+lLP8+9kL1lPxqG5PldZOP2N59skMd1QmCInas
ggomyE5gJivxdrC/kGsDwoKKa+krzgVC8C81oBFi9Bz0RW16us7kaFvFDE3qNsS8n++YUTvgWNX/
M7Lkf55Gyxkb5WUhGJImQf2wmLONLOdYidN4TySqREcAcaWkRJ1rAedcGnk351wGJ350+Wj+bi1e
wfIgGGCY2DIgZlCw7LjtBtpjxXr2KqlOw4vHl4ZdXfoI+Ad9SEh8vFuAAAAGs0GbIUnhDyZTBTwv
//6MsAJBXr+YATGtQbsVdLexpWV9oXFzweakILLRv10lKDFeqUvDIiiUp5k+BgnFvq3TJsKr24IM
Z23yCSX26yFegR3A+vE/rFnCCeQPhVH57rUZ9Q+Y3m7mI+b8+0G5yBCVnAkyscS3+/yYZakBpCDC
exFjSIjEvzcLIOAMcIYQiWm1G1R1xLjOqF0WWA061TIpHyFr+eXqq8VlpCZ8xv5uLx+iQtXhWaa/
5535sNdj1Li92Zo0WdwILcQw8qL13XkW/gHSckJZO7Enru7ZvJs6zOXBEtdZpPSbZGur5nGAj/Rr
3QgXAdw5HVmaY0+LBhUXSLL5KjaqwfKaLr6+nOXrCXFavb8KSIQkAm3x1oyezJTeC8mdPczrTW6v
YPmqOx8IAqeNin6787tY1PbKwRymOokk5vXOas+foFgGUCLm3ZSwPSC9WeBuGcoALoi9KxILN+uG
fJ6nPdFSfc01toeIbyykOL1ukA87cGE9n+R1CyRAzE6nww94Z0TUwx8wDiLf5hh6+0ivKr26AZGd
w1PU8Fog1vwvP01k+zkHLaOD8K1UJvZ/MG7EBY1207w1Yuk0e8zs0U4ei9J6DSPQetfbziGICx4E
TiymlzJgLDY3AFgOhWyy/702ssHVyovZ5NqW8/ZBjSeRrwWmHS8zkpeyuJgnhsk0pI8gfFzrpMDZ
W7yHR+HrwFaD9YVx8qEKNYdDPwhXRj6ZEHKGofek10TTncTApyMW/OEL7M2EfZR70YaZvObbnL3W
07DuZU04FnHyOALkW4dwbDAlEMoXjXqlP9/nrb3lIMBoAAcVtNtzpt3yzMI9C0xDKzFU357zpTHa
2YPfc+fDA5X1p4CJF9iZ8CCrRXp7Un+fsBFKtCWrGZdJth6v3IavB4Jw8jJym+cUtL3XhC5OiFHG
LhGAYO2mVqrfKsqbhmV2/lPuUmIYTrWVeOSvLMbWGekYOAVueM7hoTFXiZ0euBAnTiEWJbGloo33
5KqRYeIYyCY6lzifPaC/E+v/BrTuFHqz0J5tUbJn4luc5kY/ce2j93sZuZA+S7PkPR3xFf+VEYG3
ypKqAWZY9rKPbm7ZIjFtCNUlP10aN4hs9KIP5rcMQrhETpZfNaiAcramwC1nDEpj6vnU765GVzwU
dmxiYa9qxVNuZSVtZOQP8La/e4bEdGxdXuBCNRq02rFNQjO3mvtdMfjaY9QgFtvhT920EPxrCmN3
Fb74agDt218lZFgkNKULEiX5LtJNYmpn4XNfIHAAKrN/vpAstYnIvH/qSxzEDwa0drgfWQTDi3Hj
8c+Ysx0ahSanPu4D71AgR+MTuu2WpFJU4qHS50mW9jag84frr2t5spVfFuzewQvWAnVmcdaJDUfS
K9uegkTmpB88j/+GBfnOzxGAy+9bhedYXczx8jodMKsyT86BZ9YLQC+FKXFa+lYjcI5UGemzGLzd
KvjjVTSin91pNvk68UfUto8fKSf6h/COH50KmZaIlze+0DPBywV+Hhmifciu4vhFnRj0GStw1qyh
5mQLVBSl69KCY5PfBNTufV9amqvW1iFEfFZlbDUWr9VVmM4holBQYwLFk66V97Z4wqF4nIvuhWiO
ev6VBLmBgdUENDfE2N1bP+8EJ5GpRCXgMqaADmIOfvvFnU+2gQe2/vUJdlULwhBmnoDip4Gta8wh
dCUJx2Bkeu9T/GqxxvjrM3xy1SdDRlyRfS2tC+ff8qA5NApqEt4rutrnq+eSXfLoFmRnhas8viBk
wfmFz3/MO3tuRZAyXb36068xkmZATAxmV9imNKs19/k7QEM6o2d4na36gi1tKUylGvaW9/X7gqRe
H3p4wHDNbioX2CM+EcFEaF5qvCdROrvaGFJ/WFLkIqh7ugc2VP02qSJEOy7YwCBpGlzxqMPvwwaj
72stY/M0yDT7Li5j1DZkycAUSJMnggEnYahtaEu2tnCmUxu5u9OQVmPjK2p3yx+wwQGhApxSmZb8
6AFNqpm+zAUdHkUIcH+i9fdEqKxfRCJr8Ove/Qln2yr0u5lehYAAhdMsNYs9O4GyK+uCsHqo/UAn
M966sZd/n/184jE12hatPbclvaNbdwUZGSKvfuaONc3biPAupK2c43BMMwFbWwHb8mTarFBgcns2
6kGM8QOzbuzS4TZ8bzMb1mstWlNQevL7D/XRkE0os4Jxg3tvT6XdmNBnjUA8LVXEcm0YjWMwL3aj
o7NaKOyB23dQyiUhMIojKnxnHvm0ojypWhrgy57PB8PbLKj9hPirU++ix8mFTAztboNBAAACQgGf
QGpH/wESarZWI2K50Qb6fnC0jb7EAHxNAaxoDmJNT2qKWPSMTIGPPq8ohz9xESRVYd++p/d4jTtU
nlVi1Mh2zXap8N/gH2eHW7unAHCLDpTjWzxrfeboclcvfYpo/9ef1Q2gsPNvXbi3WKca5r8iuBDv
ccatWwfrOvRwX6sq7q5HCiuldiSIQ1Wkmh6ab86tQrsdsjuDfCRXMDRTAZ5XbOToBREpfG1pgzlL
gPqPx01SPJEpYIpstr5B2WAGae8bLRr4HkqtVmqWjj8jDVoMqPNotS8EL0fijaA3KunLd1eXQz7w
0aSJVIjlk+wN78nmxaPD/t8wIEOvr8pPdy37wRC0Wvq6X4eBHDIVyD7O5EE3Py+oYG2C6t2U81xw
tKM3KZ0KnC8tLzUdxFG8fWi8Fi0OdXGlvfVUwJivHe0rd0qibylL/SIY8mGTsbItZ2M/ICEenohb
WE0fZZb9e2PE7pxysA35ez0aK/CuMFjnJb5+QQiavILcqJoQ/AHR8KSZ8G5IKfTDo0n+829aXuV1
o99XOBGK8SZaanBGQEEZmmvFD7gJ4RxkxV5NEJ1jE74mGemxrn0TRtSzpAfDXUYfS+9U4RICToRb
Xha9Ej8P/712nLyR+Ta+YJuI48JD7NzwZX8AybI+Mju9rt6chLRDPG26nCn5Z72T4AaLYZHt8Xjo
D2Hu1Y9QQJYvSPX+gLbsbl9FRYrdsk/AsPnikc/WP5+KXhZ+pVxNL5na0UkKP/x6INY+r3E5mOrJ
XALThag3AAAGjUGbQ0nhDyZTBTwv//6MsAJT8ToUYJsZCBKV8AJzwTJqukANgcgp/AIx83HfJqbx
OiSxlmfSOcegtF0DiPOxz52lNoYZXmgKRN0Psll4aXzxbDwaI5wT8WtBmIrcYOYFs2ailDeoTk1D
bk/wPdox6sE4rfNNm+Tc+eXvUoZECtuuHRgAAgZV5c7TsXRwHXhIyA0p4gAi/2CHbD7VkObUB0u1
9kvqr3lJBVm4Z10sNBTWu2TIwGYRnK9a5vHthvYZZAQp5CBRxyGJiS575OzVijUC8tGZPWylrxAf
7YcYu8raMlRk6AvMkQ+O2SYxNk5yOwEtGfAT22LOLZZc4NmCixKXWUYyjPp76irlFE1jDpHPAfuF
CdQ0tffLkFeQbFDSIZasj417RxkmNZACKA1n2MeUcH/2Er1PCneIawu8pqMgBaOIYS/ZtubtjJjO
ScyjtJafJKS70dUWS2k9qPRawFL6Giwv+qBtrsZ8kY74qm5U4SPFe/2F3V+eZxDzH5lwH+rv8WdG
jJWkNrkxYYtwflA7VGmB7Ck7PyxWaFeXC+uG+ledjq97zgeU4ApYt9AJVRcmdxJjrZZTrnG6egaF
lWEhHow9z6z0MiydTD8Y8gFEH74DbnK1l5cPrxkAe7plvjT5gkX2bFUmWrSAPyVcMYbjsq3I43MO
FzxtI+4C/J3wGhZc2BMyc1J5QkGt8bQ0ou43oaAeVi43DJ7k/xtnWxH1CgjRDVm9YNyifydD3hkr
y7ItDvmBX0ewjmmUrmIUv83uepTJ7tU+eIYT+bYlFBO5PqzC0ZS8tCoTxexmnTmLvwd79pJ/MZMQ
kK4eHhq2YVSLLoR7CPNK66v6+qq82eWB3/7qjB71B0dw06eUsbYgsKPTLm+ocb0KT+D3/QOdnOHR
jAPiUpm2JvMun/oaulpu2G8OJQFqh6OwD5l4duo6b3YBi5TExGcOPgq/HBjmgm6uDiB18IDfsn7/
3+jFL2cz5jonauR0fpOord2FCXeJ8djtz5pQO5gvZ/QJ/WUZUMs9WFFrM1s9sWdlVgUlNbk22ObK
uKSmkv5LwaHDtZtXrdBsygEGitemo3yPr4nGu5Xo6Jqie6Yv2eXGUhidjTxkgngdzTEfLtQmRUtj
hxzcPl0zMHQ++WpU0DffUW10f0WRuSzRYHzVP/4XdWvh+sorA765UeDoP8+Pe7bsCRHredKc0qby
MQWRu10+odH83MumLc+C09pDasqfBhYCH6zplhmhHsQGH8Xn77o2DvAZv2u5lucXuGzWOTe+73Vr
re2QHfKt0HaGYwC+kx+3EZctRY3Gsvhe3Jtf3L/6btFn1hdpmWRmu3vZd686lN9RBoRwYHNwnHjL
11NGLmtRMk6JzfhYAFmgl6wgN7mbrhmDe4XUK61aJ8BdI1BxI8OGf7wk9Hb9DiUcJqF2U5Hm7HPf
jebNqSgBFbcN8Kzo2dfUVSdLdLZzI05i0LosrciCgnV5DtsvwNVeSn68sSHc5MoU/OGsZBJfjnba
hqqx+BJ7Qz5xEpvmebVO21rBMnFaK/aU7YEZGN4RbtKVQpiayEoohPoJRjiCLDx9bjyBXHiJ7rxT
m57hgIhDL+jyoRriJBqKbbgtSDjgXJJ/8cMJxTBPIJFKXM/lHb+4BWMaUbi1aUakvw9s21P45XJ+
Hw2LbVZzjDp3aSZ7lKWHypbSKCJm+SP9PJ8WA7i5vdSiAVaV4xdpPnWMmz4xPJZGTFoLH4Jw0JnV
Bz1lLjurGaX3pRQFg1rOe6asdQAXyT0gl5adQyaseWew/dVlZLX/lbyZnqTjzYeTUdzSYOQnoDM/
hc/M84aDBZYDRKadz0b2RFZq56Mv64qDCDA5m5gn7c0KPDtDPyCCgc0yPXLPEu5xcKDLHOTJlW1h
Webicy8yegJi9v77U3k56wEkJEzwtL+LIhqtSRYf0ex8fiTBgtvyeu/BvAcRuFiiaHNDLWaKMNEZ
1NetI57VPVTsQZx8jcFVa5ulwmpc0BuguW2n1YD8SYH+y7HALC6kq69tmau81e+1SbIHdVmtFmol
Mv852pjK59ClDvEOi4SXE0Bf8gpm2g4acJtuA/Dsx6BxAACmqVJOPesoxiZCjsD1AbdnvK1z0ssQ
eXa0Z5QDJH3MOx+t4Enyg5QPYwEQcbDju5l4Kblj/IaJvFLZZghe7uIMlL0Dqhpvi9kWF2+NmwTu
skB8SXZzorn1E8weRvwjflqbB0bLMR1M3eEq1cAuC/gAkQAAAl0Bn2JqR/8BLZKkIgPcXT8AAmAr
VLZ+rST98aYgWik9RV8VAjaxjy6m9yXjyMP6zwdpvj70KBgslkro9P4TTsXZAlpkXV6LnKduQz4S
uRmmi/KxW7DCt9rrWvNAC63Q7YhBJbxW2MozSpIO09RbJ1gEGcTAC80C9jX5Y3lJ9SUt4xCwq3ck
lq4GAHyYil6dOdrdy2Jh7dCs/DhFbaifGApHYfthGrA96b9wOESiq2uon3CvIp35TGeJAHYvlWGN
/WYhrkG0qB3CPavxTjNrrFo5zuiZvsMGybr4xQj8S/mHkWs0n8SFK4XKbqNr3nCfXxdePTkRXJ1O
hbZd3rIv4juY4EVNhGfPYBgLgaBarI/N6N56rx4es1xaLNxnDSOB4hfwU7/VFenj9JSEznblaAf4
geVaq7KBJxa+B0KliROi1FvImjjB1B4s4/pgKZSdSHTvWYt6RaUJSQ/9XPBF0W+jqaFkJzU7NJR2
3bSMZo/KGq+UseIRvFr2C6QTfO7n30lmlOHJyFhks7GXTwSWyrDmnk/1IGFd5l2nTrBGsWB9BXdW
1k2kOFL96wwRNieu7XQESRH2RP/tf8/9qy/mapUmBeXuQ5wmlemms/k1Ch9lx1DQrDglQOKfbVbV
VmJOrwmDuX3dZoRVDNMjcCd7EuApML18LPpK90t9dW+lrwo4tOPCFIxofIAK93SMUjeySLhY4UCO
SIhx5Go0vzyqkh4m23l6aFEg88LwowGWg80tHgk8UZsn6vFouqlO1QGf5lBuZmVRxvNf8jRN8Ihd
6k0afV/XagLwtHNgsilwQAAABqpBm2VJ4Q8mUwU8L//+jLABZkJZL0kAgHjK6PiZ+fT4YUEiRC5p
78tfEvax5Htb4iIfJBuHOwluXfRlsZla1SQUlokHQuYpNXml1qNQl1+mGx1V6fJ23qvFqZsQWUZe
/uDbJkCSZzhaiqVRDI2T4g7EXBTrJE56z7S3PcQGGQ9853W1OeeqkCsMbIoy0bUFTn2XFjQq5Qvi
rZkIQttVo7urLEe1HzhOkNatFivHv3hUqT+tw/zD7GiFTxSUGfV4D8zDsW5I43dk+zgg4r9GmZk7
LrDDN696NPP44ycK0ZtwMQ+GpDxN19EQiVprQ6eE2QPv3/a37j5ro9fULWMF3ZnzZGfxgeoIb1PK
Qb4S7midaL1stOouaM3T6eE/BFU5nSye8xKHKBcxN8IbyaAPcJCRzxzIwP2/QYKufysBuiK4Jvny
rdFGyQKhzBLCpt1zLPBi71ALHcPMSg6sW5yl7iV0X5Hk2mYURSk1LFZHGo6JyrvIeLv1s0iIQs/a
Ey2r60vp+NBqQ97Z1AzYtDqLwdiGpdG1sbopRiY28zAQISNutvpt37/Gw0L4bdhbJHXT1w8uUs6h
FySbbI0C5ycI/3m5nDB0c4iCm7YOC8j3Q4PU0ev9Ss6cyOGTAC4jBUZcQOQL2VWXcdM7C7VF/yp9
DCJBWyjCTz+Y7FWjABkogkmp0jBgt8AoN9phTe22YqQ0ArFAK1ozSvuKWzoXvUeedunXbTQP0yMu
my/ibRjIppOi6GZ+vVyVFN7GW3f3XXnJ5x8WOCoP5tXgJh4raLKOwWWQgAiJ2jfvgVygyzWd0V6n
r3jm6+ZFO6+SmKDN5mYbGHMzKNbmcgV3PUrv4ZBAHEKuyyN7AEDAQgg5kG/83h1qyWGIoVIHZG2N
zlUwAUuGl4X70TAiTgHyg0elTnzJ5F8G/ERBHC8a5YdMIpFbduaKiznxKUhAT+epC8VE4RMMyxlh
rElYHO/AYNDeDlnaegjt2kaSBsR8IPD7zVsk8AJv42CsZV9CZk6lQccCAH9/hcVxGedxd/Pyeahr
/MHk/psAMyQAinJ/KZeqTyDopET37l3g2eNnoJR0Ay1SEHIsDQTy62qHflpr/XKlCNu4W0Bu0n8v
av0Ek/r8ys3ThKEqstaNCGdZZcjU9/DRtNPE7yWfE7tEEiVxwxVSykJXdFaEMWoXxQheKNQ/Kmki
iRXtTtwZ26ylckOz8i6rQiQ7OMKxPRycSDfrPOmNUr1RLkgM3qKvY06Ul0dGHnBkaicSv5CbVr5v
NiWbTHTVAn9McsAhwq+Xn3yWHXDm1YMZZGl9AeDkepqBbPTIxGD/0r4fUFU+2qdXsHoj6xZPYxvG
gKE2lxbt17aHJDtzN/M/+j/O57nFj3a9v9zBwFdd6T2uwU7usptOLkHyuDAe+5rpWp5eKEEbTUB7
LtnHKMpALRlSqydUwLNGsNGExgyRLtlmsA4uuoMMB29WfTj8B91btVXXXIaRo9JMbmdvRFLHNjMX
mz5nLF1CrAFqOFKpJNjG0dVO2fnAjdmAAZ9EWVuq4qtqmGxyS9aGGjFZc/ZbzCmTLTnieTcSeZEI
rveYlDadKwbn5gobbeb6/F8AatZNcn/J5oi0RTh9W21iXj0fEUIqrWIUyAQ5N0LuCvqjl4y1Ebrs
w02JpV4GX1DLDxSqnvbubVJVHQJiRbR+fuZNOP2CtJMPk2/z9NsSrWi3XeR4AJnsK3JBxegSUZqn
c5/EPpoXH4VpJHr/VR8Cbnh4FPHw1HSC0y2EAxafvtsIuRGKqauEiOEiGcfosyE711L8QEXD1rpl
5OARNV1Hz3ItZKxQJEftNcbHrmFk1w3/VdlerA6qgZ2TiO0/W+TVlF0RimMXaN1x6uabWnlDc/G4
t1+BM0Z8VHCK5FiIS9VHQIhdDLCTFc2O49lC0x+I0hrREu4iEDkYIf8qf2t2onHu8v5SRpg0kB8i
XZH8WNjgzrSy/J02rxBKQ7zd8sqCNDf4NPnbC0BTRn2RHj9XET10sGgqX//BIhduEUgTXym+LCBe
CuHuP68z/q7/E+dMl/ZutozwZrlbjmXEhdhaI/HY58QHQPm9eXkhwENZlfq3CuHt/sDNI7PJShua
vayGFwmbskY6FQlA09taHA9RF1aq1To/eQSHYtZsnvmPrxeqy8oDOynGFQH5ujGzPSwkWTCvzYQM
Y012uw8ozuACX3z9UpkONSgXPxHXVqa9PMRdQRT9iXwWV8isl3nxUIvSG3p8k+dLuXuZlzL5qVH7
0bZQiibJFQ91FnY6tSTEkQAAAmQBn4RqR/8AsSYiIAAGy2824ZlLmzxHUitmIYANp08pCHfpDb1W
p981SHdwSQz5QB3ROs7jAWW70nbKeCntKXDGs9Rkc4z1CNpoJ4TX7iasst7pfoVClZMiwjElHDzP
H291VP4q0lvC0oQyBZ1qUBZDlCazMwHkNOfSKQNFAZo57Ia5L9QGJF22XtqC1BlCEvM45ClmBAke
OdsJDC+cZI5YDTTSKr7NvAhKbSZA0f9MPqPAyms9MTTjU8HEm09lay17Hrp8p8JSRbsgjF+StchP
QJdvQsV8YA4X++9NoDiAoVa+e1ehuAe+ZpeM5/1xL5IwcDAXbUBNnLjVewhGRrh/eKRs/uLw0z9W
gL0Ek62Nw5H4MSt8yAoAHjtnV2vU+IDMh6J1zHEjln7fU5L80GGHOKhMyNZlzf4vkHs181v0oTyb
N0RL0vSRJLKgPcnZq9PpOdrBNax+yXitXtho5GeZ3z3q4yjNFJGtZ1dWGGs4Iakcq5s8XysbZ7rf
Fp+eLmrsXFmY0cZgnrDHW+r3kvyufwL4ZpzfjgKB3UBYlOaVRWHp2fMkCZ8xaWeggYWoW4KrAJWg
CyD7H5k55bG63MRHqFHfG3csuDkc0mdpcjAr1XOPl3A5J3VaU0Al+8srAggy95tdriNRk4gE0P5G
QpHVzGRRzTKbljOa2L1K6lL0PDGL1R9AhhTdG9mKkLcSlHc9UzrA7tgugT6YU7hQjE2nj+Qmls3J
Baj7roTwLcIlFDCtlYwOP+8X+JFZD9qEfZMuUOgQdcIRLG2scvbxmevWPirIb9sCByBIzhI5PjT6
jFsz0X0AAAYMQZuHSeEPJlMFPC///oywANRAQOAOKKkMkwJdtvBV+tKuAkfjvnvxDi/rRkhp2ZdQ
a1hEay9Pvw2G/04AiF5X1mZkAMMsH0xV+Xi8GyFQoTv67WbDbUQv25pxPWijLLMBztNDB3rdT6EP
c+qcZoZZve6FTad03YLZ6uiqbjVh7tcFSgfvF2N5LOpj0LHSAch9LCi/zGt0wK4QR/s0yrBBJZhC
TSLjWXKrw7y/IukIZkEheYZH3UzXIQZH/u7+WQb1oVRR0PS7EhHcPIgWgWFuCxuQtJqdDT6jpQNY
IlrHpBD8Su1f7FrVNLTYJ+16o6QtJSS/rwXgyX7Jgxpk8smrip15DgLyWkv3+aI5BBLUQ0orH5XU
wdQNmuWsv+H1dBM43Rv9D8066DecyCLVN9p8Y+t/2hhY4/ADvrAJJxSs7F+IBj6M0D33jfN0NgLN
KLjbBXWKiNUwJWDV2Nb5Y3Y9IIoViqvKkAk4fChSJutWym0+RhdAMMzROnUSh1VLbNWiBJcN5EsC
v9l+P73S9E1ELIS6elst+tuoA+hUWe1ucHQGL+g4ArO9e8wFgMQ7C5p2WCvap6/9dH9hl0M2xJD5
mi6Z0mWtkNjYdX2nG1x7gtiltwnZwMdO6bSqgUhVmknnF0kumqRxq7wwMgIHq1EdworwCqjsrcDm
DCK5tdexkMZuRXR758OOFpdBqtGFvsy/+QqmFudjuEYv/GwChjWFE7I1GWAjtGsqsnLsVr/JIm1T
6IlYtWHM2+c46B0k4Kom6wcgltyrH+JV/ceSoEBDsNsZsoHcKqChwSSW3SkY9Ts1qjRudB2xzqfU
sgdLbf8o+V1OlL5v+3oegG8izjpOPVWT44hGc4x2WXRW4aZD0bOv0mi84Bkm0wI8lTy/xqn8RpuR
HfCoLrz5HqldnW5LlaCUCgYBhOniIaHwSYj12OvHsK6OM0fR0PGr88xUKYpxXmsvO1H7tZKsYvNg
6p+rbRCLRVZdF2l6lgRtynVQS2dnliaZjwctMWZTF6lUpa526C+cOG/rjq/GEgEvHJ4qjU/14GPb
5/Z8FzgeCArLhTJvjl0qNl+cfagPOejeMPWeKUADwNekFPj4jr35Y9ORMvEp3vLZP8+kWURcqUH/
sUTEElARkjfNgcfYDVNe8FZugBsxxc7UXHiTeDP3DOAC0ubrE5/kElwEy/+mc9+SUmB/3lKsqkE7
80ZdVuxsO8jaI+VTOUrr0yO7ouG6iWpMUVwNGJ6ENJ/W+LVWjZLCyEsmCw95/Hi2OASXqz2An4aM
KiWF+SVuMrV7rzqm9aiA8C07S3p3sRHUlglJyHHD4C5sdyd7AIJSUsDU/t/NRIMDC93iFG5o+W5N
9Gp+ge/bPCctsMq8tkJ2I5FCbsUg4pQxUnwKMRGFr0sIlkTsHTlfhHH+gqTAThpTnNHqUeVId8hS
JhDp5BK58nTxKolq9S/N4fnZXXH3Su2n8kkp6G2gJgy89Z2Z1j4A/Z+u6w8I1wwKosSibsGqws3f
IWzvlKl/aG2whSZXNblFbQTDjGaCUjidLQGnhs6zUvjePxjyj+pDFFVXT8pet1I2nZZX7FlrhLOp
9Gq9aB+nseYLdOjaMn6nC7ItUVjhBZZ8P1XE8lxGI0Qu3MaZa9Z5cItu2xvr+Nb5iGryK1DXssrD
qXv857UlzPbFfhVt3CJAorUeYuE3qPMLpPlZXhVF3NyrvRsHny8Nh19tws8K5siIU3L8M/iJSgnl
Cm9KAex/iG/TYK/UBejeY0tiWwsU5q378U+WxsRBtiWrVtLXrnZkhiONiSBJqOU+TDu30aXjWCnY
rCxCnZdt73PlaIoG0Hc7blNJopjWtCzE/QcfYGSC3uwhtMq0KI5d99cRP9TiCGkHDF830Jz/0Sfp
DTk+dJMPf8OMQryNs5doKHwEAqq/61Q+bGQg4ByGKQzXhgPKxsgL0bCIsiPHD9fZ5miS/xHfC87y
by2I3XwvbWnpFgndLkafPe5cB4X9hef+qEnMGHz5TlbxStMLG+LOOk8LjhwNeiOLvQkCfKzuTtkx
dcwFANSmnqzsx+IRE6G3yTZhAAACCAGfpmpH/wBqvaCs4PJ2cKOYQSnpIVQRjgAbIEeY7b64Pqog
WjPcI+Mz/Hb0MJuzTI1k8c98U3qfbkFWRyQwe6X5idDrH+pTGcLrvi6y3JQYdZ+vM6GnoHy31HLs
zQPPCAOiKtRRlYHIyitQ9VZrIGed89WuJa5n6r/bre8VVnFaAr1VCVR1OBFmZcPLwI9F8khIkMRH
ZGtGkFif2zQoa4c/HU6UvsANm50A58OCRryZYT5p96/oWFi/FVjocq94YOElQT9ynR+ENOSnKsaS
isgkW5lxRQ4ArCVJunagjMazhfzNqQDLxDYLalJqi8HW6AvUF+1ipsaRXMfo+fvGkZ/L3e4+2EVl
Huc60wPBYfrEuKNaNhPXUlQ0DQPRB0aHlriYyzRjd5sBCVSHLzZZPOIvM58rvfneUa8O/cRtwS7j
m9djgeDqukL6USqBM6Zz4HnALk9xYT8pDOqMQMI2eBK/DUbng/lWqSA7V9POoOI+mYm6MJLEQ1Tl
4wj4N9sTGycYoWOVPAn6zXq4b2NIb/tsQF+Hc2llbozO0yG3+0aA4ArOKlgsHOdgIM4vD95VCkHj
0syYYgQoPNIipk3YZC6c3n9os+yxW6mc1yB/dBhqIwxfjZWKlhyUbl/3CWMSHVbSymiTLimfpqUm
o2Cb2SscHbzDHeFzr+bmUoyxyocJXS/PVKPZjYEAAAepQZurSeEPJlMCFf/+OEADNc1U/3B+gBNc
Wkb3yPaTYrdH/GLXeBXJ6ArN9A+KLI6XP4Gvnwa+Lq3oM3aj5Yk3HRthhLz0aB4p9cXdWZD+xp02
hLbvPLBxpHpjwGpG4ffjwVyD4GGUXk4H88W5a1sF6jmRP4tpYH67LUNYiPAzzXweHJywLOaEpGlZ
TekvUtJ7E5/kmYcmjOFe4Po4D4wOgOIWD5FyLhXF+fNIKHLdZ6tGrljv7957PKP4/utrh4UG+wDu
NTWxj1gK4t90lkas+SWCktJ8EBUtrnoT2zm6oJn7FaP23BgSAzjdbgpRIuQS4tGDGKMpgdvogJl6
4UJ2Tnm/qXr6OnkbgJoM8H6EqgZtRmJ1p97xm1+Oa6lrhze6fgKSy19NLbiBlSgAI1Y/QLN7zqeR
81uW5yFXnnAI9dFy0b2+aXgY0cPBIcro4Za3WGxG4bi6JIxMcxmRuc4ALuQkC8CwRvriZ8NzZ/SH
sag2eryRQmDVmhAE8ZlRSebnk/b+um75uo92QDc43a0wzq2pKlbO2KUWXfPYQ3L0yaujwCLhUtB+
307wbW2cB+5rz5j//gkZiipMGugbZ1Phnq8tWLi8RYGqkzcHxJxE89OVcACiUzqo7zWHbehYQQ/8
fBy97xuoSFMc6Bl2lTf+V5fLdhmooRQSP0UgvdL6jMGGQDCovGu1tEswwnkVzdwtpv+dBQZ7zBjy
/5eDsaGOJS29CVsoBwhRo/tBAL8l068mbybCxdcqjExDQf74SlCZVG+6Ur9vqGFRPMIAvv5DtGPc
O8BkiiX8tUeFhrDD+ZoPSsJGI7EojHtKTGJFFyd/BdR8eG4PhvZv7bps++SuBQaWuPGY+qAnASS0
M1NpfcJqbe2hE7CTJ72zj2t+qcTChQKIOWj9zwk8bW3T1JR96IUCi08Puh+/wp2rphVHNi26rJHQ
+Q2wzxwG12pfD4WxMlWuzwL8kdZ8Ax9hpmW+SkZpsB8HKhdQkD0GtIVKMgvnATHZQMBAYay1+6cu
06vBkbgtNG1pMyD4clW5OmwFVN7P/pX5S7f3/0CieQabpBk3BaMMQE42gSPWU23Bcpq8WASdeshK
b/pu+yAOGx5NU9eTCt/rxLSZ5RP7ZYkG9wsdyuOU+6O4mceuUsGuOHDFnC7mUi5DyoviyBnWgt06
Ptrlx8nEVB7dFQIUieYhkaPZTstvBpUMuG33WITePrVONk/UPyE0zZH6f5v5yEPPRYghOTacmmKN
tpJsRI44XfIhvxKtOsWesKaZk61GjXYXEL31RGOlRGGZEWFu0y+xzPHx4Ec45AkVzk29xhrcHC9a
KeMbylMbpmDoc4R4jBqaMAo1VC1CHLlBgIZcGpIMxr1XQtZTz4I2/C+VBFVeHjnRgudjivcahFjb
QkY2fX6IB9Q1IxmvpcKgIYpahg0d+R6k/zOA6CEKAqTxp+OiBB8oRFDDUqjS4Qiu1ZhIolqpZrOb
G81DN7oKzOSMURztIOyEwnbAjoy1MLbylz0xueAjzi3YzL4mQWnl5kZwSCHR2JIXiiQfz6rCRKWa
1L65+jA5LmUKl+JZA4hF04zAVGi/dEGAOiK75B/JTqZqrzDYn9QhjrMq8EG+Kh6RD+9oIgNM93jM
WTr0+E+sAf4mA6tJFvGOZ9Hld/j3jKhpguVptWOq88TU+5q7phQX0Y5OoFUnKovVx/ddyWLbxFsS
4oRt3zU5paaQtZfNdfiTYEE/7TZwJ9A5y3v4+qfSoVZt1lMWsOyFMx2MXxRU9Hh6mgT6iAU9i2hM
nQtRpmQ/a0Hy4LP9NfivWKN7APThTuZx6VKMVhvPIa/q+9yx7c/xCGpZGHadoz/ft5yfOOiiX9Sz
AY4X6pf3fgQWMv5DLPlSuJGrNidbz+Try+nl02BwZ2t2CDLk+Qi5Hoy9LnEZN6lbu6RpBrSDkPKn
6Jox7/J717xb815wFsRfEWP/tVkdKnyuYJdaBzVS2HEqnbUGqh8tQsqdcayyPKbJKDkR3gY9XwPe
AZplyKOqa7JLXmtlgVEXtCq2y8wiXfmVsgQb8Q/j6FXA1U86hbDSYstUn7OG+mbCzzq3vvUZALg2
Rljpo5rjzbLOVvreXbv+bXYu883mfZvagxfdWznsYO35PvnLmP8DTfKSEEH53EY1UJTrDPFkE8il
g+XHgKeT0eSffwQyNKa9ekp3Oy31y9OPkM4bLwN3DFG4o83qoaoEwW+Jt/vuuV3jbz/SGWsnzESR
vOcXAcIU2Z0YQM9p7MA/t8tRXAKf5u0DZCcCzh4jXv/lBg9hfW9q8XU2Nsezrl8aAHyX8vNcC7iV
15SPMVsuCjpbKricOvne+hb0I7H+oMCo2lM2tlmK6vftiVNG6zfhwCAjg2MF1wQtI1BW7ToaGedZ
UR/+j09byQmAXSmiXpnoEzA9IMfnBpSSKwoCfqzC7F+LboXTsTQ5IuDGAPiMfa73aBQLapQY0Ww8
RNuH0ZBbLS1DebiUAzHtVMsv1+3B13ySECuIhWe07i6RIK+VGoFr98MLC4Vx2mUvW6ooIdSkg03v
AeCUXQJIsGyQFKDwp4G2FQTh+Ru9/KnCTHfXftsK/7QEp3LyLpjjUO0akn3e7cxYpzPHze/+lZgA
AAOJQZ/JRRE8I/8AQ19QY9lhQnlSAEipJSlMiadkBiEvnEepajRYFqtnNM+CeEjzCQZ7lwRMtcmn
LgnRR7PRVHmILhS+kf4meDiwnljWKnj5qzwDsAL5cW3Lwx8KYI86PtlXzH4ZWbqNYuDjuhWySgfl
VdqcDy0+6sU/lPcfPMq7K549FWrmr/Kw5YxPlnlzVePTTAerjiJXYUojLbaId3BDX+kPuBo/KIDR
okek/zmOrbJtH5GvJt29+ByLNUMQz8cU0GaXuQ2f2Kl4Fw/WBz3vx026oY/IzjV21hP1SA9BZiRG
qNOKEkjyS6A2UmnMEVsAMi7zvV2kQaSDmmAX1HoW9UsH20hKpz+FHkV5J0xsylWh0AsTlqpayWOE
ljdgv3sw4xG3N06g1RV3PVLAfwFLYJlUh9C0JEXh/haXDq7sdAPKRw+u6mcOy1Rne2cKPRmWmkem
UvcPKxsdjOZH7iZJ8QvfFoUTLb84+Nqs7YToXqOic3T4O3JXOVdiRKWQrFVpP+OMoozXXn6YOpCi
DmObzYJbc4M+6X7Xktk9DvXrwHYjXiloqXcwFo+8PQwmjeC8VzGGDVn9T4XZsRb4VKJWB1c4M8oM
SDtYttJY1NPbn9LkKdofxfNfWU+EQJb8BzskIcPrEWr/6fP8InCpt30//GJrXEDZYmMaHuYNiI/Y
KU2Rm8SUn2bCckCM5Z9Y1KgBaOBFzroMxyyyQWzONL6m4WPrKpmPmUmwIUenU+/o30TMhNrGZ9Ew
XM6jkGWCdr2KMiwrAkSr3jWR9GyoUXfyNIw3y1eLtg+nmX8rSe+iSjUJLA2LqmJHvTmVRSl1t5jb
McR71x7DFSc4l5LXZj4cGIzkMnCR4XE/xx+ZuuY+NQEzykaty9uwU3o3nnVERe+SIANwKVn4Ttt3
DtGftrfGiP+391bfmaSQ1ZrBAUxzd8Rp2Mnu2cC7qomQCeJ4YvBQCFQcwF66HB2EDlPy3KnbmnrX
Zdov82eKDp/Eyqa7DaHGsrKh0GRiacIAcxpEKiGdu77NIJgHr862eYcycjFHH6cIwRKhnE0Lq5ZM
Sd1qJC+/qDeHiob19j5DWu7BSvnDAeNGlTfx7aZcAp2dK0HoF2qu50UzTvV/yRz/6PyHrhRh4iSR
koRiqQ0H2oMDvZkexb7rBQAKIDFcQ/DNPXLfPvdBqIUDpxLgFuCouXyX2EVFTtfAn0qsOVAAAAJR
AZ/odEf/AGvv46yKAqDv4JzDH4vgAE6lPIPjzTvKIkHXLwDq9ab16mzBB+WsAuoB1bE8CUVyXEe9
92JglMDbh898qzaPzJcnJsALdkrwLAzj80VQPavI1fIRi+lEBYxS5699kEKO84jfHeToL5quDaYa
WjVvx/2hvM84y0BFXn93tKpef35Li64JnJLawToz8KBQBBteUilsfrZRWzzYNIA5aN37WYXFH78d
Qo1cFlsVF2/figHHwQHz1q+YUhldfvgkmFuyi9FR90aaB5z7GnyTISWQNyEmQm7QJgPeasD4euAH
wsUDMkSKqhl62Yw/u9qPfxiP+Inidm7iTEPc1lcudbpDGcRqUrxZGAwAPuhjw3qrIGGDt/W6eTd4
91iID1eKw3BjKHJpBjZSZLHYi/lb8BWU6uJQoC3bdirRV3317T+8y49HJk0NiM2CtTpZDRnZhnJ/
bQ2/8Ndz8Y8m0yuKhA5YO/zL09uiT4i0/sdIQXH9PWThcDEx7SS1zp2Oybx9LliIdpIBhSkZg/8F
xaytgbgsQ9jz1H0fxS02430/SUJYZO1ZWP/vkGmgWL0qzp8zTjAUK96VdqARr6tboTsxilB7to64
9IcoM1WU9HjtzKFtVdix9qKSB+9dS4Ej/Yr82P2orSXNvpi1dDCCzhZq1/NCjeTTeDqsT9iOVm+M
Oj1wU3AewszZoQ09tpcPjg+wO5uA46mZwXCzp+w/KCmGrpwYO6PfRctEndDZeGsoW8IgJHcsditd
ZFR7KOnIWEcLDLaDcD7z75CdpjllrFUAAAH0AZ/qakf/AGl/HP9AfuP11eMRYkNQJTeX0f3vWgEp
QARBpFD+e41yxde8r80MfJ41yauP/19tYs0Q5hwDPY9gh1AfC4IBekw9PKMItVL1Mb5IDuMw7yE7
83ZsScw9iuuP7ProJS51dispiLwmZAk6Eecm3crUvdksoPYd4ZGnobALDLYrIePMbdKenzLCYIGj
FAejTH8kAKU9ZZWo10W/9a+hlRPJln8/3+rCSEPqpa62lI9jYX9nK6V5cpNJO07a1V808Iu6/q7w
ISmmZEdd+FFQdiRHJz0Tdof8Fe1z/nGO1r+wdq49cJde/d1VO4x1UnHBKgfRBP++rnbfVgp7Dr8Y
5BWWwlUIjvm3B7Cw6REThyp4eSpL5HvAIfyAq38bZjt869JXdxKyLFLUbVF4EoXuvzWKX9xb83Gc
3IPRyWwtbr595qQvTaejtoZgXGeo5kDMuOqjqluU2sFj3zq4u6uaR7V7efWO8NUE4IoyeoEKaZQ9
fCnoD7ySzBS3UoI70SbRSUYDVT+4PkdG0J7iixa1YxjlKsL+WJYBCVUAZEnz+a21VqCN+We/IeE4
db9GKfx2sCnbdLnlTWyM/B0KdG7VcZ9J9AH6+WuFpDollXMdByJydVh6SZaBz75yWeqPUNfeLj5D
jTybfx/U3y9wh4Gq0kAAAAXoQZvtSahBaJlMFPCv/jhAAebTpsj3k+oAAE36CMxXEJItwTucVC8u
2mz/e1+1tEvsR69HJbaNemMmRnqo3+MdfqbkCHzm833IWrMp2YEG3hZtGd6ihB5Jof0C52tTYCIg
UNMJc/4QQO0Lk4EGgrqKwMBw9YjWjXse88Wm4ymN7hlMpPeOIuOtVFB1bD90yNcnm7Le/vVn4Crh
2ErKSRQCQyoH4BGcLbvvjLNR1WtnZeloYUyF3V1/3OlCTICEQ/7n724SWQyYXwrc6tXgQ9KL3nRz
NPD/pw51MRf5ib2g5gxUTloK4vwsMLYAH0f54Ik2M5IF8NQk/3DZY9b9fRtafWjc6xgZ4tF2NgAt
jGb+Dl4aJh9o5pI6IG76t9ifq25X0bAnSiNtW97wp8zUMFmycraoBbmQVRt865wZ1S6Vgm9bomHg
lBjYtvk4aPMe1hF3fRUF31Iq8XPnFsmRUYlVIzecvcanVz7jXv8BlTIWHcQ4/jHl3IMRVGN6Nu2/
qwva4MqdIByYBQZAI+irRqsVOL8a5WD8eKpITwAw+SkW+5ySUXdfwiTJHggklEeoMKjuW8Rd5wKd
rU1vo+YHyc8CTVKu99KuhAdjIrvnfLvVED26erHAnTw8/1GLs9dCSPCMuZT4MPXvfgQeKUCiVdXP
pDBIka0Se/mzfXrjBRiDGNfDAhpN8Wdct/RdE5OP72lITj1kLdjoNT9viqBvnsJFZtRAEU82ajzV
2pT9MbUiwMio5S0QLXfbedgo+98QynI+I8Cf2ajpVj9IVcUe5CGImrWP4BwybbZNiVxNF4eMJevx
g6yYv2izL0WP83XR7cS2qqsvPXrriP3PhmY3h2Fh3NlIyuOZdnT1wGmHD0dQ5rfurJYzdM6ZivqJ
W+UaqfXC+tKpknmPCMR1vGkHVSrvo5UFmjrBmsBE1yj5MQN1TyCZjw2XsRrgMvzB9GIrRIGe1pnw
P62Rf37omIKN/svcwdH5QfvhGz3crKaRPzHCF1/VFzNspcxzGyIOhrzfwQnkAb8EvrIGhuGwv+xu
CP5vttG1TtRqd42qN80S6BDxOcCg0UAfH9F3DH8WZ/47W278EmXbFbVqnSJabzSEZmt8PzmxgBRX
ZStAo4UJwL5c6Zp+X82mmy5IhI9FZW9Yj5wLzt3rW1uKMFWcRbcK3ola4UEiZdpPgQ4PjBijaf/h
AiYPXZp9SWo4m0HCuZ7g4Wz6a9wNc6ESCeo0UCJdMrksnlSrP+mTeYUo7tK7miGOGJfEPhKPwiWK
U8PM972C7ZOAlP7L7ZM57NY+T1fUJz1qiwiWldNj6wm4pkmTVhjIa4niuhS7Y71Pxt27UNqXzpvp
NEJgQxYQWrHrb8kVVT4yPs3a7CCjHQZOfo/1B0+wJibl81/AmN7k+zcwOLLWvwai3QYNx3NUWpba
+AYIXQR5aJeN3Rfv4oGzetOXp4x0czIggqxFGML+FVHO7Q45rdWmpz7aKbCHK01hEX3X+8G9rfJS
YJG+TnVp7ABnq7bVzUBHIiyU2gLzElDiamxaKKrNQVYKs5taO9v/TlJUEFkn0oJhWa+dEnUJMgNh
9sCeWzM2aC5gQqIQTQ2X4R0iPZ0RUbn4UpdgfGTFcI//Og2tqKUF3k+5niR9Zlxt45iy21F/P3ZB
q+tuvYA84vpBGMwNh7wYCg1IpLbGCZDvWhUh2yTwqmZuBiP4oQ9OBIK2JATuqimjLn4NcK1UDpyX
HQvg7F0BDbOmyd44IpGg4vbphIJ6JLAjl1/A6RqCNlVU2A5bjGY/0KNCwrPIpgR7Z65qg7JUMczn
sDsykS9HLGn/gE/+woatFJSYPJgdl0WHbt1itJkS+Kk/SeJgem4oB8Z8YTWCNmpry0XkLJ7TaWqd
0hGHlbtjrOx3TPQqyoukTlvLV2ImpK5LKVGCca90VQsajfuYsc4oH1BHgeeuv97y0ugCz92vrExJ
FgugYe+RGQEoQBvNISSX5SH2ExQ+T83OEFMEcw6bKycYoOL4c37agO8qaTQ+nH1sAAACCwGeDGpH
/wA/WYkp9oQATZ9/lXvAG2mFuv7TsQSNZ8a/+Pmt0sc1BKmFm7X/efejkeTQl+Xv8YTi0Q/YlscO
nQUMwcIItIwF3I0Na8+9nORHyJ0jZjlwN1KXWVGMjgm9aExtdOwWfxUNAjr/esHk3Yg1riaPYKeU
ebuoFmBHDFjVAsKiADfL5jyN6K8mDcTyRccfkr07BnGNhitoedCJy1Tvar+YlCc7DEA/JcWndYYh
Zr5eZv4rnJejTfk0peFewCdf1DqevuAbj4jTzajPeJHhZyL2tukBWew6Z04aCBkd928EhIE5ujp8
StKepYieqdlQIXCzjv1Yjm+Ob2dZ9a6TMwx6z9fQO91y0Hg3rsnvxqUwkmLIKxp7R8ITY2/11JI1
FWbEtUgr1L70dEQuevkjbpV6bCn3yg8m70qSmmUtCFCoMoJkRcTPTnJR7VVBILxJvDJPyuFt8gtC
W/n3FNvmlj/O/31jOH2sOVsg8KBvUqTFe0+wGVJ+vwGx0mWQnpHwK7BgAK+/gq1Qy700EDIVnxDN
DPnmBlE8Z8OcuFVFtC6Thfz9qXXwAoHC9GfqCJpNjlQOJ9G9bhKM38/n1DpMEXReIwdyYjn+aLyJ
uHLMlRQj7YDtroG69wWwiS6/0Nd04y/vlewRuq9+5NXUWi32p3igekKdB7ZPqfLhyQczR6ty4Gmh
KMqGjWkAAAWhQZoPSeEKUmUwUsK//jhAAeRmzw9dLlDgNALSApAHVAonyFwxkNibq/MoGcaOuoOB
eP18K+zMgLmHchkFLAMXvYg9kurkpmiEP7N8ipSMzEo93w4Lc7Wh/L0szA3Zvdfls2fQtxcAOGhp
PBjq5VIEdJUhdEq4cXevJWO7XEkGjWF4ZudMEGU2ZJvqUAUK2NR3g1X0tpfOwRwrhSkJrrzNKS0M
uVSz0tPSXufpNbb06l8gsn4iYpOvzpoGiyEf84E04zh2REWkzJwUADu8Nf4yN/UIEot6XeFFvit1
XAYH1FKo/oxNAlvb4dgOj9u8n3//O3FNMHgQcCvofnsAybQpfmlQ47vynJ9O96QA1ikjuhvq5La5
ayVFkvAgucLWzN0SLsQvZR5p+V1jNSrPcY7bTYxKPsuZ9hV/zID80XSwBx4v4ljEWBu3NcuzXIQL
YvhqQ16fM7pXrIzoLWoBKiyx0n6RmEFh8a8deyyhk5iEVTLhzf1+M+0Os+Bi9Kb70jz5Vi9a0N9D
jp5duKnrhTdr8XXJytWjv6rSxly59gU1LPJxtpfAGkc8doYjS3UmV04d2IAsdgYQr4Q5EBpLsb12
9dKc5L8vxStzLrGktDn51JQNL9XI1NfkfvA30BtygsLlUmwODdxqf/huGtMSwjLAWMb24VBsCGH+
R+dD9VBIvx+VcOSJkg7BhIcDcGmKiJ/GkgPxCY1xtVVHd+mpHlcFw/7Csl42nD90Yq19FxoN8Ak1
rulUMFPpmTg2D1Bs8n717aGnpQvhS2UWuT3rlPcXXyU0W/tVPRD4mv0Rzy7qS0u2DW7u1UZYOGDd
pktbH6PuTZHcjA5YDTJCLHWkmjqlkLG+cjoV90wENjguS/jDn1ggSrjxfOzXMsvAfhbDC4VXBdDw
8gH0WnNm/lm0ZsKBWYPZChXgFRvrNl6P05zQ2cOIA557mYXPQwNhcIJWcpOkBsfNBlT1seh+jHJY
l1Sgi9VwtzUm8ZyFJyy6HUl+xFhontOnFhMNFvZJaFC2rmG+lkA8fQrn8zIDFcIZJqrlWjJpxgFj
pwMXC+RYkY/z0ZI2xwskaoQ2Z1J8xsoKZYwBxYiFCth3Wd1d3rQaJGWABv9fmSjhv/EGPN2nfCtG
Cqj+OLlgsVydpCbDYJSKYEIQ0sUwHG3U3li6XC9biqbJBO6THmtyYmQNfcsm+BSo8+LIMuyzJmuf
9D5J95er9wyr7TenS3MGKY07EmcbLsKBwg6dBAxUKm1uYq2XCHljvVngi38nVd0p6GtifTW7dHnc
WRydBCiDVIPkMxAYwmUyvc0Rg1xMsm63vLB9FGr7Nciy6vccwioGdkI20EWOMZrChK30C1mAhGUY
AR/dLZUTQJtZPZqppImzFoDbaujOaeqPWOk9LwNEKLxLr6nS6zxafBxI2FcmEvl7eD7Irz0vdabW
KZ+oO1K5qAkmRbRl5XdqPDRYEeESbW6VdW0Jy6g3TZC6CaAnkdN2FnkotyQMD/a28x0pLr52yndF
lRitXBzWInyeCCiYHnXtpnlwlkoM/WJvKqAZ3EEh45LZlqzIgM41qddm1ocVX/yT62YwJDwcDESb
QtNU4wU1UJpTtbWYjc1r2fB21aSf1ZafplqsIEDhdhFlEfZsX+XG5yrtyLA5DqvRNX+Ps+ERSjLf
XDdBCSarlra8pjz+cDivX0qLUsRIW84HhczdKXDDHR8ExH3zYtKcjpf/IiiZM7mGTUU2N31fJvUh
cW0Rjvx/rtxEUiJbSCRoUS8qiQBhAaGojIONOGghF2trsZf7+NRuuTrAeInMVNOa3z/rLldVvND4
q+Zabvb+kEHO7SkebNC1hy87X8MTEJ852Mi3x0ZuoFpmRSySafIGYYgCKdSb14L+tIbS68EItI9l
SNYjHUGD1ujeLqnQHIrBAi4kdRUXUL3c4QAAAeIBni5qR/8AP3nddaR84bpX6EBR9Dn2kYieR3gA
QprPwnyUpG5gMnzjwXpzHiAfyQcp1Q230HjJOwFTR8OYCFxoex7bbjWv2woogna/oYE+z80Rzmeg
WzIL1hqNva02RkNyXA774NbThTCe0126TvnG7x4Kp5cB+v/S2Aal2xnBZ/D7NXSnH9CrLKRBHEOx
2oiWZi15q8QPmgfI4M6HsOdvzFVX7lOhgSsHgaKMGQ4PwVi6lSIneIgfeSLcE3/+x4gAjKNwYjmQ
TrQSKlSHKyw2pLa5wRIZSanm7zr3SLzSNBgMlXRvgdamb6Hl4Rw4CEs80eEdnPHlhvMKBi+XIU+j
/EnJCxS9i/totc6sgUubH7UHu6PTLGNPPR+2ISz2wW0ahHKg0pGsUwUWFzUVa8pjaEDqptiIoGQ8
SO72a1yzsU5z90+7Zjgr/mwnmNxzVIds3VDuwisQmvTSocS2yFG9ojjVL2gj/d26ljYnCAS8goUf
nl1vChDljgCpkk6lH/zkQHWP+3FzfPzs5TM/kkAKxtavX8iO3MDxISbL6iZ2JHnskYqcBRGp2AhS
RScPOFnHpfnbs6PXernOF0IoETtOwo/UPdG9umYGPhGIiSgL2yucynUppBWwO+UbucupF5UNsQAA
BSRBmjBJ4Q6JlMCF//6MsABN9gIVSNt6VOyDAFb9Ipn/F+dkmRATPO1wyki18IkOp8YvxxDpwvL/
LknT8tm29+qju6wRJjpqxqqoZpK/v7T/LMKyKYetEn/y6fo5ObG7uOQG0oYEvwbnx6YIgBl+zPvg
62y2VgS7mDsxxTW1Tfb8dQfvfpGqS+f0nbaUdZcEz/Vwvxa0iG3EdHwDylD3mrPQ+yyko2zVBp2+
J8g/9EsnMKOLHn9VejJtvYcUWOHGK8CpwehqKmubRw04f/Wl/jrPXbnbKcR2c6uLyc8/j8HEHMum
tHkFx61s717lIqN+YWNXNoOZLlHa2x+fkFyem7tEVrz4fiM5FySw6ft3k3JIQiTPYPHTxcOcwrke
3OxdTQSyHK0S2ozwoFdcdGHktzRlS6O54EGuvUqbM2SKPSPpcSjv4FV1Z3qm+d7cRq2TwsqXYNUH
LqycKwQ0dXqsQ/fclz3uTBKbjqub6N0Clq5C6l80ZZSxzyENxRuFgRb19jpRQF4WGnklavjTIgdf
Tv5NerjQrCGmVTIFcpzR7JiO4bfjJI9mn0ImhEcIevt24U2tKy4dxt/wy/5QTMjUnhmxMwboqAf1
MwjHXo2VTLvrLYouZrRq736EK4NCS4gHiyZ2Skd9ERMChR1Ckr0IF0xptfBZyMGy6nEq1Nmeko4t
kbKzSiJAJ+odxdR4ekOBIXEhGX2jy4DLVuR45nzNsrF3/W8YM7Um3xFtm0lZsRHeqpFGpM8miwWX
Mj9vn1ZZfOYkyV12jJCitW5Jr1e4SjWGAbal+xhqaOTXrSIR1qMV5vfZm01ePUlhbvRCp3Jw3e91
nyUMi9LhjhfvIa5PtANKP8NihtFxDoZ7KdY9/lQEXqujXwrhOKSi71P8JkzxXs4LIbRmFthxle89
ajrf7lpcTzp6J4JHfdah9iuNiWIxyjnJykrfGWzZbaB2uil2pxNRrIBF5raQibzmV1heeQeRLyZN
XQyNjIVS2sTdfIeCa9yos/WPZyfF7/SuVc6l0naPlDbpPs3l00ixPdb+CAliWopwaa1JkjVt8N2R
brKSf+oNHQ3tRHHKaVOccHjQ6rxs2k2oPEm6+8eshPxLCddF3VLXD7xNXVhgREZB+DOFfHUFFkQo
Vaev0yTJjg+6BsqILSpjAtX2SQ7225YqV2mHBDdQ9hl7Tk/BXe4zr4Agyn0wV0bwnPEPNwVZf5at
ngtm4+tVlAhTA8BdeBacbsgtChEFeWE/WJJmes0vB5ZYPVzw7+9jBxzpmJ3TUvvV4oVw3z8RifLk
vJfEbiaqY2AoTpnfPFuyiPm5h8vymDVel2JWr1VbZz6FWVjsV/toLLbmZOdDPFB7UCrmJ7lHoCzy
2AeFj8NZfIpDI4OhyGvXikiA1SbjhHQpCCte8jtfI0ibfqVvwfEQCdqhSrNH6JD424fizsBHwU6M
WSbOXWqJsU0hoR/gS/uDMDyDDGBxA+llmqYLYdNvDUrLYPrVDgx+QAxRN+EwyhC6HTOil0wiKbZB
PCq7nSC2dAFxMluMT0HDhTU4Txl0dXXJu135emKgq+vsK3Q+/x7sxMQ5HLqj11gHOwMHCPi0j9Or
8To4EiVkebgF5SPDmzW0N/E/wPxrsf4E6bJ8C/SVqIfV8k421YH7cuIYwwKsXm+S1vfMRJVloS6f
YkKd7f4vYT2Q01MZ/Nj2l/kQJxU2LrdQ1Bnlrmt0mnr9Nmdar+a9o0mnYYOykWryWbcfj+ndOdR+
WlYz9nAsMgAACAhBmlRJ4Q8mUwIV//44QAEuVR/C235gE186OzAIRHD1MRjF6l3HMm61xmeiugmY
aJ9H4GSNuEhjrClhMGAB49kkeXY5P9cya74XV5aHEFcNa6LJTbAoALMmKdvs1EAU8tbtoi8TQSta
gLN2dKgFvlyWWv1zwnf85xAcD+Ai/l9+aoIPjWI8XCPc7KEz85hQzGHac+XA5/DmJHrscwj3SJrB
4XUx31rUlz730X3k0oxIbuGn3SkVB3kuqqYNWks2IF2p3/vSVYEEHvVASuWET/b8QPsI4V3fmGUt
j5psKMjfcmjNO/4tAuKXadeuP2sk5fzzfsHHVGPlb5ddgf3bOacIj7ypeL/tGynMB1TLaAPgSN3Z
VEJGYOE5PLoHbcxTJF0aaz4pq+TgHmcTPix+qESIqWOTU2LvrMTHJ5oYQx9Ow0+6n/3EClPP2BcY
Q+pVj5EFMjm3bciaAd9+uf6IOPL4ohHUyqQ49wif8aaBU3tRerHfjJ42RXVz5uzIwFy53DePwIdN
qJKvAlQxi4cVj/w7QRh6sT7IOydzqKXvlq3LA/wp9FK+QcCZMA9GPtcI9b8BPDphcXrtyV7GNrN/
vywadsg/VmIssMDEap8G3lVd7mdsUfW/eeUR5yXQYFr8MSdCFYyhWvj8I0RhWw17uY3ejqA4p5Kk
FfLAJQ9npJCiqFOZ9M4ao8/oXSOaVStTYcgnyL4i2ayMOo9uVK1yUkeAfWuqxTdWP6amINhh0N2e
kSMq7fz746LdQjOV8/DkHav1aRFQCcStBJ7ACgHE66HkyPUKdy+0bMtJJqqlLqzav9I2eLbjeG7l
iKvLBsLK85fBoNiL+VIQrcRAL7E5zMjDVfn/zsCqacNbLjUvFr9bfI81UvR9ImHOH0SZg0MPXAcB
tY8RXB7DZAouaBuvR23RghCgDWs9FcyMSc0+w+3vjFh+KiGFsiaQdoGKFzAScJwMDuNQrJWDrdhH
M/8206Spvb4UWbK+FFgrkxlvOX5Amlu/3xqbl1eXhvywV4Lfsz4d8eP8Cw0lA9Fz/maZIG671BAR
rLjdynENNUTCJ7sMgbJcZJiST1hfNxOZSOhkgPzUEmLuDJmrH8LJoXa5g0EI4PqPz/W0IE+d9C/l
XEFvUOLV4tqFfVYGMWbo3zS3wnCJNyP0vZEt0bQc2w8oHsPs3HRvL9V0QU1mp9x5KjI+yI1KD4b2
eLbwZclS4NixRpVCDR7cru5FPOe9CXTxTTlYfNaH6z/6fZADBkUD9/bJqw5h+3PLeF3ANZpxmSmW
Y8nWPmNPKL2CVz4OTrEsHo1Rq7v9cW8hQ/1QFAAmmDWImD6QmbZssMOESTQ6Jp5k9KzwjM0j7dHb
WqJb+NpIUFioGyTnly2rYs17lqFjTkuzqlICMh/YXbHGVZfTlTsGaVvVphz6hCFd+M49Ze9ukf48
P71uPy75SpvD7KGnz8/i1N6GIaVTWfOsR9vU5h2mSqaSr7t9dEEjt40DfWo4pUq4d/Njv9F7xLcr
sWvsNzdHBxThAbjkOpYmDP8YSQFC0RPee72II2FP7NcIHEwCloMCZIHHgtHEbpzz3DGQSCrNDl4d
jAPP3ISCCJV1+9ps7F+PZfrVBnihOM9X8CQQbEQUd9+rwJt0ksz/83CRUxUzYBlTFrEDcNA38HbJ
Ws2gVm/yvDsUjo4fwkLUtSiYbeBEGoMTsc9YJincdI0mXfAchqnvmJHM2AMx/nndUQf21UjVzNS3
d3xEbM8+pBBfWuGG+bPVnp51acqz2YrBrUA1huB+geNdg8ZWZOIccPHgVkGfcdjLI/gsB66Fm/CU
TNRvdusyoDlhSn0trP/NBeEI2dFB5KyhX5ZOMEb2etVxGVm4EgxNrGcpPyZ38OykbLV2VU7NmRMC
+AK2A8f9hyasPDSmFnVVLa046fPOCmoq6HFOVf68SXATIS9aP68IW2i24smMUYn3mV0J8w6UAIGV
SoRgEaNMH8I1RJsR7IK16zFu71qCdkTuD67LpknPhHyh4PhFmUyeZVXbPkj7YSVn+iA65i9Nq2Sx
WtfWtiy//6oFv0rx96K/LCzoK66sUBe+JXeVEWgDA3RWRkWTW8+Z5TxwEwP2kSI8B8IwhzHQ7UUv
jgXWiqPjnHVBPH6X7dqbpi+5dYAfl0vp/n31KBPAyCPQTIgdQZT1YnnoyOqHL9m9mWtk2FGcIwlS
yA7DY5EggdRydy8CRwFeHhTij5pH7NeqLXkgHdgry9EI3Z1iG6fTtirY9c99ptFiFiXZmHOMWBRp
uE77QpIaF2hAir8eAkP5Lb+82bZUQ5h6sKJ1a5jms07z0zHF6G0ogsVwgSls559DgEf9tyXkpUlX
jaVRLRuEeubCbGWbJL+zX+AlpogBxEF8h2x/YRLUErMFV4EaHKGc0LUl7TW35cO/FD+gs/7FhJ7G
DYPzXtTRN+UEVSj+m9VFfK7uqGSTT9fg9c7aeAJbNk3oDVSld4gpFxngOu7FbaPoE6doXa/vavRg
8sSgwxYZ+1X3hNohxbjsWJJKVR3BVPzdxrIRoLXCBW/faa0tXWX/MtxrAFu9rxE63PDea3CCUGP3
sEtPWub2VAfVT+Cp571s+rIRXcCb1xSpU6rraNjjMry3uGkOuXqeGfkqwmca5m4it+ztaVVy3fts
1vcEPJRankWGakQVtpn5YOvROPm14CQjbD5IvpwvmLVGZY8ltihZrNi54pwj9517R1R7MMyZYJNe
9yyHmU5IA/K/Dwu4u56uAAADM0GeckURPCP/ABkiayxpmWKh6TwAlqsmrW8q/8k5DSUYCDrmLiQD
IrAnp2NHLf+q4N2MvblIsn+FAPaYcr6N0ABeynPQbNwZBMei84N6e7P8XK+ve+QZqXGQZvaaLckZ
2jgKooK79okGCLE5xqZLoJWndUN932odimnTWsZ5k3DklYXgq+FEq9rjGawsJpTyxeObiIdVx+hj
7YD02GM/IUFBwSs+nvqUkLjiporAGzlDAJlKVKrycdPAT/jSxy93JvMCuqVAwPnOeEujAwMh7OOK
/Fq1UHNBFIm96JHsGQDnGrzqSm6DsSGWnZy+uIKJWq49h3Krfpjms1iAL/+G4zrfuH9tN2+4ySWb
NOnreWXhg8SFYU3ax0Wy3wWToYOAtIUBIN98bO/WFAjLj90Y8VBFRdguJJIGj1ungXuVjWBOouXc
FDycUA5Ub+CJrCrMaNcVgTxnBOuCYjzCFpc4aaph9HiQtOcLlAZosZWxUwzY0kWxDwA/P+6OHZeC
63fQ4T2DZNwQuCW42i0d5EVSwQRTIR1/qRQeVzLNC96KYFIwvzHI8Q8W8iL26Z5wMx72alfXGM08
cJtaV7dDpDQXB+HRxCOiQkqjQsan4RnjjTUSajtFyufhfeH7u5tIK2jeS1GJ22mVBATuPP+l+g8J
bVz+gd2IoZSVRTBx1ncvTILAuZ4aOIghLSQG6m2ufaIkt6DC/1iZZmsYHb8X7zuxHdAFdTbIBeR6
h0q9PwMUEAG2xwgv+k5E0ZjuVrukWNXUs0+8B7InkyZVIPd50K93gWYwmpGxoAMITznEK+zmyHfy
/xWWymBBkh6Rn9tl/HJ+KTF4OQHxNowxaNUFj9Mjr/MoxC+HgR2c6rfBdlhRATyZxRnO0YPAf0Is
SiAvEwbSPcAwTqxPkL1X0sCa8D5NRF3tC2gwjmzyvARxNK3TjVDnwZW9XiY/CPgAr+W/W4ds2guZ
HmaWo/w4+5VPy1HthTf6z5Z23ViDUeir4EKD/+7FnNmuo+mGffiWGWGkBep4T3Gu8tVz7kf9UH7r
D9cnbCDNKiTrpmro1FGOqKh4fBBft+Oe2sX5hVul0e3anv4U75VLCQAAAhYBnpF0R/8AJ8SK8AE7
W1RIqFhvMZ3vdgPSY3/T5CBaP0H1dgxmccEfqX+QJ/tfR483CL6UOYWk+ERjQqGDdwR5favc2w8B
eBmMTy9egAxCIKDXHGAYEdRMfJr0LAqrrySLbEBK3TsMO05B3t9OPN+0wWpENsPs9GXwrfa3NY1H
iLIK9k31tpNZ1fhMAcQ6hDmlY6+yw60+ZP67x65GFpbb1/GTD6KLqoog8JEfcdZxQ4s+D/RIO2l+
Vre6HHe1tfnw4hEFqBOzfYUvhyiqPbPG8oZrr/9N8OZ0UpMt8qP8Wcy0lePoRioBrbUYWZP+kzXh
zOU+qhw6eovrTaaC4FXU/3bxIYKQPo2xxjwksJIkhDkNlR6QhnlXoxf5gJHzGgAj5IzrkpaMuSl9
RNKVHJUiRe7KNwoEZbOOR6E8ZrrrLecOaUBQII8X23GtxVRzMk/OqTynoEpQuM/0MdRAPIgF2bk7
IWlWOHA7uvgcOrtYYdG0rW7tKTSRq0g0Y8beqbR/sPT3+ONif0Dy0AI2nBDx3cjN68pCe0xNa+K4
L+NlMgsRTqmHjFcJ/CDDKHSCSrQtiDCabw65jJXytEp7ymfqzLuSj5wdDSWEBhwtag7U6Z9D3hWY
xxQ9QQchv210JPTkGBnudoCTVTpyA8dHReYgqvu8uZRe/CXQAIfKer4g9BRSfHvdfAfxiSeo/2lc
ktVfrmX1vTAAAAIGAZ6Takf/ABhNBqsnFagAmqb4GH/quHJAA4wO9uvAHzCwf2TUTJQUgiuc6PIv
m07iZLlUzN7buTVv7357bVJXQF6vIgQ7991cufwCY8KvQ8JsDXk8yHva4In/xAQ+TzdpFyzMMFmm
urh2ajzbTcCUdw2DGD0+xZ89Gvd1n6o6Q6Q1/9nSArp63Kqmb3tNm9x6AoFbfwSgeQzYhkXioC5H
rydMgGnverGRHwxZKtgZnyyEFy3wOQKLRPAoBk2W58DwDmOTJthGfaVAiXv8DWOyU0EviEK3HYQ3
x+cK2k2EuIKqeXHIc50qNUFDO9P43nClF9mQpUoJV0n66QDTLkXHtBgeGK+IZdDk69AiM8AlyLkc
abcYUNMhuyaAFE16EIYiJ+aS2MYgUEab4ascXAcowyQJX6t4Sh+o5EVjkzU+1SkFDZYQWMK1y4hQ
cMrmDmAAKtGCljuao/1XXxgLzSUHQd1gS5pij9sO0G69ug4D6+eGUyJVOQsd3y1X7e82tTob8g6C
xll0SvebflzAjjYJTEr9tnzbLnYOvellN0stI2iDmmVArVPWQZxBGZkP4cxZMcNlQgQ+IH4Efkfl
pfbEe9Z1F27yuwjlcWn2t8E+VDamE0GnQGTfUI+5Az16Pdnjc+f9hSsxrbsKW8QtSKM+1+ePuGyH
Qare1SNtKIgC+kGi6ejrtUAAAARLQZqVSahBaJlMCFf//jhAALmkQ91NWX0AhHT5Ij7MJ8xZuGZL
3kcRHspkPwd1okxPdd234TR4y3nZ4br3NqgC6LKztZYK/hf93Jd8huLt42oXyzeP6q30IXWyySLQ
rM8kzXZy8bvzqqSwzzF2jsWqBL0VQejPoM9irX2hnMQZCZM/VKwNijigFILM3GqyDdEyFqdozih1
05yUZDrR311RBByydD0Pnq7T3PApv/XWYGncc26guyETA6IUifcJ+t+OuYS+sAIwO8PEkseATAPF
f4mD/Iy8B0AdtusZlTXoZQUpYINegVEkbrurrmcs79HXOIidbYdsjJkDIdUOqmmKhBDUMTUV0sSo
eB29uqI0ZnCHsKQkK2Ofzyk2m204p55DQRoORYjS8azXW6QZAAA0VvJ+oKnopPpSOHtEObCr2ydu
CKN9Wq7mASYW0UJsSgPr8LHcD/7f3O1IkbceRIIwmxWhzQ5FxAXyDu+9TihGIROk2aaKYmrQkZ/I
y3ZnwVk+oK7mYlzjr6sY3thNTW/HGKYsK5EVlF6Kqyl0FNUSa6i08dPMuycgbf1yKgxpcdc7vUeD
vdrRMGUVds/rlD1X7p4nOXWBT01CGx95k1nch2B+WoXLNKn8pZBL+nDzbGdLdjPHPtEYFHj4H8XY
xO0GPJc46O86trD/vDIVU9eZzdKbiB9eU002HCuk0dWbd7zT5XwzK9RQnk+7Bx2aP/xZzRq5wgVm
uW55UeGWq2LnLmX8POfuokybIWBAX4Lgj6CXpijNSn6HhJkjg+jC3NGhlsAvnz/atI5VhAIDxuYt
NTwEibf4ZBH/SCGsfn2tflCBW0iSQMA2UP66fqlI0sO61RSN7vY3MhZORIB1sA3NYrO950ay3625
SC4mvznxwAXoNE8K3bYbId6m7ruzSnp2vN9qYKIikvnQNfU/czQ+cJJrc+1rRfUCcatjM3qlGwm4
QmyLUUo2tIA4P1wlanKDlvGJuWxbSKj9II0hFgG5/GgxAt86MNAFVRtBF81mOnYq3EzptBcvGoQH
apZGzld5jUTrAXht3mIER0ev5Eg1V33SRFREf26Ah5NC1Rr6mJx2qPCOMxmkiTy/PRNVr8JGZmr7
03SUjgp7PR8eWVHcMCs2H2r9+SrnykXge+OIZi2El1ShZbeKau+W70YaOARbsailmkUmA7JXF4ir
ySfn1kLpujXihbRdX4pT4Swd4pmtx2zUtCtN9K++YZLWKtPsULFkVXoIb4rn0/22enZLwhE7wiPy
OlcPe0A1kdwf/Pl/aJ3impSmH47eU6ab6a1N5DGEZeZXRQ8AeBTbwXi5rbDgx07FHn69X47xWNz3
Qw3R4EtmI+Pu7yPZDW4oLLn+baxFR47MMJxf1LzxOVJ/DuRs7zwAYm2RddgnvpiDT0OkVXqAoLpo
TmaHA4+mDBK9leAsSl4PVAjVgUK8/s23liwaOz28ot+oWo7k6QAABGdBmrZJ4QpSZTAhX/44QAC5
oyX1FQAE444GTRIjGH5Bn1rhgLRbsRVr3RJ/CSIGzGk3iWxJhcanUzkiBSdcmjWq9lSbNQzv9BUj
sZLnPxsaDTbQOCGthdzpD8wvfBMFUTr+yqtbFTWT2R2IONLpeBJhLYhd6UkGpZqN1uldHgChZH0U
C6fs5GcVMvXK0o9MniQXk/thF0JVtaQbJKR65rliFFyqPlb3ocVzrJ3EbyIbNeVpnmRW9NAcsabk
Nttxo1HDEVuTM4fZHreulbISXYb1tbLbw1OXasdGok1gHN8ENXLQs8uwNO76zI8i2U0WHPg17gUI
2OXpiF14wqDEGCEc3Wp5gD5njqu5mXF0CN4XOufOzNOm7PGLM2tuAE5hSk9CiDx44/jc7dMwifaI
PPDwgFJDojDBbiTPBwyPBcE4v0Ai6Is6WK7oProAmgrWLL0BonBr2S32Q447SJwY2KLZdUtuJSbE
jmXKAqz5pj+rr3dA/dGuXdvkA+nK8d4kvOiJMY2YKzBp43a0KUrcblcDifamRiuHyf3a5FTlFM6l
A2AuZaf+g/MwsHnTyGB3aU7S1Tkv4UIb3igEoocJRaCpKlcXki/hQTz5mk5O+CdT1Y68CWR/vRse
lccm5o3R1/I19HJR91Q12MSeFGDwoq8DYOzNvyirP+TjoM4zZAAsvBF9foIZtCLqDBrk58R1vfQN
qjjkE/8L1FB3znLv6MUjR2QLuVSiWC906PMFVrjT6hesDw6tpdKGfkbWpQFGys9boSzAW4p9HyQH
y42M/a+5IB4NWisPvDYxHeADcwIdkvgN2XiN9qbDU1HOivDXQtKcKkWmXx6wue1YS01unSbQiD3f
wzUigb5yxHabhMA7zSgpjDQiJjIsav/dstliilBkYuT2oHgDaXxobIEfvxLB/6qWbO6PAHjYvazP
MYKBDUZx4lMzPzAVgBhHJyY5Gj4V0ChiJBKQh+vnTkAkw0I9FLvQ1h+bahUYHzcP8MWuHZFsdS6g
xpJggt0vtU8iKyBdJetdy0hrTnyCEAJ5JtYtJWGW19E4DNf3lWG1Ggc6ANdu9ylmIdXttMxMB3sJ
wF+NGfI7jFZujW5ZzuzhC3zM7vHi0AIYdCxCxGKcYClSFhw+S0unfl4cB05NHxFz2fV+QJqNBex5
RXrJKCZorEFu5zccrkrmVKiny5/zJoYcqoiqv0MQ26KhjyG8jdeS3YVHcqkQNK3/n7dv/xZ06dyy
tJUQZ07P1bINUU+ix+W166FbGWT5/mA0VE2+CRAhJeZ+09QkhZdVzFxgeIMrMA+ricoz7yYBFwd5
+i0RoHec3kO7AQtt7HNDUFcFqp3VXEePAU08mSTeUnQ89z9BMkVVkaSLAfjxjtKXzMYHwPizHBDC
n+lEjx9pGkrWBqVUM0TRerpTNW2g4NI2rOfK2bZZqeusJN8GteaWA2sQ21q6NF5jtudMINEQT2xm
ZFhfZSHZ6xcfGEG1nDuL5WgSntirbk1X1xEZgAAABIpBmtdJ4Q6JlMCF//6MsAFJw/GlHcVBIFk0
JchdvySAWl1/GAT/tvsz6QvQ+I8XSFvgcxeUy4bjvcr5g2ZFSGmkqIDBJ/Y7Z033+4SqDrY3puW9
CIZEzgn/wEJ03JUTEg6KYleNj3aben04iueMGu8p982ST0UShJBLhQ8CFP34ZqKSW5f+k8sD56da
Yc2JCMyWi7qZcqwFXhldulKs5mHqrx+LetqTizP0U+8tkC6lHsHZ+MXuZ241vx0sPsrtyAWUIrBq
yqga34kFgLIp/UtPDzGtFlbTG/T/ctRDXsWgt9HyIueWT35HFMIvtAJL4v95+K7S7UMsraFarIBc
lRqrOkCynGv2zz6u8xZ/ZVhx8D68pEahh9357r+KkAbYWedIFWnVQVeCmDTaUr+ZvO6YoZG5oRMU
ZG23CRwfKYtxSpBEpQ4GuDLRI1N5UEDbbO8seU1Dyk5Hh37fRdQv4NATcK/hmT1pocHtZXwXKMRC
77S19WTTZIagTaOh332Y7r8wdwR8inm/hWbckBE7FIlsrnBUeERSVbBlnlZGfzPuO1J3o+62+eCF
Qnf7UNXLy5bU7HZVPHuqsyMCe5pP34yNJHTfrxMjZNTbyl/1BEX2wgZnGoaw0bWIhxSqnhUdoJ+i
SLdReiRYpGJTWEBi5wJc6FNdL3GZTmtsWKCHBrjrYL6Vr9bI7XBIf1TrjhwdxVoeM45h4X+ipSb4
5WfGhrvLWZjfP6BsDTG2VeNpfy3m+gKgCZVd1xFD6NkZt0iYO3CPled6iQmRyJeXXRlHzXrLVfsQ
HVjOphP8MLXovJKL24xbk5kXVAlwzFVO2LGkuOzUzzBEO8C7tPtRhbdg/hRbPOlqKFwdPjxcU8zv
McQN2R798YXMuiYWMyHsBxGeqwAwOX0pFlcIm4tM4NDouSTNWr5jC1NKTSxn4pDHtK3nbct4CYZ5
n54EDd8tIgME9ODyoer/6dSxQH1QvlXn3mm2VJGsW4i0fUL8usuxa65KWu3Ms/rbu85JuYGr1OWR
juW4FcXBN8NzsXLm2KMi2t9mAO5pqYlX6G1evMapY7d2m0XQcOkGMPLC+Cv8l+2KPTUH9qycN+B6
5IFZyhtYFZVaU4IOf7094WM8TJx3zw10/W5xQw8A5167NnDGjkY7j79YM3UXkzFVNmBrKKDENhcE
6Np7YtXcyP4csQPFvX3TUn4co2rsbl976hv4472sUi4HutlST85XH8Lv7mHx0SSdUwQol1yCEgYu
u+xLvUpw/RbSupZi4gKeNOT7hpl6SWa7tmIMnCFhfirxovAC9W9kKKyyHtcOywmD29sCcYNEqGRv
vfWSLTyYRFYh28MvmbhMR8o5PsadkbHJKXGTgwG1heRnSW+pChYuDlUgKtuNmlvclEYpoZzQEdY0
2DtQO9VjXSDfBOmU4fbJ2aHTmeZCeiYJgiqRhlOzxLa9zRiuxiWLgYw6i6Yy0LyEW/rz5Vx5VSBd
ouLkuaOyjSCRci3zh7aTCiFx99Y6T9UT3P+Sak1m//UadzvR526nMNPPAsAkS49MZqoWirm5AAAE
eEGa+EnhDyZTAhn//p4QAB0O8Hx2bgBUN+F3tSJxsf6CyGyq8V0uA3qDqzOILU4FAdC3eQU4Q3Jy
Fzaxzpav9sQ2VH15GfzhR0+kokUQzMzhre5KqvKjYsoJujDcTVnRNz3n3pypOoZdQN2NJET5Lq3S
kHGH2iBHn54OxscP39jGc2H/Y7N/BN19m4mDMjlCefr57jOGwaDcJgUebbLDR8pa/K3bchzkjJ/F
3xwO2b7Y7NxxdPOhIHv+Qypq9WAghXKqMMfev0frchRRnDP8aozaE9KvEMyB03aK1c2hkyXy5+ZA
OM4FzKcrCLSIHQ135ThFRgPwoN33DdMVZCBxvVlYX8V+DLtgoq95nbKYkZcA4irsg3EB+cGdVtYe
BCggQQcrzzTzWjEupWF5XBncAv4kltMqV9abvKGAbv6NXVmr1Nk17G/bHt/HzEmIDxjw6PjzVRDw
cL7zRsYvt5KB3X7df774xXTLi3ALc7roMhHijXOSgl7pWw6Jud4dTqmaKcoOhYjEmWV5zkhJkxXQ
B43Mai2oEKaSIkM7bj9L5nyV9CUV987ZeHC1QoqiA1ExS+hfyqfatVVjUmsKH+F0RBBIL3O+MbSc
46wioYXVZ3yCwYl3M1Ga7/TMKVHHg4Ph34Ah/sg521jJe2zZWKzpy45vmkEmrUSXBe9+cvnkPeK4
mSn6bkhStl0eiQ0kj+lVN3yu1N76oGkPoED6GDfZZi52yCfzT0dxQE6BQkUmWZZCXPGywYvjHHJ5
Dusgb0mhcvEaz1D2jL1e7QWN60mQrfJeGr+C8VduYo4cwzylzXCtkHahN2dVOGvZx+9d8Q0XIimq
spU6V/dD/wu9k/6s1++kVTkIs7GrsZuQl/1KuGBLRFSH268+deVJ7xcSj2Miz/taGe91FZg0MuWf
KQOJhgg8/INXyHjjnXo9+Vzbwvr4Icvpgq+7DCVCYjeDSWZgNrfvS1oH+PFbLnZqO5PTmULcg0mD
hCeV+4Y5BdsvhFIZRga0Jy9NB8rGZl50B/xaaRAqwfvDgS3YS8unD38OfxqcJvgNVG/5Rfou0duG
pmsFBywAo6OLK1RvaOV3LPemYWGxent11cV6PBYBaafo28lVIk4rbj2Vbclm2914SmrQ71YwNJzs
scDjq3s5l85r+pYhkS813GgdjWG9wIouVJjka4MQuax0peYVONOQtIANSHK3RYMNZWNMDcplNUEx
/L/CcmBC4su1SEBGAJu7U9FZgc7tCfsdaEbUBdrnFkS59whmjkfc52An3DtC0B5YU8GBTAZI3SJU
WAd+tQtq/TXurwDHLmHYr2dVzuKgTAjvfcqsIzBCs4UiZz45fVDotDw3jjRUZsLTaALnFrV7l54u
nwRGSMEX+1QFeKOg0LRAnq/MjJ+lp32GhpolDkXfP9J4+2W3kkHAracV6R8Imz/TIA9nYxRKibWe
Df+BFhCp6J0Rzm6DAfb7/4zBEDgWVwqc0oRwD2DfK2INoJSBHc8uNhEDJ2CKB8A5XZF4byJZPjjw
55f+ZOEAAAdwQZscSeEPJlMCGf/+nhAAHRQjkzTgABpQHZWi7N3S3knCwrhDaKEtaQch+aqZn/MC
Xa53P0nW8B0QryqOtlPZGkt6T91SBQLPX6cZ8mqyDJ0b9ji+8+j2DGKFjefG+SZj0on1xHDSqQTY
pslJ/qy8jKLL3jMmCdCwkxatl7TSFCss7Ypv4YFl4CCVncl/eRBee/tY1AkA7KlC2SD5VHbiMN9k
msHGWALvj12CimZ7k9cbE76vhuwM3sT1DF6Zgp/NzLvi/+LoUQl3RoTQA0GsBkD3n5Ao20Whpivl
ch6GhxmAPMNrt2y1VPuwAHtl+zyhF3sU4pKmMKCW2ANvgRG2IAC1WjYq77SzhxdXSKCJdGB8ocvs
XjMbmSdPz3RPBrgS0FCeAEzJ44tPuUab/hxZpmhMmBhwJdem7laHH2ViqcVsVJo5j3SZ7Lf3Edu2
A/8wakXcMQ978W0C9OJKtVsO4AEkrWd/hXmKZgOxiPsu4ybwK8kCD1ozqtsYRzabGlfKAKtClNn7
w8WshVSOZ2+m2oI30nOdNhnspBTedEsX6ko7AC5/2KK5rQ4vKQ6utG4K1jBEIaOcoTHDe487u4xs
5/7x9kwzVRdP46tVGl0VNZMcyVMYxSuhlXGKXOXUfx285kQhqdbJPCcYZvP9Sco9sIpYC19KyNhQ
zQw2INlt7wBz6a9W5mt/iEQ5l4khibGvl7Z8Gw/QxZLpET371gT0Z3QhwQmVZcosgOkYRbrpjyZQ
y/z+QdNc2PqpRmMCssmplJGm26BgTBlF2rOBvs5WvI6pwqyyRVFlR/225hunhqF6WNlopYExQjwV
YVSXtyLyU9aCbCCwtw6kToVITO1nqBuvSU/XBhCMDfsKztV4IYvqcAVZCFf98eEVBZWqz86khtCE
lRh56NgIO7v4wj9phEbrStD2ww6lbShIJmloPvgVA3JfC8v2M/4s7KG/9bdsgXDtQDwynoOymNNY
gIrrg2plKjcZCjP+xgic6pfR6zecOB3EQ3TvuaY2xtrH5+qFU3/QQS1VzMHkaQuYG4L/rs7bIol4
WME/UkpPJKA7C+u8wA4SeSCpy4A+A6H82jznj4eTBcpl7M0Q177yQPwjJdNzC2uonDFGgmmpQc1q
BFHXlMtxeeQ8TZF0LZez2MNfp+RIsr6xl/veNCpJ1LvqwRDVkwCzdkS3a9A0+imoATIrv8lVjkDC
qrzmfrykjMtjRmtDDjvxZV1n6K51F6C99wzrFRyUDuHSeMFjV4pa9PA3rvO3dIhooSTtFk3Nhokv
o37vdLNe4AUi0wpeFea9K/LXAqNZfh1Hy7g4+ZzhReWELJgsEB5TUlVB3FFXFffzgUkyoOGx9TX1
RRa74sYewjbiKQEFUzvMeuD0JLwDGmKNJM103z8y/nWIWIT9NW3NGELLLrOyEEATFuf6T7FeIxPp
UQ3HSnWlzyYTFJzOMOi5ys29yoGhkHo4gELNUfVObLgF8vQjJAKzJvVOmujGKC4U/3VK363qyW11
Hk7gguy+XqU0EgKDzhoyRdsmGz7nOoZ6miuocVXlIUAno+qL3TEczCzEUo4hSGoPM8VyrmGOC6n2
JhrZrMzSpA2Lj0bCPuoEs9lOO+ywQHnYJnFjcH4+VJgXNvtMbVPG1TZqGrD7ovgcz+SoOW4pl1Fa
DWB1MMXZDTYAV1eFQKeny5ZmQbMjixE9IXoUTW+41Ej6n9AUN2ov5OdM1OorBAsVMkSFrSr7jKVu
GvhVSO1hBzwXXpCQrq8DGNqmyZXolOjROzHhbfINNoME8o3eAfqwtBewBYr3fRiZNjz4EbxoAR7i
hOju7sNCXlKM3Bg+pM+wO2OC2K6cVgbFiqMseGbNwMyzclf4WZGYvJmYZB/59WEfgRjuwMovPXDr
0XlUSDzNpMYhkmjNug5K8og/9TMEuQKg+BZVcbrzqlLWf+CcZ3qk04i6hjqxmOjDnRK9CBAwtuAy
/UuNAQpOf5odanAs9n3r+31HejE7ZJ/iz8prg+L54qBc9bj+thGYdsoI0Wd1+zEPoxnvnP3XHqqV
jqLN5X5xeeh9sPqdDYtBzgZozK7BxN5bMfwzo7IMqtR+tcSW6X/OCRLCOiV8ZD7vENnGpuGRpM8c
PipmVNHLnKIRVkXD/Sy7uUNc3uu3i8MXuZrhXiJNtPcGz+Ok9slxlSLZwivHbz1jiyfvvQ38yewg
CvbMX0TmkQ1RC0oHCfh2bYioaiFcPTjpXkn381tT9hCgmJJ2GYUm5Le3fOy3PE02PMtD1F6IDIi0
cmW5Wd3RDcoo7MdnrFtcJCTr+tXBgaZKtCyMcR7tWxhe7H2CoYCC7ZIByEQNbSzs4Bt+v2zH/FH5
a4J0KnHlfor71VByXGip5TEvRlTGED3tlofF9EXrEC5kVVkQWXcP81TBP5OkYWFym5ovODh/hAxu
QWliT8iPflsJd6+zD/ELU4/8+pepJRhgmc6kNeEXLHJAnGfMDUHehQxIukfSsUYVLv22ydM1v4Eo
WMldOoDPuM1kOLs6foyPgajxVAL0l6iZ97E22P2EuMEAAALMQZ86RRE8I/8ACWwDcBqUloGyrpCA
uFTSQAS1ZDkgnP9VZJp/v3p0MvpT+uWJMHrvmcd/eDoM3rrW0a7AUON+tYBfV2qNQzsiAhGDAW4t
2Yi0bXxcqIBODDFtjjepUgA6DmY2RW0CCchwWDCaiFIc8ASODm7hjVCXQ/OX2M5mOAax5BK1s6He
2YMYLpMhhDQxNDj/hjd8GLL4kAL3WkAS04N4dcQIQaEBQY3bEs89Pqzywn3bZApA3fX2thSwplPJ
i1iggoW042Zv2iag3k0iv2isjiwF8OES2qaOaWy/77O7jIFw3cIrHjQsnEa2pwYlrlLFsx5bx8xj
ucUWkEaK1qE2wM5sXzaEl+PLzlk3FIKVq4ihSfBGUcVMj+RXScGqpZ86pLCBCyBM2yRV/2NQ0o0J
kYNlTTLvpwdHMuZwtFBPiy/rwsamkg/3au/GVv3A9BMjJ3vCC6pbIglzM4Tl3TlQowaM3SC8rnly
FU+/XZAy+weoJjR2VwiTWoLSLAKu8xg6jKPiKMHrIzdYCsC+pGzLt+9l8i+4DflTwvA8sUY4jyoJ
Y7r/MUDKerySB8znO8+J1t9w5sHAJeQ9VOktZ+R63uFfGCf1TKtywi/7lXLwi48WYkrPGZoS+Qwf
/TdzRPiNXABfBcTZ0+QJDPw9Bj0k+AuDQZbjaFh08jPQwJf8Scs33A25e2HhFiwVAS8MQLeppQzZ
ghJD6IacMlwX0+Cep3j3Ad04tgDw4v//HBCi6pl8bZP/LX8GvLWvdJjKftJTqDO7j1OnV3t81C4T
4p72dwVp9xMJpNHi6VhDma+quzqwfnIg8qHFXPVYCBX/DfYLz5Ra39H1aUhxssfU+oA02c8bqhYf
JKNUhNcO+hdJMNlj/+qtK7RUK4uOXPcaPnuj6fM3F/nCAHKXS3+e/P6mrnkKfPrJOcaRxi0JZMp2
Lk6b/7s7bk/saYUAAAG+AZ9ZdEf/AA7UPs/KF2tFlRgAAfztIr7UDJwAvZrIcQ1Fqs006WAN1qPv
cjDjMW1TN2NwkG3fhJAoTI8wFweMrfWVyXIcFeYy6stJ1AlGlPifXlVR0mL6akFWqX2iOI7AfV76
gLjqTxqcJ3bODOWMKbia4oLEp9BpmWDykRo3Hyd33Tjl6jLAQlt6F43mvc+/ceOXxlwvxS44HzkI
tvfPA6F7GudlCbQ5n9oH5shNjBAWAw9xLbO7q8kCYvkNhDER/A7lttNC1+/O/hez/MXROCfW4Lda
JQGNPJVvJXvNTgHwT1GNu3zPOPcWiAlBaMqbmV5MZsRcjlZXUvpbhJCrxe8FjtE7FgZcEmmuTImm
QCXLiBB6mnKnGoamNl/Tn7RJXxZpZwglXjkh+IJa4zfwatqJG1lCkx0fPBZ3OdmLpwY+WZGAyyyw
sDWHW7Z6kC5g83ksAmon8SWJC7+xc2CYnJPmOgkOBsynkAAeyOW2g6i5p9ZFj5cTKbINQg5PakBI
Wx2UxnTlMJkOjxLOsMahOx1LLKmGpxNOO/kDgzISqHldavi/nXib8y4K3wkcC5XS5AyCIod5qRPj
nJ0XzIAAAAHhAZ9bakf/AA5XjiKUp9Pe5hwWuTiwATttg8K65qUcCnMNql3MxMmq8u+cl1Kdhw+F
LeBqxrpFm3vTnrI2Bc+rlOtVr+FkZXu7IuTRWhne9YVhqTqi+3ssG40qIezRaiHxoAHQXq4xTi4F
u+Au7EvZtD3Wbri/kURKxUfsHsltQ3NhQ5g7OIGkiftFUlb74huqMSIe2GJyBlxUGHIkp4u4Rmu/
3XT70uLsK2IxtufIizkqfldYJ2fBHFGwDNS8aDlf834T9MSIbR/90CpJcbcZdN4owKNk5W0AImFR
DAwSYFKjyOHHp7hOI7awECDW1wNZRjtiqEcesg2dY/RNEINwi1nMZ33cpvqa+U3Zhy7gGNezBMna
QlWIBdOGC7qI9CgxF2z9HeZY1mpTKg2L4Heg18wTtPaIydBWV+5fCMViygFrVi30Ld2x3b5jup6g
Hfhff4NrdwBRkD6GM1lRCGYj6Rt1EbrgwtNaMEQwAZaONuthsu358R/TpHlupPgRr4/8St/aqx+s
5wId63Lah7eVK/io/8KXqrXR+p1wXfh0q4LGU+fRqv9ASeb+1+U1cqu0eiBbo0prKkXBOSpj6yJy
WX/2SOZjDsqpXs0J5+GoyuvBuuGUyWV6wqGrz6IPWI7vuQAABshBm0BJqEFomUwIX//+jLAAHRiD
lGWCEAkDSsF8XSYExQC4XYSDHtrVzADLDI8/qRelu0LKYwjfonRliUyCYeynAFLFu2XNTsFOgaHC
5kiwhkviWI6O2H/crJeEKUyTsBT9CnTM8gmO+7UukC+lz0cSuFeQklV7hYF//+usckhkdk9McKw8
GlJT0Q1vU2jW12xqHPfGfn6zgMcdV3fcNDvexshhD9UEbWq5xybQnkdiMo+MIj8LKs70ezB2fZ3L
6Cqtqe+91pdSZvE0XHv98vFJlg5kBk+qZSE5nXOw+g2gqQayjCr8V/cIHRcLxHu7AGHMsoH8R6kz
kwf6OLLfh/im/AypSN2Wzimy2hHpDOYH7sHxPParGkwjwgmdBE6Xfo03E6FVWYfdgk75YwGS5V1b
5qlM+8JBD6TFxA2RzS2QHkwQ3CzsUrJZkNWcsbMFHacdK/YKpLPKNYXIIZuW1ouZTPnQPy9yM3sw
SCIIC+ZfBTAz2Rxu7WEbD38EVrVpBu2Rlaws22m2A2vrd8o4ugtql7w/NbRFuoXHnywpiOkZytGr
pqPsbFKaJ0m6K6AtKvSWu1Zg0bhsTUR1tPUuxmg+Iflu/81Bwr54LvvbQhkrNV3YTwj6eB7XprAg
xFWMW3V6sbXB5Vkysj4XzS0BgVXhBbVUSujhKCnefJjrw1APCHN2jF2N6rJaHjtPHhUBrPSvaSBf
yup2QwI1Fp1aUk0MYTSmM78wczEzxBmLfjbH6IAgq/pBsRuUMVmgeIDDsN2P34fOVfFSGTuzL5El
jCs2jCtEB8c6BVemxX0kzYvc1yucPOA5NW5yJkMZO26S3peNvVVUBJib/YYsRKdlupv+53+nTTw3
czh3TNUkqTY7yUtDr9oQLiPDaHUk9kvDTH+T4bCejqfbKNbBjpmoZYkYMClqGgydgRH2x5X6N2tm
x0z/9+SrUre1IsdUaksk69z6LJt6hP6kwqBA3GCtlDt9WfETUtf+SRziyr3EL8UQw4XbnDTGmpJu
Lmny4AGOr7kJb2MNkbLs6daWVeGBtQq/QU9gjN+puGOr5iqlEbBe+UsrnzYEAtZ2ZES0McgUgYbe
OqRddzIqiDM1ABKZ9RvfK9f9bxn2TSp/bQqhn31XX/pa1JSllRWNp1fsUgsSE8sduHHfWD0ojqoL
NA98l9v0HHOpZJf3tPEzRHlO/+COcXrvKc7h8qlQRTwIHeTQIHdCLq7hOr3cv40fDHdjUTXJNgHZ
tLoCr09yeTDIZy7dhsnSrsIq8KDskDQ3e4oTgv3oWa8oC1rK/RS5J9jhsZPm6qCw/aLgG7EwACG9
L2vfxQ/JbrlQdTjWmfpipbryOwSRgDtczXpI5sryGQwfzRIUD9wJ++GCgOsRpIv1WYddK9V8FemO
zzdU/QvYH7IUtAlCbvGRiKIggGTUS9L4xUYmq8tLRnpVCjc93wFLiRtheBoxuFc9Ib0WG321KYz3
9LOb/wSTSAX5eqI6nc6OcsujYhbJRSmlMgs8SxvYX8tjdPdwBWpgtyBn22ckgs7v2qBf2R59Qe14
Gm7LzYPXDkS6eDgUptlbg7X34zT85UuuKBScB8Y1Oz/FF2Zw/VzA6wTxgqiYnsVkUqHfEvuAkzjf
WRCB+HmW7ttzEeayDWbf//Cdx598tSUbGEZoCXw3w0Ip5bot1arYsrSkyrSj+g9J0wEOdVZp8wq1
ik4EpHyxBiCYdDu5dGNjAo0GYSmOj2HIJnhwDcGidKwtH6T5PT9cu+my7Ia3XzL3FWnAAX5cWejR
YTu/pFFiYIoDGdOysUDGab3bNX+SVTFpDaEBG22AMwEZnGQM3q25uGGyrSXJFYpFVxZrMGntINq0
f4nEjbVTevHnHq7uEZGHU61BlfpIsQC9QR4n1FQpNa3qn9IZf7i0oCwxDeMDq431iU+drcIystoR
pQRTBzUfQW7kQvYwp3R+zJlKBMUZO3szRWNejCBQDSUkOB3cKNjT0SD2Hrnm9knUSpOqszJI3/3O
F6S427qcdjV970bL+CsPNepFQ180aCnBDnjp4ynLeptPt3apl6XUA3kKiP1mvrEp9qhZ8lsf+slP
yitE2KFPA3I/kWWaKwY+PH/et0r8DxaDMvVTUKk6o61ylkz4MUTsj/cS+cf2JVHNY97Nw57oyO9W
4Lxkhc4cGAZCDYXtdXGuVU2uhSTQrFDduvJ6Bs/U62ac68gCSuRyGlZP1O/QJvLNcUDoq15q5c5i
htTOVLgY/Xj6N3ttW6ByI/BUz2tF4tbzqS8ojJUmdJ5kgx+CBal/86shpCLzrX+/RFWQrCBLHA1b
4NRIwBemYQAAAnNBn35FESwj/wADiiakACIOqXvIfDB9loyHZZRlVtY0WGYDA2HnOqVxnOjBI+E6
97j7fsVejhbsWfXKpzUxkXnj5UAUf3hZM2xeqp5M/bkcgik7ynNuyxGwjZAMl790+EZUM5vCXfxT
gjdq600RZcNxz2BaQEtrP1AEyc3xKByhAN/m+evRN2vvEusoMcNdDmu6Hf7JqO4WBv8JHrgJdgaY
VVer5XQ75u4E0nexrT7DS/34P5t0Fa2pzvej1m09Ymmbltor3szsmFpmJqpVJIdCPbhNcRV0vGl3
jtJ9dW3sXbh7qU04ZDljk/PQjaw8UIzsgMR7jkyohWV0UQHUOeVaVQmK/YiqM+/L7mdi5Bqao5J6
2XLIFbFPkoqmNOSaCYco2T7FLUgMu3Nr2rohvxRtz18KbUEwTw+FBGY0tszRqVJAZQ6vQHUzCTVy
6q3AB4t9rEOGWac5p6L3TVxtw9HzgtbKuDiYTpSQRGT1jN6Dx9FXALxEZqWrJ0wzkvusEn+Bbc45
HfxBxvOlR5Vw4Bq9aI3UlgO5rXeMGhxbuMIzKwTsHjOmwFLRM+YB0+2OTN75pRzfpQPX/2++a4e8
kNv/Cs6vPLCZ+xM+WM4quqwGJLGd3pjM7ERY+eWzcTojAFlPeCuGA6W64j3q1hG+NUV4bil//X/2
97awLhL8NZFgjOZsWY4RXonsmF1TORFn6EWWri9jV8mLLtwPH0u9UwNKGahyrwhCBAxiX0MZ+RjR
zPwD98qynYBv2rN+MthBXVYVSby6zdvgGGdf0EbOYXJ/tJ1cEeUqrzRC5PrBrJnfUPV/Wfe4+1td
4nfg+nrSolXeqkAAAAHVAZ+ddEf/AAWoc/mgAmqwnj/xmjSu4DzmaLj/LSFPvwITnWw+9t+nSCV1
dhhT8McG4PDdnkOjFK91Ft4rQrHSWYd9Y109sD7gKv7B8HO0qSTc3+1b5mDzVL0tHys86WLiMbSR
nX1JQ78PCZ4vbZtv2HHFGD1f5sHP03iYk9XXRgwiLTrnWHERL+6/h+Pj/iSJOSSJ7BdI9Un9KDRe
y7DZSaCUOr6jy1IpTC7EYplQY+3PditPa0Hr6ZLSTMb2LWn/LSIE7L9KV/goLDztf0hI9Q9aTaMD
w9NNeAYBfmPrUCUiGlFQdyfiuoawEbPXEymm8o5Ok7xDiHqVZWO/3wwbNlhd1iX9KsDei3NVo2SS
PuD4sD7MAt8b6uRGZZ7qJXKCa/SIyFrczXBV4pVg2cKa/4jCkMZ5TG9N1emmmeyUQ5drMYH791Nw
ZmJ7Zy8ZZF873ofd116lQYDF4KPASptZ8yWf+DolzUHEopWB48QWK0HLc3gNtxbEupdMuYgsldjr
q37rQd6/eoiwj3aVC/Co5kjgHraktYcSMOGXHknK3uvB2/TfooRRtZM39xT8j5km5lKaW/ILaouK
XivQnBHMKUnwAfBmGfNC04Sug0jeyEDkEYe5qwAAAZ8Bn59qR/8ABa0wEOozL8MeT0ZmQAC0XzCu
gv6hbNenHZmhnbC3snkyGbCsEJ31vmUz0kDiS7H3eURq20IK+H2qLZSq8oW2QKzWk5hokeRw9bNQ
Zp+JSsbqUUxdUnKhdxc6zvyYGo9P1GqkxeS3jGCZ+F5qjMsGwUF89UyNIjfdUvhlaH+AVSdmJzc1
JoxvJRubVMLqmPRcBs0BPcGlnOQf0yFXY2s0Ua+YeXS4n+2DSI3FTciO7hulE0RLf2/CQjy9FC5O
+kEnBfUaUMbfH8U2e8vNjMcpCEyKhgKw38ei5sv/2fGvmGeS+34rV36KeHEZgaUJwobO2h66yKRn
U6jqdHBmmMmBB7QrHpdOkYF1xrn9MRTclarcCczBhIsGD1IpXoUwt57stHICcdZSKHTzEuhG6Kgk
a6ozQ5KKHk9h33QdSrNWVrIdqmiP4vXcJbS2rWZjytroj6l1HUkzPiwrEAOFnWoejnsmau19eoPi
kXypkHZ/5XQ6St4IgiK0znlFoOqY9ENY5IcD0wXewf3R1VWre2OOCo/8ESZ6cADxAAAGukGbhEmo
QWyZTAhf//6MsAAGzciacYthKqh3SwCNHASynyAYM4OH7CNfYg3L2G9p10hujt3ysy82eoud/9VD
hj0/9Wpykf8zXZaHy7VZDW8Hx8Gwkx8m0syhNxmzTQFfNK5wr49kGLX5O8W71nzwsFjqCYM73fx3
IBduS29FY7TzzQfr7aX/llnsbdNPRNhuUwGcVq53kLl9262tgVhzZvVPjV/p/R4Mo8hVIa+WYQu9
jT5WDzmIViUOyCvryg87+IMr41JYrJqBZ0aHfr991FsTaNGG3MTSRhCxoX4r1/mdGosm507rCsFN
oeh25dLldCD1E37MIag1hKPwR/4v7/MjXy2c72OkzWAeqFpt3RQ7dFYolJ5fM/bErYPeLZWgGOwt
oqr5Q2GiYvAbWRXX9a2qrGpeo87oDcj373po+I2fU8o1TvI4HGNuArsMEWSmCwm9pz1z4OwbFnjq
bOZi3tYA/v12Q2Juo3eD+fSsrWiQxPrye6OmQuSqw9Sb/CeFMgup2UwXhRPZZJPIJqcWM458e/Uk
dgMHeI4Qhg7OQA9Skcv5fNI3vFGRE/WuNyr8OHrTktNsq0lifONiclS/+WnAHfxNe5S+ywAim8eO
NCcQ3gJ/J3FdSCpIvVEb8S0kIg6meaJqkvCs0bAhWU/CfGeQ5dP3ObZhOGI9NA7Ba71EQiVIqAyF
nf4Xv1K0mmiwP9OyHduSILYYX5Vb+cyXWPG4vlxGr/Eh+NvO0WpGqNa+3C+6wKsMQTa3iJt/NepC
kEckmlquE91IoAeEXdkUDBxTlFTt/Z8zR9tNhi54e/7JNHHjcTZOsEaEuEhuPqBk6PjUZ5uuCCgf
v+wPmIF49VfQU7XEW6wDW1g1CsdaAHgu6zm9mbeKaeJZ39ueNl+ECN0bBeqxs8POTxqWo0CDEH12
I85lh+haOXBKgWPVOJyZ3H1bmBp3m4dI1OWfie/wxArJ1trx1H3LuwrX5gjwcPpCQ9n1eYIXpnEC
i1nmz6XwbI+ZdEc9HW/kbTHmagPJxId2KvFBHw1GgXknvzNXttccNzB+ReLG8oIsf70OTZrTCMR/
CxGl1pzifkanTaRL3RstUU798FrGD6GFXoWGKy2JD0hZTDKm8zYmUEakFfskAfBC9NedIpMCmawS
PWpcRnA6YXP/csfScQgjf1yBmqzj0lR6vXRWOJfowiZmx/zNhXzJT1JqYHR27TzWZi9dU/K0x3vT
/yMxmFwqB3t3plx6LGSW7Rr7Jc7Z36CyLNkFcAsc369VmYYQTxNSWj3ChYGm0JUlhs7HpU+dZitE
s+Pud+KxgOqzgQO+Ich9esdxaxaySu0wD60hux7qDAMCn0q/3j4iBtZnMixhobGja5DiIDgT9m5/
wjCtzjpBFjU88ys7W2/qB442jWZyqWTrieAwETUwwFr2ZSijc625fNF5aHcC/54zHHqTOHqVEcjn
FPqtdkbCtCiqUk7aHTeZ5j4/1zO+xtc/xZQTWcw8ENo1o5xOb5Xvp7CS4PsIjrdaCjkSC6m/OIpu
pcr4UfeE/TaU9PWC6sYDLvugUakIImqwT89DJTPxE35DG5pZ/nHgPa4hw+ysGKOX339x5LwplT4h
Lc6P56D7Bv8/TGZe1agQvqvhAJWCTvRgoQQIU02wUCALni6CNWXJjF6iUFOe55MTdGk1HZoruwi8
DmXirGyvYgnzLdTRFGHOupKVarGbkXY4ubqF3VFq0t2I+cR2Lei92ITuKfkOwAckNsihnEwTfdHs
YluCTspri7EDk8wTT+yCwupB+aeQKQWPeotnwIraQQ2/y81fIlKCzYBkMUs/Te4ecBn0kMqN0Cku
Oua7d9IZATWD0yVhpbGNatN6l6FKaqFTobrMiEFOzk9bxpkBmgwYPjcefZHF1rE7vQuDvkxL+/Ql
EaaLDX5uI0q4OjBfd6xs8PkvtpNhIdFotzcccE7sPBmFi90Gd4BT1faMM4VwJFYIsljn6uQA/YfT
aTEWO592VJ1yBr5fIgrb6Uz3JET9wvJn5OxyeV7MnmJWHhEWXZIT382J6IlFv27HrPPKsmo0cNwb
O5803R//HX4DLGvYxQRcFjjwIQOhtbmfcN3o/p7hkbLYinmZxsGeckvpJDQLZbAlwn7X/w+wFMwt
0nQr2SErsuqxVxcqySJzWt0GIG/hvhOJ+Rc7Y5UB09Mmn1rFIS/hwLX9rt6GDdkP2xt+4jaFByW8
jV5v+rN0N3Ibczwf2LwTpcrPkKWsIf5nYviXDBOKgxo3IYre+f6aHw5wxlG0b4B5e0RboEfc1K4G
qrnOiFbAVQAAAndBn6JFFSwj/wACKv66/rRMFKgHjlQAl362OTN0wSpaj06khMjhx7pq8JmnmChJ
KRw3zLmhuMQafaE6orKhqj8jjIsdYyGyfSj6d/YTyPQALGUgy3ORkUGXpYn+oqVvly2UEXWkX9uo
UQ2dsXCgmpFxcB/5EaEEpGkJNvC5wNzLBM2X6gF7gNRavZ01EDbSYdRNog/ybasTGyMXue076JXk
DMz56fSoqqKHQKR9RnIlAj5/CCFT+guM/JbQ09AQxhkyUKHP6KKZaAly8Oe/Wr4bmX15jJmwWF9K
E47RHWDft7bAUh5TNs9vAPGUYEoTw4oMaX5/frj5HRWZN5bwmSr84ZVTvny4L/zAGIqMkl3pZ4q7
gUCQjhfM6JMAxbtsqty3BniP0fR4tEk0tRYJghA+38FQBGb/56HlEPHRrwzaCqF0U6BxjzLoIKEN
+Uu0SnszXYSdtdNhG4fRXP2ZmM7NTGbP9s1e5/atrNKGluC1kugCLZ1k2qTBoqBdN98UvGyjY+Z/
HsI0YuP9SeKn3dYltZERi9fBNO5MNUcJAiaRhLGRRHP8EOymCAxrfYGBQxHHnH6ToE5n404YCtVI
zzswmC+xTie2pcPsXtcK5qSJ2orBH6j5oVqkEbsiZcVtfUqzfiCcaqXS/18dKujGGaKmmQXK8jX3
Y7tw5vS4xjxWM4R+xda16RpzEqCtKOxXBOas5GT1EMphssqaIXypJYhpucMiKQC3sPReULqaXOIl
OFMp05XGwQjTbf1nm/4v7fjYXk3oVZo5DeRpq/D3SsEG+/g2gsCJzF0ZNzt6P1DBfn1Zm9duJJ3e
6pUzuDEHUEi6dtDA9RbBAAABYgGfwXRH/wADc5pPABO3RHKYKOHm2f39zfqW1M7QHWWPP97B8Fyp
FKjjWyE11/T84WRSMGYKEcpeM+d6tUKTtYP7UzJYK0q+5k7Gk30/1ZKyvD6uBJ1xOgjPHqQGdrmo
hro90p4sELOcVWtbVXxjzSVvuq6eeQu172TbuaQ71lXAFeTpOs1Pq2/m6JCZQzca+waQc7VhP01G
IEFDANK0zys45sp7TWRsHQDyvgnZDL+oFiPh6Pz74KargVcL+vBszwpRSa9PmKsRZWz9uxSh9FJ3
1HcO1Rw0sPQYVAtR8hNSNEYcFytnswVCL6xu/pmb/sywxBXKJdLXr90DAjsb6X764S+nhYk1TvP/
AnyPjYek5oSHjojyuJjEgzHvl2Y0QSAnRioO370qKo+Ll2jdn1OV4ocl8dQupT3KcylNPAU/8bWX
dNR72YCKsWc5fdAWL1kS4vSFxB3ZmjE37Od9BLF7CAAAAd0Bn8NqR/8AAhuWIQBexPZWI+U5yKDI
/TMqQAhMp5z8Ev26/GOW7JbMGlNNkA0dOG44xL1QeS1SA9ATwiBCn+uXHUXZyC8CQzoxSlKtaivn
L997QxvC7XrmFLsgk/dFb6TPsfoMdAYZNWVTVcY/qglNvmbx4kVDxIKLl4fc7b8/5zpOP9x8leb/
GPBvzG7nluIrmTcvj1uB0uhqcicGe+v52fejdjM4UceHpQocl/yo6F36I7Ol9F6lKcDkF8kLDc7F
yw8vZvX3zKXCDetkHpQJSOge0LltUJuAjsX2uUu8yR4TP8+lbhbOxD4XfzDQnkdlVA0qgDA/W/3x
Jq2wKw0yVqhOhHTnjJu5p6vU4W2T/WN0oBGOLliyQNN5DaYmoq1U0PZFa4UYRgPHDlds35WaFMDj
6VJXerF8ZRngwVgH3WG1GbB9lhqD+BVqp7Hwyv3W18mpr8aAbdvCCCRgMLE1rEeY+SvU6L85gwqu
Ldudaa1x9p23QG5qRkk9M7IAiZT5iiFABIOeVX5U6ip/hFuvGL6tcgeY/mHzSan+RhQFXYvTPQAa
QCMVrEot82KqrP8rPtWkGy2C1bxWaLLVSRjBZ2oDdwGNfA31Xspmwb9G0XJPbCfcp8HiZuEbKYEA
AAYzQZvISahBbJlMCF///oywAAQnpv/zZPU//8ceTCk6wj2DW2fIL81N/ggKBg8eSEmZPBwWlyzT
BhrP5faLwxu2X2GVYIwcdF+/wIlH9iLvQwWCQ7bupB8DyModeXjye/PmDTuTF86GMKAowu8ln3JM
XV4PVJ5fIy8InlwzCQIOt39zDdqCk0dWz5AWbeWZ2Iq5L/hsjGtNNDFzNst4rxyW6hzGKHFrPDlR
UAETNKpAioyr4OET3mR7g9arUSB0XYJaFKCuLA4euQDGlxrVZm23dybrB2EU8BT8nuBC6FSfZfP5
4IPnGECz6N3G12ECZN+yW5FjbHzMFGt7s1WP9uwGPxiowOG6oh024WYVfW4hFKQBeM6SSR2VeYXX
k2kJqYdEYWI0js8SdX1ZsihqqcSzrXwYxMMuUzQDBLHz9SewFaku9O0Z8DyiQ0DZaCCtaKbAJupV
S76K6O1zzlICLpQ1OHQc/x1sy8s1KPaZ+BonHPWvkkuUBoGa7rfNvQo+tntFqST/2gf6b+BdXl1z
3todGiY45DbuOKJGT9YABWqIspoGufwVlq6mwLXPL+B3PVOP4ywPbfQzNetwlAhuHcUredqI47T2
Qm97KzUwilkkiJp3o4fYEYAw+DmlWl9zgQI2SIj9TXKkuK1EcHfjq0/BP23Ug+UDgCp2IOF1+JDT
q1no43i1QH7bhMBH7PsfujHuwQ0Dypth7y5xUUWyF8iVRksxztVmZ9ktwSrf3za8fsIRU/UDW4Nq
zt+8nTEd/94XKAaTE1CheF/c9QAleU7qv5Cq2wOxrlxJnyQ2ktR2Xdh5X9JW5FSRHSekCnhw+5Ny
VaLh3AzaRHjD2WjY3d+8YsO3esNlDjSiotRBoN2zeNa8/2JjJA3WN8CIq55XGdZ0cHyiAVFCO1Nd
ktZiuOEmuJnQOxzUjnCylJq6kHvodQt9jZdxKIeuokNm7GItDPxGgMW3WuMQNI89JcIV0cKiX3gO
iCI2l7chpTW5+WdM62zfkRYoZmQAPffFVY8FsGkP+mIHqD9TavxPO3YIOSqo9q+E4DVhyJ4v+cZK
GlIWTxbm4Ioq4rRLkVZmB5dbnWG31F86S29LLuf6q3cmQXXXAWsaeWoC9fX0pu3psnHL7HZ+IrE9
vflPslhDvVEvwK9zlUegh3UC2Q3Dclhk270oQZXxm8xT5dNJGCg0ymV4qvSfAWtd2kBLQVNPY3mZ
Kt9L5VMPiciPG03Oe25nBydgnSgywk0YOhob49nhSaS5U8fy+yCub6p7DB1BnNSwm2ycmsVZ94EU
OYkOtMTMJ9R8h7TOCN/ebrFDsdCvJewCBi/xDEljdnmTqWFgaXMzesftVtjsCi/AlpheXG0VF+gJ
IG/Uf+biLhyIyVo1lHVDDD6YGYMXOEOP78tvZHWbICuBVxHx6Tje7wyFFAV8nDrhR2/l/I9pODSe
piTuqcTJ91poEZ+rNy6YhQeU+1sP5gimIai4UfZRsvlevhJxCQWiYCis23fE2/6SHKI6OouTF6a5
5zP+GtwHa8864+5tZPXkA4lNhW4ligrySH1emleKy1/1+CRVSBqrLwTwnTyMnL1GKnoXXGXuRmJi
nA+GTgOnYVpFPC0g/zlXMyPRZ8KKeOE2Rs10iLCiOiX6JjYJUs4J9G1doqWgVJuw6mc3AwISMjfD
GS++2BYaPgvqhn4l8NSSnU+yABMMxSHQINp39wuBn3cZzw1HaZQTEtw/Q3SsIzxGoXesZh7YnVIV
Zcq0lph7zac910w9HbxZmVMb+KH5k3vRzUzy/p1gjUsNdQboT/PPnzkvfuZqEn51SdiCuimvqeVf
8MUmShWmweNNMaoGFyJTqsW/2igQsjNnyvLYcTgnDDwMbn6pX+cEihmUqNREYBEBHtj+4o2WpMQH
pq5sBEokgKArm3DTRoTpjpbGauvkwSUC4BalQuPcLrAkghB60tPHIR3Lefnl1882dNf2ctzO/4E5
K7SbxrtkQHpR8S7xuMBmklLJz/MFxoUkOF2oC3DGxcGGK7mWhHXu/HGVsEviLtX5dVEQn1NO8xRy
4e8soj1lkPNjl+6ciL7T7UqPvetjSVbxd16P/WyihOmRA8a/+7gqOD+Sjc24HxqkL8dBAAACMkGf
5kUVLCP/AAFZURiZvmboinOAgAhus7S2QNkBW7qjbwZS1vRKMFkx3Ase6CGPcoRyyJWqMYWT/fNY
P9OkMHT1u7z1D0ExWpvH9saKqPO2CTZpnDH+iTkBzmBEsz+wz0SpQrWCZcNUVWhCgZd5tlMQuXst
zOwrZVF2sPYinFOvL2OtH8DSSNDi/kI/4zl6srPlCR/AR3pXnUhpC39MZL3vELE9ds3139nv9sIA
PZtsAt3rwC/MUPtv87pks20G3rQwx1rxh7K1FdaSq9tu5oT1ABJ0b2mdsiJQKhXib1/9wGPVM/nf
qdrjRJvpa9PsddRhm8YLa7qKIBlboft/K2sGCuLyztJMRL0Bl7v6l4dP5/7yfcX0BEf7jt+ursET
1czeI91tNodWeNgEJ/8doT/jLQxU8DmioNgkR6WiQRhYyrmkNv+lMZV34rymngQnlHZODVtFk9cf
BJdE+sR89OAKKAeoI/a69wlihVuAPgR+kz1YnXt5dY4aXjmSdi3128F85JFo1962XTtc2pseMhMx
anGHodjdGMsqTCKdhScab807rlIGS3ijq02FDu3PqCIiSh0W+EgHIUQ1Pj0RMgVsA6fb/E5KvCrL
0X+0MAPjOyHvaiW1HN/fXhB6GTbqd7L1l0DgXqbywq3WTp29DvodcohYAx+k/88uruikvwqjwCsh
mp9dHmSwZwkQjUDFhz1rUtKKZQWQHyLbma0+POzHZ5X4FoFqbqydNSqPHfUAoOEAAAGuAZ4FdEf/
AAIav8/UjgABwF1KQIPkHZ/E/yZmnLwkx1G83UXY1YWOoqJaeuYbjOxNSTdp18AFbW7fiVyi7hqX
mCYI77bpuDsZOTMH17Yx99DSXxaNvUT3OoCaMXniO4fYd/k7Hr/Q6z1N3P1BB9sd9hMKUC1xD1MW
C/Jxlf/Gucsw4oaJHNrlFCcdS1GfachI2MwsIS8tjeCBMJt2quUrkIlLTrf2WBlqIqbnGGC3XumR
y91LxF2SHxbq81lpFymIN7EKc/KKLwNuACqvdjL3NXhZDP2eRwHD1k+zUwgd7hMeJAJqhXNuP22z
//IsfN0A8U1FuYtdzsY9gRm6pNNBpm3qevgwLFeevI6cq69tuPu37pw7JykH9XQfMXyv/Yjbj3au
x4dBWGbkkU0NSDlQGAVoNEJnxbfvR0nfKdz2jie3/VFi/0stzmzadot71RjczPaXMAOqIjayeZ/E
IEAtsAlkOagqMcqBMCtOQxDWhx5+dp44iBKc0p59ELzLnOZ5PqxZzDfAXMbwDp+o4emNrHSd9QMJ
/sPJWRnBUWRvWLfoznIhORi6X35xQS60FwAAAZ4BngdqR/8AAUdleQAQpi36MxIkpZ6aIaL9DKyo
E1bXo1BE7ksMJ4ubM3abJyatYjPOZIzDakVQGxtOjB/7ZARRGRU4hWMQIoIjK+X5prGxE9BQkFdl
TjMGkpIHnQDTQtxc+kU7lMrUHzV8TEF57OB35fkhy1gdjlcZauMn5tB/AS/b2XRwmdpM2WpwPIDB
XorlzU/ITfwLY5VR+YvNM5eHVHpny8qiPTkl/KxA75AsV8wYH693N4D11ncVzCtUW1ZZt04QITmR
AKkbyYNCh3tkktIpBm7OWPIbmsxHXPQsO7rVRPGkPRVN70z/MJEPehTQ3AGyUsq65SnHsM8drrdq
tUs8tZNHtkC1PylS8uregZXp4Nu/ASEq5bwNWKSAgYJzYJhnsWWIchmQwjlICpqA/P/Lbjjr1fEw
TQM1dkn8BUnGMQZmZcvdxIbvjjsFIu9pdd+1d9GcqJfjzsdlKdApepWjbvC/K6t4tz1ElEbD2j9A
8o+hxu3DatxuRdDyf+o2vx7rtCAe9CkuWTU3fvcS8rorjLz3LgeKQcUGFNwAAAQGQZoKSahBbJlM
FEwv//6MsAAEBo8VdnADc1XUesRJ7Ttwk/QEyIPtS7EgPnQ1cu0WR0ja0TgMZsTOoUAh12B9+MJV
8ZGfIcl/9Lfad1jmU7Xds1OFZFIQ9PJhSvZnmH6sc5HQKupeXDmPEU7rVVa8eDKMRZLCNgV5iRm5
2Ikr35/9divvZacQM8Orzhl2io1+EAUtzM3h396LNi4C8xjFxlPzwOGatbssHxwtVKJdKyCQKAOA
rfw51rk5btaV99FEeYkab6TWJQKlXLixJ1eczqEml5t+xkSpO2GXLqQTfPhLY2tvISIebZ3ReDEq
EYfSZme2NBERGFSxhKhueHR7gTj7ab+9gYmoMcudlY2f6m2Dacy9tO4tWWWibNqJURkSi1t/LvlL
+d1YXIzUklnIsGhotlsDJznJJC/kNH7ugoVMe6IXum5CiN5Ms6azVS/rreIpjbpvfi+evo7x7b3i
06w/BI89aZdSN0Aaauov+DvHGT/rsgXfeLuw4gytI/Yy1xXndluDryYukirUpEPYXaZJfH4V7Uxj
Kvh9wGW98YelDJT1gifQo2pd5+rmF1HWRPvuS9GPugtVTWVF79ZogHBGS+wiSvFnfHUADk21Rrbk
FJxLfkAVKaWQYfvi5bU2sxZ/YVRxmclLbWtuATTfC29UVgSSx/PNwBrfJmtYar4iBKuzshjdvyhH
WTTJoCNdl4LgA86808YX/CEP7lckc+F/6n6GjguDBXWu6isrbIJ6VhExOaMPd63bzfexzcnSrCtp
X9dIRLpjpWX8Z76MGT3wSdkTo9/7SwZ89WBt5p98nML0Km//gSSwiP+m3ZDJSNpQz1ljk9dY7COj
bsbnKVeltlviq8jI1E8Rpj83LR2ieGpYwFN+GeabzHh62MvSgM5cm8uHh3YZcsO0z+LVBvUHiwwy
igFTC/jA6PWD8JisfWRXbmi7rs225uf1M+uiwdlSej2IWU0n1BemzNDnXQgMc6HNWrZlxomRDuEQ
9Ivm0AJUTUcktKTK97EvEAGUP/yPbqGKajwY2POs6ms/+h2eMgg1Ctu2wVH+lWWwIlSgoN/kYAZq
xO3yjwS+zVoQW7Td1EVnHOXAywBBINWSkho7m5c36ZJdJyvEiVsRfFXuiFlMIMsDUWVWykTfewu9
9unRCsnLgFkyeaFVYRFqWNB0V8pBFNc2i2dGdgVkpXJj4xZ/3CVhGCx1VW7I9Br06Jw1O0EQ7E+Q
FtyPW3O3aV/VhCjfXG46Phiw4OzT7+kpqRZBB+uHvdnsfM7cBv0mG+0gOu2qTZuKpPKuFOGxReWQ
84iMZgaPvyBFnXdF+hf/LXalpvwS4uBmnzoXQDxAD5J4ErSUllBP5LgPrp+sxR/SjT+pyQAAAWkB
nilqR/8AAhvvi+RWIZ4t8ZCoowJjf9LHIgAE4vOwk9wftgZAHUUkuUspk1pndBVewhQpwZpq6vge
b0PACUi5Nh/GftukZUwYhOx7kIGdNMIQZU0BLDG/eVA4Yu/fI4ERnW1jF8xftWyjeQxRMv/CL7eU
b9p5FKx2GHAYyj/kMSP+Q7PpCmupEqenbQliEZ5Jro8asTKCQRETenmkYURmk5yj/oL90Uqcd3GF
mis/419eNRPkWG+bzq0eV77DPzz1+TvHC5au1k3mUrmSrcxPoOxLgnbly1tBrb+wizwAtyPNtuOF
s4004v10IlpLG9TlDt4DMe9NfVMjvf+Lmw20YVVB8KVHwqvait1nU7zf6F9qKPkicgUaFdpxZW3N
lPEqqp2Y/w88gbMwkN92gZTM5CO7F/Mnf838c4WRUc4JdQN9NZIe6b7hqkNhrfPPTMZjt189O6t0
uYhzb207N8XY73ODCq8thqZ9AAADXkGaLEnhClJlMFLC//6MsAAEIRwSB6CLY9zQHSa7qmrOATDF
e8BxnpS5Bg1iIwaS7unC0LdT+VJhJ8BmPOIVf0jT8PJUmxYIs8NxsRLFqZiC8nuRwz3FpKKE8N8D
jncoGqainq/nOX3vSOpoS+AcKdsrOYHnapZog042VNPwOZsz+mOBPEmAelnzywvyrnJz5on2Gw7v
/XMjFtI4nOuu0kpaYgWFYOQI/LxEZIDQu8gbuXXMBQKXUcaSDi7EQx7PykvBpaxsletmEDiONnPb
jK2+nqAzJIkHbvQCjQPD/WbI2sZfoBHnw2NmuYYos2LYhtgGjsF79IBy0wFMZiNzQ0hVkGTVtwOK
VGo312HZwl8hyKUojwM8ZZAuOioET6IW9CBoONwhgGTuXFLbbjU1Gizv6vXBdnmA1UB12QMVESL4
1vhEEF1opzT5aajtSvv//yAeP61ksqGpfjc2wLhdTLLU/aAwHU4AiqQQImH/tcBTdkbST1Tvdiuo
TFufHnXEAzdaGvRhP34964pz04SkvnbYLHLB7kpjMTKKzf791CzkqLcea7P8TI2LEEq/DK+NYjKL
Og4344aC//iI6C85j/W8VvIDCocbqDP8yza53nuegJtduuUDOwwmJ5dKpAeqqWzeKIjnH+8ARsn+
XrhhjGyvMjqLWW/aoonq5yHnXvpKMXMrCz4pEotFmgt3tyA4INm6xjGCCHOJcQ0+Qi4Lbc1Jo2wl
BsYy7V+KNPM2qQluTy/GlYeTHgULyKdHfL2ksQOxOGHAz3mqRC5wETknlVRL/lYA5/GdQrCQf5m1
MFD40mPoDox8k6f5ojBRerSwP5IjfQ2+rjW2UGoVg9XrtLEpY/S3vCCGR1gZeSTrFeizEw3LdOj7
TyluAqhuotsUSmXNhSmnlwI3n5omtXwO7devUNasVfCdLB87mqLGyslDDMXIOC7Db/vNffDbA9G+
t+maJqqHvsr0kf4D/Sbroe5lm4TVZAdZjl3InPffBy3ZO5NezqA+jAgmGCU1bBUQA2aKbiW4QFNE
RtIortYDJ/Ryguzm7Z7UaM/kwzjnLtulRqnUYo3Wum3cN2p8+Rccd0ppc1ujoI/EP1Fl8mpQr6G8
65VDhsOLugEGy/TEH8a2J2TVq0WWUzkWhU7bTyEAAAEVAZ5Lakf/AAIbJNoVaNE/lhMWw0AAiuW0
MeenJt57jm9XdRCe8SakZ7Wb/SJrtK+nvIafoM6ZQOUWAT+3r51kGPVaZ2tDMuPHwuaYe8fmPj2Y
NuedQRfcGfXeI/WP3rCY138rGuYajPC/qfTzedbsa34okbQY+NBimmFOJsiGJs/VKh3ZJW9E5NYp
BapvBEXPYSvUv/9f+d/+2w5GLEdJ4ff+AItg50uJFhRrbft8BmQQGd+aRe6NdmCmtxeJuS/jgr6n
+0n2015VHSUzDuef7HcAO1V4nesgyc9c8WJEqHbcHXe8IerDSsO/ht08LAB4mQGhPpwk49Y/PhaO
+2y/QLbUWzE0VEFAzRUomnWfMJH7DJmtJAAAAwBBmk5J4Q6JlMFEwv/+jLAAAOjjx0z8yyOeANgu
2L1lQAUWt62atK5xnxgRvqj+sXf0ldQ//JvYmnHbyWq42KjBvw6QF48mX+SUz/ctCdAnyECZCeRT
8MCnrYOmhSmXHAEI2ktX9sfSmh7EKiLmPDHBT6Hd66iIAMNArJn494J0NIef3w/7tE/gcRxBEQKy
DswDTRsZKaHoV4KA1jaCiiSdAv0tIqJETrdhmoie5yjkRekGJnoLLGDprsQroPWfvmou+WJwlSaa
c8Cjdd06ZxIsOaI8DN+9qhgE6wCBYD3VPetrPKTpX0Izlgx/D0YDEvNmfd8vt9/Y9Po0TeViaocw
K/csJl4kvH952jodJqG++eoHND8/+YnNcyEtOemtMeA7CWqDiR6FOvQb2oHjbKRqkodOD96sQivv
vjy3Q4EEUtekKK7Zm+Mhf5KN37OzkSt0fkNpesAoq8UZX68ogWqj7cU1GojF0ZCL/4002Q9Bkq7i
oU4are4UJQNttpHMZnFuqCo8Aks+0AJw7cE/KOJiPKrl+pUtbG77OT5GTpV9GKZI5XiVs3L44EiR
JsZKknFrl3Q+juC9K3/9xyXlPWtlh7ZpTxntQIzOwOkRW3puJ9LcDg+3b6XAC92Qd+35qVK6rkoN
kbFOu75hZ+0d005z4bvaaIFmcm8/2WSoYeUh8A4AazQEdz2dNUie5UWsUU1HPie8jrNhZnunW/SA
CDW47Mi9sXJ0yHBeKeMgNV4Mku3EKKLon2RIjZC41edzQBqd2xEqZTttTAfOrc24E9VXkb7ll0Kk
U+68hBpofzxgWKkppAMcS687EoDW4TE3QsB74Wo6c9WSFpE18LEM5THLFTnpdNqxc7AgWOk17824
L/6IK/sLoiz4oWVE/r2YWTKoV46PVYsLax2B6jnSwV7sHrD5pr1KqYpJ7EjjrhuxQoPkJXWRCvIX
ngIwGVMAvhI+Fq9XD2yVDiaBMjj4J3M/GdTP+v7j3+7L58GwvIkFF4xB46m21tS9mFGYwAD+2EEA
AAEzAZ5takf/AABNY/qySZKagAkrD5FlDXSv1DKFJrjamuQ/QlVf7zgGFYkQFufHXM73d7np1Voz
Lh719feVSwqzS/amoGO2DqCe2IWINHsqj2e820psenc582GovKehlZn4dr1dWPQKhpCvm0YWkIRu
/ODGB4TsjAN1b8UV/bfUn/d+kvgUzZUXcSa7dS5LcXf+3x6jdNw9gyetDp+y72p86Xz84mQ4xH5x
OrVbyQZwB5wzEsu4RWtauq2OuZBq7+JhlAcO2naqflgS4pxXMiDGm7ZSuF8w4fOyM4Oq2e/J+G6f
gwAowHlSIoJLWHl/08DMdiMINliGSDEl9VRF1P9D5syETDj8xIzSJXudegwBrZSkQ5JvN93O8/iJ
Z2opK2rSFmi3Kde/TK2pDXO1Dy4dxfCJgQAAA/ZBmnJJ4Q8mUwIV//44QAACPMACFQA6MRxOBzKz
ZFRyRP2WIpoDqao1+6JpXQ8XhKt3iBD0tfWA+nztmuEZTTm+daFsV+PLS800BWGZog81824uDzdr
P2rgmuIDAhH6R4gY4uD0++aEwc00TU/COulJoVgHPIMIkBQ1lH1muo3BgWLrtwjBY6ntbsfzH7rn
QHisBIjM3Bv2vyYiW2QfRXMhnInHG9pku1Zc+3+QFVWT06OCW2aHn0igQvMMjtGGLpg5eL06cK0Y
TDlSii81xeO47FZeZHZT52VzLgeFu2d31pzxe9w2LD9injdzM6qa4LRnGL7/c0Hw+EudpkYyZg9E
CiWaaMHAxj9UaGvtDRgQAtK/IVsPpBWC30Qee3dvi2kiiPK0ZwuFN2P+v2F+Ds/0sLoa6bHqfQyx
Zm2aFBieiqDj45NfIp3o4FrzapT/Tf1FcKRfb05+H2g0ONePSd+ljYC5QNXNMybiQGjb6zIVTgYI
aNvxbpZ9W+4QJxwbnBh9ZzKEaM8UrVU2Yx6EGNJzxodBtqMq0X5AyDbJgZpXjnw7kCdwIpS905lx
8UzpPH7DpDnZ1J3DcAAqzlhNnqHku5FJcm5fdnlziOeQ0SfM2hdUh8DyuOibyMWhJ0t4Pmb46mEH
rOI+q1N8Trtn//NJ/zzOEL6pvoLtH3YC68i1HdPjLKdDI3OLGGS7J0NYSWppO1RAbtE9g755Z1Yz
BBM6t35JmtrnnImytieTZ2Jw89jgaepuEB9vQ+BuDuy3qYy7wVdgRJAuP1DvM0lHvEIgwJ8eyXYP
V94T+iP1MVUV7+BoXWoqReYAQNeQVLCP5na51Sp5uYL8erEG5GAPEuqVnDiMDsJqm6ujICGO0qU3
C0EONzH4mrOM7ATz8yAxRPvprIxA92urhbIiS4qhKNbXLJtqhdLL0E8ZIwzJ6alnvWuhjgYJKTJm
SXaspr7qKGUHNOlh61421W82PSh3qvnJih1i2WbsmqQno6PpGEiq8xtLpOJDQ1+njEWUVcc/og6N
c15lp1CVNJiToC7raKVsuWLslllWgYgsulsrsGKbcTELz+uvJH1mDcheO9K1+vUyG6Yku+dtvwlx
zcJG58G+NSbIFwWN0aGp7GCTVhWTEW/FMxxg7aFusH/PyfaQg/d661YO8HYZIY0ALUawtmAlY6vA
HJeom2YxsXs6VLkrRS2Kz0CuC2LRldKenDVKIlOacn7wTmr3sMZv8PnJq041+Ya35FVr4UPKxMxJ
y9Yd1OBum5RJaPkhh2xwpC1Z/sUo27R8kZ1fzMoLcAnUVDK3UDpLXobb9U2CDq0hntmRljPMm7ne
6UFOl6b56m0kO6xtBWXXfcUAAAGEQZ6QRRE8I/8AAC/FNR5uwjIviz4xi8s4J6sADVHFA0q/vV4/
0e0NgAm7RW2dZnoOdIJF7uCMdpOsL14hk2+XZ3I4LX+ioTsbdeiaJcjIHFPH5UxlSiaG7uyYLnja
Blk5V7k+9zSJ/m/5BpnpNZmtYoDV5GhrBHYaFbYVtt9cB9eEFTD+xpiyHL5snwS+/xvRn7zwoRd4
6+S+POLfEuMcoBDC/LUZRkIpI4yLmih28Bqx7B9G4003H3OugA2cNB46n+UY4e/Gb/cbXZlv5v/M
zwOkOXfcRTo67vEp2NLWp3jwN/iulmskKhuD3INmtRnEw30n4zia6dg8VkkTGLAHHSx/yjqknV7x
aOJQ4OT0JL+FKVZZkxNyddYaef60AE1RP4PwgWFTLDn5/T1snVtbz5GWrEf5PmIyjZRqN5MZsAs4
34/2K/Gn5K2S0rzjDrR6swOZ/Uvq/zCwTGD+DAe9AehSLRUIyT58/kp5NbjYuKc0AVmtjb5zxjoP
hjoEZ5pEhVjb5AAAATABnq90R/8AAEtYFS0USw4NGVMPsMAE7dEfBnVsjV/Jq7eLGt5EXyPAXj/+
BXTuHAEoYFQJjhuznMcj8Xtv0Cg4cgeu3H322mUhzmCEs0Ydyl784E0CefyF0BhaQcAApF+2zNtJ
1j1Ai291MNHW/9XOQ+vV1xU62Niy8Achx3FjTAZBNXtgTmRFsjdskoedDX5TxR0F9u21WDZYxSDu
PzMppLMwnci6Ero7jp5WhShhOrvFgJcHF140h9vyDhzLmcB1Sv1kV4/0J7FNOa2aOAFjGlIBpOHY
oS9gaQLKX8kuxxCf59iuoWqJKo8PY3jO9YIa+jmQlSBrS5ZD6CDP9O7NUYgNFHRuo2cgsXubEKV1
Nl9mXU0pS4fYKC5a5ivDm+KcaKlkMrQmxCX8Yn6XXLwQAAABHQGesWpH/wAALonCfkfMTeh6AAmD
SX4Tdh3VkI1QO3Iz3HwEMezNWfNGB8ccm3u156srvFtQEmtD/MFYkDL4KN8jKTheoK6xSgifc6OV
z9rvLAMmMhEAKUCmtMxiKBx1pJ+MKvHugt2It1pTrKMQy6Bfe9RH0cP+7iGfFQMlNMhwFGhTNs11
QI7mFlLzv0dpJPbM3WlK9ssCBP8DEfuuOUgJOz9MqKBj5gmTUpBviK7kY88daBewwmbKOIxVtTyw
rnt7BJ7RApvqWIvHngutYEM5JnjSkqtTZs7y3XVF3gBIqDvVZ+qhTasFEl3oOVgBaoQCOJ+wANai
Gc3V+D78ZnZZhcSDNuUI+POyAsK+UgAreo+eFrX2wBxtGacy6QAAAeBBmrRJqEFomUwU8K/+OEAA
AVj6iyVo3qcQQY0HgCp0u/UxhrjbO2FT7YCSYWFCndFy8uor3vWTL/3fTh6G31YpfrN8qjeSvEPH
Qchl24e1xKibjRb6Sb9o8EmCWv7/aIuBgfSbueoAWWrHH7oba47USm9wnJyjbSyv7P9ktXEwzUDw
yGDwFFZYVDHHonZDrmEQ+5AQBRjdJGRp/TSLTK1HkBOn9SPktVtvlHyIawRcIC5T5gdO1xitfpDL
RIMWI5XtQ7DqFMOrc7pGAMutX39njXLoiAcGQuvWExfoO94hCHZKLZgy3/u+WJ0i+UfdclxlCVir
EZ54CfMNwyeLlQqDwzaFkWz0Ct5BR+VyBWKMSZQm0J/zdLtLopCDnd57+6ovTTRScQTAJak1YCvL
zKcS84w36PArPM0gBJRUy7V3mMOU9M/v7ww1g9NA9OASgTS5cF5qoSa9wSVoiK4qOrGrIbitFWa3
toGPzrL+NmN7ZJnxrbYqej+MLlnORB1a7TLkGcw2GCy8LBl8U+/BH5nLeKufqF/9BRnFJK/zoXRM
JmJDU7Hh4bUaIJ2HmIb4Dn0UBVmB66xMY/KQ1r/qdhYAX3e6BH12W2kDSoeJPO/BCuXppoI057cU
pCUKE1ZIDUoAAADpAZ7Takf/AAAtah9lDEIKeoLW/iQAqqUsxvS1/W3PhFGajA9ElXB4BY53Lr2x
Ib2BJe8ZiilyCxCn40TPvf8CkVr+UJXuYWHM54bwSN7XUUjdjEA28t3UO0Tz3PmmkjP4AB0gjBZn
w+SSWRjFQ38eUQC7SPQhXrXSrqbYgPTq+iQ4DKauTEvdNcJTitD3CTs/2ZIWsOUNS4/QcNdH3mGR
7HnqplE/xAdOD6qwYSJUkSiPekn6Kt7Gjme18bYznTJcaXO6yD+VZK7EsiaRBaKPs3Vj4NyO1czw
xIOwzcFAUTNhiQGYuOSJZlAAAAGUQZrVSeEKUmUwIX/+jLAAADZYCcgJj8NGjipyeQA49rzD2aNs
iWoaQn4OBeCZq2jujQovlu6847hpYQ9xxl6jOr3+ihxfbowdxMh0izCs0POBXtpM/yi/3aBFJ9LU
X1o9kuPiSYNgPdrKbXt1UAJoRq+5OaTE6aZWu4MLZqa0ywmmBkDOtk0prf58Jy78pgJXXFYQ1HF2
GKWvjglmK+fNw5jC0RAq4nht5n7jdMuphGgMD/gxK3uc6+Y+FCU0A89uLI8xdVyPwmeSimyaE3xg
BHnPgIcagVawkoA3+nLvg2aarEkl+SWSr/y4Kdw+/XodXwQfl70UXJth51iFl/yNWw2EyWil8Pkk
9obygzrPBXVETIltaJaELNHc+6cNZ6FkqxUI3P8srQy7ZUMKGHk2BU6pc6xHflw3Q3RtYXn2Kg7O
7nd6VD/D80tbdDt89719gAH//xKTaLMJZPjbOmO+hG0M2x/9uedg9dV0C7h2BOaSkFXqe1Nw75ob
QZuy50kPnCWGL1bzJ/6MIItI+xtU7jUHMqcAAAKDQZr3SeEOiZTBTRML//6MsAAAIi9Yx2FVmuAJ
2t9sILO0x/rogt8twZNwVmkaHrZHg4fw22Viqa9N3D6j+mqB8pgJ+yGrYqBAEjEDqCdIAYzBfz+v
vEq+42ie/mzp09q5kiBOjbikXcSbnX6oATBp3M0khonmApIctISDNaGGWlJvv6X3h8I1odjOt8AU
jv4SXzVpQyC0cMPKYCFlj5cDTPQQlQm2gL5IlSo6NqjidnZqstwQqNunthM7DnZF5UmbQDJn7vFR
wEQBShp1APtEqbGFwRbqjPztsiTUOC7PYPHVAENiuKle5JyIlvDXoUrN2X9MFozlDl6OJGDHBYRm
xUwi4rtmY9vWfi2otT0lJFhXJXYTz5uscdC5NG6BZHwXgtzya+Er6nAc+IllOtcTHfYxSiiU4cr2
1A2DcBOPnmWHsau+AoKqigMOhPST0u2TKEt7kEhHxosq8bSe8ncC11A1jak4t0yiqDk2MYd8yqep
msuGfxHOMivtqHgsCj1w16K5bs7c8RMN4Ie2ecz7ONqL/hEUD7d4lo7kUf4ahOdxGKCCYe1dDr3I
gnXiji8b4LHhnEBgez7uY8t2DoE2igJl8q8czfxljFuE/7KX5Gxsb1VtAjHzprRmPrfOuF4fRS8j
umxb69F2UgfiY28mO1ACk/v1Y1k/Jy0rYgvtOgGcOhV27kH6HBXj2ITDdlbKXZcVglOuMB4VtQX/
jR3bE8JkYBsQHGE6XYBLcASJqsFYwIFszNKCunIEblwNo7EsgvsE1V9g8iOC3E/dkcjkzM3sk/VJ
3uJV0cxDnGHvWrPtvtTESfCm6Lkcy50rs4+ZWjWUjopT1TPHDbZKP+pyXHAl0AAAAR8BnxZqR/8A
ABFYgilGPIv3PeKVTuLVb+AAH87IhhXYYlQtbckRekIUQPBAcG9r5dd4ZsRuDlj8iMDMKjI7bXFQ
VADAP4ayE0ZVPak1a2pJaaovwDCaIz+4FAeE5ESKlLfYTCkCw7AWvsOuN4XY3/bckuS2gwPvZxoW
oyesECedNx+ZCvsVjCiWbNggPwCTChtbrDM3rtsnyHF3CLW0pdHdDDhksYldN0PYmmpibzNbHHYq
7XI3B6W/CSzIhBi2jzDrRJ+j1lCzvna5kUYuoCQIqygeT8ZCyRkqh5uX7+k2dpKCbbNBQDGmlWbA
63AXinWmCfmLmjv/glFWmldPqHivHGa9lCuL0qiz/8geddHEl6NiS0FE2NdyfRGFdewb0QAAAnRB
mxtJ4Q8mUwIX//6MsAAAIQoqp6i4TX5vR7A5dZ8iAGwjGhHKfGSvjJmPr4VvvYcwepjeZMRzjWSV
lNfc303zd4/TEM1p1uxeOpYMu+XvDP+y1S+JiA37AABjXeVYCZ3why4EAhwxsb1NRy98jQAvCcdm
JnCxIc/O8AJ48NNloafJoqoykXS0dUx966OnNMQaZGcxZYiyizZpvrXQUYT1RX2o1ukCDa6tKqUI
NoSeqdjTDlQ74bkY7CslPEWEuDH3zr+96pUp3HVBNBBqmxaU2XVDyjCEKe7+YygmugneDgTaJtuj
RhTBu+eZOFK1aslfL8Qv/rrAtTEDesfLxD/eHm9oULLJWPzNxfP7jMesqVe8x4TdqQuHwk2tlVlm
rwxjXbaKR1McGp7BNM5rao/jo+GkKypG1HeMZTR3vJI6AXQIM+KG2EH27fMML1wWuCw/NVeuZiuJ
aP9kqttEKIHZxdGWO6lGAgkbvw0FX1oSJ79ezy6+NvFcyEjEjPSEYmc21PlYRlTbpVqsOEA9+A/G
U+XB68ZlPvaMFQYDD7Oec99iizFjh0VZf7Jwda284gzJzR3/z582czQ838sOSu2tkyuO7H1jo+R7
5UiIl2LKUQT58zsz5G0Vdk/WH7DAPm95lN09H1XDaqFtY681AAnAdL2qmGq4mDCL1WRDTp9R8bap
covl0bZ4/b8LWAj0NsFFApw+/jb7z9eW2RVB9vVmhOP7LXOh5GUVSqxYONoxT7JNlq5DvLo3599F
jxE2kZKA/8Z67xCTPpDzhDLIPbzMP71AOMya/RWa9avmHJtn/V+S1khLxhZz6qxOvh3Zw4S3a0SZ
AAABFkGfOUURPCP/AAAKymaVcWls2P6dtBoxpABGRtKH6EtJ/mgMD9y5WSLJQwl6hfdlz/QUNQQ7
vtVHt8ed3wRIglDIEIP+3swvnPaTxWdXUIhCw9tkRgTM/mheG3duDt/X0p7uJdmD0QNx4hbzoXoK
YeneE2NE8FRmCBL822dia/Fz+lK783KUa53nekx2/7mkNFdUiH8CSh+WKrk8Y4pnbWasoXHap8LE
APeTS3r7EAyCyhlYKRIyqvZzO6mHJPv2MFXa/rodAjMFHAabNWI1kakzPtbsOl7ZEywRHIr9i3Z0
VcTIWSjU7m83or0as6PSt5lPoUuEltQPLlhjVMm8afe91z0u2IcoUzUWxby96rf719j2ZPGxAAAA
wQGfWHRH/wAAENX8CnVSoFqeX5qpaACLz9M74HWgzSNqXNbORb57o/YO62bb7qf+nSc/ktesnF8h
ydvGh78PSTIecpcqokKI7rf5Gbpi2Mkc/HBQlHesZgPH+7lSe5zbpP1X/FrHnbthhyU4qAypU0Lc
H3vpLqZpt/b+szAfpqJmUz/XpnAHyE8Vb4ENypAjyerIO3LSjQqnfZnVrLv9QPAFBGnNLkORFkx9
bq7UcmmQMfMUCNu3kEsxnNEwdZrXBL0AAAC9AZ9aakf/AAAQX5gq/LKwaAcMDcX6zced6DGgeAEj
KqV/ivOOHNoGGPjf7jl+LpZ34Nrno1YAWTeCglMw+96mpFYyZSl/kZ1q9WCliHRAh4ISaLkfbJVi
OVulr8Rv8o7g6sjRu63G6ofwIxy1OCQIeDgC25mTQWw5fWAwflAM6yv3xtwMR7+LeAF5lqlNiSf1
zIww5Fn4TbVI0qLPufOPOUIAPkcclXE72LHdzCi46VWs0xQYSj1VZ5j1Wg3HAAAB1UGbXkmoQWiZ
TAhX//44QAAAHn9R9XZzcABopEoMxYQtdIll4Y/QSwxBf2Jf1qk7kjIZlqb1WpdoYy8LYnretZVl
VAHyhPbmuA//Kf2VB2fl8WyuH5nJzgu7wpZjott0I4CHVJtJyY5+JaQneC4JSXuDWn7nBWuB5wVe
JC/ROygy/2ZceGnnpuxJRYWSyVaSGl5qp0Ewh1N6UbUVMRZGbRXzZ1+2iuw3fVIIM1ELhNx9N6d6
zlLoeI2Swek5VVxuXwdg7PR2MbFQ1l1Bt5ci3DViIijcpzyxzBBiLOSf73gxzqpXZBAZzn6gYi/L
ICUFPvcfvHe2Hjc2hBeDljQCI7oNHGFPg0Jq7GI01QssqyciADmJ2O2D0WJJ6JsKlJYUuisjCThP
CFGVs1KgXCwI54MAb1tXZiXOl6iM1jalb9kfKfFtZzy5rDVyWAbcpzDecLG9iysjelqyRv1zGsaE
Cr1U8UX2pfrt43meZvFI3/WjTkebvwFo+QQaAgasLwRdrNHvSMDDPQihXoakLlFQPv+i64zsG5NG
h0ULUuygAgO322t+Ac0qPhFNvAXS/cI7IXYyyfS+woe/McwLRv4UayHjR+I/7eu05ifEOtngvQUg
21PZneEAAADjQZ98RREsI/8AAAqIUdGscH5jl8uNsSbbxwAhTXqQgoioH+0QlL4HltJKhhrBtnie
P+FUaYgfcRYqVDLnTPH6TV4Qk86XGqrOjj/F5avi6XGFHS6yZvGvCQzBUWrflr2rEpNqstXXiMtn
EykrYfj4mzw5CAyYvkX95j/Sm1JyD4qm9AmQJ7wl1b8Z+KIk/t2Pu2RrtxCajS/Qh0sPoRC0E9Dj
PlzExUZgWW/05gX7dD+Qa4VQmws2X4kPOLJDDML7oy3n8NauCUhV+tY+BPKIefQYq8FItb0/0eXG
UQGvg06AU6UAAACcAZ+dakf/AAAQX5gq+03S5+uABs++sFpBtNH8n82WrQJkJ4nwa5p9DjEkfCll
oE5ZqxGj8hRPYkMLUjooRXWBGLygw5gVaIdYlXMDh5gUGhEyiHpa2Uf6yqT0s8Yhr0d2g7cdfUmT
HpcTU9HpIqWjU5Z+W88Aran1LOp/VQOWgQ+bAgThk6toKEfq9fetaaZyyyVA8jm1j3bSejQQAAAA
1UGbn0moQWyZTAhf//6MsAAAAwMF+ZsLWnzLOSP67cPUAJZOJLtYbpgnRuATs7j/ZsSvYv9rwt2w
vvxmbebli39aa2l5qgnfPxhfAKAtvet3eUtV1S7J9rm6PJIRfE1V5hpm1LLNP7+/50FylbTmOfBf
qK875wkiHwnAgfjxdI1APTvekJlnCmI5gK3onC8zxciNpwdxvo+gYrbEpjUIS/PEmNMIuzXoSZyz
1Ea1XyrihOaQ1ko+JSIVwROBy6yuQy8+3bGGXI8RRbuBvGxMRVfs61oL2AAAARhBm6NJ4QpSZTAh
X/44QAAAC1c8EKtCjvA2P30sR1B1xoBoAV1abq3aseJqkte59QZr2DscaOto4eX1YP+q/ouxdL4b
j2wB6FHvMa2lRTiZhfUXUkENsyTAwG5eLyczKtTA7/faVaqjzDTmNk16ZjkIkR2AsMCO34O98f+S
FfsSUxgcTPpLCk+aCJUX9m7HV/2xCqpocgcr5XScFyIRyV8u7GZpUPdT7gAL/xZAQzvL/QcAASJ9
9zuEXgq4FFR+UbebPYdN4IutOmE+6wJqjZyC6KlXhtNNQlMm3ta+2PUoYq7ovFmHzBtTRmkgluop
t4EL7AJ9on6rfbNeeguRn/hBx3/h2u3QrbyEHhKdHw4UNjHEATfKOvJfAAAAokGfwUU0TCP/AAAK
h1SWIbggajLVYFkpJsIAB2gXLP7K4JEtat9YL0hpeN43BWrOmekhB1icCnWORvwaUj23hM8ykGO3
Ty0rN1o1dJ5Ubwqb4XzNNQFuwvb6KEaQ0e/Yr8kc85vnWL7h4f06Z9F4OhP1PEZ3GtGTyFklhfEn
+l/vcOLICRDlOwMm7BwZol0toUHdGD88j3PU0ZYLoni2aY2AmgAAAJ4Bn+B0R/8AABBWLuPxlN0Q
REbZv3YgA7jaacrkzrarXMRcj1vnCVerwJBh1y2g4zIQPQ6zTgM6yXkWW0YCPpYm3Wyu+jsJ3XUt
C/As+3IGCxLKxTeh0KZce3l/kdS6DAjmAEdOEW/daNO2IrG0s/2DB98ng7C2A8Sl0TGKLQFGiy5o
Txo0r8vNCecSKuZj4SdWFqHVzr58OszMVKi8TQAAAGIBn+JqR/8AABBfmCr6zXbHC8+7T6GAAlp+
VeV3fBfGvsLJK5bh28LIAUwk1TaAtcRsOqg4eC1oR0eFjvl1U8VGENBUeQgmM8PszVJ84DsjrHYj
2pv6FhoaqUrFWxGXOw4rUAAAAKVBm+dJqEFomUwI//yEAAADACeX7Tf8VPlsc/kf4AITkyZTDKRZ
DvOZgelJh2k6Hjf6q3fa1JWQoqznmfmYB3jNhafI86JoPyHXmSxx34z8rOy4m/OUyDH5gwmuEvz9
9/my4e/Z1EQeD6KsgYL6PmjRAjNnU8v+qk2BRX68Yv6yomleJjitcyl4R15lz+wwD3T4/fwabnDO
529LXjlR+Y1uzqMPrqsAAACaQZ4FRREsI/8AAAqIUdGscH5RHD8/r7+avUV7qACWC1OnXDZVdi3M
cWAu2akO8G12JMyv1XGr4UrYY20znHuXbgP2PFG2/XhuRY7ryLvWZkczvbiB6XOLyYXwofdsNxSu
SvMvPxyY7CVy/YpA3TllK0cAygi5wF78b+WvqpUuJwti1TCFUdbmInITbQ9MyzPLQUWweRdJPzJC
mQAAAFYBniR0R/8AABBWLuPxDjYYV03umjDwU+AEBauotnP6WOcyAAkjIR9ZBA+lyGfBVLaqS3Ie
fv//t+AINBJEJ05t9wHFZilWZO2K6eRQSRwDcAsF0KfJHQAAAD8BniZqR/8AABBfmCr6zXccxjfQ
rpqJtnqc5npM9jWara4AH4fvHW233eeJl7+1xpcGuFD+p0R8PpMfKRrk5k0AAAwbbW9vdgAAAGxt
dmhkAAAAAAAAAAAAAAAAAAAD6AAAD6AAAQAAAQAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAB
AAAAAAAAAAAAAAAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAC0V0cmFrAAAA
XHRraGQAAAADAAAAAAAAAAAAAAABAAAAAAAAD6AAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAA
AAAAAAABAAAAAAAAAAAAAAAAAABAAAAAASwAAAJYAAAAAAAkZWR0cwAAABxlbHN0AAAAAAAAAAEA
AA+gAAACAAABAAAAAAq9bWRpYQAAACBtZGhkAAAAAAAAAAAAAAAAAAAyAAAAyABVxAAAAAAALWhk
bHIAAAAAAAAAAHZpZGUAAAAAAAAAAAAAAABWaWRlb0hhbmRsZXIAAAAKaG1pbmYAAAAUdm1oZAAA
AAEAAAAAAAAAAAAAACRkaW5mAAAAHGRyZWYAAAAAAAAAAQAAAAx1cmwgAAAAAQAACihzdGJsAAAA
uHN0c2QAAAAAAAAAAQAAAKhhdmMxAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAASwCWABIAAAASAAA
AAAAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAGP//AAAANmF2Y0MBZAAe/+EA
GWdkAB6s2UEwTe5YQAAAAwBAAAAZA8WLZYABAAZo6+PLIsD9+PgAAAAAHHV1aWRraEDyXyRPxbo5
pRvPAyPzAAAAAAAAABhzdHRzAAAAAAAAAAEAAADIAAABAAAAABRzdHNzAAAAAAAAAAEAAAABAAAF
2GN0dHMAAAAAAAAAuQAAAAEAAAIAAAAAAQAABQAAAAABAAACAAAAAAEAAAAAAAAAAQAAAQAAAAAB
AAACAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAcA
AAIAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAAAQAA
AwAAAAABAAABAAAAAAEAAAIAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAAD
AAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEA
AAAAAQAABQAAAAABAAACAAAAAAEAAAAAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAAAQAABAAA
AAACAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAA
AAEAAAUAAAAAAQAAAgAAAAABAAAAAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAA
AQAAAQAAAAABAAAFAAAAAAEAAAIAAAAAAQAAAAAAAAABAAABAAAAAAEAAAUAAAAAAQAAAgAAAAAB
AAAAAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEA
AAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAIAAAAAAQAABAAAAAACAAABAAAAAAEAAAQAAAAAAgAA
AQAAAAABAAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAAD
AAAAAAEAAAEAAAAAAQAABAAAAAACAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEA
AAAAAQAAAwAAAAABAAABAAAAAAEAAAIAAAAAAQAAAwAAAAABAAABAAAAAAEAAAQAAAAAAgAAAQAA
AAABAAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAA
AAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAA
AQAAAwAAAAABAAABAAAAAAEAAAIAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAAB
AAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAAFAAAAAAEA
AAIAAAAAAQAAAAAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAADAAAAAAEAAAEAAAAAAQAA
AgAAAAABAAAFAAAAAAEAAAIAAAAAAQAAAAAAAAABAAABAAAAAAQAAAIAAAAAAQAABQAAAAABAAAC
AAAAAAEAAAAAAAAAAQAAAQAAAAABAAAFAAAAAAEAAAIAAAAAAQAAAAAAAAABAAABAAAAAAEAAAUA
AAAAAQAAAgAAAAABAAAAAAAAAAEAAAEAAAAAAQAABQAAAAABAAACAAAAAAEAAAAAAAAAAQAAAQAA
AAABAAADAAAAAAEAAAEAAAAAAQAAAwAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAAFAAAA
AAEAAAIAAAAAAQAAAAAAAAABAAABAAAAAAEAAAMAAAAAAQAAAQAAAAABAAACAAAAAAEAAAMAAAAA
AQAAAQAAAAABAAAFAAAAAAEAAAIAAAAAAQAAAAAAAAABAAABAAAAAAEAAAQAAAAAAgAAAQAAAAAB
AAACAAAAAAEAAAUAAAAAAQAAAgAAAAABAAAAAAAAAAEAAAEAAAAAAQAABQAAAAABAAACAAAAAAEA
AAAAAAAAAQAAAQAAAAAcc3RzYwAAAAAAAAABAAAAAQAAAMgAAAABAAADNHN0c3oAAAAAAAAAAAAA
AMgAADhQAAAJjwAAA54AAAISAAABgAAABFAAAAZLAAABsQAABiUAAAGnAAAGtgAAAaoAAAS+AAAF
JwAABRMAAAWyAAAGBAAABj4AAAYuAAAIWgAAAlkAAAhQAAACMAAACIMAAAIlAAAHsAAAAjQAAAYX
AAAH5gAAAhIAAAgWAAACiQAAB1IAAAIRAAAHMgAAAmUAAAgRAAACNgAAB/4AAAJjAAAJ9QAAA+sA
AAK3AAACxgAABz0AAAJcAAAIUAAAAxcAAAI7AAAGUQAAAkEAAAd0AAACYgAABs0AAAJyAAAJegAA
A6cAAAJGAAACtQAABy0AAAKPAAAG4AAAAtgAAAlIAAADxwAAAroAAAJpAAAI5AAAA5oAAAI9AAAC
FAAABogAAAJfAAAGCgAAAiUAAAZrAAACiAAABqMAAAKMAAAFCAAABsYAAAMJAAACjQAACBQAAANt
AAAC4QAAB2MAAAJCAAAF6gAAAgkAAAXJAAACJAAABiQAAAIRAAAHDQAAAsQAAAJVAAAGVAAAAlYA
AAZKAAACSQAABicAAAIrAAAFKwAABkYAAAJNAAAHnAAAA0UAAAKHAAAHEAAAAmIAAAYTAAACVAAA
BkQAAAJPAAAGiQAAAlMAAAZ3AAACXAAABuAAAAJvAAAF6QAAAjAAAAUyAAAB3wAABFkAAAV5AAAC
MQAABrcAAAJGAAAGkQAAAmEAAAauAAACaAAABhAAAAIMAAAHrQAAA40AAAJVAAAB+AAABewAAAIP
AAAFpQAAAeYAAAUoAAAIDAAAAzcAAAIaAAACCgAABE8AAARrAAAEjgAABHwAAAd0AAAC0AAAAcIA
AAHlAAAGzAAAAncAAAHZAAABowAABr4AAAJ7AAABZgAAAeEAAAY3AAACNgAAAbIAAAGiAAAECgAA
AW0AAANiAAABGQAAAwQAAAE3AAAD+gAAAYgAAAE0AAABIQAAAeQAAADtAAABmAAAAocAAAEjAAAC
eAAAARoAAADFAAAAwQAAAdkAAADnAAAAoAAAANkAAAEcAAAApgAAAKIAAABmAAAAqQAAAJ4AAABa
AAAAQwAAABRzdGNvAAAAAAAAAAEAAAAwAAAAYnVkdGEAAABabWV0YQAAAAAAAAAhaGRscgAAAAAA
AAAAbWRpcmFwcGwAAAAAAAAAAAAAAAAtaWxzdAAAACWpdG9vAAAAHWRhdGEAAAABAAAAAExhdmY2
MC4xNi4xMDA=
">
  Your browser does not support the video tag.
</video>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Solucionemos numericamente el problema 4.7 del blog: <a href="https://openstax.org/books/f%C3%ADsica-universitaria-volumen-1/pages/4-3-movimiento-de-proyectil#:~:text=El%20movimiento%20de%20proyectil%20es,f%C3%ADsica%20e%20ingenier%C3%ADa%20son%20numerosas">https://openstax.org/books/f%C3%ADsica-universitaria-volumen-1/pages/4-3-movimiento-de-proyectil#:~:text=El%20movimiento%20de%20proyectil%20es,f%C3%ADsica%20e%20ingenier%C3%ADa%20son%20numerosas</a>.</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
</body>







</html>
