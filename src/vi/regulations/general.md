# QUY CHẾ TỔ CHỨC VÀ VẬN HÀNH DỰ ÁN GDVN

## MỤC LỤC

- **CHƯƠNG I: PHẠM VI ÁP DỤNG VÀ ẢNH HƯỞNG**
    - Điều 1. Không gian & Nền tảng quản lý
    - Điều 2. Đối tượng chi phối
    - Điều 3. Giới hạn thẩm quyền & Quyền sở hữu
- **CHƯƠNG II: NHỮNG QUY ĐỊNH CHUNG**
    - Điều 4. Mục tiêu & Nguyên tắc cốt lõi
    - Điều 5. Chiến lược "Tài sản hóa" & Kháng đứt gãy
- **CHƯƠNG III: CƠ CẤU TỔ CHỨC VÀ NHÂN SỰ**
    - Điều 6. Cấu trúc Ban quản trị (Core Team)
    - Điều 7. Ma trận Phân quyền, Tuyến báo cáo & Mức độ ổn định nhân sự
    - Điều 8. Quy trình Tuyển dụng & Quản lý Nhóm Xoay vòng (Rotation)
- **CHƯƠNG IV: QUY TRÌNH VẬN HÀNH DỰ ÁN**
    - Điều 9. Quy trình tiếp nhận yêu cầu (Bug/Feature)
    - Điều 10. Quy trình Kỹ thuật (Dev Workflow)
    - Điều 11. Khung vận hành sự kiện
- **CHƯƠNG V: QUẢN TRỊ RỦI RO**
    - Điều 12. Các rủi ro cốt lõi & Biện pháp xử lý khẩn cấp
- **CHƯƠNG VI: PHỤ LỤC**
    - Điều 13. Biểu mẫu & Tiêu chuẩn

---

## CHƯƠNG I: PHẠM VI ÁP DỤNG VÀ ẢNH HƯỞNG

### Điều 1. Không gian & Nền tảng quản lý
Quy chế này có hiệu lực bắt buộc và chi phối toàn bộ các hoạt động vận hành, phát triển trên các tài sản số chính thức của GDVN, bao gồm nhưng không giới hạn:
1. **Hệ thống Kỹ thuật & Dữ liệu:** Website GDVN.net, hệ thống xếp hạng (Bảng xếp hạng Classic/Platformer/Challenge), các bản Mod Geode độc quyền, Bot Discord và toàn bộ cơ sở dữ liệu.
2. **Hệ thống Cộng đồng & Truyền thông:** Group Facebook GDVN (hạn chế), Server Discord GDVN và các kênh mạng xã hội chính thức khác.
3. **Kho Tài nguyên & Mã nguồn:** Các tổ chức (Organization) và kho lưu trữ (Repository) trên GitHub thuộc quyền sở hữu của Ban quản trị.

### Điều 2. Đối tượng chi phối
1. **Nhân sự nội bộ:** Áp dụng tuyệt đối đối với toàn bộ các cá nhân nằm trong Ma trận Nhân sự (Từ Project Lead, Tech Lead cho đến các vị trí xoay vòng như Developer, Trusted Player, Mod, CTV).
2. **Thành viên cộng đồng (End-users):** Chi phối cách thức cộng đồng tương tác với dự án (Quy định gửi/duyệt Record, quy trình báo cáo lỗi, đề xuất tính năng).

### Điều 3. Giới hạn thẩm quyền & Quyền sở hữu
1. **Ranh giới xử lý:** Ban quản trị chỉ tiếp nhận và giải quyết các sự cố, vi phạm, hoặc tranh chấp phát sinh **bên trong** các nền tảng được quy định tại Điều 1. Dự án từ chối can thiệp vào các mâu thuẫn cá nhân hoặc nền tảng bên thứ ba không thuộc quyền quản lý.
2. **Quyền sở hữu tài nguyên (Asset Ownership):** Để đảm bảo tính liên tục của dự án (kháng đứt gãy), mọi dòng code, cấu trúc dữ liệu, ấn phẩm thiết kế, video hoặc tài liệu do các cá nhân đóng góp trong thời gian giữ vai trò tại GDVN được mặc định là **tài sản chung của dự án**. Ban quản trị có toàn quyền lưu trữ, tái sử dụng, chỉnh sửa và phân phối lại ngay cả khi cá nhân đó đã rời khỏi tổ chức.
3. **Bảo vệ danh tiếng:** Bất kỳ nhân sự nào (kể cả nhóm xoay vòng) sử dụng danh nghĩa, chức danh của GDVN để hoạt động cá nhân gây ảnh hưởng xấu đến uy tín của cộng đồng đều sẽ bị tước quyền và cấm tham gia vĩnh viễn (Ban/Blacklist).

