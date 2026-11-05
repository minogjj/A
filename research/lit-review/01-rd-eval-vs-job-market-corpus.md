# 선행연구 검토 (초벌): 국가연구개발사업 평가지표 vs. 채용시장 코퍼스 비교

- **작성일**: 2026-11-05
- **모드**: `deep-research` (ARS) — `lit-review` 모드 (narrative/integrative review)
- **AI 사용 고지**: 이 문서는 Claude(Anthropic)의 웹 검색 도구(Firecrawl)를 이용해 초벌 탐색한 결과입니다. 아래 "한계" 절에서 밝히듯, 원문 전체를 읽고 검증한 것이 아니라 검색 스니펫(제목·요약) 수준에서 1차 스크리닝한 것이므로, 실제 인용 전에는 원문 확인이 필요합니다.

---

## 1. 연구 목적 재확인

국가연구개발사업 평가지표(성과지표·역량지표 등)에서 쓰이는 언어/개념과, 실제 채용시장(채용공고 텍스트)에서 요구하는 직무역량 언어 간의 간극(gap)을 비교분석. 즉, **정책 코퍼스(policy corpus)**와 **시장 코퍼스(market corpus)**를 코퍼스언어학적으로 비교하는 연구.

## 2. 검색 범위와 한계 (먼저 명시)

- 사용 도구: Firecrawl 웹검색(일반 웹 + research 카테고리). **KCI, RISS, DBpia, Scopus, Web of Science 등 전문 학술DB에 대한 직접 질의가 아니라, 구글 계열 인덱스를 통한 간접 검색**입니다. 따라서 (1) 국내 학술지 논문 중 색인이 안 된 것은 빠질 수 있고, (2) 동일 주제의 더 정확한 선행연구가 존재할 가능성이 있습니다.
- 각 항목은 **제목·요약(스니펫) 수준**에서만 확인했고, 원문 전체를 읽어 주장의 타당성을 검증하지는 않았습니다. 따라서 아래 표의 "요지"는 1차 스크리닝 수준이며, 실제 논문에 인용하기 전에는 원문을 받아 재확인이 필요합니다.
- 저자명이 스니펫에 명확히 드러나지 않는 국내 보고서·정책문서는 기관명을 저자로 표기했습니다(예: 과학기술정보통신부, KISTEP). 개인 저자를 임의로 추정하지 않았습니다.
- 이 문서는 "narrative/integrative review" 수준의 지도이며, 체계적 문헌고찰(systematic review)의 엄격한 스크리닝 절차(PRISMA 등)를 따른 것은 아닙니다.

## 3. 주제별 클러스터와 1차 수집 문헌

### A. 국가연구개발사업 성과평가 제도·지표 (국내 정책)

