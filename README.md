# Better Benedu

한국디지털미디어고등학교의 E-러닝 시스템인 베네듀의 세션 타임아웃을 개선합니다.

현재는 Firefox 브라우저만 지원합니다.
Chrome 브라우저는 https://bugs.chromium.org/p/chromium/issues/detail?id=104058 이슈가 수정되면 지원할 수 있습니다.

## 특징
 * 베네듀의 세션 타임아웃을 개선합니다. (이건 은행도 아니고 뭐...)

## 사용법
현재는 위에 나온 문제때문에 Firefox만 지원합니다.

혹시 위에 나온 이슈가 해결되거나 마땅한 해결책이 있으신분은 PR 바랍니다.

또한 몇달 테스트 후에 잘 작동하는것 같으면 앱 스토어에 등재할 예정입니다.

### Firefox에서 사용법
1. 우선 about:debugging#/runtime/this-firefox 로 들어갑니다.
1. 임시 확장 기능을 엽니다
1. 임시 부가기능 로드를 누릅니다
1. manifest.json을 선택합니다.
1. 베네듀 페이지를 새로고침하면 잘 작동합니다!

## 버그 제보/기여
 * 2021년 부터 버그 제보는 제가 처리할 수 없습니다.
 * 대신 PR은 받습니다.
 * 물론 포크해도 괜찮습니다.