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