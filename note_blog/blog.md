# Notes for chinese blog
## Chapter-1.0 并行计算与计算机架构
## Chapter-1.1 异构计算与CUDA
1. CUDA是基于CPU和GPU的一种异构计算平台，通过CUDA NVCC进行编译，其中把CPU称为Host，GPU称为Device。相应地，NVCC会自动分离程序中CPU和GPU部分，其中CPU的部分依然由Host上的C编译器编译，GPU部分由CUDA NVCC编译。
2. 四种主要的NVIDIA计算平台（根据应用场景分类）：Tegra (embedding devices), Geforce (games), Quadro (design) and Tesla (computing)。
3. CUDA程序的五个步骤：1）分配GPU内存；2）拷贝内存到设备；3）调用CUDA内核函数来执行计算；4）把计算完成数据拷贝回主机端；5）内存销毁。
