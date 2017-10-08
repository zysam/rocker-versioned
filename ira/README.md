## koala_dashboard 项目，docker 打包部署

P.S. 提前打包好一个 base 镜像，如何 R 的依赖有变更，则更新 base.
prod 镜像基于 base 镜像，无需安装 R packages, 可快速升级。
