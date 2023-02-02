# cronjob-controller
A cronjob controller init by kubebuilder

# 设计目标

在 K8s 中创建一个 CRD `CronJob` 支持以下能力：

- 配置 cron format，然后周期性的创建 K8s `Job`