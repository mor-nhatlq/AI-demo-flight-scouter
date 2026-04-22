# AI-demo-flight-scouter

Tài liệu training nội bộ ghi lại quá trình xây dựng **FlightScouter** — một PoC tìm kiếm chuyến bay bằng React — trong một phiên hội thoại AI duy nhất (~45 phút).

## Live demo

👉 **https://mor-nhatlq.github.io/AI-demo-flight-scouter/**

Trang walkthrough đính kèm một bản compile tương tác của app. Bạn có thể:

- Chọn điểm đi / điểm đến từ danh sách 50 sân bay (autocomplete)
- Chọn ngày đi / ngày về, toggle round-trip
- Xem danh sách chuyến bay được generate bằng seeded random
- Lọc theo hãng, sort theo giá
- Xem **dự báo thời tiết thật** tại điểm đến (API Open-Meteo, không cần key)

## Nội dung walkthrough

9 mục:

1. **Bài toán** — mục đích, khán giả, stack, dữ liệu
2. **Quy trình** — 6 bước từ brainstorm đến refactor
3. **Các prompts** — 12 prompt gốc (tiếng Việt), kèm ý định / skill / kết quả / bài học
4. **Skills** — 10 skill được dùng và mục đích
5. **Subagents** — 4 subagent và vai trò
6. **Bài học** — 10 thói quen prompting
7. **Timeline** — 17 mốc thời gian
8. **Tái hiện** — playbook 10 bước
9. **Thành phẩm** — cây file AI đã tạo

## Mục đích

Training đội pre-sales / engineering cách:

- Prompt AI hiệu quả (WHY trước WHAT)
- Chọn skill và subagent phù hợp
- Audit plan trước khi thực thi
- Pivot giữa build mà không mất công
- Tự document phiên làm việc

## Files

- `index.html` — trang walkthrough + live demo (truy cập qua GitHub Pages)
- `session-walkthrough.html` — bản copy cùng nội dung, giữ nguyên tên gốc

Đây là một file HTML duy nhất, self-contained (ngoài Google Fonts CDN). Có thể mở trực tiếp bằng trình duyệt, hoặc host ở bất cứ đâu.
