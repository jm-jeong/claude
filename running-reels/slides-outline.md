# 러닝 3요소 릴스 1·2·3편 — 슬라이드 텍스트 개요

원본: Claude Design 캔버스 https://claude.ai/artifact/58tgpYbPt69apMZRM38KAM


## 1편

### 00 훅 질문  (`Hook.dc.html`)

- 러너들이 가장 많이 묻는 질문
- 가민 VO2max는 높은데, 왜 기록은 안 늘까요?
- ≠
- ?
- 레이스 기록

### 01 이유① 시계 추정치  (`Watch.dc.html`)

- 이유 ①시계 VO2max
- 시계 VO2max는 실제 값이 아니라 심박수로 추정한 값
- 산소를 직접 재지 않고, 심박수와 페이스의 관계로 계산해요
- 스마트워치
- 재는 것 심박 + 페이스
- 공식으로 추정
- 실제 VO2max
- 재는 것 들이쉬고 내쉰 산소
- 마스크로 실제 산소 값 측정
- 시계가 60이면, 실제는 이 정도 차이 날 수 있어요
- 시계 60
- 50
- 55
- 60
- 65
- 70
- 평균 오차 약 7~8%
- 값이 흔들리는 원인최대심박 설정손목 심박 오차더위언덕
- 참고: Forerunner 245 vs 실험실 호흡가스 측정 · 지구력 선수 35명 · 평균 절대오차 7.2~7.9%

### 02 이유② 3가지 요인  (`Main.dc.html`)

- 이유 ②
- VO2max가 진짜 높아도, 기록은 이 3가지로 정해진다
- 1
- VO2maxml/kg/min
- 운동 강도를 올려도 더 이상 늘지 않는 최대 산소섭취량 (체중 1kg당 · 1분)
- ↑
- 높을수록 좋음
- 2
- 러닝 이코노미ml/kg/km
- 젖산역치보다 느린 일정한 페이스에서 1km를 달리는 데 드는 산소량 (체중 1kg당)
- ↓
- 낮을수록 좋음
- 3
- 젖산역치역치 페이스 (분/km)
- 페이스를 올릴 때 혈중 젖산이 안정 수준을 벗어나 쌓이기 시작하는 운동 강도
- ↑
- 빠를수록 좋음
- 모델: Joyner MJ (1991) J Appl Physiol · Joyner & Coyle (2008) J Physiol

### 03 VO2max 정의  (`VO2max-Def.dc.html`)

- 01VO2max
- 페이스를 올려도 산소섭취량이 더 늘지 않는 지점
- = 1분 동안 체중 1kg당 쓸 수 있는 산소의 최대량
- 10:00
- 7:30
- 6:00
- 5:00
- 4:00
- VO2max 도달
- 4:00/km
- 1km 페이스 (분:초) · 오른쪽일수록 빠름
- 산소섭취량 (L/분)
- 예시: 체중 70kg · VO2max 60
- 4.2L
- VO2max
- 1분에 산소 4.2L · 더 빨라져도 안 오르는 천장
- 1분마다 페이스를 올리면
- 산소섭취량도 함께 오른다
- 몇 분전력질주 순간이 아니라, 몇 분 버틸 수 있는 강도에서 이 천장에 닿아요.
- 기준: 점증부하 테스트에서 산소섭취량이 정체되는 값

### 04 VO2max 60의 의미  (`VO2max-50.dc.html`)

- 01VO2max
- VO2max 60 이란?
- 60
- ml / kg / min1분 동안 체중 1kg당 산소 60ml를 쓸 수 있다
- 안정 시
- 3.5
- VO2max
- 60
- 약 17배체중 70kg이면 1분에 산소 4.2L
- 안정 시 산소섭취량 1 MET = 3.5 ml/kg/min 기준 · 60 ÷ 3.5 = 약 17 · 60 × 70kg = 4.2L

### 05 러닝 이코노미 정의  (`Economy-Def.dc.html`)

- 02러닝 이코노미
- 같은 페이스로 쭉 달릴 때 쓰는 산소량
- 젖산역치(LT2)보다 느린 페이스를 몇 분간 그대로 유지하며 측정 · ml/kg/km
- 0
- 20
- 40
- 0
- 1
- 2
- 3
- 4
- 5
- 6
- 시간 (분)
- 산소섭취량 (ml/kg/min)
- 예시 데이터
- 40
- 이 구간 평균
- 1km 6:00 페이스 고정 · 6분 내내 같은 페이스로
- 호흡마다 측정한 값
- 평균 추세
- 40 × 6분1분에 40을 쓰며 1km를 6분에 달리면 1km에 드는 산소는 240 ml/kg이에요.
- 이코노미 = 1분 산소섭취량 × 1km 걸린 시간(분) · 참고: Barnes & Kilding (2015) Sports Med Open

### 06 이코노미 비교  (`Economy-Compare.dc.html`)

- 02러닝 이코노미
- VO2max(체중 같음)가 같아도 같은 페이스에서 쓰는 산소는 다르다
- 30
- 40
- 44
- 50
- 60
- 7:30
- 6:00
- 5:00
- 4:30
- 4:00
- 3:20
- VO2max 60 · 두 러너 체중 같음
- 러너 B
- 44
- 40
- 러너 A
- 예시 데이터
- 1km 페이스 (분:초) · 오른쪽일수록 빠름
- 산소섭취량 (ml/kg/min)
- −9%1km 6:00 페이스에서 A가 산소를 덜 써요. 이코노미가 더 좋다는 뜻이에요.
- 예시값 · 두 러너 체중 같음 · 이코노미 A 240, B 264 ml/kg/km

### 07 젖산역치 정의  (`Threshold-Def.dc.html`)

- 03젖산역치
- 페이스를 올리면 혈중 젖산이 꺾여 오르는 지점이 두 곳 있다
- LT1 젖산이 처음 오르기 시작 · LT2 젖산이 급격히 쌓이기 시작
- LT1 · 5:43/km
- LT2 · 4:42/km
- 편하게 오래
- 젖산이 안정 수준
- 버틸 수 있는 구간
- 젖산이 조금씩 오름
- 빠르게 지침
- 젖산이 계속 쌓임
- 7:30
- 6:30
- 5:43
- 5:00
- 4:42
- 4:00
- 예시 데이터
- 1km 페이스 (분:초) · 오른쪽일수록 빠름
- 혈중 젖산 →
- LT1 · LT2역치는 두 곳이에요. 각각의 의미는 다음 편에서 자세히 다룰게요.
- 예시 러너: VO2max 60 · 이코노미 240 ml/kg/km · LT1 = VO2max 70%, LT2 = 85% 지점

### 08 젖산역치 비교  (`Threshold-Compare.dc.html`)

- 03젖산역치
- VO2max와 이코노미가 같아도 역치 페이스는 다를 수 있다
- 러너 C 역치 페이스5:20/km
- 러너 D 역치 페이스4:42/km
- 왜 다를까? 역치가 나타나는 위치가 달라서
- 같은 VO2max(60)에서 역치(LT2)가 몇 % 지점에 오는지
- 러너 CVO2max의 75% 지점에서 역치
- 산소 45
- 60
- 러너 DVO2max의 85% 지점에서 역치
- 산소 51
- 60
- 둘 다 VO2max 60(체중 같음) · 이코노미 240 ml/kg/km · 페이스 = 240 ÷ 역치 산소량

### 09 정리 공식  (`Formula.dc.html`)

- 기록은 세 가지의 조합
- VO2max1분, 체중 1kg당 쓸 수 있는 산소의 최대치
- 60
- ×
- 역치(LT2)가 오는 위치LT2가 VO2max의 몇 %에서 나타나나
- 85%
- =
- 역치에서 쓰는 산소1분, 체중 1kg당
- 51
- 러닝 이코노미1km에 드는 산소량
- 240
- = 역치(LT2) 페이스240 ÷ 51 = 4.71분 → 1km 4분 42초
- 4:42/km
- VO2max, 어떻게 올릴까?
- 다음 편 →
- 모델: Joyner MJ (1991) J Appl Physiol · 모든 값은 체중 1kg당 · 숫자는 예시


## 2편

### 2편 00 훅  (`E2-Hook.dc.html`)

- 러닝 3요소 · 2편
- VO2max, 타고나는 걸까?
- 훈련해도 안 오른다는 말, 반은 맞고 반은 틀려요.
- 타고난 것
- 유전
- 성별 · 나이 · 인종
- VS
- 바꿀 수 있는 것
- 훈련
- 체중

### 2편 01 VO2max 재는 법  (`E2-Recap.dc.html`)

- 복습VO2max 재는 법
- 산소섭취량이 더 안 느는 천장
- 마스크로 산소 측정점증부하 테스트 (CPET)
- 11분마다 페이스 올리기
- 2마스크로 산소 측정
- 3더 안 오르는 값 = VO2max
- 실제 측정 그래프 가로: 시간(분:초)
- 산소섭취량 (왼쪽 축)심박수CO2 배출
- ↑ 천장 = VO2max (약 52)
- 왜?그런데 이 천장 높이는 사람마다 왜 다를까요?
- 측정: 점증부하 테스트 + 호흡가스 분석 · 1편 "VO2max 정의" 참고

### 2편 02 Fick 방정식  (`E2-Fick.dc.html`)

- 복습 심화VO2max의 정체
- VO2max = 심장이 보내는 피 × 근육이 꺼내 쓰는 산소
- VO2max
- 1분에 쓰는 산소
- =
- 심박출량
- 심장이 1분에 보내는 피 = 심박수 × 1회 박출량
- ×
- 산소 추출
- 근육이 피에서 꺼내 쓰는 산소 (동정맥 산소차)
- 엘리트와 일반인, 심장이 보내는 피 비교
- 128ml
- 21.3L
- 일반인
- 145ml
- 26.3L
- 대학 러너
- 187ml
- 33.8L
- 엘리트 러너
- 1회 박출량
- 최대 심박출량
- 1회 박출량
- 최대 심박출량
- 1회 박출량
- 최대 심박출량
- 1회 박출량 = 심장이 한 번 뛸 때 · 최대 심박출량 = 1분 동안근육의 산소 추출은 세 그룹 차이 없음
- 심장엘리트의 차이는 주로 심장에서 나요. 심장이 한 번에 보내는 피가 달라요.
- Fick 원리 · Zhou et al. (2001) Med Sci Sports Exerc (엘리트 5 · 대학 러너 10 · 일반인 10) · Bassett & Howley (2000)

### 2편 03 유전  (`E2-Genetics.dc.html`)

- 바꿀 수 없는 것 ①유전
- VO2max 차이의 절반 이상은 유전
- 사람마다 VO2max가 다른 이유 중 유전이 설명하는 비율
- 절반
- 연구 8개 종합
- 체중당 VO2max
- 72%
- 연구 8개 종합
- 절대 VO2max (L/분)
- 59%
- 1971 쌍둥이 연구
- 25쌍 · 10살 전후 · 소규모
- 93%
- "거의 다 타고난다"는 말은 이 옛날 소규모 연구에서 나왔어요.
- 60~70%개인차의 절반 이상은 타고나요. 그래도 내 VO2max가 고정이라는 뜻은 아니에요.
- Schutte et al. (2016) Physiol Genomics 메타분석 · Klissouras (1971) 쌍둥이 연구

### 2편 04 성별 나이 인종  (`E2-SexAgeRace.dc.html`)

- 바꿀 수 없는 것 ②성별·나이·인종
- 그래서 VO2max는 같은 성별·나이끼리 비교해요
- 가민이 "연령 및 성별 중 상위 5%"로 보여주는 이유
- 성별
- 엘리트끼리 체중당 약 10% 차이
- 남성 심장이 약 30% 크고, 헤모글로빈도 더 많아요
- 10%
- 나이
- 10년마다 줄어드는 VO2max
- 안 할 때
- −12%
- 꾸준히
- −5.5%
- ½
- 인종
- VO2max 자체 차이는 근거가 약해요
- 동아프리카 엘리트의 비밀은 러닝 이코노미 → 3편
- 비슷
- 성별: 생리학 리뷰(2021) · 나이: 마스터즈 vs 비활동 남성 추적 · 인종: 에리트레아 vs 스페인 엘리트(소규모)

### 2편 05 체중  (`E2-Weight.dc.html`)

- 바꿀 수 있는 것 ①체중
- 엔진은 그대로, 차만 가벼워지면
- 엔진1분에 쓸 수 있는 산소 4.2L 그대로
- 80kg
- 4.2L ÷ 80kg
- 52.5
- ml/kg/min
- VO2max 도달 페이스4:34/km
- −10kg→
- 70kg
- 4.2L ÷ 70kg
- 60
- ml/kg/min · +14%
- VO2max 도달 페이스4:00/km
- 단, 지방만 빼야 해요. 굶어서 빼면 근육과 혈액량이 줄어 엔진(4.2L)까지 작아져요.
- 계산 예시 · 1편 러너 기준 · 이코노미 240 ml/kg/km · 체중당 산소 비용이 같다고 가정

### 2편 06 거리별  (`E2-Distance.dc.html`)

- VO2max가 높으면어디서 빠를까
- 레이스가 짧을수록 VO2max를 거의 다 쓴다
- 레이스 페이스가 VO2max의 몇 %인지
- VO2max 100%
- 약 98%
- 5km
- 엘리트 · 약 15분
- 약 87%
- 1시간 레이스
- 훈련된 러너
- 80~85%
- 마라톤
- 약 2~3시간
- 5~10km
- VO2max가 기록을 크게 좌우해요. 엘리트 5km 연구에서 기록 차이의 약 75%를 VO2max가 설명
- 하프 · 마라톤 · 하이록스
- VO2max는 천장 역할. 역치·이코노미·연료의 비중이 더 커져요
- 5km: 엘리트 8명 연구 · 1시간·마라톤: Bassett & Howley (2000) · 하이록스는 경기 시간 기준 추론

### 2편 07 엘리트 VO2max  (`E2-Elite.dc.html`)

- 엘리트얼마나 높을까
- 세계 최고 마라토너도 VO2max는 70~85
- 단위 ml/kg/min · 엘리트끼리는 VO2max만으로 순위가 안 갈려요
- 황영조
- 한국 · 1992 올림픽 금
- 84.5
- 이봉주
- 한국 · 1996 올림픽 은
- 78.6
- 케냐 세계적 선수 7명
- 평균 · 2022 학회 발표
- 75.9
- Breaking2 선수 16명
- 평균 · 킵초게 참가 프로젝트
- 71.0
- 폴라 래드클리프
- 여자 마라톤 前 세계기록
- 약 70
- 일반 20~30대 남성
- 참고
- 약 45
- 킵툼 · 케젤차 공개된 실측치가 없어요. 현역 여자 엘리트도 공개 자료가 드물어요. 킵초게도 개인 값은 공개되지 않았어요.
- 황영조·이봉주: 매일신문(2003) 보도, 원 측정 출처 미기재 · 케냐: ECSS(2022) · Breaking2: Jones et al. (2021) · 래드클리프: Jones (2006)

### 2편 08 중추 vs 말초 적응  (`E2-Adapt.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 훈련하면 몸에서 바뀌는 두 곳
- 중추
- 심장 · 혈액
- 한 번에 보내는 피(1회 박출량) ↑
- 혈액량(적혈구·혈장) ↑
- 최대심박은 거의 그대로
- VO2max를 직접 올림
- 말초
- 근육
- 모세혈관 ↑
- 미토콘드리아 ↑
- 산소를 꺼내 쓰는 능력 ↑
- 오래 버티는 힘(역치)에 큼
- 16주 훈련 연구VO2max가 오르는 동안 심박출량 +8%, 산소 추출은 +3.6%. 오른 몫은 심장 쪽이 두 배 넘게 컸어요.
- 피 빼기 실험6주 훈련으로 VO2max +9%. 늘어난 적혈구만큼 피를 빼자 훈련 전으로 돌아갔어요. 미토콘드리아는 +43%였는데도요.
- 그래서VO2max를 올리려면 심장을 최대 근처까지 쓰는 훈련. 그게 인터벌이에요.
- Bassett & Howley (2000) · Ekblom et al. (1968) 인용 · Montero et al. (2015) J Physiol, 비훈련 남성 16명

### 2편 09 무엇과 비교했나  (`E2-Meta.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 인터벌은 무엇보다 더 올렸나?
- 실험잘 훈련된 지구력 선수 41명 · 9주 · 시작 VO2max 평균 62.6
- 저강도 대량
- 쉬운 장거리 위주
- 변화 없음
- 역치 위주
- 역치 인터벌 위주
- 변화 없음
- 4×4 집중 블록
- 16일에 12회 × 2블록
- +4.8%
- 양극화
- 대부분 쉽게 + 주 2회 인터벌
- +11.7%
- 인터벌 27회 한 4×4 블록보다, 14회만 한 양극화가 더 올랐어요
- 메타분석무작위 대조 연구 53개 (Wen 2019)
- 비교 대상중강도로 쭉 달리기 (지속주)
- 결과2분+ 인터벌 · 회당 15분+ · 4~12주일 때만 지속주보다 더 올림. 짧고 적은 인터벌은 지속주보다 낫지 않았음
- 메타분석엘리트 선수 9개 연구 · 176명 (Ma 2023)
- 비교 대상엘리트의 기존 훈련 (지속주 · 저강도 대량 · 반복 스프린트)
- 결과인터벌이 더 올림. 효과 크기 0.58, 중간 정도
- Stöggl & Sperlich (2014) Front Physiol · Wen et al. (2019) J Sci Med Sport · Ma et al. (2023) Heliyon

### 2편 10 노르웨이 4x4  (`E2-Norway.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 노르웨이 4×4 인터벌
- 노르웨이 과학기술대(NTNU) 헬게루드·호프가 1990년대 엘리트 스포츠에 도입
- 워밍업 10분
- 4분
- 3분
- × 4세트
- 쿨다운 10분
- 4분: 최대심박 90~95% · 말 한마디도 힘든 강도
- 3분: 최대심박 70% 회복 조깅
- 왜 하필 4분?
- 심장이 최대에 닿는 데 2~3분. 4분이면 최대치 근처에서 1~2분을 버텨요.
- 8주 연구존2·역치 그룹은 VO2max 변화 미미, 4×4 그룹은 약 +7~8%, 심장이 한 번에 보내는 피도 늘었어요.
- Helgerud et al. (2007) Med Sci Sports Exerc, 중간 수준 훈련자 · NTNU 보도(2024)

### 2편 11 대표 처방 3  (`E2-Rx.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 대표 처방 3가지
- 셋 다 목표는 같아요: VO2max 근처에서 오래 머물기
- 1
- 노르웨이 4×4기본
- 4분 강하게 · 3분 회복 · 4세트
- 최대심박 90~95% · 가장 검증된 기본형
- 2
- 5×3분
- 3분 강하게 · 3분 회복 · 5세트
- VO2max 페이스의 95% · 1편 러너라면 약 4:13/km
- 3
- 30/15
- 30초 강 · 15초 약 × 13회 · 세트 간 3분 · 3세트
- 엘리트 사이클 선수 연구에서 긴 인터벌보다 효과
- Helgerud et al. (2007) · 1편 러너 VO2max 도달 4:00/km ÷ 0.95 = 약 4:13 · Ronnestad et al. (2020) Scand J Med Sci Sports

### 2편 12 어떤 형식  (`E2-Format.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 어떤 형식이 최고일까? 아직 정답은 없다
- 러너 12명 · 2025같은 운동 시간, VO2max 90% 이상에 머문 시간
- 긴 인터벌
- 3분 × 4세트
- 5.5분
- 짧은 인터벌
- 30초 × 24회
- 3.4분
- 그런데 심박은 짧은 인터벌이 더 높게 나왔어요. 심박만 보면 속을 수 있어요.
- 19개 연구 종합 · 2026어떤 인터벌 구조도 확실히 우월하지 않았어요.
- 4×4 논쟁 · 2024한 가지 방식만 고집하면 정체될 수 있다는 비판도 있어요.
- 결론끝까지 지킬 수 있는 형식으로, 최대치 근처 시간을 쌓으세요.
- Fleckenstein et al. (2025) Front Sports Act Living · Held et al. (2026) BMC Sports Sci Med Rehabil · NTNU 보도(2024)

### 2편 13 빈도와 구성  (`E2-Frequency.dc.html`)

- 바꿀 수 있는 것 ②훈련
- 강하게는 가끔, 나머지는 쉽게
- 약 80% 쉽게
- 20%
- 엘리트 지구력 선수 훈련의 강도 분포
- 일주일 예시
- 월쉽게
- 화인터벌
- 수쉽게
- 목쉽게
- 금인터벌 선택
- 토롱런 · 쉽게
- 일휴식
- 주 1~2회 VO2max 인터벌이면 충분해요
- 강한 날 사이에는 최소 하루 쉬운 날
- 4~12주 꾸준히 → 그다음 회복 주
- 강도만 더 올린다고 이미 훈련된 사람이 계속 좋아진다는 근거는 약해요
- Seiler (2010) Int J Sports Physiol Perform · 기간: Wen et al. (2019) · 일주일 구성은 예시

### 2편 14 정리  (`E2-Wrap.dc.html`)

