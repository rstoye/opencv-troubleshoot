## How to install under Manjaro

```sh
sudo pacman -S opencv python-opench hdf5
export OPENCV4NODEJS_DISABLE_AUTOBUILD=1
export OPENCV_LIB_DIR=/usr/lib/

# now either
pnpm install

# or
npm install

# whatever you prefer
```

## Run the project

```sh
pnpm start

# or

npm start
```
