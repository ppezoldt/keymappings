# Goal
Intuitive keymap that works for most IDEs and text editors and has no or only few changes when switching between Windows/Linux/Mac and en/de keyboard layout

# Visual Studio
Download keymappings.vssettings and import via Tools => import and export settings

# Visual Studio Code
#### Cloud sync
Use [Settings sync extension](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)

Set **removeExtensions** and **syncExtensions** to **false** to prevent overwriting of installed extensions

Select Download Settings from public gist and use gist id

	5483190ad0576a711f5add905d3b8a2d

#### Manual overwrite
Download keybindings.json or keybindingsMac.json and replace file

# Sublime Text
Download **.sublime-keymap** files and replace

# Jetbrains Rider, Webstorm, etc
Download **jetbrains_macos.jar** and import via File => Import Settings

# Keymapping table


|  |  |  |  |  |  |  |  |  |
|  ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|   | **Mac** | **Windows/Linux** | **Rider macOS** | **Webstorm macOS** | **VS Code macOS** | **Visual Studio** | **Sublime Text macOS** | **Sublime Text linux** |
|  **Navigation** |  |  |  |  |  |  |  |  |
|  **back** | cmd j | ctrl j | X | X | X | X | X | X |
|  **find next** | F3 | F3 | X | X | X | X | X | X |
|  **find previous** | shift F3 | shift F3 | X | X | X | X | X | X |
|  **find usages/references** | cmd F12 | ctrl F12 | X | X | X | X |  |  |
|  **forward** | cmd k | ctrl k | X | X | X | X | X | X |
|  **goto declaration** | shift F12 | shift F12 | X | X | X | X |  |  |
|  **goto file** | cmd p | ctrl p | X | X | X | X |  |  |
|  **goto implementation** | F12 | F12 | X | X | X | X | X | X |
|  **goto symbol in context** | cmd shift p | ctrl shift p | X | X | X | X | X | X |
|  **goto type** | cmd t | ctrl t | X | X | X | X | X | X |
|  **open anything** | shift shift <code>&amp;#124;</code> F4 | shift shift <code>&amp;#124;</code> F4 | X | X |  | X | X | X |
|  **open file** | cmd o | ctrl o | X |  | X | X | X | X |
|   |  |  |  |  |  |  |  |  |
|  **Debugging** |  |  |  |  |  |  |  |  |
|  **build** | cmd b | ctrl b | X |  | X | X |  |  |
|  **continue** | F5 | F5 | X | X | X | X |  |  |
|  **debug** | F5 | F5 | X | X | X | X |  |  |
|  **delete all breakpoints** | cmd shift F9 | ctrl shift F9 |  |  | X | X |  |  |
|  **enable/disable all breakpoints** | shift F9 | shift F9 |  |  |  |  |  |  |
|  **rebuild** | cmd shift b | ctrl shift b | X |  |  | X |  |  |
|  **restart debug** | cmd shift F5 | ctrl shift F5 |  |  | X | X |  |  |
|  **run** | cmd F5 | ctrl F5 | X | X | X | X |  |  |
|  **step into** | F6 | F6 | X | X | X | X |  |  |
|  **step out** | F7 | F7 | X | X | X | X |  |  |
|  **step over** | F8 | F8 | X | X | X | X |  |  |
|  **stop debug** | shift F5 | shift F5 | X | X | X | X |  |  |
|  **toggle breakpoint** | F9 | F9 | X | X | X | X |  |  |
|  **view breakpoints** | cmd F9 | ctrl F9 | X | X | X | X |  |  |
|   |  |  |  |  |  |  |  |  |
|  **Editor** |  |  |  |  |  |  |  |  |
|  **actions/commands** | cmd shift a | ctrl shift a | X | X | X | X | X | X |
|  **close all editor tabs** | cmd shift w | ctrl shift w | X | X | X | X | X | X |
|  **close editor tab** | cmd w | ctrl w | X | X | X | X | X | X |
|  **comment block** | cmd shift option c | ctrl shift alt c | X | X | X | X | X | X |
|  **comment line** | cmd shift c | ctrl shift c | X | X | X | X | X | X |
|  **copy** | cmd c | ctrl c | X | X | X | X | X | X |
|  **cut** | cmd x | ctrl x | X | X | X | X | X | X |
|  **delete line** | cmd l | ctrl l | X | X | X | X | X | X |
|  **duplicate line** | cmd d | ctrl d | X | X | X | X | X | X |
|  **generate here** | cmd shift g | ctrl shift g | X | X |  | X |  |  |
|  **move line down** | ctrl shift option down | ctrl shift alt down | X | X | X | X | X | X |
|  **move line left** | ctrl shift option left | ctrl shift alt left | X |  |  | X |  |  |
|  **move line right** | ctrl shift option right | ctrl shift alt right | X |  |  | X |  |  |
|  **move line up** | ctrl shift option up | ctrl shift alt up | X | X | X | X | X | X |
|  **next editor tab** | ctrl tab | ctrl tab | switcher | switcher | switcher | switcher | X | X |
|  **open autocompletion** | ctrl space | ctrl space | X | X | X | X | X | X |
|  **open suggestions** | cmd enter | ctrl enter | X | X | X | X |  |  |
|  **organize code in document** | cmd shift o | ctrl shift o | X | X | X | X | X | X |
|  **paste** | cmd v | ctrl v | X | X | X | X | X | X |
|  **previous editor tab** | shift ctrl tab | shift ctrl tab | switcher | switcher | switcher | switcher | X | X |
|  **redo** | cmd shift z | ctrl shift z | X | X | X | X | X | X |
|  **refactor this** | cmd shift r | ctrl shift r | X | X |  | X |  |  |
|  **replace** | ctrl h | ctrl h | X | X | X | X | X | X |
|  **replace over files** | ctrl shift h | ctrl shift h | X | X | X | X | X | X |
|  **save** | cmd s | ctrl s | always save all | always save all | X | X | X | X |
|  **save all** | cmd option s | ctrl alt s | always save all | always save all | X | X | X | X |
|  **save as** | cmd shift s | ctrl shift s |  | X | X | X | X | X |
|  **search** | cmd f | ctrl f | X | X | X | X | X | X |
|  **search over files** | cmd shift f | ctrl shift f | X | X | X | X | X | X |
|  **select all** | cmd a | ctrl a | X | X | X | X | X | X |
|  **undo** | cmd z | ctrl z | X | X | X | X | X | X |
|  **zoom in** | cmd + | ctrl + | X | X | X | X | X | X |
|  **zoom out** | cmd - | ctrl - | X | X | X | X | X | X |
|   |  |  |  |  |  |  |  |  |
|  **Views** |  |  |  |  |  |  |  |  |
|  **File explorer** | cmd 1 | ctrl 1 | X | X | X | X |  |  |
|  **Issues** | cmd 2 | ctrl 2 | X | X | X | X |  |  |
|  **Find** | cmd 3 | ctrl 3 | X | X |  | X |  |  |
|  **Favorites** | cmd 4 | ctrl 4 | X | X |  |  |  |  |
|  **Debug** | cmd 5 | ctrl 5 | X | X | X |  |  |  |
|  **Build** | cmd 6 | ctrl 6 | X | X |  | X |  |  |
|  **Unit Tests** | cmd 8 | ctrl 8 | X | X |  | X |  |  |
|  **Version Control** | cmd 9 | ctrl 9 | X | X | X |  |  |  |
|   |  |  |  |  |  |  |  |  |
|  **Double hotkeys** |  |  |  |  |  |  |  |  |
|  **Refactor** |  |  |  |  |  |  |  |  |
|  **extract field** | cmd e f | ctrl e f | X | X |  | X |  |  |
|  **extract interface** | cmd e i | ctrl e i | X | X |  | X |  |  |
|  **extract method** | cmd e m | ctrl e m | X | X |  | X |  |  |
|  **extract parameter** | cmd e p | ctrl e p | X | X |  | X |  |  |
|  **extract superclass** | cmd e s | ctrl e s | X | X |  | X |  |  |
|  **extract variable** | cmd e v | ctrl e v | X | X |  | X |  |  |
|  **move** | cmd r m | ctrl r m | X | X |  | X |  |  |
|  **pull member up** | cmd r u | ctrl r u | X | X |  | X |  |  |
|  **push member down** | cmd r d | ctrl r d | X | X |  | X |  |  |
|  **rename** | cmd r r | ctrl r r | X | X | X | X |  |  |
|  **secure delete** | cmd r l | ctrl r l | X | X |  | X |  |  |
|   |  |  |  |  |  |  |  |  |
|  **Generation** |  |  |  |  |  |  |  |  |
|  **constructor** | cmd g k | ctrl g k |  |  |  | X |  |  |
|  **new class** | cmd g c | ctrl g c |  |  |  | X |  |  |
|  **new interface** | cmd g i | ctrl g i |  |  |  | X |  |  |
|  **override member** | cmd g o | ctrl g o |  |  |  | X |  |  |
|  **override ToString()** | cmd g s | ctrl g s |  |  |  | X |  |  |
|  **equals** | cmd g e | ctrl g e |  |  |  | X |  |  |
|   |  |  |  |  |  |  |  |  |
|  **Unit Test** |  |  |  |  |  |  |  |  |
|  **show unit tests** | cmd u u | ctrl u u | X |  |  | X |  |  |
|  **run all tests** | cmd u a | ctrl u a | X |  |  | X |  |  |
|   |  |  |  |  |  |  |  |  |
|   |  |  |  |  |  |  |  |  |
|  **More** |  |  |  |  |  |  |  |  |
|  **integrated terminal** | cmd m t | ctrl m t | X | X | X | X |  |  |
|  **Nuget** | cmd m n | ctrl m n | X |  |  | X |  |  |
|  **split vertically** | cmd m s | ctrl m s | X | X | X | X | X | X |
|  **type hierarchy** | cmd m h | ctrl m h |  | X |  | X |  |  |
|  **unsplit** | cmd m shift s | ctrl m shift s | X | X |  |  | X | X |