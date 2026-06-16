# 📊 Kế hoạch Quảng cáo META: Menu nhà hàng

**Ngày tạo:** 16/06/2026 15:14:28

---

# 📱 KẾ HOẠCH META ADS — MENU NHÀ HÀNG
**In ấn Thành Trung | Budget: 300,000 VNĐ | Duration: 7 ngày | Mục tiêu: Sales (Lead → Inbox)**

---

## ⚠️ LƯU Ý TRƯỚC KHI SETUP

> Các ô **[cần bạn cấp]** = số liệu bạn phải điền trước khi publish. Tất cả phần còn lại có thể setup ngay.

---

## 1. CAMPAIGN STRUCTURE

### 🏗️ Sơ đồ tổng thể

```
CAMPAIGN: TTTUNG_MENU_SALES_W[số tuần]
├── Budget: 300,000 VNĐ / 7 ngày (~42,857 VNĐ/ngày)
├── Objective: LEADS (Tin nhắn Messenger)
├── Buying Type: Auction
│
├── AD SET 1: "F&B Hà Nội — Nỗi đau menu" (180k — 60%)
│   ├── Ad 1A: Creative Hook "Menu màu lệch"
│   └── Ad 1B: Creative Hook "Khai trương gấp"
│
└── AD SET 2: "F&B Hà Nội — Retarget Engager" (120k — 40%)
    └── Ad 2A: Creative "Proof + CTA mạnh"
```

---

### 📋 Chi tiết Campaign

| Trường | Giá trị |
|--------|---------|
| **Campaign Name** | `TTTUNG_MENU_SALES_W[XX]_[THÁNG]` |
| **Objective** | Engagement → Tin nhắn (Messenger) |
| **Budget Type** | Campaign Budget Optimization (CBO) TẮT — chia thủ công |
| **Total Budget** | 300,000 VNĐ |
| **Schedule** | Đặt ngày bắt đầu cụ thể, chạy 7 ngày liên tục |
| **Bid Strategy** | Lowest Cost (không đặt bid cap — budget quá nhỏ) |
| **Special Ad Category** | Không chọn |

> **Lý do chọn Messenger objective:** Khách F&B quen inbox hỏi trực tiếp; chốt đơn qua chat nhanh hơn form; phù hợp OPC xử lý từng đơn.

---

## 2. AD SETS CHI TIẾT

### 📦 AD SET 1 — "F&B Hà Nội — Cold Audience"

**Tên:** `ADSET1_COLD_HANOI_FB_[THÁNG]`
**Budget:** 180,000 VNĐ / 7 ngày (~25,700 VNĐ/ngày)

#### 🎯 Audience Targeting

```
📍 LOCATION
├── Hà Nội (toàn thành phố)
├── Bán kính: Không thu hẹp thêm
└── Chế độ: Người sống tại đây (không bao gồm khách du lịch)

👤 DEMOGRAPHICS
├── Age: 24 – 45
├── Gender: Tất cả
└── Language: Tiếng Việt

🎯 DETAILED TARGETING (Interests)
├── [NHÓM 1 — Ngành F&B]
│   ├── Nhà hàng (Restaurants)
│   ├── Quán cà phê (Cafes)
│   ├── Kinh doanh thức ăn (Food business)
│   ├── Đồ uống (Beverages)
│   └── Ẩm thực đường phố (Street food)
│
├── [NHÓM 2 — Hành vi chủ kinh doanh]
│   ├── Small business owners
│   ├── Khởi nghiệp (Entrepreneurship)
│   └── Self-employed
│
└── [NHÓM 3 — Behavior]
    ├── Facebook Page admins
    └── Engaged shoppers

⚙️ AUDIENCE SETTINGS
├── Narrow Audience: Bật
│   └── Phải khớp THÊM: Small business owners HOẶC Page admins
├── Exclude: Người đã nhắn tin Page trong 30 ngày
└── Audience Size mục tiêu: 50,000 – 300,000 người
```

#### 📐 Placement

