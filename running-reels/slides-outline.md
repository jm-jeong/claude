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

### 재구성 00 훅 · 같은 페이스 다른 산소  (`E3R-Hook.dc.html`)

- 러닝 3요소 · 3편
- 같은 페이스, 다른 산소. 러닝 이코노미
- VO2max도 체중도 같은 두 러너가 6:00/km로 달려도 쓰는 산소는 10% 달라요. 이 차이, 무엇으로 줄일 수 있을까요?
- 러너 A
- 240
- ml/kg/km · 1km에 드는 산소
- vs
- 러너 B
- 264
- ml/kg/km · 1km에 드는 산소
- 예시값 · 1편 비교 러너 (1분 산소 40 vs 44 × 6분)

### 재구성 01 러닝 이코노미란 · 측정  (`E3R-Def.dc.html`)

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
- 같은 사람을 다시 재도 약 2~3% 흔들려요
- 1러닝머신 경사 1%
- 야외에서 받는 공기 저항만큼 비용을 맞추려고
- 2역치보다 느린 속도 · 단계당 3~5분
- 산소가 안정될 때까지 · 역치를 넘으면 젖산이 쌓여 산소로 다 못 재요
- 3마스크로 마지막 1~2분 평균
- 그래프의 초록 구간 · 같은 시간대·식사·신발로 통제
- 4× 1km 걸린 시간 = ml/kg/km
- 40 × 6분 = 240 · 최신 연구는 kcal/kg/km로도 표시
- Jones & Doust (1996) J Sports Sci · Barnes & Kilding (2015) Sports Med Open · Saunders et al. (2004) 측정 오차 2.4% · 시계는 산소를 재지 않아 이코노미를 직접 알 수 없어요

### 재구성 02 왜 중요할까  (`E3R-Why.dc.html`)

- 개념왜 중요할까
- 엔진 · 버티는 힘 · 연비, 셋이 함께 기록을 만든다
- 엔진
- VO2max
- ×
- 버티는 비율
- 젖산역치
- ÷
- 연비
- 이코노미
- =
- 버틸 수 있는
- 속도
- 모델 계산1편 예시 러너 · VO2max 60 · 역치에서 85%(1분에 산소 51 ml/kg)까지 버팀
- 이코노미 2401편 예시 그대로
- 240
- 4:42/km
- 이코노미 21610% 좋아지면
- 216
- 4:14/km
- 엔진과 역치가 같아도 연비가 10% 좋으면 역치 페이스가 약 28초 빨라져요. 실제 기록 변화는 공기 저항 때문에 빠를수록 이보다 작아요 (엘리트 속도에선 약 2/3).
- 측정 연구2시간 마라톤 후보 16명 (Breaking2)
- VO2max
- 71
- 젖산 전환점
- 92%
- 이코노미 (7명)
- 191
- 높은 VO2max는 전제예요. 정상급끼리는 그 위에서 이코노미와 역치가 차이를 만들어요.
- Joyner (1991) J Appl Physiol 모델 · Jones et al. (2021) J Appl Physiol · Kipp, Kram & Hoogkamer (2019) Front Physiol · 계산: 51 ÷ 이코노미 = km/분

### 재구성 03 래드클리프 11년  (`E3R-Radcliffe.dc.html`)

- 엘리트 사례래드클리프 11년
- VO2max는 그대로, 러닝 이코노미만 15% 좋아졌다
- 폴라 래드클리프 · 2003.4.13 런던 마라톤
- 2:15:25
- 여자 마라톤 세계기록 · 2019년까지 16년 유지 1992~2003년 거의 매년 측정한 기록의 끝이 바로 이 해 사진은 2005 런던 마라톤
- VO2max
- 70
- 71
- 67
- 69
- 75
- 70
- ≈ 70 그대로 (본문: 18세 72)
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

### 재구성 04 래드클리프 무엇이 바뀌었나  (`E3R-Radcliffe2.dc.html`)

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
- 근력주 2회 정도 웨이트 · 수직점프 29cm(1996) → 38cm(2003)
- 고지대훈련 상당 부분을 고지대에서 · 평소 달리기 대부분 3:20~3:40/km
- 본인 말코어 안정성 · 메디신볼 · 웨이트 (2020 인터뷰) · 물리치료사 Gerard Hartmann과 폭발력 훈련 보강 (2002)
- 1명 사례 · 저자도 원인을 하나로 꼽기 어렵다고 했어요 · 2003년 이후 이코노미는 165까지 더 좋아졌어요
- Jones (2006) 그림 6 · 본문 · Sports Illustrated (2002) · Coventry Telegraph (2020)

### 재구성 05 무엇이 정하나  (`E3R-Factors.dc.html`)

- 구조무엇이 정하나
- 타고난 몸 vs 바꿀 수 있는 4가지
- 타고난 몸
- 바꾸기 어려워요
- 가는 종아리와 발목실험
- 체중이 아니라 다리 끝이 가벼운 것 · 신발 한 짝 100g ≈ +1%
- 긴 정강이 · 체형상관
- 엘리트 비교에서 함께 나타남 · 원인인지는 몰라요
- 발 크기 · 아킬레스 구조엇갈림
- 발 치수는 관련 없었고, 힘줄 구조는 연구마다 반대
- 바꿀 수 있는 것
- 위에서부터 바탕 → 보조
- ① 수년간의 달리기사례·상관
- 이코노미의 바탕 · 몇 주가 아니라 몇 년 단위
- ② 근력 · 점프 · 업힐실험
- 효과 작음~중간 · 몇 % · 필수는 아님
- ③ 신발실험
- 평균 2~4% · 개인차 큼 · 느린 속도에선 더 작을 수도
- ④ 체지방실험
- 몸통에 무게를 더하면 산소도 거의 비례해서 늘어요
- 왜 유리할까달릴 때 에너지는 대부분 몸을 받쳐 올리고 다리를 휘두르는 데 써요. 다리 끝이 가벼우면 휘두르는 비용이 줄어요(망치 끝을 잡으면 더 힘든 것처럼). 체형 연구는 상관이지 원인 증명이 아니에요.
- Franz et al. (2012) · Teunissen et al. (2007) · Coifman et al. (2024) · Lucia et al. (2006) · van Werkhoven & Piazza (2017) · Llanos-Lagos et al. (2024) · Knopp et al. (2023) 사진: Wikimedia Commons · Tiia Monto, Bob Ramsak, Hjfm 003, franchise opportunities (CC BY-SA) · yaaaay (CC BY 2.0) · 미 육군, Gray's Anatomy (퍼블릭 도메인)

