Traffic Camera Vehicle Classification System

This project is a traffic camera vehicle classification system that leverages YOLOv5 (You Only Look Once) to detect and classify different types of vehicles, such as cars, buses, motorbikes, and trucks, from real-time traffic images. The project scrapes live traffic camera images from Singapore’s Land Transport Authority (LTA) and performs object detection on each image to count vehicles by type.


Overview

This system collects images from traffic cameras, classifies the detected vehicles, and provides a real-time count of different vehicle types. It continuously fetches images at intervals, processes them with a YOLOv5 model, and outputs both the vehicle counts for each image and the total counts for the entire process.


Features

Scrapes live traffic images from Singapore’s LTA website.
Classifies four main vehicle types: cars, buses, motorbikes, and trucks.
Displays detection results with bounding boxes.
Summarizes the count of each vehicle type for all processed images.
Runs for a configurable duration, updating every 30 seconds.


Future Enhancements

Implement real-time dashboard visualization to monitor the vehicle count.
Improve the object detection model's accuracy by fine-tuning on traffic-specific datasets.
Add support for more vehicle types and pedestrian detection.