---
title: Bluetooth Low Energy
layout: single
permalink: /ble/
author_profile: true
toc_ads: true
---

{% capture fig_img %}
![ble-intro]({{ '/assets/images/2020-04-12-banniere-article-ble.jpg' | relative_url }})
{% endcapture %}

<figure style="width: 100%">
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>출처: https://elainnovation.com/what-is-ble.html</figcaption>
</figure>

본 시리즈에서는 저전력 블루투스 (<span style="color:#0174DF"><b>Bluetooth Low Energy, BLE</b></span>) 기술에 대해 소개하고, **[DevZone](https://devzone.nordicsemi.com/)** 사이트에서 제공하는 포스트를 토대로 공부한 내용들을 정리할 예정입니다.

**Notice:** 각 자료에 대한 저작권 및 지적재산권 (Copyright)은 관련 링크 및 원본 포스트 작성자에게 있으며, 해당 자료를 토대로 재구성한 포스트에 대한 저작권은 필자에게 있으므로, 공부 목적 이외의 상업적 무단 배포를 금지합니다.
{: .notice--info}

---

## 포스팅 항목

* [BLE (1) - 저전력 블루투스 (BLE) 란?](https://enidanny.github.io/ble/what-is-the-ble/)
* [BLE (2) - BLE 프로토콜 스택](https://enidanny.github.io/ble/ble-protocol-stack/)
* [BLE (3) - ATT/GATT 이해하기](https://enidanny.github.io/ble/ble-att-gatt/)
* [BLE (4) - BLE 디바이스는 어떻게 연결할까?](https://enidanny.github.io/ble/ble-connection/)
* [BLE (5) - BLE 통신 속도는 실제로 1 Mbps 일까?](https://enidanny.github.io/ble/ble-effective-throughput/)
* [BLE (6) - BLE 5.0 주요 특징](https://enidanny.github.io/ble/ble5-intro/)
* [BLE (7) - 연결 파라미터](https://enidanny.github.io/ble/ble-slave-latency/)
* [BLE (8) - Nordic BLE Chip 개발환경 구축하기](https://enidanny.github.io/ble/ble-development/)
* [BLE (9) - 블루투스 메시: Overview of Mesh stack](https://enidanny.github.io/ble/ble-mesh/)
* [BLE (10) - 블루투스 메시: Overview of Mesh operation](https://enidanny.github.io/ble/ble-mesh-opeartion/)
* [BLE (11) - 블루투스 메시: Overview of Mesh concepts](https://enidanny.github.io/ble/ble-mesh-concepts/)

## 포스팅 예정 항목
<!--* BLE (?) - Nordic BLE chip 개발하기 (1): nRF52-DK 개발환경 구축 nRF52832 chip / Keil compiler / nRF command-line Tool / SDK, softdevice-->
<!--* BLE (?) - Nordic BLE chip 개발하기 (2): nRF52-DK 프로그래밍 예제 sdk 구성 / softdevice, program upload / custom board upload / GATT 예제 (link)-->
<!--* BLE (?) - Nordic BLE chip 개발하기 (3): BLE 비콘-->
<!--* BLE (?) - Nordic BLE chip 개발하기 (4): BLE 비콘 스캐너-->