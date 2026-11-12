# 이형주 · Hyeongju Lee

**데이터·백엔드 엔지니어.** 수집에서 적재, 서빙까지 데이터 시스템을 만듭니다.<br>
**Data & backend engineer.** I build data systems end to end, from collection and storage to serving.

[zoocasso.github.io](https://zoocasso.github.io) · [CV (PDF)](https://github.com/zoocasso/zoocasso/blob/main/cv_hyeongjulee.pdf) · [국문 이력서 (PDF)](https://zoocasso.github.io/files/HyeongjuLee_Resume_KR.pdf) · [zoocasso1590@gmail.com](mailto:zoocasso1590@gmail.com) · [LinkedIn](https://www.linkedin.com/in/hyeongju-lee-749542334)<br>
2027년 3월 석사 졸업 예정 · Finishing my master's in March 2027

[한국어](#한국어) · [English](#english) · [日本語](#日本語)

## 한국어

비전인사이드에서 2년 5개월(대리) 동안 데이터·백엔드 엔지니어로 일했고, 지금은 규슈공업대학교 대학원에서 렌즈 배열 영상의 3D 재구성을 연구합니다.

| 시스템 | 규모 | 제가 한 일 | 다른 사람이 한 일 |
| :--- | :--- | :--- | :--- |
| **KISTI 발주 과제 데이터 계층**<br>2022.08 – 2024.06 · [상세](https://zoocasso.github.io/work/kisti/) | 누적 **8,000만+ 행** (2023.11)<br>노트북 10~20대 분산 수집 | 비전인사이드 쪽 데이터 엔지니어로 수집·적재·서빙 전담. 크롤러와 API 수집기, 중앙 MySQL, 분석 모델의 FastAPI 서비스·관리 화면을 구축·운영. 사내 Java 팀의 프로토타입 웹 개발에 DB·프런트엔드 연동으로 참여하고, 사내 서버 이전과 Docker 실행 환경 구성 | 과제 설계는 KISTI 연구진, 일부 모델은 대학 위탁연구, 모델 1·2는 협력사, 프로토타입 웹은 사내 Java 팀. 과제는 이후 3억 원 규모 본사업으로 이어짐 |
| **유전체 변이 주석·리포트**<br>2022.08 – 2023.09 · [상세](https://zoocasso.github.io/work/genomics/) · [코드](https://github.com/zoocasso/bio_fastapi) | 공개 레퍼런스 **약 1 TB**<br>4단계 SQL 주석 | 파이프라인·백엔드·프런트엔드 구현. 직접 구축한 Harbor와 Docker로 운영서버에 배포 (내부 IP로만 접근) | 파이프라인 알고리즘은 팀장과 함께 설계 |
| **이미지 데이터 파이프라인**<br>히타치 수탁연구 · 규슈공대 연구실<br>2025.04 – · [상세](https://zoocasso.github.io/work/hitachi/) | 머신비전 카메라 여러 대<br>2026.09–10 네덜란드 현지 배포 | 카메라 제어(PySpin)·촬영·데이터셋 전처리와 비개발자용 PyQt GUI까지 소프트웨어를 처음부터 작성. 후임 연구원 2명에게 설계 인계 | 현지에서는 히타치 담당자가 직접 사용, 과제 파트너 연구진 대상 시연 |
| **WJMax 게임 서버**<br>2023.08 – 2024.02 · [상세](https://zoocasso.github.io/work/wjmax/) · [코드](https://github.com/zoocasso/wjmax-game-server) | 동시 접속 평균 약 300명<br>최대 **약 2,000명** | 서버·DB·보안 담당. FastAPI(Docker, EC2) + RDS MySQL, 앞단 Cloudflare 프록시·WAF | 게임 클라이언트는 다른 1명이 개발 |

**연구** · 규슈공업대학교 대학원 정보창성공학전공 석사과정 (2025.04 – ). 렌즈 배열(집적영상) 영상에서 학습 없이 기하광학으로 3D 장면을 재구성합니다. 국제학회 **1저자 논문 4편**, **ICMV 2026 최우수 포스터상**.
- **RIM** (ICMV 2026): 정사영 조건에서 양자화 오차 0인 일대일 재배열. Lytro 7개 장면에서 PSNR 23.31 → 25.70 dB (논문 기재값) · [상세](https://zoocasso.github.io/research/rim/)
- **원점 최적화** (ITC-CSCC 2025·2026): 원점을 카메라 파라미터로 계산해, 원점을 고르는 데 드는 재구성을 81번에서 1번으로 · [상세](https://zoocasso.github.io/research/origin-point/) · [코드](https://github.com/zoocasso/origin-point-optimization-vcr)
- **iRIM** (ICCAS 2026): 다시점 영상에서 가상 렌즈 배열 영상 합성

**그 밖에** · [3DOS XR 메이커톤](https://github.com/zoocasso/realtime-vision-xr-device) (2024, 연구실 5명 등록 팀에서 개발·발표·무대 시연 전담, 코드 분실로 발표자료만) · [상관 필터·VCR 깊이 추정](https://github.com/zoocasso/depth-estimation-using-vcr-algorithm-matlab) (2022 수업 프로젝트, 연구의 출발점)

**쓰는 도구** · 수집 Selenium, REST API, PySpin → 저장 MySQL, SQLAlchemy, pandas → 서빙 FastAPI, Jinja2 → 운영 Docker, Harbor, AWS EC2·RDS, Cloudflare, Linux. 주력 언어 Python·SQL.

**이력** · 비전인사이드 대리, 데이터·백엔드 엔지니어 (2022.07 – 2024.11) · 병역필 (산업기능요원 만기 복무)

## English

I worked for 29 months as a data & backend engineer at Vision Inside in Seoul. I am now a master's student at Kyushu Institute of Technology, researching 3D reconstruction from lens-array images.

| System | Scale | What I built | What others did |
| :--- | :--- | :--- | :--- |
| **KISTI-commissioned R&D platform, data layer**<br>Aug 2022 – Jun 2024 · [write-up](https://zoocasso.github.io/en/work/kisti/) | **80M+ rows** collected (Nov 2023)<br>crawlers spread over 10–20 laptops | Sole data engineer on Vision Inside's side: built and ran collection (crawlers, API collectors), the central MySQL store and serving (analysis models as FastAPI services, admin screens). Took part in the in-house Java team's prototype web app (database, frontend integration), then moved it to company servers with a Docker runtime | KISTI researchers designed the project, university teams designed some of the models, a partner company supplied models 1–2, and Vision Inside's in-house Java team built the prototype web app. The project later led to a KRW 300M main contract |
| **Genomic variant annotation & risk reports**<br>Aug 2022 – Sep 2023 · [write-up](https://zoocasso.github.io/en/work/genomics/) · [code](https://github.com/zoocasso/bio_fastapi) | **~1 TB** of public references<br>4 SQL annotation stages | Implemented the pipeline, the backend and the frontend. Deployed the service with Docker and a Harbor registry I set up, on a server reachable only from internal IPs | The pipeline algorithm was designed together with my team lead |
| **Image-data pipeline**<br>commissioned research with Hitachi, Kyushu Tech lab<br>Apr 2025 – · [write-up](https://zoocasso.github.io/en/work/hitachi/) | Several machine-vision cameras<br>deployed on site in the Netherlands, Sep–Oct 2026 | Wrote the software from scratch: camera control (Spinnaker SDK / PySpin), capture, dataset preprocessing and a PyQt GUI for non-developer researchers. Handed the design over to two successors | Used on site by Hitachi staff; demonstrated to the project partner's researchers |
| **WJMax game server**<br>Aug 2023 – Feb 2024 · [write-up](https://zoocasso.github.io/en/work/wjmax/) · [code](https://github.com/zoocasso/wjmax-game-server) | ~300 concurrent players on average<br>**~2,000** at peak | Server, database and security: FastAPI (Docker, EC2) and RDS MySQL behind a Cloudflare proxy and WAF | The game client was built by the other team member |

**Research** · Master's program, Kyushu Institute of Technology (Apr 2025 – ). Training-free, geometric-optics 3D reconstruction from lens-array (integral imaging) images. **4 first-author conference papers**, **ICMV 2026 Best Poster Award**.
- **RIM** (ICMV 2026): a one-to-one rearrangement with zero quantization error under orthographic conditions; PSNR 23.31 → 25.70 dB on 7 Stanford Lytro scenes (as reported in the paper) · [write-up](https://zoocasso.github.io/en/research/rim/)
- **Origin point optimization** (ITC-CSCC 2025, 2026): the origin is computed from the camera parameters, so 81 reconstructions become 1 · [write-up](https://zoocasso.github.io/en/research/origin-point/) · [code](https://github.com/zoocasso/origin-point-optimization-vcr)
- **iRIM** (ICCAS 2026): virtual lens-array images synthesized from multi-view images

**Also** · [3DOS, XR makerthon](https://github.com/zoocasso/realtime-vision-xr-device) (2024; five lab members registered, I did all of the development, the presentation and the stage demo; slides only, the code was lost) · [Depth estimation with correlation filters and VCR](https://github.com/zoocasso/depth-estimation-using-vcr-algorithm-matlab) (2022 course project where the research started)

**Tools** · collection Selenium, REST APIs, PySpin → storage MySQL, SQLAlchemy, pandas → serving FastAPI, Jinja2 → operations Docker, Harbor, AWS EC2 / RDS, Cloudflare, Linux. Main languages Python and SQL.

## Publications

All first author. Write-ups: [RIM and iRIM](https://zoocasso.github.io/en/research/rim/) · [origin point optimization](https://zoocasso.github.io/en/research/origin-point/)

| | Conference | Title |
| :--- | :--- | :--- |
| Poster · **Best Poster Award** | ICMV 2026, Budapest | Angular-to-Spatial Information Redistribution via Ray-based Inverse Mapping |
| Poster | ICCAS 2026, Sapporo | Virtual Lens Array Synthesis from Multi-View Images via iRIM |
| Oral | ITC-CSCC 2026, Bangkok | Accelerated Origin Point Optimization for Volumetric Computational Reconstruction · [code](https://github.com/zoocasso/origin-point-optimization-vcr) |
| Poster | ITC-CSCC 2025, Seoul | Image Enhancement of Volumetric Computational Reconstruction Using Origin Point Optimization · [code](https://github.com/zoocasso/origin-point-optimization-vcr) |

## 日本語

データ・バックエンドエンジニアです。収集から保存、サービングまでのデータシステムを作ってきました。九州工業大学大学院でレンズアレイ画像の3次元再構成を研究しています（2027年3月 修士課程修了予定）。[日本語のページ](https://zoocasso.github.io/ja/)