- 정리 VO2max는 심장이 정한다
- 원리VO2max = 심장이 뿜는 피 × 근육의 산소 추출엘리트와 일반인의 차이는 심장에서 나와요 최대 심박출량 34 vs 21 L/분 · 근육의 산소 추출은 비슷
- 타고나는 것유전 · 성별 · 나이개인차의 약 60~70%가 유전 · 남녀 차이 약 10% 나이 들면 10년에 −12%, 훈련을 이어가면 −5.5%
- 바꿀 수 있는 것 ①체지방산소 4.2L 그대로 80→70kg이면 52.5→60 (+14%) 근육까지 빠지면 산소량 자체가 줄어요
- 바꿀 수 있는 것 ②심장이 뿜는 양을 키우는 훈련처음엔 혈액량, 길게는 심장 자체가 바뀌어요 · 4×4 8주 +7.2% VO2max 90% 이상 머문 시간이 핵심 · 주 1~2회, 나머지는 쉽게
- 한계VO2max만으로 기록이 정해지진 않아요5km는 VO2max의 약 98%, 마라톤은 80~85%로 달려요 엘리트끼리는 러닝 이코노미와 역치가 차이를 만들어요
- 결론
- 절반 넘게 타고나지만, 심장이 뿜는 양은 훈련으로 커진다
- 확인은 시계 VO2max(오차 7~8%)보다 8주 전후 같은 코스 5km 기록으로
- Zhou 2001 · Schutte 2016 · Rogers 1990 · Helgerud 2007 · Montero 2015 · Bassett & Howley 2000

### 2편 15 참고문헌  (`E2-Refs.dc.html`)

- 참고문헌
- 1Bassett DR, Howley ET (2000) Limiting factors for maximum oxygen uptake and determinants of endurance performance. Med Sci Sports Exerc
- 2Schutte NM et al. (2016) Twin-sibling study and meta-analysis on the heritability of maximal oxygen consumption. Physiol Genomics
- 3Klissouras V (1971) Heritability of adaptive variation. J Appl Physiol
- 4Bouchard C et al. (1999) Familial aggregation of VO2max response to exercise training: HERITAGE. J Appl Physiol
- 5Senefeld JW et al. (2021) Sex-based limits to running speed in the human, horse and dog. FASEB J
- 6Rogers MA et al. (1990) Decline in VO2max with aging in master athletes and sedentary men. J Appl Physiol
- 7Lucia A et al. (2006) Physiological characteristics of the best Eritrean runners: exceptional running economy. Appl Physiol Nutr Metab
- 8The effect of VO2max percent utilization at 5km competition among elite distance runners (엘리트 8명)
- 9Jones AM (2006) The physiology of the world record holder for the women's marathon. Int J Sports Sci Coach
- 10Jones AM et al. (2021) Physiological demands of running at 2-hour marathon race pace. J Appl Physiol
- 11Physiological characteristics of world-class Kenyan runners (2022) ECSS Congress
- 12매일신문 (2003.5.16) 마라톤은 과학스포츠의 대명사
- 13Wen D et al. (2019) Effects of different protocols of HIIT for VO2max improvements in adults. J Sci Med Sport
- 14Ma X et al. (2023) VO2max in elite athletes under high-intensity interval training: a meta-analysis. Heliyon
- 15Helgerud J et al. (2007) Aerobic high-intensity intervals improve VO2max more than moderate training. Med Sci Sports Exerc
- 16Ronnestad BR et al. (2020) Short intervals induce superior training adaptations compared with long intervals in cyclists. Scand J Med Sci Sports
- 17Fleckenstein D et al. (2025) Faster intervals, faster recoveries. Front Sports Act Living
- 18Held S et al. (2026) Comparison of HIIT protocol designs on accumulated time ≥90% VO2max: network meta-analysis. BMC Sports Sci Med Rehabil
- 19Seiler S (2010) What is best practice for training intensity and duration distribution in endurance athletes? Int J Sports Physiol Perform
- 20Norwegian SciTech News (2024) 4x4 interval training popular and controversial
- 21Zhou B et al. (2001) Stroke volume does not plateau during graded exercise in elite male distance runners. Med Sci Sports Exerc
- 22Ekblom B et al. (1968) Effect of training on circulatory response to exercise. J Appl Physiol
- 23Stoggl T, Sperlich B (2014) Polarized training has greater impact on key endurance variables. Front Physiol
- 24Montero D et al. (2015) Haematological rather than skeletal muscle adaptations contribute to the increase in peak oxygen uptake induced by moderate endurance training. J Physiol

### 2편 16 다음 편 예고  (`E2-EliteLesson.dc.html`)

- 다음 편 예고엘리트의 비밀
- VO2max는 그대로였는데 세계기록을 세웠다
- 폴라 래드클리프 · 18세(1992) → 29세(2003) 추적
- 19922003
- VO2max약 70→약 70그대로
- 러닝 이코노미205→175−15%
- 역치(LT2) 속도16→20km/h ↑
- Breaking22시간 마라톤 도전 선수 16명의 VO2max는 연구진 예상보다 높지 않았어요. 핵심은 세 요소의 조합이었어요.
- 다음 편VO2max가 아니라면, 무엇이 기록을 바꿨을까? 러닝 이코노미와 젖산역치에서 이어갈게요.
- Jones (2006) Int J Sports Sci Coach · Jones et al. (2021) J Appl Physiol · 이코노미 단위 ml/kg/km(16km/h)


## 3편

### 3편 00 훅  (`E3-Hook.dc.html`)

- 러닝 3요소 · 3편
- 똑같이 달려도 누구는 덜 지친다, 러닝 이코노미
- VO2max도 체중도 같은 두 러너, 같은 6:00 페이스에서 쓰는 산소가 10% 달랐어요.
- 러너 A
- 240
- ml/kg/km · 1km에 드는 산소
- vs
- 러너 B
- 264
- ml/kg/km · 1km에 드는 산소
- 예시값 · 1편 비교 러너 (1분 산소 40 vs 44 × 6분)

### 3편 01 4%의 탄생  (`E3-History.dc.html`)

- 시작4%의 탄생
- 러닝 이코노미가 유명해진 순간
- 1980
- 개념은 40년도 더 됐어요
- VO2max가 비슷한 엘리트끼리 10km 기록을 가른 건 이코노미였다는 연구
- 2017.5
- 브레이킹2 · 킵초게 2:00:25
- 나이키가 2시간 벽을 깨려고 만든 이벤트 (비공인)
- 2017.7
- 베이퍼플라이 4% 출시
- 이름의 4% = 연구에서 에너지 소비가 평균 4% 줄었다는 뜻
- 2019.10
- 1:59:40 · 알파플라이 시제품
- 사상 첫 2시간 이내 마라톤 (비공인)
- 2020.1
- 세계육상연맹 신발 규정
- 밑창 40mm 이하 · 판 1장 · 출시 4개월 지난 신발만
- 신발개념은 오래됐지만, 대중에게 알린 건 신발이었어요.
- Conley & Krahenbuhl (1980) · CU Boulder 보도(2017.11) · NPR(2020.1) · 날짜는 공식 발표 기준

### 3편 02 4%의 진짜 의미  (`E3-FourPct.dc.html`)

- 시작4%의 진짜 의미
- 4% 덜 쓴다 ≠ 4% 빨라진다
- 실험 · 2017 수준 높은 러너 18명 · 14·16·18 km/h · 무게 맞춘 신발 3켤레
- 기존 레이싱화 A
- 17.16 W/kg
- 기존 레이싱화 B
- 17.14 W/kg
- 시제품 (베이퍼플라이)
- 16.45 W/kg · −4%
- 18명 전원 에너지가 줄었어요 · 사람마다 2~6%
- 엘리트로 환산하면
- 에너지 −4% → 속도 +3.4%
- 2:02:57 → 1:58:54 (예측)
- 느린 러너일수록 시간 이득이 커요
- 이코노미 1% 개선 시
- 2:03 러너 47초 · 4:30 러너 3분 7초
- 이 실험은 나이키가 연구비를 댔고, 책임 연구자가 나이키 자문위원이었어요. 이후 독립 연구들도 효과는 확인했지만 크기는 사람마다 달랐어요.
- 3.4%에너지가 4% 줄어도 속도는 그보다 덜 빨라져요. 빨리 달릴수록 공기 저항이 커지기 때문이에요.
- Hoogkamer et al. (2018) Sports Med · Kipp, Kram & Hoogkamer (2019) Front Physiol

### 3편 03 러닝 이코노미란 · 측정법  (`E3-Def.dc.html`)

- 개념러닝 이코노미란
- 같은 페이스로 쭉 달릴 때 1km에 드는 산소
- 자동차로 치면 연비 · 단위 ml/kg/km · 낮을수록 좋아요
- 0
- 20
- 40
- 0
- 1
- 2
- 3
- 4
- 5
- 6
- 시간 (분)
- 산소섭취량 (ml/kg/min)
- 예시 데이터
- 40
- 안정된 구간 평균
- 1km 6:00 페이스 고정 · 6분 내내 같은 페이스로
- 호흡마다 측정한 값
- 평균 추세
- 논문은 이렇게 잰다
- 같은 사람을 다시 재도 1.3~5% 흔들려요
- 1러닝머신 경사 1%
- 야외에서 받는 공기 저항만큼 비용을 맞추려고
- 2역치보다 느린 속도 · 단계당 3~5분
- 산소가 안정될 때까지 · 역치를 넘으면 젖산이 쌓여 산소로 다 못 재요
- 3마스크로 마지막 1~2분 평균
- 그래프의 초록 구간 · 같은 시간대·식사·신발로 통제
- 4× 1km 걸린 시간 = ml/kg/km
- 40 × 6분 = 240 · 최신 연구는 kcal/kg/km로도 표시
- Jones & Doust (1996) J Sports Sci · Barnes & Kilding (2015) Sports Med Open · 시계는 산소를 재지 않아 이코노미를 직접 알 수 없어요

### 3편 04 래드클리프 11년  (`E3-EliteCases.dc.html`)

- 엘리트 사례래드클리프 11년
- VO2max는 그대로, 러닝 이코노미만 15% 좋아졌다
- 폴라 래드클리프 · 2003.4.13 런던 마라톤
- 2:15:25
- 여자 마라톤 세계기록 · 2019년까지 16년 유지 18세(1992)부터 매년 측정한 기록의 끝이 바로 이 해 사진은 2005 런던 마라톤
- VO2max
- 70
- 71
- 67
- 69
- 75
- 70
- ≈ 70 그대로
- 러닝 이코노미
- 16km/h · ml/kg/km · 낮을수록 좋음 · 축은 160부터
- 205
- 1992
- 195
- 1994
- 185
- 1996
- 185
- 1998
- 180
- 2001
- 175
- 2003
- −15%
- 같은 산소로 더 빨리 → VO2max 때 속도 20.5 → 23.5 km/h
- Jones (2006) Int J Sports Sci Coach 그림 3·4·5 수치로 다시 그림 · 경사 1% · 16km/h · 대표값 · 사진: yaaaay (CC BY 2.0, Wikimedia Commons)

### 3편 05 래드클리프 무엇이 바뀌었나  (`E3-Radcliffe2.dc.html`)

- 엘리트 사례무엇이 바뀌었나
- 몸은 그대로, 달리는 속도의 기준이 바뀌었다
- 12
- 14
- 16
- 18
- 20
- 22
- 24
- 속도 (km/h) · 오른쪽일수록 빠름
- 젖산역치
- 젖산이 쌓이기 시작
- 14~15
- 17.5~18.5
- 젖산 전환점
- 젖산이 급히 오르는 지점
- 16
- 20
- 젖산 3mM 속도
- 같은 피로도의 속도
- 16
- 21
- VO2max 때 속도
- 산소 천장에서의 속도
- 20.5
- 23.5
- 1992
- 2003
- 체중 약 54kg → 약 54kg 그대로
- 그 사이 바뀐 훈련
- 주간 거리18세 때 주 40~48km 미만 → 마라톤 훈련기 주 193~257km
- 근력주 2회 웨이트 · 수직점프 29cm(1996) → 38cm(2003)
- 고지대훈련 상당 부분을 고지대에서
- 본인 말코어 안정성 · 메디신볼 · 웨이트 (2020 인터뷰) · 물리치료사 Gerard Hartmann과 폭발력 훈련 보강 (2002)
- 1명 사례 · 저자도 원인을 하나로 꼽기 어렵다고 했어요 · 2003년 이후 이코노미는 165까지 더 좋아졌어요
- Jones (2006) 그림 6 · 본문 · Sports Illustrated (2002) · Coventry Telegraph (2020)

### 3편 06 무엇이 정하나  (`E3-Factors.dc.html`)

- 구조무엇이 정하나
- 타고난 몸 vs 바꿀 수 있는 3가지
- 타고난 몸
- 바꾸기 어려워요
- 가는 종아리와 발목체중이 아니라 다리 끝이 가벼운 것 · 발에 100g ≈ +1% (실험으로 확인)
- 긴 정강이 · 체형엘리트 비교에서 함께 나타남 · 원인인지는 몰라요
- 발 크기 · 아킬레스 구조이코노미와 뚜렷한 관련 없음 · 연구마다 결과가 반대
- ① 훈련
- 근력 · 점프 훈련메타분석에서 확인 · 2~8%
- 빠른 질주 + 충분한 휴식4주에 산소 6~8% 감소
- 수년의 누적정황 증거
- ② 장비
- 신발평균 약 4% · 사람마다 다름 · 100g 무거우면 약 1% 손해
- ③ 체중
- 체지방몸통에 1kg 더하면 약 1% 더 듦
- 왜 유리할까 달릴 때 에너지는 ① 몸을 받쳐 올리고 ② 다리를 앞뒤로 휘두르는 데 쓰이고, ③ 힘줄 스프링이 일부를 돌려줘요(타고난 모양보다 훈련으로 단단해지는 쪽). 다리 끝이 가벼우면 ②가 줄고(망치 끝을 잡고 휘두르면 더 힘든 것과 같아요), 힘줄이 잘 늘었다 튕기면 ③이 늘어요. 단, 체형 연구는 상관이지 원인 증명이 아니에요.
- Barnes & Kilding (2015) · Myers & Steudel (1985) · Coifman et al. (2024) · van Werkhoven & Piazza (2017) · Lucia et al. (2006) · Llanos-Lagos et al. (2024) · Iaia et al. (2008) · Albracht & Arampatzis (2013) 사진: Wikimedia Commons · Tiia Monto, Bob Ramsak, LexSprinter, Hjfm 003, franchise opportunities (CC BY-SA) · yaaaay (CC BY 2.0) · 미 육군, Gray's Anatomy (퍼블릭 도메인)

### 3편 07 폼 교정  (`E3-Form.dc.html`)

- 흔한 오해 ①폼을 고치면 될까?
- 자세가 설명하는 건 개인차의 4~12%뿐
- 메타분석 · 2024 연구 51편 · 1,115명 · 러닝 이코노미와 얼마나 관련 있나
- 수직 진폭
- 작을수록 좋음 · 중간
- 다리 강성
- 착지 때 덜 꺾일수록 · 작음
- 케이던스
- 높을수록 약간 좋음 · 작음
- 접지 시간
- 관련 없음
- 착지법
- 뒤꿈치 = 앞꿈치
- 관련성 크기 (상관계수) · 사람끼리 비교한 결과
- 다리 강성, 세게 차면 될까?
- 아니에요. 세게 미는 힘이 아니라 착지 때 다리가 얼마나 덜 꺾이나예요. 연구실에서 재는 값이라 일반 러너가 따로 챙길 지표는 아니에요.
- 케이던스 180이 정답?
- 180은 1984 올림픽 엘리트를 레이스 페이스에서 센 숫자예요. 연구는 같은 속도에서 지금보다 5~10%를 봤어요. 160이면 168~176 · +5% 무릎, +10% 무릎·엉덩이 부담↓ (부상 관점)
- 그대로대부분 이미 내 몸에 맞는 보폭으로 달려요. 억지로 바꾸면 적응하는 동안 오히려 손해예요.
- Van Hooren et al. (2024) Sports Med · Moore (2016) · Daniels (1984 LA 올림픽 관찰) · Heiderscheit et al. (2011) Med Sci Sports Exerc

### 3편 08 마일리지  (`E3-Mileage.dc.html`)

- 흔한 오해 ②많이 뛰면 오를까?
- 몇 주로는 안 오르고, 몇 년이면 오를 가능성이 커요
- 6주
- 개선 없음
- 단기 훈련 실험 (1996) · 일반 남자 러너 15명
- VO2max는 57.7 → 61.3으로 올랐는데 이코노미는 좋아지지 않았어요. 느린 측정 속도에선 오히려 나빠졌는데, 저자도 "빨라진 몸엔 너무 느린 속도라 브레이크 걸린 듯 뛴 것"일 수 있다고 봤어요
- 수개월
- 제각각
- 장기 추적 연구들
- 변화 없음부터 1~15% 개선까지 결과가 엇갈려요
- 수년
- 관련 있음
- 경력·사례 연구
- 훈련 경력(년)과 이코노미 상관 r = 0.62 · 래드클리프 11년 −15%
- 그런데 왜 "확실하다"고 못 할까?
- 1훈련량만 바꿔서 비교한 실험이 아직 없어요
- 2거꾸로일 수도 있어요. 원래 이코노미가 좋은 사람이 다치지 않고 오래, 많이 달릴 수 있는 걸지도요
- 바탕마일리지는 몇 년에 걸친 바탕이고, 몇 주 안에 바꾸는 건 근력·질주 쪽이에요.
- Lake & Cavanagh (1996) · Barnes & Kilding (2015) 리뷰 (Mayhew · Pate · Midgley 인용) · Jones (2006)

### 3편 09 근력 메타분석  (`E3-Strength.dc.html`)

- 바꿀 수 있는 것 ①근력 훈련
- 가볍게 많이 말고, 무겁게 적게 · 점프
- 메타분석 · 2024 중장거리 러너 652명 · 6~24주 · 주 1~4회 · 비교군: 러닝만
- 둘 이상 섞기
- 고중량 + 점프 등
- 중간 효과
- 플라이오 (점프)
- 작은 효과
- 고중량
- 1RM 80% 이상
- 작은 효과
- 중간 무게
- 1RM 40~79%
- 효과 없음
- 등척성 (버티기)
- 효과 없음
- 효과 크기: 혼합 0.43 · 플라이오 0.31 · 고중량 0.27 · 근거 수준 중간 (혼합은 낮음)
- 고중량
- 8.6~17.9km/h에서 효과 빠를수록 · VO2max 높을수록 ↑
- 플라이오
- 12km/h 이하 느린 속도에서 효과
- 혼합
- 10~14.5km/h에서 가장 큰 효과
- 대상: 중간 수준 195명 · 잘 훈련된 272명 · 고도로 훈련된 185명
- Llanos-Lagos et al. (2024) Sports Med 54(4):895-932 · 개별 연구 범위 약 2~8%

### 3편 10 근력 처방  (`E3-StrengthRx.dc.html`)

- 바꿀 수 있는 것 ①실제 처방 연구
- 연구에서 효과 본 3가지
- 1하프 스쿼트
- 4세트 × 4회(최대) · 세트 사이 3분 · 주 3회 · 8주 천천히 내려가 1초 멈춤 → 최대한 빠르게 일어서기
- 이코노미 +5% · VO2max 속도 버티기 +21%
- 훈련된 러너 17명 · 체중·VO2max 변화 없음 · Støren 2008
- 2플라이오메트릭
- 제자리 발목 점프·바운딩처럼 착지 즉시 튀어 오르기 30분 · 주 3회 · 9주
- 18km/h에서 이코노미 +4.1%
- VO2max 71 엘리트 15명 · Saunders 2006
- 3종아리 등척성
- 고정된 저항을 발끝으로 최대 힘으로 3초 밀기 4회 × 5세트 · 14주
- 힘줄 강성 +16% · 이코노미 약 4%
- 26명 · Albracht & Arampatzis 2013
- 단, 메타분석에선 등척성 전체 효과가 뚜렷하지 않았어요
- Støren et al. (2008) Med Sci Sports Exerc · Saunders et al. (2006) J Strength Cond Res · Albracht & Arampatzis (2013) Eur J Appl Physiol · 사진은 동작 예시(3번 연구는 움직이지 않고 미는 등척성) · 사진: 미 해병대·미 육군(퍼블릭 도메인), GeorgeStepanek (CC BY-SA 3.0), Wikimedia Commons

### 3편 11 질주 훈련  (`E3-Speed.dc.html`)

- 바꿀 수 있는 것 ②질주 훈련
- 30초 질주 + 3분 휴식, 4주에 산소 6~8% 덜 썼다
- 실험 · 2008 훈련된 러너 17명 · 평소 훈련(주 45km)을 바꿈
- 평소 주 45km
- →30초 질주 8~12회 · 사이 3분 휴식 + 쉬운 러닝 · 총 주 15.6km
- 같은 속도에서 쓰는 산소 변화
- 11 km/h
- −6.6%
- 13 km/h
- −7.6%
- 14.5 km/h
- −5.7%
- 16 km/h
- −6.4%
- 믿을 만한가?
- 근거가 되는 점
- 같은 연구팀 후속 연구(2009, 12명)에서도 훈련량 25% 줄이고 30초 질주를 넣었더니 10km 37.3 → 36.3분
- 조심할 점
- 훈련량을 줄여 피로가 빠진 효과(테이퍼)일 수 있어요 · 17명·4주 소규모 · 2008년엔 10km 기록과 VO2max는 그대로
- Iaia et al. (2008) J Appl Physiol · Bangsbo et al. (2009) J Appl Physiol · Franch et al. (1998)

### 3편 12 신발  (`E3-Shoes.dc.html`)

- 바꿀 수 있는 것 ③신발
- 평균은 4%, 하지만 내 발엔 0%일 수도
- 실험 · 2023 카본화로 바꿨을 때 러닝 이코노미 변화
- ← 손해0이득 →
- 케냐 정상급 7명
- 하프 평균 59분 30초
- -11.3%+11.4%
- 유럽 아마추어 7명
- -1.1%+9.7%
- 세계 정상급 선수 중에도 오히려 11% 손해 본 사람이 있었어요
- 독립 연구 종합 · 2025
- 교차 실험 17개 · 281명 산소 사용 감소 (작음~중간)
- 무게도 이코노미
- 신발 100g 무거우면 약 1% 손해
- Knopp et al. (2023) Sports Med · 신발 메타분석 (2025) Int J Sports Med · Barnes & Kilding (2015) · 레이스 신발은 직접 신어보고 레이스 페이스로 미리 달려보세요

