# CodeMorpher C\C++ Code Obfuscator
## by RandomBlocks Lab
### https://codeobfuscator.net/

### Advantages of using CodeMorpher:
CodeMorpher is a powerful tool that can help you to protect your code from prying eyes, ensuring that your intellectual property remains secure. Whether you're working on a commercial software product or an in-house application, our code obfuscator can help you to keep your code safe and secure.

CodeMorpher uses a Clang AST parser to process at source level and produce new obfuscated code with same logic but always differently at binary level. Everytime new unique blocks of code, control flow of code, branchs, number of instructions, offsets and opcodes are always different.

No need to manually prepare source code by marking for success obfuscation, everything works automatically.
Use any compiler as you use for your projects. Platform & compiler independent - no matter if you compile for x86, x86 or for arm. Protected code will work anyway.

#### Our solution uses the best obfuscation techniques to make manual and automatic analysis harder.
#### Our Obfuscator is one of the most powerful solutions on the market due to it's unique functions.
#### One of the main ideas behind our solution is obfuscation that aims to not stand out.

### Obfuscation techniques and features:
-Source level scrambling
-Dummpy code insertion
-Fake functions generation
-Expressions morphig
-Strings encryption
-Arithmetic obfuscation
-Opaque predicate insertion
-GoTo obfuscation
-Ordering obfuscation
-Control Flow obfuscation
-Proxy calls obfuscation
-Anti-tampering protection
-Operators morphing
-PE Sections Obfuscation
-Code Duplication
-Code Merging
-Instructions substitution
-AI-controlled generation

* CodeMorpher is cross-platform product and can be installed and used on Windows, MacOS or Linux OS
* CodeMorpher uses command line interface. It's easy to embed it into the build process of your project
* CodeMorpher is higly customizable with manual options changing via config file
* CodeMorpher uses Clang parser and support almost all modern C++ syntax

<img>![изображение](https://user-images.githubusercontent.com/122269539/211286880-5ea741c8-4dff-433a-af54-b6a51763334e.png)

## Usage:
>  ./codemorpher -i "input_project" -o "output_project" -s seed_here -c config_here

  Example:
>  ./codemorpher -i "input_project" -o "obfuscated_project" -s 100010200202002 -c "msvc_win.cfg"
