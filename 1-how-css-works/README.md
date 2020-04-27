# Three pillars of writing good HTML and CSS

### 1) Responsive Design
Must work on all devices and all screen sizes. By using techniques like:
- Fluid layouts
- Media queries
- Responsive images
- Correct units
- Mobile first design

### 2) Maintainable and scalable
Code must be:
- Clean
- Easy to understand
- Build with growth in mind
- Reusable
- Well organised files
- Properly named, descriptive classes
- Well structured HTML

### 3) Web Performance
Make website faster and smaller by:
- Less HTTP requests
- Less code
- Compress and or minimize code
- Use a CSS preprocessor
- Use less images
- Compress images properly

### How CSS works behind the scenes
RENDER TREE   Load HTML => Parse HTML                 => Build DOM
                        => Load CSS   => Parse CSS    => Build CSS Object Model
                                        - Conflicting CSS declarations are resolved through cascade
                                        - Process final CSS values

### Parsing CSS
1. Resolving conflicting css declarations AKA the CASCADE

**Cascade**
*Process of combining different stylesheet and resolving conflicts between different CSS rules and declarations, when more than one rule applies to a certain element*

### Importance                    =>    Specificity                   =>  Source Order
1. User !important declarations         1. inline stylesheet              Last declaration will
2. Author !important declarations       2. ID's                           override all other.
1. Author                               3. classes, pseudo, attribute
4. User                                 4. elements, pseudo-elements
5. Default browser declarations         