### 재구성 06 바탕은 수년간의 달리기  (`E3R-Running.dc.html`)

- 핵심바탕은 달리기
- 이코노미의 바탕은 수년간 쌓인 달리기
- 6주단기
- 실험개선 없음
- 남자 러너 15명 · VO2max는 57.7 → 61.3으로 올랐는데 이코노미는 그대로. 느린 측정 속도 탓일 수 있다고 저자도 봤어요
- 11년장기
- 사례래드클리프 −15%
- 주 40~48km 미만 → 193~257km · 이코노미 205 → 175 · 근력·고지대도 함께 바뀌어 원인은 하나로 못 꼽아요
- 롱런90분+
- 상관지쳐도 덜 무너져요
- 기록 같은 26명 · 정기적으로 90분 이상 달리는 그룹은 90분째 이코노미 악화 +3.1%, 70분 미만만 달리는 그룹은 +6.0%
- 엘리트현장
- 현장주 160~220km · 80% 이상 저강도
- 세계 정상급 마라토너 훈련 분석 · 많이, 대부분 편하게 달려요
- 그런데 왜 "확실하다"고 못 할까?
- 1훈련량만 바꿔서 몇 년 비교한 실험은 거의 없어요
- 2거꾸로일 수도 있어요. 원래 이코노미가 좋은 사람이 다치지 않고 많이 달릴 수 있는 걸지도요
- Lake & Cavanagh (1996) Med Sci Sports Exerc · Jones (2006) · Zanini, Folland & Blagrove (2026) Med Sci Sports Exerc · Haugen et al. (2022) Sports Med Open

### 재구성 07 보조① 근력 · 점프  (`E3R-Strength.dc.html`)

- 보조 ①근력 · 점프
- 무겁게 적게, 튀어 오르기 몇 %를 더 얹는다
- 메타분석 2024중장거리 러너 652명 · 6~24주 · 주 1~4회 · 러닝만 한 그룹과 비교
- 둘 이상 섞기고중량 + 점프 등
- 중간 효과 0.43
- 점프(플라이오)12km/h 이하에서
- 작은 효과 0.31
- 고중량1RM 80% 이상
- 작은 효과 0.27
- 중간 무게 · 버티기1RM 40~79% · 등척성
- 효과 없음
- 근거 확실성 중간(혼합은 낮음) · 고중량은 빠른 속도·높은 VO2max에서 효과가 더 컸어요
- 하프 스쿼트 실험
- 4세트 × 4회(최대 무게) · 주 3회 · 8주 · 내려갈 땐 천천히, 올라올 땐 최대한 빠르게
- 이코노미 +5%
- 훈련된 러너 17명 · Støren 2008
- 플라이오 실험
- 착지 즉시 튀어 오르는 점프 30분 · 주 3회 · 9주
- 18km/h에서 +4.1%
- 고도로 훈련된 15명 · 14·16km/h는 변화 없음 · Saunders 2006
- 필수는 아니에요. 효과는 몇 % 수준이고, 케냐 정상급 상당수는 체육관 대신 언덕·드릴로 비슷한 자극을 받아요.
- Llanos-Lagos et al. (2024) Sports Med · Støren et al. (2008) Med Sci Sports Exerc · Saunders et al. (2006) J Strength Cond Res · 사진은 동작 예시: 미 해병대·미 육군 (퍼블릭 도메인, Wikimedia Commons)

### 재구성 08 보조② 업힐 · 짧은 질주  (`E3R-Hills.dc.html`)

- 보조 ②업힐 · 짧은 질주
- 언덕과 짧은 질주, 근거는 있지만 크기는 작다
- 업힐 인터벌 6주 무작위 실험
- 강도를 다르게 한 5개 그룹으로 비교했어요. 이코노미는 가장 센 강도가 가장 좋았고, 5km 기록은 강도와 상관없이 좋아졌어요.
- 이코노미 +2.4% (±1.4)5km 기록 평균 +2.0%
- Barnes et al. (2013) Int J Sports Physiol Perform
- 30초 질주 4주 소규모 · 주의
- 주 45km 대신 30초 질주 8~12회(사이 3분 휴식) + 쉬운 러닝, 총 주 15.6km. 같은 속도에서 산소를 6~8% 덜 썼어요. 다만 훈련량을 65% 줄여 피로가 빠진 효과가 섞였고, 17명뿐이며, 10km 기록은 그대로였어요.
- Iaia et al. (2008) J Appl Physiol · 후속 연구(12명, 훈련량 −25%)에선 10km 37.3 → 36.3분 · Bangsbo et al. (2009)
- 케냐 · Canova 방식 현장 사례
- 기초기에 많은 양의 편한 달리기와 함께 짧은 업힐 스프린트, 기술 드릴을 넣어요. "근력 훈련은 체육관이 아니라 트레일 위에서"라는 말도 있어요.
- Renato Canova 훈련 체계 · 동아프리카 러너 지도자 Shane Benzie 인터뷰
- 얹기바탕 훈련을 대신하는 게 아니라 그 위에 짧게 얹는 훈련이에요.
- Barnes, Hopkins, McGuigan & Kilding (2013) · Iaia et al. (2008) · Bangsbo et al. (2009) · Wikipedia: Renato Canova · Yahoo News (Benzie)

### 재구성 09 엘리트는 이렇게 한다  (`E3R-Elites.dc.html`)

- 현장엘리트는 이렇게
- 엘리트의 실제 훈련, 많이 달리고 + 조금 강하게
- 폴라 래드클리프
- 논문 기록
- 주 193~257km · 대부분 3:20~3:40/km
- 역치 근처 템포 + 주 1~2회 고강도
- 웨이트 주 2회 정도 · 고지대
- 엘리우드 킵초게
- 팀 영상·기사
- 주 2회 약 60분 근력·가동성
- 밴드·맨몸: 브리지, 플랭크, 한 발 데드리프트, 균형
- 목적은 부상 예방 · 코치 Patrick Sang이 도입
- 야콥 잉게브릿센
- 인터뷰·브랜드 콘텐츠
- 주 4회 근력
- 주 초반: 드릴 · 가동성 · 플라이오
- 금·일: 웨이트
- 케냐 · Renato Canova
- 코치 자료
- 기초기: 많은 양의 편한 달리기
- 짧은 업힐 스프린트 · 기술 드릴
- "근력은 트레일 위에서"
- 공통점: 모두 많이 달려요. 근력·점프는 부상 예방과 파워를 위해 적게 해요.※ 현장 관행이지, 이 방법이 이코노미를 올렸다는 증거는 아니에요.
- Jones (2006) Int J Sports Sci Coach · NN Running Team · Running Magazine · Higher Running(Outside 인용) · Coros 인터뷰 · Wikipedia: Renato Canova · Yahoo News(Benzie)