| 문헌 | 구분 | 핵심 내용(스니펫 기준) | 링크 |
|---|---|---|---|
| 과학기술정보통신부, 「국가연구개발사업 표준성과지표(제5차) 성과목표지표 설정 안내서」(2021) | 정책 가이드라인 | 국가R&D사업의 표준성과지표 체계와 성과목표지표 설정 방법을 규정 | [msit.go.kr](https://www.msit.go.kr/bbs/view.do?sCode=user&nttSeqNo=3158679&bbsSeqNo=72) |
| 국가과학기술자문회의, 「2025년 국가연구개발 성과평가 실시계획(안)」 | 정책 계획 | 연도별 성과평가 실시계획 | [pacst.go.kr](https://www.pacst.go.kr/jsp/council/councilArchiveView.jsp?archive_id=1176&) |
| 과학기술정보통신부, 「제5차 국가연구개발 성과평가 기본계획(2026~2030)」 | 정책 계획 | "도전적 R&D 촉진 및 국민 체감 성과 창출을 위한 성과평가 체계 고도화" 목표 명시 | [krict.re.kr](https://www.krict.re.kr/bbs/BBSMSTR_000000000922/view.do?nttId=B000000108421Rl3sN3) / [hrstpolicy.re.kr(KISTEP)](https://hrstpolicy.re.kr/kistep/kr/policy/policyPlanKorDetail.html?rootId=2003000&menuId=2003102&board_class=BOARD01&board_seq=54819) |
| 「국가연구개발사업 등의 성과평가 및 성과관리에 관한 법률」 | 법령 | "성과평가"·"성과지표"의 법적 정의 | [law.go.kr](https://law.go.kr/LSW/lsInfoP.do?lsiSeq=115324) |
| (저자 미확인), 「한국의 국가연구개발 성과평가(1999~2013) 전개와 특징」 | KCI 학술논문 | 국가R&D 성과평가 제도의 역사적 전개와 특징 분석 — **제도사적 접근**이라 현재 지표의 언어 분석과는 결이 다름 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART001933840) |
| KISTEP, 「국가연구개발 성과 수집항목 및 제도 개선」 (K2Base 보고서) | 정책연구보고서 | 성과 수집항목·제도 개선안 | [k2base.re.kr](https://www.k2base.re.kr/ekp/view.do?rptNo=RES0220220035) |

**스크리닝 메모**: 이 클러스터는 "제도·지표가 무엇인가"를 다루는 1차 정책·법령 자료가 주를 이루고, **지표에 쓰인 언어(텍스트) 자체를 코퍼스로 다룬 연구는 확인되지 않음.** 이것이 본 연구의 공백(gap) 후보 중 하나.

### B. R&D/기업 역량·성과 평가지표 개발 (국내 학술·정책연구)

| 문헌 | 핵심 내용 | 링크 |
|---|---|---|
| 「중소기업지원 국가연구개발사업 선정평가지표에 관한 연구」 | AHP 분석으로 '기술개발 능력', '시장환경변화 대응능력' 등 선정평가지표 우선순위 도출 | [kmi.re.kr PDF](https://www.kmi.re.kr/web//downloadCon.do?rbsIdx=115&idx=19079&conIdx=7...) |
| 「한국 대학의 취업지원역량 평가지표 개발에 관한 연구」(KCI) | 전문가 자문을 통한 대학 취업지원기구 역량평가지표 개발 | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART001533462) |
| 「중소기업의 글로벌 역량 평가 지표 개발 연구」 | 중소기업 글로벌 역량 평가모형·지표 개발 | [scienceon.kisti.re.kr](https://scienceon.kisti.re.kr/srch/selectPORSrchReport.do?cn=TRKO201600013463) |
| SPRi, 「인공지능 연구지수 개발 및 성과 결정 요인 분석 연구」 | AI 분야 연구역량 지수 개발 | [spri.kr](https://spri.kr/posts/view/23268) |

**스크리닝 메모**: 지표 "개발 방법론"(AHP, 전문가 자문 등)에 대한 선행연구는 있으나, 역시 개발된 지표의 **텍스트/언어적 특성**을 분석 대상으로 삼은 연구는 아님.

### C. 채용공고 기반 스킬 추출·텍스트마이닝 (해외 NLP/노동경제 학술)

| 문헌 | 핵심 내용 | 링크 |
|---|---|---|
| (저자 미확인), "From Data to Insight: Transforming Online Job Postings into Labor-Market Intelligence," *Information* (MDPI), 2024 | 채용공고 텍스트마이닝으로 산업/직종/스킬 추출, 스킬 추출 챌린지와 접근법 리뷰 포함 | [mdpi.com](https://www.mdpi.com/2078-2489/15/8/496) |
| "SKORE: Skill-oriented extraction engine from job advertisements" | 채용공고 스킬 추출 엔진(사전기반·지도학습 접근의 한계 극복 시도) | [sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S2215016126001251) |
| "Extracting Structured Labor Market Information from Job Postings with Generative AI," ACM, 2024 | LLM(생성형 AI)을 활용해 채용공고에서 구조화된 노동시장 정보 추출 | [dl.acm.org](https://dl.acm.org/doi/full/10.1145/3674847) |
| "A Survey on Skill Identification From Online Job Ads," IEEE | 채용공고 스킬 식별 연구에 대한 서베이 | [ieeexplore.ieee.org](https://ieeexplore.ieee.org/iel7/6287639/9312710/09517309.pdf) |
| Zhang et al., "SkillSpan: Hard and Soft Skill Extraction from English Job Postings," 2022 | 채용공고에서 hard/soft skill 추출을 위한 데이터셋 및 도메인 적응 BERT 모델(SKILLSPAN) 제시 | [ar5iv.labs.arxiv.org](https://ar5iv.labs.arxiv.org/html/2204.12811) |
| "A survey on skill extraction and classification from job postings" | 채용공고 스킬 추출·분류 연구 서베이 | [ar5iv.labs.arxiv.org](https://ar5iv.labs.arxiv.org/html/2402.05617) |
| Sibarani et al. (2017) — SARO 온톨로지 (MDPI 논문 내 인용) | 데이터사이언스 스킬 식별을 위한 온톨로지 기반 추출(SARO), F-measure 79–83% | (1차 인용, 재확인 필요) |
| Fareri et al. (2021), "SkillNER," *Expert Systems with Applications* (MDPI 논문 내 인용) | NER 기반 soft skill 추출, ESCO 기반 검증 | (1차 인용, 재확인 필요) |

**스크리닝 메모**: 이 클러스터는 방법론적으로 **본 연구의 "시장 코퍼스" 축에 직접 참고할 수 있는 technique layer**(스킬 추출·텍스트마이닝 기법)를 제공. 단, 대부분 해외(영어권) 사례이며 국내 채용공고(한국어)에 그대로 적용 가능한지는 별도 검토 필요.

### D. 스킬 미스매치(정책/교육 vs 시장) 이론 및 측정 (해외 노동경제학)

| 문헌 | 핵심 내용 | 링크 |
|---|---|---|
| "Mismatch in the 21st century: An overview," *ScienceDirect* | 스킬 미스매치의 다차원적 측정, 결정요인(제도·기술변화 등), 결과(임금·생산성) 개관 | [sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S0927537126001077) |
| "Approaches to Skills Mismatch in the Labour Market: A Literature Review" | 스킬 미스매치 측정 접근법에 대한 문헌리뷰 | [researchgate.net](https://www.researchgate.net/publication/265204085_Approaches_to_Skills_Mismatch_in_the_Labour_Market_A_Literature_Review) |
| "Understanding and measuring skill gaps in Industry 4.0 — A review" | 스킬 갭의 개념·원인·결과를 유형화(논문코드별 매트릭스 제공) | [sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S0040162524000027) |
| "Dynamics of Skill Demand and Mismatch in the Dutch Labor Market: Evidence from Online Job Postings and VET Curricula" | **채용공고 ↔ 직업교육(VET) 커리큘럼 비교**라는 점에서 본 연구와 구조적으로 가장 유사한 선행연구 | [skills2capabilities.eu PDF](https://www.skills2capabilities.eu/files/results/papers/01_d4.3_dynamics_of_skill_demand_and_mismatch_in_the_dutch_labor_market_s2c_clean.pdf) |
| IMF Staff Discussion Note, "Bridging Skill Gaps for the Future: New Jobs Creation in the AI Age" (2026) | 채용공고 기반 신규 스킬 수요 측정("100건 이상 등장해야 신규 스킬로 인정" 등 운영적 정의) | [imf.org PDF](https://www.imf.org/-/media/files/publications/sdn/2026/english/sdnea2026001.pdf) |

**스크리닝 메모**: D클러스터의 **네덜란드 VET-채용공고 비교 연구**가 방법론적으로 가장 근접한 참조점. "교육/정책 문서 vs 채용공고"라는 본 연구의 구조와 직접 비교 가능하며, 반드시 원문을 받아 방법론(측정 변수, 통계기법)을 검토해야 함.

### E. 국내 NCS(국가직무능력표준)·교육과정-산업 요구역량 연계 비교 (국내 응용연구)

| 문헌 | 핵심 내용 | 링크 |
|---|---|---|
| 「NCS기반과 역량기반 채용 사례 비교 연구」(KCI) | NCS기반 채용과 역량기반 채용 사례 비교 — **NCS(정책 표준)와 채용실무 간 비교**라는 점에서 본 연구와 유사한 문제의식 | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002084413) |
| 한국직업능력연구원(KRIVET), 「국가직무능력표준(NCS) 활용 효과분석: 자격제도·채용 분야를 중심으로」 | NCS의 자격제도·채용 분야 활용 실효성 분석 및 개선안 | [krivet.re.kr](https://www.krivet.re.kr/kor/sub.do?menuSn=12&pstNo=E120183699) |
| 「컴퓨터과학 교육과정-산업체 요구역량 연계성 정량 분석」 | 대학 교육과정과 산업현장 요구역량 간 연계성을 **정량적으로 분석** — 방법론적으로 본 연구의 "비교분석" 축에 직접 참고 가능 | [ki-it.com PDF](https://www.ki-it.com/xml/49711/49711.pdf) |
| 한국지능정보사회진흥원(NIA), 「AI·데이터 사이언스 분야 직무 역량 강화를 위한 커리큘럼 연구」 | **채용공고 텍스트 분석으로 도출한 필요역량**과 해외 기업 요구역량을 비교 — 본 연구와 가장 직접적으로 겹치는 선행연구 | [nia.or.kr PDF](https://www.nia.or.kr/common/board/Download.do?bcIdx=23572&cbIdx=65684&fileNo=1) |
| 한국인공지능·소프트웨어산업협회(SW산업협회), 「인공지능 분야 직무분석 보고서」 | AI 분야 직무별 요구 지식·기술 목록화 | [sw.or.kr PDF](https://www.sw.or.kr/common/board/Download.do?bcIdx=41808&cbIdx=289&...) |

**스크리닝 메모**: **NIA의 커리큘럼 연구**가 "채용공고 텍스트 분석 → 필요역량 도출 → 비교"라는 절차를 국내에서 실제로 수행한 사례로, 본 연구의 직접적 선행연구(가장 가까운 비교대상)로 보임. 단, 비교 대상이 "해외 기업 요구역량"이며 "국가R&D 평가지표"는 아니라는 점에서 본 연구의 차별점(= 공백)이 분명해짐.

### F. 방법론: 코퍼스 비교 기법 (Keyness / 비교코퍼스 분석)

| 문헌 | 핵심 내용 | 링크 |
|---|---|---|
| Gries, "A new approach to (key) keywords analysis: Using frequency, and now also dispersion," *RCL*, 2021 | 전통적 빈도 기반 keyness에 분산(dispersion) 지표를 결합한 개선된 키워드 분석법 제안 | [stgries.info PDF](https://www.stgries.info/research/2021_STG_KeynessAsFreq&Disp_RCL.pdf) |
| "Keyness analysis: Nature, metrics and techniques" | 코퍼스 기반 (비판적) 담론분석에서 가장 널리 쓰이는 keyness 분석의 정의·지표·기법 개관 | [researchgate.net](https://www.researchgate.net/publication/319208347_Keyness_analysis_Nature_metrics_and_techniques) |
| "The reference corpus matters: Comparing the effect of different reference corpora on keyword analysis" | **참조 코퍼스(reference corpus) 선택이 키워드 분석 결과에 미치는 영향** — 본 연구가 "R&D 지표 코퍼스"와 "채용공고 코퍼스" 중 어느 쪽을 참조/타겟으로 둘지 설계할 때 방법론적으로 반드시 참고해야 할 문헌 | [researchgate.net](https://www.researchgate.net/publication/336040325_The_reference_corpus_matters_Comparing_the_effect_of_different_reference_corpora_on_keyword_analysis) |
| "Corpus Linguistics in Legal Discourse," *Int J Semiot Law*, 2021 | 법률/정책 담론에 대한 코퍼스언어학적 접근 사례 — 본 연구의 "정책 코퍼스" 분석에 참고 가능 | [link.springer.com](https://link.springer.com/article/10.1007/s11196-021-09860-8) |

### G. [2차 검색] 국내 학술DB(KCI/ScienceON/RISS) 직접 검색 결과

1차 스크리닝의 한계(일반 웹검색)를 보완하기 위해 `includeDomains`로 kci.go.kr / scienceon.kisti.re.kr / riss.kr / journal.kci.go.kr을 직접 질의했습니다. (※ 이 역시 각 DB의 자체 검색엔진이 아니라 외부 인덱스를 경유한 결과이므로, 완전한 재현을 보장하지 않습니다. 확정 전 각 DB에서 직접 재검색 권장.)

| 문헌 | 연도/저자(확인됨) | 핵심 내용 | 본 연구와의 관련성 | 링크 |
|---|---|---|---|---|
| 「국내 직무역량 연구동향 분석: 키워드 네트워크 및 토픽모델링 분석을 중심으로」 | KCI | 국내 학술지에 게재된 '직무역량' 관련 논문을 키워드 네트워크·토픽모델링으로 분석, 연구동향 파악 | **최우선 확인 대상.** 본 연구가 다루려는 '직무역량' 연구 지형을 이미 지도화했을 가능성이 있어, 본 연구의 공백 주장이 유지되는지 직접 검증해야 함 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART003036082) |
| 박정일 (2023), 「채용공고 빅데이터를 활용한 괜찮은 일자리 공급의 ...」 | 2023 · Cited by 2 | 채용공고 빅데이터 분석, 제조업 정책지원·수도권/비수도권 일자리 질 격차에 대한 정책 함의 도출 | 채용공고(시장 코퍼스) 분석 결과를 **정책 함의로 직접 연결**한 국내 선례 | [scienceon.kisti.re.kr](https://scienceon.kisti.re.kr/srch/selectPORSrchArticle.do?cn=JAKO202309343218064) |
| 한국경제지리학회지 2026, Vol.29 No.1 게재 논문 | 2026 | 온라인 채용공고 데이터 + 공출현 네트워크 분석으로 AI 전환기 문화콘텐츠산업 직무수요·공간적 집적구조 분석 | **채용공고 코퍼스에 네트워크분석을 적용한 최신 국내 사례** — 본 연구의 '시장 코퍼스' 분석 기법 설계에 직접 참고 가능 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/journalArticleList.kci?vol_isse_id=VOL000195201&sere_id=001359) |
| 「사물인터넷 인력수요 구조에 대한 분석과 전망」 | — | "사물인터넷 산업 실태조사" **정책조사 자료**와 **고용보험 데이터**를 비교하여 인력수요 전망 도출 | **구조적으로 가장 유사한 선례**: "정책/실태조사 자료" vs "고용 관련 시장 데이터"를 비교하는 2축 설계 — 단, 비교 대상이 R&D 평가지표는 아님 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART002898851) |
| 「요구분석 기반 산업체 기초직무역량 비교 분석」 | KCI | 계열별 산업체가 요구하는 기초직무역량을 요구분석 방법으로 비교 | 산업체 요구역량 비교 방법론 참고 | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002787219) |
| 「키워드 네트워크 분석을 통한 코로나19 이후 ICT 중소벤처기업정책 비교분석」 | KCI | ICT 중소벤처 지원정책 문서를 코로나19 전후로 나눠 키워드 네트워크 분석 | **정책 문서(코퍼스)에 키워드 네트워크 분석을 적용한 국내 선례** — 본 연구의 '정책 코퍼스' 분석 축 방법론에 직접 참고 | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002997178) |
| 「대학생 취업에 관한 이론적 접근과 NCS 기반 채용의 활용가능성 탐색」 | KCI | 대학생 취업영향요인 문헌연구 + NCS기반 채용 활용가능성 탐색 | NCS-채용 연계 이론적 배경 | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002065374) |
| 「네트워크 분석 및 토픽모델링을 활용한 직업교육 연구 동향 분석」 | KCI | 직업교육연구·직업능력개발연구 학술지의 연구동향을 네트워크분석/토픽모델링으로 분석 | 연구동향분석 방법론 선례(위 직무역량 연구동향 분석과 유사 계열) | [kci.go.kr](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003072420) |
| 박자현 (2013), 「토픽모델링을 활용한 국내 문헌정보학 연구동향 분석」 | 2013 · Cited by 216 | 토픽모델링 기반 국내 학술 연구동향 분석의 방법론적 원형(매우 높은 피인용) | 연구동향분석 토픽모델링 방법론의 국내 표준 참조문헌으로 활용 가능 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART001758589) |
| 「대학졸업생들의 중소기업 취업촉진 방안에 관한 연구: 기대가치이론을 ...」 | KCI | "산업현장에서 요구하는 인재와 대학을 거쳐 공급하는 인재 간의 불일치" 명시 | 국내 맥락에서 '인재 불일치(mismatch)'를 명시적으로 언급한 선례 | [kci.go.kr](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART001903544) |

**2차 검색 스크리닝 메모**: (1) NIA의 AI·데이터사이언스 커리큘럼 연구가 KCI에도 정식 등재되어 있음을 확인(ART002731017, LinkedIn 채용공고 텍스트마이닝). (2) "사물인력연구"(IoT 인력수요)는 "정책조사 vs 고용데이터" 비교라는 점에서 본 연구와 구조적으로 가장 가깝지만 R&D 평가지표가 아닌 산업 실태조사라는 차이가 있음. (3) **가장 먼저 원문을 확인해야 할 문헌은 "국내 직무역량 연구동향 분석"**(ART003036082)으로, 이 논문이 이미 '직무역량'과 '평가지표/정책지표'를 비교한 하위주제를 다뤘는지 여부에 따라 본 연구의 공백 주장이 좁아지거나 유지될 수 있음.

---

## 4. 종합(Synthesis)과 공백(Gap) 분석 — 잠정 (2차 검색 반영 수정)

> 아래는 1차 스크리닝 결과에 대한 **잠정적** 해석이며, 원문 검증 전까지는 확정적 주장으로 쓰지 않는 것을 권합니다.

1. **국내 R&D 평가지표 연구(A, B)**는 제도사·지표개발방법론(AHP, 전문가 자문)에 집중되어 있고, 지표에 쓰인 **언어 자체를 코퍼스로서 분석한 연구는 확인되지 않음**.
2. **해외 채용공고 텍스트마이닝 연구(C)**는 스킬 추출 기법은 성숙했으나, 대부분 "시장 코퍼스 단독 분석"이거나 "시장 vs 교육과정/자격체계" 비교이며, **"시장 vs 국가R&D 평가지표"라는 비교축은 선행연구에서 확인되지 않음**.
3. **스킬 미스매치 이론(D)** 중 네덜란드 VET-채용공고 비교연구는 구조적으로 가장 근접하지만, 비교 대상이 "직업교육 커리큘럼"이라는 점에서 본 연구(비교 대상="R&D 성과평가지표")와 다름.
4. **국내 NCS/교육과정 비교연구(E)**, 특히 NIA의 AI·데이터사이언스 커리큘럼 연구는 "채용공고 텍스트 분석 → 역량 도출 → 비교"라는 절차적 선례를 국내에서 제공하지만, 비교 대상이 해외 기업 요구역량이라는 점에서 본 연구와 차별화됨.
5. **방법론(F)**: keyness/참조코퍼스 선택 문헌은 본 연구 설계(어느 코퍼스를 target/reference로 둘지, 어떤 정규화 지표를 쓸지) 단계에서 직접 적용 가능.

**2차 검색(KCI/ScienceON/RISS 직접 질의) 반영 후 수정된 종합**: "국가R&D 평가지표"와 "채용시장 코퍼스"를 **직접 비교축으로 삼은 선행연구는 2차 검색에서도 확인되지 않았습니다.** 다만 (1) '직무역량' 연구동향을 이미 지도화한 논문(ART003036082)이 존재하고, (2) "정책/실태조사 자료 vs 고용데이터"를 비교한 구조적으로 유사한 선례(IoT 인력수요 연구, ART002898851)가 존재하며, (3) 정책 코퍼스에 키워드 네트워크 분석을 적용한 선례(ICT 중소벤처정책 비교, ART002997178)와 채용공고 코퍼스에 네트워크분석을 적용한 선례(한국경제지리학회지 2026)가 각각 따로 존재합니다. 즉, **"정책 코퍼스 분석" 방법론과 "시장 코퍼스 분석" 방법론은 국내에 각각 선례가 있으나, 두 코퍼스를 하나의 연구에서 직접 교차비교한 사례는 여전히 확인되지 않음** — 이것이 1차보다 더 구체화된 공백 주장입니다. 다만 이 결론은 (a) 외부 인덱스 경유 검색의 한계, (b) ART003036082 원문 미확인 상태에서의 잠정 결론이라는 점을 분명히 유지합니다.

## 5. 다음 단계 제안

- [x] KCI/RISS/DBpia 등 국내 DB 직접 검색 (1차 완료 — 외부 인덱스 경유 질의. §3-G 참조. DB 자체 검색엔진으로의 재확인은 여전히 권장)
- [ ] **최우선**: 「국내 직무역량 연구동향 분석」(ART003036082) 원문 확보 및 세부 토픽/키워드 확인 — 본 연구의 공백 주장이 좁아지는지 검증
- [ ] 「사물인터넷 인력수요 구조에 대한 분석과 전망」(ART002898851)의 "정책조사 vs 고용데이터" 비교 방법론 상세 검토
- [ ] C, D, E 클러스터의 원문 전체 입수 후 방법론(특히 네덜란드 VET 연구, NIA 커리큘럼 연구) 상세 검토
- [ ] 본 연구의 연구질문(RQ)과 방법론 블루프린트를 `deep-research`의 `research_question_agent`/`research_architect_agent`로 구체화 (현재는 lit-review 단독 모드로 수행하여 RQ 확정 단계는 생략됨)
- [ ] 확정 후 `academic-paper`(내장) 스킬로 서론·이론적 배경 집필 단계로 핸드오프
