# YOLO-Claw
#### Thank you for your interest in our research!" Important results and source code of "YOLO-Claw: Improved YOLOv5 based on TCA and AFPN for detecting chicken claws in commercial farms" will be posted here!
## <div align="center">Basic information about the manuscript</div>
#### "Dihua Wu; Yibin Ying; Mingchuan Zhou; Jinming Pan and Di Cui. YOLO-Claw: Improved YOLOv5 based on TCA and AFPN for detecting chicken claws in commercial farms"
## <div align="center">Important results</div>

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
|[Jiang et al.,2019]      |Cow  |FLYOLOv3   |90.83   
|[Wu et al., 2020]      |Cow  |YOLOv3   |93.73       
|[Kang et al., 2020]      |Cow  |RFB_Net_SSD   |87.0       
|[Zheng et al., 2023]      |Cow  |Siam-AM   |93.80   
|[Feuser et al., 2022]      |Horse  |Key point detection   |-       
|[Hu et al., 2023]      |Pig  |PointNet++   |91.48       
|[Zheng et al., 2022]     |Chicken  |YOLOv5   |92.36       
|[**Ours**]      |**Chicken**  |**YOLO-Claw**   |**97.1**    

* ### Performance under different lighting conditions
<p>
   <img width="850" src="https://github.com/PuristWu/YOLO-Claw/assets/90194261/30d0799f-db74-4861-a6a9-6d40249b29ea">
</p>
