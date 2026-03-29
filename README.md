# Natalia_Project

Neural Async Task Allocation & Logic Integrated Architecture
(神经网络异步任务分配与逻辑集成架构)
Natalia：娜塔莉娅

本项目采用“逻辑底座层+动态专家矩阵层+评估分发层+外挂记忆与知识模块”的四层解耦架构
专为在有限显存（如8GB）下运行而设计，具备无限扩展的领域专家能力、长期记忆与持续学习机制，以及卓越的逻辑推理性能。

架构概览：

<img width="1162" height="828" alt="8ea1d66de82f71badf352980889b3bee" src="https://github.com/user-attachments/assets/50adf112-dbaa-4b55-873f-0bcaffdd9368" />



技术栈
底模：ai21labs/Jamba-2-3B（Hugging Face）
训练框架：PyTorch + PEFT + bitsandbytes + TRL
推理优化：llama.cpp / LM Studio + Quamba2 + TurboQuant / VQKV
RAG：LightRAG / GraphRAG
硬件适配：RTX 3070 Ti Laptop 8GB（已验证）

许可证：GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 19 November 2007
维护者：Misaka477
联系方式：rapidsound@163.com
