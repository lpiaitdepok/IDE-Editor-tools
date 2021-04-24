| Command                                     | Key              | Command id                         |
| :------------------------------------------ | :--------------- | :--------------------------------- |
| Copy line (empty selection)                 | Ctrl+C           | editor.action.clipboardCopyAction  |
| Cut line (empty selection)                  | Ctrl+X           | editor.action.clipboardCutAction   |
| Paste                                       | Ctrl+V           | editor.action.clipboardPasteAction |
| Copy Line Down                              | Shift+Alt+Down   | editor.action.copyLinesDownAction  |
| Copy Line Up                                | Shift+Alt+Up     | editor.action.copyLinesUpAction    |
| Delete Line                                 | Ctrl+Shift+K     | editor.action.deleteLines          |
| Insert Line Below                           | Ctrl+Enter       | editor.action.insertLineAfter      |
| Insert Line Above                           | Ctrl+Shift+Enter | editor.action.insertLineBefore     |
| Move Line Down                              | Alt+Down         | editor.action.moveLinesDownAction  |
| Move Line Up                                | Alt+Up           | editor.action.moveLinesUpAction    |
| Select all occurrences of current selection | Ctrl+Shift+L     | editor.action.selectHighlights     |
| Select all occurrences of current word      | Ctrl+F2          | editor.action.changeAll            |
| Select current line                         | Ctrl+L           | expandLineSelection                |
| Insert Cursor Below                         | Ctrl+Alt+Down    | editor.action.insertCursorBelow    |
| Insert Cursor Above                         | Ctrl+Alt+Up      | editor.action.insertCursorAbove    |
| Jump to matching bracket                    | Ctrl+Shift+\     | editor.action.jumpToBracket        |
| Indent Line                                 | Ctrl+]           | editor.action.indentLines          |
| Outdent Line                                | Ctrl+[           | editor.action.outdentLines         |
| Fold (collapse) region             | Ctrl+Shift+[       | editor.fold                                      |
| Unfold (uncollapse) region         | Ctrl+Shift+]       | editor.unfold                                    |
| Fold (collapse) all subregions     | Ctrl+K Ctrl+[      | editor.foldRecursively                           |
| Unfold (uncollapse) all subregions | Ctrl+K Ctrl+]      | editor.unfoldRecursively                         |
| Fold (collapse) all regions        | Ctrl+K Ctrl+0      | editor.foldAll                                   |
| Unfold (uncollapse) all regions    | Ctrl+K Ctrl+J      | editor.unfoldAll                                 |
| Add Line Comment                   | Ctrl+K Ctrl+C      | editor.action.addCommentLine                     |
| Remove Line Comment                | Ctrl+K Ctrl+U      | editor.action.removeCommentLine                  |
| Toggle Line Comment                | Ctrl+/             | editor.action.commentLine                        |
| Toggle Block Comment               | Shift+Alt+A        | editor.action.blockComment                       |
| Trigger Suggest                    | Ctrl+Space         | editor.action.triggerSuggest                     |
| Trigger Parameter Hints            | Ctrl+Shift+Space   | editor.action.triggerParameterHints              |
| Format Document                    | Shift+Alt+F        | editor.action.formatDocument                     |
| Format Selection                   | Ctrl+K Ctrl+F      | editor.action.formatSelection                    |
| Go to Definition                   | F12                | editor.action.revealDefinition                   |
| Show Hover                         | Ctrl+K Ctrl+I      | editor.action.showHover                          |
| Peek Definition                    | Alt+F12            | editor.action.peekDefinition                     |
| Open Definition to the Side        | Ctrl+K F12         | editor.action.revealDefinitionAside              |
| Show Problems                      | Ctrl+Shift+M       | workbench.actions.view.problems                  |
| Go to Next Error or Warning        | F8                 | editor.action.marker.nextInFiles                 |
| Go to Previous Error or Warning    | Shift+F8           | editor.action.marker.prevInFiles                 |
| Show All Commands                  | Ctrl+Shift+P or F1 | workbench.action.showCommands                    |
| Save As...                         | Ctrl+Shift+S       | workbench.action.files.saveAs                    |
| Close                              | Ctrl+F4            | workbench.action.closeActiveEditor               |
| Close Others                       | unassigned         | workbench.action.closeOtherEditors               |
| Close Group                        | Ctrl+K W           | workbench.action.closeEditorsInGroup             |
| Close Other Groups                 | unassigned         | workbench.action.closeEditorsInOtherGroups       |
| Close Group to Left                | unassigned         | workbench.action.closeEditorsToTheLeft           |
| Close Group to Right               | unassigned         | workbench.action.closeEditorsToTheRight          |
| Close All                          | Ctrl+K Ctrl+W      | workbench.action.closeAllEditors                 |
| Reopen Closed Editor               | Ctrl+Shift+T       | workbench.action.reopenClosedEditor              |
| Keep Open                          | Ctrl+K Enter       | workbench.action.keepEditor                      |
| Copy Path of Active File           | Ctrl+K P           | workbench.action.files.copyPathOfActiveFile      |
| Reveal Active File in Windows      | Ctrl+K R           | workbench.action.files.revealActiveFileInWindows |
| Show Opened File in New Window     | Ctrl+K O           |                                                  |
| Toggle Full Screen                 | F11                | workbench.action.toggleFullScreen                |
| Toggle Zen Mode                    | Ctrl+K Z           | workbench.action.toggleZenMode                   |
| Leave Zen Mode                     | Escape Escape      | workbench.action.exitZenMode                     |
| Zoom in                            | Ctrl+=             | workbench.action.zoomIn                          |
| Zoom out                           | Ctrl+-             | workbench.action.zoomOut                         |
| Reset Zoom                         | Ctrl+Numpad0       | workbench.action.zoomReset                       |
| Toggle Sidebar Visibility          | Ctrl+B             | workbench.action.toggleSidebarVisibility         |
| Show Explorer / Toggle Focus       | Ctrl+Shift+E       | workbench.view.explorer                          |
| Show Search                        | Ctrl+Shift+F       | workbench.view.search                            |
| Show Source Control                | Ctrl+Shift+G       | workbench.view.scm                               |
| Show Run                           | Ctrl+Shift+D       | workbench.view.debug                             |
| Show Extensions                    | Ctrl+Shift+X       | workbench.view.extensions                        |
| Show Output                        | Ctrl+Shift+U       | workbench.action.output.toggleOutput             |
| Quick Open View                    | Ctrl+Q             | workbench.action.quickOpenView                   |
| Open New Command Prompt            | Ctrl+Shift+C       | workbench.action.terminal.openNativeConsole      |
| Toggle Integrated Terminal         | Ctrl+`             | workbench.action.terminal.toggleTerminal         |
| Open Settings                      | Ctrl+,             | workbench.action.openSettings                    |
| Open Keyboard Shortcuts            | Ctrl+K Ctrl+S      | workbench.action.openGlobalKeybindings           |
| oggle Breakpoint                   | F9                 | editor.debug.action.toggleBreakpoint             |
| Start                              | F5                 | workbench.action.debug.start                     |
| Continue                           | F5                 | workbench.action.debug.continue                  |
| Start (without debugging)          | Ctrl+F5            | workbench.action.debug.run                       |
| Pause                              | F6                 | workbench.action.debug.pause                     |
|                                    |                    |                                                  |
