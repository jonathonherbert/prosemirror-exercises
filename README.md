# prosemirror-exercises

Exercises for developers working with ProseMirror. They aim to help explore core ProseMirror concepts.

Here's a menu of exercises. PRs that add to this list, or implement list items that are unchecked, are welcomed.

## Exploring the document state

- [ ] Find all the paragraph nodes in a document.
- [ ] Find the start and end positions of a node containing a particular string.
- [ ] Find all the ranges in the document that cover nodes with a `Mark` of type `strong`.

## Making changes to document content

- [ ] Create a new `EditorState` by dispatching a `Transaction`.
- [ ] Amend a document by adding text.
- [ ] Amend a document by removing text. 
- [ ] Amend a document by adding a list.
- [ ] Amend a document by removing a list.

## Commands

- [ ] Create a command that styles the selected text with the `strong` `Mark`.
- [ ] Ensure the command does not interfere with the structure of the document.

## Plugins

- [ ] Create a new plugin that highlights ranges that contain a particular string.
- [ ] Create a new plugin that 'cleans up' the document, removing double spaces and converting single- and double-quotes to their curly equivalents.
