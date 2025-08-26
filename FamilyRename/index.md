1. Application Short Description (200 characters)
Professional Revit add-in for batch renaming families and family types with advanced filtering, preview, and multi-version support (2019-2026).

2. Application Description (4000 characters)
ZJY Family Rename is a comprehensive and professional Revit add-in designed to streamline the process of renaming families and family types in your Revit projects. This powerful tool addresses one of the most common yet time-consuming tasks in BIM workflows - maintaining consistent and organized naming conventions across your project families.

Key Features:

Multi-Version Compatibility: Supports Revit 2019 through 2026, ensuring compatibility across different project environments
Batch Operations: Rename multiple families and family types simultaneously, saving hours of manual work
Advanced Filtering: Smart search and filtering capabilities to quickly locate specific families by category, name, or usage status
Visual Management: Intuitive interface displaying family hierarchies, types, and usage statistics within your project
Safety Features: Built-in protection against renaming system families, preventing potential model corruption
Preview & Validation: Preview changes before applying them, with comprehensive name format validation and conflict detection
Find & Replace: Powerful text replacement tools with prefix/suffix addition capabilities
Usage Tracking: View which family types are actively used in your project before making changes
Modern Interface: Clean, user-friendly interface with theme adaptation and responsive design
Professional Benefits:
This tool significantly improves project organization and collaboration by ensuring consistent naming standards. It's particularly valuable for large projects with extensive family libraries, renovation projects requiring family reorganization, and teams working with standardized naming conventions. The batch processing capabilities can reduce what would typically take hours of manual work into minutes of automated operations.

Technical Excellence:
Built with robust architecture featuring comprehensive error handling, transaction-based operations with rollback capabilities, and optimized performance for large datasets. The plugin integrates seamlessly into Revit's ribbon interface and follows Autodesk's development best practices.

3. General Usage Instructions
Workflow Integration:

Access: Launch the tool from the "ZJY Revit Kit" tab in Revit's ribbon interface
Selection: Select families directly in the Project Browser or within the 3D model view
Configuration: Use the intuitive interface to set up renaming rules - choose from prefix/suffix addition, find & replace operations, or manual renaming
Preview: Review all proposed changes in the preview pane before applying them
Apply: Execute the renaming operations with full transaction support and automatic rollback on errors
Verification: Confirm changes and review the operation summary
The tool integrates naturally into standard BIM workflows, particularly during project setup phases, family library organization, and quality control processes. It works seamlessly with existing Revit project structures without requiring any special preparation or file modifications.

4. Installation/Uninstallation (1000 characters)
Installation:
The plugin uses Autodesk's standard Bundle deployment method. After download, the installer automatically places files in C:\ProgramData\Autodesk\ApplicationPlugins\ZJY Family Rename.bundle\. The plugin will appear in Revit's ribbon upon next startup. No manual configuration required.

System Requirements:

Windows 64-bit
Revit 2019-2026 (any version)
.NET Framework 4.7.2 or higher
Administrative privileges for installation
Uninstallation:
Use Windows "Add or Remove Programs" or manually delete the bundle folder. The plugin cleanly removes without affecting Revit or project files. All plugin-related registry entries are automatically cleaned up during uninstallation.

Multi-Version Support:
Single installation supports all compatible Revit versions simultaneously. Version-specific components are automatically loaded based on the running Revit version.

5. Support Information (1000 characters)
Technical Support:

Primary Support: GitHub Issues at https://github.com/zjy/family-rename
Email Support: support@zjy.com for direct technical assistance
Response Time: Typically within 24-48 hours for technical issues
Documentation: Comprehensive help documentation included with installation
Community: Active user community for tips and best practices
Support Hours: Monday-Friday, 9 AM - 6 PM (UTC+8)

What We Support:

Installation and setup assistance
Feature usage guidance
Bug reports and troubleshooting
Compatibility issues
Performance optimization advice
Before Contacting Support:
Please include your Revit version, Windows version, error messages (if any), and steps to reproduce any issues. Screenshots are helpful for UI-related questions.

