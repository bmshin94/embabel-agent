# Embabel Agent Framework (embabel/embabel-agent)

## 프로젝트 개요
금융 및 엔터프라이즈 환경에서 검증된 엔터프라이즈 자바 가상머신(JVM) 생태계에서 자율 AI 에이전트를 안정적으로 구축하는 "엔터프라이즈 에이전트 프레임워크"
기업의 기존 거대한 백엔드 인프라와 즉각 융합되어 기업 데이터를 안전하게 다루는 신뢰도 100%의 엔터프라이즈 에이전트 구현
보수적인 대기업이나 금융권 시스템에서도 안심하고 최첨단 인공지능 에이전트를 도입할 수 있도록 돕는 탄탄한 뼈대

## 핵심 특징 & 추천 분야
- 엔터프라이즈에이전트
- 대기업금융권표준인프라
- 기존시스템완벽융합
- 신뢰도100안전엔진
- 자율비즈니스에이전트

---
*이 문서는 오픈소스 큐레이터(Curator-Agent)에 의해 자동 생성된 가이드 문서입니다.*


---
## 기존 CLAUDE.md 내용

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Important

- ALL instructions within this document MUST BE FOLLOWED, these are not optional unless explicitly stated.
- ASK FOR CLARIFICATION If you are uncertain of anything within the document.
- DO NOT edit more code than you have to.
- DO NOT WASTE TOKENS, be succinct and concise.

## Coding Style

IMPORTANT: Adhere to coding style in `.embabel/coding-style.md` for coding style guidance.

## Working Approach

NEVER execute git commit or push. You may use git tools for history, diffing or staging only.

ALWAYS work test first. When making an enhancement or fixing a bug,
write failing tests first, then implement the feature or fix the bug to make the tests pass.

IMPORTANT: You should build the most relevant project (closest pom.xml) with Maven before
presenting finished changes. Run the individual tests you have changed
or that are most relevant.

If any change impacts usage of the project, update relevant documentation files.

## Advice for Documentation in embabel-agent-docs

When working on documentation in the `embabel-agent-docs` module, follow these guidelines:

Use Asciidoctor syntax for writing documentation.

When asked to edit a particular .adoc file, look for a parallel file with a name prefixed with a . for instructions.

For example, if you are asked to edit `tools.adoc`, look for `.tools.adoc` for specific instructions about how to go
about it.
Thus you will be given a combination of user instructions such as ("edit tools.adoc to cover the FooBar tool in
FooBar.kt").
You will follow the user instruction but bear in mind the instructions in any .tools.adoc file.
If there is no .<filename>.adoc file, follow the general instructions in this document.

When writing documentation, ensure that you cover the following general instructions:

NEVER make up code unless asked. Code examples must come from the following repositories:

- This repository
- The `embabel-agent-examples` repository at https://github.com/embabel/embabel-agent-examples/
- The `java-agent-template` repository at https://github.com/embabel/java-agent-template/
- The `impromptu` repository at https://github.com/embabel/impromptu/
- Any repositories the user specifically asks you to use



