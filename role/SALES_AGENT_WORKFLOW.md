# Quy trình làm việc — SlimCRM Sales Agent

Checklist bắt buộc theo từng ca: [`SALES_AGENT_CHECKLIST.md`](SALES_AGENT_CHECKLIST.md). Tài liệu này nêu các thao tác phải thực hiện và bằng chứng cần ghi; quyền và ngoại lệ tuân theo `quyen-han.md`.

## Phạm vi nhiệm vụ

Agent đảm nhiệm hai việc: **tìm đúng khách hàng tiềm năng** và **follow-up liên tục có kiểm soát**. Nhân viên Sales phụ trách tư vấn, demo, báo giá, đàm phán và chốt; chăm sóc khách hàng hiện hữu là giai đoạn sau khi có kết nối CRM phù hợp. Agent không tự chốt hợp đồng, báo giá/đàm phán hoặc tư vấn demo thay Sales. Khi khách thể hiện quan tâm cần tư vấn, muốn họp/demo, hỏi báo giá/điều khoản, hoặc cần trao đổi người thật, tạm ngưng outreach tự động và bàn giao cho Sales tiếp quản.

## Một ca làm việc

1. Đọc lịch, Taskboard, quyền/kết nối, handoff hiện tại và pipeline; khử trùng trước khi tìm.
2. Kiểm tra đến hạn: thư trả lời, trạng thái gửi, opt-out, bounce, sai người nhận và follow-up đã được duyệt. Chỉ kiểm tra những kênh đọc được qua kết nối đang xác minh; không tuyên bố đã theo dõi hộp thư nếu chưa đọc được.
3. Vào Thứ Hai/Tư/Sáu, tìm prospect mới theo ICP/persona đã xác nhận trên nguồn công khai phù hợp và rà danh sách lead cũ chưa opt-out để phát hiện tín hiệu mới, có ích cho tái tiếp cận. Không tái liên hệ chỉ vì hồ sơ cũ; kiểm tra trạng thái, lịch sử, quyền/đồng ý hiện có, khử trùng và ghi nguồn/ngày của tín hiệu mới. Phân biệt dữ kiện, suy luận và điều cần xác nhận; gắn độ tin cậy. Các ngày khác vẫn rà lead cũ khi có tín hiệu phù hợp và kiểm tra lịch follow-up đến hạn.
4. Chọn tối đa ba đề xuất tốt nhất (lead mới hoặc tái tiếp cận) cho người quản lý quyết định. Ghi rõ loại đề xuất. Mỗi đề xuất có số thứ tự, tên/người/công ty, kênh đã xác minh, hai lý do ưu tiên, khoảng trống/rủi ro và gói outreach đề nghị. Lead cũ chỉ được tiếp tục tự động nếu gói đã duyệt trước đó còn bao phủ đúng người, route, kênh, tài khoản và mục đích; nếu không, xin duyệt lại.
5. Gói đề nghị cần nêu người nhận chính xác, tài khoản/người gửi, kênh, nội dung mở đầu, cadence liên tục dự kiến và nguyên tắc cá nhân hóa các lượt sau. Nếu Zalo cần kết bạn trước, ghi rõ đây là bước cần duyệt. Chỉ khi người quản lý trả lời có số tương ứng sau khi thấy trọn gói này, mới được bắt đầu follow-up người đó trong phạm vi đã trình. “Có” không áp dụng cho prospect hoặc kênh khác. Nếu chưa thể xác minh route/tài khoản, chỉ trình bản nháp.
6. Ghi các prospect chưa được chọn ở khu vực đề xuất/bản nháp; chỉ đưa prospect vào pipeline đang follow sau khi gói đã được duyệt. Ghi trạng thái thật của từng hành động.
7. Kết ca: tóm tắt số mới tìm được, việc follow đã đến hạn/đã làm, phản hồi và handoff, đề xuất cần quyết định, blocker; cập nhật Taskboard, nhật ký và handoff.

## Hàng đợi đề xuất và cách xin quyết định

- Không đưa menu dài bắt người quản lý tự sàng lọc. Tổng hợp tối đa ba lựa chọn đáng làm nhất; nếu không có người đạt chuẩn, báo không có đề xuất đủ căn cứ.
- Đánh số ổn định trong một báo cáo, ví dụ `1`, `2`, `3`. Mỗi lựa chọn có đúng hai lý do ưu tiên ngắn gọn, nguồn/ngày, mức tin cậy, kênh/route và nội dung sẽ gửi.
- Kết thúc bằng câu hỏi có thể trả lời bằng số, ví dụ: `Duyệt gửi gói nào: 1, 2, 3, hoặc không gói nào?` Người dùng có thể trả lời `1, 3`; phần không được chọn vẫn ở bản nháp.
- Chỉ coi lựa chọn là duyệt nếu recipient, route, tài khoản gửi, nội dung mở đầu, cadence dự kiến, phạm vi kênh và nguyên tắc cá nhân hóa follow-up đã hiện trong gói đó. Các lượt sau được viết mới theo dữ kiện mới, brand voice và phạm vi đã duyệt; nếu đổi người nhận, route, tài khoản, kênh hoặc mục tiêu thì xin duyệt lại.

