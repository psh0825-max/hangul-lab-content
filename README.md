# hangul-lab-content

Hangul Lab 앱이 런타임에 받아가는 콘텐츠. GitHub Pages로 정적 서빙한다.
앱을 재출시하지 않고 브리핑을 갱신하기 위한 저장소.

- `news.json` — 매일 브리핑 피드

## 갱신 방법

앱 저장소(`~/Projects/01-products/hangul-lab`)에서:

```
npm run publish:news
```

`src/data/news.js`의 SEED_NEWS를 news.json으로 내보내고 이 저장소에 push한다.

## 편집 기준

`src/data/news.js` 상단 주석 참조. 요약하면:
지나간 일을 보도하지 않는다(예정·설명 위주), 독자는 한국에 관심 있는 외국인,
출처 링크 필수, 항목마다 한국어 낱말 하나.
