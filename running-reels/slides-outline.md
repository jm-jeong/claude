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


## c편

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


## 1편

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
- 나이키 4%의 정체, 러닝 이코노미
- 4% 빨라진다는 말이 아니에요. 같은 속도에서 에너지를 4% 덜 쓴다는 뜻이에요.
- 신발 이름
- 4%
- 2017 · 베이퍼플라이 4%
- =?
- 실제 의미
- 러닝 이코노미
- 같은 속도, 덜 쓰는 에너지

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

### 3편 03 러닝 이코노미란  (`E3-Def.dc.html`)

- 개념러닝 이코노미란
- 러닝 이코노미 = 1km 가는 데 드는 산소
- 자동차로 치면 연비 · 단위 ml/kg/km · 낮을수록 좋아요
- VO2max 페이스=VO2max÷이코노미
- VO2max 60으로 똑같을 때 · 막대 = 1km에 드는 산소
- 1편 예시 러너
- 평범한 연비
- 240
- 4:00/km
- 10% 좋아지면
- 216
- 3:36/km
- 엘리트 수준
- Breaking2 후보 평균
- 191
- 3:11/km
- −24초엔진(VO2max)이 같아도 이코노미가 10% 좋으면 VO2max 페이스가 1km에 24초 빨라져요.
- 계산 예시: 60 ÷ 이코노미 = km/분 · 1편 러너 기준 · 191은 Jones et al. (2021) Breaking2 후보 16명 평균

### 3편 04 측정법  (`E3-Measure.dc.html`)

- 개념논문은 이렇게 잰다
- 러닝 이코노미 측정 = 역치 아래 속도에서 산소 재기
- 1러닝머신 경사 1%
- 야외에서 받는 공기 저항만큼 비용을 맞추려고 (1%가 가장 비슷)
- 2역치보다 느린 속도 여러 단계
- 단계마다 3~5분 · 산소가 안정(정상 상태)될 때까지 · 젖산이 쌓이면 산소로 다 못 잼
- 3마스크로 마지막 1~2분 평균
- 들이쉬고 내쉰 산소 → ml/kg/분
- 4속도로 나눠서 1km당으로
- ml/kg/분 ÷ km/분 = ml/kg/km · 최신 연구는 탄수화물·지방 비율까지 넣어 kcal/kg/km
- 5조건 통제
- 같은 시간대 · 식사·카페인·전날 운동 · 같은 신발
- 래드클리프 측정 예경사 1% · 3분 단계 · 16km/h에서의 값으로 11년 비교
- ±2.5%같은 사람을 다시 재도 1.3~5% 흔들려요. 엘리트에서 의미 있는 변화는 약 2.2~2.6% 이상.
- Jones & Doust (1996) J Sports Sci · Barnes & Kilding (2015) Sports Med Open · Jones (2006) · Støren et al. (2008) · 시계는 산소를 재지 않아 이코노미를 직접 알 수 없어요

### 3편 05 이코노미 차이  (`E3-Variance.dc.html`)

- 개념얼마나 차이 날까
- VO2max가 비슷해도 러닝 이코노미는 최대 30% 차이
- 고전 연구 · 1980 VO2max가 비슷한 엘리트 러너 12명
- 이코노미 좋음
- 이코노미 나쁨
- 10km 빠름
- 10km 느림
- 같은 엔진인데도 10km 기록 차이를 이코노미가 대부분 설명했어요
- 훈련된 러너끼리도
- 같은 VO2max에서 최대 30% 차이
- 그래서
- VO2max만으로는 기록을 다 설명 못 해요 → 3요소를 따로 봐야 하는 이유
- Conley & Krahenbuhl (1980) Med Sci Sports Exerc · Barnes & Kilding (2015) Sports Med Open · 그래프는 개념도

### 3편 06 동아프리카  (`E3-EastAfrica.dc.html`)

- 엘리트 ①동아프리카의 비밀
- VO2max는 더 낮은데 러닝 이코노미가 12% 좋았다
- 에리트레아 엘리트 7명 vs 스페인 엘리트 9명 (2006)
- 에리트레아
- 스페인
- VO2max
- 73.8
- 77.8
- 통계적 차이 없음
- 21km/h에서 산소 ml/kg/분 · 낮을수록 좋음
- 65.9
- 74.8
- 약 12% 적게
- 종아리 둘레
- 30.9cm
- 33.9cm
- 더 가늘다
- 정강이 길이
- 44.1cm
- 40.6cm
- 더 길다
- 알 수 있는 것
- 비슷한 수준의 선수가 낮은 VO2max + 좋은 이코노미로 달릴 수 있다. 10km 기록이 같은 아프리카·백인 러너 비교(2000)에서도 VO2max 13% 낮고 이코노미 5% 좋았어요.
- 알 수 없는 것
- 훈련을 맞춘 실험이 아니에요. 타고난 체형 때문인지, 어릴 때 환경·훈련 때문인지 원인은 몰라요.
- Lucia et al. (2006) Appl Physiol Nutr Metab · Weston et al. (2000) Med Sci Sports Exerc · 둘 다 소규모 비교 연구

