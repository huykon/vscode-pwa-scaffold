# Magento PWA Studio Snippets for VS Code

This extension for Visual Studio Code adds snippets for Magento PWA Studio.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

### Visual Studio Marketplace

Launch _Quick Open_:

-   [_Linux_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf): `Ctrl+P`
-   [_macOS_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf): `⌘P`
-   [_Windows_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf): `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install huykon225.vscode-pwa-scaffold
```

### GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:

-   _Linux_: `~/.vscode/extensions`
-   _macOS_: `~/.vscode/extensions`
-   _Windows_: `%USERPROFILE%\.vscode\extensions`

```shell
git clone git@github.com:huykon/vscode-pwa-scaffold.git
```

For development you open the cloned directory and press `F5` then VS-Code open new Window with the loaded extension.

### PWA Studio Snippets

| Snippet               | Short Snippet | Purpose                                      |
| :-------------------- | :-----------: | -------------------------------------------- |
| `pst-comp`            |    `pstc`     | Simple function component                    |
| `pst-test`            |    `pstt`     | Snapshot test based on jest                  |
| `pst-test-case`       |    `psttc`    | Simple Jest Test case for snapshot           |
| `pst-test-lib`        |    `psttl`    | Snapshot test based on react testing library |
| `pst-export-default`  |    `psted`    | Default export for index                     |
| `pst-route`           |    `pstro`    | Venia-UI route target                        |
| `pst-route-sub`       |   `pstros`    | Venia-UI route child target                  |
| `pst-rich-con`        |    `pstrc`    | Venia-UI rich content renderer target        |
| `pst-hook`            |    `psth`     | Peregrine hook target                        |
| `pst-hook-sub`        |    `psths`    | Peregrine hook target sub                    |
| `pst-target-special`  |    `pstts`    | Special feature target                       |
| `pst-targetable-comp` |    `psttc`    | Targetable to component                      |
| `pst-targetable-adj`  |    `pstta`    | Targetable to adjustment component           |
