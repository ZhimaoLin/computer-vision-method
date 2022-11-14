# Use Computer Vision to Read Dial Indicator

Computer vision can be also used to detect bolt looseness. The looseness of the bolt is converted to the reading of a depth gauge through the inspection hole on the bolt. Then, an algorithm using [Hough Transform](https://en.wikipedia.org/wiki/Hough_transform) with [Canny edge detection](https://en.wikipedia.org/wiki/Canny_edge_detector) was developed to read the dial indicator. With this algorithm, a range of 0-3 $mm$ depth change can be detected with a resolution of 1 $\mu m$. 

## References

- [Analogue Gauge Reader using Computer Vision](https://medium.com/@nayak.abhijeet1/analogue-gauge-reader-using-computer-vision-62fbd6ec84cc)
- [MACHINE LEARNING IN PRACTICE: USING ARTIFICIAL INTELLIGENCE TO READ ANALOG GAUGES](https://objectcomputing.com/resources/publications/sett/june-2019-using-machine-learning-to-read-analog-gauges)
- [analog-gauge-reader](https://github.com/intel-iot-devkit/python-cv-samples/tree/master/examples/analog-gauge-reader)
- [Edge Detection | Boundary Detection | SIFT Detector](https://www.youtube.com/playlist?list=PL2zRqk16wsdqXEMpHrc4Qnb5rA1Cylrhx)
