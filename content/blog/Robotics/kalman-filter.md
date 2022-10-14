---
title: Kalman Filter
date: 2022-10-12 15:10:25
category: robotics
thumbnail: { thumbnailSrc }
draft: false
---

이 글은 [김진솔님의 블로그의 글](https://gaussian37.github.io/ad-ose-lkf_basic/)을 참고하여 작성했습니다. 다양한 사람들이 이해할 수 있도록 부연 설명과 시각화를 추가했습니다.

## Bayes Filter
칼만 필터는 센서에서 값을 읽어온 뒤 읽어온 값을 가지고 현재 상태에 대해서 추정하고자 할 때 씁니다.
