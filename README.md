# 🛠️ MinhKySu-AutoCAD-Mastery
> Kho lưu trữ kiến thức, phím tắt và bài tập AutoCAD phục vụ lộ trình Kỹ sư Nhúng & Tự động hóa.

![AutoCAD](https://img.shields.io/badge/Tools-AutoCAD-red?style=flat-square)
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
* **Phím SPACE (Cách) = ENTER:** Trong AutoCAD, ngón cái tay trái luôn đặt ở phím Space để gọi lệnh nhanh.
* **Lặp lại lệnh:** Nhấn Space/Enter khi không có lệnh nào -> Gọi lại lệnh vừa dùng gần nhất.
* **Thoát lệnh:** Luôn nhấn `ESC` (2-3 lần) để hủy bỏ lệnh hiện tại trước khi nhập lệnh mới.
* **Chuột giữa (Đè xuống):** Pan (Kéo trượt màn hình).
* **Chuột giữa (Lăn):** Zoom in / Zoom out.

---

<a name="group1"></a>
## 🛠️ Nhóm 1: Cài đặt & Hỗ trợ vẽ (Setup & Aids)
*Các lệnh dùng để thiết lập môi trường và hỗ trợ quá trình đi nét.*

| Lệnh / Phím | Phím Tắt | Chức Năng | Ghi chú |
| :--- | :--- | :--- | :--- |
| **MVSETUP** | `MVSETUP` | Thiết lập khổ giấy | Chọn No -> Metric -> Tỉ lệ |
| **ORTHO** | `F8` | Chế độ vẽ thẳng góc | Chỉ vẽ ngang/dọc |
| **POLAR** | `F10` | Chế độ vẽ theo tia | Vẽ xiên theo góc 30, 45... |
| **DYNAMIC INPUT**| `F12` | Nhập liệu cạnh con trỏ | Nhấn TAB để chuyển ô |
| **LINEWEIGHT** | `LWDISPLAY`| Hiển thị độ dày nét | Bật lên mới thấy nét đậm |
| **ZOOMFACTOR** | `ZOOMFACTOR`| Tốc độ lăn chuột | Khuyên dùng: 60 - 100 |
| **TỌA ĐỘ CỰC** | `@L<A` | Nhập độ dài và góc | Ví dụ: `@100<45` |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group2"></a>
## ✏️ Nhóm 2: Công cụ Vẽ (Draw - Group A)
*Các lệnh tạo hình cơ bản.*

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **LINE** | `L` | Vẽ đường thẳng rời. |
| **POLYLINE** | `PL` | Vẽ đa tuyến liền mạch (Nét liền). |
| **XLINE** | `XL` | Vẽ đường dóng vô tận (Dùng dựng hình). |
| **MULTILINE** | `ML` | Vẽ 2 nét song song (Vẽ tường). |
| **RECTANGLE** | `REC` | Vẽ hình chữ nhật (`F` để bo góc, `C` vát mép). |
| **POLYGON** | `POL` | Vẽ đa giác đều (`I`: Nội tiếp, `C`: Ngoại tiếp). |
| **CIRCLE** | `C` | Vẽ hình tròn. |
| **ARC** | `A` | Vẽ cung tròn. |
| **ELLIPSE** | `EL` | Vẽ hình Bầu dục. |
| **HATCH** | `H` | Tô vật liệu (Mặt cắt). |
| **DIVIDE** | `DIV` | Chia đoạn thẳng thành n phần bằng nhau. |
| **MEASURE** | `ME` | Chia đoạn thẳng theo độ dài cho trước. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group3"></a>
## ✂️ Nhóm 3: Công cụ Chỉnh sửa (Modify - Group B)
*Các lệnh can thiệp, sửa đổi đối tượng.*

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ERASE** | `E` | Xóa đối tượng. |
| **COPY** | `CO` / `CP`| Sao chép. |
| **MIRROR** | `MI` | Lấy đối xứng (Soi gương). |
| **OFFSET** | `O` | Copy song song (tạo tường/viền). |
| **MOVE** | `M` | Di chuyển. |
| **ROTATE** | `RO` | Xoay hình. |
| **SCALE** | `SC` | Phóng to / Thu nhỏ tỷ lệ. |
| **STRETCH** | `S` | Kéo dãn hình (Quét chuột phải sang trái). |
| **TRIM** | `TR` | Cắt xén phần thừa. |
| **EXTEND** | `EX` | Phóng dãn đường tới đích. |
| **BREAK** | `BR` | Ngắt đoạn thẳng tại 2 điểm. |
| **JOIN** | `J` | Nối các nét rời thành 1 nét liền. |
| **FILLET** | `F` | Bo tròn góc (`R` nhập bán kính). |
| **CHAMFER** | `CHA` | Vát mép góc. |
| **ARRAY** | `AR` | Copy mảng (Hàng cột/Vòng tròn). |
| **MATCH PROP** | `MA` | Copy thuộc tính (Layer/Màu) từ A sang B. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group4"></a>
## 📝 Nhóm 4: Text & Ký tự đặc biệt (Group C)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **TEXT STYLE** | `ST` | Cài đặt Font chữ. |
| **MTEXT** | `MT` / `T` | Viết đoạn văn bản (Nhiều dòng). |
| **DTEXT** | `DT` | Viết chữ đơn dòng. |
| **EDIT** | `ED` | Sửa nội dung chữ/số. |
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
| **DIMSTYLE** | `D` | Cài đặt kiểu đo | Chỉnh Text, Arrow, Unit |
| **LINEAR** | `DLI` | Đo thẳng (Ngang/Dọc) | Không đo được đường chéo |
| **ALIGNED** | `DAL` | Đo đường xiên/chéo | Dùng cho cạnh nghiêng |
| **RADIUS** | `DRA` | Đo bán kính (R) | |
| **DIAMETER** | `DDI` | Đo đường kính (Ø) | |
| **ANGULAR** | `DAN` | Đo góc độ | |
| **CONTINUE** | `DCO` | Đo nối tiếp | Cần có 1 Dim gốc trước |
| **BASELINE** | `DBA` | Đo song song | Đo từ 1 mốc chuẩn |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group6"></a>
## 📦 Nhóm 6: Block & Quản lý (Group E)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **BLOCK** | `B` | Đóng gói đối tượng thành khối. |
| **EXPLODE** | `X` | Phá khối (Nổ) ra thành nét rời. |
| **REFEDIT** | `REF` | Sửa khối tại chỗ. |
| **PASTEBLOCK**| `Ctrl+Shift+V` | Dán thành Block ngay lập tức. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group7"></a>
## 🔍 Nhóm 7: Thống kê & Hiển thị (Group F)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ZOOM EXTENTS**| `Z` -> `E` | Zoom toàn bộ hình vừa màn hình. |
| **ZOOM WINDOW** | `Z` -> `W` | Zoom vùng chọn. |
| **ZOOM ALL** | `Z` -> `A` | Zoom tất cả không gian giấy. |
| **AREA** | `AA` | Tính diện tích/Chu vi. |
| **DISTANCE** | `DI` | Đo khoảng cách X, Y nhanh. |
| **LIST** | `LI` | Xem thông tin chi tiết đối tượng. |
| **PURGE** | `PU` | Dọn rác, làm nhẹ bản vẽ. |

---
*Created by Clement - 2026*