### 3편 13 내구성  (`E3-Durability.dc.html`)

- 최신 연구피곤해도 유지되나
- 같은 페이스인데 90분째엔 산소가 더 든다
- 러닝 이코노미는 보통 "쌩쌩할 때" 재요. 그런데 레이스 후반엔 달라요.
- 2024 훈련된 남성 44명 · 편안한 강도(LT1)로 90분 · 같은 속도에서 드는 에너지
- 시작
- 45분
- 90분
- 0%
- +2%
- +4%
- 하위권(10km 41분대) +4.3%
- 상위권(10km 31분대) +2.3%
- 잘 달리는 사람일수록 이코노미가 덜 무너졌어요 = 이걸 "내구성"이라고 불러요
- 에너지로 재든 산소로 재든 거의 같아요: 90분째 산소 사용 +2.4% vs +4.5% (같은 페이스인데 산소가 그만큼 더 든다는 뜻)
- 하이록스라면1km 달리기 8번을 스테이션 사이에 해요. 쌩쌩할 때 이코노미보다 지친 상태의 이코노미가 기록을 정해요. (코치 해석 · 하이록스 직접 연구는 아직 없음)
- Zanini, Folland & Blagrove (2024) Med Sci Sports Exerc · 그래프는 시작과 90분 값을 직선으로 이은 것

### 3편 14 팩트체크  (`E3-FactCheck.dc.html`)

- 이코노미 팩트 체크
- 맞아요
- 근력운동이 이코노미를 올린다
- 메타분석에서 확인 · 고중량·점프·혼합
- 애매해요
- 케이던스 180이 정답
- 높을수록 약간 좋지만 모두에게 맞는 숫자는 없음
- 많이 뛰는 게 유일한 답
- 수년 누적은 정황 증거 · 근력·질주도 효과
- 슈퍼슈즈는 누구나 4%
- 평균은 맞지만 개인차 −11~+11%
- 근거 없어요
- 폼·착지법을 바꿔야 한다
- 자세는 개인차의 4~12% · 착지법 차이 없음
- 접지 시간을 줄이면 좋아진다
- 관련 없음 (r = −0.02)
- 호흡을 2:1로 맞추면 좋아진다
- 직접 근거를 찾지 못함
- 아마추어는 신발 효과가 작다
- 느린 러너일수록 줄어드는 시간이 더 커요(이론)
- Van Hooren (2024) · Llanos-Lagos (2024) · Barnes & Kilding (2015) · Knopp (2023) · Kipp (2019)

### 3편 15 정리  (`E3-Wrap.dc.html`)

- 정리 러닝 이코노미는 폼이 아니라 몸이 만든다
- 원리이코노미 = 1km 가는 데 드는 산소낮을수록 좋음 · 역치 아래 속도에서 산소로 측정
- 엘리트VO2max가 아니라 러닝 이코노미, 젖산 역치래드클리프 11년 −15% (VO2max 그대로) → 2003년 2:15:25 세계기록
- 오해폼 교정 · 착지 · 접지 시간자세는 개인차의 4~12% · 억지로 바꾸면 오히려 손해
- 확실한 것근력 · 점프 · 빠른 질주 + 충분한 휴식고중량·플라이오·혼합 2~8% · 30초 질주 4주에 6~8%
- 조건부신발 · 수년의 누적 훈련신발은 평균 4%, 개인차 큼 · 마일리지는 수년 단위 정황 증거
- 결론
- 신발이 4%를 줄 수는 있어도, 러닝 이코노미는 근력·속도·시간이 만든다
- 하이록스는 지친 상태의 이코노미 싸움 · 근력과 스트라이드를 주 1~2회 꾸준히
- Hoogkamer 2018 · Jones 2006 · Van Hooren 2024 · Llanos-Lagos 2024 · Iaia 2008 · Knopp 2023 · Zanini 2024

### 3편 16 참고문헌  (`E3-Refs.dc.html`)

- 참고문헌
- 1Conley DL, Krahenbuhl GS (1980) Running economy and distance running performance of highly trained athletes. Med Sci Sports Exerc
- 2Hoogkamer W et al. (2018) A comparison of the energetic cost of running in marathon racing shoes. Sports Med
- 3Kipp S, Kram R, Hoogkamer W (2019) Extrapolating metabolic savings in running: implications for performance predictions. Front Physiol
- 4Hoogkamer W, Kram R, Arellano CJ (2017) How biomechanical improvements in running economy could break the 2-hour marathon barrier. Sports Med
- 5Barnes KR, Kilding AE (2015) Running economy: measurement, norms, and determining factors. Sports Med Open
- 6Barnes KR, Kilding AE (2015) Strategies to improve running economy. Sports Med
- 7Lucia A et al. (2006) Physiological characteristics of the best Eritrean runners: exceptional running economy. Appl Physiol Nutr Metab
- 8Jones AM et al. (2021) Physiological demands of running at 2-hour marathon race pace. J Appl Physiol
- 9Jones AM (2006) The physiology of the world record holder for the women's marathon. Int J Sports Sci Coach
- 10Van Hooren B et al. (2024) The relationship between running biomechanics and running economy: a systematic review and meta-analysis. Sports Med
- 11Moore IS (2016) Is there an economical running technique? A review of modifiable biomechanical factors affecting running economy. Sports Med
- 12Lake MJ, Cavanagh PR (1996) Six weeks of training does not change running mechanics or improve running economy. Med Sci Sports Exerc
- 13Llanos-Lagos C et al. (2024) The effect of strength training methods on middle-distance and long-distance runners' running economy. Sports Med
- 14Storen O et al. (2008) Maximal strength training improves running economy in distance runners. Med Sci Sports Exerc
- 15Saunders PU et al. (2006) Short-term plyometric training improves running economy in highly trained middle and long distance runners. J Strength Cond Res
- 16Albracht K, Arampatzis A (2013) Exercise-induced changes in triceps surae tendon stiffness and muscle strength affect running economy. Eur J Appl Physiol
- 17Iaia FM et al. (2008) Four weeks of speed endurance training reduces energy expenditure during exercise. J Appl Physiol
- 18Franch J et al. (1998) Improved running economy following intensified training correlates with reduced ventilatory demands. Med Sci Sports Exerc
- 19Knopp M et al. (2023) Variability in running economy of Kenyan world-class and European amateur male runners with advanced footwear. Sports Med
- 20Effects of advanced footwear technology on running economy and endurance performance: a meta-analysis (2025) Int J Sports Med
- 21Zanini M, Folland JP, Blagrove RC (2024) Durability of running economy. Med Sci Sports Exerc
- 22Hunter B, Muniz-Pumares D (2025) Durability of parameters associated with endurance running in marathoners. Eur J Sport Sci
- 23Jones AM, Doust JH (1996) A 1% treadmill grade most accurately reflects the energetic cost of outdoor running. J Sports Sci
- 24Weston AR, Mbambo Z, Myburgh KH (2000) Running economy of African and Caucasian distance runners. Med Sci Sports Exerc
- 25Morin JB et al. (2005) A simple method for measuring stiffness during running. J Appl Biomech
- 26Heiderscheit BC et al. (2011) Effects of step rate manipulation on joint mechanics during running. Med Sci Sports Exerc
- 27Bangsbo J et al. (2009) Reduced volume and increased training intensity elevate muscle Na+-K+ pump alpha2-subunit expression as well as short- and long-term work capacity in humans. J Appl Physiol
- 28CU Boulder Today (2017.11) New shoe makes running 4 percent easier · NPR (2020.1) Track's governing body sets new rules for shoes

### 3편 17 다음 편 예고  (`E3-Next.dc.html`)

- 다음 편 예고젖산역치
- 엔진도 같고 연비도 같은데, 마라톤 후반에 갈리는 이유
- 1편에서 본 두 개의 역치
- LT1 · 5:43/km
- LT2 · 4:42/km
- 편하게 오래
- 젖산이 안정 수준
- 버틸 수 있는 구간
- 젖산이 조금씩 오름
- 빠르게 지침
- 젖산이 계속 쌓임
- 7:30
- 6:30
- 5:43
- 5:00
- 4:42
- 4:00
- 예시 데이터
- 1km 페이스 (분:초) · 오른쪽일수록 빠름
- 혈중 젖산 →
- Breaking2 후보들
- VO2max의 92%까지
- 젖산이 급격히 쌓이기 전까지 버틴 지점 (평균)
- 마라토너 90분 뒤
- 역치 속도 −5.5%
- 덜 떨어진 사람이 더 빨랐어요
- 4편에서 다룰 것
- LT1젖산이 처음 오르는 지점 · 존2의 진짜 기준
- LT2젖산이 급격히 쌓이는 지점 · 하이록스 페이스의 천장
- 훈련역치는 어떻게 올리나
- Jones et al. (2021) J Appl Physiol · Hunter & Muniz-Pumares (2025) Eur J Sport Sci


## 3편 재구성안

### 재구성 00 훅 · 더 좋은 이코노미 곡선으로  (`E3R-Hook.dc.html`)

- 러닝 3요소 · 3편 · 러닝 이코노미
- 이코노미가 더 좋은 그래프로 이동하려면 어떻게 해야 할까?
- 지금이코노미가 좋아진 나
- 40
- 50
- 60
- VO2max 60 · 엔진은 그대로
- 4:24
- 4:00
- 같은 6:00 페이스에서
- 산소 44 → 40 (−9%)
- 7:30
- 6:00
- 5:00
- 4:00
- 1km 페이스 · 오른쪽일수록 빠름
- 1분 산소 (ml/kg)
- 아래 곡선일수록 같은 페이스에 산소를 덜 써요
- 예시 그래프 · 1편 비교 값 (1km에 드는 산소 264 → 240 ml/kg/km) · VO2max 60 동일 · 세로축은 30부터

### 재구성 01 러닝 이코노미란  (`E3R-Def.dc.html`)

- 개념러닝 이코노미란
- 같은 페이스로 달릴 때 1km에 드는 산소
- 자동차로 치면 1km에 드는 연료 · 낮을수록 좋아요
- 0
- 20
- 40
- 0
- 1
- 2
- 3
- 4
- 5
- 6
- 시간 (분)
- 산소 (ml/kg/분)
- 40
- 안정된 구간
- 1km 6:00 페이스 고정 · 6분 동안
- 예시 데이터
- 40 × 6분 = 240 ml/kg/km
- Barnes & Kilding (2015) Sports Med Open · 그래프는 예시 데이터

### 재구성 02 논문은 이렇게 잰다  (`E3R-Measure.dc.html`)

- 개념논문은 이렇게 잰다
- 러닝 이코노미는 이렇게 재요
- 1러닝머신 경사 1%
- 야외 공기 저항만큼 비용을 맞추려고
- 2역치보다 느린 속도로 3~5분씩
- 산소가 안정된 마지막 1~2분을 평균
- 3× 1km 걸린 시간 = ml/kg/km
- 요즘은 kcal/kg/km로도 표시해요
- 다시 재도 약 2~3% 흔들려요. 시계는 산소를 재지 않아요.
- Jones & Doust (1996) J Sports Sci · Saunders et al. (2004) Med Sci Sports Exerc · Barnes & Kilding (2015) Sports Med Open

### 재구성 03 왜 중요할까  (`E3R-Why.dc.html`)

- 개념왜 중요할까
- VO2max·역치·이코노미, 셋이 기록을 만든다
- 엔진
- VO2max
- ×
- 버티는 비율
- 젖산역치
- ÷
- 1km 연료
- 이코노미
- =
- 결과
- 속도
- 모델 계산VO2max 60 · 역치 85%로 같은 러너
- 이코노미 240
- 4:42
- 10% 좋아지면 216
- 4:14
- 역치 페이스가 1km에 약 28초 빨라져요
- 모델로 보면 빠를수록 덜 바뀌어요 (엘리트 속도에선 약 2/3)
- Joyner (1991) J Appl Physiol 모델 · Kipp, Kram & Hoogkamer (2019) Front Physiol · 페이스 = 이코노미 ÷ 역치 산소 51

### 재구성 04 래드클리프 2:15:25  (`E3R-Radcliffe.dc.html`)

- 엘리트 사례래드클리프
- 11년 동안 실험실에서 추적한 세계기록 보유자
- 폴라 래드클리프
- 2:15:25
- 2003.4.13 런던 마라톤
- 여자 마라톤 세계기록 · 16년 유지
- 18세(1992)부터 거의 매년 VO2max와 이코노미를 쟀어요
- Jones (2006) Int J Sports Sci Coach · World Athletics · 사진: 2005 런던 마라톤, yaaaay (CC BY 2.0, Wikimedia Commons)

### 재구성 05 래드클리프 11년 그래프  (`E3R-RadcliffeChart.dc.html`)

- 엘리트 사례래드클리프 11년
- VO2max는 그대로, 이코노미는 15%↓
- VO2max (ml/kg/분)
- 70
- 71
- 67
- 69
- 75
- 70
- ≈ 70 그대로
- 1km에 드는 산소 · 16km/h · ml/kg/km · 축은 160부터
- 205
- 1992
- 195
- 1994
- 185
- 1996
- 185
- 1998
- 180
- 2001
- 175
- 2003
- −15%
- 같은 산소로 더 빨리: VO2max 속도 20.5 → 23.5km/h
- Jones (2006) 그림 3·4·5 수치로 다시 그림 · 대표값 · 본문엔 18세 VO2max 72

### 재구성 06 래드클리프 무엇이 바뀌었나  (`E3R-Radcliffe2.dc.html`)

- 엘리트 사례무엇이 바뀌었나
- 체중은 54kg 그대로, 역치 속도는 +3.5km/h
- 젖산역치 속도
- 14~15
- →
- 17.5~18.5
- km/h
- 젖산 전환점
- 16
- →
- 20
- km/h
- 그 사이 바뀐 훈련
- 주간 거리40~48km 미만 → 약 193~257km
- 웨이트주 2회 정도 · 점프 29 → 38cm
- 고지대훈련 상당 부분을 고지대에서
- 몸체중 같음 · 키 5cm↑ · 더 말라짐
- 1명 사례 · 원인을 하나로 꼽기 어려워요
- Jones (2006) Int J Sports Sci Coach 본문·그림 6 · 1992 → 2003 (점프는 1996 → 2003) · 주간 거리는 마라톤 훈련기

### 재구성 07 타고난 몸  (`E3R-Factors.dc.html`)

- 구조타고난 몸
- 타고난 몸, 무엇이 진짜 유리할까
- 가는 종아리·발목무게 실험
- 다리 끝에 무게를 달면 비용↑ · 신발 한 짝 100g ≈ +1%
- 긴 정강이 · 체형상관
- 에리트레아 엘리트(7명)에서 길었지만 원인은 몰라요
- 뒤꿈치 · 힘줄 지렛대엇갈림
- 연구마다 결과가 반대예요
- 왜?다리를 휘두르는 비용이 줄어요. 망치도 끝을 잡고 휘두르면 더 힘들죠.
- Franz (2012) · Coifman (2024) · Lucia (2006) · Scholz (2008) · van Werkhoven & Piazza (2017) · 사진: Tiia Monto, Bob Ramsak (CC BY-SA 4.0) · Gray's Anatomy (퍼블릭 도메인)

### 재구성 08 바꿀 수 있는 4가지  (`E3R-Changeable.dc.html`)

- 구조바꿀 수 있는 것
- 바꿀 수 있는 4가지, 바탕부터 순서대로
- ① 러닝 마일리지 쌓기실험·사례
- 몇 주에도 조금, 크게는 몇 년
- ② 근력 · 점프(플라이오메트릭)메타분석
- 작음~중간 · 필수는 아님 · 업힐은 근거 약함
- ③ 신발실험
- 평균 약 2~4% · 사람마다 크게 달라요
- ④ 체지방무게 실험·추론
- 총 산소는 무게에 비례 · kg당 VO2max가 올라가요
- Franch 1998 · González-Mohíno 2020 · Jones 2006 · Llanos-Lagos 2024 · 신발 메타 2025 · Teunissen 2007 · 사진: yaaaay (CC BY 2.0) · 미 육군 (PD) · Hjfm 003, franchise opportunities (CC BY-SA)

### 재구성 09 러닝 마일리지 쌓기  (`E3R-Running.dc.html`)

- 핵심러닝 마일리지 쌓기
- 이코노미는 수년간의 마일리지와 함께 좋아져요
- 6주
- 결과가 엇갈려요실험
- 개선 없음(15명) vs 약 3% 좋아짐(36명)
- 11년
- 래드클리프 −15%사례
- 주 40~48km 미만 → 약 193~257km
- 엘리트
- 주 160~220km현장
- 엘리트 마라토너 · 80% 이상은 편한 강도로
- → 몇 주에도 조금, 크게는 몇 년 단위로
- Lake & Cavanagh (1996) · Franch et al. (1998) · González-Mohíno et al. (2020) · Jones (2006) · Haugen et al. (2022) Sports Med Open

### 재구성 10 왜 확실하다고 못 할까  (`E3R-Uncertain.dc.html`)

- 그런데확실하지 않은 이유
- 그런데 왜 “확실하다”고 못 할까?
- 1훈련량만 바꾼 장기 실험은 거의 없어요
- 6주 실험은 결과가 엇갈려요 (그대로 vs 약 3%↑)
- 2거꾸로일 수도 있어요
- 이코노미가 좋은 사람이 다치지 않고 많이 뛸 수 있어요
- 3많이 뛰는 사람은 다른 것도 달라요
- 경력·체형·근력… 비교 연구로는 못 가려요
- → “많이 뛰면 오른다”는 아직 관련(상관)이에요
- Lake & Cavanagh (1996) · Franch et al. (1998) · 2·3번은 비교 연구의 일반적인 한계

### 재구성 11 보조① 근력 · 점프  (`E3R-Strength.dc.html`)

- 보조 ①근력 · 점프
- 근력·점프 훈련, 몇 %를 더 얹는다
- 메타분석 2024중장거리 러너 652명 · 6~24주
- 두 가지 이상 섞기
- 예: 고중량 + 점프
- 중간 0.43
- 점프(플라이오)
- 12km/h 이하에서
- 작음 0.31
- 고중량
- 1RM 80% 이상
- 작음 0.27
- 중간 무게·버티기
- 1RM 40~79% · 등척성
- 효과 없음
- 필수는 아니에요. 효과는 몇 % 수준이에요
- Llanos-Lagos et al. (2024) Sports Med · 근거 확실성 중간 (섞기는 낮음) · 숫자는 효과 크기

### 재구성 12 근력 · 점프 실제 처방  (`E3R-StrengthRx.dc.html`)

- 보조 ①실제 처방
- 연구에서 효과 본 두 가지 처방
- 하프 스쿼트실험
- 무릎 90°까지 · 4회가 한계인 무게 4세트 · 주 3회 · 8주
- 이코노미 5% 좋아짐
- 17명(훈련 8 · 대조 9) · Støren 2008
- 점프(플라이오)실험
- 착지 즉시 튀어 오르기 30분 · 주 3회 · 9주
- 18km/h에서 4.1% 좋아짐
- 15명 · 느린 속도는 변화 없음
- Støren et al. (2008) Med Sci Sports Exerc · Saunders et al. (2006) J Strength Cond Res · 사진은 동작 예시: 미 해병대·미 육군 (퍼블릭 도메인)

### 재구성 13 보조② 업힐 인터벌 방법  (`E3R-Hills.dc.html`)

- 보조 ②업힐 인터벌 방법
- 경사 10%, 30초 × 10~14번
- 연구는 러닝머신 경사 10%로 했어요
- 10m ↑
- 100m 앞으로 → 10m 올라가요 (약 6°)
- 경사 10%
- 실제 비율로 그렸어요
- 30초 · VO2max 속도
- 30초 오르막 × 10~14회
- 1
- 10
- 14
- 회복: 심박이 최대의 65%로 내려올 때까지
- 업힐 인터벌 주 2회+ 45~60분 지속주 주 2회6주
- Ferley, Osborn & Vukovich (2014) J Strength Cond Res · 잘 훈련된 러너 32명 · 평지 그룹은 같은 속도로 4~6회 · 사진: Alastair Seagroatt (CC BY-SA 2.0, Wikimedia Commons)

### 재구성 14 업힐 인터벌 결과  (`E3R-HillsEvidence.dc.html`)

- 보조 ②업힐 인터벌 결과
- 세 그룹 모두 좋아졌어요 업힐만의 효과라 보긴 어려워요
- 실험 20146주 뒤, 같은 속도에서 드는 산소 변화
- −8.4%
- −8.6%
- 업힐
- −4.2%
- −4.1%
- 평지
- −6.8%
- −8.1%
- 하던 대로
- 역치 속도의 60%에서
- 80%에서 · 아래로 길수록 산소↓
- 실험 2013업힐 강도 5가지 · 가장 높은 강도에서 이코노미 +2.4% · 5km 2% 빨라짐 · 평지·대조 그룹 없음
- Ferley et al. (2014) J Strength Cond Res · 편차 큼 (±7~13%) · Barnes et al. (2013) Int J Sports Physiol Perform · Ferley (2013): 평지가 버틴 시간은 더 늘어남

### 재구성 15 현장의 업힐 훈련  (`E3R-HillsPractice.dc.html`)

- 보조 ②현장의 업힐 훈련
- 선수들은 언덕을 이렇게 써요
- 현장 사례
- 10초
- 짧은 언덕 질주
- 약 10초 전력 · 걸어 내려오며 완전히 회복
- 케냐식 언덕
- 오르막은 세게, 내리막도 쉬지 않고 이어 달리기
- Canova 업힐 서킷
- 짧은 오르막에 바운딩·스킵을 섞어서
- → 대부분 편한 달리기를 많이 하는 기초기에 얹어요
- 코치 자료 · 효과 크기는 연구로 확인 안 됨 · Renato Canova 훈련 체계 (Wikipedia) · The Running Channel: Kenyan hills · 사진: Chris Upson (CC BY-SA 2.0, Wikimedia Commons)

