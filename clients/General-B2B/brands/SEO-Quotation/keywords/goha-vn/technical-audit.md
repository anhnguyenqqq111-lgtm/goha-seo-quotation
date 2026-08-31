# Technical SEO audit — goha.vn

## Scorecard sơ bộ

| Hạng mục | Điểm (/10) | Trạng thái | Ghi chú |
|---|---:|---|---|
| Core Web Vitals | 5 | 🟡 | Chưa có PageSpeed export; cần đo mobile/desktop theo template và URL quan trọng |
| Mobile-friendly | 7 | 🟡 | Cấu trúc trang và form hiện diện; cần kiểm tra tap target, CLS, popup trên thiết bị thật |
| Indexing/crawlability | 7 | 🟡 | Website có nhiều URL nội dung; cần xác nhận robots, sitemap, canonical và URL phân trang |
| Schema | 6 | 🟡 | Có cấu trúc nội dung/TOC; cần kiểm tra JSON-LD thực tế và lỗi rich result |
| HTTPS/security | 9 | 🟢 | Website sử dụng HTTPS; chưa có bằng chứng mixed-content trong dữ liệu thu thập |
| **Tổng technical** | **34/50** | **🟡** | Cần crawl và PageSpeed trước khi triển khai sửa lỗi |

## Phát hiện ưu tiên

1. Chuẩn hóa canonical, sitemap và nhóm URL cũ/biến thể; GSC có nhiều truy vấn dạng URL path và anchor cho cùng bài, cần kiểm tra phân mảnh tín hiệu.
2. Kiểm tra title/H1/meta cho các URL dịch vụ SEO, SEO AI/AIO và Maps để tránh cạnh tranh nội bộ.
3. Kiểm tra schema Organization, WebSite, BreadcrumbList, Article và FAQ; chỉ dùng FAQ schema khi nội dung hiển thị đúng trên trang.
4. Chạy PageSpeed Insights cho homepage, trang dịch vụ SEO, AIO, báo giá và một bài blog nặng hình ảnh.
5. Kiểm tra liên kết nội bộ từ các bài có impressions cao (`backlink`, `schema`, `SEO AI là gì`) về landing page dịch vụ.
