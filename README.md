# World Diversity Train Set 월드 다양성 열차세트 /DTS_World
![DTS_board](https://github.com/DTS-NewGRF/DTS_World/blob/main/docs/DTS_board.png)
**월드 다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 `[YST]는 중단되었다.`<br>
2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.<br>
2026년 3월 4일 `World Diversity Train Set 월드 다양성 열차세트 / DTS_World`로 이름을 변경하여 실존 열차 위주로 관리하며, 가상열차는 별도로 분리되었다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS_World/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
[1.68] 곧 작업예정 <br>

## 인게임 등록
[1.67] 2026.03.16 <br>
[이슈외작업]
* [DTS-Track] 지하선로, 협궤선로 추가 대응
* [가상열차] 삭제예정 그래픽 적용 및 추가 구입 불가 설정. 곧 삭제예정.
* [기본셋] 가상열차와의 분리로 인해 DTS->DTS_World로 이름을 변경하였음.

[이슈작업]
* [열차변경] KTX-청룡 2세대 그래픽 변경 ([#708](https://github.com/DTS-NewGRF/DTS_World/issues/708))(2026.01.01)
* [열차변경] SRT 320 이관 (실존 → 가상) ([#709](https://github.com/DTS-NewGRF/DTS_World/issues/709))(2026.01.01)
* [열차변경] SRT 320 그래픽 변경 (32bpp) ([#710](https://github.com/DTS-NewGRF/DTS_World/issues/710))(2026.01.01)
* [열차변경] KTX-청룡 2세대 수송량 변경 및 등장년도 변경, SRT 320 등장년도 변경 ([#711](https://github.com/DTS-NewGRF/DTS_World/issues/711))(2026.01.10)
* [버그] 부산김해경전철 전동차가 부산교통공사 그룹 아래에 있음 ([#712](https://github.com/DTS-NewGRF/DTS_World/issues/712))(2026.02.01)
* [열차추가] TLX 관광열차 (32bpp) ([#713](https://github.com/DTS-NewGRF/DTS_World/issues/713))(2026.02.21)
* [열차추가] [1067mm 협궤 전기열차] 타이완철로유한회사 EMU900 (회사 색상) ([#714](https://github.com/DTS-NewGRF/DTS_World/issues/714))(2026.02.23)
  * [버그] 타이완철로유한회사 EMU900 그래픽 문제 수정 ([#715](https://github.com/DTS-NewGRF/DTS_World/issues/715))(2026.02.25)
  * [버그] 타이완철로유한회사 EMU900 그래픽 문제 수정 (2) ([#716](https://github.com/DTS-NewGRF/DTS_World/issues/716))(2026.03.01)
* [열차변경] NSW TrainLink D set 그래픽 리메이크 ([#717](https://github.com/DTS-NewGRF/DTS_World/issues/717))(2026.03.01)
* [버그] Dual head 디젤액압동차의 출력이 낮은 문제 ([#718](https://github.com/DTS-NewGRF/DTS_World/issues/718))(2026.03.16)

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.

## 라이선스
DTS는 크리에이티브 [커먼스 라이선스 v3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) (CC-BY-NC-SA v3.0)을 따릅니다.<br>
DTS 프로젝트에 기여함은 라이선스에 동의함을 의미합니다.