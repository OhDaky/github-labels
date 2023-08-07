# github-labels

✨ github-label-sync를 위한 레포

1. labels.json 파일

```
[
  {"name": "front",
  "color": "F3CBA8",
  "description": "설명",
  }, {
    "name": "",
    "color": "E5B7D1",
    "description": "설명2"
  }
]
```

2. personal access token 발급받기

- Select scopes : repo 선택하기

3. npx github-label-sync --access-token {token} --labels ./labels.json {repo}
