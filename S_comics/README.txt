DLC 웹툰·코믹 스트립 (RP 일러와 분리)

로컬 원본:
  asset-work/comics/{챕터코드}/원본.png
  예) asset-work/comics/dlc01-opening/ry-hl-scene01.png
  예) asset-work/comics/ch01/01.png

Worker 배포 (로어북 URL용):
  lorebox-worker/public/assets/comics/{챕터코드}/파일.webp

로어북 출력 (고정 URL — 번호·랜덤 없음):
  ![](https://bi.pharang.workers.dev/assets/comics/ch01/01.webp)

※ raw/{캐릭}/{상황}/ 는 RP 일러 전용입니다.
  bi/i/{캐릭}/{코드} 규칙(랜덤 -1~-n)과 다르므로 웹툰은 comics/ 를 쓰세요.

배포: lorebox-worker 에 webp 복사 → npx wrangler deploy (bi)