### 재구성 16 짧은 질주  (`E3R-Sprint.dc.html`)

- 보조 ②짧은 질주
- 30초 질주 4주, 산소 6~8%↓ 그런데
- 30초 질주 8~12회 사이 3분 휴식 주 45km → 15.6km
- 주의할 점
- 훈련량을 65% 줄여 피로가 빠진 효과가 섞였을 수 있어요
- 17명 · 4주뿐이에요
- 10km 기록은 그대로였어요
- Iaia et al. (2009) J Appl Physiol · 사진: LexSprinter (CC BY-SA 3.0, Wikimedia Commons)

### 재구성 17 엘리트는 이렇게 ①  (`E3R-Elites.dc.html`)

- 현장엘리트는 이렇게
- 엘리트의 실제 훈련 ① 많이 달리고, 조금 강하게
- 폴라 래드클리프사례 · 논문 기록
- 주 약 193~257km · 상당 부분 3:20~3:40/km
- 역치 근처 템포 + 주 1~2회 고강도
- 웨이트 주 2회 정도 · 고지대
- 엘리우드 킵초게팀 영상·기사
- 근력·가동성 주 2~3회 · 매체마다 20~60분
- 밴드·맨몸: 브리지, 플랭크, 균형
- 목적은 부상 예방·경기력 · 코치 Patrick Sang
- Jones (2006) Int J Sports Sci Coach · NN Running Team · Running Magazine

### 재구성 18 엘리트는 이렇게 ②  (`E3R-Elites2.dc.html`)

- 현장엘리트는 이렇게
- 엘리트의 실제 훈련 ② 근력·언덕은 이렇게
- 야콥 잉게브릿센인터뷰·브랜드
- 근력 주 4회
- 주 초반 드릴·점프 · 금·일 웨이트
- 케냐 · Canova코치 자료
- 기초기: 많은 양의 편한 달리기
- 짧은 업힐 스프린트 · 기술 드릴
- 공통점모두 많이 달려요 · 근력은 부상 예방·파워용현장 관행이지, 효과의 증거는 아니에요
- Coros (Ingebrigtsen 인터뷰) · Wikipedia: Renato Canova · Yahoo News (Shane Benzie)

### 재구성 19 러닝 자세  (`E3R-Form.dc.html`)

- 흔한 고민러닝 자세
- 러닝 자세, 억지로 바꾸지 마세요
- 메타분석 · 상관연구 51편 · 1,115명
- 수직 진폭
- 작을수록 · 중간
- 다리 강성
- 덜 꺾일수록 · 중간
- 케이던스
- 높을수록 · 작음
- 접지 시간
- 관련 없음
- 착지법
- 뒤꿈치 = 앞꿈치
- 앞꿈치로 바꾸면 단기적으론 오히려 나빠졌어요
- Van Hooren et al. (2024) Sports Med · Anderson et al. (2020) Sports Med · 자세 변수 하나로는 개인차의 4~12%만 설명돼요

### 재구성 20 케이던스  (`E3R-Cadence.dc.html`)

- 러닝 자세케이던스
- 케이던스 180이 모두의 정답은 아니에요
- 관찰180 = 1984 올림픽 엘리트의 레이스 페이스
- 실험산소가 가장 적게 드는 케이던스
- 회색 지금 → 초록 최적 · 걸음/분
- 초보
- 156
- 170
- 180
- 숙련
- 169
- 174
- 180
- 소규모 실험올려서 연습하면?
- 10일 × 매일 15분, 180으로 → 산소 −11%
- 여자 러너 11명 vs 11명 · 같은 팀 이전 결과는 −3%로 불확실
- → 효율: 초보 +5~10%, 숙련자 +3% 안팎 +5~10%는 무릎·엉덩이 부담도 줄여요
- Daniels' Running Formula (1984 올림픽 관찰) · de Ruiter 2014 · Quinn 2021 · Heiderscheit 2011

### 재구성 21 신발  (`E3R-Shoes.dc.html`)

- 바꿀 수 있는 것신발
- 카본화 평균 약 2~4%, 내 발엔 손해일 수도
- 실험 2023카본화로 바꿨을 때 이코노미 변화
- ← 손해0이득 →
- 케냐 정상급
- 7명
- −11.3%+11.4%
- 유럽 아마추어
- 7명
- −1.1%+9.7%
- 세계 정상급 중에도 11% 손해 본 사람이 있었어요
- 레이싱 플랫 대비 카본화 3종 · 신발마다 한 번씩만 재서 측정 오차(2~3%)도 섞여 있어요
- 메타분석 평균 약 2~3%↓ (4%는 빠른 속도 실험) · 느리면 약 1%
- 무게도 이코노미: 한 짝 100g ≈ 1% 손해
- Knopp et al. (2023) Sports Med · 2025 리뷰 (Int J Sports Med · Front Sports Act Living) · Joubert et al. (2023) · Franz et al. (2012)

### 재구성 22 최신 경향 지쳐도 유지되는 힘  (`E3R-Durability.dc.html`)

- 최신 경향지쳐도 유지되는 힘
- 같은 페이스인데 90분째엔 산소가 더 든다
- '지쳐도 유지되는 힘'을 넷째 요소로 보자는 제안이 나왔어요
- 비교 연구 2024훈련된 남성 44명 · LT1(존2 상한)로 90분
- 상위권
- 10km 약 31분
- +2.4%
- 하위권
- 10km 약 42분
- +4.5%
- 잘 달리는 사람일수록 덜 무너졌어요
- 하이록스라면1km × 8번을 지친 상태로 달려요. 이 힘이 크게 작용할 거라 봐요코치 해석 · 하이록스에서 '지친 뒤 이코노미'를 잰 연구는 아직
- Zanini, Folland & Blagrove (2024) Med Sci Sports Exerc · Jones (2024) J Physiol (제안) · 에너지로 재면 +2.3% vs +4.3%

### 재구성 23 롱런과 내구성  (`E3R-LongRun.dc.html`)

- 최신 경향롱런과 내구성
- 90분 이상 롱런(LSD)한 그룹, 이코노미가 덜 무너졌다
- 상관10km 기록이 같은 남자 러너 13명 vs 13명 · 2026
- 90분째 같은 페이스의 산소 증가
- 롱런 정기적
- 90분 이상
- +3.1%
- 짧게만
- 모두 70분 미만
- +6.0%
- 롱런을 시켜 본 실험이 아니라, 원래 롱런하던 사람과 안 하던 사람을 비교 → 상관 (원인은 아직)
- 실험 2025근력·점프 10주 뒤 90분째 산소: −2.1% vs 러닝만 +0.6%
- Zanini et al. 2026 · Zanini et al. 2025 (28명) · Med Sci Sports Exerc

### 재구성 24 팩트 체크 ① 맞아요·관련은 있어요  (`E3R-FactCheck.dc.html`)

- 정리팩트 체크
- 이코노미 팩트 체크 ①
- 맞아요 · 실험으로 확인팔치기는 효율에 도움
- 팔을 고정하고 달리면 비용 3~13%↑
- 근력·점프는 효과가 있다
- 작음~중간 · 필수는 아님
- VO2max가 높으면 기록이 좋다
- 혈액 재주입 실험으로 확인 · 단, 비슷한 수준끼리는 이코노미·역치가 갈라요
- 관련은 있어요 · 상관, 인과는 아직많이 뛰면 이코노미가 오른다
- 수년 사례와 관련 · 롱런은 '지친 뒤 이코노미'와 관련 · 6주 실험은 엇갈림
- 근거: Arellano & Kram 2014 · Llanos-Lagos 2024 · Buick 1980 · Zanini 2026 · Franch 1998 · 판정은 연구 설계 기준 (실험 / 상관)

### 재구성 25 팩트 체크 ② 애매해요  (`E3R-FactCheck2.dc.html`)

- 정리팩트 체크
- 이코노미 팩트 체크 ②
- 애매해요 · 결과가 엇갈리거나 부족해요체중 1kg = km당 몇 초
- 무게를 더한 실험뿐 · 감량 실험은 거의 없어요
- 가벼운 신발일수록 무조건 이득
- 100g ≈ 1%는 맞지만 쿠션이 상쇄하기도
- 케이던스를 조금 올리면 효율↑
- 초보는 최적보다 낮게 뛰는 편 · 소규모 실험, 결과 엇갈림 (−11% vs −3%)
- 호흡을 2:2·3:2로 맞추면 효율↑
- 소규모 연구뿐 · 결론이 없어요
- 근거: Teunissen 2007 · Franz 2012 · de Ruiter 2014 · Quinn 2021 · 걸음-호흡 동기화는 소규모 연구뿐 (학위논문 포함)

### 재구성 26 팩트 체크 ③ 틀려요·근거 없어요  (`E3R-FactCheck3.dc.html`)

- 정리팩트 체크
- 이코노미 팩트 체크 ③
- 틀려요 · 근거 없어요케이던스는 180이 모두의 정답
- 엘리트 레이스 페이스 숫자 · 최적은 사람마다
- 앞꿈치 착지가 더 효율적
- 차이 없음 · 바꾸면 단기적으로 오히려 나빠짐
- 유연할수록 효율적
- 근거 없어요 · 오히려 덜 유연한 러너가 더 경제적 (상관)
- 카본화는 누구나 4%
- 카본화로 바꿔도 사람마다 −11 ~ +11%까지 갈렸어요
- 근거: de Ruiter 2014 · Anderson 2020 · Jones 2002 · Knopp 2023

### 재구성 27 오늘부터 할 일 ①  (`E3R-Todo.dc.html`)

- 실천오늘부터 할 일
- 내 이코노미를 위해 오늘부터 할 일 ①
- 1러닝 마일리지 쌓기사례·상관
- 몇 년 단위로 · 주 1회 90분 이상 롱런 포함
- 2근력 주 2~3회, 무겁게 적게메타분석
- 스쿼트 4×4나 점프 · 처음엔 가볍게 동작부터
- 3업힐·짧은 질주는 가끔실험코치 해석
- 메인 훈련을 대신하지 말고 위에 얹기
- Zanini 2026 · Llanos-Lagos 2024 · Støren 2008 · Barnes 2013 · Ferley 2014

### 재구성 28 오늘부터 할 일 ②  (`E3R-Todo2.dc.html`)

- 실천오늘부터 할 일
- 내 이코노미를 위해 오늘부터 할 일 ②
- 4자세는 그대로, 케이던스만 살짝실험
- 같은 페이스에서 초보 +5~10%, 숙련자 +3% 안팎
- 5레이스 신발은 직접 비교코치 해석
- 레이스 페이스로 미리 달려보기 · 느낌·심박으론 1~3% 차이 구별 어려워요
- 6시계 숫자에 휘둘리지 않기코치 해석
- 같은 코스·페이스에서 심박이 내려가는지 보기
- de Ruiter 2014 · Heiderscheit 2011 · Knopp 2023 · Aubry 2018 · 5·6번은 코치 해석이에요

### 재구성 29 참고문헌 ①  (`E3R-Refs.dc.html`)

- 참고참고문헌
- 참고문헌 ①
- 1Barnes & Kilding (2015) Sports Med Open
- 2Jones & Doust (1996) J Sports Sci
- 3Saunders et al. (2004) Med Sci Sports Exerc
- 4Joyner (1991) J Appl Physiol
- 5Kipp, Kram & Hoogkamer (2019) Front Physiol
- 6Jones (2006) Int J Sports Sci Coach
- 7Franz, Wierzbinski & Kram (2012) Med Sci Sports Exerc
- 8Coifman, Kram & Riemer (2024) Appl Ergon
- 9Lucia et al. (2006) Appl Physiol Nutr Metab
- 10van Werkhoven & Piazza (2017) J Appl Biomech
- 11Teunissen, Grabowski & Kram (2007) J Exp Biol
- 12Llanos-Lagos et al. (2024) Sports Med
- 13Lake & Cavanagh (1996) Med Sci Sports Exerc
- 14Haugen et al. (2022) Sports Med Open
- 15Støren et al. (2008) Med Sci Sports Exerc
- 16Saunders et al. (2006) J Strength Cond Res
- 17Ferley, Osborn & Vukovich (2014) J Strength Cond Res
- 18Ferley, Osborn & Vukovich (2013) J Strength Cond Res
- 19Barnes et al. (2013) Int J Sports Physiol Perform
- 20Iaia et al. (2009) J Appl Physiol
- 현장 자료NN Running Team (Patrick Sang) · Running Magazine · Coros (Ingebrigtsen) · Wikipedia: Renato Canova · Yahoo News (Shane Benzie) · The Running Channel · Daniels' Running Formula (1984 올림픽 관찰)

### 재구성 30 참고문헌 ②  (`E3R-Refs2.dc.html`)

- 참고참고문헌
- 참고문헌 ②
- 21Bangsbo et al. (2009) J Appl Physiol
- 22Van Hooren et al. (2024) Sports Med
- 23Anderson et al. (2020) Sports Med
- 24de Ruiter et al. (2014) Eur J Sport Sci
- 25Quinn et al. (2021) J Strength Cond Res
- 26Heiderscheit et al. (2011) Med Sci Sports Exerc
- 27Knopp et al. (2023) Sports Med
- 28Joubert et al. (2023) Int J Sports Physiol Perform
- 29신발 리뷰 (2025) Int J Sports Med · Front Sports Act Living
- 30Zanini, Folland & Blagrove (2024) Med Sci Sports Exerc
- 31Jones (2024) J Physiol
- 32Zanini, Folland & Blagrove (2026) Med Sci Sports Exerc
- 33Zanini et al. (2025) Med Sci Sports Exerc
- 34Arellano & Kram (2014) J Exp Biol
- 35Conley & Krahenbuhl (1980) Med Sci Sports Exerc
- 36Jones (2002) Int J Sports Med
- 37Aubry et al. (2018) J Strength Cond Res
- 38Cureton & Sparling (1980) Med Sci Sports Exerc
- 39걸음-호흡 동기화 연구 (Univ. of Oregon 학부 우등논문)
- 추가Franch 1998 MSSE · González-Mohíno 2020 Sports Med · Buick 1980 J Appl Physiol · Brandt 2025 Front Physiol · Scholz 2008 J Exp Biol
- 사진Wikimedia Commons · yaaaay (CC BY 2.0) · Tiia Monto, Bob Ramsak, Hjfm 003, franchise opportunities (CC BY-SA) · LexSprinter (CC BY-SA 3.0) · 미 육군·미 해병대, Gray's Anatomy (퍼블릭 도메인)

### 재구성 31 다음 편 예고  (`E3R-Next.dc.html`)

- 다음 편 예고젖산역치
- 엔진도 연비도 같은데, 후반에 갈리는 이유
- LT1 · 5:43/km
- LT2 · 4:42/km
- 편하게 오래
- 젖산이 안정 수준
- 버틸 수 있는 구간
- 젖산이 조금씩 오름
- 빠르게 지침
- 젖산이 계속 쌓임
- 7:30
- 6:30
- 5:43
- 5:00
- 4:42
- 4:00
- 예시 데이터
- 1km 페이스 (분:초) · 오른쪽일수록 빠름
- 혈중 젖산 →
- LT1처음 오르는 지점
- LT2급격히 쌓이는 지점
- 훈련어떻게 올리나
- 1편 예시 러너 그래프 · 4편 젖산역치에서 이어져요


## 4편

### 4편 00 훅  (`E4-Hook.dc.html`)

- 러닝 3요소 · 4편
- 엔진도 연비도 같은데 38초 차이, 젖산역치
- VO2max도 이코노미도 같은 두 러너, 차이는 얼마나 높은 강도까지 버티느냐였어요.
- 러너 C · 역치 페이스
- 5:20/km
- VO2max 75%에서 역치
- vs
- 러너 D · 역치 페이스
- 4:42/km
- VO2max 85%에서 역치
- 예시값 · 1편 비교 러너 (둘 다 VO2max 60 · 이코노미 240)

### 4편 01 젖산은 연료  (`E4-Lactate.dc.html`)

- 오해젖산은 범인일까
- 젖산은 피로물질이 아니라 연료
- 1다시 태워 쓰는 연료 리뷰
- 운동 중 젖산의 75~80%는 근육·심장에서 다시 태워져요. 나머지는 간에서 포도당으로 바뀌어요.
- 2산성화의 범인도 아니에요 리뷰
- 산성을 만드는 H⁺는 에너지(ATP)를 쓸 때 나와요. 젖산을 만드는 반응은 오히려 산성화를 늦춰요.
- 계기판젖산 수치는 범인이 아니라 ‘지금 힘든 강도’를 알려주는 신호예요.
- Brooks (리뷰) · Robergs et al. (2004) Am J Physiol · Ferguson et al. (2018) Eur J Appl Physiol

### 4편 02 근육통은 젖산 탓?  (`E4-Soreness.dc.html`)

- 오해근육통은 젖산 탓?
- 다음 날 근육통, 젖산 때문이 아니에요
- 리뷰실험 · 소규모
- 혈중 젖산 · 반감기 약 15~25분
- 근육통 · 1~3일 뒤 최고
- 직후
- 1시간
- 6시간
- 24시간
- 48시간
- 72시간
- 젖산은 1~2시간이면 거의 정리돼요. 근육통은 하루~사흘 뒤에 가장 심해요.
- Cheung et al. (2003) Sports Med · 젖산 반감기: 회복 방법별 실험 (1996, 10명) · Denadai et al. (2000) · 그래프는 개념도

### 4편 03 역치는 두 개  (`E4-Two.dc.html`)

- 개념역치는 두 개
- 역치는 하나가 아니라 두 개
- LT1
- LT2
- 중강도
- 편하게 오래
- 고강도
- 버틸 수 있음
- 심한 강도
- 빨리 지침
- 7:30
- 6:30
- 5:00
- 4:00
- 5:43
- 4:42
- 예시 데이터
- 1km 페이스 · 오른쪽일수록 빠름
- 혈중 젖산 →
- 비슷한 이름 LT1 ≈ 첫 환기역치(VT1) · LT2 ≈ MLSS·임계속도 근처 (완전히 같은 값은 아니에요)
- 그래프: 1편 예시 러너 (VO2max 60 · 이코노미 240 · LT1 = VO2max 70%, LT2 = 85%) · Jamnick et al. (2020) Sports Med · Jones et al. (2019) Physiol Rep

### 4편 04 논문은 이렇게 잰다  (`E4-Measure.dc.html`)

- 개념논문은 이렇게 잰다
- 같은 ‘역치’도 정의가 25가지
- 리뷰 점증부하(예: 3분마다 속도↑) · 단계마다 손끝·귓불 피 한 방울로 젖산 측정
- ①고정값
- 젖산 2·4 mmol이 되는 속도
- 간단 · 개인차 무시
- ②처음 오르는 지점
- 기준선보다 일정량 오른 곳
- → LT1
- ③급격히 꺾이는 지점
- 곡선 꺾임 · 30분 테스트(MLSS)
- → LT2
- Faude et al. (2009) Sports Med: 젖산역치 개념 25개, 세 부류

### 4편 05 4 mmol = 역치?  (`E4-MLSS.dc.html`)

- 개념4 mmol = 역치?
- ‘4 mmol = 역치’일까?
- MLSS30분 같은 속도로 달려, 10~30분 사이 젖산이 1 mmol 넘게 오르지 않는 가장 빠른 속도
- 비교 · 9명조정 선수 · 같은 사람의 두 기준
- 4 mmol 기준
- 287 W
- +12%
- 실제 MLSS
- 255 W
- 실제 MLSS 때 젖산은 평균 3.0 mmol. 4 mmol 기준은 역치를 약 12% 높게 잡았어요.
- Jones et al. (2019) Physiol Rep: MLSS 정의 · Beneke (1995) Med Sci Sports Exerc: 조정 선수 9명

### 4편 06 존2의 세 가지 뜻  (`E4-Zone2.dc.html`)

- LT1존2의 진짜 기준
- 같은 ‘존2’, 뜻이 세 가지
- 운동 앱 5구간
- 관행
- 최대심박의 약 60~70%
- 연구용 3구간
- 리뷰
- LT1과 LT2 사이 · 꽤 힘든 구간
- 요즘 ‘존2 훈련’
- 현장
- LT1 바로 아래 · 젖산이 오르기 직전
- LT1 아래존2의 기준은 시계 숫자보다 ‘젖산이 아직 안 오르는 강도’
- 연구용 3구간: Seiler 등 · Haugen et al. (2022) · 존2 훈련: San Millán 등 (현장) · Jamnick et al. (2020) Sports Med

### 4편 07 최대심박 공식의 오차  (`E4-HRmax.dc.html`)

- LT1최대심박 공식의 오차
- 최대심박 공식부터 ±10박
- 메타분석220 − 나이 · 208 − 0.7 × 나이
- ±10박
- 둘 다 평균 추정이에요. 같은 나이라도 10박 안팎 차이는 흔해요.
- 리뷰%최대심박으로 구간 나누기
- 근거 약함
- 고정 비율은 사람마다 같은 강도를 잘 못 나눠요. LT1·환기역치는 근거가 있어요.
- 실전 존2 = 문장으로 대화가 편한 정도
- Tanaka et al. (2001) · 개인 오차 약 10~12박은 후속 연구 기준 · Jamnick et al. (2020) · Quinn & Coons (2011)

### 4편 08 LT2 버틸 수 있는 상한  (`E4-LT2.dc.html`)

