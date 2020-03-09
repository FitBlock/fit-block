# fit-block
a blockchain system which using JS implement

# build Node
```sh
git clone --recursive git@github.com:FitBlock/fit-block.git
git submodule update --remote
cd ./fit-block/components/fit-block-ui
npm run build
npm run web
```

# develop
clone project
```sh
git clone --recursive git@github.com:FitBlock/fit-block.git
git submodule update --remote
# or
# git clone git@github.com:FitBlock/fit-block.git
# git submodule init
# git submodule update --remote
```
install
```sh
npm install
npm run bootstrap
```
add components
```sh
# example
git submodule add git@github.com:FitBlock/fit-block-core.git ./components/fit-block-core
```