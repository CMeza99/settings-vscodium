# VSCodium Settings
Configuration for [VSCodium](https://github.com/VSCodium/vscodium), 
synced with [Syncify](https://github.com/arnohovhannisyan/vscode-syncify)

# Install
## Reset Settings

### User
Paths:
* `${HOME}/.config/VSCodium`
* `${HOME}/.vscode-oss`

Clear:
```sh
rm -rf -- ~/.config/VSCod* ~/.vscod*
```
### Market Place
I am using the [Visual Studio Marketplace](https://marketplace.visualstudio.com). 
The [Open VSX Registry](https://open-vsx.org) is documented for completeness.

File: `/usr/share/codium/resources/app/product.json`

#### Visual Studio Marketplace
```json
"extensionsGallery": {
    "serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
    "cacheUrl": "https://vscode.blob.core.windows.net/gallery/index",
    "itemUrl": "https://marketplace.visualstudio.com/items"
}
```

#### Open VSX Registry
```json
"extensionsGallery": {
    "serviceUrl": "https://open-vsx.org/vscode/gallery",
    "itemUrl": "https://open-vsx.org/vscode/item"
}
```

## Syncify
### Install 
```sh
codium --install-extension arnohovhannisyan.syncify
```
### Configure
see `globalStorage/arnohovhannisyan.syncify/settings-example.json`
