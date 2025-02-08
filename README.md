### Xcode shortcuts

These are my notes from having to watch [XCode Fundamentals in Pluralsight](https://app.pluralsight.com/library/courses/xcode-fundamentals).

- command [0-9] all panels on the left
- command option [1-3] all panels on the right..
  - example command option 3, to read documentation
    - also option + space on any code to pop documentation
- type and search
  - command e applied in word selected, opens search box with the word
  - command shift f then searches for it

#### when writing code
- command shift o to search for a given file.. similar to Jetbrains
- move between tabs command + shift + brackets (left or right)
- jump to definition, bring cursor to word, select command and then right click. Instead of right click also tap on mouse track.
  - I need to find what is the command to go back in the path navigation
- command j to switch between two panes open. 
- command + L, jumps to a given line.. same like Jetbrains
- control 4 jump to file structure
- control 5 jump to current module
- special comments
```
// TODO: Add documentation
// MARK: - AnyDataRepository
```
- control6 shows all methods per file
- command option left and right arrows to collapse or expand a code block
  - if you apply shift then it collapses and expands all blocks in the file
- use preference editor to toggle code foldable ribbbon
- top right corner in editor has a second icon to adjust how to view it. 
  - I used minimap and I saw all the code minified in a small panel and navigate.
  - There is also the option to view/hide the canvas preview for SwiftUI
- place new file in a given pane.. command + shift + o to search for file, then hit (option shift enter) and then use arrow and then hit enter to select position.
- command shift c, to open command prompt


tools:
- xcode provides bookmarks, groups of bookmarks.. this is so nice like in Jetbrains
  - you can even bookmark searches...
- very interesting to preview swiftUI and also uikit
- last chapter is about logging, same idea of using types and preview like in Logcat



### These notes are from [XCode Essentials](https://developer.apple.com/videos/play/wwdc2024/10181).

#### Editing

Being able to search based on a given folder.. See View below
<img width="549" alt="Image" src="https://github.com/user-attachments/assets/81c13b31-f342-49c4-9f17-32f42506258f" />

We have in Android Studio ways to look for subclasses from current class. But this tool does it similarly. 

<img width="490" alt="Image" src="https://github.com/user-attachments/assets/10a91a18-4d26-4551-9eef-b697cc5faa05" />
<img width="497" alt="Image" src="https://github.com/user-attachments/assets/51773a7e-af95-43aa-a849-ab34cb9864ee" />


In Android Studio we have a special command to jump from production class to testing class.. In here that option is found under the grid icon in the tab bar..

<img width="433" alt="Image" src="https://github.com/user-attachments/assets/f73b2675-5c4d-4352-8121-65a012ccfa59" />

For git I loved this way to preview changes to commit. I like to use Gitkraken when reviewing changes to commit and push.
But this preview within Xcode is a lot friendlier. Also we are able to edit those files!

<img width="1461" alt="Image" src="https://github.com/user-attachments/assets/b59caf88-1443-4e57-8efd-396ee215e5b4" />
