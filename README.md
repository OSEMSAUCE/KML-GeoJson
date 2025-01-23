*Geojson Converter*

Maps are cool, but they're so cool that developers get very distracted with what's really important. 
Our job is very, very simple. So simple that it might be better if a non-geography dev or analyst does it.

We need only the *polygons*. 

- A polygon is a shape, drawn by connecting the dots (gps points). It could have 3 corners, just 3 gps points. Or 5,000 data points (hopefully not!).
- Polygons come in different formats of data. The format we want we wanna use is **GeoJson**. 
- Another easy format is **KML**
- There's also Shape files which are much more difficult to manage because of proprietary and costly ArcGIS software.
- We simply want the polygons to load onto our map. The polygon may however, have some metadata, and if possible preserve that metadata, along with the shape.
- Here is an ([example of the formats](https://drive.google.com/drive/folders/1vBWcN2G2ByaEwRjLUQlDajLVIcmTxGXJ?usp=sharing))

**What we need**, is a drag and drop app, or otherwise sufficiently automated process, to drop a shape file and an app will extract only the shape file and metadata where possible. ([Like this appl](https://mygeodata.cloud/converter/kml-to-geojson) but 
This is harder than it sounds, even though an app can identify the string of GPS data easily, there are like 4 several GPS formats.  You could just have the app print all 3-4 locations and a person could load each one since we can see on a map if ti's in Brazil or not. But there's other considerations like keeping the metadata, and some shape files have A LOT of data in them so handling all the edge cases is a hassle.  
But this is a good project, we're aiming low ;)  Anything would be better that what we're doing currently 🌲️♥️
Let me know if you have any questions.
Regards, 
Chris

![image](https://github.com/user-attachments/assets/b38105be-1355-4819-b8fd-d7da7cce8688)


![image](https://github.com/user-attachments/assets/63c37a0c-bfed-463a-be2b-29a9d3e0bf3a)
