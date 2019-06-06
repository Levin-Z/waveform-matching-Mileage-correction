# waveform-matching
Waveform Matching in Time Domain for Dynamic Detection Data of High-Speed Railway

高速铁路的动态不平顺影响着乘客的舒适性乃至线路的行车安全，因此各铁路局安排轨道检查车（和谐号动车组）进行轨道动态不平顺的检测（0.25m一个测点），根据计划，一条高铁线路（以京沪高铁为例）每月上中下旬往返运行三次，单次单程产生的数据量为**<u>5272000</u>**条，且每次的检测数据都会因为轨道检查车的影响产生【里程误差】，时域上表现为波形错位，此误差非<u>**常量**</u>也非随时间累计的<u>**线性函数**</u>，因此对于每次的不平顺数据的预处理工作变得尤为重要。

本项目分为**波形匹配**和**伤损检测**两大部分，在这一repository详述波形匹配过程。

