---
title: "Research Overview"
permalink: /research/
layout: default
---

# Research Overview
- An operating system is an essential system s/w for organizing system components and managing both policies and mechanisms for various computing devices, from traditional PCs and servers to cloud data center h/w platforms, IoT devices, smartphones, automobiles, intelligent robots, and so on. 
- We focus on studying the entire system s/w stack from a low-level device control (firmware or device driver-level) and resource scheduling to pursue various goals (OS subsystems) and abstraction of intelligent and high-level system management functions (API-level).
- 운영체제는 기존의 PC와 서버에서 클라우드 데이터센터 H/W 플랫폼, IoT 기기, 스마트폰, 자동차, 지능형 로봇 등 다양한 컴퓨팅 기기에 대한 시스템 구성 요소를 구성하고 정책과 메커니즘을 관리하는 필수적인 시스템 소프트웨어입니다.
- 본 연구실은 전체 시스템 s/w 스택을 연구하며, 저수준의 장치 제어부터, 다양한 목적으로 수행되는 자원 스케줄링, 고수준의 시스템 관리 기능을 지능적으로 추상화하는 것에 대한 연구에 초점을 둡니다.

# Research Interests & Topics (2021-now.)
- Lightweight virtualization resource management for esatablishing efficient microservices (효율적인 마이크로서비스 구축을 위한 경량 가상화 기반 자원 관리)
- Analyzing workloads in cloud XaaS and OS kernel-level resource management (클라우드 XaaS 워크로드 분석 및 커널 레벨 자원 관리)
- Workload characterization and system support for machine-learning based GPU workload 머신러닝을 위한 GPU 워크로드 특성 분석 및 시스템 지원
- Cloud service level objective system resource managment (클라우드 서비스 수준 목표 맞춤 시스템 자원 관리)
- Optimizing distributed platform S/W running on low-power mini-cluster (저가/소형 기반의 미니클러스터를 위한 분산 플랫폼 SW 최적화)
- Other topics related to Cloud IaaS, Microservice, System S/W, OS kernel, etc.
- If you are interested in any of the above topics or would like to study, please contact us. (위 주제 가운데 관심이 있거나, 연구해보고 싶은 학생들은 연락 바랍니다.)
	- ypkim at inu ac kr

# Appendix. FYI (continuously updating)

# Microservices/Microarchitectures

## Google's definition:
- From https://cloud.google.com/learn/what-is-microservices-architecture?hl=ko   (2022.11)
- A microservices architecture is a type of application architecture where the application is developed as a collection of services. It provides the framework to develop, deploy, and maintain microservices architecture diagrams and services independently.
- 마이크로서비스 아키텍처는 애플리케이션이 서비스 모음으로 개발되는 애플리케이션 아키텍처의 한 유형입니다. 또한 마이크로서비스 아키텍처 다이어그램과 서비스를 독립적으로 개발, 배포, 유지관리할 수 있는 프레임워크를 제공합니다.

## Amazon's definition 
- From https://aws.amazon.com/ko/microservices/ (2022.11)
- With a microservices architecture, an application is built as independent components that run each application process as a service. These services communicate via a well-defined interface using lightweight APIs. Services are built for business capabilities and each service performs a single function. Because they are independently run, each service can be updated, deployed, and scaled to meet demand for specific functions of an application.
- 마이크로서비스 아키텍처의 경우, 애플리케이션이 독립적인 구성 요소로 구축되어 각 애플리케이션 프로세스가 서비스로 실행됩니다. 이러한 서비스는 경량 API를 사용하여 잘 정의된 인터페이스를 통해 통신합니다. 서비스는 비즈니스 기능을 위해 구축되며 서비스마다 한 가지 기능을 수행합니다. 서비스가 독립적으로 실행되기 때문에 애플리케이션의 특정 기능에 대한 수요를 충족하도록 각각의 서비스를 업데이트, 배포 및 확장할 수 있습니다.

## IBM's definition 
- From https://www.ibm.com/kr-ko/cloud/learn/microservices (2022.11)
- Microservices (or microservices architecture) are a cloud native architectural approach in which a single application is composed of many loosely coupled and independently deployable smaller components, or services. 
- 마이크로서비스(또는 마이크로 서비스 아키텍처)는 단일 애플리케이션이 다수의 느슨하게 결합되고 독립적으로 배치 가능한 더 작은 컴포넌트 또는 서비스로 구성되는 클라우드 네이티브 아키텍처 접근 방식입니다.
