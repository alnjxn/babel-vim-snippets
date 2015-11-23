# babel-vim-snippets
Next generation JavaScript and React snippets for Vim https://babeljs.io

A direct port of the snippets from available from [babel-sublime-snippets](https://github.com/babel/babel-sublime-snippets)

Currently written with support for [UltiSnips](https://github.com/SirVer/ultisnips) only.

## Installation
Install your favorite Vim plugin manager. (i.e. [Vundle](https://github.com/VundleVim/Vundle.vim), [pathogen](https://github.com/tpope/vim-pathogen), [vim-plug](https://github.com/junegunn/vim-plug), [neobundle](https://github.com/Shougo/neobundle.vim))

Modify the following depending on your plugin manager and add to your `.vimrc` file. If you do not alread have [UltiSnips](https://github.com/SirVer/ultisnips) installed you will need it for compatibility.

Example using [neobundle](https://github.com/Shougo/neobundle.vim)

```
" UltiSnips required for compatability
NeoBundle 'SirVer/ultisnips'

" babel-vim-snippets
NeoBundle 'alnjxn/babel-vim-snippets'

" Other snippets (optional)
NeoBundle 'honza/vim-snippets'
```

## Available snippets

### ES6

### React

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rcc→`   | legacy component skeleton |
| `cdm→`   | `componentDidMount() {…}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `cwm→`   | `componentWillMount() {…}` |
| `cwr→`   | `componentWillReceiveProps(nextProps) {…}` |
| `cwun→`  | `componentWillUnmount() {…}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `fdn→`   | `React.findDOMNode(…)` |
| `gdp→`   | `getDefaultProps() {…}` |
| `gis→`   | `getInitialState() {…}` |
| `ren→`   | `render() {…}` |
| `sst→`   | `this.setState(…)` |
| `scu→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |

## ToDo:

* [ ] Add snipmate support

