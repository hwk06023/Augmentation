# Sequence

### Window cropping or slicing
원본 데이터에서 랜덤하게 연속적인 slice를 추출하는 방법이다.
CV에서 이미지를 랜덤하게 잘라 데이터를 증강하는 것과 유사하다.

### Window warping
랜덤한 구간을 선정하여 압축 or 확장하는 방법이다. (DTW와 유사함)
원본 시계열의 전체 길이를 바꿀 수 있다.

https://www.iaarc.org/publications/fulltext/ISARC_2019_Paper_152.pdf

### Flipping
원본 데이터의 부호를 바꿔 새로운 시퀀스를 만드는 방법이다.
부호를 바꿔도 라벨은 동일하다. (시계열 분류, 이상치 탐지 둘 다 해당됨)

### Noise injection
라벨을 바꾸지 않은 채 원본 데이터에 노이즈를 삽입