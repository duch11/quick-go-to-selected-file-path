# quick-go-to-selected-terraform-path
Original code by g8up/quick-go-to-selected-file-path
This is a patch to have it filter for git repositories, in specific it's for terraform source definitions in git.
( I know.. Very specific use case, maybe it should be upgraded later )

# Usage
1. Select a file path in the text editor with a similar format as this: 
source = "git@github.com:my-tf-org/tf-modules.git//route53/a-module-i-want-to-go-to?ref=master"
2. `Ctrl | ⌘ + E`: fill the text of selection to `quickOpen`Panel
3. `Enter` to confirm

# Keybinding
- customize your own shotcut by search `extension.quickGoToSelectedFilePath` in `Keyboard Shortcuts` list;

**Enjoy it!**
