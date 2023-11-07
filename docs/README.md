## 로또 🎯
### 기능 목록
1. 사용자 입력 
- [x] 로또 구입 금액을 입력받기
- [x] 당첨번호 및 보너스 번호 입력 받기

2. 당첨 결과로 수익률 계산하기:
- [ ] 구매한 로또 번호와 당첨 번호 비교하기
- [ ] 당첨내역 및 수익률 계산 후 저장하기

3. 사용자가 발행한 로또 결과 출력:
- [ ] 사용자가 발행한 로또 수량 및 번호 출력하기
- [ ] 당첨 내역 출력하기
- [ ] 수익률 출력하기

4. 예외 처리:
- [ ] 1부터 45사이의 로또 번호가 아닌 경우
- [ ] 로또 번호가 중복되는 경우
- [ ] 로또 구입 금액이 1000원 단위로 나누어 떨어지지 않는 경우
- [ ] 당첨 번호와 보너스 번호의 개수가 정확하지 않은 경우

### 디렉토리 설계
📦src
 ┣ 📂constant
 ┃ ┗ 📜ErrorMessage.js
 ┣ 📂controller
 ┃ ┣ 📜App.js
 ┃ ┗ 📜UserController.js
 ┣ 📂models
 ┃ ┣ 📜Lotto.js
 ┃ ┣ 📜Reward.js
 ┃ ┗ 📜WinningLotto.js
 ┣ 📂views
 ┃ ┣ 📜Inputview.js
 ┃ ┗ 📜Outputview.js
 ┣ 📜index.js
 ┗ 📜Lotto.js