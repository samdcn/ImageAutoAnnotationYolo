This is a utility software that requires the .NET 9 library to be installed manually.
The software automatically annotates image sets and videos into YOLO format, reducing the tedious manual annotation work.
Users can customize the output folder, and the software supports automatic annotation for video streams. During video annotation, it automatically performs frame similarity comparison — frames are only captured when differences are detected, followed by automatic annotation. This prevents generating a large number of identical frame images at the same moment.
After automatic annotation, the LabelImg annotation tool can be used for further manual refinement.
Finally, the annotated data can be fed into Python for enhanced model training.
Built-in libraries: YOLOv26n model library and YOLOv26n license plate model library.
