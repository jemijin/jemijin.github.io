---
layout: post
title: "kubeadm을 이용하여 Kubernetes설치"
subtitle: "Kubernetes Install"
categories: cloud
tags: kubernetes
comments: false
---

Kubernetes를 설치하는 방법은 다양하게 많다.
대상 인프라에 따라 단일/멀티 노드에 따라서 쉬운 방법에서 어려운 방법까지 다양하다.
지금도 새로운 방법으로 설치하는 방법이 나오고 있다.

몇가지 많이 알려진 방법들은 아래와 같다.
- Minikube (난이도 1)
- Play with Kuberenetes(PWK) (난이도 1)
- Installing in the Google Cloud with GKE (난이도 1)
- Installing in the Azure Cloud with AKS (난이도 1)
- Installing on AWS using the kops tool (난이도 3)
- Installing manually usig kubeadm (난이도 5)
- Installing on VirtualBox/Ubuntu with Vagrant: k8s-playground (난이도 5)

참고) https://kuberentes.io/docs/setup/pick-right-solution/

Kubernetes를 설치하는 방법은 다양하게 많다.
그 중에서 난이도가 높고 어렵다는 kubeadm을 이용한 설치방법으로 설치해보겠다.





## PC에서 kubeadm으로 kubernetes 멀티 노드 구성하기
---
1. 가상 리눅스 설치 및 환경 구성   
  1) VM 생성  
  2) Linux 설치  
  3) 고정 IP 설정  
  4) VirtualBox GuestAddition 설치  
  5) Linux SWAP 비활성화  
 
2. Kubernetes 설치  
  1) Docker 설치  
  2) kubenetes tool 설치 (kubeadm, kubectl, kubernetes-cni)  
  3) Initialize Master  
  4) Install a CNI (Pod Network)  
  5) Join Nodes  
  * route setting  
 
