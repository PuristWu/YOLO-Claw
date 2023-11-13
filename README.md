# YOLO-Claw
#### Thank you for your interest in our research!" Important results and source code of "YOLO-Claw: Enabling robust all-day claw detection on commercial layer farms" will be posted here!
   
#### Note:Due to file size limitations, the longer video demos can be viewed on the following platforms:
### [YouTube](https://www.youtube.com/watch?v=f_NXkoem-bc)     [Bilibili](https://www.bilibili.com/video/BV13N41137Ko/?vd_source=dbf425d5883bb58ae44146a6ba54e40d) 
---
## <div align="center">Basic information about the manuscript
#### <div align="left">"Dihua Wu; Yibin Ying; Mingchuan Zhou; Jinming Pan and Di Cui. YOLO-Claw: Enabling robust all-day claw detection on commercial layer farms"</div>
## <div align="center">Claw detection process and potential applications in PLF</font></div>
![幻灯片2](https://github.com/PuristWu/YOLO-Claw/assets/90194261/ccf83bab-353e-4c29-9682-fb0b7dfd861d)
## <div align="center">Challenges</font></div>
![幻灯片3](https://github.com/PuristWu/YOLO-Claw/assets/90194261/c36a5f21-225d-4932-88eb-643923a41133)
## <div align="center">Overall technical route</font></div>
![幻灯片4](https://github.com/PuristWu/YOLO-Claw/assets/90194261/6fe666b0-5d07-4a8d-8689-1acb553bc235)
## <div align="center">Contributions</font></div>
![幻灯片5](https://github.com/PuristWu/YOLO-Claw/assets/90194261/0f7e761a-ccb5-420b-9c6e-1edd1a474495)
## <div align="center">Important results</font></div>

* ### <div align="left">Performance of different object detection algorithms for chicken claw detection</div>
|Algorithms |Precision<br>(%) |Recall<br>(%) |mAP<br>(%) |Speed<br>(ms/frame) |Model Size<br>(MB) |Calculations<br>(GFLOPs) |
|---                    |---  |---    |---    |---    |---    |---    
|[YOLOv5]      |95.2  |91.7   |96.6   |7.1 |14.1|15.8
|[YOLOv6]      |93.8  |75.3   |93.9   |8.5     |36.2    |44.1    
|[YOLOv7]      |94.0  |91.1   |93.5   |9.2    |71.2    |103.2    
|[YOLOv8]     |95.0  |92.3   |96.3   |9.7    |21.4   |28.4    
|[**YOLO-Claw(Ours)**]      |**<ins>95.3<ins>**  |**<ins>93.6<ins>**   |**<ins>97.1<ins>**   |**<ins>7.6<ins>**    |**<ins>12.1<ins>**   |**<ins>14.3<ins>**   
#### <div align="left">Grad-CAM visualization of claw detection on different object detection algorithms</div>
![图2](https://github.com/PuristWu/YOLO-Claw/assets/90194261/877ccb1a-d326-4c10-b68e-4b965ee7182d)

* ### <div align="left">Comparison of the proposed algorithm with the state-of-the-art research</div>
|Authors |Object |Method |mAP<br>(%) |
|---                    |---  |---    |---        
|([Jiang et al.,2019](https://www.sciencedirect.com/science/article/abs/pii/S0168169919309263))      |Cow  |FLYOLOv3   |90.83   
|([Wu et al., 2020](https://www.sciencedirect.com/science/article/abs/pii/S1537511019309006))      |Cow  |YOLOv3   |93.73      
|([Kang et al., 2020](https://www.sciencedirect.com/science/article/pii/S002203022030713X))      |Cow  |RFB_Net_SSD   |87.0      
|([Zheng et al., 2023](https://www.sciencedirect.com/science/article/abs/pii/S0168169923000066))      |Cow  |Siam-AM   |93.80  
|([Feuser et al., 2022](https://www.mdpi.com/2076-2615/12/20/2804))      |Horse  |Key point detection   |-       
|([Hu et al., 2023](https://www.sciencedirect.com/science/article/abs/pii/S0168169922008687))      |Pig  |PointNet++   |91.48      
|([Zheng et al., 2022](https://www.sciencedirect.com/science/article/abs/pii/S0168169922003064))     |Chicken  |YOLOv5   |92.36      
|[**Ours**]      |**Chicken**  |**YOLO-Claw**   |**<ins>97.1<ins>**    

* ### <div align="left">Performance under different lighting conditions</div>
![幻灯片7](https://github.com/PuristWu/YOLO-Claw/assets/90194261/2d486b9f-1416-4c80-a0c9-f13ceba05d0d)
* ### <div align="left">Work accomplished and to be done</div>
![幻灯片12](https://github.com/PuristWu/YOLO-Claw/assets/90194261/1c5f2fbe-e7d1-4303-b9bb-21b21d176aa3)
![幻灯片14](https://github.com/PuristWu/YOLO-Claw/assets/90194261/7c29c3fb-eba2-42e8-9035-1fa1748caa2a)
* ### <div align="left">Author info</div>
![幻灯片16](https://github.com/PuristWu/YOLO-Claw/assets/90194261/28b07afe-e506-4f9b-8733-e607aa0d90c8)

* ### <div align="left">Notes</div>
<div align="left">Since the software we developed is under application, the full source code of the peoposed YOLO-Claw will be released here after licensing.</div>
