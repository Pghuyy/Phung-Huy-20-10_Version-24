# 20/10 · 10B4 — V20 REPLY MOMENT

V20 keeps the stable V18/V19 letter experience and rebuilds the moment after a letter is finished.

## Changes
- Removed the 10B4 tree completely.
- Removed tree/localStorage progression logic.
- Fixed the letter footer so the signature never sits on top of the final paragraph.
- Separated `10B4` metadata from the close button.
- After the last typed character, a clear **Đọc xong rồi ♡** interaction panel appears outside the paper.
- The panel exposes **Mở một điều nhỏ nữa** and all three reply reactions immediately, instead of hiding the reply behind a tiny corner button.
- The paper remains a clean screenshot-ready block; the interaction panel never covers the letter text.
- Mobile layout keeps the paper and the interaction panel within the viewport as much as possible, without requiring a second scroll just to discover the reaction.
- Existing typing, sound, search, heart burst and performance behavior are preserved.

## Files
- `index.html`
- `style.css`
- `app.js`
- `data.js`
- `README.md`

Deploy the five files together at the root of a GitHub Pages repository.


## V23 — letter photo finish
- Keeps the V21 bonus and all three reactions.
- Adds an optional client-side personal photo upload after the letter finishes.
- The selected photo is shown as a small fixed-size photo stamp inside the letter, so it does not increase letter height or cause mobile overflow.
- No photo is uploaded to a server; the browser uses a local object URL only.
- The 40-student finale is now wired to appear after all student letters have actually been opened.
- Removed the unused soundHint element.

- V23: làm rõ luồng khám phá: 3 thẻ hướng dẫn, ô tìm tên luôn hiện, CTA tìm kiếm dễ nhận biết; giữ nguyên bonus, 3 reaction, gửi lại 10B4, finale và photo upload.


## V24 — CONTENT REWORK
- 40 thư học sinh: mỗi câu mở đầu có lý do và được viết khác nhau, giữ đúng tên gọi hiện có của từng thư.
- Làm mới phần lời chúc để giảm lặp từ, giảm câu vòng và ưu tiên câu ngắn, rõ, tự nhiên hơn.
- Giữ nguyên thư cô Hằng.
- Giữ nguyên các tính năng V23: tìm tên, 40 trái tim, thư cô, ảnh trong thư, bonus, 3 phản hồi, gửi lại 10B4, finale.


## V25 — Nội dung lời chúc
- Giữ 40 câu mở đầu cá nhân hóa từ V24.
- Viết lại phần lời chúc của cả 40 thư theo hướng dài hơn, có ý rõ ràng và giàu hình ảnh hơn.
- Hạn chế lặp các cụm “mong”, “chúc”, “những ngày”, tránh câu chung chung hoặc khó hiểu.
- Giữ riêng thư cô Hằng.
