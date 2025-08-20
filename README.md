# Diversity Train Set 다양성 열차세트 /DTS
![DTS_board](https://github.com/DTS-NewGRF/DTS/blob/minengallery/docs/DTS_board.png)
**다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 `[YST]는 중단되었다.`<br>
2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 깃허브 폴더 재정비
기존부터 쓰던 폴더의 구조를 재정비하는 작업을 순차적으로 진행합니다.
이슈작업과는 별도로 진행하므로, 이슈작업을 우선적으로 진행하는 것을 원칙으로 합니다.
본 공지는 모든 자료의 정비가 완료되면 삭제처리 됩니다.
인게임내 열차 정보는 변동이 없습니다.

[변경될 폴더구조]
```
* src : 대표적인 파일들만 남김.
* Objects : 오브젝트 관련 자료. (기존 src/Objects에 존재함 폴더 위치 변경.)
* Template : 템플릿 관련 자료. (기존 src/Template에 존재함. 폴더 위치 변경.)
* Waypoint : 경유지 관련 자료. (기존 src/Waypoint에 존재함 폴더 위치 변경.)
* Trains : DTS열차메인 열차자료들모임. (기존 src, src_나라별 등으로 구분하여 존재. 정비하면서 통합)
```
방대한 분량의 자료이므로 작업과정에 대한 공지는 하지 않습니다.
이전 작업완료된 자료는 폴더 위 명시된 해당 폴더를 참고하시기 바랍니다.

## 최근 등록 프리 릴리즈
[1.65] 2025.08.19 <br>
* [열차변경] SRT-320 중련용 그래픽 추가 (8bpp) ([#682](https://github.com/DTS-NewGRF/DTS/issues/682))
  * [버그] SRT-320 TC1 그래픽 문제 수정 ([#683](https://github.com/DTS-NewGRF/DTS/issues/683))
* [열차변경] 서울교통공사 5000호대, 7000호대, 8000호대 전동차 그래픽 변경 [8bpp, 2CC] ([#684](https://github.com/DTS-NewGRF/DTS/issues/684))

## 최근 등록 릴리즈
[1.64] 2025.07.13 <br>
[이슈 외 작업]
* 사운드 파일 정리
  * Sound.pnml의 스위치 코드로 정리
  * `sw_열차이름_sound` -> `sw_사운드파일명_sound` 코드명 변경
  * 부산교통공사는 기존수익사운드가 다르므로 `sw_사운드파일명_Busanmetro_sound`로 정의함

[이슈 작업]
* [버그] HYEL-150 그래픽 문제 ([#666](https://github.com/DTS-NewGRF/DTS/issues/666))
* [열차변경] [단량]8600호대 전기기관차 컨셉 변경 ([#667](https://github.com/DTS-NewGRF/DTS/issues/667))
* [버그] [4량] 한국철도공사 200000호대 전동차 (누리로) 의 중량이 지나치게 높게 되어있는 현상 ([#668](https://github.com/DTS-NewGRF/DTS/issues/668))
* [열차변경] [2량]8600호대 전기기관차 컨셉 변경 ([#669](https://github.com/DTS-NewGRF/DTS/issues/669))
* [열차변경] [3량]8600호대 전기기관차 & [4량]8600호대 전기기관차 컨셉 변경 ([#670](https://github.com/DTS-NewGRF/DTS/issues/670))
  * [버그] HYEL-강산 운전객차가 후부에 위치할 때 그래픽 오류 ([#671](https://github.com/DTS-NewGRF/DTS/issues/671))
  * [버그] [3량] HYEL-강산의 수송량 수정 ([#672](https://github.com/DTS-NewGRF/DTS/issues/672))
  * [버그] HYEL-강산 M칸 그래픽 문제 ([#677](https://github.com/DTS-NewGRF/DTS/issues/677))
* [열차변경] HYEL-강산 편성 수 추가 ([#673](https://github.com/DTS-NewGRF/DTS/issues/673))
* [열차추가] SRT 320 ([#674](https://github.com/DTS-NewGRF/DTS/issues/674))
* [열차변경][도색추가] KTX-청룡 2세대 ([#675](https://github.com/DTS-NewGRF/DTS/issues/675))
* [열차변경] [가상] KTX-청룡 수송량 변경 ([#676](https://github.com/DTS-NewGRF/DTS/issues/676))
* [열차변경] 통일호 일반실 도색 추가 ([#678](https://github.com/DTS-NewGRF/DTS/issues/678))
* [버그] KTX, KTX-산천 특정 방향에서 그래픽 문제 ([#679](https://github.com/DTS-NewGRF/DTS/issues/679))
* [열차변경] HYEL-무궁화 그래픽 변경 ([#680](https://github.com/DTS-NewGRF/DTS/issues/680))
* [열차변경] HYEL-무궁화 DD 그래픽 변경 ([#681](https://github.com/DTS-NewGRF/DTS/issues/681))

## 인게임 등록
```
[1.60] 2025.02.02
[추가]
- [가상] KTX-청룡 JR 도색 16량
- [가상] KTX-온누리 16량
- [기관차] 4400호대 교외선 도색
- [교외선] 객차, 발전차
- [한국철도공사] 6세대 VVVF 전동차 4, 6, 8량
- [인천교통공사] 1000호대 3세대 8량
[변경]
- [성능] 신칸센 E2, 500, 700계 가상 고속열차 속도 매겨변수 적용
- [그래픽] 템플릿 오류 일괄 수정 (열차길이 7을 쓰는 고속열차 차량)
- [이름변경] HYEL-200->HYEL-무궁화 / HYEL-220->HYEL-무궁화 DD
- [그래픽] 무궁화 일반실 객차 (장대형 신도색 방송실 개조)
- [그래픽] 레이디버드, 유선형 발전차 일부
- [사운드] 공항철도 2000호대 4차분 출발 사운드 변경
- [이름변경] 한국철도공사 4세대 PMSM 도색 이름
- [성능] MEL-150 6량 힘 (1,680->3,360) 증가
- [성능] 공항철도 2000호대 4세대 힘 (2,520->3,360)증가, 수송량 (360->714) 증가
- [그래픽] 한국철도공사 6세대
[삭제진행]
- E6 + E5 & H5 삭제 그래픽 적용 / (1.61) 일괄 삭제처리
```
`Next 인게임 온라인컨텐츠 버전 : 1.70`

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