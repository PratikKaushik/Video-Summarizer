# Video-Summarizer
It becomes a very difficult task to go through so many hours of footage 
to find useful content. Storing the videos also takes up a huge amount of space. Thus, a need for 
surveillance solutions is recognized that can condense such long footage into short videos while 
still retaining important events. Our model can summarize hours of footage shot by CCTV cameras 
into a short clip that shows all interesting events simultaneously. All moving objects that are 
present in the video are identified and tracked by our program. These events are then overlaid on 
a single clip, while also displaying the timestamps for each event, thus letting the user perform 
surveillance for multiple events. Our model uses the KNN model for extracting and subtracting 
background from videos and a custom Object Tracking algorithm to detect moving objects, which 
are then overlapped on the extracted background. 
