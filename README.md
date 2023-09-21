# YOLO-Claw
#### Thank you for your interest in our research!" Important results and source code of "YOLO-Claw: Improved YOLOv5 based on TCA and AFPN for detecting chicken claws in commercial farms" will be posted here!
<div align="center">
   
   <img src="https://github.com/PuristWu/YOLO-Claw/blob/main/img/YOLO-Claw.gif"><br>
Note:Due to file size limitations, the longer video demos can be viewed on the following platforms:

## <div align="center">Basic information about the manuscript</div>
#### "Dihua Wu; Yibin Ying; Mingchuan Zhou; Jinming Pan and Di Cui. YOLO-Claw: Improved YOLOv5 based on TCA and AFPN for detecting chicken claws in commercial farms"
## <div align="center">Important results</font></div>

* ### Performance of different object detection algorithms for chicken claw detection
|Algorithms |Precision<br>(%) |Recall<br>(%) |mAP<br>(%) |Speed<br>(ms/frame) |Model Size<br>(MB) |Calculations<br>(GFLOPs) |
|---                    |---  |---    |---    |---    |---    |---    
|[YOLOv5]      |95.2  |91.7   |96.6   |7.1 |14.1|15.8
|[YOLOv6]      |93.8  |75.3   |93.9   |8.5     |36.2    |44.1    
|[YOLOv7]      |94.0  |91.1   |93.5   |9.2    |71.2    |103.2    
|[YOLOv8]     |95.0  |92.3   |96.3   |9.7    |21.4   |28.4    
|[**YOLO-Claw(Ours)**]      |**95.3**  |**93.6**   |**97.1**   |**7.6**    |**12.1**   |**4.8**   

* ### Comparison of the proposed algorithm with the state-of-the-art research
|Authors |Object |Method |mAP<br>(%) |
|---                    |---  |---    |---        
|([Jiang et al.,2019](https://www.sciencedirect.com/science/article/abs/pii/S0168169919309263))      |Cow  |FLYOLOv3   |90.83   
|([Wu et al., 2020](https://www.sciencedirect.com/science/article/abs/pii/S1537511019309006))      |Cow  |YOLOv3   |93.73       
|([Kang et al., 2020](https://www.sciencedirect.com/science/article/pii/S002203022030713X))      |Cow  |RFB_Net_SSD   |87.0       
|([Zheng et al., 2023](https://www.sciencedirect.com/science/article/abs/pii/S0168169923000066))      |Cow  |Siam-AM   |93.80   
|([Feuser et al., 2022](https://www.mdpi.com/2076-2615/12/20/2804))      |Horse  |Key point detection   |-       
|([Hu et al., 2023](https://www.sciencedirect.com/science/article/abs/pii/S0168169922008687))      |Pig  |PointNet++   |91.48       
|([Zheng et al., 2022](https://www.sciencedirect.com/science/article/abs/pii/S0168169922003064))     |Chicken  |YOLOv5   |92.36       
|[**Ours**]      |**Chicken**  |**YOLO-Claw**   |**97.1**    

* ### Performance under different lighting conditions
<p>
   <img width="850" src="https://github.com/PuristWu/YOLO-Claw/assets/90194261/30d0799f-db74-4861-a6a9-6d40249b29ea">
</p>

- # Notes
Since the software we developed is under application, the code of the source code of the peoposed YOLO-Claw will be released here after licensing.
