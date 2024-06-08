# BLIND-SPOT-DETECTION
The project is related toward's blind spot detection using image processing.

The project is built using method of image processing, deep learning and embedded system.

What is a Blind Spot?
A blind spot is an area that the driver cannot see either directly or by using the vehicle’s mirrors. Typically, a blind spot occurs in an area that is behind the driver and off to one side of the car. Larger vehicles are more prone to bigger blind spots because the body of the car obscures the view of surrounding motorists.

Also, the height of the vehicle can make it harder for a driver to see vehicles below where they are seated, such as in the elevated driver’s seat of a truck’s cab. In large trucks, blind spots may also exist in the space that can extend several feet behind the truck’s trailer, which makes tailgating behind a truck extremely risky. The front of a big truck, or even a smaller vehicle, may also have a large blind spot.

What Typically Causes a Blind Spot Car Accident?
Although this type of accident is possible when a car first starts, such as when a vehicle is in reverse and backs over something in the driveway, blind spot accidents often occur when the car is moving on a busy road. Blind spot accidents frequently happen when drivers are merging or changing lanes. These accidents are more likely to happen on highways, where travelling at high speeds makes maneuvers even more perilous. Additionally, blind spot collisions commonly occur in roundabouts and intersections.

A blind spot accident typically occurs because a driver does not properly check all mirrors and angles to ensure that the area around the vehicle is free of other cars or obstructions. Before driving, it is important to adjust all mirrors to reduce the likelihood of an accident.

In this project the Hardware componenet used are:
    -> esp32cam,
    -> OLED display,
    -> FTDI module(This module is used for the purpose of connectting the esp32cam with the laptop or pc),
    -> memory card.

The prototype works in given steps ->
    1. The image is taken by the esp32cam,
    2. The image is preprocessed and further transfered for the process of object classification,
    3. The given image data is classified and it's output is displayed on Oled display.
