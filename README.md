Datalogger to Dropbox with Yun
===============================

A project to use the Arduino Yun as a datalogger that logs to Dropbox. This example is extended from the [Yun Datalogger tutorial](http://arduino.cc/en/Tutorial/YunDatalogger) .

For this example, the Yun reads three sensors, saves them in a text format on the SD card, and uploads the same file to Dropbox.

The Arduino Sketch in this example calls the Python script to upload the file with the logged data. The Python script makes use of the [Dropbox Python Core API](https://www.dropbox.com/developers/core/start/python) for the upload.

![Schematic](https://raw.githubusercontent.com/ankitdaf/yun-datalogger-dropbox/master/Schematic.jpg)

Links
------

Project page : [Yun Datalogger to Dropbox](http://ankitdaf.com/projects/DropboxDatalogger/)

Instructable : [Yun Datalogger to Dropbox](http://www.instructables.com/id/Datalogging-to-Dropbox-with-Arduino-Yun/)