---

## CHƯƠNG II: NHỮNG QUY ĐỊNH CHUNG

### Điều 4. Mục tiêu & Nguyên tắc cốt lõi
1. **Bảo vệ Tech Lead (Solo Dev):** Trọng tâm của quy chế là ngăn chặn tình trạng kiệt sức (burnout) cho kỹ sư cốt lõi. Tuyệt đối loại bỏ các yêu cầu phát sinh qua tin nhắn cá nhân. Dev chỉ làm việc dựa trên tài liệu đặc tả (Issue) đã được phê duyệt.
2. **Hệ thống "Plug-and-play" (Cắm và chạy):** Chấp nhận tỷ lệ biến động nhân sự cao ở các vị trí phi quản trị (Designer, Editor, Contributor). Quy trình phải đảm bảo một người mới có thể tiếp quản công việc đang dang dở trong thời gian ngắn nhất.
3. **Cô lập luồng cốt lõi:** Các tính năng sống còn của nền tảng do Solo Dev độc quyền kiểm soát. Tiến độ dự án không được phép chờ đợi lực lượng Staff/Contributor.

### Điều 5. Chiến lược "Tài sản hóa" & Kháng đứt gãy
1. **Đóng gói thiết kế (Component-driven):** Từ bỏ việc thiết kế UI/UX độc bản cho mỗi tính năng mới. Tận dụng tối đa các thư viện giao diện (ví dụ: tái sử dụng các Svelte component) để "lắp ráp" giao diện. Thẩm mỹ nhường bước cho tốc độ và tính thực dụng.
2. **Template hóa truyền thông:** Xây dựng sẵn các kho tài nguyên (bộ template Figma/Canva có sẵn layout). Quản lý cộng đồng chỉ việc thay đổi văn bản/hình ảnh. Lập trình viên tuyệt đối không tham gia làm ấn phẩm truyền thông lặt vặt.
3. **Lưu trữ tập trung (Fail-safe):** Core Team nắm giữ toàn quyền quản trị các kho mã nguồn, file thiết kế gốc, database (như Supabase/MySQL). Cấm lưu trữ tài nguyên phân tán trên máy cá nhân của cộng tác viên.

---

## CHƯƠNG III: CƠ CẤU TỔ CHỨC VÀ NHÂN SỰ

### Điều 6. Cấu trúc Ban quản trị (Core Team)
Ban quản trị là những người nắm giữ tài nguyên cốt lõi và định hướng chiến lược.
1. **Project Lead (Trưởng Dự án):**
    - *Quyền hạn:* Toàn quyền kiểm soát và ra quyết định tối cao về định hướng của GDVN.
    - *Trách nhiệm:* Giải quyết các vấn đề vĩ mô, phê duyệt nhân sự cấp cao. Không can thiệp vào các tác vụ vi mô hàng ngày.
2. **Tech Lead (Phụ trách Kỹ thuật / Solo Dev):**
    - *Quyền hạn:* Nắm toàn quyền hệ thống Web, bot Discord, mod Geode. Có quyền **TỪ CHỐI** mọi yêu cầu không thông qua quy trình chuẩn (GitHub Issue).
    - *Trách nhiệm:* Đảm bảo uptime của hệ thống. Phân bổ công việc cho Developer (nếu có).
3. **Community & Staffing Lead (Phụ trách Cộng đồng & Nhân sự):**
    - *Quyền hạn:* Đại diện cho Ban quản trị phát ngôn trên FB/Discord. Được quyền đình chỉ công tác của các Mod/CTV vi phạm.
    - *Trách nhiệm:* Làm màng lọc bảo vệ Tech Lead. Quản lý trực tiếp nhóm Admin FB, Admin Discord và Admin Truyền thông.

### Điều 7. Ma trận Phân quyền, Tuyến báo cáo & Mức độ ổn định nhân sự

