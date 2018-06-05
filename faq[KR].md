**작업한 데이터는 어디에 저장 되나요?**

작업 공간이 동기화되지 않으면 파일은 브라우저 내부에만 저장되며 ([IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)를 사용하여) 그 외에 다른 곳에는 저장되지 않습니다.

브라우저 데이터를 지우면 파일이 손실되지 않도록 작업 영역을 동기화하는 것이 좋습니다.

**작업 영역을 동기화하면 작업한 데이터는 어디에 저장됩니까?**

Google로 로그인하면 기본 작업 공간인 Google 드라이브 ([앱 데이터 폴더](https://developers.google.com/drive/v3/web/appdata)) 에 저장됩니다.

Google 드라이브 작업 영역을 열면 작업 영역의 파일을 다른 사용자와 공유 할 수있는 Google 드라이브 폴더에 저장됩니다.

CouchDB 작업 공간을 열면 작업 공간의 파일이 CouchDB 데이터베이스에 저장됩니다. 이 데이터베이스는 개인 정보 보호를 위해 구내에서 호스팅 할 수 있습니다.

**StackEdit은 허락 없이 내 데이터에 액세스 할 수 있습니까?**

StackEdit은 프론트 엔드 애플리케이션입니다. Google, Dropbox, GitHub ...에 의해 발행 된 액세스 토큰은 브라우저에 저장되며 모든 백엔드 또는 3일간 당사자에게 전송되지 않으므로 누구도 데이터에 액세스 할 수 없습니다.