- LT2버틸 수 있는 상한
- LT2 아래는 멈추고, 위는 계속 쌓인다
- 개념도같은 속도로 30분 달릴 때 혈중 젖산
- LT2 아래 · 멈춤
- LT2 근처 · 1 mmol 이하 상승
- LT2 위 · 계속 쌓임
- 0분
- 10분
- 20분
- 30분
- 혈중 젖산 →
- 약 1시간1시간쯤 전력으로 버틸 수 있는 ‘편하게 힘든’ 페이스 근처 코치 기준
- Jones et al. (2019) Physiol Rep · Daniels T 페이스 (코치 기준) · 그래프는 개념도

### 4편 09 하이록스와 젖산  (`E4-Hyrox.dc.html`)

- LT2하이록스와 젖산
- 하이록스에선 젖산이 스테이션에서 더 오른다
- 상관 · 11명하이록스 첫 생리학 연구 · 모의 대회
- 최고 젖산 (중앙값)
- 스테이션
- 8.5 mmol
- 러닝
- 7.7 mmol
- 빠른 완주는 높은 VO2max·많은 지구력 훈련량과 관련 있었어요
- 코치 해석러닝 구간을 LT2 아래로 달려야 스테이션에서 쌓인 젖산을 정리할 여유가 생겨요
- Brandt et al. (2025) Front Physiol · ‘LT2 = 하이록스 러닝의 천장’은 코치 해석

### 4편 10 역치의 위치  (`E4-Position.dc.html`)

- LT2역치의 위치
- VO2max가 같아도 역치 위치가 페이스를 바꾼다
- 러너 C · VO2max의 75%5:20
- 산소 45
- 60
- 러너 D · VO2max의 85%4:42
- 산소 51
- 60
- Breaking2 선수 · 16명 평균92%
- VO2max의 92%에서 LT2
- 역치 페이스 = 이코노미 ÷ (VO2max × 역치 위치)C: 240 ÷ 45 → 5:20/km · D: 240 ÷ 51 → 4:42/km
- 러너 C·D: 1편 예시 (둘 다 VO2max 60 · 이코노미 240 ml/kg/km) · Jones et al. (2021) J Appl Physiol · 모델: Joyner (1991)

### 4편 11 기록과 더 가까운 것  (`E4-Predict.dc.html`)

- LT2기록과 더 가까운 것
- 기록과 더 가까운 건 역치 속도
- 젖산이 오르기 시작하는 속도
- r ≥ 0.91
- VO2max
- r ≥ 0.83
- 상관 남자 장거리 18명 · 3.2km부터 마라톤까지 모든 거리 기록과의 상관 (1979)
- Farrell et al. (1979) Med Sci Sports · r이 1에 가까울수록 함께 움직여요 (원인이라는 뜻은 아니에요)

### 4편 12 무엇이 역치를 정하나  (`E4-Why.dc.html`)

- 왜무엇이 역치를 정하나
- 젖산은 늘 만들어진다, 문제는 치우는 속도
- 개념도리뷰
- 물 높이 = 혈중 젖산
- 만드는 양
- 페이스를 올릴수록 ↑
- 당을 빨리 쪼갬
- 치우는 양
- 근육·심장에서 태움
- 간에서 포도당으로
- 들어오는 양이 빠지는 양을 넘으면 물이 계속 차요 → 그 지점이 LT2
- Brooks (리뷰) · Ferguson et al. (2018) Eur J Appl Physiol · 욕조 그림은 개념도

### 4편 13 훈련으로 바뀌는 것  (`E4-Adapt.dc.html`)

- 왜훈련으로 바뀌는 것
- 훈련하면 치우는 힘이 커진다
- 리뷰
- 미토콘드리아 ↑
- 젖산·피루브산을 근육 안에서 더 많이 태워요
- 운반체(MCT1) ↑
- 지구력 훈련으로 늘어 젖산을 태울 곳으로 옮겨요
- 모세혈관 ↑
- 산소가 들어오고 젖산이 나가는 길이 넓어져요
- 래드클리프 11년 사례 1명
- VO2max는 약 70 그대로인데 LT1 14~15 → 17.5~18.5 · LT2 16 → 20 km/h
- Billat et al. (2003) Sports Med: 훈련 후 젖산 제거↑, MCT1↑ · Brooks (리뷰) · Jones (2006) Int J Sports Sci Coach

### 4편 14 노르웨이 더블 역치  (`E4-Norway.dc.html`)

- 엘리트 ①노르웨이 더블 역치
- 역치를 ‘넘지 않게’, 대신 자주·많이
- 하루 2번 역치
- 화·목
- 오전 목표 · mmol
- 약 2.5
- 오후 목표 · mmol
- 약 3.5
- 핵심은 브레이크 리뷰·현장
- 1~3회 반복마다 젖산을 재서 2~4.5 mmol 안에 머물게 해요
- 근거는 아직 ‘물음표’ 리뷰
- 2023년 리뷰 제목도 “다음 단계인가?” 다른 방식과 비교한 통제 실험은 아직 없어요
- Casado, Foster, Bakken & Tjelta (2023) Int J Environ Res Public Health · Outside · Trail Runner · 젖산 단위 mmol/L

### 4편 15 노르웨이식 한 주  (`E4-NorwayWeek.dc.html`)

- 엘리트 ①노르웨이식 한 주
- 노르웨이식 한 주 예시
- 현장 사례마리우스 바켄 자료 · 기사 재인용
- 화
- 오전 · 약 2.56분 × 5 · 휴식 1분
- 오후 · 약 3.51000m × 10 · 휴식 1분
- 목
- 오전 · 약 2.52000m × 5 · 휴식 1분
- 오후 · 약 3.5400m × 25 · 휴식 30초
- 월·수·금
- 쉬운 달리기
- 토
- 짧고 빠른 세션 1회 · 자료마다 다름
- 일
- 쉬운 달리기 · 롱런 · 자료마다 다름
- 역치 세션은 주 4번, 나머지는 쉽게
- Casado et al. (2023) · Outside · Trail Runner (바켄의 예시 주 재인용) · 숫자는 목표 젖산 mmol/L

### 4편 16 세계 정상급의 한 주  (`E4-WorldClass.dc.html`)

- 엘리트 ②세계 정상급의 한 주
- 대부분은 쉽게, 역치·인터벌은 조금
- 리뷰연구 + 실제 훈련 기록
- 쉬움 · LT1 아래
- 역치·인터벌
- 주간 거리의 80% 이상이 쉬운 강도
- 마라토너 주간 거리
- 160~220km
- 트랙 130~190km
- 한 주 훈련
- 11~14회
- 하루 두 번이 흔해요
- 아프리카 선수
- 2000~2500m
- 고지대에 살며 훈련
- Haugen, Sandbakk, Seiler & Tønnessen (2022) Sports Med Open

### 4편 17 기록을 설명한 훈련  (`E4-WorldClass2.dc.html`)

- 엘리트 ②기록을 설명한 훈련
- 쉬운 달리기의 양 + 템포·짧은 인터벌
- 상관세계 정상급 선수들의 첫 7년 훈련
- 쉬운 달리기의 양과 템포런·짧은 인터벌을 꾸준히 한 것이 기록을 가장 잘 설명했어요
- 현장 사례킵초게 캠프 · 케냐 캅타갓
- 해발 약 2,400m · 주 최대 200km 안팎 주 1회 30~40km 롱런 · 파틀렉
- 기사마다 세부가 달라요
- Casado, Hanley, Santos-Concejero & Ruiz-Pérez (2021) J Strength Cond Res · 킵초게: Outside · Gulf News 등 기사

### 4편 18 노르웨이 싱글  (`E4-Singles.dc.html`)

- 트렌드노르웨이 싱글
- 하루 두 번은 무리라서, 하루 한 번 서브역치
- 어디서 왔나 현장 사례해외 러닝 커뮤니티(LetsRun)의 한 아마추어가 정리한 ‘마일리지 적은 사람을 위한 노르웨이식’
- 서브역치
- 주 2~3회
- 역치보다 살짝 느리게
- 롱런
- 주 1회
- 길게, 편하게
- 나머지
- 전부 쉽게
- 역치 위는 안 해요
- LetsRun 글타래 “Modifying the Norwegian approach to lower mileage” 정리 문서 · Outside (노르웨이 방법, 일반인편)

### 4편 19 싱글의 시간 비중  (`E4-Singles2.dc.html`)

- 트렌드싱글의 시간 비중
- 한 주 시간의 20~25%만 서브역치
- 커뮤니티 권장한 주 시간 비중
- 쉬움·롱런 75~80%
- 20~25%
- 왜 인기일까
- 하루 한 번으로 끝나고, 역치를 넘지 않아 회복 부담이 적다는 후기가 많아요
- 주의할 점
- 통제된 실험은 아직 없어요 효과는 후기와 사례 수준이에요
- LetsRun 정리 문서 · Outside · 비중은 커뮤니티 권장값

### 4편 20 어떤 분포가 좋을까  (`E4-TID.dc.html`)

- 연구어떤 분포가 좋을까
- 역치를 더 많이 한다고 더 좋아지진 않았다
- 실험 · 12명서브엘리트 · 5개월 · 10.4km 기록 향상
- 저강도 비중↑쉬운 달리기 위주
- −157초
- 역치 사이 비중↑LT1~LT2 위주
- −121.5초
- 고강도(LT2 위) 비중은 두 그룹 모두 약 8%로 같았어요
- Esteve-Lanao, Foster, Seiler & Lucia (2007) J Strength Cond Res

### 4편 21 메타분석이 말하는 것  (`E4-TID2.dc.html`)

- 연구메타분석이 말하는 것
- 분포 이름보다 쉬운 양이 먼저
- 메타분석 2024
- 폴라라이즈드가 VO2max를 조금 더 올렸어요 (12주 미만에서만). 다른 기록 지표는 차이가 없었어요.
- 개인 데이터 메타분석 2025
- 13개 연구 348명 · 폴라라이즈드 vs 피라미드 VO2max·타임트라이얼 차이 없음
- 경쟁 선수는 폴라라이즈드, 일반인은 피라미드가 나을 수도
- 폴라라이즈드 쉬움 많이 + 고강도 조금 피라미드 쉬움 > 역치 사이 > 고강도
- Sports Med (2024) 폴라라이즈드 메타분석 · Rosenblat et al. (2025) Sports Med 네트워크 메타분석

### 4편 22 역치도 지친다  (`E4-Durability.dc.html`)

- 최신 경향역치도 지친다
- 90분 달리면 역치 속도가 5.5% 떨어졌다
- 2024 런던 마라톤 참가자 18명 · 평균 3시간 17분 · 41세
- 비교 · 18명달리기 전 vs 90분 뒤
- 역치 속도km/h
- 전 12.8
- 90분 뒤 12.1
- VO2maxml/kg/분
- 전 56.7
- 90분 뒤 53.4
- 이코노미 · 역치 위치는 그대로
- r = 0.68역치 속도가 덜 떨어진 사람이 마라톤도 더 빨랐어요 상관
- Hunter & Muniz-Pumares (2025) Eur J Sport Sci

### 4편 23 지쳐도 유지되는 힘  (`E4-Durability2.dc.html`)

- 최신 경향지쳐도 유지되는 힘
- 지쳐도 유지되는 힘, 4번째 요소
- 실험 · 14명사이클 2시간 뒤 LT1 파워
- 212 → 190W
- 약 10% 떨어졌어요
- 리뷰요즘 관점
- ‘지쳐도 유지되는 능력’을 VO2max·이코노미·역치 위치 다음의 4번째 요소로 봐요
- Stevenson, Kilding, Plews & Maunder (2022) Eur J Appl Physiol · Jones (2024) J Physiol

### 4편 24 랩 없이 역치 찾기  (`E4-Field.dc.html`)

- 실전내 역치 찾기
- 랩 없이 역치 찾기, 정확도는 방법마다 다르다
- 말하기 테스트→ LT1 근처
- 문장으로 편하게 말이 되는 마지막 강도 · 연구마다 맞는 역치가 조금씩 달라요
- 대략
- 1시간 레이스 페이스→ LT2 근처
- 약 1시간 전력으로 갈 수 있는 페이스 · Daniels T 페이스(코치 기준)
- 대략
- 스마트워치 추정→ 참고용
- 심박은 실험실과 비슷, 페이스는 평균 오차 약 26% (가민 FR265, 2025)
- 페이스 주의
- Quinn & Coons (2011) J Sports Sci · Daniels' Running Formula · Front Physiol (2025) 스마트워치 LT 검증

### 4편 25 임계속도 테스트  (`E4-CS.dc.html`)

- 실전임계속도 테스트
- 임계속도 테스트는 비교적 정확
- 실험 · 10명같은 날 3번 전력
- 3600 · 2400 · 1200m 전력 사이 30분 휴식
- 실험실 측정과 차이 없음 · r = 0.89
- MLSS보다 조금 빨라요 · 16.4 vs 15.2 km/h 비교
- 간단 계산 (기록 2개)
- (긴 거리 − 짧은 거리) ÷ (긴 시간 − 짧은 시간)
- 예: 3600m 14:00 · 1200m 4:00 → 2400m ÷ 600초 = 4.0 m/s ≈ 4:10/km
- Galbraith et al. (2014) Int J Sports Physiol Perform · Nixon et al. (2021): 잘 훈련된 러너 · 계산 예시는 가상 기록

### 4편 26 팩트 체크 ① 틀려요  (`E4-FactCheck.dc.html`)

- 팩트 체크흔한 말 검증
- 팩트 체크 ① 틀려요
- “젖산은 피로물질이다”
- 젖산은 연료이고, 산성화를 오히려 늦춰요
- “다음 날 근육통은 젖산 때문”
- 젖산은 1~2시간이면 정리, 근육통은 1~3일 뒤
- “역치 = 4 mmol”
- 사람마다 달라요 · 약 12% 높게 잡은 연구도
- “젖산은 산소가 부족해서 생긴다”
- 산소가 충분해도 생겨요 · 치우는 속도를 넘을 때 쌓여요
- Robergs (2004) · Ferguson (2018) · Cheung (2003) · Beneke (1995)

### 4편 27 팩트 체크 ② 애매해요  (`E4-FactCheck2.dc.html`)

- 팩트 체크흔한 말 검증
- 팩트 체크 ② 애매해요
- “존2 = 최대심박 60~70%”
- 앱·연구·코치마다 존2 정의가 달라요 · 최대심박 공식도 ±10박 오차
- “워치가 알려주는 젖산역치”
- 심박은 실험실과 비슷, 페이스는 크게 틀릴 수 있어요 (2025)
- “폴라라이즈드(80/20)가 정답”
- 메타분석상 다른 분포와 차이가 작거나 없어요
- Tanaka (2001) · Jamnick (2020) · Front Physiol (2025) · 2024·2025 메타분석

### 4편 28 팩트 체크 ③ 맞아요  (`E4-FactCheck3.dc.html`)

- 팩트 체크흔한 말 검증
- 팩트 체크 ③ 맞아요
- “역치 속도는 기록과 밀접하다” 상관
- 3.2km~마라톤 기록과 상관 r ≥ 0.91 (1979, 18명)
- “VO2max가 그대로여도 역치는 오른다” 사례
- 래드클리프 11년: VO2max 약 70 그대로, LT2 16 → 20 km/h
- Farrell et al. (1979) Med Sci Sports · Jones (2006) Int J Sports Sci Coach

### 4편 29 이번 주부터  (`E4-Todo.dc.html`)

- 실천이번 주부터
- 역치를 올리는 네 가지
- 1쉬운 날은 LT1 아래로 리뷰
- 대화가 되는 강도 · 정상급도 거리의 80% 이상
- 2역치 세션은 주 1~2회, 끊어서 현장
- LT2 살짝 아래, 6~10분씩 짧게 쉬며 반복
- 3몇 주마다 내 역치 다시 찾기 현장
- 1시간 레이스 페이스·임계속도로 확인
- 4롱런으로 ‘지쳐도 유지’ 연습 상관
- 90분 뒤 역치를 덜 잃은 사람이 더 빨랐어요
- Haugen et al. (2022) · Casado et al. (2023) · Daniels · Galbraith et al. (2014) · Hunter & Muniz-Pumares (2025)

### 4편 30 3요소 공식  (`E4-Formula.dc.html`)

- 기록은 세 가지의 조합
- VO2max1분, 체중 1kg당 쓸 수 있는 산소의 최대치
- 60
- ×
- 역치(LT2)가 오는 위치LT2가 VO2max의 몇 %에서 나타나나
- 85%
- =
- 역치에서 쓰는 산소1분, 체중 1kg당
- 51
- 러닝 이코노미1km에 드는 산소량
- 240
- = 역치(LT2) 페이스240 ÷ 51 = 4.71분 → 1km 4분 42초
- 4:42/km
- 모델: Joyner (1991) J Appl Physiol · 모든 값은 체중 1kg당 · 숫자는 1편 예시

### 4편 31 세 가지와 내구성  (`E4-Series.dc.html`)

- 정리세 가지와 내구성
- 세 가지 + 내구성, 무엇으로 키우나
- +
- 내구성 지쳐도 이 세 값을 얼마나 지키나 · 최근 ‘4번째 요소’로 주목받아요
- 2편
- VO2max
- 고강도 인터벌로 엔진 키우기
- 3편
- 러닝 이코노미
- 수년간 달리기 + 근력·업힐
- 4편
- 젖산역치
- 쉬운 양 + 넘지 않는 역치 세션
- Jones (2024) J Physiol · 각 편 요약

### 4편 32 참고문헌 ①  (`E4-Refs.dc.html`)

- 참고참고문헌 ①
- 1Faude, Kindermann & Meyer (2009) Sports Med · 역치 개념 25개
- 2Jamnick et al. (2020) Sports Med · 강도 구간
- 3Jones et al. (2019) Physiol Rep · MLSS 정의
- 4Nixon et al. (2021) · 임계속도 vs MLSS
- 5Beneke (1995) Med Sci Sports Exerc · 조정 선수 9명
- 6Robergs, Ghiasvand & Parker (2004) Am J Physiol
- 7Brooks · 젖산 셔틀 (리뷰)
- 8Ferguson et al. (2018) Eur J Appl Physiol
- 9Billat et al. (2003) Sports Med
- 10Cheung, Hume & Maxwell (2003) Sports Med · 근육통
- 11젖산 반감기 실험 (1996, 10명) · Denadai et al. (2000)
- 12Tanaka, Monahan & Seals (2001) J Am Coll Cardiol
- 13Quinn & Coons (2011) J Sports Sci · 말하기 테스트
- 14Jones et al. (2021) J Appl Physiol · Breaking2
- 15Farrell et al. (1979) Med Sci Sports
- 다음 장에 이어져요

### 4편 33 참고문헌 ②  (`E4-Refs2.dc.html`)

- 참고참고문헌 ②
- 16Jones (2006) Int J Sports Sci Coach · 래드클리프
- 17Casado, Foster, Bakken & Tjelta (2023) IJERPH · 노르웨이
- 18Haugen et al. (2022) Sports Med Open
- 19Casado et al. (2021) J Strength Cond Res
- 20Esteve-Lanao et al. (2007) J Strength Cond Res
- 21Sports Med (2024) 폴라라이즈드 메타분석
- 22Rosenblat et al. (2025) Sports Med · 네트워크 메타분석
- 23Hunter & Muniz-Pumares (2025) Eur J Sport Sci
- 24Stevenson et al. (2022) Eur J Appl Physiol
- 25Jones (2024) J Physiol · 4번째 요소
- 26Galbraith et al. (2014) Int J Sports Physiol Perform
- 27Front Physiol (2025) · 스마트워치 LT 검증
- 28Brandt et al. (2025) Front Physiol · 하이록스
- 29현장 자료: Daniels' Running Formula · Outside · Trail Runner · LetsRun 정리 · 킵초게 기사
- 현장 사례(기사·인터뷰·커뮤니티)는 슬라이드에서 연구 근거와 구분해 표시했어요


## 5편

### 5편 00 훅  (`E5-Hook.dc.html`)

- 러닝 3요소 · 5편 · 고지대 트레이닝
- 케냐 선수처럼 높은 곳에서 훈련하면 나도 빨라질까?
- 케냐 이텐 · 해발 약 2,400m
- 헤모글로빈은 늘지만 기록은? 논문으로 확인해요
- 사진: Shadychiri (CC BY-SA 4.0, Wikimedia Commons) · 이텐 고도: 현지 훈련지 자료

### 5편 01 산소 압력  (`E5-Pressure.dc.html`)

- 원리산소 압력
- 산소 ‘농도’는 그대로, ‘압력’이 낮아져요
- 계산해발 고도별 기압 (해수면 = 100%)
- 해수면
- 100%
- 1,000m
- 89%
- 2,000m
- 78%
- 2,500m
- 74%
- 3,000m
- 69%
- 산소 비율은 어디서나 20.9%예요. 공기가 옅어져 한 번 숨에 들어오는 산소가 줄어요.
- 국제표준대기(ICAO) 기압 공식으로 계산

### 5편 02 높을수록 VO2max ↓  (`E5-VO2drop.dc.html`)

- 원리높을수록
- 올라갈수록 VO2max가 1,000m마다 약 6% 줄어요
- 실험 · 8명저압 챔버에서 바로 잰 VO2max
- 55
- 60
- 65
- 70
- 300
- 800
- 1,300
- 1,800
- 2,300
- 2,800
- 66
- 55
- 해발 고도 (m)
- VO2max
- −17%300m → 2,800m에서 66 → 55 평소 페이스 인터벌이 힘들어져요
- Wehrlin & Hallén (2006) Eur J Appl Physiol · 지구력 선수 8명 · 적응 전 급성 노출

### 5편 03 몸의 반응  (`E5-EPO.dc.html`)

