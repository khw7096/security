# Cloud 정책 / Cloud Computing Policy
75미리스튜디오(주)는 Aws 클라우드를 사용합니다.<br/>
75mm Studio Co.,Ltd. shall use AWS cloud computing services.

MPAA 관련규칙 : MS-4.0(사업연속성), MS-6.0(사업연속성, 재해복구), DS-10.9(백업,복원 시스템 구현)<br/>
MPAA-related Rule : MS-4.0(Business Continuity Plan), MS-6.0(Business Continuity Plan, Disaster Recovery), DS-10.9(Backup,Implemantation of Restoration System)

## 임직원 / Employer
- 각 사용자마다 개별 보안정책을 적용합니다.
- 모든 계정의 암호는 대문자, 소문자, 숫자, 특수문자를 포함한 8자 암호 + MFA(이중인증시스템)으로 로그인할 수 있습니다.
- 클라이언트의 경우 최대 90일까지 사용가능한 계정을 발급합니다.
- 해당 프로젝트가 종료되면 외부 관계자의 계정을 협의후 제거합니다.
- 클라우드 권한이 있는 On-set 장비가 도난시 바로 관리자에게 연락하여 사용자 클라우드 키를 제거합니다.
- The Company shall apply individual security policy for each user.
- Passwords for all individual account shall require:
    - eight(8) characters
    - combination of english upper case letters, english lower case letters, numbers and special symbol.
    - MFA(Multi-Factor Authentication)
- In the case of client, account is available only for a maximum of 90 days.
- On the day of end of project, accounts of externel parties related to the project are removed upon the mutual consultation between the parties.

## 퇴사자 / Retiree
- 퇴사발표 이후 보안서약서를 작성후 즉시 AWS IAM 접근키를 제거합니다.
- After dismissal announcement, retiree shall draw up security pladge.
- Immediately after drawing up, Company shall remove AWS IAM access key.

## 클라이언트 데이터 / Data of Client
- 클라이언트가 문의한 작업데이터는 클라우드에 저장됩니다.
- 건물의 재난, 화재를 대비하고 사업의 연속성을 유지하기 위해서 클라우드로 위험을 분산합니다.
- Work data that client has requested will be stored at cloud.
- Company shall store data on cloud:
    - to spread risk of building collapse and fire.
    - for BCP(Business Continuity Plan).
    
## 프로젝트 백업 / Project Backup
- 프로젝트가 종료되면 완료된 데이터는 클라우드(AWS Glacier)로 백업합니다.
- 건물의 재난, 화재 대비 사업의 연속성을 위해서 클라우드로 위험을 분산합니다.
- Every completed data will be backed up on cloud(AWS Glacier) at the end of the project.
- Company shall store data on cloud:
    - to spread risk of building collapse and fire.
    - for BCP(Business Continuity Plan).
    
## 클라우드 Logs / Cloud Logs
- Log는 MPAA기준 12개월을 보관합니다. (MPAA 관련규칙 : PS-16.2)
- 스토리지에 저장되는 데이터는 [액세스 로그정책](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/ServerLogs.html#BucketLoggingStatusChanges)에 따라서 Log가 생성됩니다.
- Log will be storaged for 12 months on the basis of MPAA. (MPAA-related Rule : PS-16.2)
- Every data that will be stored at storage  generate logs according to [access log policy](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/ServerLogs.html#BucketLoggingStatusChanges)
