# [<img src="" height="48" width="48" /> gobby](https://chocolatey.org/packages/nomacs)

nomacs is a free image viewer for windows, linux, and mac systems, which is licensed under the GNU General Public License v3. nomacs is small, fast and able to handle the most common image formats including RAW images. Additionally it is possible to synchronize multiple viewers. A synchronization of viewers running on the same computer or via LAN is possible. It allows to compare images and spot the differences (e.g. schemes of architects to show the progress).

## Features

- Image Viewing
  - supports the most common image formats including RAW
  - fast thumbnail preview
  - zoomable grid preview of thumbnails
  - display exif information
  - framless view
  - change transparency of windows
  - display overview/histogram/file info
  - file filtering/searching/sorting
  - improved anti-aliasing
  - hide menubar and toolbar
- Image Editing
  - crop images
  - resize images
  - pseudo color function
  - color adjustments (brightness, contrast, saturation …)
  - multi page TIFF export
  - rotate images
  - drag and drop images
  - automatically save screenshots
  - delete/rename images
  - create mosaic image
  - set wallpaper (windows only)
- Viewer Synchronization
  - synchronize multiple instances
    - synchronized zooming
    - synchronized panning
    - synchronized next/previous file
    - overlay of two or more instances (with changing opacity)
    - arrange synchronized instances
  - synchronize multiple instances in the LAN
    - synchronized zooming
    - synchronized panning
    - images can be sent over LAN connection

See detailed nomacs [features page](http://nomacs.org/features/).

## Notes

- This package will **always install the latest version**, regardless of the version specified in the package. Nomacs is using [online installer](https://www.nomacs.org/redmine/issues/573) for non-portable package exlusivelly.
- If you are installing **behind the proxy**, you will need to configure proxy settings in the installer manually (via Settings button) during the installation. You can use [nomacs.portable](https://chocolatey.org/packages/nomacs.portable) as alternative in such scenario.