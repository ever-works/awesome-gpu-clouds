# Awesome GPU Clouds

A curated directory of GPU clouds, GPU marketplaces and serverless GPU providers for AI training and inference.

## 📑 Table of Contents

- [AI Training Platforms (4)](#ai-training-platforms)
- [Bare-Metal & Reserved Clusters (4)](#bare-metal--reserved-clusters)
- [Container Registries/Images (3)](#container-registriesimages)
- [GPU Marketplaces (10)](#gpu-marketplaces)
- [Hyperscalers (9)](#hyperscalers)
- [Kubernetes GPU Platforms (2)](#kubernetes-gpu-platforms)
- [Price Comparison Tools (3)](#price-comparison-tools)
- [Serverless GPU (12)](#serverless-gpu)
- [Specialized GPU Clouds (15)](#specialized-gpu-clouds)


## AI Training Platforms

- [Databricks Mosaic AI](https://www.databricks.com/product/machine-learning/mosaic-ai) - Unified platform for fine-tuning, training, and serving large language models inside the Databricks Lakehouse, providing end-to-end MLOps for generative AI applications. ([Read more](/details/databricks-mosaic-ai.md)) `Paid` `Api` `Enterprise` `Ai Powered`
- [Hugging Face Training Cluster as a Service](https://huggingface.co/training-cluster) - On-demand GPU clusters integrated with Hugging Face tools and datasets for training machine learning models at scale. ([Read more](/details/hugging-face-training-cluster-as-a-service.md)) `Paid` `Api` `Ai Powered`
- [MosaicML Foundry](https://github.com/mosaicml/llm-foundry) - Open-source training framework for large language models from 125M to 70B+ parameters, providing tools for distributed training and fine-tuning. ([Read more](/details/mosaicml-foundry.md)) `Open Source` `Self Hosted` `Ai Powered`
- [Weights & Biases](https://wandb.ai/) - MLOps platform for experiment tracking, model registry, and performance monitoring for GPU training runs, providing tools to track, visualize, and optimize machine learning experiments. ([Read more](/details/weights-biases.md)) `Paid` `Api` `Enterprise` `Ai Powered`

## Bare-Metal & Reserved Clusters

- [Nscale](https://www.nscale.com/) - GPU cloud built for large-scale AI training and sovereign AI deployments, offering GPU clusters for enterprise and research workloads. ([Read more](/details/nscale.md)) `Paid` `Enterprise` `Cloud Gpu`
- [NVIDIA DGX Cloud](https://www.nvidia.com/en-us/data-center/dgx-cloud/) - AI supercomputing-as-a-service with NVIDIA DGX systems, NIM/NeMo microservices, and access through NVIDIA Cloud Partners for enterprise AI training and inference. ([Read more](/details/nvidia-dgx-cloud.md)) `Paid` `Enterprise` `Api`
- [NVIDIA DGX Cloud Lepton](https://www.nvidia.com/en-us/data-center/dgx-cloud-lepton/) - Compute marketplace connecting developers to tens of thousands of GPUs across global NVIDIA Cloud Partners, providing access to distributed GPU capacity for AI workloads. ([Read more](/details/nvidia-dgx-cloud-lepton.md)) `Paid` `Marketplace` `Api`
- [Voltage Park](https://voltagepark.com/) - Bare-metal and reserved GPU cluster provider for large-scale AI training. Offers dedicated NVIDIA clusters with high-bandwidth networking. Pricing is paid, typically contract-based. ([Read more](/details/voltage-park.md)) `Paid` `Enterprise`

## Container Registries/Images

- [Docker Hub](https://hub.docker.com/) - Public container registry hosting official GPU-enabled images for CUDA, PyTorch, TensorFlow, and community ML projects. ([Read more](/details/docker-hub.md)) `Free Plan` `Cloud Gpu`
- [GitHub Container Registry](https://github.com/features/packages) - Container and artifact hosting tightly integrated with GitHub Actions and repositories for storing and deploying GPU container images. ([Read more](/details/github-container-registry.md)) `Free Plan` `Cloud Gpu`
- [NVIDIA NGC Catalog](https://catalog.ngc.nvidia.com/) - Curated GPU-optimized containers, models, SDKs, and Helm charts for PyTorch, TensorFlow, TensorRT, CUDA, and more, hosted by NVIDIA for AI and HPC workloads. ([Read more](/details/nvidia-ngc-catalog.md)) `Free Plan` `Ai Powered`

## GPU Marketplaces

- [Akash Network](https://akash.network/) - Decentralized GPU marketplace built on open-source blockchain infrastructure. Allows users to lease compute from a global network of providers. Pricing is paid. ([Read more](/details/akash-network.md)) `Open Source` `Paid` `Api`
- [Hyperbolic](https://hyperbolic.xyz/) - Decentralized GPU marketplace aggregating compute for AI inference and training. Offers on-demand access to global GPU supply via API. Pricing is paid. ([Read more](/details/hyperbolic.md)) `Paid` `Api` `Ai Powered`
- [io.net](https://io.net/) - Decentralized GPU network aggregating compute for AI and machine learning. Offers on-demand clusters via a marketplace model. Pricing is paid. ([Read more](/details/io-net.md)) `Paid` `Api` `Ai Powered`
- [Prime Intellect](https://www.primeintellect.ai/) - Decentralized compute exchange aggregating 12+ providers for distributed training and inference, enabling access to aggregated GPU capacity across multiple clouds. ([Read more](/details/prime-intellect.md)) `Paid` `Marketplace` `Api`
- [RunPod](https://www.runpod.io/) - GPU cloud marketplace offering on-demand and spot instances for AI training and inference. Targets developers and teams needing scalable NVIDIA GPU compute. Pricing is usage-based with no long-term commitment. ([Read more](/details/runpod.md)) `Paid` `Api` `Ai Powered`
- [Salad](https://salad.com/) - Distributed cloud platform leveraging consumer GPUs for containerized AI workloads. Provides scalable inference and batch processing at low cost. Pricing is paid. ([Read more](/details/salad.md)) `Paid` `Api` `Ai Powered`
- [Shadeform](https://shadeform.com/) - GPU cloud marketplace deploying across 30+ clouds with one console, API, and unified bill for finding and managing GPU capacity. ([Read more](/details/shadeform.md)) `Paid` `Api` `Marketplace`
- [Spheron](https://spheron.network/) - Decentralized compute platform offering GPU instances for AI deployment and hosting. Targets developers needing distributed infrastructure. Pricing is paid. ([Read more](/details/spheron.md)) `Paid` `Api`
- [TensorDock](https://tensordock.com/) - GPU marketplace providing on-demand cloud instances from a network of data centers. Targets users needing flexible, hourly GPU compute for AI workloads. Pricing is paid. ([Read more](/details/tensordock.md)) `Paid` `Api`
- [Vast.ai](https://vast.ai/) - Decentralized GPU marketplace connecting users with idle compute capacity from hosts worldwide. Suitable for cost-sensitive AI training and inference jobs. Pricing is usage-based, paid. ([Read more](/details/vast-ai.md)) `Paid` `Api` `Ai Powered`

## Hyperscalers

- [Alibaba Cloud GPU](https://www.alibabacloud.com/product/gpu) - Alibaba Cloud GPU-accelerated ECS instances including GN7 (A10), GN10e (V100) for AI and rendering workloads in Asia-Pacific regions. ([Read more](/details/alibaba-cloud-gpu.md)) `Paid` `Enterprise`
- [Amazon Web Services](https://aws.amazon.com/) - Hyperscaler offering GPU instances such as P4d, P5, and G5 for AI and HPC. Provides broad cloud services and managed AI tools. Pricing is paid, on-demand or reserved. ([Read more](/details/amazon-web-services.md)) `Paid` `Enterprise` `Api`
- [AWS EC2 Accelerated Computing](https://aws.amazon.com/ec2/instance-types/accelerated-computing/) - Amazon Web Services EC2 instance types for GPU-accelerated computing including P5/P5e (H100/H200), P4d (A100), G6e (L40S), and Trainium/Inferentia accelerators. Offers EFA networking and UltraClusters for large-scale distributed training. Pricing models include on-demand, spot, reserved, and capacity blocks. ([Read more](/details/aws-ec2-accelerated-computing.md)) `Paid` `Api` `Enterprise`
- [Azure NC/ND GPU Virtual Machines](https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/) - Microsoft Azure GPU-accelerated virtual machines including NCads H100 v5, ND H100 v5, NC A100 v4, and NVads A10 v5 series. Offers InfiniBand networking options and is well-suited for Windows/Linux workstations and Azure ML training jobs. ([Read more](/details/azure-ncnd-gpu-virtual-machines.md)) `Paid` `Api` `Enterprise`
- [Google Cloud](https://cloud.google.com/) - Hyperscaler offering GPU instances including A2, A3, and G2 for machine learning workloads. Integrates with Vertex AI and other managed services. Pricing is paid. ([Read more](/details/google-cloud.md)) `Paid` `Enterprise` `Api`
- [Google Cloud GPU Instances](https://cloud.google.com/compute/docs/gpus) - Google Cloud Platform GPU-accelerated virtual machine instances including A3 (H100), A3 Ultra (H200), A4 (B200), A4X (GB200), G2 (L4), and G4 (RTX PRO 6000) machine types. Tightly integrated with Vertex AI, GKE, and TPUs for AI training and inference workloads. ([Read more](/details/google-cloud-gpu-instances.md)) `Paid` `Api` `Enterprise`
- [IBM Cloud GPU](https://www.ibm.com/cloud/gpu) - IBM Cloud GPU instances featuring NVIDIA H100 and A100 GPUs for AI training, inference, and virtual desktop infrastructure (VDI) workloads. ([Read more](/details/ibm-cloud-gpu.md)) `Paid` `Enterprise`
- [Microsoft Azure](https://azure.microsoft.com/) - Hyperscaler offering ND- and NC-series GPU virtual machines for AI training and inference. Integrates with Azure Machine Learning and AI services. Pricing is paid. ([Read more](/details/microsoft-azure.md)) `Paid` `Enterprise` `Api`
- [Oracle Cloud Infrastructure GPU](https://www.oracle.com/cloud/compute/gpu/) - Oracle Cloud GPU instances including bare-metal and VM options with NVIDIA H100, H200, A100, L40S, and AMD MI300X GPUs. Features RDMA cluster networking and is often priced below AWS/GCP/Azure for equivalent shapes, with free egress tiers. ([Read more](/details/oracle-cloud-infrastructure-gpu.md)) `Paid` `Enterprise`

## Kubernetes GPU Platforms

- [Crusoe Cloud Managed Kubernetes](https://www.crusoe.ai/cloud) - Managed Kubernetes service for GPU and CPU workloads with InfiniBand-backed clusters, offered by Crusoe Energy for AI training and inference. ([Read more](/details/crusoe-cloud-managed-kubernetes.md)) `Paid` `Kubernetes` `Cloud Gpu`
- [SUNK (Slurm on Kubernetes)](https://www.coreweave.com/products/slurm-on-kubernetes) - CoreWeave's Slurm-on-Kubernetes solution for running HPC and AI training workloads on the same cluster, combining Slurm scheduling with Kubernetes orchestration. ([Read more](/details/sunk-slurm-on-kubernetes.md)) `Paid` `Kubernetes` `Hpc`

## Price Comparison Tools

- [AMD MI210](https://getdeploying.com/reference/cloud-gpu) - AMD MI210 is a data center accelerator based on the CDNA2 architecture with 64 GB of HBM2e memory, released in 2022. It is available from 1 cloud GPU provider at $1.00/GPU/hr. Pricing model: paid, hourly rental. ([Read more](/details/amd-mi210.md)) `Paid` `Price Comparison` `Amd` `Cloud Gpu`
- [GPUFindr](https://gpufindr.com/) - Live price comparison across CoreWeave, Lambda, RunPod, Vast.ai, and other GPU clouds with a free API and MCP server for finding the best GPU deals. ([Read more](/details/gpufindr.md)) `Free Plan` `Api` `Price Comparison`
- [NodeHawk](https://nodehawk.polsia.app/) - Price aggregator scanning 50+ clouds to surface the cheapest GPU deals across multiple providers. ([Read more](/details/nodehawk.md)) `Free Plan` `Price Comparison` `Api`

## Serverless GPU

- [Anyscale](https://www.anyscale.com/) - Managed serverless platform built on Ray for scaling AI and Python workloads. Supports GPU-optimized clusters for training and inference. Pricing is paid with usage-based billing. ([Read more](/details/anyscale.md)) `Paid` `Api` `Ai Powered`
- [Baseten](https://www.baseten.co/) - Model-serving platform with low-latency inference, async workers, and the open-source Truss packaging framework for deploying machine learning models. ([Read more](/details/baseten.md)) `Paid` `Api` `Open Source`
- [Beam Cloud](https://www.beam.cloud/) - Serverless GPU cloud for training and inference with per-second billing and a Python SDK for deploying machine learning workloads. ([Read more](/details/beam-cloud.md)) `Paid` `Api` `Ai Powered`
- [Cerebrium](https://www.cerebrium.ai/) - Serverless GPU platform for AI inference and training with infrastructure-as-code capabilities and fast cold starts for deploying machine learning models. ([Read more](/details/cerebrium.md)) `Paid` `Api` `Ai Powered`
- [Fal](https://fal.ai/) - Generative-media inference engine optimized for diffusion and real-time image/video workloads, providing scalable GPU inference for creative AI applications. ([Read more](/details/fal.md)) `Paid` `Api` `Ai Powered`
- [Google Cloud Run GPUs](https://cloud.google.com/run) - Serverless container platform on Google Cloud with NVIDIA L4 GPU support for request-driven or job-based GPU workloads, enabling scale-to-zero containerized AI inference. ([Read more](/details/google-cloud-run-gpus.md)) `Paid` `Api` `Enterprise`
- [Hugging Face](https://huggingface.co/) - AI platform offering serverless GPU inference endpoints and training infrastructure. Hosts models and datasets with managed deployment options. Pricing is freemium with paid compute plans. ([Read more](/details/hugging-face.md)) `Freemium` `Api` `Ai Powered`
- [Koyeb](https://www.koyeb.com/) - Serverless cloud platform with global GPU deployment and scale-to-zero capabilities, supporting H100, A100, and Tenstorrent accelerators for AI workloads. ([Read more](/details/koyeb.md)) `Paid` `Api`
- [Modal](https://modal.com/) - Serverless platform for running AI workloads on GPU infrastructure with automatic scaling. Targets developers deploying inference and training jobs without managing servers. Pricing is freemium with paid usage tiers. ([Read more](/details/modal.md)) `Freemium` `Api` `Ai Powered`
- [Novita AI](https://novita.ai/) - GPU cloud and serverless inference platform with 200+ ready-to-use models and on-demand GPU instances for AI training and inference workloads. ([Read more](/details/novita-ai.md)) `Paid` `Api` `Ai Powered`
- [Replicate](https://replicate.com/) - Serverless GPU platform for running machine learning models via API. Enables developers to deploy and scale inference without managing infrastructure. Pricing is freemium with paid usage. ([Read more](/details/replicate.md)) `Freemium` `Api` `Ai Powered`
- [Together AI](https://together.ai/) - Serverless GPU platform for training, fine-tuning, and inference of open-source models. Provides API access to GPU compute and model endpoints. Pricing is paid with usage-based billing. ([Read more](/details/together-ai.md)) `Paid` `Api` `Ai Powered`

## Specialized GPU Clouds

- [Akamai Cloud GPU](https://www.akamai.com/products/gpu) - Akamai Cloud GPU instances and managed Kubernetes (LKE) nodes with NVIDIA RTX PRO 6000 Blackwell and L40S GPUs for AI and graphics workloads. ([Read more](/details/akamai-cloud-gpu.md)) `Paid` `Api` `Kubernetes`
- [ClearML](https://clear.ml/) - Open-source MLOps platform for experiment management, orchestration, and GPU cluster management. Can be self-hosted or used as a managed service. Pricing is open source for self-hosted deployment. ([Read more](/details/clearml.md)) `Open Source` `Self Hosted` `Enterprise` `Api`
- [CoreWeave](https://coreweave.com/) - Specialized GPU cloud and bare-metal provider focused on large-scale AI and HPC workloads. Offers NVIDIA GPU clusters with high-performance networking for enterprises. Pricing is paid, typically reserved or contract-based. ([Read more](/details/coreweave.md)) `Paid` `Enterprise` `Api`
- [Crusoe](https://crusoeenergy.com/) - Specialized GPU cloud powered by stranded energy, offering on-demand and reserved NVIDIA instances. Designed for AI training and inference workloads with sustainability focus. Pricing is paid. ([Read more](/details/crusoe.md)) `Paid` `Enterprise` `Api`
- [DataCrunch / Verda](https://datacrunch.io/) - Low-cost GPU instances and clusters in Iceland and Finland, offering affordable GPU computing with renewable energy-powered data centers. ([Read more](/details/datacrunch-verda.md)) `Paid` `Cloud Gpu`
- [Fluidstack](https://fluidstack.com/) - Specialized GPU cloud offering on-demand and reserved NVIDIA instances for AI training and inference. Serves startups and enterprises with scalable compute and managed options. Pricing is paid. ([Read more](/details/fluidstack.md)) `Paid` `Enterprise` `Api`
- [GMI Cloud](https://www.gmicloud.ai/) - GPU cloud with H100, H200, B200, and GB200 clusters and managed Kubernetes for large-scale AI training and inference workloads. ([Read more](/details/gmi-cloud.md)) `Paid` `Kubernetes` `Cloud Gpu`
- [gpu.nz](https://gpu.nz/) - gpu.nz is a GPU cloud provider offering on-demand GPU instances for AI and ML workloads. It provides an MCP server for AI agents to discover GPU availability, estimate VRAM requirements, rent, monitor, and stop GPU servers programmatically. The service is paid and cloud-deployed, with free hosted MCP access requiring no API key. ([Read more](/details/gpunz.md)) `Paid` `Api` `Cloud Gpu`
- [Hyperstack](https://www.hyperstack.cloud/) - EU-focused GPU cloud with NVIDIA H100, A100, and L40S instances, powered by 100% renewable energy for AI training and inference workloads. ([Read more](/details/hyperstack.md)) `Paid` `Cloud Gpu` `Renewable Energy`
- [JarvisLabs](https://jarvislabs.ai/) - Per-minute billing GPU cloud for individual developers and small teams, offering on-demand GPU instances with consumer and data-center GPUs. ([Read more](/details/jarvislabs.md)) `Paid` `Cloud Gpu`
- [Lambda](https://lambdalabs.com/) - Specialized GPU cloud providing on-demand instances and reserved clusters for machine learning workloads. Serves AI researchers and engineering teams with NVIDIA GPUs and preconfigured environments. Pricing is hourly or reserved, paid. ([Read more](/details/lambda.md)) `Paid` `Enterprise` `Api`
- [Nebius](https://nebius.com/) - AI-centric cloud platform offering GPU infrastructure and managed services for training and inference. Built for European enterprises and AI developers requiring compliant compute. Pricing is paid. ([Read more](/details/nebius.md)) `Paid` `Enterprise` `Api`
- [NVIDIA Run:ai](https://www.run.ai/) - Kubernetes-native GPU orchestration and workload scheduler for maximizing AI compute utilization across GPU clusters. ([Read more](/details/nvidia-runai.md)) `Paid` `Api` `Kubernetes` `Enterprise`
- [Paperspace](https://www.paperspace.com/) - Specialized GPU cloud providing notebooks, training, and deployment environments for machine learning. Targets individual developers and teams with a managed platform. Pricing is paid with a free tier for limited usage. ([Read more](/details/paperspace.md)) `Freemium` `Paid` `Api`
- [SaladCloud](https://salad.com/) - Distributed cloud using consumer gaming GPUs across 450,000+ provider nodes, offering low-cost GPU instances for containerized workloads. ([Read more](/details/saladcloud.md)) `Paid` `Cloud Gpu` `Consumer Gpu`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg