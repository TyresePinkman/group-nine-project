# 检索式变更日志


# 检索式设计依据

**创建日期**：2026 年 3 月 21 日

## 研究问题
RISC-V CPU 架构与处理器设计的研究趋势与技术发展是什么？

本项目旨在利用文献计量方法分析与 RISC-V 处理器相关的学术文献，以识别研究热点、合作网络和新兴趋势。

---

## 概念分解
遵循文献计量检索设计中使用的对象-方法-背景框架：

- **对象**：RISC-V 处理器架构  
- **方法**：处理器架构设计与微架构  
- **背景**：计算机架构与嵌入式系统  
- **约束**：时间窗口 2020–2025 年

---

## 时间窗口
2020–2025 年

**理由**：RISC-V 近年来发展迅速，尤其在工业界和学术界的采用日益广泛。将时间窗口限定在最近几年，有助于捕捉当前的研究趋势。

---

## 文献类型
- Article（研究论文）  
- Review（综述）

**理由**：研究论文代表原创性成果，综述论文总结重要发展。

---

## 字段限定
- 标题  
- 摘要  
- 关键词

**理由**：标题检索提高查准率，摘要和关键词检索提高查全率。

---

## 同义词策略
为提高查全率，每个概念内的同义词使用 `OR` 运算符组合。

### 对象同义词
- RISC-V  
- RISC V  
- RISC-V processor  
- RISC-V CPU  
- RISC-V architecture

### 方法同义词
- processor design  
- cpu architecture  
- microarchitecture  
- processor architecture  
- instruction set architecture

### 背景同义词
- computer architecture  
- embedded system  
- system on chip  
- SoC  
- hardware design

---

## 布尔逻辑结构
检索式遵循 `(对象) AND (方法) AND (背景)` 结构。

**示例表达式**：("RISC-V" OR "RISC V" OR "RISC-V processor" OR "RISC-V CPU" OR "RISC-V architecture")
AND
("processor design" OR "cpu architecture" OR "microarchitecture" OR "instruction set architecture")
AND
("embedded system" OR "computer architecture" OR "system on chip" OR "SoC")


---

## 预期结果
该检索式预期检索到聚焦以下内容的文献：
- RISC-V CPU 架构设计  
- 处理器微架构  
- RISC-V 硬件实现  
- 在嵌入式与计算机系统中的应用

检索数据集将用于文献计量分析，包括：
- 关键词共现分析  
- 合作网络分析  
- 研究趋势探测



## 2026-03-22 检索式优化记录

为了扩大文献检索范围，对原有的 RISC-V 检索式进行了优化。

优化内容：
- 新增关键词：RV32、RV64、RISC-V ISA、accelerator
- 扩展处理器架构相关术语，例如 processor、cpu、core、microarchitecture 等

优化后的检索式能够覆盖更多与 RISC-V 处理器架构、指令集设计以及 SoC 系统相关的研究文献。

本次优化后，数据库检索结果数量显著增加，提高了文献计量分析的数据覆盖范围。