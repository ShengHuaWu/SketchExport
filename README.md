# Sketch Export
Export image assets into your Xcode project from the _.sketch_ file via a python program.

## Usage
- Place your _.sketch_ file and the _sketch-export.py_ file under your project directory.

- Open Xcode, then create a new _Run Script_ in your target's _Build Phases_, and add the following code into it
```
python "$PROJECT_DIR/sketch-export.py" "$PROJECT_DIR/your_design_file.sketch" "$PROJECT_DIR/$PRODUCT_NAME/Images.xcassets"
```

- Build your project and all assets will be located in _Slices_ folder.

## Reference
Thank Ryan Gomab's for providing [this post](http://www.ryangomba.com/automatically-export-sketch-slices-xcode.html).
