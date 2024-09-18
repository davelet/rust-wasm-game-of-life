Constructed from https://rustwasm.github.io/docs/book/game-of-life/introduction.html.

# Clone this repo
这个库包含了子模块，所以克隆的时候需要使用
```bash
git clone --recursive git@github.com:davelet/rust-wasm-game-of-life.git
```
或者
```bash
git clone git@github.com:davelet/rust-wasm-game-of-life.git
cd rust-wasm-game-of-life
git submodule update --init --recursive
```
# Build
在根目录`rust-wasm-game-of-life`下执行
```bash
wasm-pack build --release
```
新起一个终端，切到`www`下面执行
```bash
npm run start
```
# Use
浏览器访问 https://localhost:8080/ ，点击画布开始。
