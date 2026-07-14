![image](https://user-images.githubusercontent.com/67373938/225011454-59943482-b4f7-4a18-adbe-5cf08d711bd4.gif)
# DSM을 위한 통합 인프라, XQUARE Infrastructure
> 안녕하세요, tema-xquare입니다 :)  
XQUARE Infrastructure는 대덕소프트웨어마이스터고등학교만을 위한 통합 인프라 서비스로 DSM 학생이라면 누구나 쉽게 배포할 수 있도록 도와줍니다.

### XQUARE Infrastructure는 다음과 같은 목적으로 탄생했어요.
1. 누구나 쉽게 배포하고 운영의 기회를 제공합니다.
2. DSM의 개발자는 배포의 걱정없이 새로운 빠르고 쉽게 서비스를 배포하여 성장의 기회를 얻습니다.

### XQUARE Infrastructure는 아래의 기능들을 제공해요.
1. 간단한 설정으로 배포합니다.
2. 환경변수를 쉽게 수정할 수 있습니다.
3. 어플리케이션 코드 수정 없이 APM을 제공합니다.
4. Tracing 을 기반으로 한 Alert 를 제공합니다.
5. 팀원들을 손쉽게 관리할 수 있습니다.
6. 배포내역을 쉽게 확인할 수 있습니다.
7. 다양한 Metric, Log, Trace 를 제공합니다.

### 링크
* XQUARE Organization : https://github.com/team-xquare 
* XQUARE Infrastructure : https://xquare-infra.xquare.app
* XQUARE DevOps : https://team-xquare.notion.site/DevOps-a8693ce0928c465db3a1e598473dda6f

<details>
<summary><h3>XQUARE를 통해 배포된 서비스 보기</h3></summary>

### DMS

