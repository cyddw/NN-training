## Q1：MPLs的输出层是什么结构？

输出层和隐藏层结构一样，只是输出层的维度是固定的，由任务目标决定，而隐藏层的维度是可调节的

## Q2：MPLs如何通过pytorch实现

## Q3：Pytorch中requires_grad的含义

requires_grad表达的含义是，这一参数是否保留（或者说持有，即在前向传播完成后，是否在显存中记录这一参数的梯度，而非立即释放）梯度，等待优化器执行optim.step()更新参数。

## Q4：Epoch、Iteration、Batchsize的含义

+ Batchsize：批大小。在深度学习中，一般采用SGD训练，即每次训练在训练集中取batchsize个样本训练

+ Iteration：1个iteration等于使用batchsize个样本训练一次

+ Epoch：1个epoch等于使用训练集中的全部样本训练一次

例如：

> <img width="476" alt="image" src="https://github.com/user-attachments/assets/f783ce8c-f16b-4063-9935-c52f4d93e210">



