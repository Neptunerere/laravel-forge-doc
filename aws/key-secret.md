# KEY / Secret 세팅하기

<mark style="color:purple;">**※ AWS 세팅하기 전. AWS 계정 생성이 사전에 꼭 필요합니다.**</mark>

## 사용자 생성

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

AWS 계정을 생성 완료했다면. 상단 이미지에서 빨간 네모로 쳐진 `AWS IAM dashboard`를 클릭합니다.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

접속하였다면 사용자 부분에서 나타나고 있는 숫자를 클릭합니다.

클릭하면 사용자 리스트가 나타나는데 우측 상단 사용자 생성 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

규칙에 맞추어 사용자 이름을 입력 후 다음 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

권한 설정을 직접 정책 연결로 변경하고 권한 정책에서 "AmazonEC2FullAccess", "AmazonVPCFullAccess" 를 검색하여 권한을 설정합니다.

다음 단계로 이동한 후 3단계 검토 및 생성으로 넘어가는데 따로 설정할 것 없이 사용자 생성 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

설정이 완료되면 사용자 리스트로 넘어오게 되는데 방금 생성한 사용자를 클릭합니다.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

상세 화면에서 보안 자격 증명 탭을 클릭합니다.

스크롤을 내리다 보면 액세스 키라는 탭이 있는데 액세스 키 만들기 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

라라벨 Forge는 서드 파티 서비스이기 때문에 서드 파티 서비스를 클릭한 후 하단에 있는 약관 동의를 누르고 다음 단계로 이동합니다.

설명 태그 설정하는 단계로 넘어가는데 사용자분께서 편하신 이름으로 설정해주시면 됩니다.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

3단계로 넘어오게 되면 드디어 액세스키와 비밀 액세스 키를 발급 받게 되는데 복사를 해서 하단 이미지에 있는 입력란에 붙여넣기 합니다.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

Servers 탭이 나타나면 정상적으로 세팅이 완료되었습니다.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
