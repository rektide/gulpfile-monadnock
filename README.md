# gulpfile-monadnock
A basic structure for project building, where the build isolates itself inside a "build" container and the the top level remains dedicated to source. Includes a complementary skeleton gulpfile from [Apex Gulpfile](http://vmorneau.me/basic-gulpfile/), whose greater structure I find to be fair and hence include as a getting started reference.

#Apex Gulpfile Features
- CSS (concatenation, minification, autoprefixer)
- JS (concatenation, minification)
- IMG (optimization)
- Vendor files (copy)
- Output of minified and un-minified JS & CSS
- Filesize indicator
- User friendly error handling

#Install
```npm install```

#Run
```npm start```

#How to use
From the root folder, You can create, edit or delete any files in:
```
|-/
    |-**/*.j
    |-css
    |-img
    |-lib
```

The Gulp magic will happen and compile your files to this folder structure:

```
|-/build
    |-css
    |-img
    |-js
    |-lib
```

###That's all! Enjoy a faster & cleaner static files handling.