| Service | GitHub | URL |
|---------|--------|-----|
| frontend-prod | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [admin-dms.dsmhs.kr](https://admin-dms.dsmhs.kr) |
| frontend-stag | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [admin-dev-dms.dsmhs.kr](https://admin-dev-dms.dsmhs.kr) |
| webview-prod | [GitHub](https://github.com/team-aliens/dms-webview) | [webview-dms.dsmhs.kr](https://webview-dms.dsmhs.kr) |
| gateway-prod | [GitHub](https://github.com/team-aliens/DMS-Backend) | [api-dms.dsmhs.kr](https://api-dms.dsmhs.kr) |
| gateway-stag | [GitHub](https://github.com/team-aliens/DMS-Backend) | [dev-api-dms.dsmhs.kr](https://dev-api-dms.dsmhs.kr) |
| main-prod | [GitHub](https://github.com/team-aliens/DMS-Backend) | No routes |
| main-stag | [GitHub](https://github.com/team-aliens/DMS-Backend) | No routes |
| notification-prod | [GitHub](https://github.com/team-aliens/DMS-Backend) | No routes |
| notification-stag | [GitHub](https://github.com/team-aliens/DMS-Backend) | No routes |
| head-frontend-prod | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [head-teacher-dms.dsmhs.kr](https://head-teacher-dms.dsmhs.kr) |
| general-frontend-prod | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [general-teacher-dms.dsmhs.kr](https://general-teacher-dms.dsmhs.kr) |
| student-frontend-prod | [GitHub](https://github.com/yellowstarr0323/DMS-FE-Student) | [student-dms.dsmhs.kr](https://student-dms.dsmhs.kr) |

### ENTRY

| Service | GitHub | URL |
|---------|--------|-----|
| entry-admission | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [admission.entrydsm.hs.kr](https://admission.entrydsm.hs.kr) |
| entry-admin | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [admin.entrydsm.hs.kr](https://admin.entrydsm.hs.kr) |
| entry-auth | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [auth.entrydsm.hs.kr](https://auth.entrydsm.hs.kr) |
| entry-user | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [www.entrydsm.hs.kr](https://www.entrydsm.hs.kr) |
| casper-config-server | [GitHub](https://github.com/EntryDSM/Casper-Config-Server) | [config.entrydsm.hs.kr](https://config.entrydsm.hs.kr) |
| casper-gate-way | [GitHub](https://github.com/EntryDSM/Equus-Api-Gateway) | [api.entrydsm.hs.kr](https://api.entrydsm.hs.kr) |
| casper-application | [GitHub](https://github.com/EntryDSM/Casper-Application) | [casper-application.entrydsm.hs.kr](https://casper-application.entrydsm.hs.kr) |
| casper-feed | [GitHub](https://github.com/EntryDSM/Casper-Feed) | [casper-feed.entrydsm.hs.kr](https://casper-feed.entrydsm.hs.kr) |
| casper-user | [GitHub](https://github.com/EntryDSM/Casper-User) | [casper-user.entrydsm.hs.kr](https://casper-user.entrydsm.hs.kr) |
| casper-status | [GitHub](https://github.com/EntryDSM/Casper-Status) | [casper-status.entrydsm.hs.kr](https://casper-status.entrydsm.hs.kr) |
| casper-schedule | [GitHub](https://github.com/EntryDSM/Casper-Schedule) | [casper-schedule.entrydsm.hs.kr](https://casper-schedule.entrydsm.hs.kr) |
| entrydsm-community-manager | [GitHub](https://github.com/EntryDSM/entrydsm-community-manager) | No routes |

### PICK

| Service | GitHub | URL |
|---------|--------|-----|
| pick-core-prod | [GitHub](https://github.com/DSM-PICK/PiCK_CORE_SERVER) | [pick-core.dsmhs.kr/](https://pick-core.dsmhs.kr/) |
| pick-core-stag | [GitHub](https://github.com/DSM-PICK/PICK_CORE_SERVER) | [pick-core-stag.dsmhs.kr](https://pick-core-stag.dsmhs.kr) |
| pick-admin-prod | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_V2) | [pick-admin.dsmhs.kr](https://pick-admin.dsmhs.kr) |
| pick-admin-stag | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_V2) | [pick-admin-stag.dsmhs.kr](https://pick-admin-stag.dsmhs.kr) |
| pick-teacher-prod | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_TEACHER_V2) | [pick-teacher.dsmhs.kr](https://pick-teacher.dsmhs.kr) |
| pick-teacher-stag | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_TEACHER_V2) | [pick-teacher-stag.dsmhs.kr](https://pick-teacher-stag.dsmhs.kr) |

### XQUARE

| Service | GitHub | URL |
|---------|--------|-----|
| xquare-supporter-prod | [GitHub](https://github.com/team-xquare/xquare-community-manager) | No routes |
| infra-backend-stag | [GitHub](https://github.com/team-xquare/xquare-infra-backend-v3) | [infra-backend-stag.dsmhs.kr](https://infra-backend-stag.dsmhs.kr) |
| infra-backend-prod | [GitHub](https://github.com/team-xquare/xquare-infra-backend-v3) | [infra-backend.dsmhs.kr](https://infra-backend.dsmhs.kr) |
| infra-frontend-stag | [GitHub](https://github.com/team-xquare/xquare-infra-frontend-v3) | [xquare-stag.dsmhs.kr](https://xquare-stag.dsmhs.kr) |
| infra-frontend-prod | [GitHub](https://github.com/team-xquare/xquare-infra-frontend-v3) | [xquare.dsmhs.kr](https://xquare.dsmhs.kr) |
| xquare-server | [GitHub](https://github.com/team-xquare/xquare-server) | [xquare-server.dsmhs.kr](https://xquare-server.dsmhs.kr) |

### DAEMA

| Service | GitHub | URL |
|---------|--------|-----|
| daema-client-prod | [GitHub](https://github.com/kangeunchan/daema-coin-client) | [daema.dsmhs.kr](https://daema.dsmhs.kr) |
| daema-client-stag | [GitHub](https://github.com/kangeunchan/daema-coin-client) | [daema-stag.dsmhs.kr](https://daema-stag.dsmhs.kr) |
| daema-seller-prod | [GitHub](https://github.com/kangeunchan/daema-coin-client) | [daema-seller.dsmhs.kr](https://daema-seller.dsmhs.kr) |
| daema-admin-prod | [GitHub](https://github.com/kangeunchan/daema-coin-client) | [daema-admin.dsmhs.kr](https://daema-admin.dsmhs.kr) |
| daema-server-prod | [GitHub](https://github.com/kangeunchan/daema-coin-server) | [daema-server-prod.dsmhs.kr](https://daema-server-prod.dsmhs.kr) |

### FINDA

| Service | GitHub | URL |
|---------|--------|-----|
| finda-gateway-dev | [GitHub](https://github.com/team-FINDA/Finda-Backend) | [finda-dev.dsmhs.kr](https://finda-dev.dsmhs.kr) |
| finda-auth-dev | [GitHub](https://github.com/team-FINDA/Finda-Backend) | [finda-auth-dev.dsmhs.kr](https://finda-auth-dev.dsmhs.kr) |
| finda-volunteer-dev | [GitHub](https://github.com/team-FINDA/Finda-Backend) | [finda-volunteer-dev.dsmhs.kr](https://finda-volunteer-dev.dsmhs.kr) |
| finda-notification-dev | [GitHub](https://github.com/team-FINDA/Finda-Backend) | [finda-notification-dev.dsmhs.kr](https://finda-notification-dev.dsmhs.kr) |
| finda-batch-dev | [GitHub](https://github.com/team-FINDA/Finda-Backend) | [finda-batch-dev.dsmhs.kr](https://finda-batch-dev.dsmhs.kr) |

### DSMREPO

| Service | GitHub | URL |
|---------|--------|-----|
| whopper-prod | [GitHub](https://github.com/DSM-Repo/Whopper) | [api.dsm-repo.com](https://api.dsm-repo.com) |
| repo-main-prod | [GitHub](https://github.com/DSM-Repo/repo) | [www.dsm-repo.com](https://www.dsm-repo.com) |
| repo-teacher-prod | [GitHub](https://github.com/DSM-Repo/repo) | [teacher.dsm-repo.com](https://teacher.dsm-repo.com) |
| repo-user-prod | [GitHub](https://github.com/DSM-Repo/repo) | [user.dsm-repo.com](https://user.dsm-repo.com) |

### GUPSIKBULK

| Service | GitHub | URL |
|---------|--------|-----|
| backend | [GitHub](https://github.com/GupSikBulk/GupSikBulk_BE) | [gupsikbulk-api.dsmhs.kr](https://gupsikbulk-api.dsmhs.kr) |
| frontend | [GitHub](https://github.com/GupSikBulk/GupSikBulk_FE) | [gupsikbulk.dsmhs.kr](https://gupsikbulk.dsmhs.kr) |
| backend-dev | [GitHub](https://github.com/GupSikBulk/GupSikBulk_BE) | [gupsikbulk-dev-api.dsmhs.kr](https://gupsikbulk-dev-api.dsmhs.kr) |
| frontend-stag | [GitHub](https://github.com/GupSikBulk/GupSikBulk_FE) | [gupsikbulk-stag.dsmhs.kr](https://gupsikbulk-stag.dsmhs.kr) |

### DAEDONGYEOJIDO

| Service | GitHub | URL |
|---------|--------|-----|
| daedong-api-prod | [GitHub](https://github.com/Team-jeong-ho-kim/Daedongyeojido_BE_v4.0) | [daedong-api-prod.dsmhs.kr](https://daedong-api-prod.dsmhs.kr) |
| daedong-api-stag | [GitHub](https://github.com/Team-jeong-ho-kim/Daedongyeojido_BE_v4.0) | [daedong-api-stag.dsmhs.kr](https://daedong-api-stag.dsmhs.kr) |
| little-be-temp | [GitHub](https://github.com/Little-DSM/Little-BE) | [little-be-temp.dsmhs.kr](https://little-be-temp.dsmhs.kr) |

### SIGNSAFE

| Service | GitHub | URL |
|---------|--------|-----|
| signsafe-api | [GitHub](https://github.com/signsafe-io/signsafe-api) | [signsafe-api.dsmhs.kr](https://signsafe-api.dsmhs.kr) |
| signsafe-ai | [GitHub](https://github.com/signsafe-io/signsafe-ai) | No routes |
| signsafe-web | [GitHub](https://github.com/signsafe-io/signsafe-web) | [signsafe-web.dsmhs.kr](https://signsafe-web.dsmhs.kr) |

### DONGNEDEUKTEM

| Service | GitHub | URL |
|---------|--------|-----|
| server | [GitHub](https://github.com/dongne-deuktem/server) | [dongne-deuktem-server.dsmhs.kr](https://dongne-deuktem-server.dsmhs.kr) |
| seller-web | [GitHub](https://github.com/dongne-deuktem/seller-web) | [dongne-deuktem-seller.dsmhs.kr](https://dongne-deuktem-seller.dsmhs.kr) |

### DSG

| Service | GitHub | URL |
|---------|--------|-----|
| dsg | [GitHub](https://github.com/2026DSG/DSG_Backend) | [dsg-api.dsmhs.kr](https://dsg-api.dsmhs.kr) |
| dsg-fe | [GitHub](https://github.com/2026DSG/DSG_Frontend) | [dsg.dsmhs.kr](https://dsg.dsmhs.kr) |

### FABLO

| Service | GitHub | URL |
|---------|--------|-----|
| falletter-server-prod | [GitHub](https://github.com/FABLOFABLO/Falletter-Backend) | [falletter-api.dsmhs.kr](https://falletter-api.dsmhs.kr) |
| falletter-server-dev | [GitHub](https://github.com/FABLOFABLO/Falletter-Backend) | [falletter-dev-api.dsmhs.kr](https://falletter-dev-api.dsmhs.kr) |

### JOBIS

| Service | GitHub | URL |
|---------|--------|-----|
| fe-webview-prod | [GitHub](https://github.com/Team-return/JOBIS-WEBVIEW) | [jobis-webview.dsmhs.kr](https://jobis-webview.dsmhs.kr) |
| fe-webview-stag | [GitHub](https://github.com/Team-return/JOBIS-WEBVIEW) | [jobis-webview-stag.dsmhs.kr](https://jobis-webview-stag.dsmhs.kr) |

### LEEJH08

| Service | GitHub | URL |
|---------|--------|-----|
| gifty-prod | [GitHub](https://github.com/leejh08/Gifty_Server) | [leejh08-gifty-api.dsmhs.kr](https://leejh08-gifty-api.dsmhs.kr) |
| gifty-dev | [GitHub](https://github.com/leejh08/Gifty_Server) | [leejh08-gifty-api-dev.dsmhs.kr](https://leejh08-gifty-api-dev.dsmhs.kr) |

### MOHAENG

| Service | GitHub | URL |
|---------|--------|-----|
| be-prod | [GitHub](https://github.com/SERVICE-MOHAENG/Mohaeng-BE) | [mohaeng-api.dsmhs.kr](https://mohaeng-api.dsmhs.kr) |
| be-stag | [GitHub](https://github.com/SERVICE-MOHAENG/Mohaeng-BE) | [mohaeng-api-stag.dsmhs.kr](https://mohaeng-api-stag.dsmhs.kr) |

### MOTIVEET

| Service | GitHub | URL |
|---------|--------|-----|
| backend | [GitHub](https://github.com/team-gozip/motiveet-BE-online) | No routes |
| frontend | [GitHub](https://github.com/team-gozip/motiveet_FE_online) | [motiveet-web.dsmhs.kr](https://motiveet-web.dsmhs.kr) |

### OPENAIPROXY

| Service | GitHub | URL |
|---------|--------|-----|
| proxy | [GitHub](https://github.com/aiminted/openai-proxy) | [openai-proxy.dsmhs.kr](https://openai-proxy.dsmhs.kr) |
| admin | [GitHub](https://github.com/aiminted/openai-proxy-admin) | [openai-proxy-admin.dsmhs.kr](https://openai-proxy-admin.dsmhs.kr) |

### PROJECTSILMOO

| Service | GitHub | URL |
|---------|--------|-----|
| gujeuk-check-in-server | [GitHub](https://github.com/GuJeuk-Check-in/GuJeuk-Check-In_server) | No routes |
| gujeuk-check-in-server-docker | [GitHub](https://github.com/GuJeuk-Check-in/GuJeuk-Check-In_server) | No routes |

### AIRLEG

| Service | GitHub | URL |
|---------|--------|-----|
| airleg-docs | [GitHub](https://github.com/leejh08/AirLeg) | [airleg-guide.dsmhs.kr](https://airleg-guide.dsmhs.kr) |

### BOOKMARU

| Service | GitHub | URL |
|---------|--------|-----|
| bookmaru | [GitHub](https://github.com/plain-bookshelf/BookMaru-BE) | [bookmaru.dsmhs.kr](https://bookmaru.dsmhs.kr) |

### DSMAUTHSERVICE

| Service | GitHub | URL |
|---------|--------|-----|
| dsm-login-prod | [GitHub](https://github.com/DAS-DsmAuthService/Dsm-login-server) | [dsm-login.dsmhs.kr](https://dsm-login.dsmhs.kr) |

### EPM

| Service | GitHub | URL |
|---------|--------|-----|
| epm | [GitHub](https://github.com/nerhwida/epm) | [epm.dsmhs.kr](https://epm.dsmhs.kr) |

### GUNYOIL

| Service | GitHub | URL |
|---------|--------|-----|
| gunyoil-be | [GitHub](https://github.com/GUNYOIL/gunyoil-be) | [gunyoil.dsmhs.kr](https://gunyoil.dsmhs.kr) |

### JAKBU

| Service | GitHub | URL |
|---------|--------|-----|
| be-prod | [GitHub](https://github.com/Team-selfton/JakBu_BE) | [jakbu-api.dsmhs.kr](https://jakbu-api.dsmhs.kr) |

### KIMSARAM32

| Service | GitHub | URL |
|---------|--------|-----|
| iamout | [GitHub](https://github.com/kimsaram32/iamout-slop) | [iamout.dsmhs.kr](https://iamout.dsmhs.kr) |

### LITTLEDSM

| Service | GitHub | URL |
|---------|--------|-----|
| little-be-prod | [GitHub](https://github.com/Little-DSM/Little-BE) | [littledsm-api.dsmhs.kr](https://littledsm-api.dsmhs.kr) |

### LOCALQUEST

| Service | GitHub | URL |
|---------|--------|-----|
| ai-api | [GitHub](https://github.com/Local-Quest/AI) | [localquest.dsmhs.kr](https://localquest.dsmhs.kr) |

### MEDIASEGMENTDOWNLOADER

| Service | GitHub | URL |
|---------|--------|-----|
| msd | [GitHub](https://github.com/nerhwida/MSD) | [msd.dsmhs.kr](https://msd.dsmhs.kr) |

### NONAMED

| Service | GitHub | URL |
|---------|--------|-----|
| osj-be-prod | [GitHub](https://github.com/OSJ-v3/OSJ_V3_BE) | [osj.dsmhs.kr](https://osj.dsmhs.kr) |

### NSG

| Service | GitHub | URL |
|---------|--------|-----|
| nsg-be | [GitHub](https://github.com/DSM-NSG/NSG-BE) | No routes |

### PLS

| Service | GitHub | URL |
|---------|--------|-----|
| backend-stag | [GitHub](https://github.com/PLsDsm/backend-v1) | [backend-stag.dsmhs.kr](https://backend-stag.dsmhs.kr) |

### PLSDSM

| Service | GitHub | URL |
|---------|--------|-----|
| pls-backend | [GitHub](https://github.com/PLsDsm/backend-v1) | [plsdsm-pls-backend.dsmhs.kr](https://plsdsm-pls-backend.dsmhs.kr) |

### SCHOOLFESTIVAL

| Service | GitHub | URL |
|---------|--------|-----|
| dsmbattle | [GitHub](https://github.com/minecraft-festival/dsmbattle) | [dsmbattle.dsmhs.kr](https://dsmbattle.dsmhs.kr) |

### SOFTWARERENGINEERING

| Service | GitHub | URL |
|---------|--------|-----|
| brawlgg-server-v2 | [GitHub](https://github.com/Team-selfton/BrawlGG) | [brawlgg-server.dsmhs.kr](https://brawlgg-server.dsmhs.kr) |

### TEACHER

| Service | GitHub | URL |
|---------|--------|-----|
| teacher-prod | [GitHub](https://github.com/SeoMuseong/DSMLearnCast) | [learn.dsmhs.kr](https://learn.dsmhs.kr) |

### YUON

| Service | GitHub | URL |
|---------|--------|-----|
| server | [GitHub](https://github.com/team-yuon/server) | [yuon-api.dsmhs.kr](https://yuon-api.dsmhs.kr) |

</details>
