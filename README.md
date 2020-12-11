# parking-lot-search-demo

------

Here is the simple demo for searching parking lots on the street side:


![](demo.gif)



## How to finish it?

We finish the project based on the works:

- Lane Detection
- Drivable Area Segmentation
- Object Detection

And we search the available free space based on the number of cars on the street side and the mean IoU of all the cars. 

If there are few detected cars and the mIoU of 2 cars is less than 0.1, then the free space is available!!!


The codes used above the works will be uploaded and open to the public in the future.