6. Additional Information (2000 characters)
Technical Specifications:

Architecture: Modular design with separate core logic and version-specific implementations
Performance: Optimized for large datasets with progress tracking for batch operations
Safety: Transaction-based operations with automatic rollback on failures
Compatibility: Tested across all supported Revit versions with consistent behavior
Advanced Features:

Smart Validation: Prevents duplicate names and invalid characters
Usage Analysis: Shows family type usage statistics before renaming
Batch Processing: Handles hundreds of families efficiently
Error Recovery: Comprehensive error handling with detailed reporting
Development Standards:
Built following Autodesk's official development guidelines and best practices. Regular updates ensure compatibility with new Revit releases and incorporate user feedback.

File Resources:

Help Documentation: Integrated Help System
User Manual: Available within the plugin interface
Video Tutorials: Available on project repository
Compliance:

Follows Autodesk App Store guidelines
No external dependencies beyond .NET Framework
Secure code with no network communications
Respects user privacy with no data collection
Future Updates:
Regular maintenance updates for new Revit versions and feature enhancements based on user feedback.

7. Known Issues (1000 characters)
Current Limitations:

System Families: Cannot rename system families (by design for model safety)
In-Place Families: Limited support for in-place family renaming
Large Projects: Performance may be slower with projects containing 1000+ families
Workarounds:

For large projects, use filtering to process families in smaller batches
Close unnecessary views and worksets to improve performance
Ensure adequate system memory (8GB+ recommended for large projects)
Compatibility Notes:

Some third-party plugins may conflict with ribbon interface
Worksharing environments require proper permissions for family modifications
Network drives may cause slower performance during batch operations
Planned Improvements:

Enhanced performance for large datasets
Additional filtering options
Improved worksharing support
Not Issues:

Warning messages about system families are intentional safety features
Undo operations work through Revit's standard undo system, not plugin-specific undo
These descriptions provide comprehensive information about your Family Rename plugin while staying within the character limits specified by the Autodesk App Store requirements.
1. 申请简短说明（200 个字符）
Professional Revit 附加模块，用于批量重命名族和族类型，具有高级过滤、预览和多版本支持（2019-2026）。

2. 应用说明（4000 个字符）
ZJY 族重命名是一个全面且专业的 Revit 插件，旨在简化在 Revit 项目中重命名族和族类型的过程。这个强大的工具解决了 BIM 工作流程中最常见但最耗时的任务之一 - 在项目系列中保持一致且有组织的命名约定。

主要特征：

多版本兼容性：支持Revit 2019至2026，确保不同项目环境的兼容性
批量作：同时重命名多个族和族类型，节省手动工作时间
高级过滤：智能搜索和过滤功能，可按类别、名称或使用状态快速定位特定系列
可视化管理：直观的界面显示项目中的族层次结构、类型和使用情况统计信息
安全特性：内置防止重命名系统系列的保护，防止潜在的模型损坏
预览和验证：在应用更改之前预览更改，具有全面的名称格式验证和冲突检测功能
查找和替换：具有前缀/后缀添加功能的强大文本替换工具
使用情况跟踪：在进行更改之前查看项目中正在使用哪些族类型
现代界面：干净、用户友好的界面，具有主题适配和响应式设计
专业福利：
该工具通过确保一致的命名标准来显着改善项目组织和协作。它对于具有大量家庭图书馆的大型项目、需要家庭重组的翻新项目以及使用标准化命名约定的团队特别有价值。批处理功能可以将通常需要数小时的手动工作减少为几分钟的自动化作。

卓越技术：
采用强大的架构构建，具有全面的错误处理、具有回滚功能的基于事务的作以及针对大型数据集的优化性能。该插件无缝集成到 Revit 的功能区界面中，并遵循 Autodesk 的开发最佳实践。

3. 一般使用说明
工作流程集成：

