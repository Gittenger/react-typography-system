# React typography system

This is a typography system I developed to easily import fonts to an existing react project, as well as to easily create extendable components using styled-components.

Go to the "fonts" directory and add your font. Create an index file using the same API as used in the example file. Font will be automatically imported in global style component according to the rules you set in the index.

Set CSS custom properties for the imported font in the "fontVars" file.
Set shared font styles in "sharedStyles" file. These will be set in global styles.

Create custom typography components in components directory. Then compose components using these custom components. Extend them using styled-components styled function.
