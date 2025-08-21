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

### ENTRY

| Service | GitHub | URL |
|---------|--------|-----|
| entry-lts-prod | [GitHub](https://github.com/EntryDSM/Entry-Mono) | [www.entrydsm.hs.kr](https://www.entrydsm.hs.kr) |
| entry-auth-prod | [GitHub](https://github.com/EntryDSM/Entry-Mono) | [auth.entrydsm.hs.kr](https://auth.entrydsm.hs.kr) |
| entry-admission-lts-prod | [GitHub](https://github.com/EntryDSM/Entry-Mono) | [apply.entrydsm.hs.kr](https://apply.entrydsm.hs.kr) |
| entry-admission-admin-lts-prod | [GitHub](https://github.com/EntryDSM/Entry-Mono) | [admin.entrydsm.hs.kr](https://admin.entrydsm.hs.kr) |
| entry-admission-2025-prod | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [entry-admission-admission-dev.entrydsm.hs.kr](https://entry-admission-admission-dev.entrydsm.hs.kr) |
| entry-admission-2025-admin-prod | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [entry-admission-admin-dev.entrydsm.hs.kr](https://entry-admission-admin-dev.entrydsm.hs.kr) |
| entry-admission-2025-auth-prod | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [entry-admission-auth-dev.entrydsm.hs.kr](https://entry-admission-auth-dev.entrydsm.hs.kr) |
| entry-admission-2025-user-prod | [GitHub](https://github.com/EntryDSM/Entry-Admission) | [entry-admission-user-dev.entrydsm.hs.kr](https://entry-admission-user-dev.entrydsm.hs.kr) |
| casper-config-server-prod | [GitHub](https://github.com/EntryDSM/Casper-Config-Server) | [entry-admission-api-config-server-dev.entrydsm.hs.kr](https://entry-admission-api-config-server-dev.entrydsm.hs.kr) |

### PICK

| Service | GitHub | URL |
|---------|--------|-----|
| pick-core-prod | [GitHub](https://github.com/DSM-PICK/PICK_CORE_SERVER) | [pick-core.dsmhs.kr](https://pick-core.dsmhs.kr) |
| pick-core-stag | [GitHub](https://github.com/DSM-PICK/PICK_CORE_SERVER) | [pick-core-stag.dsmhs.kr](https://pick-core-stag.dsmhs.kr) |
| pick-admin-prod | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_V2) | [pick-admin.dsmhs.kr](https://pick-admin.dsmhs.kr) |
| pick-admin-stag | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_V2) | [pick-admin-stag.dsmhs.kr](https://pick-admin-stag.dsmhs.kr) |
| pick-teacher-prod | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_TEACHER_V2) | [pick-teacher.dsmhs.kr](https://pick-teacher.dsmhs.kr) |
| pick-teacher-stag | [GitHub](https://github.com/DSM-PICK/PiCK2024_FRONT_TEACHER_V2) | [pick-teacher-stag.dsmhs.kr](https://pick-teacher-stag.dsmhs.kr) |

### DMS

| Service | GitHub | URL |
|---------|--------|-----|
| dms-backend-prod | [GitHub](https://github.com/team-aliens/DMS-Backend) | [api.dms-dsm.com](https://api.dms-dsm.com) |
| dms-backend-stag | [GitHub](https://github.com/team-aliens/DMS-Backend) | [dev-api.dms-dsm.com](https://dev-api.dms-dsm.com) |
| dms-frontend-prod | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [admin.dms-dsm.com](https://admin.dms-dsm.com) |
| dms-frontend-stag | [GitHub](https://github.com/team-aliens/DMS-Frontend) | [admin-dev.dms-dsm.com](https://admin-dev.dms-dsm.com) |
| dms-webview-prod | [GitHub](https://github.com/team-aliens/dms-webview) | [webview.dms-dsm.com](https://webview.dms-dsm.com) |

### DSMREPO

| Service | GitHub | URL |
|---------|--------|-----|
| whopper-prod | [GitHub](https://github.com/DSM-Repo/Whopper) | [api.dsm-repo.com](https://api.dsm-repo.com) |
| repo-main-prod | [GitHub](https://github.com/DSM-Repo/repo) | [www.dsm-repo.com](https://www.dsm-repo.com) |
| repo-teacher-prod | [GitHub](https://github.com/DSM-Repo/repo) | [teacher.dsm-repo.com](https://teacher.dsm-repo.com) |
| repo-user-prod | [GitHub](https://github.com/DSM-Repo/repo) | [user.dsm-repo.com](https://user.dsm-repo.com) |

### XQUARE

| Service | GitHub | URL |
|---------|--------|-----|
| xquare-frontend-prod | [GitHub](https://github.com/team-xquare/xquare-frontend-v2) | [infra.dsmhs.kr](https://infra.dsmhs.kr) |
| xquare-frontend-stag | [GitHub](https://github.com/team-xquare/xquare-frontend-v2) | [infra-stag.dsmhs.kr](https://infra-stag.dsmhs.kr) |
| xquare-infra-prod | [GitHub](https://github.com/team-xquare/xquare-infra-backend) | [xquare-api.dsmhs.kr](https://xquare-api.dsmhs.kr) |
| xquare-infra-stag | [GitHub](https://github.com/team-xquare/xquare-infra-backend) | [xquare-api-stag.dsmhs.kr](https://xquare-api-stag.dsmhs.kr) |

### DAEMAWIKI

| Service | GitHub | URL |
|---------|--------|-----|
| daemawiki-prod | [GitHub](https://github.com/daemawiki/Claude) | [daemawiki.dsmhs.kr](https://daemawiki.dsmhs.kr) |
| daemawiki-stag | [GitHub](https://github.com/daemawiki/Claude) | [daemawiki-stag.dsmhs.kr](https://daemawiki-stag.dsmhs.kr) |

### MOZU

| Service | GitHub | URL |
|---------|--------|-----|
| mozu-server-prod | [GitHub](https://github.com/team-mozu/mozu-BE) | [mozu.dsmhs.kr](https://mozu.dsmhs.kr) |
| mozu-server-stag | [GitHub](https://github.com/team-mozu/mozu-BE) | [mozu-stag.dsmhs.kr](https://mozu-stag.dsmhs.kr) |

### BREMENTOWNMUSICIANS

| Service | GitHub | URL |
|---------|--------|-----|
| wemeet-stag | [GitHub](https://github.com/BremenMusicians/WeMeet_BE) | [wemeet.dsmhs.kr](https://wemeet.dsmhs.kr) |

### DAEDONG

| Service | GitHub | URL |
|---------|--------|-----|
| sillok-be-prod | [GitHub](https://github.com/Team-jeong-ho-kim/Sillok_BE) | [sillok-api.dsmhs.kr](https://sillok-api.dsmhs.kr) |

### DAEDONGYEOJIDO

| Service | GitHub | URL |
|---------|--------|-----|
| whispy-prod | [GitHub](https://github.com/Team-jeong-ho-kim/Whispy_BE) | [whispy.dsmhs.kr](https://whispy.dsmhs.kr) |

### DSMAUTHSERVICE

| Service | GitHub | URL |
|---------|--------|-----|
| dsm-login-prod | [GitHub](https://github.com/DAS-DsmAuthService/Dsm-login-server) | [dsm-login.dsmhs.kr](https://dsm-login.dsmhs.kr) |

### HELPER

| Service | GitHub | URL |
|---------|--------|-----|
| helper-prod | [GitHub](https://github.com/Team-LoopCat/Helper_Backend) | [helper.dsmhs.kr](https://helper.dsmhs.kr) |

### HIGHTONTEAM8

| Service | GitHub | URL |
|---------|--------|-----|
| backend | [GitHub](https://github.com/HighTon-Team-8/Team8_BE) | [highton-team8.dsmhs.kr](https://highton-team8.dsmhs.kr) |

### NONAMED

| Service | GitHub | URL |
|---------|--------|-----|
| lotura-prod | [GitHub](https://github.com/team-osj/Lotura_BackEnd_V2) | [lotura.dsmhs.kr](https://lotura.dsmhs.kr) |

### NUNEDDINE

| Service | GitHub | URL |
|---------|--------|-----|
| nuneddine-deployment-prod | [GitHub](https://github.com/taeyang-s-playGround/Nuneddine) | [nuneddine.dsmhs.kr](https://nuneddine.dsmhs.kr) |

### SILENTFLOWERS

| Service | GitHub | URL |
|---------|--------|-----|
| silent-flowers-prod | [GitHub](https://github.com/Silent-flowers-bloom-gracefully/backend) | [silent-flowers.dsmhs.kr](https://silent-flowers.dsmhs.kr) |

</details>