### 재구성 10 폼과 케이던스  (`E3R-Form.dc.html`)

- 폼폼과 케이던스
- 폼은 억지로 바꾸지 말고, 케이던스만 살짝
- 메타분석 · 상관연구 51편 · 1,115명 · 이코노미와 얼마나 관련 있나
- 수직 진폭
- 작을수록 좋음 · 중간
- 다리 강성
- 덜 꺾일수록 좋음 · 중간
- 케이던스
- 높을수록 약간 좋음 · 작음
- 접지 시간
- 관련 없음
- 착지법
- 뒤꿈치 = 앞꿈치
- 변수 하나씩 보면 개인차의 4~12%만 설명해요 · 사람끼리 비교한 결과라 원인은 아니에요
- 착지법 바꾸기?실험 종합
- 뒤꿈치 러너가 앞꿈치로 바꾸면 단기적으로 이코노미가 나빠졌어요. 다치지 않았다면 바꿀 이유가 없다는 게 결론이에요.
- 케이던스 180?실험
- 엘리트를 레이스 페이스에서 센 숫자예요. 숙련자는 최적보다 약 3%, 초보는 약 8% 낮게 달렸어요. 같은 페이스에서 +5~10%면 무릎·엉덩이 부담도 줄어요.
- 팔치기는 그대로: 팔을 묶고 달리면 비용이 3~13% 늘었어요
- Van Hooren et al. (2024) Sports Med · Anderson et al. (2020) Sports Med · de Ruiter et al. (2014) Eur J Sport Sci · Heiderscheit et al. (2011) · Arellano & Kram (2014) J Exp Biol · Daniels (1984 LA 올림픽 관찰)

### 재구성 11 신발  (`E3R-Shoes.dc.html`)

- 바꿀 수 있는 것신발
- 평균은 2~4%, 하지만 내 발엔 손해일 수도
- 실험 · 2023 카본화로 바꿨을 때 러닝 이코노미 변화
- ← 손해0이득 →
- 케냐 정상급 7명
- 세계 정상급 로드 러너
- -11.3%+11.4%
- 유럽 아마추어 7명
- -1.1%+9.7%
- 세계 정상급 선수 중에도 오히려 11% 손해 본 사람이 있었어요
- 2025 연구 종합
- 산소 약 2~3%↓ 느린 페이스는 약 1%
- 무게도 이코노미
- 신발 한 짝 100g 무거우면 약 1% 손해
- Knopp et al. (2023) Sports Med · 2025 리뷰(Front Sports Act Living · Int J Sports Med) · Joubert et al. (2023) Int J Sports Physiol Perform · Franz et al. (2012) · 레이스 신발은 레이스 페이스로 직접 비교해 보세요

### 재구성 12 최신 경향 내구성  (`E3R-Durability.dc.html`)

- 최신 경향지쳐도 유지되나
- 같은 페이스인데 90분째엔 산소가 더 든다
- 요즘은 "지쳐도 버티는 힘"을 넷째 요소로 봐요.
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
- 산소로 재도 거의 같아요: 90분째 +2.4% vs +4.5%
- 상관 롱런 습관
- 90분 이상 달리는 그룹 +3.1% 70분 미만만 달리는 그룹 +6.0%
- 기록 같은 26명 · 2026
- 무작위 실험 근력+점프 10주
- 90분째 이코노미 −2.1% 러닝만 한 그룹 +0.6%
- 28명 · 2025
- 하이록스라면1km 달리기 8번을 스테이션 사이에 해요. 쌩쌩할 때 이코노미보다 지친 상태의 이코노미가 기록을 정해요. (코치 해석 · 하이록스 직접 연구는 아직 없음)
- Zanini, Folland & Blagrove (2024, 2026) Med Sci Sports Exerc · Zanini et al. (2025) Med Sci Sports Exerc · Jones (2024) J Physiol · 그래프는 시작과 90분 값을 직선으로 이은 것

### 재구성 13 이코노미 팩트 체크  (`E3R-FactCheck.dc.html`)

- 정리팩트 체크
- 이코노미 팩트 체크
- 맞아요팔치기는 효율에 도움
- 팔을 묶으면 비용 3~13%↑
- 근력·점프는 효과가 있다
- 작음~중간 · 몇 % · 필수는 아님
- 애매해요많이 뛰면 이코노미가 오른다
- 6주로는 그대로 · 수년 사례와 롱런 습관은 관련 · 인과 실험은 거의 없음
- 카본화는 누구나 4%
- 평균 2~4% · 같은 신발로 −11 ~ +11% · 느린 속도에선 작을 수도
- 체중 1kg = km당 몇 초
- 무게를 더한 실험뿐 · 근육·건강을 잃으면 역효과
- VO2max 높으면 기록 좋다
- 실력이 섞이면 맞지만 비슷한 수준끼리는 약해요
- 틀려요케이던스는 180이 정답
- 엘리트 레이스 페이스 숫자 · 내 최적은 사람·속도마다 달라요
- 앞꿈치 착지가 더 효율적
- 차이 없음 · 바꾸면 단기적으로 오히려 나빠짐
- 유연할수록 효율적
- 덜 유연한 러너가 오히려 더 경제적이었어요(상관) · 달리기 전 정적 스트레칭도 이득 확인 안 됨
- 시계 지표로 이코노미를 안다
- 시계는 산소를 안 재요 · 파워도 사람 간 비교는 부정확
- Arellano & Kram (2014) · Llanos-Lagos (2024) · Lake & Cavanagh (1996) · Zanini (2026) · Knopp (2023) · Joubert (2023) · Teunissen (2007) · Conley & Krahenbuhl (1980) · de Ruiter (2014) · Anderson (2020) · Jones (2002) · Aubry (2018)

