<div align=center>

# Logit-TimeLine
Log-it 서비스의 타임라인 오픈소스를 소개합니다.

</br>
</br>
</br>

<image src="https://user-images.githubusercontent.com/59721896/218363355-7da8c7d3-a478-4fc5-9560-2e460ec0098a.png" width=70%>

</br>
</br>
</br>

</div>

<div align=center>

## 개발 환경

</div>

- `Vue3`를 기준으로 만들어졌습니다. ([Vue3 Doc 바로가기 >](https://vuejs.org/guide/introduction.html))
- `Swiper Vue.js Components`를 활용한 스와이프 기능을 추가했습니다. ([swiper 바로가기 >](https://swiperjs.com/vue))

</br>
</br>
</br>

<div align=center>

## 기능 소개

</div>

✔  시작 날짜를 기준으로 오름차순 정렬합니다.

✔  `일주일 단위(일-토)`로 나누어 타임라인을 생성합니다.

✔  `첫 날, 전 주, 오늘, 다음 주, 마지막 주` 총 다섯 가지의 스와이프 이동이 가능합니다.

</br>
</br>
</br>

<div align=center>

##  소스 사용법

</div>

```javascript
...
<script>
  ...
    setup() {
      const state = reactive({
        events: [{title: '이벤트 1', startDate: '2023-02-13', endDate: '2023-03-01'},
                  ... ]
  ...
</script>
...
```

> script > setup > state > reactive > events
>
> startDate와 endDate에 `yyyy-MM-dd` 형식의 날짜를 넣어주세요.

</br>
</br>
</br>


---

<image src="https://user-images.githubusercontent.com/59721896/218374787-766e98b3-0367-4b6b-9760-7043427d17ad.png" width="10%">


[Log-it 서비스 바로가기 >](https://i8a609.p.ssafy.io/)

[타임라인 데모 바로가기 >](https://i8a609.p.ssafy.io/demo)

---
