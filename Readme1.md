# 🛠️ Clement-AutoCAD
> **Phiên bản áp dụng:** AutoCAD Mechanical 2022

![AutoCAD](https://img.shields.io/badge/Tools-AutoCAD_Mechanical-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Learning-green?style=flat-square)
![Author](https://img.shields.io/badge/Author-Clement-blue?style=flat-square)

---

## 📑 MỤC LỤC (TABLE OF CONTENTS)
*(Click vào dòng dưới để nhảy đến mục cần xem)*

1. [⚡ Quy tắc vận hành chung](#quytac)
2. [🛠️ Nhóm 1: Cài đặt & Hỗ trợ (Setup)](#group1)
3. [✏️ Nhóm 2: Công cụ Vẽ (Draw)](#group2)
4. [✂️ Nhóm 3: Công cụ Chỉnh sửa (Modify)](#group3)
5. [📝 Nhóm 4: Text & Ký tự đặc biệt](#group4)
6. [📏 Nhóm 5: Kích thước (Dimension)](#group5)
7. [📦 Nhóm 6: Block & Quản lý](#group6)
8. [🔍 Nhóm 7: Thống kê & Hiển thị](#group7)

---

<a name="quytac"></a>
## ⚡ QUY TẮC VẬN HÀNH CHUNG
* Luôn để ngôn ngữ là ENG khi thao tác để không bị lỗi khi nhập lệnh.
* **Phím SPACE (Cách) = ENTER:** Ngón cái tay trái luôn đặt ở phím Space để gọi lệnh nhanh.
* **Lặp lại lệnh:** Nhấn Space/Enter khi không có lệnh nào -> Gọi lại lệnh vừa dùng.
* **Thoát lệnh:** Luôn nhấn `ESC` (2-3 lần) để hủy bỏ lệnh cũ trước khi nhập lệnh mới.
* **Bảng Setup (Dialog):** Nếu lệnh hiện bảng cài đặt, nhập số trực tiếp vào bảng hoặc gõ `D` để bật/tắt bảng này.

---

<a name="group1"></a>
## 🛠️ Nhóm 1: Cài đặt & Hỗ trợ vẽ (Setup & Aids)
*Các phím chức năng dùng liên tục trong quá trình vẽ.*

| Lệnh / Phím | Phím Tắt | Chức Năng | Ghi chú |
| :--- | :--- | :--- | :--- |
| **ORTHO** | `F8` | Chế độ vẽ thẳng góc | Bật liên tục để vẽ ngang/dọc |
| **DYNAMIC INPUT**| `F12` | Hiển thị & Nhập liệu | Nhập số cạnh con trỏ chuột |
| **CHUYỂN Ô** | `TAB` | Chuyển đổi nhập liệu | Chuyển giữa ô Chiều dài <-> Ô Góc (khi bật F12) |
| **TỌA ĐỘ CỰC** | `@L<A` | Nhập độ dài và góc | Ví dụ: `@100<45` |
| **POLAR** | `F10` | Chế độ vẽ theo tia | Vẽ xiên theo góc 30, 45... |
| **MVSETUP** | `MVSETUP` | Thiết lập khổ giấy | Chọn No -> Metric -> Tỉ lệ (Chỉ dùng lúc đầu) |
| **LINEWEIGHT** | `LWDISPLAY`| Hiển thị độ dày nét | Bật lên mới thấy nét đậm/nhạt |
| **ZOOMFACTOR** | `ZOOMFACTOR`| Tốc độ lăn chuột | Khuyên dùng: 60 - 100 |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group2"></a>
## ✏️ Nhóm 2: Công cụ Vẽ (Draw - Group A)
*Các lệnh tạo hình cơ bản, sắp xếp theo độ phổ biến.*

| Lệnh | Phím Tắt | Chức Năng | Ghi chú quan trọng |
| :--- | :--- | :--- | :--- |
| **LINE** | `L` | Vẽ đường thẳng rời. | Lệnh dùng nhiều nhất |
| **CIRCLE** | `C` | Vẽ hình tròn. | |
| **RECTANGLE** | `REC` | Vẽ hình chữ nhật. | `F`: Bo tròn (Fillet)<br>`M`: Vát mép (chaMfer)<br>`D`: Bảng cài đặt (Dialog) |
| **POLYLINE** | `PL` | Vẽ đa tuyến liền mạch. | Các nét dính liền nhau |
| **ARC** | `A` | Vẽ cung tròn. | |
| **POLYGON** | `POL` | Vẽ đa giác đều. | `I`: Nội tiếp, `C`: Ngoại tiếp |
| **HATCH** | `H` | Tô vật liệu (Mặt cắt). | |
| **ELLIPSE** | `EL` | Vẽ hình Bầu dục. | |
| **XLINE** | `XL` | Vẽ đường dóng vô tận. | Dùng để dựng hình chiếu |
| **MULTILINE** | `ML` | Vẽ 2 nét song song. | Dùng vẽ tường nhà |
| **DIVIDE** | `DIV` | Chia đoạn thẳng đều nhau. | Rải điểm point |
| **MEASURE** | `ME` | Chia đoạn theo độ dài. | |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group3"></a>
## ✂️ Nhóm 3: Công cụ Chỉnh sửa (Modify - Group B)
*Các lệnh sửa hình, lệnh nào dùng nhiều để lên trên.*

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ERASE** | `E` | Xóa đối tượng. |
| **TRIM** | `TR` | Cắt xén phần thừa. |
| **MOVE** | `M` | Di chuyển đối tượng. |
| **COPY** | `CO` / `CP`| Sao chép đối tượng. |
| **OFFSET** | `O` | Copy song song (tạo tường/viền). |
| **MIRROR** | `MI` | Lấy đối xứng (Soi gương). |
| **FILLET** | `F` | Bo tròn góc (`R` nhập bán kính). |
| **ROTATE** | `RO` | Xoay hình. |
| **EXTEND** | `EX` | Phóng dãn đường tới đích. |
| **SCALE** | `SC` | Phóng to / Thu nhỏ tỷ lệ. |
| **STRETCH** | `S` | Kéo dãn hình (Quét chuột phải sang trái). |
| **MATCH PROP** | `MA` | Copy thuộc tính (Layer/Màu). |
| **ARRAY** | `AR` | Copy mảng (Hàng cột/Vòng tròn). |
| **CHAMFER** | `CHA` | Vát mép góc. |
| **JOIN** | `J` | Nối các nét rời thành 1 nét liền. |
| **BREAK** | `BR` | Ngắt đoạn thẳng tại 2 điểm. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group4"></a>
## 📝 Nhóm 4: Text & Ký tự đặc biệt (Group C)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **DTEXT** | `DT` | Viết chữ đơn dòng (Nhanh). |
| **MTEXT** | `MT` / `T` | Viết đoạn văn bản (Nhiều dòng). |
| **EDIT** | `ED` | Sửa nội dung chữ/số. |
| **TEXT STYLE** | `ST` | Cài đặt Font chữ. |
| **FIND** | `FIND` | Tìm và thay thế chữ. |

**Bảng mã ký tự (Gõ khi viết text):**
* `%%C` : Ø (Đường kính)
* `%%P` : ± (Cộng trừ)
* `%%D` : ° (Độ)
* `%%U` : Gạch chân

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group5"></a>
## 📏 Nhóm 5: Kích thước (Dimension - Group D)

| Lệnh | Phím Tắt | Chức Năng | Lưu ý |
| :--- | :--- | :--- | :--- |
| **LINEAR** | `DLI` | Đo thẳng (Ngang/Dọc) | Dùng nhiều nhất |
| **ALIGNED** | `DAL` | Đo đường xiên/chéo | Dùng cho cạnh nghiêng |
| **CONTINUE** | `DCO` | Đo nối tiếp | Cần có 1 Dim gốc trước |
| **RADIUS** | `DRA` | Đo bán kính (R) | |
| **DIAMETER** | `DDI` | Đo đường kính (Ø) | |
| **ANGULAR** | `DAN` | Đo góc độ | |
| **DIMSTYLE** | `D` | Cài đặt kiểu đo | Chỉnh Text, Arrow, Unit |
| **BASELINE** | `DBA` | Đo song song | Đo từ 1 mốc chuẩn |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group6"></a>
## 📦 Nhóm 6: Block & Quản lý (Group E)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **BLOCK** | `B` | Đóng gói đối tượng thành khối. |
| **EXPLODE** | `X` | Phá khối (Nổ) ra thành nét rời. |
| **PASTEBLOCK**| `Ctrl+Shift+V` | Dán thành Block ngay lập tức. |
| **REFEDIT** | `REF` | Sửa khối tại chỗ. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group7"></a>
## 🔍 Nhóm 7: Thống kê & Hiển thị (Group F)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ZOOM EXTENTS**| `Z` -> `E` | Zoom toàn bộ hình vừa màn hình. |
| **ZOOM WINDOW** | `Z` -> `W` | Zoom vùng chọn. |
| **DISTANCE** | `DI` | Đo khoảng cách X, Y nhanh. |
| **AREA** | `AA` | Tính diện tích/Chu vi. |
| **ZOOM ALL** | `Z` -> `A` | Zoom tất cả không gian giấy. |
| **PURGE** | `PU` | Dọn rác, làm nhẹ bản vẽ. |
| **LIST** | `LI` | Xem thông tin chi tiết đối tượng. |

---
*Created by Clement - 2026*
