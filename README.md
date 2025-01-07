1. Chuẩn bị ban đầu
Chọn một workflow: Quyết định sử dụng mô hình làm việc (Gitflow, Feature Branching, hoặc Trunk-based Development).
Thiết lập repository:
Một thành viên tạo repository trên GitHub và cấu hình quyền truy cập (Collaborators/Teams).
Cấu hình các nhánh chính:
main hoặc master: Chứa mã nguồn chính, đã ổn định.
develop (nếu dùng Gitflow): Chứa mã nguồn đang được phát triển.
Đồng bộ công cụ: Đảm bảo các thành viên cài đặt Git, biết cách dùng GitHub, và có công cụ phù hợp (IDE, terminal, Git GUI, v.v.).
2. Phân công công việc
Lập kế hoạch công việc:
Tạo issues (vấn đề) trên GitHub để quản lý từng task.
Sử dụng GitHub Projects hoặc bảng Kanban (Board) để quản lý tiến độ.
Gắn nhãn (Labels) cho các issues (bug, feature, documentation, v.v.).
Assign (phân công) từng issue cho thành viên.
3. Phát triển tính năng (Feature Development)
Tạo nhánh làm việc:
Mỗi thành viên tạo một nhánh mới từ main hoặc develop:
bash
Sao chép mã
git checkout -b feature/ten-chuc-nang
Thực hiện thay đổi:
Code và kiểm tra các thay đổi trên nhánh riêng.
Commit thường xuyên với thông điệp rõ ràng:
bash
Sao chép mã
git commit -m "Mô tả thay đổi ngắn gọn"
Push lên GitHub:
Đẩy nhánh lên repository:
bash
Sao chép mã
git push origin feature/ten-chuc-nang