### 3편 07 래드클리프 11년  (`E3-EliteCases.dc.html`)

- 엘리트 ②래드클리프 11년
- VO2max는 그대로, 러닝 이코노미만 15% 좋아졌다
- 여자 마라톤 세계기록 보유자 · 18세(1992) → 29세(2003) 매년 측정
- 1992
- 2003
- VO2max
- 72
- →
- 약 70
- 그대로
- 러닝 이코노미 16km/h · ml/kg/km
- 205
- →
- 175
- −15%
- 젖산역치 속도
- 14~15
- →
- 18.5
- km/h ↑
- 젖산 전환점 속도
- 16
- →
- 20
- km/h ↑
- 체중
- 약 54kg
- →
- 약 54kg
- 그대로
- 그 사이 바뀐 훈련
- 주간 거리18세 때 주 40~48km 미만 → 마라톤 훈련기 주 193~257km
- 근력주 2회 웨이트, 점점 정교해짐 · 수직점프 29cm(1996) → 38cm(2003)
- 고지대훈련 상당 부분을 고지대에서
- 저자도 "원인을 하나로 꼽기 어렵다"고 했어요. 1명 사례 연구예요.
- Jones (2006) Int J Sports Sci Coach · 측정: 러닝머신 경사 1% · 3분 단계

### 3편 08 무엇이 정하나  (`E3-Factors.dc.html`)

- 구조무엇이 정하나
- 타고난 몸 vs 바꿀 수 있는 3가지
- 타고난 몸
- 바꾸기 어려워요
- 다리 끝의 무게종아리·발이 가벼울수록 유리
- 정강이 길이 · 체형동아프리카 엘리트의 특징
- 힘줄 구조연구마다 결론이 엇갈림
- ① 훈련
- 근력 · 점프 훈련메타분석에서 확인 · 2~8%
- 빠른 질주 + 충분한 휴식4주에 산소 6~8% 감소
- 수년의 누적정황 증거
- ② 장비
- 신발평균 약 4% · 사람마다 다름 · 100g 무거우면 약 1% 손해
- ③ 체중
- 체지방몸통에 1kg 더하면 약 1% 더 듦
- 경계는 있어요 힘줄도 근력 훈련으로 단단해질 수 있어요(14주에 +16%). 타고난 것도 훈련으로 일부는 변해요.
- Barnes & Kilding (2015) · Lucia et al. (2006) · Llanos-Lagos et al. (2024) · Iaia et al. (2008) · Albracht & Arampatzis (2013)

### 3편 09 폼 교정  (`E3-Form.dc.html`)

- 흔한 오해 ①폼을 고치면 될까?
- 자세가 설명하는 건 개인차의 4~12%뿐
- 메타분석 · 2024 연구 51편 · 1,115명 · 러닝 이코노미와 얼마나 관련 있나
- 수직 진폭
- 작을수록 좋음 · 중간
- 다리 강성
- 단단할수록 좋음 · 작음
- 케이던스
- 높을수록 약간 좋음 · 작음
- 접지 시간
- 관련 없음
- 착지법
- 뒤꿈치 = 앞꿈치
- 관련성 크기 (상관계수) · 사람끼리 비교한 결과
- 다리 강성이란?
- 착지할 때 다리가 얼마나 덜 눌리나 = 받는 힘 ÷ 다리가 눌린 길이 실험실: 지면반력판 · 간이: 접지·체공 시간으로 계산
- 케이던스는 몇이 정답?
- 정답 숫자는 없어요. 속도·키에 따라 달라요. 지금보다 5~10% 올리면 무릎·엉덩이 부담이 줄어요 (이코노미보다 부상 관점)
- 그대로대부분 이미 내 몸에 맞는 보폭으로 달려요. 억지로 바꾸면 적응하는 동안 오히려 손해예요.
- Van Hooren et al. (2024) Sports Med · Moore (2016) · Morin et al. (2005) · Heiderscheit et al. (2011) Med Sci Sports Exerc

### 3편 10 마일리지  (`E3-Mileage.dc.html`)

- 흔한 오해 ②많이 뛰면 오를까?
- 몇 주로는 안 오르고, 몇 년이면 오를 가능성이 커요
- 6주
- 변화 없음
- 단기 훈련 실험 (1996)
- VO2max는 57.7 → 61.3으로 올랐는데, 폼은 그대로였고 느린 속도의 이코노미는 오히려 나빠졌어요
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

### 3편 11 근력 메타분석  (`E3-Strength.dc.html`)

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

### 3편 12 근력 처방  (`E3-StrengthRx.dc.html`)

