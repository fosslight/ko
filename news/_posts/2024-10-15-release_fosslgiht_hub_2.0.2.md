---
layout: post
title: FOSSLight Hub 2.0.2 릴리즈
description: >
  FOSSLight Hub 2.0.2 릴리즈
hide_last_modified: true
---


FOSSLight Hub 2.0.2가 출시되었습니다!
이번 버전은 기존 UI 2.0이 반영된 pre-release 버전에서 데이터베이스(DB) 관련 변경사항까지 포함된 정식 2.0 버전입니다.

FOSSLight Hub 2.0버전은 사용자 인터페이스(UI)를 한층 더 직관적으로 개선하고, 새로운 기능들로 편의성을 높였습니다.
또한 오소리 프로젝트에 맞춰 Restriction 데이터 업데이트 등 여러 추가 변경사항이 있습니다.

주요 신규 변경점에 대해 정리드리면 아래와 같습니다:

- **라이선스 및 오픈소스 정보 강화**
  - 오소리 프로젝트에 맞춰 Restriction 데이터 업데이트
  - License에 Restriction, Source Code Disclosing Scope 정보 추가
  - Open Source에 Restriction 정보 추가
  - Open Source Vulnerability 정보 매칭 보완을 위한 로직 추가 (include cpe, exclude cpe, version alias) 
- **데이터 관리 효율화를 위한 스키마 변경**
  - Open Source 데이터 관리 효율화를 위해, OSS_COMMON과 OSS_VERSION으로 테이블을 분리함

특히 2.0에서는 DB 관련 다양한 변경사항들이 있으니 적용하실 때 참고해주시기 바랍니다. 변경사항에 대한 자세한 내용은
[Release Note](https://github.com/fosslight/fosslight/blob/main/docs/RELEASE_NOTES_kor.md#200-2024-09-27)
을 확인하시기 바랍니다. DB 업데이트하실 떄 주의사항도 있으니 참고해주시기 바랍니다.


현재 FOSSLight Hub 2.0에서 최신버전은 v2.0.2입니다. 이전 버전들과 비교하여 변경사항은 다음과 같습니다.
- v2.0.1: 2.0.0 버전에서 jqGrid CDN을 불러오지 못하는 주요 버그가 있어, 이를 수정한 hotfix 버전입니다.
- v2.0.2: Save시 발생하는 이슈 등 여러 이슈에 대한 수정 사항 및 속도 개선이 적용되었습니다.

상세한 내용은 각 버전의 Release Note를 참고하시기 바랍니다.
([v2.0.1](https://github.com/fosslight/fosslight/blob/main/docs/RELEASE_NOTES_kor.md#201-2024-09-30),
[v2.0.2](https://github.com/fosslight/fosslight/blob/main/docs/RELEASE_NOTES_kor.md#202-2024-10-14))

FOSSLight 2.0 사용자 분들께서는 2.0.2버전을 사용해주시기 바랍니다.
FOSSLight 2.0 버전에서는 많은 변화가 있었던 만큼, 더 빠른 안정화를 위해 릴리즈가 자주 이루어지고 있습니다.
많은 관심 부탁드리며, 이슈가 발견되면 [Github issue](https://github.com/fosslight/fosslight/issues)에 리포트 해주시기 바랍니다.
또한 언제든지 기여를 환영합니다 🤗

앞으로도 FOSSLight Hub의 발전을 위해 지속적인 성원과 관심을 부탁드립니다. 🙏
