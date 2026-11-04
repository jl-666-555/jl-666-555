<h3 align="center">软件工程本科生 | Java 后端开发 | 算法竞赛爱好者</h3>

<p align="center">
  🎓 广州华商学院 (2023.09 - 2027.06) | 💻 大四全职，随时到岗
</p >

---

### 🚀 个人项目 (Featured Projects)

#### 1. [AI Agent 驱动的个人知识管理与学习平台](https://github.com/jl-666-555/selfKnowledge-hub)
> 基于 Spring AI 的笔记 Agent：模型自主调用工具检索笔记与学习记录，再组织回答。
*   **Agent 核心**：6 个 `@Tool` 接口（笔记检索、分类筛选、学习记录读写等），模型按问题自主选择工具并多轮调用，完成检索问答与自动记录。
*   **记忆与流式**：记忆按 sessionId 滑动窗口隔离，聊天历史全量落库；SSE 流式返回走独立线程池，不占用 Tomcat 请求线程。
*   **安全与高可用**：userId 由 ToolContext 服务端注入防越权；Resilience4j 熔断降级，写操作 AOP 异步审计。
*   **技术栈**：`Java` `Spring Boot 3` `Spring AI` `MySQL` `Redis` `Resilience4j` `Vue 3`

#### 2. [校园选课与生活社区平台](https://github.com/jl-666-555/school-hub)
> 基于 Spring Boot 的高并发选课系统，解决秒杀与消息可靠性问题。
*   **核心特性**：Redis + Lua 脚本原子扣库存、RabbitMQ 异步削峰落库、乐观锁与唯一索引防重、缓存穿透/击穿/雪崩治理。
*   **技术栈**：`Java` `SpringBoot` `MySQL` `Redis` `RabbitMQ` `Vue`

---

### 🏆 获奖与竞赛经历 (Awards & Competitions)

| 时间 | 比赛名称 | 获奖情况 |
| :--- | :--- | :--- |
| 2026-05 | 团体程序设计天梯赛（国赛） | **三等奖** |
| 2026-05 | 码题杯（省赛） | 三等奖 |
| 2025-07 | 睿抗编程赛道（省赛） | 三等奖 |
| 2025-04 | 蓝桥杯（省赛） | 三等奖 |

*   **ICPC/CCPC 竞赛经历**：代表学校参加 ICPC/CCPC 区域赛。在训练与比赛过程中积累了扎实的算法设计、团队协作和临场解题经验。（注：未曾获得顶级奖项，但这段经历让我极度重视底层基础能力和抗压能力）。
*   **其他荣誉**：校级二等奖学金（2023-2024、2024-2025）、英语四级（CET-4）。

---

### 🛠️ 技术栈 (Tech Stack)

*   **后端**：Java, Spring Boot, Spring Security, MyBatis-Plus, JWT
*   **数据库与中间件**：MySQL, Redis, RabbitMQ
*   **工具与部署**：Git, Postman, JMeter, Docker (学习中)
*   **AI 辅助开发**：熟练使用 Claude, Copilot 进行代码提效与 Bug 排查
