# SneakyKobold Project Setup Tutorial
Here's how to setup your EclipseIDE before pulling from [this project link](https://github.com/2110215-ProgMeth/cedt-project-2024-2-n-and-his-backup).<br>
(I'll change this later once the project is complete!)

## Here's what you're gonna have to do
1. You'll have to download `jdk-21` and `javafx-sdk-21.0.6` (which you can download the files from here).
2. Move them to somewhere you wouldn't have trouble navigating, I recommened moving both to `C:\Program Files\Java` or wherever your Java folder is located. (You'll have to allow it using admin's permission, otherwise use another folder)
3. Open Eclipse, navigate to: Window > Preferences > Java > Installed JREs > Add
4. Add both `jdk-21` and all files in `javafx-sdk-21.0.6\lib` to the `Standard VM` jre type.
5. Name the new jre `jdk-21-with-fx` (If you use other names, Eclipse won't be able to find it from `.classpath`).
6. Add the VM argument. If your `javafx-sdk-21.0.6` is in `C:\Program Files\Java` you can copy this line:

> -module-path "C:\Program Files\Java\javafx-sdk-21.0.6\lib" --add-modules javafx.controls,javafx.fxml
 
Otherwise, replace the `"C:\Program Files\Java\javafx-sdk-21.0.6\lib"` with your javafx path.