访问：从 Revit 功能区界面中的“ZJY Revit Kit”选项卡启动该工具
选择：直接在项目浏览器或 3D 模型视图中选择族
配置：使用直观的界面设置重命名规则 - 从前缀/后缀添加、查找和替换作或手动重命名中进行选择
预览：在应用之前，在预览窗格中查看所有建议的更改
应用：执行重命名作，支持完整的事务和错误自动回滚
验证：确认更改并查看作摘要
该工具自然地集成到标准 BIM 工作流程中，特别是在项目设置阶段、族库组织和质量控制流程中。它与现有的 Revit 项目结构无缝协作，无需任何特殊准备或文件修改。

4. 安装/卸载（1000 个字符）
安装：
该插件使用 Autodesk 的标准 Bundle 部署方法。下载后，安装程序会自动将文件放置在 C：\ProgramData\Autodesk\ApplicationPlugins\ZJY Family Rename.bundle\ 中。该插件将在下次启动时出现在 Revit 的功能区中。无需手动配置。

系统要求：

Windows 64 位
Revit 2019-2026（任何版本）
.NET Framework 4.7.2 或更高版本
安装的管理权限
卸载：
使用 Windows“添加或删除程序”或手动删除捆绑文件夹。该插件会干净地删除，而不会影响 Revit 或项目文件。卸载期间，所有与插件相关的注册表项都会自动清理。

多版本支持：
单次安装同时支持所有兼容的 Revit 版本。特定于版本的组件会根据正在运行的 Revit 版本自动加载。

5. 支持信息（1000 个字符）
技术支持：

主要支持：https://github.com/zjy/family-rename 的 GitHub 问题
电子邮件支持：support@zjy.com 直接技术援助
响应时间：技术问题通常在 24-48 小时内
文档：安装中包含的综合帮助文档
社区：活跃的用户社区，提供提示和最佳实践
支持时间：周一至周五，上午 9 点至下午 6 点（UTC+8）

我们支持什么：

安装和设置协助
功能使用指南
错误报告和故障排除
兼容性问题
性能优化建议
在联系支持人员之前：
请包括您的 Revit 版本、Windows 版本、错误消息（如果有）以及重现任何问题的步骤。屏幕截图有助于解决与 UI 相关的问题。

6. 附加信息（2000 个字符）
技术规格：

架构：模块化设计，具有独立的核心逻辑和特定于版本的实现
性能：针对大型数据集进行了优化，并跟踪了批量作的进度
安全性：基于事务的作，故障时自动回滚
兼容性：在所有受支持的 Revit 版本中进行了测试，具有一致的行为
高级功能：

智能验证：防止重复名称和无效字符
使用情况分析：在重命名之前显示族类型使用情况统计信息
批处理：高效处理数百个家庭
错误恢复：全面的错误处理和详细的报告
开发标准：
按照 Autodesk 的官方开发指南和最佳实践构建。定期更新可确保与新 Revit 版本的兼容性并纳入用户反馈。

文件资源：

帮助文档：集成帮助系统
用户手册：在插件界面中可用
视频教程：可在项目存储库中找到
合规：

遵循 Autodesk App Store 指南
没有 .NET Framework 以外的外部依赖项
无需网络通信即可保护代码
尊重用户隐私，不收集数据
未来更新：
根据用户反馈对新 Revit 版本进行定期维护更新和功能增强。

7. 已知问题（1000 个字符）
当前限制：

系统族：无法重命名系统族（出于模型安全设计）
就地系列：对就地系列重命名的有限支持
大型项目：包含 1000+ 个系列的项目的性能可能会变慢
解决方法：

对于大型项目，使用筛选处理小批量的族
关闭不必要的视图和工作集以提高性能
确保足够的系统内存（大型项目建议 8GB+）
兼容性说明：

某些第三方插件可能与功能区界面冲突
工作共享环境需要适当的族修改权限
网络驱动器可能会导致批处理作期间性能下降
计划改进：

增强大型数据集的性能
其他过滤选项
改进的工作共享支持
不是问题：

有关系统族的警告消息是有意的安全功能
撤消作通过 Revit 的标准撤消系统进行，而不是特定于插件的撤消
这些描述提供了有关“族重命名”插件的全面信息，同时保持在 Autodesk App Store 要求指定的字符限制范围内。
