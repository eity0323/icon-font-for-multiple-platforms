Using icon font for multiple platforms
---

This project can make icon font files from Sketch file. 

These font files can be used in Web, Android and iOS.

This project also demos how to use the font files on these platforms.

<div>
    <img src='https://raw.githubusercontent.com/liaohuqiu/icon-font-for-multiple-platforms/master/art/feature.png' width="600px" />
</div>

Thank you [@Okernel](https://github.com/okernel) for make this feature image:

<div>
    <img src='https://raw.githubusercontent.com/liaohuqiu/icon-font-for-multiple-platforms/master/art/feature-okernel.png' width="600px" />
</div>


### Requirements

* Mac
* Skecth
* npm

### How to use

1. Clone or download this project

2. Install

    `sh manage.sh install`

3. Make icon font from Skecth file

    ```
    sh manage.sh make
    ```

    `cube-icons-sample.sketch` is a sample Skecth file, you can change your own one.

4. See what we have

    1. Web

        You can open `samples/web/index.html` in your browser, then you  will see all the icons.

        You also can open it by: 

        ```
        sh manage.sh open
        ```

    2. iOS project

        You can open XCode sample proejct under dirctory: `samples/ios`

    2. Android proejct

        You can open Android Studio sample proejct under dirctory: `samples/android`

### Customize

1.  You can edit `gulpfile.js` to:

    1. Use you own Sketch icon file.

    2. Change the name of the icon files.

    3. Change the css class name.

    4. Other things you want.

2.  All the files under dirctory `dist/` are generated by `gulpfile.js` according the file under dirctory '/templates'

    If can customize your own template files if you want.

### License

MIT

### Thanks

1. This project is mainly based on https://github.com/cognitom/symbols-for-sketch.

2. [@Okernel](https://github.com/okernel)'s beautiful feature image. 

    https://github.com/liaohuqiu/icon-font-for-multiple-platforms/issues/1
