# 🚗 DS LAB - Multi UGV Control System

> ROS 기반 자율주행 UGV와 웹 기반 GCS를 통합한  
> **실시간 다중 로봇 관제 시스템**

---

## 📌 Overview

DS LAB 프로젝트는 다중 UGV(무인 지상 차량)와 GCS(Ground Control Station) 간의  
**실시간 양방향 통신 시스템**을 구축하는 프로젝트입니다.

ROS 기반 자율주행 시스템과 Node.js / React 기반 웹 시스템을 연동하여  
센서 데이터 수집, 영상 스트리밍, 원격 제어까지 통합한 **통합 관제 플랫폼**을 구현했습니다.

---

## 🎯 Key Features

### 📡 Real-time Telemetry
- GPS / IMU / LiDAR 데이터 수집 및 전송
- UDP 기반 저지연 스트리밍

### 🎥 Live Video Streaming
- 카메라 데이터 WebSocket 전송
- 브라우저 실시간 렌더링

### 🎮 Remote Control
- TCP/UDP 기반 제어 명령 전송
- AUTO / MANUAL 모드 지원

### 🤖 Multi-UGV Management
- 다중 로봇 상태 관리
- 실시간 클라이언트 모니터링

---

## 🏗️ Architecture
