# Keybinding Reference

## iamb keybindings

| Modes           | Keybinding        | Aliases | Help                                |
| --------------- | ---------------   | ------- | ----------------------------------- |
| Normal, Visual  | `^Wm`             | `^W^M`  | See [Message Scrollback]            |
| Normal, Visual  | `^Wz`             | `^W^Z`  | See [Organizing Windows]            |

## Vim keybindings

Note that this is not a complete list of all Vim keybindings available within
__iamb__, but just some of those referenced and explained throughout this
documentation.

| Modes           | Keybinding        | Aliases        | Help                                |
| -----           | ---------------   | -------------- | ----------------------------------- |
| Normal          | `gt`              | `<C-PageDown>` | See [Switching Tabs]                |
| Normal          | `gT`              | `<C-PageUp>`   | See [Switching Tabs]                |
| Normal          | `m{a-z}`          |                | See [Message Scrollback]            |
| Normal          | `n`               |                | See [Message Scrollback]            |
| Normal          | `N`               |                | See [Message Scrollback]            |
| Normal          | `o`               |                | See [Sending]                       |
| Normal          | `O`               |                | See [Sending]                       |
| Normal          | `yy`              |                | See [Message Scrollback]            |
| Normal          | `Y`               |                | See [Message Scrollback]            |
| Normal          | `'{a-z}`          |                | See [Message Scrollback]            |
| Normal          | `/`               |                | See [Message Scrollback]            |
| Normal          | `?`               |                | See [Message Scrollback]            |
| Normal, Visual  | `^B`              | `<PageUp>`     | See [Message Scrollback]            |
| Normal, Visual  | `^E`              |                | See [Message Scrollback]            |
| Normal, Visual  | `^F`              | `<PageDown>`   | See [Message Scrollback]            |
| Normal, Visual  | `^D`              |                | See [Message Scrollback]            |
| Normal          | `^I`              | `<Tab>`        | See [Switching Windows]             |
| Normal          | `^O`              |                | See [Switching Windows]             |
| Normal, Visual  | `^U`              |                | See [Message Scrollback]            |
| Normal, Visual  | `^Wf`             | `^W^F`         | See [Opening Tabs]                  |
| Normal, Visual  | `^Wh`             | `^W^H`         | See [Switching Windows]             |
| Normal, Visual  | `^WH`             |                | See [Organizing Windows]            |
| Normal, Visual  | `^Wj`             | `^W^J`         | See [Switching Windows]             |
| Normal, Visual  | `^WJ`             |                | See [Organizing Windows]            |
| Normal, Visual  | `^Wk`             | `^W^K`         | See [Switching Windows]             |
| Normal, Visual  | `^WK`             |                | See [Organizing Windows]            |
| Normal, Visual  | `^Wl`             | `^W^L`         | See [Switching Windows]             |
| Normal, Visual  | `^WL`             |                | See [Organizing Windows]            |
| Normal, Visual  | `^Wo`             | `^W^O`         | See [Closing Windows]               |
| Normal, Visual  | `^Wq`             | `^W^Q`         | See [Closing Windows]               |
| Normal, Visual  | `^Ws`             | `^W^S`         | See [Opening Windows]               |
| Normal, Visual  | `^WT`             |                | See [Organizing Windows]            |
| Normal, Visual  | `^Wv`             | `^W^V`         | See [Opening Windows]               |
| Normal, Visual  | `^W-`             |                | See [Resizing Windows]              |
| Normal, Visual  | `^W+`             |                | See [Resizing Windows]              |
| Normal, Visual  | `^W<`             |                | See [Resizing Windows]              |
| Normal, Visual  | `^W>`             |                | See [Resizing Windows]              |
| Normal, Visual  | `^W=`             |                | See [Resizing Windows]              |
| Normal, Visual  | `^Y`              |                | See [Message Scrollback]            |

<style>
table {
    width: 100%;
}
table th:first-of-type {
    width: 25%;
}
table th:nth-of-type(2) {
    width: 10%;
}
table th:nth-of-type(3) {
    width: 25%;
}
table th:nth-of-type(4) {
    width: 40%;
}
</style>

[Closing Windows]: ./layout/windows.md#closing-windows
[Message Scrollback]: ./messages/#message-scrollback
[Opening Tabs]: ./layout/tabs.md#opening-tabs
[Opening Windows]: ./layout/windows.md#opening-windows
[Organizing Windows]: ./layout/windows.md#organizing-windows
[Resizing Windows]: ./layout/windows.md#resizing-windows
[Sending]: ./messages/#sending
[Switching Tabs]: ./layout/tabs.md#switching-tabs
[Switching Windows]: ./layout/windows.md#switching-windows