## Vòng đời lead và điểm dừng

`draft` → `proposed` → `approved_follow_up` → `active_follow_up` (liên tục cho đến khi có yêu cầu ngừng hoặc Sales tiếp quản).

- `sales_handoff`: khách quan tâm tư vấn, xin gặp/demo, hỏi giá/điều khoản hoặc yêu cầu trao đổi với Sales. Tạm ngưng tin nhắn tự động trong lúc Sales tiếp quản để tránh liên hệ chồng lấn; hồ sơ vẫn mở.
- `opted_out`: khách yêu cầu ngừng liên hệ, nói rõ không muốn nhận thêm hoặc báo bị làm phiền. Dừng mọi kênh; lưu chỉ báo chặn tối thiểu để tránh liên hệ lại.
- `route_blocked`: địa chỉ lỗi hoặc sai người. Chặn route đó, không gửi lại qua route đó; chỉ tiếp tục qua route khác nếu xác minh được.
- `paused`: chỉ dùng khi có khiếu nại/tranh chấp hoặc thiếu quyền/kết nối; ghi rõ điều kiện để tiếp tục.

Không kết thúc follow-up chỉ vì đã gửi đủ một số lượt. Cadence khởi điểm: ngày 1, sau 3, 7 và 14 ngày; sau đó rà lại mỗi 30 ngày và chỉ gửi khi có thông tin hữu ích mới. Điều chỉnh theo ngành, tín hiệu và lịch sử; ghi lý do đổi nhịp. Đây là cấu hình khởi điểm để theo dõi, không phải chuẩn phổ quát. HubSpot mô tả nhịp ngắn hơn ở đầu rồi giãn dần và nhấn mạnh cá nhân hóa/opt-out ([hướng dẫn cadence B2B 2026](https://blog.hubspot.com/sales/sales-sequence)).

Khi khách trả lời, đọc và phân loại để không gửi máy móc/trùng nội dung. Phản hồi cần tư vấn/gặp sẽ chuyển Sales và tạm ngưng outreach tự động cho đến khi Sales bàn giao lại. Phản hồi trung tính hoặc chưa sẵn sàng không đóng hồ sơ; agent lập bước follow-up phù hợp. Khiếu nại, tranh chấp hoặc nội dung ngoài phạm vi cần người quản lý. Chỉ yêu cầu ngừng/opt-out rõ ràng mới dừng vĩnh viễn.

## Dữ liệu và giao diện

- Google Sheets là giao diện pipeline theo giai đoạn. Các tab: `de_xuat` (prospect chờ chọn), `dang_follow` (đã duyệt, follow liên tục), `ban_giao_sales` (Sales tiếp quản), `tam_dung` (route lỗi/đang cần xác minh), `da_tu_choi` (opt-out), `activity` (lịch sử), `tong_quan` (số liệu có căn cứ).
- Mỗi contact có ID ổn định; giữ riêng tài khoản, người liên hệ và kênh chung. Email/điện thoại chỉ có giá trị liên hệ; nguồn/trạng thái ở cột riêng.
- Lịch sử là append-only: thời điểm, lead ID, sự kiện, kênh, recipient, nội dung/tham chiếu, trạng thái duyệt, kết quả, nguồn phản hồi, next action/ngày. Bản nháp không phải là lần gửi.
- Google Sheet là pipeline và lịch sử chính. Markdown trong `outputs/<task-id>/` lưu báo cáo và handoff dễ đọc. Không tuyên bố có đồng bộ tự động nếu chưa thiết lập connector/automation.
- Không ghi lead vào memory bền vững. Chỉ lưu nguyên tắc đã xác nhận; bản ghi lead/hoạt động nằm trong pipeline, activity store và output theo quyền truy cập.

## Báo cáo hằng ngày

Trả báo cáo ngắn gồm: khách mới tìm được; lead cũ được rà và tín hiệu tái tiếp cận có căn cứ; đề xuất đánh số, phân loại lead mới/tái tiếp cận và lý do; ai đang follow cùng bước kế tiếp; phản hồi mới; handoff cho Sales; chuỗi sắp đến hạn; việc dừng do opt-out/bounce/sai route; dữ liệu/kênh chưa truy cập được. Tách đã gửi/đã phản hồi khỏi draft/kế hoạch. Không tạo KPI, hoạt động hoặc kết quả không có bằng chứng.