### 재구성 14 일반 러너가 할 일  (`E3R-Todo.dc.html`)

- 실천일반 러너가 할 일
- 내 이코노미를 위해 오늘부터 할 수 있는 것
- 1꾸준히, 오래 달리기사례·상관
- 몇 주가 아니라 몇 년 단위로 보기 · 주 1회 90분 이상 롱런은 지친 상태의 이코노미와 관련
- 2근력 주 2회, 무겁게 적게메타분석
- 스쿼트 4×4(최대 무게)나 점프 · 6주 이상 · 처음엔 가볍게 동작부터
- 3업힐·짧은 질주를 가끔실험
- 바탕 훈련을 대신하지 말고 위에 짧게 얹기
- 4폼은 그대로, 케이던스만 살짝실험
- 초보라면 같은 페이스에서 지금보다 5% 정도까지 · 착지법은 억지로 바꾸지 않기
- 5레이스 신발은 직접 비교실험
- 평균이 아니라 내 발에서 · 레이스 페이스로 미리 달려보기
- 6시계 숫자에 휘둘리지 않기코치 해석
- 시계는 산소를 재지 않아요 · 같은 코스·같은 페이스에서 심박이 내려가는지가 더 현실적인 신호예요
- Zanini (2024, 2026) · Llanos-Lagos (2024) · Støren (2008) · Barnes (2013) · de Ruiter (2014) · Heiderscheit (2011) · Anderson (2020) · Knopp (2023) · Aubry (2018) · 6번의 심박 신호는 코치 해석이에요

### 재구성 15 참고문헌  (`E3R-Refs.dc.html`)

- 참고참고문헌
- 참고문헌
- 1Joyner (1991) J Appl Physiol
- 2Jones & Doust (1996) J Sports Sci
- 3Saunders et al. (2004) Med Sci Sports Exerc
- 4Barnes & Kilding (2015) Sports Med Open
- 5Jones et al. (2021) J Appl Physiol
- 6Kipp, Kram & Hoogkamer (2019) Front Physiol
- 7Jones (2006) Int J Sports Sci Coach
- 8Franz et al. (2012) Med Sci Sports Exerc
- 9Teunissen et al. (2007) J Exp Biol
- 10Coifman et al. (2024) Appl Ergon
- 11Lucia et al. (2006) Appl Physiol Nutr Metab
- 12van Werkhoven & Piazza (2017) J Appl Biomech
- 13Lake & Cavanagh (1996) Med Sci Sports Exerc
- 14Zanini et al. (2024) Med Sci Sports Exerc
- 15Zanini et al. (2025) Med Sci Sports Exerc
- 16Zanini et al. (2026) Med Sci Sports Exerc
- 17Jones (2024) J Physiol
- 18Haugen et al. (2022) Sports Med Open
- 19Llanos-Lagos et al. (2024) Sports Med
- 20Støren et al. (2008) Med Sci Sports Exerc
- 21Saunders et al. (2006) J Strength Cond Res
- 22Barnes et al. (2013) Int J Sports Physiol Perform
- 23Iaia et al. (2008) J Appl Physiol
- 24Bangsbo et al. (2009) J Appl Physiol
- 25Van Hooren et al. (2024) Sports Med
- 26Anderson et al. (2020) Sports Med
- 27de Ruiter et al. (2014) Eur J Sport Sci
- 28Heiderscheit et al. (2011) Med Sci Sports Exerc
- 29Arellano & Kram (2014) J Exp Biol
- 30Knopp et al. (2023) Sports Med
- 31Joubert et al. (2023) Int J Sports Physiol Perform
- 32신발 리뷰 (2025) Int J Sports Med · Front Sports Act Living
- 33Jones (2002) Int J Sports Med
- 34Aubry et al. (2018) J Strength Cond Res
- 35Conley & Krahenbuhl (1980) Med Sci Sports Exerc
- 36Cureton & Sparling (1980) Med Sci Sports Exerc
- 현장 자료NN Running Team (Patrick Sang) · Running Magazine · Higher Running (Outside 인용) · Coros (Ingebrigtsen) · Sports Illustrated (2002) · Coventry Telegraph (2020) · Wikipedia: Renato Canova · Yahoo News (Shane Benzie)
- 사진Wikimedia Commons · yaaaay (CC BY 2.0) · Tiia Monto, Bob Ramsak, Hjfm 003, franchise opportunities, Modifyphysio (CC BY-SA) · 미 육군·미 해병대, Gray's Anatomy (퍼블릭 도메인)
- 논문 제목·링크·판정은 running-reels/e3-factcheck.md에 정리했어요

### 재구성 16 다음 편 예고  (`E3R-Next.dc.html`)

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
- 마라톤 참가자 18명 · 90분 뒤
- 역치가 덜 떨어질수록
- 마라톤 기록도 빨랐어요 (r = 0.68)
- 4편에서 다룰 것
- LT1젖산이 처음 오르는 지점 · 존2 기준으로 많이 쓰는 곳
- LT2젖산이 급격히 쌓이는 지점 · 하이록스 페이스의 천장
- 훈련역치는 어떻게 올리나
- Jones et al. (2021) J Appl Physiol · Hunter & Muniz-Pumares (2025) Eur J Sport Sci


## 4편

### 4편 00 훅  (`E4-Hook.dc.html`)

- 러닝 3요소 · 4편
- 엔진도 연비도 같은데 38초 차이, 젖산역치
- VO2max도 이코노미도 똑같은 두 러너, 차이는 얼마나 높은 강도까지 버티느냐였어요.
- 러너 C · 역치 페이스
- 5:20/km
- VO2max의 75%에서 역치
- vs
- 러너 D · 역치 페이스
- 4:42/km
- VO2max의 85%에서 역치
- 예시값 · 1편 비교 러너 (둘 다 VO2max 60 · 이코노미 240 ml/kg/km)

### 4편 01 젖산은 범인일까  (`E4-Lactate.dc.html`)