- 원리몸의 반응
- 산소가 부족하면 몸이 적혈구를 더 만들어요
- 적혈구 · 전자현미경
- 산소 압력 ↓고지대
- →EPO ↑콩팥에서 분비
- →적혈구 생산골수
- →헤모글로빈 ↑산소 운반 ↑
- 새 적혈구가 늘기까지 몇 주가 걸려요리뷰
- Levine & Stray-Gundersen (1997) · Gore et al. (2013) · 사진: Scootdive (CC BY-SA 3.0, Wikimedia Commons)

### 5편 04 100시간에 1%  (`E5-Hbmass.dc.html`)

- 원리시간
- 100시간에 약 1%씩 헤모글로빈이 늘어요
- 메타분석 · 17개 연구고지대에 머문 시간과 헤모글로빈 질량
- +1.1%
- 100시간
- +3.3%
- 300시간
- 약 12일 내내
- 막대 위 선 = 300시간 때 사람별 예상 범위 (1.1~6%)
- 1~6%평균은 3% 남짓, 사람마다 크게 달라요
- Gore et al. (2013) Br J Sports Med · 고전 고지대·LHTL 모두 약 1.1%/100시간

### 5편 05 방법 4가지  (`E5-Models.dc.html`)

- 방법4가지
- 어디서 자고, 어디서 훈련하나
- 높게 살고 높게 훈련LHTH
- 잠
- 훈련
- 전통 고지대 캠프
- 높게 살고 낮게 훈련LHTL
- 잠
- 훈련
- 잠은 위, 인터벌은 아래
- 낮게 살고 높게 훈련LLTH
- 잠
- 훈련
- 저산소 방에서 운동
- 텐트·호텔에서 자기인공 LHTL
- 잠
- 훈련
- 집에서 잠만 저산소
- 리뷰 Wilber (2007) Med Sci Sports Exerc · 텐트·호텔은 질소를 섞거나 산소를 걸러 저산소를 만들어요

### 5편 06 높게 살고 낮게 훈련  (`E5-Levine.dc.html`)

- 연구 ①고전 실험
- 높게 살고 낮게 훈련한 그룹만 5km가 빨라졌다
- 대학 장거리 선수 39명 · 2,500m에서 4주
- 실험 · 39명4주 뒤 5km 기록 변화
- 높게 살고 낮게 훈련훈련은 1,250m
- −13.4초
- 높게 살고 높게 훈련
- 변화 없음
- 낮게 살고 낮게 훈련
- 변화 없음
- VO2max +5%적혈구 +9%고지대 두 그룹 모두
- 적혈구는 두 그룹 다 늘었는데, 훈련 속도를 지킨 쪽만 빨라졌어요
- Levine & Stray-Gundersen (1997) J Appl Physiol

### 5편 07 얼마나 높이  (`E5-Altitude.dc.html`)

- 연구 ②얼마나 높이
- 2,000~2,500m에 산 그룹만 빨라졌다
- 실험 · 48명4주 동안 산 고도와 3,000m 기록
- 2,000~2,500m
- 1,780m
- 그대로
- 2,085m
- 빨라짐
- 2,454m
- 빨라짐
- 2,800m
- 그대로
- 적혈구는 네 그룹 모두 늘었어요. → 적혈구만으로는 설명이 안 돼요.
- Chapman et al. (2014) J Appl Physiol · 대학 장거리 선수 48명 · 훈련은 모두 같은 코스(1,250~3,000m)

### 5편 08 얼마나 오래  (`E5-Dose.dc.html`)

- 연구 ③얼마나 오래
- 하루 몇 시간, 몇 주를 머물러야 할까
- 계산평균 1.1%/100시간으로 본 헤모글로빈 예상치
- 텐트에서 잠만 10시간 × 3주
- 약 +2.3%
- 캠프 2주 (하루 종일)
- 약 +3.7%
- 캠프 3주 (하루 종일)
- 약 +5.5%
- 단순 계산 · 실제는 사람마다 1~6% (300시간 기준)
- 메타분석 결론: 2주 캠프로도 대부분 늘 가능성이 높아요메타분석
- Gore et al. (2013) Br J Sports Med · 머문 시간 × 1.1%/100시간

### 5편 09 개인차  (`E5-Responders.dc.html`)

- 연구 ④개인차
- 같은 캠프에서도 누구는 안 늘어요
- 반응한 그룹
- 17명
- EPO가 오래 높게
- 적혈구·VO2max ↑
- 5km 빨라짐
- 반응 안 한 그룹
- 15명
- EPO 금방 원래대로
- 적혈구·VO2max 그대로
- 고지대 인터벌 속도 ↓
- 높게 머물러도 반응은 사람마다 달라요비교
- Chapman, Stray-Gundersen & Levine (1998) J Appl Physiol · 39명을 5km 변화로 나눈 사후 분석

### 5편 10 철분  (`E5-Iron.dc.html`)

- 연구 ⑤철분
- 철분이 모자라면 헤모글로빈이 덜 늘어요
- 관찰 · 178명약 3주 고지대 뒤 헤모글로빈 질량
- +1.1%
- 철분 안 먹음
- +3.3%
- 하루 105mg
- +4.0%
- 하루 210mg
- 가기 전에 페리틴(저장 철) 검사부터, 철분제는 의사와 상의해요코치 해석
- Govus et al. (2015) PLoS One · 1,350~3,000m · 무작위 실험이 아닌 관찰 연구

### 5편 11 메타분석  (`E5-Meta.dc.html`)

- 연구 ⑥메타분석
- 근거가 가장 좋은 건 자연 고지대 LHTL
- 메타분석 · 51개 연구비엘리트의 지구력 파워 변화
- 자연 고지대 LHTL
- +4.2%
- 인공 · 짧은 간헐 노출
- +2.6%
- 인공 LHTL · 긴 시간
- +1.4%
- LHTH
- +0.9% 불확실
- LLTH
- +0.9% 불확실
- 인공 LHTL · 짧은 시간
- +0.7% 불확실
- 엘리트: 자연 고지대 LHTL만 효과 가능(약 4%), 나머지는 불확실
- 저자들도 위약·캠프 효과가 섞였을 수 있다고 했어요.
- Bonetti & Hopkins (2009) Sports Med · 평균 추정치 · 분류명은 논문 기준

### 5편 12 가짜 저산소와 비교  (`E5-Placebo.dc.html`)

- 연구 ⑦반전
- 가짜 저산소와 비교하자 차이가 사라졌다
- 진짜 저산소
- 하루 16시간 × 4주
- 3,000m 상당 · 10명
- =
- 가짜 (정상 공기)
- 같은 방, 같은 일정
- 6명
- 헤모글로빈 질량
- 그대로그대로
- VO2max
- 그대로그대로
- 26km 타임트라이얼
- 그대로그대로
- 선수도 연구자도 그룹을 몰랐어요이중맹검 16명 소규모라 단정은 어려워요
- Siebenmann et al. (2012) J Appl Physiol · 저지대 훈련 사이클 선수

### 5편 13 그래서 효과는?  (`E5-Verdict.dc.html`)

- 정리그래서?
- 늘어나는 건 확실, 기록은 아직 논쟁
- 헤모글로빈 질량
- 충분히 높게, 충분히 오래 머물면 늘어요메타분석
- 기록
- 평균 몇 % 개선 보고 · 위약을 통제하면 불확실실험·메타분석
- 누구에게나?
- 철분, 개인 반응에 따라 크게 달라요비교·관찰
- Gore 2013 · Bonetti & Hopkins 2009 · Siebenmann 2012 · Chapman 1998 · Govus 2015

### 5편 14 의외의 효과  (`E5-Economy.dc.html`)

- 연구 ⑧이코노미
- 헤모글로빈은 그대로인데 이코노미가 3.3% 좋아졌다
- 실험 · 엘리트 22명20일 뒤, 같은 속도에서 쓰는 산소
- −3.3%
- 인공 LHTL
- 2,000~3,100m
- 기준
- 중간 고도
- 1,500~2,000m
- 기준
- 해수면
- 600m
- 3편 ‘러닝 이코노미’와 이어지는 결과예요. 이유는 아직 분명하지 않아요.
- Saunders et al. (2004) J Appl Physiol · 헤모글로빈 질량·환기·심박은 그룹 차이 없음

### 5편 15 내려온 뒤  (`E5-Return.dc.html`)

- 실전내려온 뒤
- 내려와도 약 3주는 헤모글로빈이 남아요
- 메타분석 추정고지대 전 대비 헤모글로빈 질량
- +3.3% 유지
- 이후 점차
- 원래대로
- 0일
- 10일
- 20일
- 30일
- 내려온 뒤 지난 날
- 경기는 언제가 최적일까? 헤모글로빈, 호흡 적응, 훈련 피로가 함께 작용해 아직 논쟁 중이에요.
- Gore et al. (2013) · Chapman, Stickford, Lundby & Levine (2014) J Appl Physiol 리뷰 · 감소 속도는 연구마다 달라요

### 5편 16 엘리트의 고지대  (`E5-Camps.dc.html`)

- 엘리트어디로 가나
- 엘리트가 찾는 곳은 해발 1,800~2,500m
- 프랑스 퐁로뮤 고지대훈련센터
- 현장 사례대표 고지대 훈련지 고도
- 연구상 최적 2,000~2,500m
- 케냐 이텐
- 2,400m
- 케냐 캅타갓
- 2,400~2,500m
- 스페인 시에라네바다
- 2,320m
- 미국 플래그스태프
- 약 2,100m
- 스위스 생모리츠
- 1,856m
- 프랑스 퐁로뮤
- 1,850m
- 고도: 각 훈련지·팀 공식 자료 · 사진: Lud Au43 (CC BY-SA 4.0, Wikimedia Commons)

### 5편 17 엘리트 사례  (`E5-Elites.dc.html`)

- 엘리트사례
- 세계 정상급도 해마다 고지대로 간다
- 케냐 이텐의 흙 트랙
- 폴라 래드클리프사례 논문
- 훈련 상당 부분을 퐁로뮤(약 1,850m)·앨버커키(약 1,600m)에서
- 엘리우드 킵초게현장 사례
- 케냐 캅타갓 캠프 (약 2,400~2,500m)
- 야코브 잉게브릿센현장 사례
- 시에라네바다·생모리츠에서 3~4주 블록
- Jones (2006) Int J Sports Sci Coach · NN Running Team · Sportskeeda (2024~2025) · 사진: edskoch (CC BY 2.0, Wikimedia Commons)

### 5편 18 동아프리카  (`E5-EastAfrica.dc.html`)

- 엘리트동아프리카
- 동아프리카가 빠른 건 고지대 하나 때문이 아니에요
- 이텐에서 본 리프트 밸리
- 고지대 생활·훈련
- 어릴 때부터 걷고 뛰기
- 체형과 이코노미
- 헤모글로빈
- 근섬유·효소
- 전통 식단
- 훈련 방식
- 경제적 동기
- 특별한 유전·생리 하나로는 설명이 안 돼요리뷰
- Wilber & Pitsiladis (2012) Int J Sports Physiol Perform · 사진: Appleslerp (CC BY-SA 4.0, Wikimedia Commons)

### 5편 19 저산소 텐트  (`E5-Tent.dc.html`)

- 장비저산소 텐트
- 저산소 텐트는 오래, 매일이 기본
- 집에서 잠만 저산소= 인공 ‘높게 살고 낮게 훈련’
- 메타분석비엘리트
- 긴 시간 +1.4% · 짧은 시간 +0.7% (불확실)
- 이중맹검사이클 선수
- 하루 16시간 × 4주도 가짜 텐트와 차이 없음
- 메타분석엘리트
- 인공 방식은 모두 효과 불확실
- Bonetti & Hopkins (2009) · Siebenmann et al. (2012) · 사진: Go2altitudepics (CC BY-SA 3.0, Wikimedia Commons)

### 5편 20 고산 마스크  (`E5-Mask.dc.html`)

- 장비고산 마스크
- 고산 마스크는 고지대가 아니에요
- 6주 고강도 사이클마스크 12명 vs 일반 12명
- VO2max둘 다 비슷하게 ↑
- 헤모글로빈·폐 기능차이 없음
- 숨을 힘들게 하는 호흡근 훈련 기구에 가까워요실험
- Porcari et al. (2016) J Sports Sci Med · 사진: 미 공군 (퍼블릭 도메인, Wikimedia Commons)

### 5편 21 열 훈련  (`E5-Heat.dc.html`)

- 최신 경향열 훈련
- 더운 곳 훈련으로도 헤모글로빈이 늘었다
- 실험 · 엘리트 사이클 23명5주 · 주 5회 1시간 · 37.8℃ · 습도 65%
- +42g
- 열 훈련
- 893 → 935g
- +6g
- 대조
- VO2max는 더 오르지 않았고, 2019년 다른 실험에선 그룹 차이가 뚜렷하지 않았어요.
- Rønnestad et al. (2021) Exp Physiol · Oberholzer et al. (2019) Front Physiol · 더위 훈련은 탈수·열질환에 주의

### 5편 22 한국에서는  (`E5-Korea.dc.html`)

- 실전한국에서는
- 국내 산은 대부분 2,000m가 안 돼요
- 한라산 · 정상 1,947m
- 최적 2,000~2,500m
- 한라산 정상
- 1,947m
- 1,780m (2014 연구)
- 기록 그대로였던 고도
- 함백산 고지대 훈련장
- 약 1,300m
- ‘헤모글로빈 늘리기’용 고지대 효과는 국내에서 기대하기 어려워요코치 해석
- Chapman et al. (2014) · 함백산 고지대 훈련장: 서울신문(1999) · 사진: LG전자 (CC BY 2.0, Wikimedia Commons)

### 5편 23 팩트 체크 ① 틀려요  (`E5-FactCheck.dc.html`)

- 팩트 체크 ①틀려요
- 고지대 상식, 틀려요
- 고산 마스크 = 고지대 효과
- 공기 흐름만 막아요 · 혈액 변화 없음실험
- 고지대는 산소 농도가 낮다
- 20.9%는 같고, 압력이 낮아요계산
- 동아프리카는 고지대 덕분
- 여러 요인이 겹친 결과예요리뷰
- 1,000m대 산에서 가끔 뛰면 효과
- 2,000m 이상에서 몇 주를 지내야 해요실험
- Porcari 2016 · 국제표준대기 · Wilber & Pitsiladis 2012 · Chapman 2014 · Gore 2013

### 5편 24 팩트 체크 ② 애매해요  (`E5-FactCheck2.dc.html`)

- 팩트 체크 ②애매해요
- 고지대 상식, 애매해요
- 고지대 훈련은 누구나 효과
- 반응하는 사람만 · 철분·시간 따라 1~6%비교·메타분석
- 산소 텐트면 충분
- 하루 16시간 × 4주도 가짜와 같았던 실험실험
- 내려오면 바로 기록이 오른다
- 헤모글로빈은 약 3주 유지, 최적 시점은 논쟁리뷰
- Chapman 1998 · Govus 2015 · Gore 2013 · Siebenmann 2012 · Chapman 2014 리뷰

### 5편 25 팩트 체크 ③ 맞아요  (`E5-FactCheck3.dc.html`)

- 팩트 체크 ③맞아요
- 고지대 상식, 맞아요
- 높은 곳에선 평소 강도로 못 뛴다
- VO2max가 1,000m마다 약 6% 줄어요실험
- 충분히 머물면 헤모글로빈이 는다
- 100시간에 약 1%메타분석
- 철분이 모자라면 효과가 작다
- 철분 없이 +1.1% vs 철분 +3~4%관찰
- Wehrlin & Hallén 2006 · Gore 2013 · Govus 2015

### 5편 26 가려면 이렇게  (`E5-Todo.dc.html`)

- 정리할 일
- 고지대 캠프, 가려면 이렇게
- 1가기 전에 페리틴 검사
- 부족하면 의사와 철분 계획
- 22,000~2,500m · 2주 이상
- 하루 대부분을 그곳에서
- 3첫 주는 강도를 낮추기
- 빠른 인터벌은 낮은 곳에서
- 4마스크·짧은 텐트에 기대지 않기
- 하이록스도 기본 훈련이 먼저
- 코치 해석Govus · Chapman · Gore · Levine · Porcari 연구 바탕
- 하이록스 관련 내용은 연구가 아닌 코치 해석이에요

### 5편 27 참고문헌 ①  (`E5-Refs.dc.html`)

- 참고문헌①
- 1Levine BD, Stray-Gundersen J (1997) "Living high-training low". J Appl Physiol
- 2Chapman RF, Stray-Gundersen J, Levine BD (1998) Individual variation in response to altitude training. J Appl Physiol
- 3Chapman RF, Karlsen T, Resaland GK et al. (2014) Defining the "dose" of altitude training. J Appl Physiol
- 4Chapman RF, Stickford ASL, Lundby C, Levine BD (2014) Timing of return from altitude training. J Appl Physiol
- 5Gore CJ et al. (2013) Altitude training and haemoglobin mass: a meta-analysis. Br J Sports Med
- 6Bonetti DL, Hopkins WG (2009) Sea-level exercise performance following adaptation to hypoxia: a meta-analysis. Sports Med
- 7Siebenmann C et al. (2012) LHTL using normobaric hypoxia: double-blinded, placebo-controlled. J Appl Physiol
- 8Wehrlin JP, Hallén J (2006) Linear decrease in VO2max and performance with increasing altitude. Eur J Appl Physiol
- 9Saunders PU et al. (2004) Improved running economy after 20 days of simulated altitude. J Appl Physiol

### 5편 28 참고문헌 ②  (`E5-Refs2.dc.html`)

- 참고문헌②
- 10Govus AD et al. (2015) Pre-altitude ferritin and oral iron dose mediate Hbmass responses. PLoS One
- 11Porcari JP et al. (2016) Effect of wearing the elevation training mask. J Sports Sci Med
- 12Rønnestad BR et al. (2021) Five weeks of heat training increases haemoglobin mass in elite cyclists. Exp Physiol
- 13Oberholzer L et al. (2019) Hematological adaptations to prolonged heat acclimation. Front Physiol
- 14Wilber RL, Pitsiladis YP (2012) Kenyan and Ethiopian distance runners. Int J Sports Physiol Perform
- 15Wilber RL (2007) Application of altitude/hypoxic training by elite athletes. Med Sci Sports Exerc
- 16Jones AM (2006) The physiology of the world record holder for the women’s marathon. Int J Sports Sci Coach
- 17현장 자료: Swiss Olympic St. Moritz · NN Running Team (캅타갓) · Sportskeeda (2024~2025) · 서울신문 (1999)
- 18기압: 국제표준대기(ICAO) 공식 계산 · 사진: Wikimedia Commons (각 장에 작가·라이선스 표기)

### 5편 29 다음 편 예고  (`E5-Next.dc.html`)

- 다음 편6편
- 다음 편: 점프 훈련, 러너에게 필요할까?
- 6편 플라이오메트릭
- 착지하자마자 튀어 오르는 훈련
- 이코노미 효과는 ‘작음’3편 메타분석 효과 크기 0.31
- 어떻게, 얼마나 할까
- Llanos-Lagos et al. (2024) Sports Med · 3편에서 다룬 메타분석


## 6편

### 6편 00 훅  (`E6-Hook.dc.html`)

- 러닝 3요소 · 6편 · 플라이오메트릭
- 점프 훈련, 러너에게 진짜 필요할까?
- 높이 뛰면 좋은 플라이오일까?
- 효과는 있어요. 다만 생각보다 작고, 방법이 중요해요
- 사진: Sgt. Justin A. Naylor, 미 육군 (퍼블릭 도메인, Wikimedia Commons)

### 6편 01 플라이오란  (`E6-SSC.dc.html`)

- 개념플라이오란?
- 늘어났다가 바로 튕기기
- ① 착지
- 늘어나며 힘 받기
- ② 전환
- 짧을수록 좋아요
- ③ 튕김
- 줄어들며 튕겨 나가기
- 달리기도 매 걸음 이 '스프링'을 써요
- 리뷰늘어났다 바로 줄어들면, 그냥 줄어들 때보다 힘이 커요
- Komi (2000) J Biomech · Nicol, Avela & Komi (2006) Sports Med · '접지 250ms 미만 = 빠른 튕김'은 코칭 관행이에요. 2024년 연구는 그 기준의 근거가 약하다고 봤어요

### 6편 02 효과 크기  (`E6-Effect.dc.html`)

- 효과 ①얼마나 좋아질까
- 플라이오만 하면 사소, 근력과 함께면 큼
- 메타분석 · 2023러닝 이코노미 효과 크기
- 0.19
- 사소
- 1.34
- 큼
- 플라이오만
- 근력 + 플라이오
- 메타분석15세션 · 7주 · 주 2회를 넘기면 효과가 더 컸어요
- Dudagoitia Barrio et al. (2023) Kinesiology · 체계적 리뷰 18편 · 메타분석 10편 · 효과 크기: 0.2 작음 · 0.5 중간 · 0.8 큼

### 6편 03 속도마다 다르다  (`E6-Speed.dc.html`)

- 효과 ②속도마다 다르다
- 속도에 따라 효과가 달라요
- 메타분석 · 2024이코노미가 좋아진 속도 범위
- 고중량 근력
- 근력+플라이오
- 플라이오만
- 가벼운 근력·등척성
- −0.27 · 확실성 중간
- −0.43
- 확실성 낮음
- −0.31
- 확실성 중간
- 효과 없음
- 7:30
- 6:00
- 5:00
- 4:17
- 3:45
- 3:20
- 가로축: 1km 페이스 · 오른쪽일수록 빠름
- 플라이오만 할 땐 5:00/km보다 느린 쪽에서만 작은 효과
- Llanos-Lagos et al. (2024) Sports Med · 효과 크기 음수 = 산소 비용 감소(좋아짐) · 근거 확실성은 논문 평가 · 고중량 효과는 빠를수록, VO2max가 높을수록 컸어요

### 6편 04 근력보다 나을까  (`E6-VsStrength.dc.html`)

