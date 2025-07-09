---
layout: post
title: FOSSLight Hub 2.3.0 릴리즈 
description: >
  Hub 2.3.0 릴리즈 
hide_last_modified: true
---

FOSSLight Hub 버전 2.3.0이 릴리즈되었습니다. 이번 업데이트에는 새로운 기능들과 여러 개선사항들이 포함되어 있습니다.


**⭐️3rd Party**  
FOSSLight Report export 시 3rd Party Information Sheet가 추가되어, 3rd party 컴포넌트에 대한 더욱 포괄적인 정보를 제공합니다.

**⭐️Project**  
Project Information에 보안 담당자를 입력할 수 있는 필드가 새롭게 추가되었습니다. Creator와 Editor와 함께 보안 담당자는 FOSSLight Hub에서 발송되는 vulnerability 관련 메일을 수신할 수 있습니다. 또한 Pre-Review > Open Source, License 탭에 오소리(Osori)의 DB 정보를 참조할 수 있도록 추가되었습니다. DEP 탭에서는 FOSSLight Dependency Scanner를 통해 분석된 경우 각 의존성(dependency)의 관계를 트리 구조로 시각화하여 확인할 수 있습니다.

**⭐️API**  
Security Responsible Person을 업데이트할 수 있는 API (/api/v2/projects/{id}/security-person)와 Security Mail을 disable/enable할 수 있는 API (/api/v2/projects/{id}/security-mail)가 추가되었습니다. 사용자가 발급받은 Token 정보를 메일 뿐만 아니라 FOSSLight Hub 내 User Setting 메뉴에서도 확인할 수 있게 되었습니다.

**⭐️Common**  
Custom Column 기능이 Security 탭, Project/3rd Party Identification, Self-Check에 확대 적용되었습니다. 또한 상단에 열린 탭 클릭이 아닌 다른 방법으로 탭 진입 시 refresh 팝업이 나타나는 탭 새로고침 기능이 추가되었습니다.

**⭐️Packaging**  
기존에는 OSS Package 파일을 최대 4개까지 업로드할 수 있었으나, 이번 업데이트를 통해 업로드 가능한 파일의 개수가 5개로 확장되었습니다. SPDX와 CycloneDX 문서가 생성될 때 DEP 탭의 Package URL 기준으로 출력이 되도록 변경되어, OSS Name과 OSS Version이 같더라도 Package URL이 다르면 각각 출력되어 모든 Relationship이 표시됩니다. CycloneDX 1.6 지원이 추가되었습니다.

**⭐️License, OSS**  
Share URL 버튼이 추가되었고, level에 따른 Restriction 아이콘 색깔이 변경되어 사용자에게 더 나은 시각적 피드백을 제공합니다.

**⭐️Security**  
CPE 하위에 보이는 Running on/with는 OS 정보가 표시되도록 추가되어 보안 분석에 더욱 상세한 시스템 컨텍스트를 제공합니다.


📦[릴리즈 노트](https://github.com/fosslight/fosslight/blob/main/docs/RELEASE_NOTES_kor.md#230-2025-07-09)  
더 많은 변경사항과 버그 수정사항은 릴리즈 노트를 참조해 주세요.

FOSSLight 2.3.0의 향상된 기능들과 함께 오픈소스 관련 작업을 더욱 효율적으로 수행할 수 있을 것으로 기대됩니다. 여러분의 소중한 피드백이 FOSSLight의 발전에 기여할 것입니다. 의견을 공유해 주세요!
