# CloudProject

In the realm of cloud computing, service providers
traditionally allocate excess resources to meet Service Level Objectives
(SLOs), often opting for lower CPU utilization targets to
uphold service quality amid fluctuating workloads. This practice,
though, can lead to resource inefficiencies and increased power
consumption in large-scale deployments. This project presents an
innovative approach, DeepScaling, designed to minimize resource
costs in dynamic, large-scale microservice environments while
ensuring SLO requirements are met. DeepScaling introduces
three key components: a Spatio-temporal Graph Neural Network
for workload forecasting, a Deep Neural Network for estimating
CPU utilization considering various cloud environment factors,
and an improved Deep Q Network (DQN) for generating adaptive
autoscaling policies. These policies dynamically adjust the target
CPU utilization to a stable level, ensuring SLO compliance
with minimal resource utilization. The project uses Alibaba Google Trace, 2022
for their evaluation

Index Terms—Deep Scaling, Workload Prediction, CPU Utilization, STGNN (Spatio Temporal Graph Neural Network, DNN (Deep Probabilistic Neural Network)
