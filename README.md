# C# Documentation Generator (For unity)

**Documentation Generator** simplifies generating documents for your **c#** and **unity** projects.
It uses [doxygen](https://github.com/doxygen/doxygen) with great documentation generation options and [doxygen-awesome-css](https://github.com/jothepro/doxygen-awesome-css) for looks!

## How to use:

1. Setup `config.ini` to fit your needs.
    - This file contains your **Product Name**, **Version**, and **Logo**.
    - Put your scripts path **without a `\` at the end** in `Input`.
2. Add your main index file's content in `main_content.html`.
3. Edit `Logo.png` if you need to.
4. Generate your document by executing `DocumentationGenerator.exe`
5. Congrats! You have your documentation files inside the `html\` folder.

## Preview:
![Preview Image](https://user-images.githubusercontent.com/13370906/164980204-18fa7044-820e-44f4-95c3-f4f42c813f60.png)

## Credits:

- [doxygen](https://github.com/doxygen/doxygen)
- [doxygen-awesome-css](https://github.com/jothepro/doxygen-awesome-css)
