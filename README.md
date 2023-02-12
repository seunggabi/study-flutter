### docs
- https://docs.flutter.dev/
- https://flutter.github.io/samples/#
- https://codelabs.developers.google.com/codelabs/flutter-codelab-first#3

### install
```shell
brew install flutter

flutter doctor

sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
sudo xcodebuild -runFirstLaunch
```
```shell
brew install ruby

echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
export LDFLAGS="-L/opt/homebrew/opt/ruby/lib"
export CPPFLAGS="-I/opt/homebrew/opt/ruby/include"

brew cleanup ruby
brew instal coocapods
```
```shell
cd ~/Library/Application Support/JetBrains/Toolbox/apps/AndroidStudio/ch-0/221.6008.13.2211.9514443/Android Studio.app/Contents

sudo ln -s jbr jre
```
```shell
flutter config --android-sdk ~/Library/Android/sdk 
```
```shell
flutter create app

cd app

flutter run
flutter run -d chrome --web-browser-flag "--disable-web-security"
```
