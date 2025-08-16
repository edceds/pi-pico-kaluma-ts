build
tsc index.ts --skipLibCheck

flash
kaluma flash ./index.js --bundle --shell
