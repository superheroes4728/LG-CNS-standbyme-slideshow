# LG CNS StandbyME Slideshow

GitHub Pages에서 5대의 StandbyME 화면에 각각 다른 이미지 슬라이드쇼를 띄우는 정적 웹 페이지입니다.

## 화면 주소

GitHub Pages 배포 후 아래 주소를 각 기기에 열면 됩니다.

- Screen 1: `https://superheroes4728.github.io/LG-CNS-standbyme-slideshow/?screen=1`
- Screen 2: `https://superheroes4728.github.io/LG-CNS-standbyme-slideshow/?screen=2`
- Screen 3: `https://superheroes4728.github.io/LG-CNS-standbyme-slideshow/?screen=3`
- Screen 4: `https://superheroes4728.github.io/LG-CNS-standbyme-slideshow/?screen=4`
- Screen 5: `https://superheroes4728.github.io/LG-CNS-standbyme-slideshow/?screen=5`

## 이미지 교체 방법

1. `screens/screen1`부터 `screens/screen5` 중 원하는 폴더에 이미지를 넣습니다.
2. 같은 폴더의 `list.json`에 재생할 파일명을 순서대로 적습니다.
3. 파일명 순서가 슬라이드 순서입니다.

예시:

```json
[
  "01.jpg",
  "02.jpg",
  "03.jpg"
]
```

## 운영 메모

- GitHub API를 쓰지 않고 `list.json` 정적 파일만 읽습니다.
- 이미지 목록은 10분마다 다시 확인합니다.
- 페이지는 6시간마다 자동 새로고침됩니다.
- 이미지는 가능하면 한 장당 1MB 이하의 JPG 또는 WebP를 권장합니다.
2026년  7월  4일 토요일 18시 42분 07초 KST
2026년  7월  4일 토요일 18시 43분 26초 KST
