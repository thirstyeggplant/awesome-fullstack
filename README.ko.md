# awesome-fullstack [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<!-- lang-bar -->
🔗 **웹사이트:** [https://thirstyeggplant.github.io/awesome-fullstack/ko/](https://thirstyeggplant.github.io/awesome-fullstack/ko/)

🌐 [English](README.md) · [简体中文](README.zh-CN.md) · [Español](README.es.md) · [日本語](README.ja.md) · **한국어** · [Português (BR)](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [हिन्दी](README.hi.md) · [বাংলা](README.bn.md) · [Bahasa Indonesia](README.id.md) · [العربية](README.ar.md)
<!-- /lang-bar -->

<sub>영어판을 번역한 문서입니다. 도구와 사이트 이름은 원문 그대로 두었습니다.</sub>

> 풀스택이 되는 방법에 대한 큐레이션 목록

**추천:** [Aubergine](https://github.com/thirstyeggplant/aubergine) - 브라우저의 캔버스 하나에 모든 터미널을. 여러 코딩 에이전트(Claude Code, Codex, Cursor, 일반 셸)를 나란히 실행하고, 어떤 에이전트가 당신을 기다리는지, 각각 어느 단계에 있는지, 무엇을 작성했는지 한눈에 확인하세요. 당신의 컴퓨터에서 실행됩니다.

프론트엔드, 중간 계층, 백엔드, 알고리즘, 지속적 전달을 배우세요. 참고:
Stack Overflow에서 아무 태그나 클릭한 뒤 info 탭을 열면 해당 태그에 대한 리소스를 찾을 수 있습니다.

<a id="what-to-learn"></a>
# 배울 것
0. [트렌드](https://github.com/whatwhatgoose/trending/issues)
1. [프론트엔드](#front-end-tier)
2. [중간 계층 (서버)](#middle-tier)
3. [백엔드 계층 (데이터베이스)](#back-end-tier-database)
4. [DevOps, 제품 관리, 배포 등](#dev-ops-continuous-deliveryintegrationdeployment)
5. [알고리즘, AI, 머신러닝](#algorithms-and-data-structures)
6. [AI 기반 개발](#ai-assisted-development)
7. [커뮤니티](#community)
8. [오픈 소스](#open-sourcing)
9. [면접 준비](#interview-preparation)
10. [채용](#jobs)
11. [기타](#other)
12. [학습 경로](#learning-paths)
13. [YouTube 동영상](https://news.ycombinator.com/item?id=12702651)


<a id="license"></a>
## 라이선스

MIT

<a id="contribute"></a>
## 기여하기

> 기여를 환영합니다! 풀 리퀘스트를 보내 주세요!
  - **첫 풀 리퀘스트를 준비 중인가요?** 이 *무료* 시리즈에서 방법을 배울 수 있습니다 [GitHub에서 오픈 소스 프로젝트에 기여하는 방법](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

<a id="front-end-tier"></a>
# 프론트엔드 계층
> 사람들이 보는 부분: 사용자 인터페이스 / 사용자 경험 / 클라이언트 / 디자인 / 게임 / 모바일 / TV / 하드웨어
[프론트엔드 개발자 핸드북](https://frontendmasters.gitbooks.io/front-end-handbook/content/index.html)

1. **HTML**
  - [Intro](#html-intro)
2. **CSS**
  1. [Intro](#css-intro)
  2. [Animations](https://robots.thoughtbot.com/css-animation-for-beginners)
    - [초보자를 위한 CSS 애니메이션 (YouTube)](https://www.youtube.com/watch?v=D9YQBaDBJ88)
    - [display를 얼마나 알고 있나요](https://www.chenhuijing.com/blog/how-well-do-you-know-display/)
  3. [모던 CSS](https://web.dev/learn/css)
    - [Tailwind CSS](https://tailwindcss.com/)
    - [Modern CSS Solutions](https://moderncss.dev/)
    - [CSS Grid Guide (Josh Comeau)](https://www.joshwcomeau.com/css/interactive-guide-to-grid/)
3. **Javascript**
  1. [Intro](#js-intro)
  2. [Jquery](#jquery-intro)
  3. [JS 중급](#js-intermediate)
  4. [Awesome JS](#awesome-js-list)
  5. [TypeScript](https://www.typescriptlang.org/docs/handbook/intro.html)
    - [Total TypeScript](https://www.totaltypescript.com/)
    - [Type Challenges](https://github.com/type-challenges/type-challenges)
    - [javascript.info](https://javascript.info/)
4. **클라이언트 개발 (웹)**
  - MVC 계열 프레임워크
      - [React](#react)
        - [Redux](#redux)
        - [Learn Relay](https://learnrelay.org/)
        - [React docs](https://react.dev/)
        - [Next.js](https://nextjs.org/)
        - [React Router](https://reactrouter.com/)
        - [TanStack (Query, Router, Table, Start)](https://tanstack.com/)
      - [Vue](https://vuejs.org/) + [Nuxt](https://nuxt.com/)
      - [Svelte + SvelteKit](https://svelte.dev/)
      - [Angular](https://angular.dev/)
      - [Astro](https://astro.build/)
      - [SolidJS](https://www.solidjs.com/)
      - [htmx](https://htmx.org/)
      - Legacy: [AngularJS (end of life)](https://github.com/gianarb/awesome-angularjs)
      - [Backbone](https://github.com/sadcitizen/awesome-backbone)
      - [Ember](https://github.com/nmec/awesome-ember)
      - [Mithril](https://github.com/lhorie/mithril)
  - 빌드 도구
      - [Vite](https://vite.dev/)
      - [esbuild](https://esbuild.github.io/)
      - [Rspack](https://rspack.dev/)
      - [Turborepo](https://turborepo.com/)
      - [pnpm](https://pnpm.io/)
      - [Biome](https://biomejs.dev/) - 빠른 포매터 및 린터
      - [Webpack](https://webpack.js.org/)
      - [Browserify](http://browserify.org/)
      - [Gulp](https://github.com/alferov/awesome-gulp)
      - [Grunt](http://gruntjs.com/)
  - 웹 앱 (도구 / 라이브러리 / 프레임워크)
    1. CSS / 스타일시트 언어
      - [Inline Styles](https://github.com/erikras/react-redux-universal-hot-example/blob/master/docs/InlineStyles.md)
      - [Sass](http://sass-lang.com/)
      - [Less](http://lesscss.org/)
    2. 웹 프레임워크
      - [Materialize](http://materializecss.com/)
      - [Bootstrap](https://getbootstrap.com/)
      - [shadcn/ui](https://ui.shadcn.com/)
      - [Radix UI](https://www.radix-ui.com/)
      - [Google Material Design Lite](https://getmdl.io/)
      - [Foundation](http://foundation.zurb.com/)
  - 테스트
      - [Playwright](https://playwright.dev/)
      - [Vitest](https://vitest.dev/)
      - [Testing Library](https://testing-library.com/)
      - [Cypress](https://www.cypress.io/)
      - [Storybook](https://storybook.js.org/)
      - [Selenium](https://www.selenium.dev/)
      - [Jest](https://jestjs.io/)
      - [Mocha](https://mochajs.org/)
      - [Jasmine](https://jasmine.github.io/)
      - [Chai](https://www.chaijs.com/)
      - [Sinon](https://sinonjs.org/)
  - 도구
      - [Google Analytics](https://marketingplatform.google.com/about/analytics/)
      - [PostHog](https://posthog.com/) - 오픈 소스 제품 분석, 세션 리플레이, 기능 플래그
      - [Plausible](https://plausible.io/) - 개인정보를 존중하는 분석 도구
      - [Lighthouse](https://developer.chrome.com/docs/lighthouse/)
      - [Crazy Egg](https://www.crazyegg.com/)
      - [Sumo Me](https://sumome.com/app/heat-maps)
  - 체크리스트
      - [Web Checklist](http://webdevchecklist.com/), [Github](https://github.com/ligershark/webdevchecklist.com)
      - [Landing Page Checklist](http://unbounce.com/landing-pages/checklist/)
      - [Website Laung Checklist](https://news.ycombinator.com/item?id=9522885)
      - [Web Components](https://github.com/webcomponents/gold-standard/wiki)
      - [Web checklist](http://tryblocks.com/departure/index.html)
5. **디자인, 카피라이팅, SEO, 최적화**
  - [Awesome Design, UI/UX](https://github.com/thirstyeggplant/awesome-ui)
  - [Design Resources in HH Design](https://medium.com/hh-design/design-resources-5071be5f2e43)
  - [Optimization](https://github.com/davidsonfellipe/awesome-wpo)
  - [Core Web Vitals](https://web.dev/articles/vitals)
  - [Search Engine Optimization](https://github.com/marcobiedermann/search-engine-optimization)
  - [Web Components the right way](https://github.com/mateusortiz/webcomponents-the-right-way)
6. **모바일**
  1. [Android](https://github.com/JStumpp/awesome-android)
  2. [Ios Swift](https://github.com/matteocrippa/awesome-swift) OR [awesome ios](https://github.com/vsouza/awesome-ios)
  3. [Windows](https://developer.microsoft.com/en-us/windows)
  5. [Native Script](https://www.nativescript.org/)
  6. [React Native](#react-native)
  7. [Expo](https://expo.dev/)
  8. [Flutter](https://flutter.dev/)
  9. [SwiftUI](https://developer.apple.com/xcode/swiftui/)
  10. [Jetpack Compose](https://developer.android.com/compose)
  11. [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html)
7. **게임**
  0. [Amit's Gaming Programming Information](http://www-cs-students.stanford.edu/~amitp/gameprog.html)
  1. [Unity](https://unity3d.com/)
  2. [Unreal Engine](https://www.unrealengine.com/)
  3. [GameMaker](http://www.yoyogames.com/gamemaker)
  4. [Construct2](https://www.scirra.com/construct2)
  5. [Playmaker](http://www.hutonggames.com/showcase.html)
  6. [Stencyl](http://www.stencyl.com/)
  7. [Godot](https://godotengine.org/)
  8. [Amazon Lumberyard](http://aws.amazon.com/lumberyard/)
  9. [2D resources](https://www.reddit.com/r/Unity2D/comments/3dfi5k/lets_create_a_list_of_all_100_free_2d_assets_with/)
  10. [2D unity rpg tutorial](https://www.youtube.com/watch?v=NNpLsimyu3I&index=1&list=PL_4rJ_acBNMH3SExL3yIOzaqj5IP5CJLC)
8. **IoT**
  1. [Arduino](https://github.com/Lembed/Awesome-arduino)
  2. [Raspberry Pi](https://github.com/blackout314/awesome-raspberry-pi)
9. [**Embedded**](http://www.instructables.com/tag/type-id/category-technology/)
10. 데스크톱
  1. [Awesome Electron](https://github.com/sindresorhus/awesome-electron)
  2. [Tauri](https://tauri.app/) - 웹 프론트엔드로 만드는 작고 빠른 데스크톱·모바일 앱


<a id="middle-tier"></a>
# 중간 계층
>클라이언트와 데이터베이스 사이에서 통신하는 부분

1. [**언어별 웹 서버**](#server-side)
  - [GraphQL](https://graphql.org/learn/)
  - [C](https://github.com/kozross/awesome-c)
  - [C++](https://github.com/fffaraz/awesome-cpp)
  - [C# / Dotnet](https://github.com/quozd/awesome-dotnet)
  - [Elixir/Erlang](http://www.phoenixframework.org/docs/learning-elixir-and-erlang)
  - [Go](#go-server)
  - [Java](https://github.com/akullpp/awesome-java)
  - [Javascript](#javascript-server)
  - [PHP](https://github.com/ziadoz/awesome-php)
  - [Python](https://github.com/vinta/awesome-python)
    - [FastAPI](https://fastapi.tiangolo.com/)
    - [Django](https://www.djangoproject.com/)
  - [Ruby](#ruby)
  - [Rust](https://github.com/rust-unofficial/awesome-rust)
    - [The Rust Book](https://doc.rust-lang.org/book/)
    - [Axum](https://github.com/tokio-rs/axum)
  - [Scala](https://github.com/lauris/awesome-scala)

2. [**네트워킹**](#networking)
3. **API / RESTful Service**
  - [Awesome REST](https://github.com/marmelab/awesome-rest)
  - [Awesome API](https://github.com/Kikobeats/awesome-api)
  - [HTTP API Design Guide](https://geemus.gitbooks.io/http-api-design/content/en/index.html)
  - [OpenAPI](https://www.openapis.org/)
  - [tRPC](https://trpc.io/) - 엔드투엔드 타입 안전 API
  - [gRPC](https://grpc.io/)
  - [Zod](https://zod.dev/) - TypeScript 우선 스키마 검증
4. [**서버리스**](#serverless)
  - [Cloudflare Workers](https://workers.cloudflare.com/)
  - [AWS Lambda](https://aws.amazon.com/lambda/)
  - [Vercel Functions](https://vercel.com/docs/functions)
5. [**커맨드 라인**](#command-line)
6. **Hosting**
  - [Vercel](https://vercel.com/)
  - [Netlify](https://www.netlify.com/)
  - [Cloudflare Pages](https://pages.cloudflare.com/)
  - [Fly.io](https://fly.io/)
  - [Render](https://render.com/)
  - [Railway](https://railway.com/)
7. [**마이크로서비스**](https://github.com/mfornos/awesome-microservices)
8. [테스트](http://stackoverflow.com/questions/520064/what-is-unit-test-integration-test-smoke-test-regression-test)
  1. [단위 테스트](#unit-testing)
  2. [통합 테스트 / 기능 테스트](#integration-testing)
  3. [스모크 테스트 (기본 점검)](#smoke-testing)
  4. [회귀 테스트](#regression-testing)
  5. [인수 테스트](#acceptance-testing)
  6. [시스템 테스트](#systems-testing)
  7. [플래그 테스트](#flagging-test)
  8. [E2E 테스트](#end-to-end-testing)
  9. [블로그](http://googletesting.blogspot.ca/2015/04/just-say-no-to-more-end-to-end-tests.html)
9. [**OWASP**](https://owasp.org/)
  - [OWASP Top 10](https://owasp.org/www-project-top-ten/)
  - Auth: [Auth.js](https://authjs.dev/), [Better Auth](https://www.better-auth.com/), [Clerk](https://clerk.com/), [Keycloak](https://www.keycloak.org/)
  - [Passkeys (passkeys.dev)](https://passkeys.dev/)
10. [**DevOps / 환경 / 지속적 통합**](#dev-ops-continuous-deliveryintegrationdeployment)
11. **도구**
  - [Postman](https://www.postman.com/)
  - [Bruno](https://www.usebruno.com/) - 오픈 소스이며 git 친화적인 API 클라이언트
  - [HTTPie](https://httpie.io/)
  - [Wire shark](https://www.wireshark.org/)
12. **구성 관리 / 서버 관리**
  - [Salt](https://saltstack.com/)
  - [Puppet](https://puppet.com/)
  - [Chef](https://www.chef.io/)
  - [Ansible](https://www.ansible.com/)
  - [Docker](https://github.com/veggiemonk/awesome-docker)
  - [Kubernetes](https://kubernetes.io/)
  - [Docker Compose](https://docs.docker.com/compose/)
13. [**플랫폼**](#platforms)
  - PAAS
    - [AWS](https://github.com/donnemartin/awesome-aws)
    - [Heroku](https://www.heroku.com/)
    - [Google Cloud Run](https://cloud.google.com/run)
    - [Google Cloud App Engine](https://cloud.google.com/appengine/docs)
  - IAAS
    - [Digital Ocean](https://www.digitalocean.com/)
    - [Open Shift](https://www.openshift.com/)
    - [GCE](https://cloud.google.com/compute/)
    - [AWS](http://aws.amazon.com/)
  - BAAS
    - [Firebase](https://firebase.google.com/)
    - [Supabase](https://supabase.com/)
    - [Convex](https://www.convex.dev/)
    - [Appwrite](https://appwrite.io/)
    - [pusher](https://pusher.com/)
    - [pubnub](https://www.pubnub.com/)
  - [Self Hosting](https://github.com/Kickball/awesome-selfhosted)
14. **체크리스트**
  - [체크리스트](https://securitychecklist.org/)
  - [Linux](https://github.com/lfit/itpol/blob/master/linux-workstation-security.md)

<a id="back-end-tier-database"></a>
# 백엔드 계층 (데이터베이스)
>데이터를 저장하고 조회하는 부분

1. [**SQL**](#sql)
2. [**NoSQL**](#nosql)
3. [**NewSQL**](https://en.wikipedia.org/wiki/NewSQL)
  - 관리형 Postgres / SQLite: [Neon](https://neon.com/), [PlanetScale](https://planetscale.com/), [Turso](https://turso.tech/), [Supabase](https://supabase.com/)
4. **ORM / 쿼리 빌더**
  - [Drizzle ORM](https://orm.drizzle.team/)
  - [Prisma](https://www.prisma.io/)
  - [SQLAlchemy](https://www.sqlalchemy.org/)
5. **캐싱**
  - [Redis](https://redis.io/)
  - [Valkey](https://valkey.io/)
6. **검색**
  - [Meilisearch](https://www.meilisearch.com/)
  - [Typesense](https://typesense.org/)
  - [OpenSearch](https://opensearch.org/)
7. **벡터 데이터베이스**
  - [pgvector](https://github.com/pgvector/pgvector)
  - [Qdrant](https://qdrant.tech/)
8. [**데이터셋**](https://github.com/caesar0301/awesome-public-datasets)
9. [**데이터 마이닝**](http://guidetodatamining.com/)

<a id="distributed-systems"></a>
# 분산 시스템
> 기초: CAP 정리, FLP 불가능성 정리, 바이모달 멀티캐스트, Raft / Paxos, 램포트 시계

- [MIT 6.5840 (formerly 6.824)](https://pdos.csail.mit.edu/6.824/)
- [Designing Data-Intensive Applications](https://dataintensive.net/)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Ed X](https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x)
- [Washington CSE 452](https://courses.cs.washington.edu/courses/cse452/16wi/calendar/lecturelist.html)


<a id="dev-ops-continuous-deliveryintegrationdeployment"></a>
# DevOps, 지속적 전달 / 통합 / 배포
> 소프트웨어 배포를 위한 협업 방식
- [Awesome Distributed Systems](https://github.com/theanalyst/awesome-distributed-systems)
- [DevOps](#dev-ops)
- 지속적 통합
- 지속적 전달
- 지속적 배포
- 기능 토글
- 아티팩트
- 롤백
- **도구**
  1. [GitHub Actions](https://github.com/features/actions)
  2. [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
  3. [Jenkins](https://www.jenkins.io/)
  4. [Vagrant](https://www.vagrantup.com/)
  5. [Docker](https://github.com/veggiemonk/awesome-docker)
  6. [Dev Containers](https://containers.dev/)
- **클러스터 관리 / 컨테이너 / 인프라**
  1. [Kubernetes](http://kubernetes.io/)
  2. Docker + Vagrant
  3. [Terraform](https://www.terraform.io/) / [OpenTofu](https://opentofu.org/)
  4. [Pulumi](https://www.pulumi.com/)
  5. [Podman](https://podman.io/)
- **관측 가능성**
  1. [OpenTelemetry](https://opentelemetry.io/)
  2. [Grafana](https://grafana.com/)
  3. [Sentry](https://sentry.io/)



<a id="software-product-management"></a>
# 소프트웨어 제품 관리
> 제품이나 기능 출시를 위한 작업을 관리하는 과정

- [Agile Manifesto](http://agilemethodology.org/)
- [소프트웨어 개발 프로세스](https://en.wikipedia.org/wiki/Software_development_process)
- [소프트웨어 요구사항 명세](https://en.wikipedia.org/wiki/Software_requirements_specification)
- [소프트웨어 요구사항](http://www.tutorialspoint.com/software_engineering/software_requirements.htm)
- [Joel Test: 더 나은 코드를 위한 12단계](http://www.joelonsoftware.com/articles/fog0000000043.html)
- [코드 리뷰](https://github.com/thoughtbot/guides/tree/master/code-review)

<a id="algorithms-and-data-structures"></a>
# 알고리즘과 자료구조
> 알고리즘, 데이터 과학, AI, 머신러닝

- [데이터 과학의 기초](https://news.ycombinator.com/item?id=12659141)
- [Better Explained](http://betterexplained.com/)
- [MIT ALgorithms](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)
- [Hacker Rank](https://www.hackerrank.com/domains)
- [Topcoder](https://www.topcoder.com/)
- [Coursera Stanford](https://www.coursera.org/course/algo)
- [Coursera Princeton](https://www.coursera.org/course/algs4partI)
- [Erik Demaine Classes](http://erikdemaine.org/classes/)
- [Udacity](https://www.udacity.com/course/intro-to-algorithms--cs215)
- [OEDB list](http://oedb.org/open/search-results/?search-term=algorithm)
- [ACM introduction to programming contest stanford](http://web.stanford.edu/class/cs97si/)
- [경쟁 프로그래밍 강좌](https://algo.is/t-414-aflv-competitive-programming-course-2016/)

<a id="machine-learning-and-ai"></a>
## 머신러닝과 AI

- [인공지능 강의 동영상](https://news.ycombinator.com/item?id=12667761)
- [무료 머신러닝 도서](https://hackerlists.com/free-machine-learning-books/)
- [Awesome ML](https://github.com/josephmisiti/awesome-machine-learning)
- [Andrew Ng Coursera](https://www.coursera.org/learn/machine-learning)
- [Awesome AI courses](https://github.com/prakhar1989/awesome-courses#artificial-intelligence)
- [Berkeley Intro to AI](http://ai.berkeley.edu/lecture_videos.html)
- [Berkeley Intro to AI 2015 version](https://www.youtube.com/playlist?list=PL-XXv-cvA_iA4YSaTMfF_K_wvrKAY2H8u)
- [Berkeley Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/)
- [Udacity Intro To ML](https://www.udacity.com/course/intro-to-machine-learning--ud120)
- [MIT 6.034](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/lecture-videos/)
- [Neural Networks & Deep Learning](http://neuralnetworksanddeeplearning.com/index.html)
- [Data Sets](https://github.com/caesar0301/awesome-public-datasets)
- [Open AI Generative Models](https://openai.com/blog/generative-models/)
- [Machine learning books by r/MachineLearning](https://www.reddit.com/r/MachineLearning/comments/1jeawf/machine_learning_books/)
- [Machine learning by r/MachineLearning/wiki/index](https://www.reddit.com/r/MachineLearning/wiki/index)
- [CMU ML course](http://www.cs.cmu.edu/~awm/10701/)
- [통계적 학습 이론](http://people.eecs.berkeley.edu/~jordan/courses/281A-fall07/)
- [Berkeley ML](http://inst.eecs.berkeley.edu/~cs188/sp08/lectures.html)
- [통계적 학습 이론](http://people.eecs.berkeley.edu/~jordan/courses/281A-fall07/)
- [Stanford 229](http://cs229.stanford.edu/)

<a id="deep-learning-ish"></a>
## 딥러닝 관련
>[Skills to for machine learning by OpenAI CTO, Greg Brockman](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer/answer/Greg-Brockman?srid=cgo&share=d1ac0da2)

- [머신러닝은 재미있다](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.runmpceje)
- [Deep Learning Book](https://github.com/HFTrader/DeepLearningBook)
- [딥러닝 시작하는 법](http://ofir.io/How-to-Start-Learning-Deep-Learning/)
- [Hello Tensor Flow](https://www.oreilly.com/learning/hello-tensorflow)
- [MIT deep learning press book](http://www.deeplearningbook.org/)
- [강화학습 입문](https://webdocs.cs.ualberta.ca/~sutton/book/ebook/the-book.html)
- [Reinforcement Learning at georgia tech](https://www.udacity.com/course/reinforcement-learning--ud600)


<a id="other-domains-in-cs"></a>
## 컴퓨터 과학의 다른 분야
- [통계학 독학](https://news.ycombinator.com/item?id=12703032)
- [과학 계산용 Python 치트 시트](https://ipgp.github.io/scientific_python_cheat_sheet/)
- [Nengo: 대규모 뇌 모델 시뮬레이션](https://github.com/nengo/nengo)
- [해커를 위한 통계학](https://www.youtube.com/watch?v=L5GVOFAYi8k)
- [고통 없는 통계학](https://www.youtube.com/watch?v=5Dnw46eC-0o&feature=youtu.be)


<a id="ai-assisted-development"></a>
# AI 기반 개발
> 코딩 에이전트, LLM API와 관련 도구

- **에이전트 실행 및 관리**
  - [Aubergine](https://github.com/thirstyeggplant/aubergine) - 브라우저의 캔버스 하나에서 여러 코딩 에이전트를 나란히 실행
- **코딩 에이전트 및 어시스턴트**
  - [Claude Code](https://www.anthropic.com/claude-code)
  - [OpenAI Codex](https://openai.com/codex/)
  - [GitHub Copilot](https://github.com/features/copilot)
  - [Cursor](https://cursor.com/)
  - [Aider](https://aider.chat/)
- **LLM으로 만들기**
  - [Model Context Protocol](https://modelcontextprotocol.io/) - 모델을 도구와 데이터에 연결하는 개방형 표준
  - [Anthropic Docs](https://docs.claude.com/)
  - [OpenAI Platform Docs](https://platform.openai.com/docs)
  - [Vercel AI SDK](https://ai-sdk.dev/)
  - [LangChain](https://www.langchain.com/)
  - [Hugging Face](https://huggingface.co/)
  - [Ollama](https://ollama.com/) - 오픈 모델을 로컬에서 실행
- **배우기**
  - [Neural Networks: Zero to Hero (Andrej Karpathy)](https://karpathy.ai/zero-to-hero.html)
  - [fast.ai](https://course.fast.ai/)
  - [Hugging Face Learn](https://huggingface.co/learn)

<a id="paradigms"></a>
# 패러다임
> [프로그래밍 패러다임](https://en.wikipedia.org/wiki/Programming_paradigm)

<a id="community"></a>
# 커뮤니티
> 같은 관심사를 가진 사람들 찾기

1. [Stackoverflow](http://stackoverflow.com)
2. [HN](http://news.ycombinator.com)
3. [Reddit](http://reddit.com/r/programming)

<a id="html-intro"></a>
# HTML 입문
- [Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css)
- [Free Code Camp](https://www.freecodecamp.com/challenges/say-hello-to-html-elements)
- [Code Academy](https://www.codecademy.com/learn/web)
- [Shayhowe](http://learn.shayhowe.com/html-css/building-your-first-web-page/)
- [W3C HTML5 Tutorial](http://www.w3schools.com/html/)
- [Mozilla](https://developer.mozilla.org/en-US/Learn/HTML/Introduction_to_HTML/Getting_started)
- [Everything Html Head](https://github.com/joshbuchea/HEAD)

<a id="css-intro"></a>
# CSS 입문
- [Khan Academy](https://www.khanacademy.org/computing/hour-of-code/hour-of-html/p/css-basics)
- [Free Code Camp](https://www.freecodecamp.com/challenges/use-css-selectors-to-style-elements)
- [w3c](http://www.w3schools.com/css/)
- [Learn Layout](http://learnlayout.com/margin-auto.html)
- [Shayhowe](http://learn.shayhowe.com/html-css/getting-to-know-css/)
- [Egghead](https://egghead.io/technologies/css)
- [msdn](https://channel9.msdn.com/Series/JavaScript-Fundamentals-Development-for-Absolute-Beginners)
- [FlexBox](https://github.com/cjcenizal/flexbox-patterns)
- [Awesome FlexBox](https://github.com/afonsopacifer/awesome-flexbox)
- [Awesome CSS](https://github.com/sotayamashita/awesome-css)
- [Load Spinners](http://github.danielcardoso.net/load-awesome/animations.html)

<a id="js-intro"></a>
# JS 입문
- [Free Code Camp](https://www.freecodecamp.com/challenges/comment-your-javascript-code)
- [w3c](http://www.w3schools.com/js/)
- [codeacademy](https://www.codecademy.com/learn/javascript)
- [egghead](https://egghead.io/technologies/js)
- [Stackoverflow Resource](http://stackoverflow.com/tags/javascript/info)


<a id="jquery-intro"></a>
# jQuery 입문
- [Free code camp](https://www.freecodecamp.com/challenges/learn-how-script-tags-and-document-ready-work)

<a id="js-intermediate"></a>
# JS 중급
- [AirBNB: JS Style Guide](https://github.com/airbnb/javascript)
- [Reddit learnjs](https://www.reddit.com/r/learnjavascript/top/)
- [YDKSJS](https://github.com/getify/You-Dont-Know-JS)
- [Eloquent JS](http://eloquentjavascript.net/)
- [Codementor](https://www.codementor.io/learn-javascript-online)
- [ES6](https://github.com/ericdouglas/ES6-Learning)


<a id="awesome-js-list"></a>
# 멋진 JS 목록
- [Awesome JS:Browser](https://github.com/sorrycc/awesome-javascript)
- [Awesome JS:Learning Guide](https://github.com/wwsun/awesome-javascript)
- [Awesome Promises](https://github.com/wbinnssmith/awesome-promises)
- [Awesome Books](https://github.com/wbinnssmith/awesome-promises)

<a id="react"></a>
# React
- [awesome react](https://github.com/enaqx/awesome-react)

<a id="redux"></a>
# Redux
- [awesome redux](https://github.com/xgrommx/awesome-redux)


<a id="react-native"></a>
# React Native
- [Official](https://reactnative.dev/)
- [Awesome React Native](https://github.com/jondot/awesome-react-native)
- [리소스](http://www.reactnative.com/)
- [Egg Head](https://egghead.io/lessons/react-react-native-up-and-running?series=react-native-fundamentals)
- [JS coach](https://js.coach/react-native)

<a id="server-side"></a>
# 서버 사이드
> 여러 언어로 하는 서버 사이드 프로그래밍

<a id="server-erlang"></a>
# Server Erlang
- [Elixir/Erlang](http://www.phoenixframework.org/docs/learning-elixir-and-erlang)
- [StackOverflow Erlang](http://stackoverflow.com/tags/erlang/info)

<a id="go-server"></a>
# Go Server
- [A tour of Go](https://go.dev/tour/)
- [Go Wiki](https://github.com/golang/go/wiki/Learn)
- [Stack Overflow Go](http://stackoverflow.com/tags/go/info)
- [Awesome Go](https://github.com/avelino/awesome-go)
- [Awesome Go China](https://github.com/hyper-carrot/awesome-go-China)

<a id="javascript-server"></a>
# Javascript Server
- [Node School](http://nodeschool.io/)
- [Stackoverflow Resource](http://stackoverflow.com/tags/javascript/info)
- [LearnCode.Academy](https://www.youtube.com/watch?v=pU9Q6oiQNd0&list=PLoYCgNOIyGAACzU6GliHJDp4kmOw3NFsh)
- [Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node)
- [Tutorials Point](http://www.tutorialspoint.com/nodejs/)
- [Express](https://expressjs.com/)
- [Node.js Learn](https://nodejs.org/en/learn)
- [Deno](https://deno.com/)
- [Bun](https://bun.sh/)
- [Hono](https://hono.dev/)
- [Fastify](https://fastify.dev/)
- [NestJS](https://nestjs.com/)
- [Node/Sails/Socket.IO/Angular/Mongo](https://courses.platzi.com/courses/develop-apps-sails-js/)
- [node tuts](http://nodetuts.com/)
- [Airbnb style guide](https://github.com/airbnb/javascript)
- [node.Js best practices](https://github.com/alanjames1987/Node.js-Best-Practices)
- [awesome nodejs](https://github.com/sindresorhus/awesome-nodejs)


<a id="ruby"></a>
# Ruby
- [Ruby by dreikanter](https://github.com/dreikanter/ruby-bookmarks)
- [Ruby by markets](https://github.com/markets/awesome-ruby)
- [Ruby by Sdogruyol](https://github.com/Sdogruyol/awesome-ruby)
- [Awesome Rails](https://github.com/ekremkaraca/awesome-rails)
- [Stackoverflow Ruby Resources](http://stackoverflow.com/tags/ruby/info)


<a id="networking"></a>
# 네트워킹
- [Online Course: Computer Networking Playlist](https://www.youtube.com/watch?v=d4_7dUFl4v0&list=PLkHsKoi6eZnzJl1qTzmvBwTxrSJW4D2Jj)
- [Beej's Guide to Network Programming](http://beej.us/guide/bgnet/output/html/multipage/index.html)
- [LearnCode.Academy: 인터넷의 작동 원리](https://www.youtube.com/watch?v=e4S8zfLdLgQ)
- [Eli the computer guy on youtube: 네트워킹](https://www.youtube.com/playlist?list=PLF360ED1082F6F2A5)
- [danscourses: youtube channel](https://www.youtube.com/user/danscourses/featured)
- [Professor Messer](http://www.professormesser.com/network-plus/n10-005/free-network-plus/)
- [Professor Messer (Youtube)](https://www.youtube.com/channel/UCkefXKtInZ9PLsoGRtml2FQ)
- [Andrew Crouthamel (Youtube): CCNA/CNET](https://www.youtube.com/playlist?list=PLmdYg02XJt6QRQfYjyQcMPfS3mrSnFbRC)
- [Router Alley Guides](http://www.routeralley.com/guides.html)
- [Stanford](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about)
- [Warriors of the net: Video](https://www.youtube.com/watch?v=PBWhzz_Gn10)
- [Tuts +: HTTP](http://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
- [MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-829-computer-networks-fall-2002/index.htm)
- [Cheat SHeet](http://packetlife.net/library/cheat-sheets/)
- [서브네팅 연습](http://subnettingpractice.com/howto.html)
- [Reddit CCNA](https://www.reddit.com/r/ccna/)
- [쉽게 배우는 서브넷](https://docs.google.com/document/u/1/d/1O84JC1KnLFYUNo2CUYCtvEtJkkiM05uOATxaA1hlz6Y/mobilebasic?pli=1)
- [Cisco from scratch](http://ciscoiseasy.blogspot.ca/)
- [Cisco Learning Network](https://learningnetwork.cisco.com/welcome)
- [SDN: Software Defined Networking Coursera](https://www.coursera.org/course/sdn1)
- [클라우드 컴퓨팅](https://www.coursera.org/course/cloudcomputing)
- [클라우드 네트워킹](https://www.coursera.org/course/cloudnetworking)
- [Internet Emerging Tech](https://www.coursera.org/learn/internet-technologies)
- [GNS3 Academy](http://academy.gns3.com/)


<a id="dns"></a>
## DNS
- [DNS the good parts](https://www.petekeen.net/dns-the-good-parts)

<a id="computer-networking-and-security"></a>
## 컴퓨터 네트워크와 보안
- [Ryan Lindfield](https://www.youtube.com/user/ryan813/about)

<a id="command-line"></a>
# 커맨드 라인
- [운영체제별 명령어](http://ss64.com/)
- [Awesome command line](https://github.com/herrbischoff/awesome-osx-command-line)
- [Art of command line](https://github.com/jlevy/the-art-of-command-line)
- [Awesome OSX command line](https://github.com/herrbischoff/awesome-osx-command-line)
- [Data Science command line](http://datascienceatthecommandline.com/)
- [Fish](https://fishshell.com/)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [fzf](https://github.com/junegunn/fzf)
- [zoxide](https://github.com/ajeetdsouza/zoxide)
- [Starship prompt](https://starship.rs/)
- [tmux](https://github.com/tmux/tmux/wiki)
- [Ghostty](https://ghostty.org/)
- [Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

<a id="git"></a>
# Git
- [Git tips](https://github.com/git-tips/tips)
- [github desktop](https://desktop.github.com/)
- [GitHub CLI](https://cli.github.com/)
- [lazygit](https://github.com/jesseduffield/lazygit)
- [Oh Shit, Git!?!](https://ohshitgit.com/)
- [xhacker github extensions](https://github.com/xhacker/awesome-github-extensions)
- [stefan github extensions](https://github.com/stefanbuck/awesome-browser-extensions-for-github)
- [awesome tooling and resources in chrome devtools ecosystem](https://github.com/ChromeDevTools/awesome-chrome-devtools)

<a id="serverless"></a>
# 서버리스
- [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- [Cloudflare Workers](https://developers.cloudflare.com/workers/)
- [Serverless Framework](https://www.serverless.com/)

<a id="microservices"></a>
# 마이크로서비스
- [awesome microservices](https://github.com/mfornos/awesome-microservices)

<a id="unit-testing"></a>
# [단위 테스트](https://en.wikipedia.org/wiki/Unit_testing)
- [Martin Fowler](http://martinfowler.com/bliki/UnitTest.html)

<a id="integration-testing"></a>
# [통합 테스트](https://en.wikipedia.org/wiki/Integration_testing)

<a id="smoke-testing"></a>
# [스모크 테스트](https://en.wikipedia.org/wiki/Smoke_testing_(software))

<a id="regression-testing"></a>
# [회귀 테스트](https://en.wikipedia.org/wiki/Regression_testing)

<a id="acceptance-testing"></a>
# [인수 테스트](https://en.wikipedia.org/wiki/Acceptance_testing)

<a id="systems-testing"></a>
# [시스템 테스트](https://en.wikipedia.org/wiki/System_testing)

<a id="flagging-test"></a>
# [플래그 테스트](https://en.wikipedia.org/wiki/Feature_toggle)
> 기능 토글이라고도 함

<a id="end-to-end-testing"></a>
# [E2E 테스트](http://stackoverflow.com/questions/19378183/difference-between-system-testing-and-end-to-end-testing)



<a id="sql"></a>
# Sql
- [Awesome Sql](https://github.com/shlomi-noach/awesome-mysql/blob/gh-pages/index.md)
- [PostgreSQL Docs](https://www.postgresql.org/docs/)
- [SQLite](https://sqlite.org/)
- [Use The Index, Luke](https://use-the-index-luke.com/)
- [Setting Up SQL/ PostgreSQL](https://github.com/snowplow/snowplow/wiki/Setting-up-PostgreSQL)
- [Bostongis: Postgis](http://www.bostongis.com/)
- [Boundless geo: Postgis](http://workshops.boundlessgeo.com/suiteintro/postgis/index.html)
- [Archaeogeek: Postgis](http://www.archaeogeek.com/portable-gis.html)
- [Dublin Institute: Postgis](http://www.comp.dit.ie/pbrowne/Spatial%20Databases%20SDEV4005/Spatial%20Databases%20SDEV4005.htm)
- [osgeo posgis wiki: Postgis](http://trac.osgeo.org/postgis/wiki/UsersWikiTutorials)
- [Postgis in action: Postgis](https://www.manning.com/books/postgis-in-action-second-edition)

<a id="nosql"></a>
# NoSQL
- 데이터 모델링
  - [NoSql Data Modelling Techniques 2012](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)
- 실시간
  - [Awesome RethinkDB by analytik](https://github.com/analytik/awesome-rethinkdb)
  - [Awesome RethinkDB by d3viant0ne](https://github.com/d3viant0ne/awesome-rethinkdb)
- 문서형
- 키-값
- 메모리 / 캐싱
- 컬럼형

<a id="dev-ops"></a>
# DevOps
- [Amazon Web Services — a practical guide](https://github.com/open-guides/og-aws)
- [awesome continuous integration and delivery](https://github.com/ciandcd/awesome-ciandcd)
- [awesome sysadmin](https://github.com/kahun/awesome-sysadmin)
- [awesome microservice](https://github.com/mfornos/awesome-microservices)
- [Continuous Integration / Delivery / Dev Ops](https://github.com/ciandcd/awesome-ciandcd)
- [CD](https://blog.risingstack.com/continuous-deployment-of-node-js-applications/)

<a id="infrastructure"></a>
# 인프라
- [Sysadmincats](https://sysadmincasts.com/)
- [Bash Academy](http://www.bash.academy/)
- [Smart Bear](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)
- [Fog Creek](http://blog.fogcreek.com/effective-code-reviews-9-tips-from-a-converted-skeptic/)
- [Methods and Tools](http://www.methodsandtools.com/archive/archive.php?id=66)
- [Self Hosting](https://github.com/Kickball/awesome-selfhosted)

<a id="configuration-management"></a>
# 구성 관리
- [Docker](https://www.docker.com/what-docker)
  - [LearnCode.Academy: Docker](https://www.youtube.com/watch?v=pGYAg7TMmp0)
  - [Docker cheat sheet](https://github.com/wsargent/docker-cheat-sheet)


<a id="platforms"></a>
# 플랫폼
  - Iaas
    - [Awesome AWS](https://github.com/donnemartin/awesome-aws)
  - Paas
    - [App Engine](https://en.wikipedia.org/wiki/Google_App_Engine)
    - [AWS Elastic Beanstalk](http://aws.amazon.com/elasticbeanstalk/)
    - [Open Shift](https://en.wikipedia.org/wiki/OpenShift)
    - [Heroku](https://www.heroku.com/)
    - [Azure](https://azure.microsoft.com/en-us/services/app-service/web/)
  - BAAS
    - [Firebase](https://firebase.google.com/)
    - [Supabase](https://supabase.com/)
    - [Pubnub](https://www.pubnub.com/)
    - [Pusher](https://pusher.com/)
  - [Self Hosted](https://github.com/Kickball/awesome-selfhosted)


<a id="learning-paths"></a>
# 학습 경로
- [roadmap.sh](https://roadmap.sh/) - 프론트엔드, 백엔드, DevOps 등을 위한 단계별 로드맵
- [The Odin Project](https://www.theodinproject.com/)
- [Full Stack Open](https://fullstackopen.com/en/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- [MDN Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn_web_development)
- [web.dev Learn](https://web.dev/learn)
- [CS50](https://cs50.harvard.edu/x/)
- [Frontend Masters](https://frontendmasters.com/)

<a id="resource"></a>
# 리소스
> 기타 자료

- [Awesome courses](https://github.com/prakhar1989/awesome-courses#artificial-intelligence)
- [621+ Programming Resources](https://medium.com/free-stuff/2000-programming-resources-c2c835001216#.2cmo8h11l)
- [LearnCode.academy](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw)
- [freeCodeCamp](https://www.freecodecamp.org)
- [The Odin Project](https://www.theodinproject.com/)
- [Khan Academy](https://www.khanacademy.org/hourofcode)
- [W3 Schools](http://www.w3schools.com/)
- [Tuts +](http://tutsplus.com/)
- [Coursera](https://www.coursera.org/)
- [Udacity](https://www.udacity.com/)
- [Udemy](https://www.udemy.com/)
- [Codementor](https://www.codementor.io/learn/coding)

- [awesome x 3](https://github.com/t3chnoboy/awesome-awesome-awesome)
- [프론트엔드](https://github.com/micahgodbolt/front-end-architecture)
- [Micro Service](https://github.com/mfornos/awesome-microservices)
- [Sys admin / Devops etc.](https://github.com/kahun/awesome-sysadmin)

- [squaresce logo generator](https://www.squarespace.com/logo/)

<a id="html--css-js-library"></a>
# HTML / CSS / JS 라이브러리

- [Codyhouse](https://codyhouse.co/library/)
- [UPlabs](http://www.uplabs.com/)
- [Parallax](https://github.com/pixelcog/parallax.js)
- [Waypoints](https://github.com/imakewebthings/waypoints)
- [Scroll Magic](https://github.com/janpaepke/ScrollMagic)
- [Superscrollorama](https://github.com/johnpolacek/superscrollorama)
- [Scroll Reveal](https://github.com/jlmakes/scrollreveal.js)
- [타이포그래피: Guttenburg Kit](https://github.com/matejlatin/Gutenberg)
- [Distorted Button Effect](https://github.com/codrops/DistortedButtonEffects)
- [Velocity js animation (svg support)](https://github.com/julianshapiro/velocity)
- [Snap.svg](https://github.com/adobe-webplatform/Snap.svg)
- [Reveal](https://github.com/hakimel/reveal.js)
- [Robo Browser](https://github.com/jmcarp/robobrowser)
- [Selenium](http://www.seleniumhq.org/)
- [Nightmare JS](https://github.com/segmentio/nightmare)
- [Daydream](https://github.com/segmentio/daydream)
- [MUI](https://mui.com/)
- [Motion](https://motion.dev/) - React, JS, Vue용 애니메이션
- [GSAP](https://gsap.com/)
- [Puppeteer](https://pptr.dev/)
- [Playwright](https://playwright.dev/)


<a id="open-sourcing"></a>
# 오픈 소스

- [처음 기여하기 좋은 오픈 소스 프로젝트](http://up-for-grabs.net/#/)
- [초보자를 위한 오픈 소스 블로그](https://medium.com/@kentcdodds/first-timers-only-78281ea47455#.uki6osi6z)
- [Code Triage](https://www.codetriage.com/)
- [Good First Issue](https://goodfirstissue.dev/)
- [GitHub: Open Source Guides](https://opensource.guide/)

<a id="newsletters"></a>
# 뉴스레터
- [awesome newsletters](https://github.com/vredniy/awesome-newsletters)

<a id="blogs"></a>
# 블로그
- [highscalability](http://highscalability.com/all-time-favorites/)
- [hired in tech](http://www.hiredintech.com/system-design)
- [bike shed](http://bikeshed.fm/)
- [software engineering daily](https://softwareengineeringdaily.com/)
- [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/)
- [ByteByteGo](https://blog.bytebytego.com/)
- [dropbox](https://blogs.dropbox.com/tech/2014/07/open-sourcing-our-go-libraries/)

<a id="inspirations"></a>
# 영감
- [Showcases](https://github.com/showcases)
- [트렌드](https://github.com/trending)

<a id="eli5"></a>
# ELI5
- [Children's Illustrated guide to Kubernetes](https://www.cncf.io/phippy/)
- [Selinux coloring book](https://github.com/mairin/selinux-coloring-book)
- [Alligator Egg: lambda calculus](http://worrydream.com/AlligatorEggs/)

<a id="web-scraping"></a>
# 웹 스크래핑
- [Web Scraping in 2016](https://franciskim.co/2016/08/24/dont-need-no-stinking-api-web-scraping-2016-beyond/)
- [HN Discussion](https://news.ycombinator.com/item?id=12345693)
- [Data Mining](http://guidetodatamining.com/)
- [ web scraping](https://news.ycombinator.com/item?id=4893864)
- [Data mining](http://guidetodatamining.com/)
- [Data mining algorithm](https://github.com/linyiqun/DataMiningAlgorithm)
- [mining software repos](https://github.com/dspinellis/awesome-msr)
- [데이터 마이닝 도서](https://www.lenwood.cc/2014/05/13/12-free-data-mining-books/)
- [Data mining algo](http://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)
- [stackshare](http://stackshare.io/)


<a id="other"></a>
# 기타
- [Hardware AUtopsy using gameboy](https://www.youtube.com/watch?v=RZUDEaLa5Nw)
- [LaTeX / PDF](http://www.latex-tutorial.com/tutorials/)
- [Git](http://marc.helbling.fr/2014/09/practical-git-introduction)
- [텍스트 에디터](https://www.learnenough.com/text-editor-tutorial)
- [시스템 프로그래밍](https://github.com/angrave/SystemProgramming/wiki)
- [Awesome awesomeness](https://github.com/bayandin/awesome-awesomeness)
- [Awesome](https://github.com/sindresorhus/awesome)
- [Stock Stuff](https://github.com/neutraltone/awesome-stock-resources)
- [APIs](https://github.com/Abhishaker17/Awesome-APIs)
- [풀스택 학습을 위한 중국어(간체) 자료](https://github.com/GeniusVJR/LearningNotes)


<a id="hacking"></a>
# 해킹
- [해킹](https://www.hacksplaining.com/)
- [Awesome Hack](https://github.com/carpedm20/awesome-hacking#ctf-competiton)
- [Awesome Penetration Testing](https://github.com/enaqx/awesome-pentest)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)

<a id="competitions"></a>
# 대회
- [Stupid Hackathon](http://www.stupidhackathon.com/)
- [Devpost Hackathons](http://devpost.com/hackathons)
- [Hacker Rank](https://www.hackerrank.com/)
- [Top Coder](https://www.topcoder.com/)
- [Hack the North](https://hackthenorth.com/)
- [Space Apps Challenge](https://www.spaceappschallenge.org/)
- [World Hackathon Day](http://worldhackathonday.com/)
- [Dart Lang Hackathon](https://www.dartlang.org/hackathons/2012/happy-hour/)

<a id="resume-and-cover-letter"></a>
# 이력서와 자기소개서
- [Stackoverflow: 새로운 기술 이력서](https://news.ycombinator.com/item?id=12685700)
- [이력서와 자기소개서 예시](https://www.resumonk.com/resume-examples/software-engineer-resume-examples/software-engineer-sample-resume-%231)
- [Aline Lerner](http://blog.alinelerner.com/lessons-from-a-years-worth-of-hiring-data/)
- [Json Resume](https://jsonresume.org/themes/)
- [Enhance CV](http://www.enhancv.com/)
- [Resume Monk](https://www.resumonk.com/blog/dear-software-engineer-this-is-why-your-resume-was-rejected/)
- [careercup](https://www.careercup.com/resume)

<a id="interview-preparation"></a>
# 면접 준비
- [andreis curated guide](https://github.com/andreis/interview)
- [David Byttow Post](https://medium.com/always-be-coding/abc-always-be-coding-d5f8051afce2#.szzt4wrh4)
- [David Byttow Post #2](https://medium.com/always-be-coding/four-steps-to-google-without-a-degree-8f381aa6bd5e#.vznuf3phv)
- [Dan Pupius](https://medium.com/@dpup/whiteboarding-4df873dbba2e#.cx0e5uanq)
- [Philip Youssef](http://www.restlessprogrammer.com/2013/09/hacking-coding-interview.html)
- [Carlos Bueno facebook](https://www.facebook.com/notes/facebook-engineering/get-that-job-at-facebook/10150964382448920)
- [leet code](https://leetcode.com/)
- [NeetCode](https://neetcode.io/)
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Grind 75](https://www.techinterviewhandbook.org/grind75)
- [codwars](https://www.codewars.com/)
- [geek for geeks](http://www.geeksforgeeks.org/)
- [topcoder](https://community.topcoder.com/tc?module=ProblemArchive)
- [codility](https://codility.com/programmers/)
- [quora](https://www.quora.com/Where-can-I-find-difficult-algorithm-data-structure-problems)
- [haseebq](http://haseebq.com/)
- [haseebq](http://haseebq.com/farewell-app-academy-hello-airbnb-part-i/)
- [android interview](https://github.com/fanrunqi/AndroidInterview)
- [land an autonomous vehicle job](https://medium.com/self-driving-cars/how-to-land-an-autonomous-vehicle-job-coursework-e7acc2bfe740#.rjdtvrill)
- [bingo cheat sheet (time complexity)](http://bigocheatsheet.com/)
- [average vs amortized](http://programmers.stackexchange.com/questions/161404/amortized-analysis-worst-case-performance-guarantees)
- [stackexchange amortized vs average](http://programmers.stackexchange.com/questions/161404/amortized-analysis-worst-case-performance-guarantees)
- [연봉 협상](https://fearlesssalarynegotiation.com/book/?utm_medium=social&utm_source=hackernews.com&utm_content=online+book+announcement)

<a id="jobs"></a>
# 채용
- [awesome interview questions](https://github.com/MaximAbramchuck/awesome-interview-questions)
- [awesome remote job](https://github.com/lukasz-madon/awesome-remote-job)
- [Hacker News: Who is hiring (monthly)](https://news.ycombinator.com/submitted?id=whoishiring)
- [Levels.fyi](https://www.levels.fyi/) - 보상 데이터
- [working nomads](http://www.workingnomads.co/jobs)
- [who is hiring](https://news.ycombinator.com/submitted?id=whoishiring)
- [who is hiring](https://whoishiring.io/search/56.130/-105.732/3/?order=distance)
- [stay in tech](https://stayintech.com/info/explore)
- [Wellfound (formerly AngelList Talent)](https://wellfound.com/)
- [job hero weekly](http://www.jobheroweekly.com/)
- [hnhiring](http://hnhiring.me/)
- [simply hired](http://www.simplyhired.com/)
- [hired](https://hired.ca/)
- [lever](https://www.lever.co/)
- [remote bas](https://remotebase.io/)
- [nomad list](https://nomadlist.com/)
- [remote teams](http://oinam.github.io/remote-teams/)
- [we work remotely](https://weworkremotely.com/)
- [betakit](http://betakit.com/jobs/)
- [Remote OK](https://remoteok.com/)
- [remotive io google docs](https://docs.google.com/spreadsheets/d/1TLJSlNxCbwRNxy14Toe1PYwbCTY7h0CNHeer9J0VRzE/edit#gid=0)
- [remotive.io jobs](http://jobs.remotive.io/)
- [smarthires](https://www.smarthires.io/)
- [white truffle](https://www.whitetruffle.com/#!/)
- [숙련 엔지니어를 위한 엄선된 기회](https://www.latitude.work/)
