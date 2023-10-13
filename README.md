# Data_extraction
Trajectory extraction from yolo detection

## Step 1: Combine GPS data to get the time, position, and orientation of the ego vehicle
* required code: combine_gpsdata.ipynb

## Step 2: Transform the local detection into global UTM and prepare for object tracking
* required code: rotation_transformation.ipynb

## Step 3: Object tracking 
* required code: tracking.ipynb
* Need to change the dir
  
```
#INPUT
bboxDirectory = 'yolo_frames/'  # Detection Images Directory (Text Files)

#OUTPUT
outputDirectory = 'yolo_tracking/' # Output Directory of Tracking files
```

## Step 4: Trajectory extraction
* required code: trajectory_extraction.ipynb

```
#INPUT
trackingAnnotationDirectory = 'yolo_tracking/
```

## Step 5: Data cleaning and plotting
* required code: clean_plot.ipynb
