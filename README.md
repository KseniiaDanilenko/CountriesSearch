# TASK
In this archive you can find an index.html file with provided page markup, images, some prepared .scss files, and a design/ folder with expected results.
Your task is to generate two different css files according to design.
- All required css rules and scss mixins should be written in _main.scss and variables should be  defined in _variables1.scss and _variables2.scss files
- Do not change files scss/style1.scss and scss/style2.scss. They already import all necessary partials
- scss file should use a nesting syntax
- you should use mixin for styling links and buttons
- use at least one @extend rule
- se at least one map
- index.html by default should use style1.css for styling
- All distances between blocks should be set by yourself (tips: you can use Pixel perfect browser addon, but it isn’t required)
No requirements for browser support (should correctly work in last version of Google Chrome)
Please use koala-app for compiling. Find a koala-config.json config file where compilation path is already set.
# EXPECTED RESULTS
The style1.css and style2.css are generated from source files.
Page design should match v1.png. When page is switched to use styles2.css by changing link to <link rel=“stylesheet" href="css/style2.css">  it should match v2.png.
You can switch styles manually in header section of index.html.

# FONTS AND COLORS
Fonts are already included in hlml head section, use them as: 
font-family: 'Source Sans Pro', sans-serif;
font-family: 'Hind', sans-serif;
font-family: 'Fresca', sans-serif;
Feel free to use any tool which will help you to pick the right color. Colors should be as close to design as possible. 

# RESTRICTIONS
- Do not use any CSS framework for this homework.
- Do not use any others scss compilers except koala.