- 오해젖산은 범인일까
- 젖산은 피로물질이 아니라 연료예요
- 1다시 태워 쓰는 연료 리뷰
- 운동 중 젖산의 75~80%는 근육·심장에서 다시 태워져요. 나머지는 간에서 포도당으로 바뀌어요.
- 2산성화의 범인도 아니에요 리뷰
- 근육을 산성으로 만드는 수소이온(H⁺)은 에너지(ATP)를 쓸 때 나와요. 젖산을 만드는 반응은 오히려 H⁺를 써서 산성화를 늦춰요.
- 3다음 날 근육통과도 관계없어요 실험
- 젖산은 운동 뒤 금방 줄어요. 근육통은 하루~사흘 뒤에 가장 심해요.
- 혈중 젖산 · 반감기 약 15~25분
- 근육통 · 1~3일 뒤 최고
- 운동 직후
- 1시간
- 6시간
- 24시간
- 48시간
- 72시간
- 표시등젖산 수치는 '지금 힘든 강도'를 알려주는 신호예요. 범인이 아니라 계기판이에요.
- Brooks (리뷰) · Robergs et al. (2004) Am J Physiol · Ferguson et al. (2018) Eur J Appl Physiol · Cheung et al. (2003) Sports Med · 젖산 반감기: 회복 방법별 실험 (1996 · 2000) · 그래프는 개념도

### 4편 02 역치는 두 개  (`E4-Two.dc.html`)

- 개념역치는 두 개
- 역치는 하나가 아니라 두 개
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
- LT1 아래 · 중강도
- 젖산이 안정 수준 오래 지속 가능 · 대화 가능
- LT1~LT2 · 고강도
- 젖산이 올랐다가 새 수준에서 버팀
- LT2 위 · 심한 강도
- 젖산이 멈추지 않고 계속 쌓임 · 빨리 지침
- 비슷한 이름들 LT1 ≈ 첫 환기역치(VT1)·유산소 역치 · LT2 ≈ MLSS·임계속도·두 번째 환기역치 근처 (완전히 같은 값은 아니에요)
- 그래프: 1편 예시 러너 (VO2max 60 · 이코노미 240 · LT1 = VO2max 70%, LT2 = 85%) · 강도 구간: Jamnick et al. (2020) Sports Med · Jones et al. (2019) Physiol Rep

### 4편 03 논문은 이렇게 잰다  (`E4-Measure.dc.html`)

- 개념논문은 이렇게 잰다
- 같은 ‘역치’도 정의가 25가지
- 점증부하(예: 3분마다 속도↑) + 단계마다 손끝·귓불 피 한 방울로 젖산 측정
- ①고정값
- 젖산이 2 mmol, 4 mmol이 되는 속도 (예: 4 mmol = OBLA)
- 간단 · 개인차 무시
- ②처음 오르는 지점
- 기준선보다 일정량 오른 지점, 로그 변환 꺾임점
- → LT1
- ③급격히 꺾이는 지점 · MLSS
- 곡선 꺾임(Dmax 등), 30분 일정 속도 테스트
- → LT2
- MLSS30분 동안 같은 속도로 달려, 10~30분 사이 젖산이 1 mmol 넘게 오르지 않는 가장 빠른 속도
- ‘4 mmol = 역치’일까? 비교 · 9명
- 4 mmol 기준
- 287 W
- +12%
- 실제 MLSS
- 255 W
- 조정 선수 9명의 실제 MLSS 젖산은 평균 3.0 mmol. 4 mmol 기준은 역치를 약 12% 높게 잡았어요.
- Faude et al. (2009) Sports Med: 젖산역치 개념 25개, 세 부류 · Jones et al. (2019) Physiol Rep: MLSS 정의 · Beneke (1995) Med Sci Sports Exerc: 조정 선수 9명

### 4편 04 LT1과 존2  (`E4-Zone2.dc.html`)

- LT1존2의 진짜 기준
- 같은 ‘존2’, 어디서 들었느냐에 따라 뜻이 다르다
- 운동 앱 5구간흔한 기본값
- 최대심박의 약 60~70%
- 관행
- 연구용 3구간Seiler 등
- LT1과 LT2 사이 · 꽤 힘든 구간
- 리뷰
- 요즘 ‘존2 훈련’San Millán 등
- LT1 바로 아래 · 젖산이 오르기 직전
- 현장
- 최대심박 공식부터 오차
- ±10박
- 220 − 나이, 208 − 0.7 × 나이 모두 평균 추정이에요. 같은 나이라도 10박 안팎 차이는 흔해요
- %최대심박으로 구간 나누기
- 근거 약함
- 고정 비율은 사람마다 같은 강도 구간을 잘 못 나눠요. LT1·환기역치는 근거가 있어요
- LT1 아래존2의 기준은 시계 숫자보다 '젖산이 아직 안 오르는 강도'. 실전에선 문장으로 대화가 편한 정도예요.
- Tanaka et al. (2001) J Am Coll Cardiol · 개인 오차 약 10~12박은 후속 연구 기준 · Jamnick et al. (2020) Sports Med · Haugen et al. (2022) · Quinn & Coons (2011) 말하기 테스트

### 4편 05 LT2 버틸 수 있는 상한  (`E4-LT2.dc.html`)

- LT2버틸 수 있는 상한
- LT2 아래에선 젖산이 멈추고, 위에선 계속 쌓인다
- 같은 속도로 30분 달릴 때 혈중 젖산 개념도
- LT2 아래 · 멈춤
- LT2 근처 · 1 mmol 이하 상승
- LT2 위 · 계속 쌓임
- 0분
- 10분
- 20분
- 30분
- 혈중 젖산 →
- MLSS
- 30분 테스트
- 10~30분 사이 상승 1 mmol 이하인 가장 빠른 속도
- 임계속도(CS)
- 조금 더 빠름
- 잘 훈련된 러너 16.4 vs MLSS 15.2 km/h
- Breaking2 선수 16명
- VO2max의 92%
- LT2(젖산 전환점) 위치 · LT1은 83%
- 약 1시간현장 감각으로는 1시간쯤 전력으로 버틸 수 있는 '편하게 힘든' 페이스 근처예요 코치 기준
- 하이록스 · 코치 해석 젖산은 스테이션 뒤에 더 높았어요(최고 8.5 vs 러닝 7.7 mmol, 11명 중앙값). 러닝 구간을 LT2 아래로 달려야 쌓인 젖산을 정리할 여유가 생겨요.
- Jones et al. (2019) Physiol Rep · Nixon et al. (2021) · Jones et al. (2021) J Appl Physiol · Daniels T 페이스 · Brandt et al. (2025) Front Physiol

### 4편 06 역치의 위치  (`E4-Position.dc.html`)

