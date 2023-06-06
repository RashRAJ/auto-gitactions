# Audit summary

Summary for [GitLab instance](https://gitlab.com/heliumemr)

- GitHub Actions Importer version: **1.3.19320 (45563a5b32e7c2f6a8c211f96bbba76d9ef625bf)**
- Performed at: **6/6/23 at 19:49**

## Pipelines

Total: **24**

- Successful: **13 (54%)**
- Partially successful: **0 (0%)**
- Unsupported: **4 (16%)**
- Failed: **7 (29%)**

### Job types

Supported: **20 (83%)**

- YAML: **20**

Unsupported: **4 (16%)**

- None: **4**

### Build steps

Total: **619**

Known: **615 (99%)**

- before_script: **214**
- script: **206**
- checkout: **87**
- cache: **52**
- dependencies: **35**
- artifacts: **21**

Unsupported: **4 (0%)**

- coverage: **2**
- artifacts.junit: **2**

Actions: **609**

- run: **420**
- actions/checkout@v3.5.0: **87**
- actions/cache@v3.3.1: **46**
- actions/download-artifact@v3.0.1: **35**
- actions/upload-artifact@v3.1.1: **21**

### Triggers

Total: **39**

Known: **39 (100%)**

- manual: **13**
- merge_request: **13**
- push: **13**

Actions: **29**

- push: **13**
- workflow_dispatch: **13**
- pull_request: **3**

### Environment

Total: **0**

Actions: **30**

- DOCKER_PASSWORD: **10**
- DOCKER_USER: **10**
- DOCKER_TLS_CERTDIR: **2**
- AUTO_CLOSE_TOKEN: **2**
- APP_STORE_CONNECT_API_KEY_KEY_ID: **1**
- APP_STORE_CONNECT_API_KEY_ISSUER_ID: **1**
- GCP_SERVICE_KEY: **1**
- FASTLANE_PASSWORD: **1**
- FIREBASE_TOKEN: **1**
- GCP_PROJECT_ID: **1**

### Other

Total: **13**

Known: **13 (100%)**

- auto_cancel_pending_pipelines: **13**

Actions: **410**

- image: **81**
- POSTGRES_PASSWORD: **38**
- POSTGRES_HOST: **38**
- POSTGRES_USER: **38**
- POSTGRES_DB: **35**
- PORT: **29**
- npm_config_cache: **25**
- NODE_OPTIONS: **25**
- CYPRESS_CACHE_FOLDER: **25**
- DOCKER_DRIVER: **17**
- group: **13**
- cancel_in_progress: **13**
- postgres:9.6.16: **6**
- postgres: **6**
- MIX_ENV: **6**
- GRADLE_USER_HOME: **4**
- ANDROID_HOME: **4**
- POSTGRES_DB_DEV: **3**
- POSTGRES_DB_TEST: **3**
- APP_NAME: **1**

### Manual tasks

Total: **90**

Secrets: **4**

- `${{ secrets.DOCKER_PASSWORD }}`: **4**

Self hosted runners: **86**

- `k8s`: **64**
- `privileged`: **18**
- `vm-xcode11.3.1`: **4**

### Successful

#### heliumemr/consolidated-heliumhealth-web

- [heliumemr/consolidated-heliumhealth-web/.github/workflows/consolidated-heliumhealth-web.yml](heliumemr/consolidated-heliumhealth-web/.github/workflows/consolidated-heliumhealth-web.yml)
- [heliumemr/consolidated-heliumhealth-web/config.json](heliumemr/consolidated-heliumhealth-web/config.json)
- [heliumemr/consolidated-heliumhealth-web/source.yml](heliumemr/consolidated-heliumhealth-web/source.yml)

#### heliumemr/emr-3-0

- [heliumemr/emr-3-0/.github/workflows/emr-3-0.yml](heliumemr/emr-3-0/.github/workflows/emr-3-0.yml)
- [heliumemr/emr-3-0/config.json](heliumemr/emr-3-0/config.json)
- [heliumemr/emr-3-0/source.yml](heliumemr/emr-3-0/source.yml)

#### heliumemr/consolidated-emr-api

- [heliumemr/consolidated-emr-api/.github/workflows/consolidated-emr-api.yml](heliumemr/consolidated-emr-api/.github/workflows/consolidated-emr-api.yml)
- [heliumemr/consolidated-emr-api/config.json](heliumemr/consolidated-emr-api/config.json)
- [heliumemr/consolidated-emr-api/source.yml](heliumemr/consolidated-emr-api/source.yml)

#### heliumemr/api

- [heliumemr/api/.github/workflows/api.yml](heliumemr/api/.github/workflows/api.yml)
- [heliumemr/api/config.json](heliumemr/api/config.json)
- [heliumemr/api/source.yml](heliumemr/api/source.yml)

#### heliumemr/admin_api

- [heliumemr/admin_api/.github/workflows/admin_api.yml](heliumemr/admin_api/.github/workflows/admin_api.yml)
- [heliumemr/admin_api/config.json](heliumemr/admin_api/config.json)
- [heliumemr/admin_api/source.yml](heliumemr/admin_api/source.yml)

#### heliumemr/admin-mega

- [heliumemr/admin-mega/.github/workflows/admin-mega.yml](heliumemr/admin-mega/.github/workflows/admin-mega.yml)
- [heliumemr/admin-mega/config.json](heliumemr/admin-mega/config.json)
- [heliumemr/admin-mega/source.yml](heliumemr/admin-mega/source.yml)

#### heliumemr/patients-portal-web

- [heliumemr/patients-portal-web/.github/workflows/patients-portal-web.yml](heliumemr/patients-portal-web/.github/workflows/patients-portal-web.yml)
- [heliumemr/patients-portal-web/config.json](heliumemr/patients-portal-web/config.json)
- [heliumemr/patients-portal-web/source.yml](heliumemr/patients-portal-web/source.yml)

#### heliumemr/pdf-generator

- [heliumemr/pdf-generator/.github/workflows/pdf-generator.yml](heliumemr/pdf-generator/.github/workflows/pdf-generator.yml)
- [heliumemr/pdf-generator/config.json](heliumemr/pdf-generator/config.json)
- [heliumemr/pdf-generator/source.yml](heliumemr/pdf-generator/source.yml)

#### heliumemr/claim-submission-tool-web

- [heliumemr/claim-submission-tool-web/.github/workflows/claim-submission-tool-web.yml](heliumemr/claim-submission-tool-web/.github/workflows/claim-submission-tool-web.yml)
- [heliumemr/claim-submission-tool-web/config.json](heliumemr/claim-submission-tool-web/config.json)
- [heliumemr/claim-submission-tool-web/source.yml](heliumemr/claim-submission-tool-web/source.yml)

#### heliumemr/helium-android

- [heliumemr/helium-android/.github/workflows/helium-android.yml](heliumemr/helium-android/.github/workflows/helium-android.yml)
- [heliumemr/helium-android/config.json](heliumemr/helium-android/config.json)
- [heliumemr/helium-android/source.yml](heliumemr/helium-android/source.yml)

#### heliumemr/helium-ios

- [heliumemr/helium-ios/.github/workflows/helium-ios.yml](heliumemr/helium-ios/.github/workflows/helium-ios.yml)
- [heliumemr/helium-ios/config.json](heliumemr/helium-ios/config.json)
- [heliumemr/helium-ios/source.yml](heliumemr/helium-ios/source.yml)

#### heliumemr/claim-submission-tool

- [heliumemr/claim-submission-tool/.github/workflows/claim-submission-tool.yml](heliumemr/claim-submission-tool/.github/workflows/claim-submission-tool.yml)
- [heliumemr/claim-submission-tool/config.json](heliumemr/claim-submission-tool/config.json)
- [heliumemr/claim-submission-tool/source.yml](heliumemr/claim-submission-tool/source.yml)

#### heliumemr/universe

- [heliumemr/universe/.github/workflows/universe.yml](heliumemr/universe/.github/workflows/universe.yml)
- [heliumemr/universe/config.json](heliumemr/universe/config.json)
- [heliumemr/universe/source.yml](heliumemr/universe/source.yml)

### Unsupported

#### heliumemr/onemedical-ops

- [heliumemr/onemedical-ops/error.txt](heliumemr/onemedical-ops/error.txt)
- [heliumemr/onemedical-ops/config.json](heliumemr/onemedical-ops/config.json)

#### heliumemr/onemedical-on-premise-ops

- [heliumemr/onemedical-on-premise-ops/error.txt](heliumemr/onemedical-on-premise-ops/error.txt)
- [heliumemr/onemedical-on-premise-ops/config.json](heliumemr/onemedical-on-premise-ops/config.json)

#### heliumemr/admin

- [heliumemr/admin/error.txt](heliumemr/admin/error.txt)
- [heliumemr/admin/config.json](heliumemr/admin/config.json)

#### heliumemr/heliumhealth

- [heliumemr/heliumhealth/error.txt](heliumemr/heliumhealth/error.txt)
- [heliumemr/heliumhealth/config.json](heliumemr/heliumhealth/config.json)

### Failed

#### heliumemr/staging-gitops

- [heliumemr/staging-gitops/error.txt](heliumemr/staging-gitops/error.txt)
- [heliumemr/staging-gitops/config.json](heliumemr/staging-gitops/config.json)
- [heliumemr/staging-gitops/source.yml](heliumemr/staging-gitops/source.yml)

#### heliumemr/lasser2

- [heliumemr/lasser2/error.txt](heliumemr/lasser2/error.txt)

#### heliumemr/file-exporter

- [heliumemr/file-exporter/error.txt](heliumemr/file-exporter/error.txt)

#### heliumemr/onemedical-ops

- [heliumemr/onemedical-ops/error.txt](heliumemr/onemedical-ops/error.txt)
- [heliumemr/onemedical-ops/config.json](heliumemr/onemedical-ops/config.json)

#### heliumemr/onemedical-on-premise-ops

- [heliumemr/onemedical-on-premise-ops/error.txt](heliumemr/onemedical-on-premise-ops/error.txt)
- [heliumemr/onemedical-on-premise-ops/config.json](heliumemr/onemedical-on-premise-ops/config.json)

#### heliumemr/admin

- [heliumemr/admin/error.txt](heliumemr/admin/error.txt)
- [heliumemr/admin/config.json](heliumemr/admin/config.json)

#### heliumemr/tv-queues

- [heliumemr/tv-queues/error.txt](heliumemr/tv-queues/error.txt)

#### heliumemr/appointments-backend

- [heliumemr/appointments-backend/error.txt](heliumemr/appointments-backend/error.txt)

#### heliumemr/fortress

- [heliumemr/fortress/error.txt](heliumemr/fortress/error.txt)

#### heliumemr/heliumhealth

- [heliumemr/heliumhealth/error.txt](heliumemr/heliumhealth/error.txt)
- [heliumemr/heliumhealth/config.json](heliumemr/heliumhealth/config.json)

#### heliumemr/imager

- [heliumemr/imager/error.txt](heliumemr/imager/error.txt)