| Nhóm chức danh | Vị trí (Role) | Cấp trên trực tiếp | Tần suất xoay vòng (Độ ổn định) |
| :--- | :--- | :--- | :--- |
| **Core Team** | **Project Lead** | Không có | **Tuyệt đối ổn định** - Linh hồn dự án. |
| | **Tech Lead (Solo Dev)** | Project Lead | **Tuyệt đối ổn định** - SPOF của dự án. |
| | **Community & Staffing Lead** | Project Lead | **Rất ổn định** - Nắm giữ network nhân sự. |
| **Kỹ thuật** | **Developer** | Tech Lead | **Rất cao** - Chỉ làm việc qua GitHub Issue. |
| **Nội dung List** | **Admin List (Tổng)** | Project Lead | **Thấp** - Đòi hỏi chuyên môn sâu. |
| | **Admin Sub-List** | Admin List | **Trung bình** - Cần có backup dự phòng. |
| | **Admin Event** | Admin List | **Cao** - Hoạt động mạnh theo mùa giải. |
| | **Trusted Player** | Admin List | **Rất cao** - Tuyển liên tục qua form. |
| **Truyền thông** | **Admin Truyền thông** | Community Lead | **Trung bình** - Dùng template thiết kế sẵn. |
| | **Admin Group FB** | Community Lead | **Trung bình** - Dễ burnout vì toxic. |
| | **Admin Discord** | Community Lead | **Thấp** - Nắm quyền kỹ thuật server. |
| **Xoay vòng** | **Mod Discord** | Admin Discord | **Rất cao** - Sai phạm là cắt role ngay. |
| | **Cộng tác viên (CTV)** | Admin chuyên trách | **Rất cao** - Làm xong thu hồi quyền. |

### Điều 8. Quy trình Tuyển dụng & Quản lý Nhóm Xoay vòng (Rotation)
Quy trình tuân thủ nguyên tắc: **"Vào nhanh, thử nhanh, rụng nhanh nhưng không gây thiệt hại"**.
1. **Phễu tuyển dụng thường trực:** Duy trì Form đăng ký công khai. Khấu trừ đơn không có portfolio/thành tích.
2. **Sàng lọc chớp nhoáng:** Trao đổi 10-15 phút qua voice. Nói thẳng áp lực để lọc người thiếu cam kết.
3. **Bài kiểm tra vi mô (Micro-task Onboarding):** Giao 1 tác vụ nhỏ (VD: duyệt thử 3 record). Nếu "ghost" -> Thu hồi quyền ngay lập tức.
4. **Hồ chứa dự bị (Rotation Pool):** Cấp Role chính thức và chỉ ping khi có việc cụ thể.

---

## CHƯƠNG IV: QUY TRÌNH VẬN HÀNH DỰ ÁN

### Điều 9. Quy trình tiếp nhận yêu cầu (Bug/Feature)
1. **Khóa luồng cá nhân:** Admin/Dev không tiếp nhận tin nhắn cá nhân. Mọi yêu cầu phải đi qua kênh chung.
2. **Kênh tiếp nhận chính thức:** Discord (`#bug-report`/`#feature-request`) hoặc Google Form chính thức.
3. **Kiểm chứng (Triage):** Community Lead lọc trùng, dịch sang GitHub Issue và báo lại mã Ticket cho người dùng.

### Điều 10. Quy trình Kỹ thuật (Dev Workflow)
1. Tech Lead làm việc dựa trên bảng Kanban/Project của GitHub.
2. Chỉ xử lý các Issue đã được gắn nhãn (Label) và có Tiêu chí nghiệm thu (Acceptance Criteria).
3. Áp dụng CI/CD (GitHub Actions) để tự động kiểm tra code của Contributor. Code lỗi hệ thống tự động từ chối.

### Điều 11. Khung vận hành sự kiện
1. **Tiêu chí "Đủ dùng":** Nếu thiếu nhân sự Media, sử dụng lại template cũ. Ưu tiên sự kiện diễn ra đúng giờ hơn là thẩm mỹ.
2. **Điều phối nhân sự:** Staffing Lead huy động từ "Rotation Pool". Bắt buộc có tối thiểu 1 người dự phòng (Backup) cho các vị trí quan trọng trước giờ G.

---

## CHƯƠNG V: QUẢN TRỊ RỦI RO

### Điều 12. Các rủi ro cốt lõi & Biện pháp xử lý khẩn cấp
1. **Tech Lead vắng mặt:** Dự án chuyển sang trạng thái "Bảo trì tĩnh". Ngừng phát triển tính năng mới.
2. **Nhân sự xoay vòng "Ghost" sát deadline:** Kích hoạt quy trình dùng Template dự phòng. Không cố tìm người mới bù đắp ngay để tránh rủi ro bảo mật.
3. **Bão Spam Bug/Feature:** Khóa kênh chat report. Community Lead đăng thông báo xác nhận tình trạng để trấn an cộng đồng.

---

## CHƯƠNG VI: PHỤ LỤC

### Điều 13. Biểu mẫu & Tiêu chuẩn
1. **GitHub Issue Template:** Bối cảnh -> Các bước tái hiện -> Tiêu chí nghiệm thu.
2. **Quy tắc Onboarding siêu tốc:** Repository phải có hướng dẫn cài đặt môi trường dưới 3 bước.