- LT2역치의 위치
- VO2max가 같아도 역치 위치가 페이스를 바꾼다
- 러너 C · VO2max의 75%에서 역치5:20/km
- 산소 45
- 60
- 러너 D · VO2max의 85%에서 역치4:42/km
- 산소 51
- 60
- Breaking2 엘리트 · 실측 16명 평균92%
- VO2max의 92%까지 LT2
- 역치 페이스 = 이코노미 ÷ (VO2max × 역치 위치) 러너 C: 240 ÷ 45 = 5.33분 → 5:20 · 러너 D: 240 ÷ 51 = 4.71분 → 4:42
- 기록과 더 가까운 건? 상관 · 18명
- 젖산이 오르기 시작하는 속도
- r ≥ 0.91
- VO2max
- r ≥ 0.83
- 3.2km부터 마라톤까지 모든 거리 기록과의 상관 (1979)
- 러너 C·D: 1편 예시 (둘 다 VO2max 60 · 이코노미 240 ml/kg/km) · Jones et al. (2021) J Appl Physiol · Farrell et al. (1979) Med Sci Sports · 모델: Joyner (1991)

### 4편 07 무엇이 역치를 정하나  (`E4-Why.dc.html`)

- 왜무엇이 역치를 정하나
- 젖산은 늘 만들어진다, 문제는 치우는 속도
- 물 높이 = 혈중 젖산
- 만드는 양
- 페이스를 올릴수록 ↑
- 당을 빨리 쪼갬
- 치우는 양
- 근육·심장에서 태움
- 간에서 포도당으로
- 들어오는 양이 빠지는 양을 넘어서면 물이 계속 차요 → 그 지점이 LT2
- 훈련으로 바뀌는 것 리뷰
- 미토콘드리아 ↑
- 젖산·피루브산을 근육 안에서 더 많이 태워요
- 운반체(MCT1) ↑
- 지구력 훈련으로 늘어 젖산을 태울 곳으로 옮겨요
- 모세혈관 ↑
- 산소가 들어오고 젖산이 나가는 길이 넓어져요
- 래드클리프 11년
- VO2max는 약 70 그대로인데 LT1 속도 14~15 → 17.5~18.5 km/h, LT2 속도 16 → 20 km/h로 올랐어요 사례 1명
- Brooks (리뷰) · Billat et al. (2003) Sports Med: 훈련 후 젖산 제거↑, MCT1↑ · Jones (2006) Int J Sports Sci Coach · 욕조 그림은 개념도

### 4편 08 노르웨이 더블 역치  (`E4-Norway.dc.html`)

- 엘리트 ①노르웨이 더블 역치
- 역치를 ‘넘지 않게’, 대신 자주·많이
- 노르웨이식 한 주 예시 현장 사례마리우스 바켄 자료 · 기사 재인용
- 월
- 쉬운 달리기
- 화
- 오전 · 젖산 약 2.56분 × 5 · 휴식 1분
- 오후 · 젖산 약 3.51000m × 10 · 휴식 1분
- 수
- 쉬운 달리기
- 목
- 오전 · 젖산 약 2.52000m × 5 · 휴식 1분
- 오후 · 젖산 약 3.5400m × 25 · 휴식 30초
- 금
- 쉬운 달리기
- 토
- 짧고 빠른 세션 1회 (예: 언덕 질주 · 자료마다 다름)
- 일
- 쉬운 달리기 · 롱런 (자료마다 다름)
- 핵심은 브레이크
- 1~3회 반복마다 젖산을 재서 2~4.5 mmol 안에 머물게 해요. 역치를 넘지 않게 해서, 주 4회 역치를 하고도 회복하는 게 목적이에요.
- 근거는 아직 ‘물음표’
- 2023년 리뷰 제목도 "다음 단계인가?"예요. 이 방식을 다른 방식과 비교한 통제 실험은 아직 없어요.
- Casado, Foster, Bakken & Tjelta (2023) Int J Environ Res Public Health · Outside · Trail Runner (바켄의 예시 주 재인용) · 젖산 단위 mmol/L

### 4편 09 세계 정상급의 한 주  (`E4-WorldClass.dc.html`)

- 엘리트 ②세계 정상급의 한 주
- 대부분은 쉽게, 역치·인터벌은 조금
- 세계 정상급 장거리 선수의 훈련 강도 리뷰 · 실제 훈련 기록
- 쉬움 · LT1 아래 · 거리의 80% 이상
- 역치·인터벌
- 마라토너 주간 거리
- 160~220km
- 트랙 선수 130~190km
- 한 주 훈련 횟수
- 11~14회
- 하루 두 번이 흔해요
- 아프리카 선수
- 2000~2500m
- 고지대에 살며 훈련
- 무엇이 기록을 가장 잘 설명했나 상관
- 세계 정상급 선수들의 첫 7년 훈련을 보니, 쉬운 달리기의 양과 템포런·짧은 인터벌을 꾸준히 한 것이 기록을 가장 잘 설명했어요.
- 킵초게 캠프 현장 사례
- 케냐 캅타갓, 해발 약 2,400m. 주 최대 200km 안팎, 주 1회 30~40km 롱런, 파틀렉 (기사마다 세부가 달라요)
- Haugen et al. (2022) Sports Med Open · Casado et al. (2021) J Strength Cond Res · 킵초게: Outside · Gulf News 등 기사

### 4편 10 노르웨이 싱글  (`E4-Singles.dc.html`)

- 트렌드노르웨이 싱글
- 하루 두 번은 무리라서, 하루 한 번 서브역치
- 어디서 왔나 해외 러닝 커뮤니티(LetsRun)의 한 아마추어가 '마일리지 적은 사람을 위한 노르웨이식'으로 정리한 글이 '노르웨이 싱글'로 퍼졌어요. 현장 사례
- 서브역치
- 주 2~3회
- 역치보다 살짝 느리게, 짧게 쉬며 반복
- 롱런
- 주 1회
- 길게, 편하게
- 나머지
- 전부 쉽게
- 역치 위 인터벌은 하지 않아요
- 한 주 시간 비중 커뮤니티 권장
- 쉬움 · 롱런 75~80%
- 서브역치 20~25%
- 왜 인기일까
- 하루 한 번으로 끝나고, 역치를 넘지 않아 회복 부담이 적다는 후기가 많아요.
- 주의할 점
- 통제된 실험은 아직 없어요. 효과는 후기와 사례 수준이에요.
- LetsRun 글타래 “Modifying the Norwegian approach to lower mileage” 정리 문서 · Outside (노르웨이 방법, 일반인편) · 비중은 커뮤니티 권장값

