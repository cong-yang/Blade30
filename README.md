# Blade30

Blade30 is a comprehensive dataset for multiple blade-related tasks, including blade stitching, segmentation, defect detection, classification and deduplication, contamination detection and classification, and more. Blade30 was collected during the real drone-based wind turbine inspection in various environments. It contains 1,302 real drone-captured images covering 30 full blades captured under various conditions (both on- and off-shore), accompanied by a rich set of annotations such as defects and contaminations, etc. Thus, Blade30 leads in both quality and quantity.

<img src="./demo_rst/blade30.png" height="256">

## Download
1. Baidu Disc: 
    - part1 (blade1-15): https://pan.baidu.com/s/17kv5Xadz1QcSrvoG58WtBw code：1234
    - part2 (blade16-30): https://pan.baidu.com/s/1hzcwdc6sBXOeja3nkfartg  code：1234
2. OneDrive: 
    - full dataset: https://1drv.ms/u/s!AoXJBmXKVWu5tmtUzCJULhrtYuIP?e=KYOtlo

## Citation

If you use these works in your research, please cite:

	@article{Yang2023Blade30,
		author = {Cong Yang and Xun Liu and Hua Zhou and Yan Ke and John See},
		title = {Towards accurate image stitching for drone-based wind turbine blade inspection},
		journal = {Renewable Energy},
            volume={203},
            pages={267-279},
            year={2023},
	}

## Dataset: Industral10
**Note**
1. Due to space limitation in github, here we only provide testing data and their ground truth. If you want full training data, please send us email: cong.yang@uni-siegen.de.
2. At present, it is only open to non-profit institutions such as schools and research institutes, and not to companies and enterprises. Any other use beyond that is prohibited. To ensure the continuous development of this project, we demand responsible use of the data you are about to acquire.
3. Without permission, it is not allowed to forward, publish or distribute this dataset or its subsets to any organization or individual in any ways or by any means.
4. Please cite our paper if Industral10 dataset is useful to your research.
5. We will not accept applications from generic email addresses (e.g. gmail.com, 163.com, etc.). Only applications from email addresses of non-profit institutions such as schools and research institutes are accepted.

**Data Structure**:

- obj1
   - small_distance: around 50cm camear-object distance with normal marker
      - img_0_99.jpg: original image
      - makloca_0_99.txt: marker location (four corners) within the image
      - tran_0_99.txt: rotation and translation
   - big _distance: around 100-200cm camera-object distance with nestmarker
      - img_0_99.jpg: original image
      - makloca_0_99.txt: marker location (four corners) within the image
      - tran_0_99.txt: rotation and translation

## Source Codes

