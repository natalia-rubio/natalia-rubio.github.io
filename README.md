# SimVascular Website

This is the repository for the SimVascular website.

## Usage

The SimVascular website documentation can be found in the documentation folder, and the SimVascular website clinical test cases can be found in the clinical folder. In each folder, there are `html` files and their corresponding folder, which share the same name. For example, the folder associated with the `quickguide.html` file is named quickguide.

In each folder, there are markdown files from which the content in the `html` files is generated. [Markdown](https://daringfireball.net/projects/markdown) is a lightweight markup language with plain text formatting syntax that can be editied using a text editor.

The markdown files are accessed and translated into `html` through the `<zero-md>` element, which is placed in the `html` file. Documentation on `<zero-md>` can be found [here](https://zerodevx.github.io/zero-md/).

Before editing, you should first fork **simvascular.github.io** to your own repository and sync it with https://github.com/SimVascular/simvascular.github.io.

### Editing existing documentation

### Adding new sections on the same `html` page

### Creating documentation or clinical test case pages
If you want to create a new documentation page, find and copy the `template.html` page in the documentation folder. If you want to create a new clinical test case page, find and copy the `template.html` page in the clinical folder. These pages will have the foundational `html` necessary for the documentation or clinical case page. There are three places in this file to find and update in order to create a new documentation or clinical test case page: the header, the navigation section, and the paths to the new markdown files from the `<zero-md>` element.

### Editing the home page
Unlike the documentation and clinical test cases, the home page is written purely in `html` and is not generated from `md` files.
