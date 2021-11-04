The goal of the assignments in this course is to create a web application in which one can write down and prove invariants for simple programs. We assume that the code will be written in C and the invariants will be encoded in an ACSL. One may view this as a simplified version of the Frama-C program.

The goal of the first assignment is to create a general view, i.e. mock-up, of the application in a web browser. The general format of the application page should follow the layout on the following picture

![obraz](https://user-images.githubusercontent.com/77683788/140395735-bb3bdfd8-034c-4197-8d0d-8643d284f826.png)

Remember to populate the areas of the interface with some sample data. A number of examples written in ACSL can be found here.
   1. Interface layout in accordance with a picture (5 points)
   
      I. All panes present together with example content (1 p.)
      
      II. Comfortable screen arrangement at the resolution 1024x768 or greater for the ratio 4:3 as well as comfortable screen arrangement at the resolution  1280x720 or greater for the ratio 16:9. (1 p.)
      
        III. Seamless rearrangement of the content when the browser window changes size. (1 p.)
        
        IV. Correct and complete HTML structure checked without warnings by at least one of the tools: htmltest, tidy, html-validate, ​validator@w3.org, (1 p.)
        
        V. Clear and legible HTML code structure (1 p.)
        
  2. CSS that specifies the look of the application (5 points)
 
        I. Use variables to provide at least two colour versions of the page (1 p.)
   
        II. Use media to create a version of the layout for mobile devices (1 p.)
        
        III. Provide both human-readable and automatically compressed (e.g. with yuicompressor) style versions (1 p.)
        
        IV. Correct CSS structure checked without warnings by at least one of the tools: csslint, css-validator@w3.org, stylelint (1 p.)
        
        V. Style (DRY, Naming, no !important, comments for non-local dependencies) (1 p.)
