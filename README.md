# Interactive tool for bike fitting utilizing computer vision

This repository only contains a demo with no code. Code will be uploaded once the project is done.

## Demo:
[![Bike fitting app](https://img.youtube.com/vi/ylYORl_xukI/0.jpg)](https://www.youtube.com/watch?v=ylYORl_xukI&ab_channel=MatejKocman)

Video demonstrates all the important functionality of the app.

Notes for video:
- Only the wrist, hip and shoulder keypoints are movable, as demonstrated.
- Clicking on a keypoint selects it and makes it movable with arrow keys.
- Moving a keypoint 'along a bike axis' works for wrist and hip keypoints when moving with arrow keys and means moving along the head and seat post respectively.
- 'Showing measurements in bike axes' works for the wrist and hip keypoints and shows their positional change in the x-axis and head and seat post axes respectively.
- Perfect keypoints are optimalized so that every measurement is as close to the recommended value as possible.
- Recommened keypoints are optimalized so that the biggest discrepancy between the recommended and actual value out of any measurement is the smallest possible.
- Recommended keypoints respect the adjustability limitations of the bike. Perfect keypoints don't.
- While setting up a new position and setting the seat post, head post, fore/aft and scale measurements, the points can also be selected and moved with arrow keys.
- Rebasing changes the base keypoints of the position. It is meant to be used to manually correct the position of inaccurately detected keypoints if needed.
