## Neural Network Acceleration Study
This is a repository of the study "neural network acceleration". The goal of this study is to understand the acceleration of nerual networks on various devices. The topic of acceleration includes `CPU`,`GPU`, `FPGA`, `ASIC` , `NPU` and `PIM`. Our materials are open to this github and youtube.

#### CPU/GPU and NPU
- Desinging optimized BLAS for CPU or GPU
- Optimal primitive selection on heterogeneous system architecture (HSA) device
- CUDA/OpenCL kernel design

#### ASIC and FPGA
- Low-power inference acceleration using HLS or RTL design
- High computing performance training accelerator

#### PIM (NDP)
- DIMM and HMC based neural acceleration system
- Non-HBM based design

## Paper List (17)
### Processor based Acceleration (9)
	CPU, GPU, and special system based acceleration (Parallel computing, Distribution computing)
	1. AccUDNN: A GPU Memory Efficient Accelerator for Training Ultra-deep Neural Networks, arxiv, 2019.
	2. Zion: Facebook Next-Generation Large-memory Unified Training Platform, HotChips, 2019.
	3. µLayer:Low Latency On-Device Inference Using Cooperative Single-Layer Acceleration and Processor-Friendly Quantization, EuroSys, 2019.
	4. Scalpel: Customizing DNN pruning to the underlying hardware parallelism, ISCA, 2017.
	5. MOSAIC: Heterogeneity-, Communication-, and Constraint-Aware Model Slicing and Execution for Accurate and Efficient Inference, PACT, 2019.
	6. Optimal DNN Primitive Selection with Partitioned Boolean quadratic Programming, ACM CGO, 2019.
	7. Neural Network Inference on Mobile SoCs, Arxiv 2019.
	8. Learning to infer: RL-based search for DNN primitive selection on Heterogeneous Embedded Systems, DATE, 2019.
	9. Performance analysis of CNN frameworks for GPUs, ISPASS, 2018.
  

### ASIC and FPGA (6)
	1. Cambricon: An instruction set architecture for neural networks, ISCA, 2016.
	2. In-Datacenter Performance Analysis of a Tensor Processing Unit, ISCA, 2017.
	3. Overcoming Data Transfer Bottlenecks in FPGA-based DNN Accelerators via Layer Conscious Memory Management, DAC, 2019.
	4. Optimizing FPGA-based Accelerator Design for Deep Convolutional Neural Networks, FPGA, 2015.
	5. FA3C: FPGA-Accelerated Deep Reinforcement Learning, ASPLOS, 2019.
	6. Cambricon-S: Addressing Irregularity in Sparse Neural Networks through A Cooperative Software/Hardware Approach, MICRO, 2018.
### PIM & NDP (2)
	1. Processing-in-Memory for Energy-efficient Neural Network Training: A Heterogeneous Approach, MICRO, 2018.
	2. TensorDIMM: A Practical Near-Memory Processing Architecture for Embeddings and Tensor Operations in Deep Learning, MICRO, 2019.

   
