# NgocLinh AI Video Template

Template tạo video tự động bằng [Remotion](https://www.remotion.dev/) — dùng React và TypeScript để tạo nội dung cho TikTok, YouTube Shorts và Reels.

## Tác giả
**Ngoc Linh**

## Tính năng
- **Tạo video bằng code**: Video được tạo bằng React và TypeScript.
- **Tailwind CSS**: Tạo kiểu nhanh và nhất quán.
- **Tối ưu cho TikTok/Shorts**: Tỷ lệ khung hình 9:16 (1080x1920) kèm khoảng đệm "Safe Zone".
- **Components**: Các slide có thể tái sử dụng cho nội dung kỹ thuật giáo dục.

## Các composition có sẵn
1. **LinuxFileSystem**: Video dọc 50 giây giải thích cấu trúc thư mục Linux.
2. **DockerIntro**: Video dọc giới thiệu các khái niệm về Docker.

## Cài đặt

```bash
git clone https://github.com/ngoclinhdayrui168/ngoclinhai.git
cd ngoclinhai
npm install
```

## Sử dụng

Khởi động Preview Studio:

```bash
npm run dev
```

Render video:

```bash
npx remotion render LinuxFileSystem
npx remotion render DockerIntro
```

## Giấy phép
MIT License.
