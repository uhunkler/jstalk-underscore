# jstalk-underscore

An adoption of the [underscore](https://github.com/jashkenas/underscore) functional library which can be used in JSTalk projects for Sketch and Acorn.

The methods implemented so far:
- any
- each
- filter
- find
- has
- identity
- include
- isJSTObject
- isJSTArray
- isArray
- isObject
- isUndefined
- isNull
- keys
- map
- reverse (jstalk only)

How to use the functions you can refer to the excellent [underscore.js](http://underscorejs.org/) documentation - the JSTalk version should work the same way. If not please submit a bug.

The "test" covers the underscore functionality with simple tests. To run the tests copy the `test` folder and the `underscore.jstalk` file into the Sketch plugin directory. Open the Sketch file `jstalk-underscore-tests.sketch` with three colored squares. Please don't change the document because it is part of the JSTalk functionality tests. Those tests may fail when the document is changed.

Then run the "test" from the plugin menu or with the "command shift T" shortcut. The test output is logged to the console. To watch the test logs continuously open a terminal and type 
`tail -f /var/log/system.log | awk '/Sketch\[/,/SketchEOL/'` 
to display the last logged lines.