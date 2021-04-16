# EC2 설정과 비슷한 ssh

## 시작 하는법

sudo ansible-playbook playbook.yml -e "username=kyb"
username은 루트 권한 있는 계정으로 진행 해야함

## 확인 하는법

{{user-name}}-key.pem으로 해당 유저의 홈 폴더에 키 생성
ssh -i 키DIR username@주소 로 접속 확인
