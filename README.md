# https://capacitorjs.com/docs/basics/building-your-app
# https://stackoverflow.com/questions/38194032/how-to-update-ruby-version-2-0-0-to-the-latest-version-in-mac-osx-yosemite
# https://developer.apple.com/download/more/

npm run build
npx cap copy

npx cap add android
npx cap copy android
npx cap open android