### 4편 11 어떤 분포가 좋을까  (`E4-TID.dc.html`)

- 연구어떤 분포가 좋을까
- 역치를 더 많이 한다고 더 좋아지진 않았다
- 서브엘리트 12명 · 5개월 · 10.4km 기록 향상 실험
- 저강도 비중↑쉬운 달리기 위주
- −157초
- 역치 사이 비중↑LT1~LT2 구간 위주
- −121.5초
- 고강도(LT2 위) 비중은 두 그룹 모두 약 8%로 같았어요
- 메타분석 2024 메타분석
- 폴라라이즈드가 VO2max를 조금 더 올렸어요(효과 작음, 12주 미만에서만). 다른 기록 지표는 차이가 없었어요.
- 메타분석 2025 개인 데이터
- 13개 연구 348명: 폴라라이즈드 vs 피라미드, VO2max·타임트라이얼 차이 없음. 경쟁 선수는 폴라라이즈드, 일반인은 피라미드가 나을 수도 있어요.
- 폴라라이즈드 쉬움 많이 + 고강도 조금, 역치 사이는 최소 · 피라미드 쉬움 > 역치 사이 > 고강도
- 쉬운 양 먼저분포 이름보다 공통점이 중요해요. 쉬운 날을 지키고, 역치는 넘지 않게.
- Esteve-Lanao et al. (2007) J Strength Cond Res · Sports Med (2024) 폴라라이즈드 메타분석 · Rosenblat et al. (2025) Sports Med 네트워크 메타분석

### 4편 12 역치도 지친다  (`E4-Durability.dc.html`)

- 최신 경향역치도 지친다
- 90분 달리면 역치 속도가 5.5% 떨어졌다
- 2024 런던 마라톤 참가자 18명 (평균 3시간 17분 · 41세) · 역치 속도로 90분 달린 뒤 다시 측정
- 달리기 전 vs 90분 뒤 비교 · 18명
- 역치 속도km/h
- 전 12.8
- 90분 뒤 12.1
- VO2maxml/kg/분
- 전 56.7
- 90분 뒤 53.4
- 이코노미 · 역치 위치%VO2max
- 변화 없음
- r = 0.68역치 속도가 덜 떨어진 사람이 실제 마라톤도 더 빨랐어요 상관
- 사이클 2시간 뒤 실험 · 14명
- LT1 파워 212 → 190W, 약 10% 하락
- 그래서 요즘은 리뷰
- '지쳐도 유지되는 능력'을 VO2max·이코노미·역치 위치 다음의 4번째 요소로 봐요
- Hunter & Muniz-Pumares (2025) Eur J Sport Sci · Stevenson et al. (2022) Eur J Appl Physiol · Jones (2024) J Physiol

### 4편 13 내 역치 찾기  (`E4-Field.dc.html`)

- 실전내 역치 찾기
- 랩 없이 역치 찾기, 정확도는 방법마다 다르다
- 말하기 테스트→ LT1 근처
- 문장으로 편하게 말이 되는 마지막 강도. 연구마다 맞는 역치가 조금씩 달라요
- 대략
- 1시간 레이스 페이스→ LT2 근처
- 약 1시간 전력으로 갈 수 있는 페이스 (Daniels의 T 페이스, 코치 기준)
- 대략
- 임계속도 테스트→ LT2 위쪽 경계
- 같은 날 3600·2400·1200m 전력, 사이 30분 휴식. 실험실 측정과 r = 0.89 (10명) · MLSS보다 조금 빨라요
- 비교적 좋음
- 스마트워치 추정→ 참고용
- LT 심박은 실험실과 비슷했지만, LT 페이스는 크게 틀릴 수 있어요 (가민 FR265 평균 오차 약 26%, 2025)
- 페이스는 주의
- 임계속도 간단 계산 (기록 2개)
- (긴 거리 − 짧은 거리) ÷ (긴 시간 − 짧은 시간)
- 예: 3600m 14:00 · 1200m 4:00 → 2400m ÷ 600초 = 4.0 m/s = 14.4 km/h ≈ 4:10/km
- Quinn & Coons (2011) J Sports Sci · Daniels' Running Formula · Galbraith et al. (2014) Int J Sports Physiol Perform · Nixon et al. (2021) · Front Physiol (2025) 스마트워치 LT 검증 · 계산 예시는 가상 기록

### 4편 14 팩트 체크  (`E4-FactCheck.dc.html`)

- 팩트 체크흔한 말 검증
- 젖산역치 팩트 체크
- 맞아요
- “역치 속도는 기록과 밀접하다”
- 3.2km~마라톤 기록과 상관 r ≥ 0.91 (1979, 18명)
- “VO2max가 그대로여도 역치는 오른다”
- 래드클리프 11년: VO2max 약 70 그대로, LT2 16 → 20 km/h (사례)
- 애매해요
- “존2 = 최대심박 60~70%”
- 앱·연구·코치마다 존2 정의가 달라요. 최대심박 공식도 ±10박 오차
- “워치가 알려주는 젖산역치”
- 심박은 비슷했지만 페이스는 크게 틀릴 수 있어요 (2025)
- “폴라라이즈드(80/20)가 정답”
- 메타분석상 다른 분포와 차이가 작거나 없어요
- 틀려요
- “젖산은 피로물질이다”
- 젖산은 연료이고, 산성화를 오히려 늦춰요
- “다음 날 근육통은 젖산 때문”
- 젖산은 1~2시간이면 거의 정리, 근육통은 1~3일 뒤 최고
- “역치 = 4 mmol”
- 사람마다 달라요. 4 mmol 기준이 역치를 약 12% 높게 잡은 연구도 있어요
- “젖산은 산소가 부족해서 생긴다”
- 산소가 충분해도 계속 만들어져요. 오르는 건 치우는 속도를 넘을 때
- Farrell (1979) · Jones (2006) · Tanaka (2001) · Front Physiol (2025) · 2024·2025 메타분석 · Robergs (2004) · Cheung (2003) · Beneke (1995) · Ferguson (2018)

### 4편 15 이번 주부터  (`E4-Todo.dc.html`)

