# gpx-add-SRTM-elevation
Adding SRTM elevation points to a gpx file

Building on top of [SRTM-GeoTIFF](https://github.com/nicholas-fong/SRTM-GeoTIFF), this Python code takes a gpx file and matches up SRTM data files (GeoTIFF) stored on local drive and outputs to STDOUT.

Example Usage:<br>
download n22_e114.tif, Kowloon-Peak.gpx and gpx-add-elevation.py to a local directory,<br>
python gpx-add-elevation.py Kowloon-Peak

[How to download USGS-SRTM GeoTIFF files](https://github.com/nicholas-fong/gpx-add-SRTM-elevation/blob/main/EarthExplorer-howto.md)

You can achieve the same with online tool [GPS Visualizer](https://www.gpsvisualizer.com/).

This python code offers an offline solution. If you have recorded gpx tracks using mobile phones, you can use this code to clean up/smooth the elelvation profile of the gpx tracks. 
