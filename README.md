参考文章：https://zhuanlan.zhihu.com/p/636215898
 https://blog.csdn.net/m0_59164520/article/details/145322617

lora最新进展方向：
lora核心：低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练。

1.降低参数数量
	Qlora
2.

Qlora, 量化模型（压缩）
AdaLoRA
DoRA
**MoE-LoRA**
O-LoRA / FedLoRA

<img width="921" height="356" alt="屏幕截图 2026-01-02 131617" src="https://github.com/user-attachments/assets/6f35dfd0-8234-4d38-9ced-aacce6814bc2" />


现在LORA技术最新进展

<img width="973" height="372" alt="屏幕截图 2026-01-02 131849" src="https://github.com/user-attachments/assets/834273d4-0b57-428a-80dc-9cb3cc4e03ba" />



## LORA调节层次的问题

<img width="1119" height="569" alt="屏幕截图 2026-01-02 130309" src="https://github.com/user-attachments/assets/3b520797-bc28-4d0c-8c1c-d8f75d535932" />



这几种方法的区别
该方法的核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练。