- 바꿀 수 있는 것 ①실제 처방 연구
- 연구에서 효과 본 3가지
- 90°
- 1하프 스쿼트
- 4세트 × 4회(최대) · 세트 사이 3분 · 주 3회 · 8주 천천히 내려가 1초 멈춤 → 최대한 빠르게 일어서기
- 이코노미 +5% · VO2max 속도 버티기 +21%
- 훈련된 러너 17명 · 체중·VO2max 변화 없음 · Støren 2008
- 2플라이오메트릭
- 제자리 발목 점프·바운딩처럼 착지 즉시 튀어 오르기 30분 · 주 3회 · 9주
- 18km/h에서 이코노미 +4.1%
- VO2max 71 엘리트 15명 · Saunders 2006
- 고정된 바
- 3종아리 등척성
- 고정된 저항을 발끝으로 최대 힘으로 3초 밀기 4회 × 5세트 · 14주
- 힘줄 강성 +16% · 이코노미 약 4%
- 26명 · Albracht & Arampatzis 2013
- 단, 메타분석에선 등척성 전체 효과가 뚜렷하지 않았어요
- Støren et al. (2008) Med Sci Sports Exerc · Saunders et al. (2006) J Strength Cond Res · Albracht & Arampatzis (2013) Eur J Appl Physiol · 그림은 이해를 돕는 예시

### 3편 13 질주 훈련  (`E3-Speed.dc.html`)

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

### 3편 14 신발  (`E3-Shoes.dc.html`)

- 바꿀 수 있는 것 ③신발
- 평균은 4%, 하지만 내 발엔 0%일 수도
- 일반 레이싱화
- 얇은 밑창 · 가벼움
- vs
- 카본화
- 두꺼운 반발 폼 + 탄소판
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

### 3편 15 내구성  (`E3-Durability.dc.html`)

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
- 하이록스라면1km 달리기 8번을 스테이션 사이에 해요. 쌩쌩할 때 이코노미보다 지친 상태의 이코노미가 기록을 정해요. (코치 해석 · 하이록스 직접 연구는 아직 없음)
- Zanini, Folland & Blagrove (2024) Med Sci Sports Exerc · 그래프는 시작과 90분 값을 직선으로 이은 것

### 3편 16 팩트체크  (`E3-FactCheck.dc.html`)

- 팩트체크흔히 듣는 이코노미 상식
- 맞음근력운동이 이코노미를 올린다
- 메타분석에서 확인 · 고중량·점프·혼합
- 근거 X폼·착지법을 바꿔야 한다
- 자세는 개인차의 4~12% · 착지법 차이 없음
- 반쯤케이던스 180이 정답
- 높을수록 약간 좋지만 모두에게 맞는 숫자는 없음
- 근거 X접지 시간을 줄이면 좋아진다
- 관련 없음 (r = −0.02)
- 근거 X호흡을 2:1로 맞추면 좋아진다
- 직접 근거를 찾지 못함
- 반쯤많이 뛰는 게 유일한 답
- 수년 누적은 정황 증거 · 근력·질주도 효과
- 반쯤슈퍼슈즈는 누구나 4%
- 평균은 맞지만 개인차 −11~+11%
- 근거 X아마추어는 신발 효과가 작다
- 느린 러너일수록 줄어드는 시간이 더 커요(이론)
- Van Hooren (2024) · Llanos-Lagos (2024) · Barnes & Kilding (2015) · Knopp (2023) · Kipp (2019)

### 3편 17 정리  (`E3-Wrap.dc.html`)

- 정리 러닝 이코노미는 폼이 아니라 몸이 만든다
- 원리이코노미 = 1km 가는 데 드는 산소같은 VO2max여도 최대 30% 차이 · 역치 아래 속도에서 산소로 측정
- 엘리트VO2max가 아니라 러닝 이코노미에리트레아 12% 효율 · 래드클리프 11년 −15% (VO2max 그대로)
- 오해폼 교정 · 착지 · 접지 시간자세는 개인차의 4~12% · 억지로 바꾸면 오히려 손해
- 확실한 것근력 · 점프 · 빠른 질주 + 충분한 휴식고중량·플라이오·혼합 2~8% · 30초 질주 4주에 6~8%
- 조건부신발 · 수년의 누적 훈련신발은 평균 4%, 개인차 큼 · 마일리지는 수년 단위 정황 증거
- 결론
- 신발이 4%를 줄 수는 있어도, 러닝 이코노미는 근력·속도·시간이 만든다
- 하이록스는 지친 상태의 이코노미 싸움 · 근력과 스트라이드를 주 1~2회 꾸준히
- Hoogkamer 2018 · Lucia 2006 · Jones 2006 · Van Hooren 2024 · Llanos-Lagos 2024 · Iaia 2008 · Knopp 2023 · Zanini 2024

### 3편 18 참고문헌  (`E3-Refs.dc.html`)

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

### 3편 19 다음 편 예고  (`E3-Next.dc.html`)

- 다음 편 예고젖산역치
- 엔진도 같고 연비도 같은데, 마라톤 후반에 갈리는 이유
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
- 4편VO2max의 몇 %를 오래 버티느냐, 젖산역치에서 이어갈게요.
- Jones et al. (2021) J Appl Physiol · Hunter & Muniz-Pumares (2025) Eur J Sport Sci

