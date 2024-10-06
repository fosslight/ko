---
layout: post
title: FOSSLight Hub 2.0.1 릴리즈
description: >
  FOSSLight Hub 2.0.1 릴리즈
hide_last_modified: true
---


FOSSLight Hub 2.0.1이 출시되었습니다!
이번 버전은 기존 UI 2.0이 반영된 pre-release 버전에서 데이터베이스(DB) 관련 변경사항까지 포함된 정식 2.0 버전입니다.

DB 관련 변경사항을 간략히 요약하면 다음과 같습니다:

- 오소리 프로젝트에 맞춰 Restriction 데이터 업데이트
- License에 Restriction, Source Code Disclosing Scope 정보 추가
- Open Source에 Restriction 정보 추가
- Open Source Vulnerability 정보 매칭 보완을 위한 로직 추가 (include cpe, exclude cpe, version alias) 

이외의 변경사항에 대한 자세한 내용은 [Release Note](https://github.com/fosslight/fosslight/releases/tag/v2.0.0)을 확인하시기 바랍니다.

또한, 2.0.0 버전에서 jqGrid CDN을 불러오지 못하는 주요 버그가 있어, 이를 수정한 hotfix 버전인 2.0.1이 출시되었습니다. 
사용자 여러분께서는 이 점을 참고하여 주시기 바랍니다.