- 효과 ③근력보다 나을까?
- 플라이오 vs 웨이트? 답은 '둘 다'
- +
- 고중량 쪽이 더 나을 수 있다
- 메타분석 · 2022최대에 가까운 무게와 비교
- 폭발 훈련 −4.8% · 고중량 −3.7%
- 메타분석 · 2017둘 다 좋아졌고, 크기는 비슷
- 병행함께 할 때 효과가 가장 컸어요 (효과 크기 1.34)
- Eihara et al. (2022) Sports Med Open · Denadai et al. (2017) Sports Med · Dudagoitia Barrio et al. (2023) · 사진: 미 육군 · 미 해병대 (퍼블릭 도메인, Wikimedia Commons)

### 6편 05 기록은  (`E6-Records.dc.html`)

- 효과 ④기록은?
- 2~5km 기록에 중간 효과
- 메타분석 · 511명
- 0.88
- 2~5km 기록 · 효과 크기 '중간'
- VO2max · vVO2max
- 그대로
- 엔진은 안 바뀌어요
- 실험 예시기록이 줄어든 폭
- 3km 기록
- −2.7%
- 6주 · 남성 러너 17명
- 2.4km 기록
- −3.9%
- 6주 · 경쟁 러너 36명
- 실험 · 중년 20명이코노미는 좋아졌지만 5km 기록은 그대로였어요
- Ramirez-Campillo et al. (2021) J Sports Sci · Spurrs et al. (2003) · Ramírez-Campillo et al. (2014) · Eihara et al. (2024) Eur J Sport Sci

### 6편 06 사람마다 다르다  (`E6-Responders.dc.html`)

- 효과 ⑤사람마다 다르다
- 크게 좋아진 사람은 10명 중 4명
- 실험 · 31명 · 8주플라이오 또는 맨몸 근력 추가
- 크게 좋아짐 13명 · 평균 −5.7%
- 좋아진 속도도 달랐어요: 18km/h만 · 12~14km/h만 · 12km/h 이하
- Patoz et al. (2023) Sports Biomech · 레크리에이션 러너 · 평균 2.1 ± 3.9% 개선 · 주법은 거의 그대로 · 속도: Saunders (2006) · Engeroff (2023) · Llanos-Lagos (2024)

### 6편 07 왜 좋아질까  (`E6-Why.dc.html`)

- 왜?어떻게 좋아질까
- 왜 좋아지는지는 아직 몰라요
- 더 단단한 스프링?
- 실험 · 17명6주 뒤 다리 강성↑ · 저자는 '제안'만
- 에너지가 덜 새는 힘줄?
- 실험 · 19명14주 뒤 힘줄 에너지 손실 −35%
- 신경이 근육을 더 잘 쓴다?
- 실험 · 18명폭발 훈련 9주 · VO2max 그대로, 5km 기록↑
- 메타분석힘줄 강성은 오히려 고중량 근력에서 더 확실히 올라요
- Spurrs (2003) · Fouré (2010) J Appl Physiol · Paavolainen (1999) J Appl Physiol · Kubo (2007) · Bohm (2015) Sports Med Open · Albracht & Arampatzis (2013)

### 6편 08 지쳐도 유지되는 힘  (`E6-Durability.dc.html`)

- 최신 경향지쳐도 유지되는 힘
- 근력+플라이오 10주, 90분 뒤가 달라졌어요
- 실험 · 잘 훈련된 남성 28명주 2회 · 10주
- 근력+플라이오
- 러닝만
- 90분째 산소
- −2.1%
- +0.6%
- 지친 뒤 버티기
- +35%
- −8%
- 고중량과 함께 했기 때문에 플라이오만의 효과는 몰라요
- Zanini et al. (2025) Med Sci Sports Exerc · 대조군은 지구력 훈련만 · 버티기 = 90분 달린 뒤 95% VO2max에서 버틴 시간 · 산소는 같은 속도에서 쓴 양(낮을수록 좋음)

### 6편 09 아주 작은 용량  (`E6-Micro.dc.html`)

- 방법 ①아주 작은 용량
- 하루 5분 홉도 논문이 있어요
- 5분
- 매일 · 6주 · 양발 홉
- 실험 · 아마추어 34명12·14km/h에서 이코노미 개선 · 10km/h는 그대로 · 부상 보고 없음
- 주 10~20분
- 워밍업 줄넘기 · 10주
- 실험 · 아마추어 96명반응성 근력 · 발 아치 강성 · 3km 기록 개선
- 단, 효과는 작고 사람마다 달라요
- Engeroff et al. (2023) Sci Rep · 10초 홉 세트를 늘리고 휴식을 줄이며 진행 · García-Pinillos et al. (2020) Int J Sports Physiol Perform · 주 2~4회, 줄넘기 시간은 주당 총합

### 6편 10 점프 사다리  (`E6-Ladder.dc.html`)

- 방법 ②쉬운 것부터
- 점프 사다리, 아래부터 한 칸씩
- 1
- 줄넘기
- 2
- 양발
- 포고
- 3
- 스킵
- 드릴
- 4
- 미니
- 허들
- 5
- 바운딩
- 6
- 한발
- 홉
- 7
- 드롭
- 점프
- 실험양발 → 한발, 제자리 → 전진일수록 부하↑
- 코치 해석이 순서를 러너에게 비교한 연구는 아직 없어요
- Baxter et al. (2021) Med Sci Sports Exerc (아킬레스건 부하) · 순서는 코칭 관행 · 드롭 점프는 20~30cm 낮은 높이부터

### 6편 11 아킬레스건 부하  (`E6-Load.dc.html`)

- 방법 ③아킬레스건 부하
- 한발 홉은 체중의 7.3배
- 앉아서 카프 레이즈
- 체중 × 0.5
- 한발로 앞으로 홉
- 체중 × 7.3
- 아킬레스건이 받는 최대 힘 (추정)
- 실험 · 환자 38명힘줄이 아프면 양발 · 제자리부터, 운동 중 통증은 10점 중 5점 이하로
- Baxter et al. (2021) Med Sci Sports Exerc · 건강한 성인 8명 · 추정 모델 · Silbernagel et al. (2007) 아킬레스건병증 실험 · 그림: Gray's Anatomy (퍼블릭 도메인)

### 6편 12 동작 ① 발목 스프링  (`E6-Moves1.dc.html`)

- 방법 ④동작 ① 발목 스프링
- 줄넘기 · 포고 · 스킵
- 줄넘기
- 발 앞쪽으로 낮게(2~5cm), 리듬 있게
- 양발 포고
- 무릎은 거의 고정, 발목으로만 빠르게
- A-스킵
- 무릎 들고, 지지발로 땅을 아래·뒤로 짧게
- 동작 설명은 코칭 관행 · 줄넘기 연구: García-Pinillos (2020) · 양발 홉 연구: Engeroff (2023) · 공통: 접지는 짧고 조용하게

### 6편 13 동작 ② 튕겨 나가기  (`E6-Moves2.dc.html`)

- 방법 ⑤동작 ② 튕겨 나가기
- 허들 홉 · 바운딩 · 드롭 점프
- 미니허들 양발 점프
- 10~15cm 허들, 넘을 때 짧게 튕기기
- 바운딩
- 과장된 달리기, 한 발씩 멀리·높게
- 낮은 드롭 점프
- 20~30cm에서 내려와 닿자마자 튀어 오르기
- 동작 설명은 코칭 관행 · 드롭 높이는 강도 기준이 아니에요 (Montoro-Bombú 2023) · 사진: 세단뛰기 선수, Marie-Lan Nguyen (CC BY 3.0, Wikimedia Commons)

### 6편 14 높은 박스  (`E6-Box.dc.html`)

- 팩트 체크높은 박스 = 강한 훈련?
- 박스 높이는 강도가 아니에요
- 높이 = 다리를 얼마나 접어 올리느냐
- =
- =
- 최대 힘 · 파워 · 힘 발달률 차이 없음
- 실험엘리트 핸드볼 10명 · 대학생 31명
- 리뷰 · 22개 실험드롭 높이도 강도 기준이 아니에요
- Koefoed et al. (2022) · Lopes Dos Santos et al. (2024) · Montoro-Bombú et al. (2023) Front Physiol · 한 번 뛸 때의 출력 비교예요 · 사진: 미 육군 (퍼블릭 도메인)

### 6편 15 연구들의 용량  (`E6-Dose.dc.html`)

- 방법 ⑥연구들의 용량
- 6~12주 · 주 1~3회, 세션당 약 60회부터
- 기간
- 6~12주
- 빈도
- 주 1~3회
- 세션당 접지
- 60→100+
- 일부 2차 자료
- 효과가 더 컸던 조건
- 7주·15회↑
- 주 2회 넘게 메타분석
- 접지 1번 = 한 발이든 두 발이든 땅에 닿는 1번
- Saunders (2006) · Spurrs (2003) · Ramírez-Campillo (2014) · Engeroff (2023) · García-Pinillos (2020) · Dudagoitia Barrio et al. (2023) · 세션당 접지 수는 일부 2차 자료

### 6편 16 8주 예시  (`E6-Program.dc.html`)

- 방법 ⑦8주 예시
- 8주 예시: 55회 → 125회
- 코치 해석연구 용량을 조합한 예시 · 검증된 단일 프로토콜 아님
- 55회
- 1~2주
- 포고
- 미니허들
- 90회
- 3~4주
- +바운딩
- +한발 포고
- 105회
- 5~6주
- +허들 홉
- +한발 홉
- 125회
- 7~8주
- +드롭 점프
- (경험자)
- 주 2회 · 사이에 하루 이상 쉬기 · 쿵쿵 소리가 나면 그 세트 끝
- 시작 볼륨: Spurrs (2003) · Ramírez-Campillo (2014) (2차 자료) · 진행 폭: 교과서 권장 범위 (2차 인용) · 9~10주는 유지 · 대회 전 조정 근거는 확인 못 함

### 6편 17 어디에 넣을까  (`E6-Week.dc.html`)

- 방법 ⑧어디에 넣을까
- 다리가 신선할 때, 짧게
- 월
- 쉬운 러닝
- + 플라이오
- 화
- 인터벌
- 수
- 고중량
- 근력
- 목
- 쉬운 러닝
- + 플라이오
- 금
- 휴식
- 토
- 롱런
- 일
- 휴식
- 코치 해석세션 앞부분에 · 하체가 무거운 날(썰매 등)과는 떨어뜨리기
- 같은 날 순서·간격을 비교한 실험은 아직 없어요
- 예시 주간표는 코치 해석 · 병행 근거: Dudagoitia Barrio (2023) · Llanos-Lagos (2024) · Zanini (2025)

### 6편 18 누가 조심할까  (`E6-Safety.dc.html`)

- 안전누가 조심할까
- 점프가 아니라 '갑자기 많이'가 문제
- 힘줄 통증이 있다
- 실험양발·제자리부터 · 통증 10점 중 5점 이하
- 러닝과 점프를 함께 늘리는 시기
- 상관 · 배구 선수한 번에 하나씩 늘리기
- 입문자 · 노년층
- 메타분석감독 아래 · 세트당 10회, 운동당 3세트 이하
- 골 손상 · 골다공증 · 임신
- 의료진과 상의 · 이번 조사에선 근거 확인 못 함
- Silbernagel (2007) · Visnes & Bahr (2013) 배구 코호트, 러너엔 외삽 · Moran (2018) · Vetrovsky (2019) Sports Med: 평균 58~79세, 부상 증가 보고 없음

### 6편 19 엘리트 ① 잉에브릭센  (`E6-Elites.dc.html`)

- 현장 ①잉에브릭센의 한 주
- 점프 날과 웨이트 날을 나눠요
- 현장 사례 · 스폰서 콘텐츠야콥 잉에브릭센 · 주 4회 근력
- 월
- 드릴
- 플라이오
- 화
- 수
- 홉·점프
- 허들
- 목
- 금
- 웨이트
- 2세트
- 토
- 일
- 웨이트
- 3세트
- "It's all about very explosive movement."
- 잉에브릭센, COROS 인터뷰
- 질적 연구노르웨이 정상급 코치 12명: 근력은 지구력을 돕는 2순위
- COROS 스폰서 콘텐츠 (페이지마다 운동 목록이 달라요) · Haugen et al. (2026) J Strength Cond Res (연 20~200시간) · 효과의 증거는 아니에요

### 6편 20 엘리트 ② 언덕과 드릴  (`E6-Elites2.dc.html`)

- 현장 ②케냐 · 카노바 · 리디아드
- 엘리트의 플라이오는 언덕과 드릴
- 케냐 이텐의 흙 트랙
- 현장 사례체험기 · 블로그 · 해설 글 · 효과의 증거 아님
- 이텐 러너
- 러닝 뒤 드릴 10분 이상 · 짧은 언덕 반복
- 레나토 카노바
- 언덕 전력 질주 · 바운딩·스킵 서킷
- 아서 리디아드
- 오르막에서 발끝으로 튕기며 오르기
- Running Writings · LetsRun 포럼 · 이텐 체험기 · 리디아드 해설 글 · Haugen et al. (2022) Sports Med Open · 사진: edskoch (CC BY 2.0, Wikimedia Commons)

### 6편 21 하이록스 관점  (`E6-Hyrox.dc.html`)

- 하이록스버피 브로드 점프
- 하이록스 점프는 다른 자극
- 59%
- 러닝
- 러닝 51.2분 스테이션 32.8분
- 관찰 · 11명모의 경기 총 86.5분
- 버피 예시 · 경기는 버피 브로드 점프 80m
- 코치 해석바닥까지 내려갔다 두 발로 멀리 → 연속 튕기기와 달라요 · 효과 연구는 없어요
- Brandt et al. (2025) Front Physiol · HYROX 룰북 25/26 · 사진: Sgt. Ryan Young, 미 해병대 (퍼블릭 도메인, Wikimedia Commons)

### 6편 22 팩트 체크 ① 틀려요  (`E6-FactCheck.dc.html`)

- 팩트 체크 ①틀려요
- 흔한 플라이오 상식 ①
- 틀려요높은 박스일수록 효과가 크다
- 높이를 바꿔도 힘·파워 차이 없음 (2개 연구)
- 틀려요점프는 무릎에 나쁘다
- 문제는 '갑자기 많이'와 통증 · 점프가 든 예방 프로그램에서 여성 선수 ACL 부상↓
- 틀려요러너는 근력보다 플라이오가 낫다
- 고중량이 나을 수 있고, 함께 할 때 가장 컸어요
- Koefoed (2022) · Lopes Dos Santos (2024) · AAFP (2011) 메타분석 요약 · Vetrovsky (2019) · Eihara (2022) · Dudagoitia Barrio (2023)

### 6편 23 팩트 체크 ② 틀려요  (`E6-FactCheck2.dc.html`)

- 팩트 체크 ②틀려요
- 흔한 플라이오 상식 ②
- 틀려요플라이오는 젊은 선수만
- 58~79세도 감독하면 부상 증가 없음 · 효과는 젊을수록 컸어요
- 틀려요플라이오하면 VO2max가 오른다
- VO2max는 그대로 · 좋아지는 건 연비 쪽
- 틀려요하이록스 버피 점프면 충분하다
- 경기 종목은 버피 브로드 점프 · 연속 튕기기와 다른 자극 · 연구 없음
- Vetrovsky (2019) · Moran (2018) · Dudagoitia Barrio (2023) · Ramirez-Campillo (2021) · Blagrove (2018) · HYROX 룰북 · Brandt (2025)

### 6편 24 팩트 체크 ③ 애매해요·맞아요  (`E6-FactCheck3.dc.html`)

- 팩트 체크 ③애매해요 · 맞아요
- 애매한 것 · 맞는 것
- 애매해요효과는 누구에게나 같다
- 크게 좋아진 사람 42% · 좋아진 속도도 연구마다 달라요
- 애매해요많이 뛸수록 좋다
- 7주·15회 넘으면 효과↑ · 급히 늘리면 힘줄 위험
- 맞아요줄넘기도 플라이오다
- 가장 쉬운 단계 · 10주에 3km 기록 개선
- 맞아요플라이오로 기록이 좋아진다
- 2~5km 중간 효과 · 단, 중년 5km는 그대로인 연구도
- Patoz (2023) · Dudagoitia Barrio (2023) · Visnes & Bahr (2013) · García-Pinillos (2020) · Ramirez-Campillo (2021) · Eihara (2024)

### 6편 25 이번 주부터  (`E6-Todo.dc.html`)

- 정리이번 주부터
- 이번 주부터 이렇게 시작해요
- 1
- 러닝 전 줄넘기 3~5분
- 실험워밍업 줄넘기로 3km 기록 개선
- 2
- 주 2회 · 짧은 홉 50~60회부터
- 코치 해석쿵쿵 소리 나면 그 세트 끝
- 3
- 고중량 근력과 함께
- 메타분석함께 할 때 효과가 가장 컸어요
- 4
- 힘줄이 아프면 양발·저강도로
- 실험통증 10점 중 5점 이하
- García-Pinillos (2020) · 시작 볼륨: Spurrs (2003) · Ramírez-Campillo (2014) (2차 자료) · Dudagoitia Barrio (2023) · Llanos-Lagos (2024) · Silbernagel (2007)

### 6편 26 참고문헌 ①  (`E6-Refs.dc.html`)

- 참고문헌 ①6편 플라이오메트릭
- 1Komi (2000) J Biomech · 신장-단축 주기 리뷰
- 2Nicol, Avela & Komi (2006) Sports Med · SSC 리뷰
- 3Spurrs et al. (2003) Eur J Appl Physiol · 6주 플라이오
- 4Turner et al. (2003) J Strength Cond Res · 6주 플라이오
- 5Paavolainen et al. (1999) J Appl Physiol · 폭발 훈련 9주
- 6Saunders et al. (2006) J Strength Cond Res · 9주 플라이오
- 7Berryman et al. (2010) J Strength Cond Res · 플라이오 vs 웨이트
- 8Ramírez-Campillo et al. (2014) J Strength Cond Res · 6주
- 9Engeroff et al. (2023) Sci Rep · 매일 5분 홉
- 10García-Pinillos et al. (2020) Int J Sports Physiol Perform · 줄넘기
- 11Eihara et al. (2024) Eur J Sport Sci · 중년 러너
- 12Patoz et al. (2023) Sports Biomech · 개인차
- 13Kubo et al. (2007) Med Sci Sports Exerc · 힘줄·관절 강성
- 14Fouré et al. (2010) J Appl Physiol · 힘줄 에너지 손실
- 15Bohm et al. (2015) Sports Med Open · 힘줄 적응 메타분석
- 16Albracht & Arampatzis (2013) Eur J Appl Physiol · 종아리 고부하
- 17Dudagoitia Barrio et al. (2023) Kinesiology · 메타분석
- 18Llanos-Lagos et al. (2024) Sports Med · 속도별 효과
- 근거 수준과 세부 수치는 말하기 대본(e6-script.md)에 정리

### 6편 27 참고문헌 ②  (`E6-Refs2.dc.html`)

- 참고문헌 ②6편 플라이오메트릭
- 19Eihara et al. (2022) Sports Med Open · 고중량 vs 플라이오
- 20Denadai et al. (2017) Sports Med · 폭발 vs 고중량
- 21Ramirez-Campillo et al. (2021) J Sports Sci · 점프 훈련 메타분석
- 22Blagrove et al. (2018) Sports Med · 근력 훈련 체계적 리뷰
- 23Zanini et al. (2025) Med Sci Sports Exerc · 90분 내구성
- 24Baxter et al. (2021) Med Sci Sports Exerc · 아킬레스건 부하
- 25Silbernagel et al. (2007) · 아킬레스건병증 통증 관리 실험
- 26Visnes & Bahr (2013) · 배구 선수 슬개건 코호트
- 27Moran et al. (2018) Sports Med · 노년층 점프 메타분석
- 28Vetrovsky et al. (2019) Sports Med · 노년층 플라이오 안전
- 29Koefoed et al. (2022) · 박스 높이 (핸드볼 10명)
- 30Lopes Dos Santos et al. (2024) · 박스 높이 (31명)
- 31Montoro-Bombú et al. (2023) Front Physiol · 드롭 높이와 강도
- 32Brandt et al. (2025) Front Physiol · 하이록스 모의 경기
- 33Haugen et al. (2022) Sports Med Open · 세계 정상급 훈련
- 34Haugen et al. (2026) J Strength Cond Res · 노르웨이 코치 12명
- 35AAFP (2011) · 여성 ACL 예방 메타분석 요약
- 36현장 사례: COROS 스폰서 콘텐츠 · Running Writings · LetsRun · HYROX 룰북 25/26
- 현장 사례는 효과의 증거가 아니에요

### 6편 28 다음 편 예고  (`E6-Next.dc.html`)

- 다음 편 예고7편 러너의 체형
- 러너에게 중요한 체형
- 가는 종아리 · 긴 정강이, 타고나는 걸까?
- 마른 사람이 무조건 잘 달릴까?
- 다리가 길면 유리할까?
- 하이록스 선수의 몸은 달라야 할까?
- 사진: Bob Ramsak (CC BY-SA 4.0, Wikimedia Commons) · 2015 류블랴나 마라톤


## 7편

### 7편 00 훅  (`E7-Hook.dc.html`)

- 러닝 3요소 · 7편 · 러너의 체형
- 러너에게 좋은 체형, 정해져 있을까?
- 마라톤
- BMI 19.6
- 상위 100명 평균
- 100m
- BMI 23.3
- 상위 100명 평균
- 하이록스
- BMI 약 24.7
- 세계챔피언 1명
- 뼈는 못 바꿔요. 바꿀 수 있는 것만 골라 볼게요
- BMI: Sedeaud et al. (2014) PLoS One, 남자 세계 상위 100명 평균 · 하이록스: 세계챔피언 사례연구(2026) 1명의 키·체중으로 계산 · 실루엣은 같은 키로 그린 개념도

