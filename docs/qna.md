콘텐츠 제작시 클라이언트 측에서 보안이슈 관련으로 75미리스튜디오(주)에 자주 물어보는 질문에 대한 답변입니다.

### 당사는 보안전문 회사에 가입되어있습니까?

- KT 텔레캅으로 관리되고 있습니다.

### 당사는 기밀 데이터 및 정보를 보안하기 위한 체계로서 서면으로 작성된 정책 그리고 행정수칙이있습니까? 있다면 그 정책 문서를 제공할 수 있습니까?

- 현재 접근하고 있는 문서는 75미리스튜디오(주) 회사 보안 정책 문서입니다.
- 이 문서(리포지터리)를 통해서 입사자 보안교육, 협력사 보안교육, 고객에게 보안정책을 전달하고 있습니다.

### 현재 모든 피고용인들은 정보 보안에 대해 충분한 교육이 되어있습니까? 구체적으로 어떻게 되고 있는지 설명해주세요.

- 현재 접근하고 있는 문서를 통해서 입사 보안교육을 진행합니다.
- 보안 위배시 회사 [징계조치사항](security_disciplinary_action.md)을 따릅니다.

### 당사는 정보 보안 정책 조항 안에 워크스테이션, 서버, 네트워크 장비, 그리고 전문 장비에 관련하여 행동수칙이 설정되어 있습니까?

- 인터넷망과 작업을 위한 내부 인트라넷 네트워크는 물리적으로 분리되어 있습니다.
- 아티스트 워크스테이션은 리눅스로 사용하며 기본적으로 USB 접근제한이 걸려있습니다. 인터넷을 물리적으로 사용할 수 없습니다.
- 서버실은 관리자가 총 3번의 생체인식(지문)을 통해서 접근할 수 있습니다. 항시 CCTV 녹화가 진행중입니다.

### 당사는 작업자에게 작업에 관련한 부분에 한에서 엑세스 권한를 부여합니까? 구체적으로 설명해주십시오.

- 해당 프로젝트만 접근할 수 있도록 권한 부여하고 있습니다.

### 당사는 피고용자, 계약자, 그리고 다른 서드파티에게 기밀 혹은 비공개 동의서를 작성합니까?

- 보안교육, 보안 서약서(NDA)를 작성합니다.

### 당사는 비즈니스적, 혹은 사적 방문자에게 해당하는 문서화된 정책이 있습니까? 구체적으로 설명해주십시오.

- 사내 [방문객 보안절차](guest.md)를 따라 보안절차를 진행합니다.

### 당사는 보안, 안전, 원거리 알림이 가능한 재난경보 시스템이 구축되어 있습니까? 그 시스템은 정기적으로 점검되고 있습니까? 구체적으로 설명해주십시오.

- 올레 CCTV 텔레캅으로 사무실 감시 시스템 운용을 하고 있습니다.
- 화재 경보기 시스템이 구축되어 있습니다.

### 당사는 데이터 스토리지 장비들이 감시 및 제한된 출입 체계를 갖춘 보안성이 보장되는 방이나 데이터 센터망안에 있습니까? 구체적으로 설명해주십시오.

- 서버실은 총 3번의 생체인증(지문)을 거쳐야 접근이 가능한 구조로 되어있습니다.
- CCTV 가 작동되고 있습니다.
- 고객 데이터, 백업은 사업의 연속성을 위해서 AWS Cloud에 백업하고 있습니다.


### 워크스테이션과 서버들은 안티바이러스, 안티스파이웨어 프로그램이 설치되어 있습니까? 구체적으로 설명해주십시오.

- 리눅스 : 망분리로 백신 필요없음
- 윈도우즈 : 1대 프린터 용도로만 사용함(무료 백신 설치)

### 작업자들이 기밀 정보 및 데이터들을 권한없이 삭제가 불가능하도록 어떠한 조치를 취하고 있는지 설명해주십시오. 이는 이메일 용량 제한이라던가, usb제한, 네트워크 세그먼트, 인터넷/프록시 방화벽과 같은 조치를 포함합니다. 

