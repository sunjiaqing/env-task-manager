# env-task-manager

- 因为刚学go 写个项目练个手
- 主要功能简化开发环境的搭建流程
- 通过json配置来实现task
- 方便搭建开发环境
- 可能会结合cui来在做开发,先完成基础功能
- 前期应该不会考虑代码丑不丑,先完成功能点,会随着go的深入,为该项目作出优化

## 大致开发环境的搭建流程

1. 下载zip
2. 解压zip
3. 配置系统环境变量
4. 配置xml或其他类型文件
5. copy文件到指定目录
6. 生成改动记录
7. 根据改动记录无损还原系统

>  过程中可配置询问,支持输入

## 主要要完成的功能点

1. 支持项目自带的本地变量替换
2. 完成上述流程中的task
3. 支持多版本的搭建
