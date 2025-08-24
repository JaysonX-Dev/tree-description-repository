
### 🎯 Project Introduction
**Tree Description Repository**  
Provides rich open source project mapping libraries for Tree Annotations plugin, helping developers quickly understand the structure and naming conventions of various open source projects.

### ✨ Mapping Library Content
- **Spring Framework**: Spring Boot, Spring Cloud, Spring Security, etc.
- **MyBatis**: MyBatis Core, MyBatis Spring, MyBatis Generator
- **More Frameworks**: Continuously adding...

### 📁 Mapping Library Structure
Each mapping library contains the following information:
```json
{
  "name": "Spring Boot Common Mappings",
  "version": "1.0.0",
  "description": "Common package names and file mappings for Spring Boot projects",
  "author": "Open Source Community",
  "mappings": {
    "packages": {
      "dubbo-example/src/main/java/com/example/consumer/controller": "Controller Layer",
      "dubbo-example/src/main/java/com/example/consumer/service": "Business Logic Layer",
      "dubbo-example/src/main/java/com/example/consumer/repository": "Data Access Layer"
    },
    "files": {
      "dubbo-example/src/main/java/com/example/consumer/Application.java": "Main Startup Class",
      "dubbo-example/pom.xml": "Maven Configuration File"
    },
    "packageMatch": {
      "com.example.controller": "Controller Layer",
      "com.example.service": "Business Logic Layer",
      "com.example.repository": "Data Access Layer"
    },
    "fileMatch": {
      "Application.java": "Main Startup Class",
      "pom.xml": "Maven Configuration File"
    }
  }
}
```

###  Mapping Rules
- **Package Mapping**: Exact package path matching
- **File Mapping**: Exact filename matching
- **Package Match Pattern**: Support wildcard package name matching
- **File Match Pattern**: Support wildcard filename matching

### 🤝 Contributing Mapping Libraries
We welcome community contributions for more framework mapping libraries!

#### Contribution Steps
1. **Fork this repository**
2. **Create mapping library file**:
   - Create `.json` file in the corresponding framework directory
   - Follow standard mapping format
   - Add detailed description information

3. **Submit Pull Request**:
   - Describe the purpose and content of the mapping library
   - Ensure correct JSON format

#### Mapping Library Naming Conventions
- Use official framework names
- Add version number identifiers (e.g., `spring-boot-2.x.json`)
- Use hyphens to separate words

### 🎯 Quality Requirements
- **Accuracy**: Mapping content accurately reflects the actual purpose of the framework
- **Completeness**: Cover main components and common naming of the framework
- **Standardization**: Follow JSON format specifications
- **Readability**: Clear and understandable description information

---

### 🎯 项目简介
**Tree Description Repository - 开源映射库**  
为 Tree Annotations 插件提供丰富的开源项目映射库，帮助开发者快速理解各种开源项目的结构和命名规范。

### ✨ 映射库内容
- **Spring Framework**: Spring Boot、Spring Cloud、Spring Security等
- **MyBatis**: MyBatis Core、MyBatis Spring、MyBatis Generator
- **更多框架**: 持续添加中...

### 📁 映射库结构
每个映射库包含以下信息：
```json
{
  "name": "Spring Boot 常用映射",
  "version": "1.0.0",
  "description": "Spring Boot 项目常用包名和文件映射",
  "author": "开源社区",
  "mappings": {
    "packages": {
      "dubbo-example/src/main/java/com/example/consumer/controller": "控制器层",
      "dubbo-example/src/main/java/com/example/consumer/service": "业务逻辑层",
      "dubbo-example/src/main/java/com/example/consumer/repository": "数据访问层"
    },
    "files": {
      "dubbo-example/src/main/java/com/example/consumer/Application.java": "主启动类",
      "dubbo-example/pom.xml": "Maven 配置文件"
    },
    "packageMatch": {
      "com.example.controller": "控制器层",
      "com.example.service": "业务逻辑层",
      "com.example.repository": "数据访问层"
    },
    "fileMatch": {
      "Application.java": "主启动类",
      "pom.xml": "Maven 配置文件"
    }
  }
}
```

###  映射规则说明
- **包映射**: 精确匹配包路径
- **文件映射**: 精确匹配文件名
- **包匹配模式**: 支持通配符匹配包名
- **文件匹配模式**: 支持通配符匹配文件名

###  贡献映射库
我们欢迎社区贡献更多框架的映射库！

#### 贡献步骤
1. **Fork 本仓库**
2. **创建映射库文件**:
   - 在对应框架目录下创建 `.json` 文件
   - 遵循标准映射格式
   - 添加详细的描述信息

3. **提交 Pull Request**:
   - 描述映射库的用途和内容
   - 确保JSON格式正确

#### 映射库命名规范
- 使用框架的官方名称
- 添加版本号标识（如：`spring-boot-2.x.json`）
- 使用连字符分隔单词

###  质量要求
- **准确性**: 映射内容准确反映框架的实际用途
- **完整性**: 覆盖框架的主要组件和常用命名
- **规范性**: 遵循JSON格式规范
- **可读性**: 描述信息清晰易懂

