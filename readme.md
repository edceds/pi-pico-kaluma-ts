Typescript on Raspberry Pi Pico using Kaluma

## install

`npm install -g tsc @kaluma/cli`

## build

`tsc index.ts --skipLibCheck`

## flash

`kaluma flash ./index.js --bundle --shell`
