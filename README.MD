MacOS
Homebrew

Windows
Chocolatey

All Platforms
Git
git-annex
git-annex-remote-googledrive
  https://github.com/Lykos153/git-annex-remote-googledrive
Python
Pip
Asciidoctor
GPG
Atom
  tool-bar
  asciidoc-preview
  git-plus
  git-plus-toolbar
  language-asciidoc

pip3 install git-annex-remote-googledrive

git-annex-remote-googledrive setup

git annex initremote osa_google_drive \
type=external \
externaltype=googledrive \
prefix=infrastructure/git-annex/installing_and_maintaining_a_development_environment \
chunk=50MiB \
encryption=hybrid \
mac=HMACSHA512 \
keyid=B4637334
