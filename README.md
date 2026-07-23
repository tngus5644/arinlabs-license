# ArinLabs License

apk_dynamic_analyzer 앱의 원격 사용 허가 파일. 앱은 실행 시 `license.json`을 읽어 동작 여부를 결정한다.

## 사용 통제 방법 (이 파일만 수정하면 됨)

- **사용 중지**: `"enabled": false` 로 변경 → 앱이 잠김
- **기간 제한**: `"expires": "YYYY-MM-DD"` → 이 날짜 이후 잠김 (비우려면 `null`)
- **잠금 화면 메시지**: `"message": "연락처 등 안내 문구"`

수정 후 커밋(또는 GitHub 웹에서 편집 → Commit)하면 몇 분 내 반영된다.
편집 권한은 이 저장소 소유자만 있으므로, 사용 허가는 소유자가 통제한다.
