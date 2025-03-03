---
id: getting-started
title: 이더리움↔폴리곤 브리지
sidebar_label: 개요
description: 폴리곤에서 다음 블록체인 앱을 설치합니다.
keywords:
  - docs
  - matic
image: https://matic.network/banners/matic-network-16x9.png
---

폴리곤은 플라즈마 및 PoS 보안이 적용된 크로스체인 브리지를 도입하여 폴리곤과 이더리움 간의 무신뢰 양방향 트랜잭션 채널을 제공합니다. 이를 통해 사용자는 타사 위험 및 시장 유동성 제한 없이 폴리곤을 통해 토큰을 전송할 수 있습니다. **_플라즈마 및 PoS 브리지는 뭄바이와 메인넷 모두에서 사용할 수 있습니다._**

**Polygon Bridge는 거의 즉각적이고 저렴하며 매우 유연한 확장 솔루션을 제공합니다**. Polygon은 이중 합의 아키텍처(Plasma + PoS(Proof-of-Stake) 플랫폼)를 사용하여 속도와 탈중앙화를 최적화합니다. 우리는 EVM을 지원하는 사이드체인에서 임의의 상태 전환을 지원하도록 시스템을 의식적으로 설계했습니다.

**브리지를 거쳐갈 때 토큰의 순환 공급량에는 변화가 없습니다**;

- 이더리움 네트워크를 떠나는 토큰은 잠겨 있으며 폴리곤에 페깅된 토큰(1:1)과 동일한 수의 토큰이 발행됩니다.
- 토큰을 이더리움 네트워크로 다시 옮기기 위해 토큰은 폴리곤 네트워크에서 소각되고 프로세스 중에 이더리움 네트워크에서 잠금 해제됩니다.

## PoS vs Plasma

|                       | PoS 브리지(권장)                           | 플라즈마 브리지                                     |
| --------------------- | ------------------------------------- | -------------------------------------------- |
| **간략한 설명**            | POS 시스템 보안으로 유연성과 빠른 출금을 원하는 DApp 개발자 | Plasma 종료 메카니즘으로 향상된 보안 보장을 높이고자 하는 DApp 개발자 |
| **구조**                | 매우 우연함                                | 견고함. 덜 유연함                                   |
| **입금\(이더리움→ 폴리곤\)** | 3-5 분                                 | 3-5 분                                        |
| **출금\(폴리곤→ 이더리움\)** | 1 체크포인트 = ~ 20 분 ~ 3 시간               | 이더리움의 컨트랙트에 대한 프로세스 종료 절차를 호출.               |
| **보안**                | 강력한 외부 검증 세트에 의해 보호되는 지분 증명 시스템\.    | 폴리곤의 플라즈마 컨트랙트는 이더리움의 보안에 대한 편승함.            |
| **지원 표준**             | ETH, ERC20, ERC721, ERC1155 및 기타      | ETH, ERC20, ERC721만 해당                       |
