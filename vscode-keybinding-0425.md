// 将键绑定放在此文件中以覆盖默认值auto[]
[
    {
        "key": "f2",
        "command": "editor.action.nextMatchFindAction",
        "when": "editorFocus && findInputFocussed"
    },
    {
        "key": "enter",
        "command": "-editor.action.nextMatchFindAction",
        "when": "editorFocus && findInputFocussed"
    },
    {
        "key": "f1",
        "command": "editor.action.previousMatchFindAction",
        "when": "editorFocus && findInputFocussed"
    },
    {
        "key": "shift+enter",
        "command": "-editor.action.previousMatchFindAction",
        "when": "editorFocus && findInputFocussed"
    },
    {
        "key": "f1",
        "command": "editor.action.previousMatchFindAction",
        "when": "editorFocus"
    },
    {
        "key": "shift+f3",
        "command": "-editor.action.previousMatchFindAction",
        "when": "editorFocus"
    },
    {
        "key": "f2",
        "command": "editor.action.nextMatchFindAction",
        "when": "editorFocus"
    },
    {
        "key": "f3",
        "command": "-editor.action.nextMatchFindAction",
        "when": "editorFocus"
    },
    {
        "key": "f2",
        "command": "workbench.action.terminal.findNext",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "f3",
        "command": "-workbench.action.terminal.findNext",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+o ctrl+9",
        "command": "search.action.focusNextSearchResult",
        "when": "hasSearchResult || inSearchEditor"
    },
    {
        "key": "f4",
        "command": "-search.action.focusNextSearchResult",
        "when": "hasSearchResult || inSearchEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "references-view.next",
        "when": "reference-list.hasResult && references-view.canNavigate"
    },
    {
        "key": "f4",
        "command": "-references-view.next",
        "when": "reference-list.hasResult && references-view.canNavigate"
    },
    {
        "key": "ctrl+o ctrl+y",
        "command": "goToNextReference",
        "when": "inReferenceSearchEditor || referenceSearchVisible"
    },
    {
        "key": "f4",
        "command": "-goToNextReference",
        "when": "inReferenceSearchEditor || referenceSearchVisible"
    },
    {
        "key": "ctrl+1",
        "command": "highlight.selectedWords"
    },
    {
        "key": "shift+f8",
        "command": "-highlight.selectedWords"
    },
    {
        "key": "ctrl+f1",
        "command": "highlight.clearWords"
    },
    {
        "key": "ctrl+shift+f8",
        "command": "-highlight.clearWords"
    },
    {
        "key": "ctrl+o ctrl+numpad9",
        "command": "workbench.action.showCommands"
    },
    {
        "key": "f1",
        "command": "-workbench.action.showCommands"
    },
    {
        "key": "ctrl+q",
        "command": "workbench.action.quickOpen"
    },
    {
        "key": "ctrl+p",
        "command": "-workbench.action.quickOpen"
    },
    {
        "key": "ctrl+o p",
        "command": "workbench.action.quickOpenView"
    },
    {
        "key": "ctrl+q",
        "command": "-workbench.action.quickOpenView"
    },
    {
        "key": "numpad9",
        "command": "workbench.action.quickOpenNavigateNextInViewPicker",
        "when": "inQuickOpen && inViewsPicker"
    },
    {
        "key": "ctrl+q",
        "command": "-workbench.action.quickOpenNavigateNextInViewPicker",
        "when": "inQuickOpen && inViewsPicker"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "bookmarks.toggle",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+alt+k",
        "command": "-bookmarks.toggle",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "bookmarks.jumpToNext",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+alt+l",
        "command": "-bookmarks.jumpToNext",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "bookmarks.jumpToPrevious",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+alt+j",
        "command": "-bookmarks.jumpToPrevious",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "f2",
        "command": "-editor.action.rename",
        "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "debug.renameWatchExpression",
        "when": "watchExpressionsFocused"
    },
    {
        "key": "f2",
        "command": "-debug.renameWatchExpression",
        "when": "watchExpressionsFocused"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "debug.setVariable",
        "when": "variablesFocused"
    },
    {
        "key": "f2",
        "command": "-debug.setVariable",
        "when": "variablesFocused"
    },
    {
        "key": "ctrl+enter",
        "command": "remote.tunnel.label",
        "when": "tunnelViewFocus && tunnelType == 'Forwarded' && tunnelViewMultiSelection == 'undefined'"
    },
    {
        "key": "f2",
        "command": "-remote.tunnel.label",
        "when": "tunnelViewFocus && tunnelType == 'Forwarded' && tunnelViewMultiSelection == 'undefined'"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "renameFile",
        "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
    },
    {
        "key": "f2",
        "command": "-renameFile",
        "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "workbench.action.terminal.renameInstance",
        "when": "terminalHasBeenCreated && terminalTabsFocus && terminalTabsSingularSelection || terminalProcessSupported && terminalTabsFocus && terminalTabsSingularSelection"
    },
    {
        "key": "f2",
        "command": "-workbench.action.terminal.renameInstance",
        "when": "terminalHasBeenCreated && terminalTabsFocus && terminalTabsSingularSelection || terminalProcessSupported && terminalTabsFocus && terminalTabsSingularSelection"
    },
    {
        "key": "f5",
        "command": "workbench.action.debug.continue",
        "when": "debugState == 'stopped'"
    },
    {
        "key": "f5",
        "command": "-workbench.action.debug.continue",
        "when": "debugState == 'stopped'"
    },
    {
        "key": "ctrl+o ctrl+p",
        "command": "workbench.action.debug.start",
        "when": "debuggersAvailable && debugState == 'inactive'"
    },
    {
        "key": "f5",
        "command": "-workbench.action.debug.start",
        "when": "debuggersAvailable && debugState == 'inactive'"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "debug.openView",
        "when": "!debuggersAvailable"
    },
    {
        "key": "f5",
        "command": "-debug.openView",
        "when": "!debuggersAvailable"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "workbench.action.focusNextPart"
    },
    {
        "key": "f6",
        "command": "-workbench.action.focusNextPart"
    },
    {
        "key": "ctrl+p ctrl+numpad9",
        "command": "workbench.action.debug.pause",
        "when": "debugState == 'running'"
    },
    {
        "key": "f6",
        "command": "-workbench.action.debug.pause",
        "when": "debugState == 'running'"
    },
    {
        "key": "f1",
        "command": "workbench.action.terminal.findPrevious",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "shift+f3",
        "command": "-workbench.action.terminal.findPrevious",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.openNativeConsole",
        "when": "!terminalFocus"
    },
    {
        "key": "ctrl+shift+c",
        "command": "-workbench.action.terminal.openNativeConsole",
        "when": "!terminalFocus"
    },
    {
        "key": "alt+q",
        "command": "workbench.action.terminal.new",
        "when": "terminalProcessSupported"
    },
    {
        "key": "alt+e",
        "command": "workbench.action.terminal.kill"
    },
    {
        "key": "ctrl+t",
        "command": "workbench.action.closeActiveEditor"
    },
    {
        "key": "ctrl+w",
        "command": "-workbench.action.closeActiveEditor"
    },
    {
        "key": "ctrl+oem_plus",
        "command": "workbench.action.terminal.killEditor",
        "when": "terminalEditorFocus && terminalFocus && terminalHasBeenCreated && resourceScheme == 'vscode-terminal' || terminalEditorFocus && terminalFocus && terminalProcessSupported && resourceScheme == 'vscode-terminal'"
    },
    {
        "key": "ctrl+w",
        "command": "-workbench.action.terminal.killEditor",
        "when": "terminalEditorFocus && terminalFocus && terminalHasBeenCreated && resourceScheme == 'vscode-terminal' || terminalEditorFocus && terminalFocus && terminalProcessSupported && resourceScheme == 'vscode-terminal'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeGroup",
        "when": "activeEditorGroupEmpty && multipleEditorGroups"
    },
    {
        "key": "ctrl+w",
        "command": "-workbench.action.closeGroup",
        "when": "activeEditorGroupEmpty && multipleEditorGroups"
    },
    {
        "key": "ctrl+e",
        "command": "-workbench.action.quickOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.files.action.focusOpenEditorsView",
        "when": "workbench.explorer.openEditorsView.active"
    },
    {
        "key": "ctrl+9 e",
        "command": "-workbench.files.action.focusOpenEditorsView",
        "when": "workbench.explorer.openEditorsView.active"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickOpenNavigateNextInFilePicker",
        "when": "inFilesPicker && inQuickOpen"
    },
    {
        "key": "ctrl+e",
        "command": "-workbench.action.quickOpenNavigateNextInFilePicker",
        "when": "inFilesPicker && inQuickOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.showAllSymbols"
    },
    {
        "key": "ctrl+t",
        "command": "-workbench.action.showAllSymbols"
    },
    {
        "key": "alt+x",
        "command": "toggleSearchEditorWholeWord",
        "when": "inSearchEditor && searchInputBoxFocus"
    },
    {
        "key": "alt+w",
        "command": "-toggleSearchEditorWholeWord",
        "when": "inSearchEditor && searchInputBoxFocus"
    },
    {
        "key": "alt+z",
        "command": "toggleSearchEditorCaseSensitive",
        "when": "inSearchEditor && searchInputBoxFocus"
    },
    {
        "key": "alt+c",
        "command": "-toggleSearchEditorCaseSensitive",
        "when": "inSearchEditor && searchInputBoxFocus"
    },
    {
        "key": "ctrl+numpad2",
        "command": "workbench.action.terminal.resizePaneDown"
    },
    {
        "key": "ctrl+shift+r",
        "command": "workbench.action.togglePanel"
    },
    {
        "key": "ctrl+j",
        "command": "-workbench.action.togglePanel"
    },
    {
        "key": "ctrl+numpad9",
        "command": "gitlens.showQuickRepoStatus",
        "when": "!gitlens:disabled && config.gitlens.keymap == 'alternate'"
    },
    {
        "key": "alt+s",
        "command": "-gitlens.showQuickRepoStatus",
        "when": "!gitlens:disabled && config.gitlens.keymap == 'alternate'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.toggleTerminal",
        "when": "terminal.active"
    },
    {
        "key": "ctrl+oem_3",
        "command": "-workbench.action.terminal.toggleTerminal",
        "when": "terminal.active"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.clear"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.switchTerminal"
    },
    {
        "key": "ctrl+t",
        "command": "editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+k",
        "command": "-editor.action.deleteLines",
        "when": "textInputFocus && !editorReadonly"
    },
    {
        "key": "alt+v",
        "command": "editor.action.toggleColumnSelection"
    },
    {
        "key": "oem_3",
        "command": "workbench.action.terminal.clearSelection",
        "when": "terminalFocus && terminalHasBeenCreated && terminalTextSelected && !terminalFindVisible || terminalFocus && terminalProcessSupported && terminalTextSelected && !terminalFindVisible"
    },
    {
        "key": "escape",
        "command": "-workbench.action.terminal.clearSelection",
        "when": "terminalFocus && terminalHasBeenCreated && terminalTextSelected && !terminalFindVisible || terminalFocus && terminalProcessSupported && terminalTextSelected && !terminalFindVisible"
    },
    {
        "key": "ctrl+shift+f",
        "command": "-workbench.action.findInFiles"
    },
    {
        "key": "ctrl+numpad6",
        "command": "workbench.action.terminal.searchWorkspace",
        "when": "terminalFocus && terminalProcessSupported && terminalTextSelected"
    },
    {
        "key": "ctrl+shift+f",
        "command": "-workbench.action.terminal.searchWorkspace",
        "when": "terminalFocus && terminalProcessSupported && terminalTextSelected"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.view.search",
        "when": "workbench.view.search.active && neverMatch =~ /doesNotMatch/"
    },
    {
        "key": "ctrl+shift+f",
        "command": "-workbench.view.search",
        "when": "workbench.view.search.active && neverMatch =~ /doesNotMatch/"
    },
    {
        "key": "ctrl+numpad9",
        "command": "revealFileInOS",
        "when": "!editorFocus"
    },
    {
        "key": "shift+alt+r",
        "command": "-revealFileInOS",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.centerActiveCell",
        "when": "notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-notebook.centerActiveCell",
        "when": "notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "expandLineSelection",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-expandLineSelection",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+2",
        "command": "actions.find",
        "when": "editorFocus || editorIsOpen"
    },
    {
        "key": "ctrl+f",
        "command": "-actions.find",
        "when": "editorFocus || editorIsOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.wordHighlight.trigger"
    },
    {
        "key": "ctrl+w",
        "command": "editor.action.revealDefinition",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "f12",
        "command": "-editor.action.revealDefinition",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "notebook.cell.moveDown",
        "when": "notebookEditorFocused && !inputFocus"
    },
    {
        "key": "alt+down",
        "command": "-notebook.cell.moveDown",
        "when": "notebookEditorFocused && !inputFocus"
    },
    {
        "key": "ctrl+p ctrl+numpad9",
        "command": "notebook.cell.moveUp",
        "when": "notebookEditorFocused && !inputFocus"
    },
    {
        "key": "alt+up",
        "command": "-notebook.cell.moveUp",
        "when": "notebookEditorFocused && !inputFocus"
    },
    {
        "key": "ctrl+oem_7",
        "command": "editor.action.addCursorsToTop"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.addCursorsToBottom"
    },
    {
        "key": "ctrl+numpad9",
        "command": "cursorRedo"
    },
    {
        "key": "ctrl+numpad5",
        "command": "extension.cursor-jump",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+up",
        "command": "-extension.cursor-jump",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+up",
        "command": "cursorMove",
        "args": {
            "to": "up",
            "by": "line",
            "value": 7
        },
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+down",
        "command": "cursorMove",
        "args": {
            "to": "down",
            "by": "line",
            "value": 7
        },
        "when": "editorTextFocus"
    },
    {
        "key": "alt+up",
        "command": "workbench.action.terminal.navigationModeFocusPrevious",
        "when": "accessibilityModeEnabled && terminalA11yTreeFocus && terminalProcessSupported || accessibilityModeEnabled && terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+up",
        "command": "-workbench.action.terminal.navigationModeFocusPrevious",
        "when": "accessibilityModeEnabled && terminalA11yTreeFocus && terminalProcessSupported || accessibilityModeEnabled && terminalFocus && terminalProcessSupported"
    },
    {
        "key": "alt+up",
        "command": "workbench.action.terminal.scrollToPreviousCommand",
        "when": "terminalFocus && terminalHasBeenCreated && !accessibilityModeEnabled || terminalFocus && terminalProcessSupported && !accessibilityModeEnabled"
    },
    {
        "key": "ctrl+up",
        "command": "-workbench.action.terminal.scrollToPreviousCommand",
        "when": "terminalFocus && terminalHasBeenCreated && !accessibilityModeEnabled || terminalFocus && terminalProcessSupported && !accessibilityModeEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.moveLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "alt+up",
        "command": "-editor.action.moveLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "alt+down",
        "command": "-editor.action.moveLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "alt+up",
        "command": "scrollLineUp",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+up",
        "command": "-scrollLineUp",
        "when": "textInputFocus"
    },
    {
        "key": "alt+down",
        "command": "scrollLineDown",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+down",
        "command": "-scrollLineDown",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+shift+a",
        "command": "workbench.action.openSettings"
    },
    {
        "key": "ctrl+oem_comma",
        "command": "-workbench.action.openSettings"
    },
    {
        "key": "alt+q",
        "command": "openInTerminal"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.翻译选中文本"
    },
    {
        "key": "ctrl+b",
        "command": "workbench.action.toggleSidebarVisibility"
    },
    {
        "key": "ctrl+b",
        "command": "-workbench.action.toggleSidebarVisibility"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "markdown.extension.editing.toggleBold",
        "when": "editorTextFocus && !editorReadonly && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+b",
        "command": "-markdown.extension.editing.toggleBold",
        "when": "editorTextFocus && !editorReadonly && editorLangId == 'markdown'"
    },
    {
        "key": "alt+up",
        "command": "-extension.cursor-jump",
        "when": "editorTextFocus"
    },
    {
        "key": "f3",
        "command": "findWordAtCursor.next",
        "when": "editorTextFocus && !findWidgetVisible"
    },
    {
        "key": "f3",
        "command": "-findWordAtCursor.next",
        "when": "editorTextFocus && !findWidgetVisible"
    },
    {
        "key": "f2",
        "command": "findWordAtCursor.previous",
        "when": "editorTextFocus && !findWidgetVisible"
    },
    {
        "key": "shift+f3",
        "command": "-findWordAtCursor.previous",
        "when": "editorTextFocus && !findWidgetVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "list.find",
        "when": "listFocus && listSupportsFind"
    },
    {
        "key": "f3",
        "command": "-list.find",
        "when": "listFocus && listSupportsFind"
    },
    {
        "key": "alt+x",
        "command": "workbench.action.terminal.toggleFindWholeWord",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "alt+w",
        "command": "-workbench.action.terminal.toggleFindWholeWord",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "alt+x",
        "command": "toggleFindWholeWord",
        "when": "editorFocus"
    },
    {
        "key": "alt+w",
        "command": "-toggleFindWholeWord",
        "when": "editorFocus"
    },
    {
        "key": "alt+x",
        "command": "toggleSearchWholeWord",
        "when": "searchViewletFocus"
    },
    {
        "key": "alt+w",
        "command": "-toggleSearchWholeWord",
        "when": "searchViewletFocus"
    },
    {
        "key": "alt+c",
        "command": "editor.action.toggleWordWrap"
    },
    {
        "key": "alt+z",
        "command": "-editor.action.toggleWordWrap"
    },
    {
        "key": "alt+c",
        "command": "workbench.action.terminal.sizeToContentWidth",
        "when": "terminalFocus && terminalHasBeenCreated && terminalIsOpen || terminalFocus && terminalIsOpen && terminalProcessSupported"
    },
    {
        "key": "alt+z",
        "command": "-workbench.action.terminal.sizeToContentWidth",
        "when": "terminalFocus && terminalHasBeenCreated && terminalIsOpen || terminalFocus && terminalIsOpen && terminalProcessSupported"
    },
    {
        "key": "alt+z",
        "command": "toggleSearchCaseSensitive",
        "when": "searchViewletFocus"
    },
    {
        "key": "alt+c",
        "command": "-toggleSearchCaseSensitive",
        "when": "searchViewletFocus"
    },
    {
        "key": "alt+z",
        "command": "toggleFindCaseSensitive",
        "when": "editorFocus"
    },
    {
        "key": "alt+c",
        "command": "-toggleFindCaseSensitive",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+p ctrl+o",
        "command": "workbench.action.openEditorAtIndex1"
    },
    {
        "key": "alt+1",
        "command": "-workbench.action.openEditorAtIndex1"
    },
    {
        "key": "ctrl+f",
        "command": "actions.find",
        "when": "editorFocus || editorIsOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.showHover",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+9 ctrl+i",
        "command": "-editor.action.showHover",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+oem_2",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+oem_2",
        "command": "-editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "f1",
        "command": "workbench.action.terminal.findPrevious",
        "when": "terminalFindInputFocused && terminalHasBeenCreated || terminalFindInputFocused && terminalProcessSupported"
    },
    {
        "key": "enter",
        "command": "-workbench.action.terminal.findPrevious",
        "when": "terminalFindInputFocused && terminalHasBeenCreated || terminalFindInputFocused && terminalProcessSupported"
    },
    {
        "key": "f2",
        "command": "workbench.action.terminal.findNext",
        "when": "terminalFindInputFocused && terminalHasBeenCreated || terminalFindInputFocused && terminalProcessSupported"
    },
    {
        "key": "shift+enter",
        "command": "-workbench.action.terminal.findNext",
        "when": "terminalFindInputFocused && terminalHasBeenCreated || terminalFindInputFocused && terminalProcessSupported"
    },
    {
        "key": "alt+z",
        "command": "workbench.action.terminal.toggleFindCaseSensitive",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "alt+c",
        "command": "-workbench.action.terminal.toggleFindCaseSensitive",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+3",
        "command": "editor.action.clipboardCutAction"
    },
    {
        "key": "shift+delete",
        "command": "-editor.action.clipboardCutAction"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.formatCell",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && inCompositeEditor && notebookEditable && !editorReadonly && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "shift+alt+f",
        "command": "-notebook.formatCell",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && inCompositeEditor && notebookEditable && !editorReadonly && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "ctrl+t",
        "command": "editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    },
    {
        "key": "shift+alt+f",
        "command": "-editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.formatDocument.none",
        "when": "editorTextFocus && !editorHasDocumentFormattingProvider && !editorReadonly"
    },
    {
        "key": "shift+alt+f",
        "command": "-editor.action.formatDocument.none",
        "when": "editorTextFocus && !editorHasDocumentFormattingProvider && !editorReadonly"
    },
    {
        "key": "ctrl+9 ctrl+2",
        "command": "-editor.foldLevel2",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusSecondEditorGroup"
    },
    {
        "key": "ctrl+2",
        "command": "-workbench.action.focusSecondEditorGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.sendSequence",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+shift+2",
        "command": "-workbench.action.terminal.sendSequence",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.accessibleDiffViewer.next",
        "when": "isInDiffEditor"
    },
    {
        "key": "f7",
        "command": "-editor.action.accessibleDiffViewer.next",
        "when": "isInDiffEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.wordHighlight.next",
        "when": "editorTextFocus && hasWordHighlights"
    },
    {
        "key": "f7",
        "command": "-editor.action.wordHighlight.next",
        "when": "editorTextFocus && hasWordHighlights"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.accessibleViewDisableHint",
        "when": "accessibilityHelpIsShown && accessibleViewVerbosityEnabled || accessibleViewIsShown && accessibleViewVerbosityEnabled"
    },
    {
        "key": "alt+f6",
        "command": "-editor.action.accessibleViewDisableHint",
        "when": "accessibilityHelpIsShown && accessibleViewVerbosityEnabled || accessibleViewIsShown && accessibleViewVerbosityEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.accessibleViewAcceptInlineCompletion",
        "when": "accessibleViewIsShown && accessibleViewCurrentProviderId == 'inlineCompletions'"
    },
    {
        "key": "ctrl+oem_2",
        "command": "-editor.action.accessibleViewAcceptInlineCompletion",
        "when": "accessibleViewIsShown && accessibleViewCurrentProviderId == 'inlineCompletions'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "toggleExplainMode",
        "when": "suggestWidgetVisible"
    },
    {
        "key": "ctrl+oem_2",
        "command": "-toggleExplainMode",
        "when": "suggestWidgetVisible"
    },
    {
        "key": "ctrl+oem_2",
        "command": "-workbench.action.terminal.sendSequence",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.addCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+9 ctrl+c",
        "command": "-editor.action.addCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.editor.changeLanguageMode",
        "when": "!notebookEditorFocused"
    },
    {
        "key": "ctrl+9 m",
        "command": "-workbench.action.editor.changeLanguageMode",
        "when": "!notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.addComment"
    },
    {
        "key": "ctrl+9 ctrl+alt+c",
        "command": "-workbench.action.addComment"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.nextCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+9 ctrl+alt+down",
        "command": "-editor.action.nextCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.previousCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+9 ctrl+alt+up",
        "command": "-editor.action.previousCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.createFoldingRangeFromSelection",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+oem_comma",
        "command": "-editor.createFoldingRangeFromSelection",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.debug.action.showDebugHover",
        "when": "editorTextFocus && inDebugMode"
    },
    {
        "key": "ctrl+9 ctrl+i",
        "command": "-editor.debug.action.showDebugHover",
        "when": "editorTextFocus && inDebugMode"
    },
    {
        "key": "ctrl+enter numpad9",
        "command": "editor.action.defineKeybinding",
        "when": "resource == 'vscode-userdata:/c%3A/Users/17121/AppData/Roaming/Code/User/keybindings.json'"
    },
    {
        "key": "ctrl+9 ctrl+9",
        "command": "-editor.action.defineKeybinding",
        "when": "resource == 'vscode-userdata:/c%3A/Users/17121/AppData/Roaming/Code/User/keybindings.json'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.files.action.compareWithClipboard"
    },
    {
        "key": "ctrl+9 c",
        "command": "-workbench.files.action.compareWithClipboard"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.files.action.compareWithSaved"
    },
    {
        "key": "ctrl+9 d",
        "command": "-workbench.files.action.compareWithSaved"
    },
    {
        "key": "ctrl+numpad9",
        "command": "copyRelativeFilePath",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+9 ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "copyRelativeFilePath",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+9 ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.files.openFolder",
        "when": "openFolderWorkspaceSupport"
    },
    {
        "key": "ctrl+9 ctrl+o",
        "command": "-workbench.action.files.openFolder",
        "when": "openFolderWorkspaceSupport"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.files.saveWithoutFormatting"
    },
    {
        "key": "ctrl+9 ctrl+shift+s",
        "command": "-workbench.action.files.saveWithoutFormatting"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.showAllEditors"
    },
    {
        "key": "ctrl+9 ctrl+p",
        "command": "-workbench.action.showAllEditors"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+0",
        "command": "-editor.foldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldAllBlockComments",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+oem_2",
        "command": "-editor.foldAllBlockComments",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "numpad9",
        "command": "editor.foldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+oem_minus",
        "command": "-editor.foldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+8",
        "command": "-editor.foldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "numpad9",
        "command": "editor.foldLevel1",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+1",
        "command": "-editor.foldLevel1",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel3",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+3",
        "command": "-editor.foldLevel3",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel4",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+4",
        "command": "-editor.foldLevel4",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel5",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+5",
        "command": "-editor.foldLevel5",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel6",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+6",
        "command": "-editor.foldLevel6",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel7",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+7",
        "command": "-editor.foldLevel7",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+9 ctrl+oem_4",
        "command": "-editor.foldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.formatSelection",
        "when": "editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+9 ctrl+f",
        "command": "-editor.action.formatSelection",
        "when": "editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "git.revertSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+9 ctrl+r",
        "command": "-git.revertSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "git.stageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+9 ctrl+alt+s",
        "command": "-git.stageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "git.unstageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+9 ctrl+n",
        "command": "-git.unstageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "ctrl+9 ctrl+q",
        "command": "-workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.keybindingsReference"
    },
    {
        "key": "ctrl+9 ctrl+r",
        "command": "-workbench.action.keybindingsReference"
    },
    {
        "key": "numpad9",
        "command": "inlineChat.start",
        "when": "editorFocus && inlineChatHasProvider && !editorReadonly"
    },
    {
        "key": "ctrl+9 i",
        "command": "-inlineChat.start",
        "when": "editorFocus && inlineChatHasProvider && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "inlineChat.quickVoice.start",
        "when": "editorFocus && hasSpeechProvider && !inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+9 i",
        "command": "-inlineChat.quickVoice.start",
        "when": "editorFocus && hasSpeechProvider && !inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "inlineChat.quickVoice.stop",
        "when": "hasSpeechProvider && inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+9 i",
        "command": "-inlineChat.quickVoice.stop",
        "when": "hasSpeechProvider && inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "markdown.showPreviewToSide",
        "when": "!notebookEditorFocused && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+9 v",
        "command": "-markdown.showPreviewToSide",
        "when": "!notebookEditorFocused && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.moveSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+9 ctrl+d",
        "command": "-editor.action.moveSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.collapseCellInput",
        "when": "notebookCellListFocused && !inputFocus && !notebookCellInputIsCollapsed"
    },
    {
        "key": "ctrl+9 ctrl+c",
        "command": "-notebook.cell.collapseCellInput",
        "when": "notebookCellListFocused && !inputFocus && !notebookCellInputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.collapseCellOutput",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus && !notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+9 t",
        "command": "-notebook.cell.collapseCellOutput",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus && !notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.expandCellInput",
        "when": "notebookCellInputIsCollapsed && notebookCellListFocused"
    },
    {
        "key": "ctrl+9 ctrl+c",
        "command": "-notebook.cell.expandCellInput",
        "when": "notebookCellInputIsCollapsed && notebookCellListFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.expandCellOutput",
        "when": "notebookCellListFocused && notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+9 t",
        "command": "-notebook.cell.expandCellOutput",
        "when": "notebookCellListFocused && notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.split",
        "when": "editorTextFocus && notebookCellEditable && notebookEditable && notebookEditorFocused"
    },
    {
        "key": "ctrl+9 ctrl+shift+oem_5",
        "command": "-notebook.cell.split",
        "when": "editorTextFocus && notebookCellEditable && notebookEditable && notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.cell.toggleOutputScrolling",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus"
    },
    {
        "key": "ctrl+9 y",
        "command": "-notebook.cell.toggleOutputScrolling",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notifications.showList"
    },
    {
        "key": "ctrl+9 ctrl+shift+n",
        "command": "-notifications.showList"
    },
    {
        "key": "ctrl+numpad9 ctrl+enter",
        "command": "editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+9 f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && isWeb && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+9 ctrl+f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && isWeb && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.selectTheme"
    },
    {
        "key": "ctrl+9 ctrl+t",
        "command": "-workbench.action.selectTheme"
    },
    {
        "key": "ctrl+oem_3",
        "command": "toggleVim"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+x",
        "when": "editorTextFocus && vim.active && vim.use<C-x> && !inDebugRepl"
    },
    {
        "key": "ctrl+x",
        "command": "-extension.vim_ctrl+x",
        "when": "editorTextFocus && vim.active && vim.use<C-x> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+z",
        "when": "editorTextFocus && vim.active && vim.use<C-z> && !inDebugRepl"
    },
    {
        "key": "ctrl+z",
        "command": "-extension.vim_ctrl+z",
        "when": "editorTextFocus && vim.active && vim.use<C-z> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+s",
        "when": "editorTextFocus && vim.active && vim.use<C-s> && !inDebugRepl"
    },
    {
        "key": "ctrl+s",
        "command": "-extension.vim_ctrl+s",
        "when": "editorTextFocus && vim.active && vim.use<C-s> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+p",
        "when": "editorTextFocus && vim.active && vim.use<C-p> && !inDebugRepl || vim.active && vim.use<C-p> && !inDebugRepl && vim.mode == 'CommandlineInProgress' || vim.active && vim.use<C-p> && !inDebugRepl && vim.mode == 'SearchInProgressMode'"
    },
    {
        "key": "ctrl+p",
        "command": "-extension.vim_ctrl+p",
        "when": "editorTextFocus && vim.active && vim.use<C-p> && !inDebugRepl || vim.active && vim.use<C-p> && !inDebugRepl && vim.mode == 'CommandlineInProgress' || vim.active && vim.use<C-p> && !inDebugRepl && vim.mode == 'SearchInProgressMode'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+v",
        "when": "editorTextFocus && vim.active && vim.use<C-v> && !inDebugRepl"
    },
    {
        "key": "ctrl+v",
        "command": "-extension.vim_ctrl+v",
        "when": "editorTextFocus && vim.active && vim.use<C-v> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+a",
        "when": "editorTextFocus && vim.active && vim.use<C-a> && !inDebugRepl"
    },
    {
        "key": "ctrl+a",
        "command": "-extension.vim_ctrl+a",
        "when": "editorTextFocus && vim.active && vim.use<C-a> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.toggleDevTools",
        "when": "isDevelopment"
    },
    {
        "key": "ctrl+shift+i",
        "command": "-workbench.action.toggleDevTools",
        "when": "isDevelopment"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickchat.toggle",
        "when": "hasChatProvider"
    },
    {
        "key": "ctrl+shift+i",
        "command": "-workbench.action.quickchat.toggle",
        "when": "hasChatProvider"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+e",
        "when": "editorTextFocus && vim.active && vim.use<C-e> && !inDebugRepl"
    },
    {
        "key": "ctrl+e",
        "command": "-extension.vim_ctrl+e",
        "when": "editorTextFocus && vim.active && vim.use<C-e> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "testing.debugFailTests"
    },
    {
        "key": "ctrl+oem_1 ctrl+e",
        "command": "-testing.debugFailTests"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.toggleScreenReaderAccessibilityMode",
        "when": "accessibilityHelpIsShown"
    },
    {
        "key": "ctrl+e",
        "command": "-editor.action.toggleScreenReaderAccessibilityMode",
        "when": "accessibilityHelpIsShown"
    },
    {
        "key": "ctrl+e",
        "command": "workbench.action.navigateForward",
        "when": "canNavigateForward"
    },
    {
        "key": "alt+right",
        "command": "-workbench.action.navigateForward",
        "when": "canNavigateForward"
    },
    {
        "key": "ctrl+d",
        "command": "workbench.action.navigateBack",
        "when": "canNavigateBack"
    },
    {
        "key": "alt+left",
        "command": "-workbench.action.navigateBack",
        "when": "canNavigateBack"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.addSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+d",
        "command": "-editor.action.addSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+d",
        "when": "editorTextFocus && vim.active && vim.use<C-d> && !inDebugRepl"
    },
    {
        "key": "ctrl+d",
        "command": "-extension.vim_ctrl+d",
        "when": "editorTextFocus && vim.active && vim.use<C-d> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "list.focusPageDown",
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+d",
        "command": "-list.focusPageDown",
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.openRecent"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.openRecent"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.reloadWindow",
        "when": "isDevelopment"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.reloadWindow",
        "when": "isDevelopment"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.runRecentCommand",
        "when": "accessibilityModeEnabled && terminalFocus && terminalHasBeenCreated || accessibilityModeEnabled && terminalFocus && terminalProcessSupported || accessibilityModeEnabled && accessibleViewIsShown && terminalHasBeenCreated && accessibleViewCurrentProviderId == 'terminal' || accessibilityModeEnabled && accessibleViewIsShown && terminalProcessSupported && accessibleViewCurrentProviderId == 'terminal'"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.terminal.runRecentCommand",
        "when": "accessibilityModeEnabled && terminalFocus && terminalHasBeenCreated || accessibilityModeEnabled && terminalFocus && terminalProcessSupported || accessibilityModeEnabled && accessibleViewIsShown && terminalHasBeenCreated && accessibleViewCurrentProviderId == 'terminal' || accessibilityModeEnabled && accessibleViewIsShown && terminalProcessSupported && accessibleViewCurrentProviderId == 'terminal'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+r",
        "when": "editorTextFocus && vim.active && vim.use<C-r> && !inDebugRepl"
    },
    {
        "key": "ctrl+r",
        "command": "-extension.vim_ctrl+r",
        "when": "editorTextFocus && vim.active && vim.use<C-r> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickOpenNavigateNextInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.quickOpenNavigateNextInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
    },
    {
        "key": "ctrl+r",
        "command": "workbench.action.findInFiles"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+space",
        "when": "editorTextFocus && vim.active && vim.use<C-space> && !inDebugRepl && vim.mode != 'Insert'"
    },
    {
        "key": "ctrl+space",
        "command": "-extension.vim_ctrl+space",
        "when": "editorTextFocus && vim.active && vim.use<C-space> && !inDebugRepl && vim.mode != 'Insert'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_cmd+c",
        "when": "editorTextFocus && vim.active && vim.overrideCopy && vim.use<D-c> && !inDebugRepl"
    },
    {
        "key": "win+c",
        "command": "-extension.vim_cmd+c",
        "when": "editorTextFocus && vim.active && vim.overrideCopy && vim.use<D-c> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_cmd+d",
        "when": "editorTextFocus && vim.active && vim.use<D-d> && !inDebugRepl"
    },
    {
        "key": "win+d",
        "command": "-extension.vim_cmd+d",
        "when": "editorTextFocus && vim.active && vim.use<D-d> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+numpad9",
        "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-extension.vim_ctrl+numpad9",
        "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+c",
        "when": "editorTextFocus && vim.active && vim.overrideCtrlC && vim.use<C-c> && !inDebugRepl"
    },
    {
        "key": "ctrl+c",
        "command": "-extension.vim_ctrl+c",
        "when": "editorTextFocus && vim.active && vim.overrideCtrlC && vim.use<C-c> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "list.stickyScrolltoggleExpand",
        "when": "treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-list.stickyScrolltoggleExpand",
        "when": "treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notification.toggle",
        "when": "notificationFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-notification.toggle",
        "when": "notificationFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "list.toggleExpand",
        "when": "listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-list.toggleExpand",
        "when": "listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "refactorPreview.toggleCheckedState",
        "when": "listFocus && refactorPreview.enabled && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-refactorPreview.toggleCheckedState",
        "when": "listFocus && refactorPreview.enabled && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "filesExplorer.openFilePreserveFocus",
        "when": "filesExplorerFocus && foldersViewVisible && !explorerResourceIsFolder && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-filesExplorer.openFilePreserveFocus",
        "when": "filesExplorerFocus && foldersViewVisible && !explorerResourceIsFolder && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "debug.toggleBreakpoint",
        "when": "breakpointsFocused && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-debug.toggleBreakpoint",
        "when": "breakpointsFocused && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "breadcrumbs.revealFocused",
        "when": "breadcrumbsActive && breadcrumbsVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-breadcrumbs.revealFocused",
        "when": "breadcrumbsActive && breadcrumbsVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+j",
        "when": "editorTextFocus && vim.active && vim.use<C-j> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-extension.vim_ctrl+j",
        "when": "editorTextFocus && vim.active && vim.use<C-j> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.chat.newChat",
        "when": "hasChatProvider && inChat"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-workbench.action.chat.newChat",
        "when": "hasChatProvider && inChat"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_navigateCtrlL",
        "when": "editorTextFocus && vim.active && vim.use<C-l> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-extension.vim_navigateCtrlL",
        "when": "editorTextFocus && vim.active && vim.use<C-l> && !inDebugRepl"
    },
    {
        "key": "ctrl",
        "command": "editor.action.toggleTabFocusMode"
    },
    {
        "key": "ctrl+m",
        "command": "-editor.action.toggleTabFocusMode"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+m",
        "when": "editorTextFocus && vim.active && vim.use<C-m> && !inDebugRepl || vim.active && vim.use<C-m> && !inDebugRepl && vim.mode == 'CommandlineInProgress' || vim.active && vim.use<C-m> && !inDebugRepl && vim.mode == 'SearchInProgressMode'"
    },
    {
        "key": "ctrl+m",
        "command": "-extension.vim_ctrl+m",
        "when": "editorTextFocus && vim.active && vim.use<C-m> && !inDebugRepl || vim.active && vim.use<C-m> && !inDebugRepl && vim.mode == 'CommandlineInProgress' || vim.active && vim.use<C-m> && !inDebugRepl && vim.mode == 'SearchInProgressMode'"
    },
    {
        "key": "ctrl+numpad9 m",
        "command": "-workbench.action.editor.changeLanguageMode",
        "when": "!notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.toggleMaximizeEditorGroup",
        "when": "editorPartMaximizedEditorGroup || editorPartMultipleEditorGroups"
    },
    {
        "key": "ctrl+numpad9 ctrl+m",
        "command": "-workbench.action.toggleMaximizeEditorGroup",
        "when": "editorPartMaximizedEditorGroup || editorPartMultipleEditorGroups"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.unfoldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+j",
        "command": "-editor.unfoldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.search.toggleQueryDetails",
        "when": "inSearchEditor || searchViewletFocus"
    },
    {
        "key": "ctrl+shift+j",
        "command": "-workbench.action.search.toggleQueryDetails",
        "when": "inSearchEditor || searchViewletFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "addCursorsAtSearchResults",
        "when": "fileMatchOrMatchFocus && searchViewletVisible"
    },
    {
        "key": "ctrl+shift+l",
        "command": "-addCursorsAtSearchResults",
        "when": "fileMatchOrMatchFocus && searchViewletVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.showTreeHover",
        "when": "customTreeView && listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9 ctrl+i",
        "command": "-workbench.action.showTreeHover",
        "when": "customTreeView && listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        // "key": "space",
        "command": "-list.stickyScrolltoggleExpand",
        "when": "treestickyScrollFocused"
    },
    {
        // "key": "space",
        "command": "-list.toggleExpand",
        "when": "listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        // "key": "space",
        "command": "-notification.toggle",
        "when": "notificationFocus"
    },
    {
        // "key": "space",
        "command": "-refactorPreview.toggleCheckedState",
        "when": "listFocus && refactorPreview.enabled && !inputFocus && !treestickyScrollFocused"
    },
    {
        // "key": "space",
        "command": "-debug.toggleBreakpoint",
        "when": "breakpointsFocused && !inputFocus"
    },
    {
        // "key": "space",
        "command": "-breadcrumbs.revealFocused",
        "when": "breadcrumbsActive && breadcrumbsVisible"
    },
    {
        "key": "shift+backspace",
        "command": "-deleteLeft",
        "when": "textInputFocus"
    },
    {
        // "key": "space",
        "command": "-filesExplorer.openFilePreserveFocus",
        "when": "filesExplorerFocus && foldersViewVisible && !explorerResourceIsFolder && !inputFocus"
    },
    {
        "key": "ctrl+alt+e",
        "command": "-blamer-vs.toggleBlame",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+alt+d",
        "command": "-blamer-vs.showBlame",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+shift+2",
        "when": "editorTextFocus && vim.active && vim.use<C-shift+2>"
    },
    {
        "key": "ctrl+shift+2",
        "command": "-extension.vim_ctrl+shift+2",
        "when": "editorTextFocus && vim.active && vim.use<C-shift+2>"
    },
    {
        "key": "ctrl+alt+oem_2",
        "command": "-metaGo.addCursorSmart"
    },
    {
        "key": "alt+b",
        "command": "-metaGo.scrollCurrentLineToBottom",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+m",
        "command": "-metaGo.scrollCurrentLineToMiddle",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+t",
        "command": "-metaGo.scrollCurrentLineToTop",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+end",
        "command": "-metaGo.selectEmptyLineDown",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+home",
        "command": "-metaGo.gotoEmptyLineUp",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+home",
        "command": "-metaGo.selectEmptyLineUp",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+l",
        "command": "-metaGo.selectLineDown",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+o",
        "command": "-metaGo.selectLineUp",
        "when": "editorHasSelection && textInputFocus"
    },
    {
        "key": "shift+alt+oem_period",
        "command": "-metaGo.selectAfter",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+oem_comma",
        "command": "-metaGo.selectBefore",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+oem_2",
        "command": "-metaGo.selectSmart",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+a",
        "command": "-metaGo.selectionSwitchActiveWithAnchor",
        "when": "editorHasSelection && editorTextFocus"
    },
    {
        "key": "escape",
        "command": "-metaGo.input.cancel",
        "when": "editorTextFocus && metaGoInput"
    },
    {
        "key": "shift+space",
        "command": "-metaGo.metaJump.hideDecoration",
        "when": "editorTextFocus && metaGoJumping"
    },
    {
        "key": "backspace",
        "command": "-metaGo.metaJump.backspace",
        "when": "editorTextFocus && metaGoJumping"
    },
    {
        "key": "alt+oem_6",
        "command": "-metaGo.bookmark.next",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+oem_4",
        "command": "-metaGo.bookmark.previous",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+win+home",
        "command": "-metaGo.cursorSpaceWordSpaceLeft",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+home",
        "command": "-metaGo.cursorSpaceWordSpaceLeftSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+win+end",
        "command": "-metaGo.cursorSpaceWordSpaceRight",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+end",
        "command": "-metaGo.cursorSpaceWordSpaceRightSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+shift+oem_5",
        "command": "-metaGo.jumpToBracket",
        "when": "editorTextFocus"
    },
    {
        "key": "tab",
        "command": "-metaGo.metaJump.tab",
        "when": "editorTextFocus && metaGoJumping"
    },
    {
        "key": "ctrl+alt+p",
        "command": "-metaGo.inSurroundingPairSelectionWithPairs",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+p",
        "command": "-metaGo.inSurroundingPairSelection",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+p",
        "command": "-metaGo.changeSurroundingPair",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+oem_7",
        "command": "-metaGo.bookmark.toggle",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+oem_5",
        "command": "-metaGo.bookmark.view"
    },
    {
        "key": "alt+win+left",
        "command": "-metaGo.cursorSpaceWordLeft",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+win+backspace",
        "command": "-metaGo.cursorSpaceWordLeftDelete",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+left",
        "command": "-metaGo.cursorSpaceWordLeftSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+win+right",
        "command": "-metaGo.cursorSpaceWordRight",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+win+delete",
        "command": "-metaGo.cursorSpaceWordRightDelete",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+right",
        "command": "-metaGo.cursorSpaceWordRightSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+backspace",
        "command": "-metaGo.cursorSpaceWordSpaceLeftDelete",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+win+delete",
        "command": "-metaGo.cursorSpaceWordSpaceRightDelete",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+delete",
        "command": "-metaGo.metaJump.deleteToAfter",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+backspace",
        "command": "-metaGo.metaJump.deleteToBefore",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+d",
        "command": "-metaGo.metaJump.deleteToSmart",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+oem_period",
        "command": "-metaGo.gotoAfter"
    },
    {
        "key": "alt+oem_comma",
        "command": "-metaGo.gotoBefore"
    },
    {
        "key": "alt+end",
        "command": "-metaGo.gotoEmptyLineDown",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+o",
        "command": "metaGo.gotoSmart"
    },
    {
        "key": "alt+oem_2",
        "command": "-metaGo.gotoSmart"
    },
    {
        "key": "ctrl+alt+oem_period",
        "command": "-metaGo.addCursorAfter"
    },
    {
        "key": "ctrl+alt+oem_comma",
        "command": "-metaGo.addCursorBefore"
    },
    {
        "key": "ctrl+numpad9 ctrl+c",
        "command": "-editor.action.addCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9 m",
        "command": "-workbench.action.editor.changeLanguageMode",
        "when": "!notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9 ctrl+alt+c",
        "command": "-workbench.action.addComment"
    },
    {
        "key": "ctrl+numpad9 ctrl+alt+down",
        "command": "-editor.action.nextCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+numpad9 ctrl+alt+up",
        "command": "-editor.action.previousCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_comma",
        "command": "-editor.createFoldingRangeFromSelection",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+i",
        "command": "-editor.debug.action.showDebugHover",
        "when": "editorTextFocus && inDebugMode"
    },
    {
        "key": "ctrl+numpad9 ctrl+numpad9",
        "command": "-editor.action.defineKeybinding",
        "when": "resource == 'vscode-userdata:/c%3A/Users/Administrator/AppData/Roaming/Code/User/keybindings.json'"
    },
    {
        "key": "ctrl+numpad9 e",
        "command": "-workbench.files.action.focusOpenEditorsView",
        "when": "workbench.explorer.openEditorsView.active"
    },
    {
        "key": "ctrl+numpad9 c",
        "command": "-workbench.files.action.compareWithClipboard"
    },
    {
        "key": "ctrl+numpad9 d",
        "command": "-workbench.files.action.compareWithSaved"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+o",
        "command": "-workbench.action.files.openFolder",
        "when": "openFolderWorkspaceSupport"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+s",
        "command": "-workbench.action.files.saveWithoutFormatting"
    },
    {
        "key": "ctrl+numpad9 ctrl+p",
        "command": "-workbench.action.showAllEditors"
    },
    {
        "key": "ctrl+numpad9 ctrl+0",
        "command": "-editor.foldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_2",
        "command": "-editor.foldAllBlockComments",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_minus",
        "command": "-editor.foldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+8",
        "command": "-editor.foldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+1",
        "command": "-editor.foldLevel1",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+2",
        "command": "-editor.foldLevel2",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+3",
        "command": "-editor.foldLevel3",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+4",
        "command": "-editor.foldLevel4",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+5",
        "command": "-editor.foldLevel5",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+6",
        "command": "-editor.foldLevel6",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+7",
        "command": "-editor.foldLevel7",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_4",
        "command": "-editor.foldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+f",
        "command": "-editor.action.formatSelection",
        "when": "editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9 ctrl+r",
        "command": "-git.revertSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9 ctrl+alt+s",
        "command": "-git.stageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9 ctrl+n",
        "command": "-git.unstageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+numpad9 ctrl+q",
        "command": "-workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "ctrl+numpad9 ctrl+r",
        "command": "-workbench.action.keybindingsReference"
    },
    {
        "key": "ctrl+numpad9 i",
        "command": "-inlineChat.start",
        "when": "editorFocus && inlineChatHasProvider && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9 i",
        "command": "-inlineChat.quickVoice.start",
        "when": "editorFocus && hasSpeechProvider && !inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+numpad9 i",
        "command": "-inlineChat.quickVoice.stop",
        "when": "hasSpeechProvider && inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+numpad9 v",
        "command": "-markdown.showPreviewToSide",
        "when": "!notebookEditorFocused && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+numpad9 ctrl+d",
        "command": "-editor.action.moveSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+c",
        "command": "-notebook.cell.collapseCellInput",
        "when": "notebookCellListFocused && !inputFocus && !notebookCellInputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9 t",
        "command": "-notebook.cell.collapseCellOutput",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus && !notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9 ctrl+c",
        "command": "-notebook.cell.expandCellInput",
        "when": "notebookCellInputIsCollapsed && notebookCellListFocused"
    },
    {
        "key": "ctrl+numpad9 t",
        "command": "-notebook.cell.expandCellOutput",
        "when": "notebookCellListFocused && notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+oem_5",
        "command": "-notebook.cell.split",
        "when": "editorTextFocus && notebookCellEditable && notebookEditable && notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9 y",
        "command": "-notebook.cell.toggleOutputScrolling",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+n",
        "command": "-notifications.showList"
    },
    {
        "key": "ctrl+numpad9 f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+numpad9 ctrl+f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && isWeb && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+numpad9 ctrl+t",
        "command": "-workbench.action.selectTheme"
    },
    {
        "key": "ctrl+numpad9 ctrl+s",
        "command": "-workbench.action.openGlobalKeybindings"
    },
    {
        "key": "ctrl+numpad9 ctrl+u",
        "command": "-editor.action.removeCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_period",
        "command": "-editor.removeManualFoldingRanges",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+numpad9",
        "command": "-editor.action.selectFromAnchorToCursor",
        "when": "editorTextFocus && selectionAnchorSet"
    },
    {
        "key": "ctrl+numpad9 ctrl+b",
        "command": "-editor.action.setSelectionAnchor",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+i",
        "command": "-editor.action.showHover",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+i",
        "command": "-workbench.action.terminal.focusHover",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalIsOpen || terminalFocus && terminalProcessSupported || terminalHasBeenCreated && terminalTabsFocus || terminalIsOpen && terminalTabsFocus || terminalProcessSupported && terminalTabsFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+l",
        "command": "-editor.toggleFold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+x",
        "command": "-editor.action.trimTrailingWhitespace",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9 ctrl+j",
        "command": "-editor.unfoldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_plus",
        "command": "-editor.unfoldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+9",
        "command": "-editor.unfoldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_6",
        "command": "-editor.unfoldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+w",
        "command": "-workbench.action.closeAllGroups"
    },
    {
        "key": "ctrl+numpad9 ctrl+w",
        "command": "-workbench.action.closeAllEditors"
    },
    {
        "key": "ctrl+numpad9 w",
        "command": "-workbench.action.closeEditorsInGroup"
    },
    {
        "key": "ctrl+numpad9 u",
        "command": "-workbench.action.closeUnmodifiedEditors"
    },
    {
        "key": "ctrl+numpad9 o",
        "command": "-workbench.action.copyEditorToNewWindow",
        "when": "activeEditor"
    },
    {
        "key": "ctrl+numpad9 ctrl+up",
        "command": "-workbench.action.focusAboveGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+down",
        "command": "-workbench.action.focusBelowGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+left",
        "command": "-workbench.action.focusLeftGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+right",
        "command": "-workbench.action.focusRightGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+oem_5",
        "command": "-workbench.action.joinEditorInGroup",
        "when": "sideBySideEditorActive"
    },
    {
        "key": "ctrl+numpad9 enter",
        "command": "-workbench.action.keepEditor"
    },
    {
        "key": "ctrl+numpad9 down",
        "command": "-workbench.action.moveActiveEditorGroupDown"
    },
    {
        "key": "ctrl+numpad9 left",
        "command": "-workbench.action.moveActiveEditorGroupLeft"
    },
    {
        "key": "ctrl+numpad9 right",
        "command": "-workbench.action.moveActiveEditorGroupRight"
    },
    {
        "key": "ctrl+numpad9 up",
        "command": "-workbench.action.moveActiveEditorGroupUp"
    },
    {
        "key": "ctrl+numpad9 ctrl+right",
        "command": "-workbench.action.moveEditorToNextGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+left",
        "command": "-workbench.action.moveEditorToPreviousGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+pagedown",
        "command": "-workbench.action.nextEditorInGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+pageup",
        "command": "-workbench.action.previousEditorInGroup"
    },
    {
        "key": "ctrl+numpad9 shift+enter",
        "command": "-workbench.action.pinEditor",
        "when": "!activeEditorIsPinned"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_5",
        "command": "-workbench.action.splitEditorDown"
    },
    {
        "key": "ctrl+numpad9 ctrl+shift+oem_5",
        "command": "-workbench.action.splitEditorInGroup",
        "when": "activeEditorCanSplitInGroup"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_5",
        "command": "-workbench.action.splitEditorLeft"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_5",
        "command": "-workbench.action.splitEditorOrthogonal"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_5",
        "command": "-workbench.action.splitEditorRight"
    },
    {
        "key": "ctrl+numpad9 ctrl+oem_5",
        "command": "-workbench.action.splitEditorUp"
    },
    {
        "key": "ctrl+numpad9 ctrl+m",
        "command": "-workbench.action.toggleMaximizeEditorGroup",
        "when": "editorPartMaximizedEditorGroup || editorPartMultipleEditorGroups"
    },
    {
        "key": "ctrl+numpad9 z",
        "command": "-workbench.action.toggleZenMode",
        "when": "!isAuxiliaryWindowFocusedContext"
    },
    {
        "key": "ctrl+numpad9 shift+enter",
        "command": "-workbench.action.unpinEditor",
        "when": "activeEditorIsPinned"
    },
    {
        "key": "ctrl+numpad9 f",
        "command": "-workbench.action.closeFolder",
        "when": "emptyWorkspaceSupport && workbenchState != 'empty'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "-extension.vim_ctrl+numpad9",
        "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9 ctrl+a",
        "command": "-keybindings.editor.addKeybinding",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "ctrl+numpad9 ctrl+e",
        "command": "-keybindings.editor.defineWhenExpression",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "ctrl+numpad9 s",
        "command": "-saveAll"
    },
    {
        "key": "ctrl+numpad9 f2",
        "command": "-togglePeekWidgetFocus",
        "when": "inReferenceSearchEditor || referenceSearchVisible"
    },
    {
        "key": "ctrl+numpad9 down",
        "command": "-views.moveViewDown",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9 left",
        "command": "-views.moveViewLeft",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9 right",
        "command": "-views.moveViewRight",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9 up",
        "command": "-views.moveViewUp",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9 shift+o",
        "command": "-workbench.action.compareEditor.openSide",
        "when": "inDiffEditor"
    },
    {
        "key": "ctrl+numpad9 p",
        "command": "-workbench.action.files.copyPathOfActiveFile"
    },
    {
        "key": "ctrl+numpad9 ctrl+o",
        "command": "-workbench.action.files.openLocalFolder",
        "when": "remoteFileDialogVisible"
    },
    {
        "key": "ctrl+numpad9 r",
        "command": "-workbench.action.files.revealActiveFileInWindows"
    },
    {
        "key": "ctrl+numpad9 ctrl+i",
        "command": "-workbench.action.showTreeHover",
        "when": "customTreeView && listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "vscode-easymotion.jumpToWord",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+oem_2",
        "command": "-vscode-easymotion.jumpToWord",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+oem_2",
        "command": "-vscode-easymotion.jumpToEndOfWord",
        "when": "editorTextFocus"
    },
    {
        "key": "tab",
        "command": "-vscode-easymotion.incrementSearchMode",
        "when": "vscodeEasyMotionJumping"
    },
    {
        "key": "shift+tab",
        "command": "-vscode-easymotion.decrementSearchMode",
        "when": "vscodeEasyMotionJumping"
    },
    {
        "key": "escape",
        "command": "-vscode-easymotion.cancelJump",
        "when": "vscodeEasyMotionJumping"
    },
    {
        "key": "backspace",
        "command": "-vscode-easymotion.backspaceJumpMelody",
        "when": "vscodeEasyMotionJumping"
    },
    {
        "key": "ctrl+i",
        "command": "extension.vim_ctrl+i",
        "when": "editorTextFocus && vim.active && vim.use<C-i> && !inDebugRepl"
    },
    {
        "key": "ctrl+i",
        "command": "-extension.vim_ctrl+i",
        "when": "editorTextFocus && vim.active && vim.use<C-i> && !inDebugRepl"
    },
    {
        "key": "ctrl+k ctrl+alt+down",
        "command": "-editor.action.nextCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+k ctrl+alt+up",
        "command": "-editor.action.previousCommentingRange",
        "when": "accessibilityModeEnabled && commentFocused || accessibilityModeEnabled && editorFocus || accessibilityHelpIsShown && accessibilityModeEnabled && accessibleViewCurrentProviderId == 'comments'"
    },
    {
        "key": "ctrl+k ctrl+q",
        "command": "-workbench.action.navigateToLastEditLocation"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.moveActiveEditorGroupDown"
    },
    {
        "key": "ctrl+k down",
        "command": "-workbench.action.moveActiveEditorGroupDown"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.moveActiveEditorGroupLeft"
    },
    {
        "key": "ctrl+k left",
        "command": "-workbench.action.moveActiveEditorGroupLeft"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.moveActiveEditorGroupRight"
    },
    {
        "key": "ctrl+k right",
        "command": "-workbench.action.moveActiveEditorGroupRight"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.moveActiveEditorGroupUp"
    },
    {
        "key": "ctrl+k up",
        "command": "-workbench.action.moveActiveEditorGroupUp"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.nextEditorInGroup"
    },
    {
        "key": "ctrl+k ctrl+pagedown",
        "command": "-workbench.action.nextEditorInGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.pinEditor",
        "when": "!activeEditorIsPinned"
    },
    {
        "key": "ctrl+k shift+enter",
        "command": "-workbench.action.pinEditor",
        "when": "!activeEditorIsPinned"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorDown"
    },
    {
        "key": "ctrl+k ctrl+oem_5",
        "command": "-workbench.action.splitEditorDown"
    },
    {
        "key": "ctrl+k ctrl+c",
        "command": "-editor.action.addCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+k m",
        "command": "-workbench.action.editor.changeLanguageMode",
        "when": "!notebookEditorFocused"
    },
    {
        "key": "ctrl+k ctrl+alt+c",
        "command": "-workbench.action.addComment"
    },
    {
        "key": "ctrl+k ctrl+oem_comma",
        "command": "-editor.createFoldingRangeFromSelection",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+i",
        "command": "-editor.debug.action.showDebugHover",
        "when": "editorTextFocus && inDebugMode"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.defineKeybinding",
        "when": "resource == 'vscode-userdata:/c%3A/Users/Administrator/AppData/Roaming/Code/User/keybindings.json'"
    },
    {
        "key": "ctrl+k ctrl+k",
        "command": "-editor.action.defineKeybinding",
        "when": "resource == 'vscode-userdata:/c%3A/Users/Administrator/AppData/Roaming/Code/User/keybindings.json'"
    },
    {
        "key": "ctrl+k e",
        "command": "-workbench.files.action.focusOpenEditorsView",
        "when": "workbench.explorer.openEditorsView.active"
    },
    {
        "key": "ctrl+k c",
        "command": "-workbench.files.action.compareWithClipboard"
    },
    {
        "key": "ctrl+k d",
        "command": "-workbench.files.action.compareWithSaved"
    },
    {
        "key": "ctrl+k ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+k ctrl+shift+c",
        "command": "-copyRelativeFilePath",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+k ctrl+o",
        "command": "-workbench.action.files.openFolder",
        "when": "openFolderWorkspaceSupport"
    },
    {
        "key": "ctrl+k ctrl+shift+s",
        "command": "-workbench.action.files.saveWithoutFormatting"
    },
    {
        "key": "ctrl+k ctrl+p",
        "command": "-workbench.action.showAllEditors"
    },
    {
        "key": "ctrl+k ctrl+0",
        "command": "-editor.foldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_2",
        "command": "-editor.foldAllBlockComments",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_minus",
        "command": "-editor.foldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+8",
        "command": "-editor.foldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+1",
        "command": "-editor.foldLevel1",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.foldLevel2",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+2",
        "command": "-editor.foldLevel2",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+3",
        "command": "-editor.foldLevel3",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+4",
        "command": "-editor.foldLevel4",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+5",
        "command": "-editor.foldLevel5",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+6",
        "command": "-editor.foldLevel6",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+7",
        "command": "-editor.foldLevel7",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_4",
        "command": "-editor.foldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+f",
        "command": "-editor.action.formatSelection",
        "when": "editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+k ctrl+r",
        "command": "-git.revertSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+k ctrl+alt+s",
        "command": "-git.stageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+k ctrl+n",
        "command": "-git.unstageSelectedRanges",
        "when": "isInDiffEditor && !operationInProgress"
    },
    {
        "key": "ctrl+k ctrl+r",
        "command": "-workbench.action.keybindingsReference"
    },
    {
        "key": "ctrl+k i",
        "command": "-inlineChat.start",
        "when": "editorFocus && inlineChatHasProvider && !editorReadonly"
    },
    {
        "key": "ctrl+k i",
        "command": "-inlineChat.quickVoice.start",
        "when": "editorFocus && hasSpeechProvider && !inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+k i",
        "command": "-inlineChat.quickVoice.stop",
        "when": "hasSpeechProvider && inlineChat.quickChatInProgress"
    },
    {
        "key": "ctrl+k v",
        "command": "-markdown.showPreviewToSide",
        "when": "!notebookEditorFocused && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+k ctrl+d",
        "command": "-editor.action.moveSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+k ctrl+c",
        "command": "-notebook.cell.collapseCellInput",
        "when": "notebookCellListFocused && !inputFocus && !notebookCellInputIsCollapsed"
    },
    {
        "key": "ctrl+k t",
        "command": "-notebook.cell.collapseCellOutput",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus && !notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+k ctrl+c",
        "command": "-notebook.cell.expandCellInput",
        "when": "notebookCellInputIsCollapsed && notebookCellListFocused"
    },
    {
        "key": "ctrl+k t",
        "command": "-notebook.cell.expandCellOutput",
        "when": "notebookCellListFocused && notebookCellOutputIsCollapsed"
    },
    {
        "key": "ctrl+k ctrl+shift+oem_5",
        "command": "-notebook.cell.split",
        "when": "editorTextFocus && notebookCellEditable && notebookEditable && notebookEditorFocused"
    },
    {
        "key": "ctrl+k y",
        "command": "-notebook.cell.toggleOutputScrolling",
        "when": "notebookCellHasOutputs && notebookCellListFocused && !inputFocus"
    },
    {
        "key": "ctrl+k ctrl+shift+n",
        "command": "-notifications.showList"
    },
    {
        "key": "ctrl+k f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && isWeb && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+k ctrl+f12",
        "command": "-editor.action.revealDefinitionAside",
        "when": "editorHasDefinitionProvider && editorTextFocus && isWeb && !isInEmbeddedEditor"
    },
    {
        "key": "ctrl+k ctrl+t",
        "command": "-workbench.action.selectTheme"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.openGlobalKeybindings"
    },
    {
        "key": "ctrl+k ctrl+s",
        "command": "-workbench.action.openGlobalKeybindings"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.removeCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+k ctrl+u",
        "command": "-editor.action.removeCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.removeManualFoldingRanges",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_period",
        "command": "-editor.removeManualFoldingRanges",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.selectFromAnchorToCursor",
        "when": "editorTextFocus && selectionAnchorSet"
    },
    {
        "key": "ctrl+k ctrl+k",
        "command": "-editor.action.selectFromAnchorToCursor",
        "when": "editorTextFocus && selectionAnchorSet"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.setSelectionAnchor",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+k ctrl+b",
        "command": "-editor.action.setSelectionAnchor",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+k ctrl+i",
        "command": "-editor.action.showHover",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.focusHover",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalIsOpen || terminalFocus && terminalProcessSupported || terminalHasBeenCreated && terminalTabsFocus || terminalIsOpen && terminalTabsFocus || terminalProcessSupported && terminalTabsFocus"
    },
    {
        "key": "ctrl+k ctrl+i",
        "command": "-workbench.action.terminal.focusHover",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalIsOpen || terminalFocus && terminalProcessSupported || terminalHasBeenCreated && terminalTabsFocus || terminalIsOpen && terminalTabsFocus || terminalProcessSupported && terminalTabsFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.toggleFold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+l",
        "command": "-editor.toggleFold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.trimTrailingWhitespace",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+k ctrl+x",
        "command": "-editor.action.trimTrailingWhitespace",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+k ctrl+j",
        "command": "-editor.unfoldAll",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.unfoldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_plus",
        "command": "-editor.unfoldAllExcept",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.unfoldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+9",
        "command": "-editor.unfoldAllMarkerRegions",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.unfoldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+k ctrl+oem_6",
        "command": "-editor.unfoldRecursively",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeAllGroups"
    },
    {
        "key": "ctrl+k ctrl+shift+w",
        "command": "-workbench.action.closeAllGroups"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeAllEditors"
    },
    {
        "key": "ctrl+k ctrl+w",
        "command": "-workbench.action.closeAllEditors"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeEditorsInGroup"
    },
    {
        "key": "ctrl+k w",
        "command": "-workbench.action.closeEditorsInGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeUnmodifiedEditors"
    },
    {
        "key": "ctrl+k u",
        "command": "-workbench.action.closeUnmodifiedEditors"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.copyEditorToNewWindow",
        "when": "activeEditor"
    },
    {
        "key": "ctrl+k o",
        "command": "-workbench.action.copyEditorToNewWindow",
        "when": "activeEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusAboveGroup"
    },
    {
        "key": "ctrl+k ctrl+up",
        "command": "-workbench.action.focusAboveGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusBelowGroup"
    },
    {
        "key": "ctrl+k ctrl+down",
        "command": "-workbench.action.focusBelowGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusLeftGroup"
    },
    {
        "key": "ctrl+k ctrl+left",
        "command": "-workbench.action.focusLeftGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusRightGroup"
    },
    {
        "key": "ctrl+k ctrl+right",
        "command": "-workbench.action.focusRightGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.joinEditorInGroup",
        "when": "sideBySideEditorActive"
    },
    {
        "key": "ctrl+k ctrl+shift+oem_5",
        "command": "-workbench.action.joinEditorInGroup",
        "when": "sideBySideEditorActive"
    },
    {
        "key": "ctrl+numpad9 ctrl+enter",
        "command": "workbench.action.keepEditor"
    },
    {
        "key": "ctrl+k enter",
        "command": "-workbench.action.keepEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.previousEditorInGroup"
    },
    {
        "key": "ctrl+k ctrl+pageup",
        "command": "-workbench.action.previousEditorInGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorInGroup",
        "when": "activeEditorCanSplitInGroup"
    },
    {
        "key": "ctrl+k ctrl+shift+oem_5",
        "command": "-workbench.action.splitEditorInGroup",
        "when": "activeEditorCanSplitInGroup"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorLeft"
    },
    {
        "key": "ctrl+k ctrl+oem_5",
        "command": "-workbench.action.splitEditorLeft"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorOrthogonal"
    },
    {
        "key": "ctrl+k ctrl+oem_5",
        "command": "-workbench.action.splitEditorOrthogonal"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorRight"
    },
    {
        "key": "ctrl+k ctrl+oem_5",
        "command": "-workbench.action.splitEditorRight"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.splitEditorUp"
    },
    {
        "key": "ctrl+k ctrl+oem_5",
        "command": "-workbench.action.splitEditorUp"
    },
    {
        "key": "ctrl+k ctrl+m",
        "command": "-workbench.action.toggleMaximizeEditorGroup",
        "when": "editorPartMaximizedEditorGroup || editorPartMultipleEditorGroups"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.toggleZenMode",
        "when": "!isAuxiliaryWindowFocusedContext"
    },
    {
        "key": "ctrl+k z",
        "command": "-workbench.action.toggleZenMode",
        "when": "!isAuxiliaryWindowFocusedContext"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.unpinEditor",
        "when": "activeEditorIsPinned"
    },
    {
        "key": "ctrl+k shift+enter",
        "command": "-workbench.action.unpinEditor",
        "when": "activeEditorIsPinned"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeFolder",
        "when": "emptyWorkspaceSupport && workbenchState != 'empty'"
    },
    {
        "key": "ctrl+k f",
        "command": "-workbench.action.closeFolder",
        "when": "emptyWorkspaceSupport && workbenchState != 'empty'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "keybindings.editor.addKeybinding",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "ctrl+k ctrl+a",
        "command": "-keybindings.editor.addKeybinding",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "keybindings.editor.defineWhenExpression",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "ctrl+k ctrl+e",
        "command": "-keybindings.editor.defineWhenExpression",
        "when": "inKeybindings && keybindingFocus"
    },
    {
        "key": "numpad9",
        "command": "notebook.cell.chat.start",
        "when": "config.notebook.experimental.cellChat && inlineChatHasProvider && notebookEditable && notebookEditorFocused && !inputFocus"
    },
    {
        "key": "ctrl+k i",
        "command": "-notebook.cell.chat.start",
        "when": "config.notebook.experimental.cellChat && inlineChatHasProvider && notebookEditable && notebookEditorFocused && !inputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "saveAll"
    },
    {
        "key": "ctrl+k s",
        "command": "-saveAll"
    },
    {
        "key": "ctrl+numpad9",
        "command": "togglePeekWidgetFocus",
        "when": "inReferenceSearchEditor || referenceSearchVisible"
    },
    {
        "key": "ctrl+k f2",
        "command": "-togglePeekWidgetFocus",
        "when": "inReferenceSearchEditor || referenceSearchVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "views.moveViewDown",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+k down",
        "command": "-views.moveViewDown",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9",
        "command": "views.moveViewLeft",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+k left",
        "command": "-views.moveViewLeft",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9",
        "command": "views.moveViewRight",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+k right",
        "command": "-views.moveViewRight",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9",
        "command": "views.moveViewUp",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+k up",
        "command": "-views.moveViewUp",
        "when": "focusedView != ''"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.compareEditor.openSide",
        "when": "inDiffEditor"
    },
    {
        "key": "ctrl+k shift+o",
        "command": "-workbench.action.compareEditor.openSide",
        "when": "inDiffEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.files.copyPathOfActiveFile"
    },
    {
        "key": "ctrl+k p",
        "command": "-workbench.action.files.copyPathOfActiveFile"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.files.openLocalFolder",
        "when": "remoteFileDialogVisible"
    },
    {
        "key": "ctrl+k ctrl+o",
        "command": "-workbench.action.files.openLocalFolder",
        "when": "remoteFileDialogVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.files.revealActiveFileInWindows"
    },
    {
        "key": "ctrl+k r",
        "command": "-workbench.action.files.revealActiveFileInWindows"
    },
    {
        "key": "ctrl+k ctrl+i",
        "command": "-workbench.action.showTreeHover",
        "when": "customTreeView && listFocus && !inputFocus && !treestickyScrollFocused"
    },
    {
        "key": "ctrl+k",
        "command": "extension.vim_ctrl+k",
        "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    },
    {
        "key": "ctrl+k",
        "command": "-extension.vim_ctrl+k",
        "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "inlineChat.moveToNextHunk",
        "when": "inlineChatHasProvider && inlineChatVisible"
    },
    {
        "key": "f7",
        "command": "-inlineChat.moveToNextHunk",
        "when": "inlineChatHasProvider && inlineChatVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.focusFirstEditorGroup"
    },
    {
        "key": "ctrl+1",
        "command": "-workbench.action.focusFirstEditorGroup"
    },
    {
        "key": "alt+d",
        "command": "rerunSearchEditorSearch",
        "when": "inSearchEditor"
    },
    {
        "key": "ctrl+shift+r",
        "command": "-rerunSearchEditorSearch",
        "when": "inSearchEditor"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.chat.startVoiceChat",
        "when": "hasChatProvider && hasSpeechProvider && inChatInput && !chatSessionRequestInProgress && !editorFocus && !inlineChatHasActiveRequest && !inlineVoiceChatInProgress && !notebookEditorFocused && !quickVoiceChatInProgress && !terminalChatActiveRequest && !terminalVoiceChatInProgress && !voiceChatGettingReady && !voiceChatInEditorInProgress && !voiceChatInViewInProgress || hasChatProvider && hasSpeechProvider && inlineChatFocused && !chatSessionRequestInProgress && !editorFocus && !inlineChatHasActiveRequest && !inlineVoiceChatInProgress && !notebookEditorFocused && !quickVoiceChatInProgress && !terminalChatActiveRequest && !terminalVoiceChatInProgress && !voiceChatGettingReady && !voiceChatInEditorInProgress && !voiceChatInViewInProgress"
    },
    {
        "key": "ctrl+i",
        "command": "-workbench.action.chat.startVoiceChat",
        "when": "hasChatProvider && hasSpeechProvider && inChatInput && !chatSessionRequestInProgress && !editorFocus && !inlineChatHasActiveRequest && !inlineVoiceChatInProgress && !notebookEditorFocused && !quickVoiceChatInProgress && !terminalChatActiveRequest && !terminalVoiceChatInProgress && !voiceChatGettingReady && !voiceChatInEditorInProgress && !voiceChatInViewInProgress || hasChatProvider && hasSpeechProvider && inlineChatFocused && !chatSessionRequestInProgress && !editorFocus && !inlineChatHasActiveRequest && !inlineVoiceChatInProgress && !notebookEditorFocused && !quickVoiceChatInProgress && !terminalChatActiveRequest && !terminalVoiceChatInProgress && !voiceChatGettingReady && !voiceChatInEditorInProgress && !voiceChatInViewInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.chat.stopListeningAndSubmit",
        "when": "hasChatProvider && hasSpeechProvider && inChatInput && voiceChatInProgress || hasChatProvider && hasSpeechProvider && inlineChatFocused && voiceChatInProgress"
    },
    {
        "key": "ctrl+i",
        "command": "-workbench.action.chat.stopListeningAndSubmit",
        "when": "hasChatProvider && hasSpeechProvider && inChatInput && voiceChatInProgress || hasChatProvider && hasSpeechProvider && inlineChatFocused && voiceChatInProgress"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.chat.focusInput",
        "when": "config.terminal.integrated.experimentalInlineChat && terminalChatFocus && !inlineChatFocused"
    },
    {
        "key": "ctrl+i",
        "command": "-workbench.action.terminal.chat.focusInput",
        "when": "config.terminal.integrated.experimentalInlineChat && terminalChatFocus && !inlineChatFocused"
    },
    {
        "key": "ctrl+i",
        "command": "-inlineChat.start",
        "when": "editorFocus && inlineChatHasProvider && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.chat.start",
        "when": "config.terminal.integrated.experimentalInlineChat && inlineChatHasProvider && terminalFocusInAny && terminalHasBeenCreated || config.terminal.integrated.experimentalInlineChat && inlineChatHasProvider && terminalFocusInAny && terminalProcessSupported"
    },
    {
        "key": "ctrl+i",
        "command": "-workbench.action.terminal.chat.start",
        "when": "config.terminal.integrated.experimentalInlineChat && inlineChatHasProvider && terminalFocusInAny && terminalHasBeenCreated || config.terminal.integrated.experimentalInlineChat && inlineChatHasProvider && terminalFocusInAny && terminalProcessSupported"
    },
    {
        "key": "numpad9",
        "command": "testing.toggleInlineTestOutput"
    },
    {
        "key": "ctrl+oem_1 ctrl+i",
        "command": "-testing.toggleInlineTestOutput"
    },
    {
        "key": "numpad9",
        "command": "editor.action.triggerSuggest",
        "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible"
    },
    {
        "key": "ctrl+i",
        "command": "-editor.action.triggerSuggest",
        "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible"
    },
    {
        "key": "ctrl+numpad9",
        "command": "focusSuggestion",
        "when": "suggestWidgetVisible && textInputFocus && !suggestWidgetHasFocusedSuggestion"
    },
    {
        "key": "ctrl+i",
        "command": "-focusSuggestion",
        "when": "suggestWidgetVisible && textInputFocus && !suggestWidgetHasFocusedSuggestion"
    },
    {
        "key": "numpad9",
        "command": "inlineChat.holdForSpeech",
        "when": "hasSpeechProvider && inlineChatHasProvider && inlineChatVisible && textInputFocus"
    },
    {
        "key": "ctrl+i",
        "command": "-inlineChat.holdForSpeech",
        "when": "hasSpeechProvider && inlineChatHasProvider && inlineChatVisible && textInputFocus"
    },
    {
        "key": "ctrl+i",
        "command": "-notebook.cell.chat.start",
        "when": "config.notebook.experimental.cellChat && inlineChatHasProvider && notebookEditable && notebookEditorFocused && !inputFocus"
    },
    {
        "key": "numpad9",
        "command": "testing.toggleInlineCoverage",
        "when": "testing.isTestCoverageOpen"
    },
    {
        "key": "ctrl+oem_1 ctrl+shift+i",
        "command": "-testing.toggleInlineCoverage",
        "when": "testing.isTestCoverageOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "toggleSuggestionDetails",
        "when": "suggestWidgetHasFocusedSuggestion && suggestWidgetVisible && textInputFocus"
    },
    {
        "key": "ctrl+i",
        "command": "-toggleSuggestionDetails",
        "when": "suggestWidgetHasFocusedSuggestion && suggestWidgetVisible && textInputFocus"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.chat.holdToVoiceChatInChatView",
        "when": "hasChatProvider && hasSpeechProvider && !editorFocus && !inChatInput && !inlineChatFocused && !notebookEditorFocused"
    },
    {
        "key": "ctrl+i",
        "command": "-workbench.action.chat.holdToVoiceChatInChatView",
        "when": "hasChatProvider && hasSpeechProvider && !editorFocus && !inChatInput && !inlineChatFocused && !notebookEditorFocused"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.chat.open",
        "when": "hasChatProvider"
    },
    {
        "key": "ctrl+alt+i",
        "command": "-workbench.action.chat.open",
        "when": "hasChatProvider"
    },
    // {
    //     "key": "ctrl+k",
    //     "command": "extension.vim_ctrl+k",
    //     "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    // },
    // {
    //     "key": "ctrl+k",
    //     "command": "-extension.vim_ctrl+k",
    //     "when": "editorTextFocus && vim.active && vim.use<C-k> && !inDebugRepl"
    // },
    {
        "key": "ctrl+k",
        "command": "workbench.action.quickOpenSelectNext",
        "when": "inQuickOpen"
    },
    {
        "key": "ctrl+i",
        "command": "workbench.action.quickOpenSelectPrevious",
        "when": "inQuickOpen"
    },
    {
        "command": "runCommands",
        "key": "ctrl+shift+i", // whatever keybinding
        "args": {
          "commands": [
            // commands to run in sequence
            "workbench.action.quickOpenSelectPrevious",
            "workbench.action.quickOpenSelectPrevious",
            "workbench.action.quickOpenSelectPrevious",
            "workbench.action.quickOpenSelectPrevious",
            "workbench.action.quickOpenSelectPrevious",
          ]
        },
        "when": "inQuickOpen"
    },
    {
        "command": "runCommands",
        "key": "ctrl+shift+k", // whatever keybinding
        "args": {
          "commands": [
            // commands to run in sequence
            "workbench.action.quickOpenSelectNext",
            "workbench.action.quickOpenSelectNext",
            "workbench.action.quickOpenSelectNext",
            "workbench.action.quickOpenSelectNext",
            "workbench.action.quickOpenSelectNext",
          ]
        },
        "when": "inQuickOpen"
    },
    {
        "key": "ctrl+i",
        "command": "list.focusUp",
        "when": "listFocus && !inputFocus"
    },
    {
        "command": "runCommands",
        "key": "ctrl+shift+i", // whatever keybinding
        "args": {
          "commands": [
            // commands to run in sequence
            "list.focusUp",
            "list.focusUp",
            "list.focusUp",
            "list.focusUp",
            "list.focusUp",
          ]
        },
        "when": "listFocus && !inputFocus"
    },
    {
        "command": "runCommands",
        "key": "ctrl+shift+k", // whatever keybinding
        "args": {
          "commands": [
            // commands to run in sequence
            "list.focusDown",
            "list.focusDown",
            "list.focusDown",
            "list.focusDown",
            "list.focusDown",
          ]
        },
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+k",
        "command": "list.focusDown",
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+shift+j",
        "command": "workbench.files.action.focusFilesExplorer"
    },
    {
        "key": "ctrl+shift+l",
        "command": "workbench.action.focusActiveEditorGroup"
    },
    {
        "key": "ctrl+shift+q",
        "command": "workbench.action.terminal.openDetectedLink",
        "when": "terminalFocus && terminalHasBeenCreated"
    },
    {
        "key": "tab",
        "command": "workbench.action.terminal.focusNext",
        "when": "terminalFocus && terminalHasBeenCreated && !terminalEditorFocus || terminalFocus && terminalProcessSupported && !terminalEditorFocus"
    },
    {
        "key": "ctrl+shift+w",
        "command": "workbench.action.terminal.toggleTerminal",
        "when": "terminal.active"
    },
    {
        "key": "ctrl+shift+e",
        "command": "workbench.action.togglePanel"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.refactor",
        "when": "editorHasCodeActionsProvider && textInputFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+r",
        "command": "-editor.action.refactor",
        "when": "editorHasCodeActionsProvider && textInputFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickOpenNavigatePreviousInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
    },
    {
        "key": "ctrl+shift+r",
        "command": "-workbench.action.quickOpenNavigatePreviousInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.view.explorer",
        "when": "viewContainer.workbench.view.explorer.enabled"
    },
    {
        "key": "ctrl+shift+e",
        "command": "-workbench.view.explorer",
        "when": "viewContainer.workbench.view.explorer.enabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickOpenNavigatePreviousInFilePicker",
        "when": "inFilesPicker && inQuickOpen"
    },
    {
        "key": "ctrl+shift+e",
        "command": "-workbench.action.quickOpenNavigatePreviousInFilePicker",
        "when": "inFilesPicker && inQuickOpen"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.quickOpenNavigatePreviousInViewPicker",
        "when": "inQuickOpen && inViewsPicker"
    },
    {
        "key": "ctrl+shift+q",
        "command": "-workbench.action.quickOpenNavigatePreviousInViewPicker",
        "when": "inQuickOpen && inViewsPicker"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.closeWindow"
    },
    {
        "key": "ctrl+shift+w",
        "command": "-workbench.action.closeWindow"
    },
    {
        "key": "ctrl+f",
        "command": "workbench.action.terminal.focusFind",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocusInAny && terminalHasBeenCreated || terminalFocusInAny && terminalProcessSupported"
    },
    {
        "key": "ctrl+f",
        "command": "-workbench.action.terminal.focusFind",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocusInAny && terminalHasBeenCreated || terminalFocusInAny && terminalProcessSupported"
    },
    {
        "key": "ctrl+2",
        "command": "workbench.action.terminal.focusFind",
        "when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocusInAny && terminalHasBeenCreated || terminalFocusInAny && terminalProcessSupported"
    },
    {
        "key": "ctrl+shift+oem_minus",
        "command": "workbench.action.increaseViewWidth"
    },
    {
        "key": "ctrl+shift+oem_plus",
        "command": "workbench.action.decreaseViewWidth"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.fold",
        "when": "notebookEditorFocused && !inputFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "ctrl+shift+oem_4",
        "command": "-notebook.fold",
        "when": "notebookEditorFocused && !inputFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.outdentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+oem_4",
        "command": "-editor.action.outdentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.fold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+shift+oem_4",
        "command": "-editor.fold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.action.indentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+oem_6",
        "command": "-editor.action.indentLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+numpad9",
        "command": "notebook.unfold",
        "when": "notebookEditorFocused && !inputFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "ctrl+shift+oem_6",
        "command": "-notebook.unfold",
        "when": "notebookEditorFocused && !inputFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "ctrl+numpad9",
        "command": "editor.unfold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+shift+oem_6",
        "command": "-editor.unfold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+oem_4",
        "command": "extension.vim_ctrl+[",
        "when": "editorTextFocus && vim.active && vim.use<C-[> && !inDebugRepl"
    },
    {
        "key": "ctrl+oem_4",
        "command": "-extension.vim_ctrl+[",
        "when": "editorTextFocus && vim.active && vim.use<C-[> && !inDebugRepl"
    },
    {
        "key": "ctrl+numpad9",
        "command": "workbench.action.terminal.goToRecentDirectory",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+g",
        "command": "-workbench.action.terminal.goToRecentDirectory",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+numpad9",
        "command": "extension.vim_ctrl+g",
        "when": "editorTextFocus && vim.active && vim.use<C-g> && !inDebugRepl"
    },
    {
        "key": "ctrl+g",
        "command": "-extension.vim_ctrl+g",
        "when": "editorTextFocus && vim.active && vim.use<C-g> && !inDebugRepl"
    },
    {
        "key": "ctrl+alt+g",
        "command": "-workbench.action.terminal.sendSequence",
        "when": "terminalFocus"
    },
]
