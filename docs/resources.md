# 학습 자료 라이브러리

매체(영상·글·책·코스) 가리지 않고 모은 자료 모음. 모든 링크는 조사 시점에 실재를 확인했다.

**쓰는 법**: 메인 줄기(1. Godot)부터 진행하다가, 모르는 개념·인접 분야가 나오면 해당 섹션(2~6)에서 골라 보강(가지치기). 보강한 항목은 [roadmap.md](roadmap.md)의 "가지치기 백로그"에 기록.

> 난이도: 입문 / 중급 / 심화 · 언어: KR / EN

---

## 1. Godot 엔진 / GDScript (메인 줄기)

### 공식 문서
- [Godot 공식 문서 (한국어)](https://docs.godotengine.org/ko/4.x/) — KR · 입문~심화 · 모든 것의 기준. Getting Started → Tutorials 순.
- [Your first 2D game (영문)](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html) — EN · 입문 · 공식 단계별 2D 튜토리얼(한국어판도 있음).

### 무료 인터랙티브 코스 / 사이트
- [GDQuest — Learn GDScript From Zero](https://gdquest.github.io/learn-gdscript/) — EN · 입문 · 브라우저에서 코드를 직접 치며 배우는 27강. **코딩이 처음이면 1순위.** ([데스크톱 앱](https://gdquest.itch.io/learn-godot-gdscript))
- [GDQuest — Learn 2D Gamedev from Zero with Godot 4](https://school.gdquest.com/products/learn_2d_gamedev_godot_4) — EN · 입문~중급 · 2D(횡스크롤 포함) 체계적 코스.
- [KidsCanCode — Godot 4 Recipes](https://kidscancode.org/godot_recipes/4.x/) — EN · 입문~중급 · 주제별 레시피 문서. 막힐 때 검색용 레퍼런스.
- [godotlearning.com](https://godotlearning.com/) — EN · 입문 · 노드/씬/시그널/물리 인터랙티브 학습.

### YouTube (영어)
- [Brackeys — How to make a Video Game (Godot)](https://www.youtube.com/watch?v=LOhfqjmasi0) — EN · 입문 · 1시간 17분에 2D 플랫포머 1개 완성. **영어 영상 1순위.** ([프로젝트 파일](https://github.com/Brackeys/first-game-in-godot))
- [Brackeys — How to program in Godot (GDScript)](https://www.youtube.com/watch?v=e1zJS31tr88) — EN · 입문 · 위 영상 다음 GDScript 문법 집중.
- [Clear Code — The ultimate introduction to Godot 4](https://www.youtube.com/watch?v=nAh_Kx5Zh5Q) — EN · 입문~중급 · 11.5시간 무료 강좌, 2D 게임 풀제작. ([코드](https://github.com/clear-code-projects/UltimateGodotIntro2D))
- [GDQuest 채널](https://www.gdquest.com/) — EN · 입문~중급 · Godot 4 콘텐츠 본진.

### 한국어 강의 / 영상
- [코드쉼터 — Godot으로 시작하는 첫 게임 개발 (인프런, 무료)](https://www.inflearn.com/course/고도-첫-게임개발) — KR · 입문 · 무료, 첫걸음용.
- [코드쉼터 — 마리오라이크 2D PC 게임 만들기 (인프런)](https://www.inflearn.com/course/고도-마리오라이크-만들기) — KR · 입문~중급 · 마리오풍 횡스크롤, **목표와 정확히 일치.**
- [머신튜터 — 초보자를 위한 고도엔진 입문 (인프런)](https://www.inflearn.com/course/초보-고도엔진-입문) — KR · 입문 · Godot 4.2~4.3, 개발 경험 불필요.
- [코드박치기 — 고도 엔진 게임 개발 박치기 (인프런)](https://www.inflearn.com/course/고도엔진-게임개발-박치기) — KR · 입문 · 애니메이션·충돌·UI·레벨까지 폭넓게.
- [고도엔진 한국어 강좌 정리 (아카라이브)](https://arca.live/b/godotengine4/117774143) — KR · — · 한국 커뮤니티 강좌 허브.

### 2D 플랫포머 특화
- [HeartBeast — Heart Platformer (Godot 4)](https://www.youtube.com/playlist?list=PL9FzW-m48fn0i9GYBoTY-SI3yOBZjH1kJ) — EN · 입문~중급 · 플랫포머 점프 물리·이동 시리즈. (HeartBeast의 Action RPG는 Godot 3·플랫포머 아님 — 주의)
- [DevWorm — 2D Platformer Tutorial In Godot 4](https://www.youtube.com/playlist?list=PLCcur7_Y2zTdKIQ2oM2Ec8MEfeBnAbEXT) — EN · 입문 · 2D 플랫포머 전용 단계별.
- [freeCodeCamp — Your First Platformer with Godot](https://www.freecodecamp.org/news/learn-game-development-by-building-your-first-platformer-with-godot/) — EN · 입문 · 레벨·플레이어·애니메이션·체크포인트.

---

## 2. 게임 기획 (GDD · 스코프 · 버티컬 슬라이스) 🌿

- [GDD(게임 디자인 문서)란 (brunch)](https://brunch.co.kr/@kimwayne/50) — KR · 글 · GDD 정의·구성·작성법·실수, 한국어 입문.
- [쩌는 게임 기획서, 이렇게 쓴다 (GDC 2008 번역)](https://www.slideshare.net/istoriae/how-to-write-great-design-documents-from-gdc2008-korean) — KR · 글 · 좋은 기획서 12원칙.
- [효과적인 게임 기획서 템플릿 (프라임 커리어)](https://prime-career.com/article/477) — KR · 글 · 바로 쓰는 템플릿.
- [학생 실기평가용 기획서 준비 가이드 (brunch)](https://brunch.co.kr/@whtdrgon/188) — KR · 글 · 범위를 좁혀 기획서 쓰는 법, 스코프 감각.
- [게임 디자인 레벨업 가이드 (Scott Rogers 'Level Up!' 번역서)](https://m.hanbit.co.kr/media/books/book_view.html?p_code=B9086837682) — KR · 책 · 캐릭터·레벨·기획문서·전투 전반.
- [Vertical Slice란 (Tono)](https://tonogameconsultants.com/vertical-slice/) — EN · 글 · '완성된 한 조각'의 정의와 예시.
- [Prototype / Vertical Slice / MVP / Demo 차이 (Ask a Game Dev)](https://www.tumblr.com/askagamedev/746300998961741824/game-dev-glossary-prototype-vertical-slice) — EN · 글 · 현직자의 용어 구분.
- [Scope Creep 피하기 (Wayline)](https://www.wayline.io/blog/scope-creep-indie-games-avoiding-development-hell) — EN · 글 · 인디 망하는 스코프 관리 실패와 회피.

---

## 3. 게임 디자인 & 게임 이론 (game feel · juice) 🌿

### YouTube — 채널
- [Game Maker's Toolkit (Mark Brown)](https://www.youtube.com/@GMTK) — EN · 입문~중급 · 게임 디자인 영상 에세이의 표준.
- [Snoman Gaming](https://www.youtube.com/channel/UCmY2tPu6TZMqHHNPj2QPwUQ) — EN · 입문 · Good/Bad Game Design 사례 분석.
- [Game Endeavor](https://www.youtube.com/@GameEndeavor) — EN · 입문 · Godot 기반 실전 디자인 팁.
- [Extra Credits — Game Design 재생목록](https://www.youtube.com/playlist?list=PLhyKYa0YJ_5BkTruCmaBBZ8z6cP9KzPiX) — EN · 입문 · 메커니즘·심리·원리 개괄.

### YouTube — 꼭 볼 영상 (점프감/juice)
- [Why Does Celeste Feel So Good to Play? (GMTK)](https://www.youtube.com/watch?v=yorTG9at90g) — EN · 입문~중급 · 코요테 타임·점프 버퍼 등 점프감 트릭. **플랫포머 필수.**
- [Secrets of Game Feel and Juice (GMTK)](https://www.youtube.com/watch?v=216_5nu4aVQ) — EN · 입문 · game feel/juice 개념 출발점.
- [The Art of Screenshake — Vlambeer](https://www.youtube.com/watch?v=AJdEqssNZ-U) — EN · 입문~중급 · 평범한 프로토타입을 30가지 기법으로 재미있게.
- [Juice it or lose it (GDC)](https://www.youtube.com/watch?v=Fy0aCDmgnxg) — EN · 입문 · 벽돌깨기를 라이브로 juicy하게.
- [Platformer Toolkit (GMTK, 플레이형 에세이)](https://gmtk.itch.io/platformer-toolkit) — EN · 입문 · 점프 변수 30여 개를 직접 만지며 체감.

### 책
- [The Art of Game Design (Jesse Schell)](https://www.amazon.com/Art-Game-Design-Lenses-Third/dp/1138632058) — EN · 입문~심화 · 100여 '렌즈'의 교과서. [한국어판(에이콘)](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=7384934).
- 『라프 코스터의 재미이론』 (A Theory of Fun) — KR · 입문 · "재미=학습", 얇고 강력. ([원서 사이트](https://www.theoryoffun.com/))
- [Game Feel (Steve Swink)](https://www.routledge.com/Game-Feel-A-Game-Designers-Guide-to-Virtual-Sensation/Swink/p/book/9780123743282) — EN · 중급~심화 · 조작감을 학문적으로 해부.
- [게임 디자인 원론 (Rules of Play 번역서)](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=45352952) — KR · 심화 · 규칙·플레이·문화 고전.

### 글
- [Game Feel 입문 가이드](https://gamedesignskills.com/game-design/game-feel/) — EN · 입문.
- [Platformer 디자인 기초](https://gamedesignskills.com/game-design/platformer/) — EN · 입문 · 플랫포머 핵심 메커니즘.
- [Platformer Toolkit Devlog — 점프 구현 해설 (GMTK)](https://gmtk.itch.io/platformer-toolkit/devlog/395523/behind-the-code) — EN · 중급 · 가속·점프 아크·코요테 타임 코드.

---

## 4. 레벨 디자인 🌿

- [Super Mario 3D World's 4 Step Level Design (GMTK)](https://www.youtube.com/watch?v=dBmIkEvEBtA) — EN · 영상 · 닌텐도 키쇼텐케츠 4단계 구조. **레벨 디자인 입문 필수.**
- [How to Make a Good 2D Camera (GMTK)](https://www.youtube.com/watch?v=TdWFzpgnljs) — EN · 영상 · 2D 카메라가 페이싱·가독성에 미치는 영향. ([글](https://gmtk.substack.com/p/how-to-make-a-good-2d-camera))
- [GMTK 'Level Design' 재생목록](https://www.youtube.com/playlist?list=PLc38fcMFcV_t6cVUpPXYnooVe1r_C0_4f) — EN · 영상 · 레벨/월드/퍼즐 설계 모음.
- [GMTK 'Boss Keys' 재생목록](https://www.youtube.com/playlist?list=PLc38fcMFcV_ul4D6OChdWhsNsYY3NA5B2) — EN · 영상 · 비선형 레벨·던전 구조 분석.
- [How to Design 2D Platformer Levels (Tadeas Jun)](https://www.tadeasjun.com/blog/2d-level-design/) — EN · 글 · teach → test → challenge 모델.
- [Platformer Level Design Tips (RetroStyle)](https://retrostylegames.com/blog/platformer-level-design-tips/) — EN · 글 · 난이도 곡선·페이싱 실무 팁.
- [What Makes Celeste's Assist Mode Special (GMTK)](https://www.youtube.com/watch?v=NInNVEHj_G4) — EN · 영상 · 난이도와 접근성 양립.

---

## 5. 게임 QA / 플레이테스트 🌿

- [Game Testing 101 — Beginner's Guide](https://www.softwaretestingmaterial.com/game-testing/) — EN · 글 · 게임 테스트가 무엇이고 어떤 종류인지.
- [Complete Game Testing & QA Guide](https://generalistprogrammer.com/game-testing-qa) — EN · 글 · 직무·도구(JIRA/TestRail)·베스트 프랙티스.
- [How to Write an Effective Bug Report (BrowserStack)](https://www.browserstack.com/guide/how-to-write-a-bug-report) — EN · 글 · 표준 버그 리포트 양식.
- [The Art of Bug Reporting in Game Testing (KiwiQA)](https://www.kiwiqa.com/art-of-bug-reporting-in-game-testing-tips-and-tricks/) — EN · 글 · 게임 특화 재현·증거.
- [How to Conduct Game Playtesting (Wayline)](https://www.wayline.io/blog/how-to-conduct-game-playtesting-feedback-improvement) — EN · 글 · 플레이테스트 진행 절차.
- [Jesse Schell's Six Questions for Playtesting](https://untoldplay.medium.com/jesse-schells-six-questions-for-playtesting-679a5fb9340b) — EN · 글 · 플레이테스트 6대 질문.
- [초기 스타트업의 첫 QA 프로세스 구축기](https://wooree-kwon.medium.com/초기-스타트업의-첫-qa프로세스-구축기-b26e93e67e37) — KR · 글 · 소규모 팀 QA 도입 경험담.
- [게임 LQA 테스터란 (brunch)](https://brunch.co.kr/@soossie/4) — KR · 글 · 한국 게임 QA 직무 현장.

---

## 6. 퍼블리싱 & 인디 출시 (★ 최종 목표) 🌿

- [Your first itch.io page (공식)](https://itch.io/docs/creators/getting-started) — EN · 글 · itch.io 페이지 만들기 공식 가이드.
- [itch.io for developers](https://itch.io/developers) — EN · 글 · 업로드·가격·판매 개요.
- [내가 만든 게임을 itch.io에 업로드하기](https://until.blog/@sin0105/내가-만든-게임을-itch-io에-업로드-하기) — KR · 글 · 한국어 itch.io 업로드 절차.
- [How to Publish on Steam, Epic, and itch.io](https://gamedesigning.org/gaming/how-to-publish-your-indie-game-on-steam-epic-and-itch-io/) — EN · 글 · 플랫폼별 비교·절차.
- [Self-Publish on Steam and itch.io: Launch Checklist](https://respawn.outlookindia.com/gaming/gaming-guides/self-publishing-a-video-game-solo-dev-small-team-guide) — EN · 글 · 솔로/소규모 출시 체크리스트.
- [스팀에 인디게임을 등록하는 절차 (인디터)](https://inditor.co.kr/bbs/board.php?bo_table=str&wr_id=24) — KR · 글 · 개발사 등록 + 게임 등록 + $100 절차.
- [스팀 게임 출시 하는 법 (mangveloper)](https://mangveloper.com/entry/스팀-게임-출시-하는-법) — KR · 글 · 한국어 스팀 출시 흐름.
- [itch.io — 나무위키](https://namu.wiki/w/itch.io) — KR · 글 · 플랫폼 개요·수수료 정책.

> 통념: **itch.io에 먼저 무료/데모로 올려 피드백 → 다듬어 Steam 정식 출시**. Steam은 게임당 $100(Steam Direct), 심사 1~5영업일, 위시리스트 확보 위해 'Coming Soon'을 2~6개월 전 오픈. Steam Next Fest(데모 행사) 활용 권장.
