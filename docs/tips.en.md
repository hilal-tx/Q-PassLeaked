# Professional Coding Tips - English

## What is the usage of `nmap.xml`?
Now you can ask what’s the usage of `nmap.xml`. When you want AI to implement something with that class/module, you need to give them the CODE of the class or documentation. Most AI models can read XML documentations very well and accurately.

## Why should I store the repo when reaching stable code?
TRY to store the repo when you are coming to a stable code. Why? Because we can spoil the code and not be able to run or fix it due to too many wrong fixes, one after another. So, at each stable point, commit a restore point to be able to roll back if you killed your project with wrong codes.

## Why should I test on each development/debug/fix/improvement step?
After 1 hour of development, I’m running it and getting errors one after another. That’s why I told you to test on each development/debug/fix/improvement step. I will record a video later to talk about UNIT_TESTs and logic tests and flow tests. In coding, it has techniques, but I will record how to do it in the fastest way with AI testing all possible routes.

## Why did I add `.gitkeep` to a directory after creating it before committing to git?
Because git normally doesn’t push empty directories to the repository on commit and push. So if we need that directory in our project and it’s not temporary, we need to add a file to it. Adding `.gitkeep` is a standard I normally use to force git to push the new directory to the repository on commit and push. After I add files to it, I remove the `.gitkeep`.

## Why should I first implement a cool, UX-friendly infrastructure?
I don’t like the UX it implemented. So before going forward, let’s first implement a cool, pretty, UX-friendly infrastructure for UX, which we will use in all screens. Elements and views must use non-annoying colors that follow UX-friendly and psychologically non-irritating color combinations and arrangements. Unregular fonts like handwriting are not good implementations except in specific, very rare parts like signatures, some titles, or quotes.

## Why should I ask the AI to check and think about its result?
I asked in the prompt to check and think about its result; it makes the AI recheck its implementation and its bugs. (We call this making AI models think.)

## What should I do when AI models generate incomplete code in long code generations?
In some situations, especially with long code generations, AI models change some pieces of code and add `(// existing function)`, `(// rest of functions)`, `(// summary list of variable values)` and generate incomplete code, asking us to make changes. In these situations, ask them to generate the full file, keeping all features, logic, and flow. Or, if the code is too big, make it modular and separate it into modules.

## What should I do when the chat gets too long and GROK gets confused?
The chat became too long, GROK is getting confused, it needs too much thinking... After very long contexts to achieve these goals, I suggest going to a new chat, but with specific input messages:  
- Give the required implemented codes (especially standard base classes, themes, used classes, ...)  
to let the AI model know where we are and avoid it going through new solutions with other methods that we implemented. It will conflict, produce wrong outputs, or make us re-code pieces we implemented before.