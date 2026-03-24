# beautiful-mermaid-cli

Mermaid 다이어그램을 ASCII 아트로 렌더링하는 beautiful-mermaid 기반 경량 CLI (bmm).

## 프로젝트 구조

```
bmm/
├── package.json        # bin: { "bmm": "./src/cli.ts" }
├── src/
│   ├── cli.ts          # 엔트리포인트 + argv 파싱 + help 텍스트
│   └── render.ts       # beautiful-mermaid 래핑
└── bun.lock
```

## 개발

- Language: TypeScript
- Runtime: Bun
- Task Runner: mise
- Build: `mise run build`
- Test: `mise run test`
- Lint: `mise run lint`
- Format: `mise run fmt`
