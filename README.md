# 🎵 LyricMate

**LyricMate**는 노래 제목 또는 가사 키워드를 통해 노래 정보를 검색하고, 가사까지 확인할 수 있는 웹 서비스입니다.  
좋아하는 곡에 좋아요를 누르거나, 최근 검색했던 키워드를 다시 확인할 수 있어요!

---

## 💡 주요 기능

| 기능                          | 설명 |
|-------------------------------|------|
| 🔍 노래 검색                  | 노래 제목, 아티스트, 가사 키워드로 iTunes API를 통해 곡 검색 |
| 🎤 가사 보기                  | 선택한 곡의 가사를 `lyrics.ovh` API를 통해 조회 |
| ❤️ 좋아요                    | 내가 좋아하는 곡을 저장하고 목록에서 확인 가능 |
| 🕑 최근 검색 기록             | 최근 5개의 검색 키워드를 기록 및 출력 |
| 🖼️ 커버 이미지 포함한 목록   | 좋아요 목록에 앨범 커버 포함 표시 |

---

## ⚙️ 기술 스택

### Backend
- Spring Boot
- Spring Web / JPA / H2
- JWT 없이 쿠키 기반 유저 식별

### 외부 API
- [iTunes Search API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/)
- [lyrics.ovh API](https://lyricsovh.docs.apiary.io/)