## Presentation with Video
### Week1: Introduction of Neural network acceleration (February 02, 2020)
**Optimal DNN Primitive Selection with Partitioned Boolean quadratic Programming**  

	Presentor: Constant Park (http://esoc.hanyang.ac.kr/people/sangsoo_park/index.html)  
	PPT: https://github.com/ConstantPark/Nerual-Network-Acceleration/blob/master/Optimal%20DNN%20Primitive%20Selection%20with%20Partitioned%20Boolean%20Quadratic%20Programming.pdf   
	Video:   

  

### Week2: HW accelerator (ASIC) and GPU acceleration  (February 09, 2020)
**Optimizing FPGA-based Accelerator Design for Deep Convolutional Neural Networks**  

	Presentor: 김태완 (rlaxodhksk@snu.ac.kr)  
	PPT: https://github.com/snulouis/Nerual-Network-Acceleration/blob/master/Optimal%20DNN%20Primitive%20Selection%20with%20Partitioned%20Boolean%20Quadratic%20Programming.pdf   
	Video:   

**Performance analysis of CNN frameworks for GPUs**  

	Presentor: Martin (dhhwang89@gmail.com)
	PPT:   
	Video:   


### Week3: HW accelerator (FPGA) and CPU/GPU acceleration (February 16, 2020)
**Cambricon: An instruction set architecture for neural networks**  

	Presentor: 김용우 (guruzoa@gmail.com)
	PPT:   
	Video:   
	
**Scalpel: Customizing DNN pruning to the underlying hardware parallelism**  

	Presentor: DownyK (dhhwang89@gmail.com)  
	PPT:   
	Video:   

### Week4: HW accelerator (ASIC) and CPU/GPU acceleration (February 23, 2020)
**MOSAIC: Heterogeneity-, Communication-, and Constraint-Aware Model Slicing ~ Efficient Inference**  
	
	Presentor: 이제민 (rlaxodhksk@snu.ac.kr)  
	PPT:   
	Video:   

**In-Datacenter Performance Analysis of a Tensor Processing Unit**    
	
	Presentor: Constant Park (sonicstage12@naver.com)
	PPT:   
	Video:   

### Week5: HW accelerator (FPGA) and CPU/GPU acceleration (March 01, 2020)
**Neural Network Inference on Mobile SoCs**   
	
	Presentor: 전지혜 (jyeah05@gmail.com)  
	PPT:   
	Video:   

**FA3C: FPGA-Accelerated Deep Reinforcement Learning**    
	
	Presentor: 김석중 (rlatjrwnd242@naver.com)  
	PPT:   
	Video:   

### Week6: CPU/GPU acceleration and NDP (Near-data Processing) (March 08, 2020)
**µLayer:Low Latency On-Device Inference Using Cooperative Single-Layer Acceleration and Processor-Friendly Quantization**   
	
	Presentor: Martin (dhhwang89@gmail.com)  
	PPT:   
	Video:   

**TensorDIMM: A Practical Near-Memory Processing Architecture for Embeddings and Tensor Operations in Deep Learning**    
	
	Presentor: Constant Park (sonicstage12@naver.com)
	PPT:   
	Video:   

### Week7: CPU/GPU acceleration and NDP (Near-data Processing) (March 15, 2020)
**Zion: Facebook Next-Generation Large-memory Unified Training Platform**   
	
	Presentor: DownyK (TeamBehindDowny@gmail.com)
	PPT:   
	Video:   

**Processing-in-Memory for Energy-efficient Neural Network Training: A Heterogeneous Approach**    
	
	Presentor: 김태완 (rlaxodhksk@snu.ac.kr)  
	PPT:   
	Video:   

### Week8: HW accelerator (FPGA) and CPU/GPU acceleration (March 22, 2020)
**Overcoming Data Transfer Bottlenecks in FPGA-based DNN Accelerators via Layer Conscious Memory Management**   
	
	Presentor: 이제민 (leejaymin@cnu.ac.kr)
	PPT:   
	Video:   

**AccUDNN: A GPU Memory Efficient Accelerator for Training Ultra-deep Neural Networksh**    
	
	Presentor: 김용우 (guruzoa@gmail.com)  
	PPT:   
	Video:   

### Week9: HW accelerator (ASIC) and CPU/GPU acceleration (March 29, 2020)
**Learning to infer: RL-based search for DNN primitive selection on Heterogeneous Embedded Systems**   
	
	Presentor: 전지혜 (jyeah05@gmail.com)
	PPT:   
	Video:   

**Cambricon-S: Addressing Irregularity in Sparse Neural Networks through A Cooperative Software/Hardware Approachh**    
	
	Presentor: 김석중 (rlatjrwnd242@naver.com)  
	PPT:   
	Video:   
	
## Contributors
**Main Contributor**: Constant Park (sonicstage12@naver.com)  
**Presenter**: Constanr Park (sonicstage12@naver.com), 이제민 (leejaymin@cnu.ac.kr), 김태완 (rlaxodhksk@snu.ac.kr), DownyK (TeamBehindDowny@gmail.com), 전지혜 (jyeah05@gmail.com), Martin (dhhwang89@gmail.com), 김용우 (guruzoa@gmail.com), 김석중 (rlatjrwnd242@naver.com)

