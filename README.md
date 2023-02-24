# 러스트 프로그래밍 언어

> ### 알립니다
>
> 이 번역본은 2017년 7월경부터 번역된 2nd edition을 기반으로 하고 있으며,
> 완료된 상태입니다. 문서의 최신 버전은 [https://github.com/rust-kr/doc.rust-kr.org](https://github.com/rust-kr/doc.rust-kr.org)에서
> 진행하고 있습니다. **최신 문서에 대한 정보는 rust-kr에 있는 저장소에서 확인해주세요.**
>
> 이 저장소는 최신 버전의 문서 번역이 완료될때까지 계속 유지될 것이며
> 그동안의 **2판 관련 오타 수정 등의 issue 및 pull-request만 처리**될
> 예정입니다.

### 빌드된 문서 바로가기

- [2nd edition: 완역](https://rinthel.github.io/rust-lang-book-ko)
- [2021 edition: 번역중](https://rust-kr.github.io/doc.rust-kr.org)

### 환영합니다!

[![빌드 상태](https://github.com/rinthel/rust-lang-book-ko/actions/workflows/build.yml/badge.svg)](https://github.com/rinthel/rust-lang-book-ko/actions/workflows/build.yml)

안녕하세요? 한국어를 쓰시는 러스트 유저 여러분들을 환영합니다.
이 저장소는 러스트 프로그래밍 언어 문서(소위 the book이라고 일컫는)의
2번째 판 번역을 위해 fork 되었습니다.
2번째 판의 빌드된 문서는 상단의 링크를 통해 읽으실 수 있습니다.

<!--혹시 함께 번역에 참여하고 싶으신 분들, 환영합니다! :)
저에게 메세지를 주시거나 discussions에 요청을 남겨주시면,
collaborator로 등록해 드리겠습니다!

### 번역 기조

#### 친절한 구어체

1번째 판도 그렇지만 2번째 판을 보면서 느낀 점은, 기초 C 프로그래밍 정도의 수준을
익힌 분들 혹은 스크립트 언어만 공부해본 분들 또한 읽기 쉽게끔 기초 개념에 충실한
설명을 하고 있다는 점입니다. 우리가 러스트의 저변을 더 넓히고자 한다면 보다
친절한 어투가 좋겠다고 생각하고 있습니다.

#### 번역하기 애매한 용어는 가급적 원어로

번역하기 애매한 용어를 억지로 한글화 하는 것 보다는 원어를 그대로 사용하는 편이
오해를 줄이는데 더 도움이 될거라고 생각하고 있습니다.

### 2018-edition 번역 과정 제안

- chapter 별로 issue를 만들어주세요
  * 혹시 같은 chapter에 대한 issue가 이미 만들어져있는지,
    assignee 가 할당되어 있는지 확인해주세요
- 해당 chapter에 대한 second edition 번역본을 비교하여 동일한 부분을 우선 붙여넣기 합시다
  * 붙여넣기 하면서 혹시 예제 코드 번호 등이 변경되진 않았는지 살펴봅시다
- 붙여넣은 부분에서 기존 번역 중 어색한 부분이 있다면 수정한 다음, 1차 pull-request를 날려줍시다.
- 새로 추가된 부분에 대한 번역을 진행한 뒤, 2차 pull-request를 날려줍시다.

### 오타 및 오역 수정 관련

repo fork -> 수정 후 pull-request 하셔도 좋고, 오타 및 오역에 대한
issue를 만들어 주셔도 좋습니다.

### 현재까지 번역 용어 정리 

번역 용어 정리는 Appendix - H에서 관리할 예정입니다.
더 좋은 번역 용어가 있으신 분들은 discussions에 의견 주시면 반영하겠습니다!

### 기타 사항

기타 논의할 사항 혹은 건의할 내용이 있다면 discussions에 남겨서 함께
이야기하면 좋겠습니다.-->

<!-- 1번째 판에 대한 번역 작업은 [sarojaba님께서 운영하시는 penflip 페이지](
https://www.penflip.com/sarojaba/rust-doc-korean/blob/master/About.txt)에
거의 완성되어 있으므로, 혹시 교본을 보러 오신 분이라면 이쪽을 추천하고 싶습니다. :)

이 저장소는 앞서 말씀드렸듯이 2번째 판에 대한 번역 작업을 위해 만들어졌습니다. 아래에 있는 설명에서
보시는 것과 같이, 러스트 문서는 현재 [mdbook](https://github.com/azerupi/mdBook)이라고
부르는 마크다운 기반의 웹문서 작성 툴을 이용해 빌드되는데, 이 툴에 다국어 지원 기능이 완성되면
번역본들도 함께 합쳐질 예정이라고 합니다. 한편, 2번째 판의 내용은 1번째 판과 많은 부분이 달라졌기에
새로 번역해볼 필요 겸 공부할 차원에서 만들어진 저장소라고 보시면 되겠습니다.

현재 2번째 판의 문서는 수시로 고쳐지고 있는 상태지만, [원본 저장소](https://github.com/rust-lang/book)에
프로젝트란을 보시면 frozen column이라고 되어 있는 부분들은 거의 완성되어 많은 수정이 이루어지지 않을 것이라고
언급되고 있기에, 이런 부분들을 위주로 먼저 번역해보고자 합니다. -->

---

# The Rust Programming Language

This repo contains two editions of “The Rust Programming Language”.

The second edition is a rewrite that will be printed by NoStarch Press,
available around October 2017.

[You can read it online][html]; the last few chapters aren't completed yet, but
the first half of the book is much improved from the first edition. We recommend
starting with the second edition.

[html]: http://rust-lang.github.io/book/

[The first edition is still available to read online][first].

[first]: https://doc.rust-lang.org/book/

## Requirements

Building the book requires [mdBook] >= v0.0.13. To get it:

[mdBook]: https://github.com/azerupi/mdBook

```bash
$ cargo install mdbook
```

## Building

To build the book, first `cd` into either the `first-edition` or
`second-edition` directory depending on which edition of the book you would
like to build. Then type:

```bash
$ mdbook build
```

The output will be in the `book` subdirectory. To check it out, open it in
your web browser.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

To run the tests:

```bash
$ mdbook test
```

## Contributing

We'd love your help! Please see [CONTRIBUTING.md][contrib] to learn about the
kinds of contributions we're looking for.

[contrib]: https://github.com/rust-lang/book/blob/master/CONTRIBUTING.md

### Translations

We'd especially love help translating the second edition of the book! See the
[Translations] label to join in efforts that are currently in progress. Open
a new issue to start working on a new language! We're waiting on [mdbook
support] for multiple languages before we merge any in, but feel free to
start! The chapters in [the frozen column] of the project won't see major
changes, so if you start with those, you won't have to redo work :)

[Translations]: https://github.com/rust-lang/book/issues?q=is%3Aopen+is%3Aissue+label%3ATranslations
[mdbook support]: https://github.com/azerupi/mdBook/issues/5
[the frozen column]: https://github.com/rust-lang/book/projects/1

## No Starch

As the second edition of the book will be published by No Starch, we first
iterate here, then ship the text off to No Starch. Then they do editing, and we
fold it back in.

As such, there’s a directory, *nostarch*, which corresponds to the text in No
Starch’s system.

When we've started working with No Starch in a word doc, we will also check
those into the repo in the *nostarch/odt* directory. To extract the text from
the word doc as markdown in order to backport changes to the online book:

1. Open the doc file in LibreOffice
1. Accept all tracked changes
1. Save as Microsoft Word 2007-2013 XML (.docx) in the *tmp* directory
1. Run `./doc-to-md.sh`
1. Inspect changes made to the markdown file in the *nostarch* directory and
   copy the changes to the *src* directory as appropriate.

## Graphviz dot

This is mostly for Carol's reference because she keeps having to look it up.

We're using [Graphviz](http://graphviz.org/) for some of the diagrams in the
book. The source for those files live in the `dot` directory. To turn a `dot`
file, for example, `dot/trpl04-01.dot` into an `svg`, run:

```bash
$ dot dot/trpl04-01.dot -Tsvg > src/img/trpl04-01.svg
```

In the generated SVG, remove the width and the height attributes from the `svg`
element and set the `viewBox` attribute to `0.00 0.00 1000.00 1000.00` or other
values that don't cut off the image.

## Spellchecking

To scan source files for spelling errors, you can use the `spellcheck.sh`
script. It needs a dictionary of valid words, which is provided in
`dictionary.txt`. If the script produces a false positive (say, you used word
`BTreeMap` which the script considers invalid), you need to add this word to
`dictionary.txt` (keep the sorted order for consistency).