- 메일은 mailgun을 이용해서 메일 포워딩서비스를 사용하고 있습니다. 첨부파일 최대 사이즈는 25메가로 제한하여 사용중입니다.
- 리눅스를 사용하는 작업자 컴퓨터는 USB 포트에 보안씰이 설치되어있습니다. 소프트웨어적으로 USB 스토리지 타입이 연결되지 않습니다.
- 인터넷망과 내부 작업망은 물리적으로 분리되어있습니다.

### 당사는 노트북이나, 모바일 장비를 프로덕션 작업 목적으로 사용하고 있습니까? 만약 이 디바이스들을 분실할 경우, 기밀 정보 유출을 막기 위해 어떤 조치를 취하고 있는지 설명해주세요.

- 사내에서 사용하는 노트북은 모든 포트에 보안씰을 붙혀서 사용하고 있습니다.
- 휴대폰은 카메라 보안씰을 붙혀서 사용하고 있습니다.

### 당사는 피고용인에게 클라이언트 데이터를, 개인 장비를 통해 온라인이나 오프라인으로 저장할 수 있도록 허용하고 있습니까?

- 클라이언트 IN/OUT 데이터는 AWS 클라우드에 업로드 합니다.
- 권한이 있는 사람만 개인계정 + MFA(이중인증시스템)으로 다운로드 할 수 있습니다.

### 당사는 모든 작업자 및 시스템 레벨 패스워드에 대해 강제성을 갖는 최소한의 규정 정책이 설계되어 있습니까?

- 클라우드 : 숫자, 특수문자, 대문자, 소문자가 섞인 8자 이상의 암호 + MFA(이중인증시스템)을 사용합니다.
- 내부네트워크 : 숫자, 특수문자, 대문자, 소문자가 섞인 8자 이상의 암호 사용합니다.

### 당사는 무선 네트워크 기술을 사용하고 있습니까? 만약에 그렇다면, 기밀 데이터와 무선 네트워크 사이에 어떠한 보안 체계가 갖춰져 있는지 설명해주십시오.

- 내부에 손님용 Wifi와 직원용 Wifi를 운용하고 있습니다. 작업하는 네트워크와 완전 분리되어 있습니다.

### 모든 프로덕션 데이터는 FTP, Aspera이나 혹은 개인 네트워크를 통한 보안 솔루션을 이용하여 전송됩니까? 현재 사용하고 있는 모든 데이터 전송 메소드를 리스트로 작성해주시기 바랍니다.

- AWS IAM(인증시스템) + S3(스토리지) 로만 데이터를 전송합니다. (AWS 보안정책은 기본적으로 MPAA 기준을 준수합니다. : https://aws.amazon.com/ko/compliance/mpaa/)

### 만약, 프로덕션 데이터를 물리적으로 옮길 경우, 해당 드라이버를 암호화하나요? 원거리 작업자에게는 그 보안키는 어떻게 넘기나요? 물리적으로 데이터를 넘기는 수칙을 설명해주시기 바랍니다.

- 최대한 물리적인 상황을 피하고 있습니다. 클라이언트에게 AWS S3로 데이터를 업로드하는 것은 권고하고 있습니다.

### 당사는 데이터를 어떻게 백업하는지, 그리고 불의의 사고로 데이터를 유실할 때 복원을 하는 메소드를 기술해주세요. 그리고 또 복원하는데 걸리는 시간도 포함해서 설명해주십시오.

- 사업 연속성을 위해 클라우드에(AWS S3 Glaciar) 백업합니다.
- 복원에 걸리는 시간은 요청 이후 24~48시간 이내입니다.

### 당사는 중대한 보안 및 비즈니스 문제로 인해 사고가 발생했을 경우, 그리고 그러한 경우로 딜리버리에 잠재적으로 영향을 미칠 수 있을 경우, 클라이언트에게 공지하고 알리는 방식을 기술하는 수칙이 있습니까? 구체적으로 설명해주세요.

- 클라이언트의 In/Out 데이터는 클라우드에 보관합니다. 불의의 사고에 따른 사업연속성을 유지하기 위해 사용합니다.
- 마감일을 지키지 못했을 경우 처리사항은 75미리스튜디오(주)와 클라이언트간 상호간 논의가 필요합니다.
