# Cursor Rules

> 专为后端 Spring Boot 开发设计的 Cursor 规则集合

## 📋 项目概述

本项目提供了一套完整的 Cursor 开发规则，专门针对 Spring Boot 后端开发场景。通过规范化的开发标准，提升代码质量、开发效率和团队协作。

## 🛠️ 技术栈

- **基础框架**: Spring Boot 3.x
- **Java 版本**: JDK 17
- **构建工具**: Maven
- **数据库**: MySQL + Redis
- **ORM 框架**: MyBatis-Plus
- **API 文档**: Knife4j (Swagger)
- **工具库**: Lombok, Hutool, fastjson2

## 📁 项目结构

```
cursor-rules/
├── README.md              # 项目说明文档
├── core.mdc               # 核心开发规范
├── document.mdc           # 文档编写规范
├── git.mdc                # Git 版本控制规范
├── java-17.mdc            # Java 17 语言规范
├── project-structure.mdc  # 项目结构规范
├── springboot.mdc         # Spring Boot 3 企业级最佳实践规范
└── tech-stack.mdc         # 技术栈规范
```


## 🚀 快速开始

### 环境要求

- JDK 17+
- Maven 3.6+
- IDE: IntelliJ IDEA / VS Code with Cursor

### 使用说明

1. **克隆项目**
   ```bash
   git clone https://github.com/WorkWork7mi/cursor-rules.git
   cd cursor-rules
   ```

2. **按照自己需要将其复制到Cursor配置文件中**
   - 在 Cursor 中打开规则文件夹.cursor\rules
   - 将需要的规则文件复制粘贴到.cursor\rules中

### 获取项目

```bash
git clone https://github.com/WorkWork7mi/cursor-rules.git
cd cursor-rules
```

## 📚 规则文档说明

### 核心开发原则 (`core.mdc`)
- 可测试性、代码简洁、命名规范
- SOLID 原则、异常处理、版本控制
- 架构设计、性能要求、用户体验

### Git 版本控制 (`git.mdc`)
- 提交规范：feat、fix、docs、style 等
- 分支管理：main、develop、feature、bugfix
- 代码审查和版本标签规范

### 项目结构 (`project-structure.mdc`)
- 分层组织：controller、service、repository
- 包命名原则和文件命名规范
- 模块划分和资源文件分类

### Spring Boot 最佳实践 (`springboot.mdc`)
- Spring Boot 3 企业级开发规范
- 配置管理、安全、监控等最佳实践
- 微服务架构设计原则

### 技术栈规范 (`tech-stack.mdc`)
- 基础框架和必备组件
- 推荐及可选技术栈
- 依赖管理和版本控制

### 文档编写 (`document.mdc`)
- Markdown 格式规范
- API 文档和技术文档标准
- 文档维护和版本控制

## 🤝 贡献指南

1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'feat: add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

如有问题或建议，请通过以下方式联系：

- 提交 Issue: [GitHub Issues](https://github.com/WorkWork7mi/cursor-rules/issues)
- 发送邮件至 workday7mi@outlook.com
- 项目主页: [https://github.com/WorkWork7mi/cursor-rules](https://github.com/WorkWork7mi/cursor-rules)

---

**注意**: 本规则集合持续更新中，建议定期同步最新版本以获得最佳开发体验。

## 致谢

本项目部分规则文件参考并整理自 [flyeric0212/cursor-rules](https://github.com/flyeric0212/cursor-rules) 开源仓库，特此致谢！
