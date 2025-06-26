# 4일차
### 자율주행 코드에 대해 배움
https://docs.google.com/document/d/1FA0sFxhFDvLXd1n05eeG_ynkdImzaR6Ff19dHeRtbao/edit?tab=t.0

GPS에 쓰이는 변수들.
1. 위도 (Latitude) : 지구의 수직방향 위치, 적도를 기준선으로 북쪽·남쪽 방향으로 측정한 각도. 범위: −90°(남극) ~ +90°(북극)
2. 경도 (Longitude) : 본초 자오선(영국 그리니치)으로부터 동쪽·서쪽 방향으로 측정한 각도. 범위: −180°(서경) ~ +180°(동경)
3. 고도 (Altitude / Elevation) : 기준면(보통 해수면)을 기준으로 위아래 방향으로 측정한 높이. Altitude는 항공기 고도 등 대기 중 높이를 가리킬 때 주로 사용 / Elevation은 지표면의 해발고도를 말할 때 주로 사용


**예시) 서울특별시청 :**
위도 37.5665° N (Latitude 37.5665° N)
경도 126.9780° E (Longitude 126.9780° E)
고도 38 m (Elevation 38 m)

### 리스트와 딕셔너리
https://claude.ai/public/artifacts/fd98c798-ab20-40a4-8a3b-537503b9849c

인덱스 규칙 : 음수 인덱스는 마지막 인덱스를 의미하고, 인덱스 범위를 벗어난 접근은 오류이다
```
#리스트 주요 메소드들.
.append(값): 끝에 값 추가
.insert(위치, 값): 특정 위치에 값 삽입
.remove(값): 첫 번째로 찾은 값 제거
.pop(): 마지막 값 제거하고 반환
.len(리스트): 리스트 길이(개수) 반환 - 매우 자주 사용!
```
