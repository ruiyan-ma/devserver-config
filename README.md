## Install node for coc.nvim

```
sudo dnf module list nodejs

sudo dnf module enable nodejs:12

sudo dnf module install nodejs:12
```
## cocnvim plugins

coc-word coc-tabnine coc-snippets coc-marketplace coc-lightbulb coc-html coc-xml coc-vimlsp

coc-tsserver coc-sql coc-sh coc-pyright coc-pydocstring coc-json coc-java coc-css

## Ale & cocnvim

Add the following code to your coc configuration file:

Typing `:CocConfig` in vim to open coc configuration file.

```json
{"diagnostic.displayByAle": true}
```
