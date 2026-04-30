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
[1.70] <br>
[이슈외 작업]
* 삭제열차 삭제처리
* JGR 0.72 뒤집힘 방지 설정 대비 기존 뒤집힘 방지 설정 코드 제거

[이슈작업]
* [사운드변경][사운드 삭제] 우진산전 수소연료전지동차 출발 사운드 삭제 ([#753](https://github.com/DTS-NewGRF/DTS_World/issues/753))
* [열차추가][Japan] JR 서일본 227계 500번대 전동차 (32bpp) ([#754](https://github.com/DTS-NewGRF/DTS_World/issues/754))
* 한큐전철 전동차 출력 조정 ([#755](https://github.com/DTS-NewGRF/DTS_World/issues/755))

## 인게임 등록
[1.69] <br>
* [버그] 신칸센 500계, 700계, N700계 16량 수송량이 잘못됨 ([#743](https://github.com/DTS-NewGRF/DTS_World/issues/743))(2026.04.20)
* [버그] 신칸센 N700S계 니시큐슈 출력이 과함 ([#744](https://github.com/DTS-NewGRF/DTS_World/issues/744))(2026.04.20)
* [버그] 한큐전철 7300형 전동차 6량편성 출력이 낮음 ([#745](https://github.com/DTS-NewGRF/DTS_World/issues/745))(2026.04.20)
* [버그] 고속수화물차 수송량 조정 적용이 안되어 있음 ([#746](https://github.com/DTS-NewGRF/DTS_World/issues/746))(2026.04.20)
* [버그] 중국 객차, 중국 발전차의 임시 삭제 처리가 복구되어 있지 않음 ([#747](https://github.com/DTS-NewGRF/DTS_World/issues/747))(2026.04.20)
* [열차변경] JR 서일본 125계 전동차 구매창 이미지 변경 ([#748](https://github.com/DTS-NewGRF/DTS_World/issues/748))(2026.04.20)
* [열차추가][World] 탄자니아철도공사 성신RST 객차 (32bpp) ([#749](https://github.com/DTS-NewGRF/DTS_World/issues/749))(2026.04.20)
* [사운드변경][사운드 삭제] KTX-산천 A타입, SRT + KTX-산천 B타입 중련편성 전용 사운드 삭제 ([#750](https://github.com/DTS-NewGRF/DTS_World/issues/750))(2026.04.20)
* [열차추가][World] 탄자니아 철도공사 E6800호대 전기기관차(32bpp) ([#751](https://github.com/DTS-NewGRF/DTS_World/issues/751))(2026.04.20)
* [열차변경] 니시테츠 6050형 사운드 추가(개조) ([#752](https://github.com/DTS-NewGRF/DTS_World/issues/752))(2026.04.22)

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