```
✅ BẬT:
├── Facebook Feed (ưu tiên #1)
├── Facebook Stories
├── Instagram Feed (nếu có IG đã link)
└── Instagram Stories

❌ TẮT:
├── Audience Network (tất cả)
├── Facebook Marketplace
├── Facebook Right Column
├── Messenger Inbox placement
└── Reels (video chưa có — tắt để tránh lãng phí)
```

#### 💰 Bid & Optimization

| Trường | Giá trị |
|--------|---------|
| **Optimization for** | Conversations (Messenger) |
| **Bid Strategy** | Lowest Cost |
| **When You Get Charged** | Impression |
| **Ad Scheduling** | Tất cả giờ (không chặn — budget nhỏ, không nên thu hẹp thêm) |

---

### 📦 AD SET 2 — "Retarget Engager / Warm Audience"

**Tên:** `ADSET2_WARM_ENGAGER_[THÁNG]`
**Budget:** 120,000 VNĐ / 7 ngày (~17,100 VNĐ/ngày)

> ⚠️ **Điều kiện:** Ad Set này chỉ hiệu quả nếu Page đã có engagement (like/comment/share bài) từ trước. Nếu Page mới hoàn toàn → gộp toàn bộ 300k vào Ad Set 1.

#### 🎯 Audience Targeting

```
📍 LOCATION: Hà Nội (giữ nguyên)

👤 DEMOGRAPHICS
├── Age: 24 – 45
└── Gender: Tất cả

🔁 CUSTOM AUDIENCE (tạo trước trong Audiences)
├── Tên: "CA_PageEngage_90days"
├── Source: Facebook Page của bạn
├── Event: Tất cả người đã tương tác với Page trong 90 ngày
│   (bao gồm: xem video, like bài, comment, share, click CTA)
└── Duration: 90 ngày

➕ LOOKALIKE (nếu Custom Audience < 1,000 người → bỏ qua)
└── Chưa cần — budget quá nhỏ để chạy LAL hiệu quả

⚙️ AUDIENCE SETTINGS
└── Exclude: Người đã nhắn tin Page 30 ngày (giống Ad Set 1)
```

#### 📐 Placement

```
✅ BẬT:
├── Facebook Feed
└── Facebook Stories

❌ TẮT: Tất cả còn lại (tập trung reach đúng người)
```

---

## 3. AD CREATIVES

### 🎨 Ad 1A — "Hook: Menu Màu Lệch" *(Cold — chạy trong Ad Set 1)*

**Tên Ad:** `AD1A_HOOK_MAULECH_[THÁNG]`
**Format:** Single Image hoặc Carousel 2 ảnh (Before/After)

---

#### 📝 Primary Text (copy chính)

```
Bạn chi tiền chụp ảnh món đẹp — rồi in ra màu lệch hết.

Khách cầm menu lên, nhìn ảnh gà rán màu xám xịt, đặt xuống.
Không phải vì món không ngon — mà vì menu không kích thích.

Tụi mình in menu cho quán F&B ở Hà Nội.
Trước khi in, kiểm tra màu CMYK + font — không để khách nhận hàng mới phát hiện lỗi.

✅ Giao 2–3 ngày (gấp có thể 24h)
✅ In số lượng nhỏ được — không ép mua nhiều
✅ Chất liệu chống dầu mỡ, không bong laminate

Nhắn tin để nhận báo giá + tư vấn chất liệu phù hợp với quán bạn.
```

**Headline:** `Menu in màu đúng như ảnh gốc — giao 2–3 ngày tại Hà Nội`

**Description (dòng phụ):** `Tư vấn miễn phí chất liệu chống dầu cho quán F&B`

**CTA Button:** `Gửi tin nhắn` (Send Message)

---

#### 🖼️ Visual Recommendation (Ad 1A)

```
OPTION A — Before/After (hiệu quả nhất):
├── Ảnh TRÁI: Menu cũ (màu nhợt,

---

**Ghi chú:** Kế hoạch tự động tạo bởi Ads Agent
