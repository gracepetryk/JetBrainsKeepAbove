#Keep Above for JetBrains Applications
Just a small kwin script that insures that the splash screens and startup screens for JetBrains IDE's start above other windows, while also lowering themselves if another window becomes active. This script works by altering the ```keep above other windows``` property for every window, so if you use that property for anything else this script will likely break that behavior.

##Usage
1. Add ```keepAbove.kwinscript``` in the top level of this repository to the list in ```settings > Window Behavior > Kwin scripts```
2. Add a new window behavior for jetbrains applicatins that forces the ```accept focus``` property to on.
