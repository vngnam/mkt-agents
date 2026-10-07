# CLAUDE.md — Marketing Agents (Vương Nam)

## Quy tắc bắt buộc

- **Mỗi khi tạo content marketing HOẶC cần hiểu thêm về người dùng → ĐỌC file [`Brand Voice DNA Vương Nam.md`](Brand%20Voice%20DNA%20Vương%20Nam.md)** (thư mục gốc project) TRƯỚC KHI viết. Đây là hiến pháp giọng nói thương hiệu (2 register Nam/anh, luật gai, hook đảo chiều, từ cấm, positioning). Không viết content thương hiệu mà chưa đọc file này.

## Bối cảnh người dùng

- Người dùng là **Vương Nam** — thương hiệu **Vương Kim Bảo** (phong thủy ứng dụng / Bát Tự có logic + đào tạo tư duy doanh nhân). KHÔNG phải niche AI/tech, dù project tên "Marketing Agents".
- Cốt lõi giọng: 2 register **"Nam"** (brand) / **"anh"** (thầy) — không pha trong 1 bài. Lăng kính "Nói ngược để thấy sự thật". Từ cấm: thức tỉnh · rung động · tần số vũ trụ · chữa lành · luật hấp dẫn. KHÔNG hứa doanh thu / "giàu sau X tháng"; tiết chế claim "năng lượng đá".

## Hệ thống content

- Bộ skill **Brendan Kane** (`.claude/skills/mkt-kane-*`, 17 skill) + agent orchestrator `mkt-brendan-kane-pipeline` — đã chỉnh sang persona Vương Nam.
- `mkt-kane-gsb-research-builder` có engine nghiên cứu tự động: YouTube qua **vidIQ** (đã kết nối), Facebook qua **Apify** (token ở `.claude/skills/mkt-kane-gsb-research-builder/.env`); tự phân Gold/Silver/Bronze + render HTML.
- Bộ skill viết Facebook cá nhân: `vuongnam-facebook-*`.
