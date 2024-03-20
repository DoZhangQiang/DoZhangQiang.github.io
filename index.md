An undergraduate student in the School of Computer Science and Technology at SWPU(SouthWest Petroleum University), Class of 2021. I am also a Student Member of CCF.

I am a member of the Supercomputing Team at SWPU, focusing on high-performance computing competitions both domestically and internationally. These competitions include ASC (ASC Student Supercomputer Challenge), CPC (China Parallel application Challenge on domestic CPU), PAC (Parallel Application Challenge), IPCC(International Parallel Computing Challenge) and PRA (Priority Research Application). 

I hope to continue working on porting and researching HPC applications during the master's period.

You can get an two-page version of my CV writed in Chinese [here](docs/CV.pdf).

## News

- 2024.02 [ASC24 Final](http://www.asc-events.org/StudentChallenge/Finals.html), we are coming!

- 2024.01 Authorized an [invention patent](docs/patent.pdf) (First inventor): An image processing algorithm optimized for parallel computing on the **New Sunway**.
- 2023.08 We won second prize in [CPC 2023](https://mp.weixin.qq.com/s/B6SLQ9-q2xjWaIEnGokmRw), ranked 6th.

## Personal Details

- 📞 15756210138
- 📧 zhangqiang020320@163.com

## Educations

- 2021.09 - 2025.06: Computer Science and Technology, SouthWest Petroleum University.
  - GPA: 4.2/5.0

## Publications and Patents

- Zhuozhao Xia, **Qiang Zhang**, Xinhang Zhou, and Hongjie Zhao. 2023. Parallel Optimization of SLIC Algorithm for New-Generation Sunway Processors. In Proceedings of the 2023 7th International Conference on High Performance Compilation, Computing and Communications (HP3C '23). 85–91. (EI)
- **Qiang Zhang**, Hongzhang Liao, Xitao Li, Guangsen Zhou, Huaxin Song, and Jia Zhang. An image processing method and system based on histogram equalization optimization algorithm.(Patent number : ZL 2023 1 0462081.6)

## Honors and Awards

- 2023.12 [Second prize](https://cas-pra.sugon.com/webnews/detail/243) in the PRA region at *Convolution ptimization*, 2023.
- 2023.12 [Third prize](https://cas-pra.sugon.com/webnews/detail/243) in the PRA region at *Optimization of graph convolutional*, 2023.
- 2023.11 FeiXiang Award(the Highest Honor Award of SWPU) - [Best Team Nomination](https://www.swpu.edu.cn/xsfx/info/1024/1477.htm), 2023.
- 2023.12 Merit Student of SWPU, 2022 - 2023.
- 2023.08 [Second prize](https://mp.weixin.qq.com/s/B6SLQ9-q2xjWaIEnGokmRw) in the CPC, 2023.
- 2023.08 [Second prize(3rd)](https://mp.weixin.qq.com/s/bW2WEuDNiSj1WYJV2tiRTg) in the HPC-PL, 2023.
- 2023.06 Level A Certificate of Sichuan Province, 2023.
- 2023.02 Merit Student of SWPU, 2021 - 2022.
- 2022.12 Third prize in the IPCC(Preliminary), 2022.
- 2022.12 [Third prize](https://mp.weixin.qq.com/s/XiXrfQVJtT-zG2f7bMgkZg) in the CPC, 2022.
- 2022.11 Third prize of Sichuan Province in the CUMCM, 2022.

## Experiences

- 2022.09 - 2023.09, Student Captain of the Supercomputing Team.

  - Responsible for the HPC training within the team.

- 2023.07 - 2023.08, Co-organizer of the [HPC-PL](https://mp.weixin.qq.com/s/bW2WEuDNiSj1WYJV2tiRTg).

## Selected Projects

- *swPCG: Multi-angle computation and memory access optimization for PCG algorithm on the New Generation Sunway Supercompute*	
  - This is the project for the **CPC 2023**. Base on the serial PCG algorithm that the organizing committee provided. I was responsible for the writing of slave core code. Various methods such as LDM space access adjustment and double buffering were adopted for acceleration. Additionally, the sub-algorithm LDU2CSR was refactored to eliminate its circular dependencies, thus making it more suitable for parallel computing. Achieve an average speedup of **22 times** across 600 cases.
  
- *swBlender: Parallelization of ray tracing and denoising in the Cycles renderer on the New Generation Sunway Supercompute*  
  - This is the project for the **CPC 2022**. I was responsible for designing load balancing strategies for interval distribution in ray tracing algorithms. Additionally, I optimized communication between different core groups on the same chip using cross-sections. Furthermore, I wrote and optimized slave core code for the denoising algorithm section. Achieve an average speedup of **34 times** across the evaluation case.

- *swROMS: Parallel three computation modes of ROMS on the New Generation Sunway Supercompute*
  - This is the project for the **CPC 2023**. I was responsible for analyzing the dependency patterns of more than 20 sub-algorithms and manually parallelizing over 10 of them. Additionally, I utilized cross-segment copy optimization for inter-core MPI communication. Achieved an average speedup of **3.7 times** across three evaluation cases.
