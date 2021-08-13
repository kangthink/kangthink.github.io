
## 글쓰기
1. `content/posts` 아래 `mdx` 포멧의 파일 추가해서 글쓰기
2. 완성 전에는 `main` branch 관리
3. 배포 시 `yarn deploy` 실행


## Warning
[gatsby-theme-minimal-blog)](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-minimal-blog)를 활용해 홈 화면의 hero 와 bottom을 바꾸려면 의존파일을 덮어써야 한다.

```
// src/@lekoarts/gatsby-theme-minimal-blog/texts/hero.mdx
<Text sx={{ fontSize: [4, 5, 6], fontWeight: `light`, color: `heading` }}>
  반갑습니다. 개발자
</Text>
<Text sx={{ fontSize: [4, 5, 6], fontWeight: `bold`, color: `heading` }}>
  강태훈
</Text>
<Text sx={{ fontSize: [4, 5, 6], fontWeight: `light`, color: `heading` }}>
  입니다.
</Text>

생각을 추상화하여 코드로 구현하는 것에 흥미를 가집니다. 심리학, 철학, 그리고 교육에 관심이 많으며,
`어떻게 배움을 최적화 할 수 있을까?`를 인생의 화두로 잡고 있습니다.
```

```
// src/@lekoarts/gatsby-theme-minimal-blog/texts/bottom.mdx
<Title text="Projects" />
- 🔒 추후 공개

```