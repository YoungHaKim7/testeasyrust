# Vim Setting (type 빨강색으로 강조하기 칙칙한 검은색 너무 싫다.)

-vim 에서

```
:hi CocInlayHint ctermbg=125

```

- 내가 원하는 색깔 256 컬러에서 고르자 ㅎㅎ

https://www.ditig.com/256-colors-cheat-sheet

<br>

<hr>

# Vim Command

```
:CocCommand

// rust-analyzer 다시 시작
FUZZY > rust-analyzer.reload

// rust-analyzer upgrade
FUZZY > rust-analyzer.upgrade

:CocOpenLog
error log 보기

:CocConfig
VSCode Setting.JSON 과 비슷
```

<br>

# Vim CocInstall (rust-analyzer)

https://github.com/fannheyward/coc-rust-analyzer#highlight-group

```
:CocInstall coc-rust-analyzer


remove rust-analyzer config from coc-settings.json if you've set

NOTE: For Apple Silicon users, you shouldn't use Node.js v15, checkout #975 for more.


// 이렇게 하면 coc-settings.JSON 에 들어간다.
:CocConfig

```

https://rust-analyzer.github.io/manual.html#vimneovim

<br>

# Vim 창 나누기

```
// 창 좌우로 나누기
:vs


// 창 상하로 나누기
:sp


// 가운데 선 아래(Down)으로 이동 (:sp에서 주로 사용)
:ObviousResizeDown

// 가운데 선 위(Up)로 이동 (:sp에서 주로 사용)
:ObviousResizeUp

// 가운데 선 오른쪽(Right)으로 이동(:vs에서 주로 사용)
:ObviousResizeRight

// 가운데 선 왼쪽(Left)으로 이동(:vs에서 주로 사용)
:ObviousResizeLeft
```

- Plug in 설치 없이 사용 가능

```
// Plug In 설치 없이 가능한 명령어
// 위, 아래 크기 조절
:resize +10

// 좌, 우 조절
:vertical resize +10

```

<hr>

<br>

<h1>Updating</h1>
2021-12-10 : Rust 기초 강의 시작<br>

> #### Rust 스승님 Git

> - https://github.com/Dhghomon/easy_rust/

> - 유튜브 주소(한글 강의)
> - 1강
> - https://www.youtube.com/watch?v=W9DO6m8JSSs

<hr>

> - 유튜브 주소(영어 강의)
> - 1강
> - https://www.youtube.com/watch?v=-lYeJeQ11OI&list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk&index=1

-Easy Rust eBook

- https://dhghomon.github.io/easy_rust/
<hr>

- Rust 강의 집중!!

<br>

# Rust PlayGround

[https://play.rust-lang.org/](https://play.rust-lang.org/)
