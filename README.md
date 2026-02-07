# 🛠️ MinhKySu-AutoCAD-Mastery
> Kho lưu trữ kiến thức, phím tắt và bài tập AutoCAD phục vụ lộ trình Kỹ sư Nhúng & Tự động hóa.

![AutoCAD](https://img.shields.io/badge/Tools-AutoCAD-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Learning-green?style=flat-square)
![Author](https://img.shields.io/badge/Author-Clement-blue?style=flat-square)

---

## 📑 MỤC LỤC (TABLE OF CONTENTS)
1. [Quy tắc vận hành chung](#-quy-tắc-vận-hành-chung)
2. [Nhóm 1: Cài đặt & Hỗ trợ (Setup)](#-nhóm-1-cài-đặt--hỗ-trợ-vẽ-setup--aids)
3. [Nhóm 2: Công cụ Vẽ (Draw)](#-nhóm-2-công-cụ-vẽ-draw---group-a)
4. [Nhóm 3: Công cụ Chỉnh sửa (Modify)](#-nhóm-3-công-cụ-chỉnh-sửa-modify---group-b)
5. [Nhóm 4: Text & Ký tự đặc biệt](#-nhóm-4-công-cụ-text--ký-tự-đặc-biệt-group-c)
6. [Nhóm 5: Kích thước (Dimension)](#-nhóm-5-công-cụ-kích-thước-dimension---group-d)
7. [Nhóm 6: Block & Quản lý](#-nhóm-6-block--quản-lý-khối-group-e)
8. [Nhóm 7: Thống kê & Hiển thị](#-nhóm-7-thống-kê--hiển-thị-group-f)

---

## ⚡ QUY TẮC VẬN HÀNH CHUNG
* **Phím SPACE (Cách) = ENTER:** Trong AutoCAD, ngón cái tay trái luôn đặt ở phím Space để gọi lệnh nhanh.
* **Lặp lại lệnh:** Nhấn Space/Enter khi không có lệnh nào -> Gọi lại lệnh vừa dùng gần nhất.
* **Thoát lệnh:** Luôn nhấn `ESC` (2-3 lần) để hủy bỏ lệnh hiện tại trước khi nhập lệnh mới.
* **Chuột giữa (Đè xuống):** Pan (Kéo trượt màn hình).
* **Chuột giữa (Lăn):** Zoom in / Zoom out.

---

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

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

## ✏️ Nhóm 2: Công cụ Vẽ (Draw - Group A)
*Các lệnh tạo hình cơ bản.*

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **LINE** | `L` | Vẽ đường thẳng rời. |
| **POLYLINE** | `PL` | Vẽ đa tuyến liền mạch. |
| **XLINE** | `XL` | Vẽ đường dóng vô tận. |
| **MULTILINE** | `ML` | Vẽ 2 nét song song (tường). |
| **RECTANGLE** | `REC` | Vẽ hình chữ nhật (`F` để bo góc). |
| **POLYGON** | `POL` | Vẽ đa giác đều (`I`: Nội tiếp, `C`: Ngoại tiếp). |
| **CIRCLE** | `C` | Vẽ hình tròn. |
| **ARC** | `A` | Vẽ cung tròn. |
| **ELLIPSE** | `EL` | Vẽ hình Bầu dục. |
| **HATCH** | `H` | Tô vật liệu. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

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
| **STRETCH** | `S` | Kéo dãn hình (Quét từ phải qua trái). |
| **TRIM** | `TR` | Cắt xén phần thừa. |
| **EXTEND** | `EX` | Phóng dãn đường tới đích. |
| **FILLET** | `F` | Bo tròn góc (`R` nhập bán kính). |
| **CHAMFER** | `CHA` | Vát mép góc. |
| **ARRAY** | `AR` | Copy mảng (Hàng cột/Vòng tròn). |
| **MATCH PROP** | `MA` | Copy thuộc tính (Layer/Màu) từ A sang B. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

## 📝 Nhóm 4: Công cụ Text & Ký tự đặc biệt (Group C)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **TEXT STYLE** | `ST` | Cài đặt Font chữ. |
| **MTEXT** | `MT` / `T` | Viết đoạn văn bản. |
| **DTEXT** | `DT` | Viết chữ đơn dòng. |
| **EDIT** | `ED` | Sửa nội dung chữ/số. |
| **FIND** | `FIND` | Tìm và thay thế chữ. |

**Bảng mã ký tự:**
* `%%C` : Ø (Đường kính)
* `%%P` : ± (Cộng trừ)
* `%%D` : ° (Độ)
* `%%U` : Gạch chân

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

## 📏 Nhóm 5: Công cụ Kích thước (Dimension - Group D)

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

## 📦 Nhóm 6: Block & Quản lý khối (Group E)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **BLOCK** | `B` | Đóng gói đối tượng thành khối. |
| **EXPLODE** | `X` | Phá khối (Nổ) ra thành nét rời. |
| **REFEDIT** | `REF` | Sửa khối tại chỗ. |
| **PASTEBLOCK**| `Ctrl+Shift+V` | Dán thành Block ngay lập tức. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

## 🔍 Nhóm 7: Thống kê & Hiển thị (Group F)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ZOOM EXTENTS**| `Z` -> `E` | Zoom toàn bộ hình vừa màn hình. |
| **ZOOM WINDOW** | `Z` -> `W` | Zoom vùng chọn. |
| **AREA** | `AA` | Tính diện tích/Chu vi. |
| **DISTANCE** | `DI` | Đo khoảng cách X, Y. |
| **PURGE** | `PU` | Dọn rác, làm nhẹ bản vẽ. |

---
*Created by Minh Kỹ Sư - 2026*
