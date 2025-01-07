
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
4. Code Review và Pull Request (PR)
Tạo Pull Request (PR):
Mở PR trên GitHub từ nhánh feature/ đến develop hoặc main.
Mô tả chi tiết thay đổi trong PR.
Kiểm tra PR:
Các thành viên khác review code, để lại nhận xét hoặc gợi ý sửa đổi.
Kiểm tra tự động bằng CI/CD (nếu có).
Merge nhánh:
Sau khi được chấp thuận, merge PR vào nhánh chính (sử dụng squash hoặc merge commit).
5. Kiểm tra và tích hợp
Kiểm tra tổng thể:
Chạy kiểm thử (manual hoặc automated tests).
Cập nhật tài liệu:
Đảm bảo README.md, changelog, hoặc tài liệu kỹ thuật được cập nhật.
6. Quản lý sự cố (Bug Fixing)
Tạo nhánh sửa lỗi:
Tạo nhánh hotfix/ten-loi từ main.
Sửa lỗi:
Commit, push, và mở PR tương tự như phát triển tính năng.
Merge nhanh:
Merge vào cả main và develop (nếu có nhánh develop).
7. Phát hành (Release)
Tạo phiên bản mới:
Sử dụng tags để đánh dấu phiên bản phát hành:
bash
Sao chép mã
git tag -a v1.0.0 -m "Phiên bản đầu tiên"
git push origin v1.0.0
Đóng các issues liên quan:
Liên kết PR hoặc commit với issue để tự động đóng.
8. Tổng kết và cải tiến
Đánh giá sau dự án:
Review quy trình làm việc và rút kinh nghiệm.
Cập nhật workflow:
Điều chỉnh quy trình nếu cần thiết.
