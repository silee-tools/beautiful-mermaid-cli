# beautiful-mermaid-cli

[English (영어)](../README.md)

Mermaid 다이어그램을 ASCII 아트로 렌더링하는 beautiful-mermaid 기반 경량 CLI 도구.

## 기술 스택

- 런타임: [Bun](https://bun.sh/)
- 언어: TypeScript
- 코어: [beautiful-mermaid](https://github.com/nicholasgasior/beautiful-mermaid)

## 시작하기

```bash
# 의존성 설치
bun install

# 직접 실행
echo 'graph LR; A-->B-->C' | bun src/cli.ts

# 글로벌 설치
bun link
bmm --help
```
