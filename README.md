# Simba_batch
#### Usage
![zp9NyDDC5kO92CNlWMCbEffPLz0x788bZd_qfNDpWPoadr8u-QTw7Pi1novXG9VS_VtYGxsIVcumcfjbZjOKNqbm-bG31YlDQu9FN-m9fWg-3tcN9ojaSecUyvFL copy](https://user-images.githubusercontent.com/71047773/162664557-138776ef-bfe0-4053-8274-b6ac32805ba2.jpg)

* If you run the program by simply typing <pre><code>$ python3 SAS_batch.py</code></pre> the program will search for all available projects in the current directory and process them with default parameters (a valid project folder contains scan files that look like scan_NUMBER.py and joint files that look like joints_NUMBER.csv)
* An example to run the program with the optional arguments: 
<pre><code>python3 SAS_batch.py --input /Volumes/tri-biosci/Avatars/Kinect_Data_Processing_2021/SAS_ExampleScans_Sept2021 --output /Volumes/tri-biosci/Avatars/Kinect_Data_Processing_2021/Result_Scans --radius 350 --smoothiter 2 --edgeLength 13
</code></pre>