### 7편 01 엘리트 마라토너 평균  (`E7-Elite.dc.html`)

- 엘리트 체격평균은?
- 엘리트 마라토너의 평균
- 171.9cm
- 키
- 57.9kg
- 체중
- 19.6
- BMI
- 비교 · 기술남자 세계 상위 100명 · 1996~2011
- 원문 · 소규모케냐 크로스컨트리 상위권
- 남 13명 170~173cm · 53.8~56.7kg · 체지방 6.6~7.4%
- 여 7명 168cm · 47.8kg · 체지방 16%
- 체지방률은 측정법마다 달라서 연구끼리 비교하면 안 돼요. 여자 엘리트 자료는 아직 적어요.
- Sedeaud et al. (2014) PLoS One · Billat et al. (2003) Med Sci Sports Exerc (원문 확인)

### 7편 02 키는 제각각  (`E7-Height.dc.html`)

- 엘리트 체격키
- 키는 156cm부터 190cm까지
- 비교회색: 마라톤 상위 100명 범위 · 파랑: 약 68% 구간(계산)
- 평균 171.9
- 156
- 190
- 1996 우승자 158
- 2024 우승자 181
- 1912 우승자 188
- 150
- 160
- 170
- 180
- 190
- 키 (cm)
- 키 자체보다 키 대비 가벼움과 더위가 관건으로 보여요상관
- Sedeaud 2014 (평균 ± 표준편차) · Marc et al. (2014) J Sports Sci (범위, 1990~2011) · 올림픽 우승자: Topendsports 집계(출처 혼재, 현장 자료)

### 7편 03 종목마다 다른 체격  (`E7-Ladder.dc.html`)

- 엘리트 체격종목별
- 빠른 종목일수록 무겁고 커요
- 비교● 논문 평균 · ◆ 사례 1명 · ○ 블로그 집계
- 하이록스 챔피언 1명
- 약 24.7
- 하이록스 Elite 15 남
- 약 24.2
- 100m 상위 100명
- 23.3
- 하이록스 Elite 15 여
- 약 21.8
- 마라톤 상위 100명
- 19.6
- 에리트레아 엘리트
- 18.9
- 케냐 엘리트 남
- 18.6~18.9
- 18
- 20
- 22
- 24
- 26
- 종목마다 맞는 체격이 다르고, 최상위일수록 범위가 좁아져요
- Sedeaud 2014 (8개 종목 상위 100명, 속도–BMI r = 0.71) · Billat 2003 · Lucia 2006 · 하이록스 챔피언 사례연구 2026 · Rox Lyfe 블로그 집계(Elite 15) · 일부 BMI는 평균 키·체중으로 계산

### 7편 04 마를수록 빠를까?  (`E7-Parabola.dc.html`)

- 엘리트 체격마를수록?
- 마를수록 빠를까? 최적점이 있어요
- 비교마라톤 세계 상위 100명 · 곡선은 개념도
- 최적점
- 너무 가벼우면
- 느려짐 · 부상↑
- 무거운 쪽
- 느려짐
- BMI →
- ↑ 속도
- 비교 · 184명이미 마른 최상위권 남자들
- 피하지방을 다 더한 값은 기록과 관련이 없었어요
- Marc et al. (2014) J Sports Sci (BMI–속도 포물선, 최적 BMI 값은 미확인) · Arrese & Ostáriz (2006) J Sports Sci (피하지방 6곳 합)

### 7편 05 너무 가벼우면  (`E7-REDs.dc.html`)

- 너무 가벼우면REDs
- 너무 적게 먹고 달리면 뼈가 먼저 다쳐요
- 적게 먹고
- 많이 달림
- 호르몬
- 저하
- 뼈
- 약해짐
- 골부상
- 증가
- 4.5배월경이 멈추거나 테스토스테론이 낮은 엘리트 장거리 선수의 골부상 비교
- 이 상태를 REDs라고 불러요. 남녀 모두 생겨요IOC 합의문
- Heikura et al. (2018) IJSNEM (국가대표·세계급 장거리 선수, 횡단 연구) · Mountjoy et al. (2023) BJSM, IOC REDs 합의문

### 7편 06 위험이 겹치면  (`E7-BoneRisk.dc.html`)

- 너무 가벼우면위험 신호
- 위험 요인이 겹칠수록 골부상이 늘어요
- 전향 코호트운동하는 여성 · 위험 요인 하나일 때 발생률
- 주 12시간 이상 운동
- 14.7%
- BMI 21 미만
- 15.3%
- 저골량
- 21.0%
- 요인이 겹치면
- 약 30~50%
- 비교 · 남자 156명남자도 예외가 아니에요
- 대학 장거리 선수 27%가 골스트레스 손상 · 위험 점수 1점마다 위험 +37%
- Barrack et al. (2014) Am J Sports Med · Kraus et al. (2019) BJSM (BMI 하나만으로는 유의하지 않음)

### 7편 07 무게의 위치  (`E7-Location.dc.html`)

- 무게의 과학어디에 붙나
- 같은 1kg도 발에 달면 3~4배
- 실험 · 15명다리 한쪽에 1kg · 3m/s · 에너지 증가
- 1kg
- 1kg
- 1kg
- 허벅지
- 남녀
- +4%
- 정강이
- 남
- +8%
- 여
- +11%
- 발
- 남
- +11%
- 여
- +16%
- Coifman 외, Applied Ergonomics (2023 온라인) · Martin (1985) MSSE: 발 1kg ≈ +7.2%, 허벅지의 약 2배 · 다리 끝 무게일수록 휘두르는 데 더 들어요

### 7편 08 신발 100g  (`E7-Shoes.dc.html`)

- 무게의 과학신발
- 신발 한 짝 100g = 에너지 +1.1%
- 같은 신발에 무게만 더한 실험
- +1.1%
- 에너지 · 한 짝 100g마다
- +0.78%
- 3km 기록 · 100g마다
- 실험 · 18명5km 20분 이내 남자
- 쿠션·반발을 포기한 가벼움까지 같다는 근거는 아니에요
- Hoogkamer, Kipp, Spiering & Kram (2016) MSSE · Nike 연구비 지원 · 사진: Modifyphysio (CC BY-SA 4.0, Wikimedia Commons)

### 7편 09 몸을 받치는 비용  (`E7-Support.dc.html`)

- 무게의 과학받치는 비용
- 달리기 에너지의 큰 몫은 몸을 받치는 데 써요
- 실험 · 10명하네스로 체중만 줄였을 때 에너지 변화
- 체중 100%
- 기준
- 75%
- -19%
- 50%
- -38%
- 25%
- -55%
- 파랑은 실측, 점선은 비례했다면 · 저자 추정: 받치는 비용이 최대 74%
- Teunissen, Grabowski & Kram (2007) J Exp Biol · 동호인 10명 · 3m/s · 순대사율 기준

### 7편 10 짐을 달면  (`E7-Cargo.dc.html`)

- 무게의 과학짐 실험
- 엔진은 그대로인데 짐만 늘면 느려져요
- 실험 · 6명몸통에 체중의 5·10·15% 짐
- 짐
- 12분 달리기 거리
- 체중 +5% 짐
- 약 −89m
- 체중 +15% 짐
- 약 −277m
- 속도 −8.6%
- 최대 산소섭취량(L/분) 그대로체중당 VO2max·기록 ↓
- 흔한 '1kg = km당 몇 초' 공식은 이 짐 실험을 지방 감량에 옮겨 쓴 추정이에요
- Cureton et al. (1978) Med Sci Sports · NCBI Bookshelf(IOM) 요약 · 짐 1%당 12분 거리 약 18m 감소

### 7편 11 1kg = km당 몇 초?  (`E7-PerKg.dc.html`)

- 무게의 과학1kg = 몇 초?
- 체중 1kg = km당 몇 초?
- 예: 체중 70kg · 1km 5:00 러너가 1kg 줄면
- 2.4초
- 짐 실험 기준
- 체중 1%당 기록 약 0.57%
- 4.3초
- 단순 비례 가정
- 체중 1% = 기록 1%
- 지방만 빠지고 훈련·근육·에너지가 그대로일 때만 · 굶어서 빼면 오히려 느려져요
- 판정: 애매해요코치 계산
- Cureton 1978 짐 실험(15% 짐 → 속도 −8.6%)으로 계산 · 비례 가정은 단순 계산 · REDs: Mountjoy et al. (2023) BJSM

### 7편 12 더위와 체격  (`E7-Heat.dc.html`)

- 무게의 과학더위
- 더울수록 작은 몸이 유리해요
- 모델 계산열이 쌓이지 않고 버틸 수 있는 최고 속도
- 35°C
- 습도 60%
- 45kg
- 2:13 페이스까지
- 마라톤 · 19.1km/h
- 75kg
- 3:28 페이스까지
- 마라톤 · 12.2km/h
- 비교 · 16명실측도 같은 방향
- 35°C에선 무거울수록 열이 더 쌓였어요 · 15°C에선 관련 없음
- Dennis & Noakes (1999) Eur J Appl Physiol (모델 계산) · Marino et al. (2000) Pflügers Arch (r = 0.74, 고도로 훈련된 러너)

### 7편 13 다리 길이·뒤꿈치  (`E7-Legs.dc.html`)

- 몸의 비율다리·뒤꿈치
- 다리 길이·뒤꿈치는 '관련'까지만
- 긴 다리 (체중 대비)
- 에너지 비용이 낮은 쪽과 관련 · 18명상관
- 긴 정강이
- 16km/h 이코노미와 관련 · 13명상관
- 짧은 뒤꿈치(힘줄 지렛대)
- 짧을수록 경제적 vs 케냐 엘리트는 길다 vs 관련 없음엇갈림
- Steudel-Numbers et al. (2007) J Hum Evol · Laumets et al. (2017) J Hum Kinet · Scholz 2008 · Hansen 2021 · Kunimasa 2014 · van Werkhoven & Piazza 2017 · 그림: Gray's Anatomy (퍼블릭 도메인)

### 7편 14 가는 하퇴  (`E7-Calf.dc.html`)

- 몸의 비율하퇴
- 가는 하퇴, 좋은 이코노미
- 굵은 하퇴 · 비용↑
- 가는 하퇴 · 비용↓
- 비교케냐·덴마크 성인 + 훈련 안 한 청소년
- 하퇴가 1cm² 굵을수록 km당 산소 비용↑ · 굵기·길이를 보정하면 나라 차이가 사라졌어요
- 비교 · 7 vs 9명에리트레아 vs 스페인 엘리트
- 종아리 둘레 30.9cm로 더 가늘고, 이코노미가 더 좋았어요
- Larsen 외 (2026) Exp Physiol (정정 공지 있음) · Berry (2026) 해설 · Lucia et al. (2006) APNM · 다리 끝이 가벼우면 유리하다는 7장 실험과 같은 원리일 수 있다는 건 추론이에요

### 7편 15 동아프리카  (`E7-EastAfrica.dc.html`)

- 몸의 비율동아프리카
- 동아프리카, 체형만은 아니에요
- 케냐 이텐 · 훈련 마을
- 1체중을 맞춰도 5~8% 더 경제적
- 아프리카 vs 백인 러너 8명씩 · 10km 32~33분비교 · 원문
- 2케냐 엘리트끼리는 이코노미로 기록 설명 못 해요
- 케냐 장거리 선수 32명상관
- 3VO2max 속도로 달린 거리가 차이의 59% 설명
- 케냐 엘리트 남자 · vVO2max 기준상관 · 원문
- Weston et al. (2000) MSSE · Mooses et al. (2015) J Sports Sci · Billat et al. (2003) MSSE: 유전·훈련·환경·생활의 조합 · 사진: Shadychiri (CC BY-SA 4.0, Wikimedia Commons)

### 7편 16 근육이 많으면 느릴까?  (`E7-Muscle.dc.html`)

- 몸의 비율근육
- 근력운동 8주, 이코노미 +5%
- 무작위 실험 · 17명하프 스쿼트 4회×4세트 · 주 3회
- +33%최대근력
- +5%이코노미
- +21%지칠 때까지 시간
- 그대로체중·VO2max
- 메타분석 · 652명고중량 근력 → 이코노미 소폭 개선
- 실험 · 50명남자는 시즌 중 새로 시작하면 효과 불확실
- Støren et al. (2008) MSSE (원문) · Llanos-Lagos et al. (2024) Sports Med · Barnes et al. (2013) MSSE (대학 크로스컨트리) · 사진: 미 해병대 (퍼블릭 도메인)

### 7편 17 체중보다 체지방  (`E7-Fat.dc.html`)

- 몸의 비율지방
- 체중은 그대로, 지방과 기록이 바뀌었어요
- 관찰 · 37명최상위권 러너 · 3년 훈련
- 기록
- 좋아짐
- 피하지방
- 복부·허벅지·종아리
- 체중
- 변화 없음
- 상관 · 126명동호인 마라토너
- 훈련 속도·체지방률이 기록을 예측 · 둘이 얽혀 원인은 못 갈라요
- Legaz & Eston (2005) BJSM · Barandun et al. (2012) OAJSM

### 7편 18 하이록스 시간 구성  (`E7-HyroxTime.dc.html`)

- 몸의 비율하이록스
- 하이록스 시간의 절반은 러닝
- 스테이션 예: 썰매 밀기
- 약 50%
- 엘리트 경기 39,696건
- 약 59%
- 동호인 모의 경기 11명
- 하이록스도 러닝 엔진이 기본이에요코치 해석
- Rappelt et al. (2026) Front Physiol (러닝 비중 일부는 2차 확인) · Brandt et al. (2025) Front Physiol: 러닝 51.2분 / 86.5분 · 사진: HybridFitty (CC BY 4.0, Wikimedia Commons)

### 7편 19 하이록스 체격  (`E7-HyroxBody.dc.html`)

- 몸의 비율하이록스 체격
- 하이록스는 체격 계산이 달라요
- 마라톤 상위 100명
- 19.6
- 하이록스 Elite 15 남
- 24.2
- 하이록스 챔피언 1명
- 24.7
- BMI (막대 시작 = 15)
- 상관 · 동호인 11명모의 경기 기록과의 관계
- 관련 있음
- VO2max · 지구력 훈련량 · 낮은 체지방
- 관련 없음
- 근육량 · 악력
- 유산소 엔진 + 충분한 근력 + 과하지 않은 지방코치 해석
- Sedeaud 2014 · Rox Lyfe 블로그 집계 (Elite 15 중앙값) · 하이록스 세계챔피언 사례연구 (2026) Ger J Exerc Sport Res · Brandt et al. (2025) Front Physiol

### 7편 20 바꿀 수 없는 것 vs 있는 것  (`E7-Fixed.dc.html`)

- 정리무엇을 바꾸나
- 뼈는 두고, 나머지를 다뤄요
- 못 바꿔요
- 키 · 다리 길이
- 뒤꿈치·힘줄 구조
- 골격 폭
- 여성의 필수 지방
- 바꿀 수 있어요
- 체지방 (천천히)
- 근력·힘줄 강성
- 신발·짐의 무게
- 더운 날 페이스
- 건강하게 바꾸려면: 충분히 먹고, 천천히, 근력운동과 함께코치 해석
- Cureton & Sparling (1980) 필수 지방 · Støren 2008 · Hoogkamer 2016 · Coifman · Dennis & Noakes 1999 · Mountjoy 2023 (REDs)

### 7편 21 팩트 체크 ① 틀려요·맞아요  (`E7-FactCheck.dc.html`)

- 팩트 체크 ①틀려요·맞아요
- 체형 상식, 틀려요 · 맞아요
- 마른 사람이 무조건 잘 달린다
- 최적점이 있고, 너무 가벼우면 뼈가 다쳐요상관
- 같은 무게도 발 쪽이 더 비싸다
- 1kg당 허벅지 +4% · 발 +11~16%실험
- 안 쓰는 무게(짐)는 느리게 한다
- 체중 15% 짐 → 속도 −8.6% (6명)실험
- Marc 2014 · Arrese & Ostáriz 2006 · Heikura 2018 · Coifman (Applied Ergonomics) · Cureton 1978

### 7편 22 팩트 체크 ② 애매해요  (`E7-FactCheck2.dc.html`)

- 팩트 체크 ②애매해요
- 체형 상식, 애매해요
- 키 작은 사람이 마라톤에 유리
- 우승자 158~188cm · 키 대비 가벼움·더위가 관건상관
- 체중 1kg = km당 몇 초
- 가정에 따라 약 2.4~4.3초 · 지방만 빠질 때만코치 계산
- 근육이 많으면 느리다
- 근력운동 8주: 체중 그대로, 이코노미 +5%실험
- 하이록스는 근육형이 유리
- 동호인 11명: 근육량·악력은 기록과 무관상관
- Marc 2014 · Topendsports(집계) · Cureton 1978 · Støren 2008 · Brandt 2025

### 7편 23 팩트 체크 ③ 관련은 있어요  (`E7-FactCheck3.dc.html`)

- 팩트 체크 ③관련은 있어요
- 체형 상식, 관련은 있어요
- 다리가 길면 유리하다
- 약한 상관 (13~32명) · 바꿀 수도 없어요상관
- 동아프리카는 체형 덕분
- 가는 하퇴와 얽혀 있지만, 체형만은 아니에요상관
- 신발은 가벼울수록 빠르다
- 무게만 보면 100g당 +1.1% · 쿠션·반발은 별개실험
- Steudel-Numbers 2007 · Laumets 2017 · Mooses 2015 · Larsen 2026 · Weston 2000 · Hoogkamer 2016

### 7편 24 이번 주부터  (`E7-Todo.dc.html`)

- 정리할 일
- 이번 주부터 할 일
- 1체중계 목표보다 충분히 먹기
- 월경이 멈추거나 뼈 부상이 잦으면 전문가와
- 2근력운동 주 2~3회
- 체중은 거의 그대로, 이코노미는 좋아질 수 있어요
- 3발에 붙는 무게부터 확인
- 신발 무게 · 짐은 발목보다 몸통 쪽에
- 4더운 날은 페이스를 보수적으로
- 특히 체격이 큰 러너
- 코치 해석Mountjoy 2023 · Støren 2008 · Coifman · Dennis & Noakes 1999 바탕
- 연구 결과를 바탕으로 한 코치 해석이에요 · 건강 문제는 의료 전문가와 상의하세요

### 7편 25 정리  (`E7-Summary.dc.html`)

- 정리한 장 요약
- 체중계보다 어디에, 무엇이
- 뼈받아들여요
- 키·다리·뒤꿈치는 못 바꿔요
- 지방천천히, 건강하게
- 굶으면 뼈가 먼저 다쳐요
- 근육종목에 맞게
- 러너는 힘줄·신경, 하이록스는 근력도 기록 요소
- 엘리트 체형은 결과이지 처방이 아니에요코치 해석
- 7편 근거 요약 · 하이록스 근력 요소: HYROX 수행 분석 리뷰 (2025) Strength Cond J

### 7편 26 참고문헌 ①  (`E7-Refs.dc.html`)

- 참고문헌①
- 1Sedeaud A et al. (2014) PLoS One · 종목별 BMI
- 2Marc A et al. (2014) J Sports Sci · 마라톤 체형 추세
- 3Billat V et al. (2003) Med Sci Sports Exerc · 케냐 엘리트
- 4Lucia A et al. (2006) Appl Physiol Nutr Metab · 에리트레아
- 5Kong PW, de Heer H (2008) J Sports Sci Med · 케냐 체형
- 6Arrese AL, Ostáriz ES (2006) J Sports Sci · 피하지방
- 7Legaz A, Eston R (2005) Br J Sports Med · 3년 추적
- 8Barandun U et al. (2012) Open Access J Sports Med
- 9Heikura IA et al. (2018) Int J Sport Nutr Exerc Metab
- 10Barrack MT et al. (2014) Am J Sports Med
- 11Kraus E et al. (2019) Br J Sports Med
- 12Mountjoy M et al. (2023) Br J Sports Med · IOC REDs
- 13Coifman I et al. Applied Ergonomics (2023 온라인)
- 14Martin PE (1985) Med Sci Sports Exerc
- 15Hoogkamer W et al. (2016) Med Sci Sports Exerc
- 16Teunissen LPJ et al. (2007) J Exp Biol
- 17Cureton KJ et al. (1978) Med Sci Sports
- 18Cureton KJ, Sparling PB (1980) Med Sci Sports Exerc

### 7편 27 참고문헌 ②  (`E7-Refs2.dc.html`)

- 참고문헌②
- 19Dennis SC, Noakes TD (1999) Eur J Appl Physiol
- 20Marino FE et al. (2000) Pflügers Arch
- 21Steudel-Numbers KL et al. (2007) J Hum Evol
- 22Laumets R et al. (2017) J Hum Kinet
- 23Scholz MN et al. (2008) J Exp Biol
- 24Hansen 외 (2021) Physiol Rep
- 25Kunimasa Y et al. (2014) Scand J Med Sci Sports
- 26van Werkhoven H, Piazza SJ (2017) J Appl Biomech
- 27Larsen 외 (2026) Exp Physiol · Berry (2026) 해설
- 28Weston AR et al. (2000) Med Sci Sports Exerc
- 29Mooses M et al. (2015) J Sports Sci
- 30Støren Ø et al. (2008) Med Sci Sports Exerc
- 31Llanos-Lagos C et al. (2024) Sports Med
- 32Barnes KR et al. (2013) Med Sci Sports Exerc
- 33Brandt T et al. (2025) Front Physiol · 하이록스
- 34Rappelt L et al. (2026) Front Physiol · 하이록스 기록
- 35하이록스 세계챔피언 사례연구 (2026) Ger J Exerc Sport Res
- 36HYROX 리뷰 (2025) Strength Cond J · Rox Lyfe · Topendsports(집계)