- 실천이번 주부터
- 역치를 올리는 다섯 가지
- 1쉬운 날은 LT1 아래로 리뷰
- 문장으로 대화가 되는 강도. 세계 정상급도 거리의 80% 이상이 이 구간이에요.
- 2역치 세션은 주 1~2회, 끊어서 현장
- LT2보다 살짝 아래에서 6~10분씩, 짧게 쉬며 반복. 역치를 넘지 않게 하는 게 노르웨이식의 핵심이에요.
- 3몇 주마다 내 역치 다시 찾기 현장
- 1시간 레이스 페이스나 임계속도 테스트로 확인해요. 워치 페이스는 참고만 해요.
- 4롱런으로 ‘지쳐도 유지’ 연습 상관
- 90분 뒤 역치가 덜 떨어진 사람이 마라톤도 빨랐어요. 롱런 후반을 흐트러지지 않게 달려요.
- 5하이록스: 러닝은 LT2 아래로 코치 해석
- 젖산은 스테이션에서 더 올라요. 러닝 구간에서 정리할 여유를 남겨두세요. 하이록스 연구(11명)에서도 VO2max와 지구력 훈련량이 완주 기록과 관련 있었어요.
- Haugen et al. (2022) · Casado et al. (2023) · Daniels · Galbraith et al. (2014) · Front Physiol (2025) · Hunter & Muniz-Pumares (2025) · Brandt et al. (2025) Front Physiol

### 4편 16 3요소 정리  (`E4-Formula.dc.html`)

- 기록은 세 가지의 조합, 그리고 내구성
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
- +
- 내구성 지쳐도 이 세 값을 얼마나 지키나. 최근 ‘4번째 요소’로 주목받아요.
- 2편
- VO2max
- 고강도 인터벌로 엔진 키우기
- 3편
- 러닝 이코노미
- 수년간 달리기 + 근력·업힐
- 4편
- 젖산역치
- 쉬운 양 + 넘지 않는 역치 세션
- 모델: Joyner (1991) J Appl Physiol · Jones (2024) J Physiol · 모든 값은 체중 1kg당 · 숫자는 1편 예시

### 4편 17 참고문헌  (`E4-Refs.dc.html`)

- 참고참고문헌
- 1Faude O, Kindermann W, Meyer T (2009) Lactate threshold concepts: how valid are they? Sports Med
- 2Jamnick NA et al. (2020) An examination and critique of current methods to determine exercise intensity. Sports Med
- 3Jones AM, Burnley M, Black MI, Poole DC, Vanhatalo A (2019) The maximal metabolic steady state: redefining the 'gold standard'. Physiol Rep
- 4Nixon RJ et al. (2021) Steady-state VO2 above MLSS: evidence that critical speed better represents maximal metabolic steady state in well-trained runners
- 5Beneke R (1995) Anaerobic threshold, individual anaerobic threshold, and maximal lactate steady state in rowing. Med Sci Sports Exerc
- 6Robergs RA, Ghiasvand F, Parker D (2004) Biochemistry of exercise-induced metabolic acidosis. Am J Physiol Regul Integr Comp Physiol
- 7Brooks GA. The lactate shuttle / The origin of lactate in exercise (리뷰)
- 8Ferguson BS et al. (2018) Lactate metabolism: historical context, prior misinterpretations, and current understanding. Eur J Appl Physiol
- 9Billat VL et al. (2003) The concept of maximal lactate steady state. Sports Med
- 10Cheung K, Hume P, Maxwell L (2003) Delayed onset muscle soreness: treatment strategies and performance factors. Sports Med
- 11회복 방법별 젖산 반감기 실험 (1996, 10명) · Denadai BS et al. (2000)
- 12Tanaka H, Monahan KD, Seals DR (2001) Age-predicted maximal heart rate revisited. J Am Coll Cardiol
- 13Quinn TJ, Coons BA (2011) The Talk Test and its relationship with the ventilatory and lactate thresholds. J Sports Sci
- 14Jones AM et al. (2021) Physiological demands of running at 2-hour marathon race pace. J Appl Physiol
- 15Farrell PA et al. (1979) Plasma lactate accumulation and distance running performance. Med Sci Sports
- 16Jones AM (2006) The physiology of the world record holder for the women's marathon. Int J Sports Sci Coach
- 17Casado A, Foster C, Bakken M, Tjelta LI (2023) Does lactate-guided threshold interval training within a high-volume low-intensity approach represent the next step…? Int J Environ Res Public Health
- 18Haugen T, Sandbakk Ø, Seiler S, Tønnessen E (2022) The training characteristics of world-class distance runners. Sports Med Open
- 19Casado A, Hanley B, Santos-Concejero J, Ruiz-Pérez LM (2021) World-class long-distance running performances are best predicted by volume of easy runs and deliberate practice of short-interval and tempo runs. J Strength Cond Res
- 20Esteve-Lanao J, Foster C, Seiler S, Lucia A (2007) Impact of training intensity distribution on performance in endurance athletes. J Strength Cond Res
- 21(2024) Comparison of polarized versus other types of endurance training intensity distribution on athletes' endurance performance: a systematic review with meta-analysis. Sports Med
- 22Rosenblat MA et al. (2025) Which training intensity distribution intervention will produce the greatest improvements…? Network meta-analysis of individual participant data. Sports Med
- 23Hunter B, Muniz-Pumares D (2025) Durability of parameters associated with endurance running in marathoners. Eur J Sport Sci
- 24Stevenson JD, Kilding AE, Plews DJ, Maunder E (2022) Prolonged cycling reduces power output at the moderate-to-heavy intensity transition. Eur J Appl Physiol
- 25Jones AM (2024) The fourth dimension: physiological resilience as an independent determinant of endurance exercise performance. J Physiol
- 26Galbraith A et al. (2014) A single-visit field test of critical speed. Int J Sports Physiol Perform
- 27(2025) Validity of smartwatch-derived estimates of lactate threshold heart rate and pace compared to graded exercise testing. Front Physiol
- 28Brandt T, Ebel C, Lebahn C, Schmidt A (2025) Acute physiological responses and performance determinants in Hyrox©. Front Physiol
- 29현장 자료: Daniels' Running Formula (T 페이스) · Outside · Trail Runner (노르웨이 방법) · LetsRun 노르웨이 싱글 정리 · 킵초게 캠프 기사
- 현장 사례(기사·인터뷰·커뮤니티)는 슬라이드에서 연구 근거와 구분해 표시했어요

