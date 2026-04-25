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
9. [💡 Mục đề xuất tham khảo](#dexuat)

---

<a name="quytac"></a>
## ⚡ QUY TẮC VẬN HÀNH CHUNG
* Luôn để ngôn ngữ là ENG khi thao tác để không bị lỗi khi nhập lệnh.
* **Phím SPACE (Cách) = ENTER:** Ngón cái tay trái luôn đặt ở phím Space để gọi lệnh nhanh.
* **Lặp lại lệnh:** Nhấn Space/Enter khi không có lệnh nào -> Gọi lại lệnh vừa dùng.
* **Thoát lệnh:** Luôn nhấn `ESC` (2-3 lần) để hủy bỏ lệnh cũ trước khi nhập lệnh mới.
* **Bảng Setup (Dialog):** Nếu lệnh hiện bảng cài đặt, nhập số trực tiếp vào bảng hoặc gõ `D` để bật/tắt bảng này.
* **Phân biệt rất quan trọng:**  
  * **LINE** = đoạn thẳng rời  
  * **PLINE / POLYLINE** = nhiều đoạn nhưng có thể là **1 đối tượng duy nhất**  
  * **SPLINE** = đường cong mềm  
  * **XLINE** = đường thẳng vô tận dùng để dựng hình

---

<a name="group1"></a>
## 🛠️ Nhóm 1: Cài đặt & Hỗ trợ vẽ (Setup & Aids)
*Các phím chức năng dùng liên tục trong quá trình vẽ.*

### 1.1. Thiết lập chung

| Lệnh / Phím | Phím Tắt | Chức Năng | Ghi chú |
| :--- | :--- | :--- | :--- |
| **UNITS** | `UN` | Thiết lập đơn vị bản vẽ | Cần làm lúc đầu |
| **MVSETUP** | `MVSETUP` | Thiết lập khổ giấy | Chọn No -> Metric -> Tỉ lệ (Chỉ dùng lúc đầu) |
| **ORTHO** | `F8` | Chế độ vẽ thẳng góc | Bật liên tục để vẽ ngang/dọc |
| **POLAR** | `F10` | Chế độ vẽ theo tia | Vẽ xiên theo góc 30, 45... |
| **DYNAMIC INPUT** | `F12` | Hiển thị & Nhập liệu | Nhập số cạnh con trỏ chuột |
| **CHUYỂN Ô** | `TAB` | Chuyển đổi nhập liệu | Chuyển giữa ô Chiều dài <-> Ô Góc (khi bật F12) |
| **TỌA ĐỘ CỰC** | `@L<A` | Nhập độ dài và góc | Ví dụ: `@100<45` |
| **TỌA ĐỘ TƯƠNG ĐỐI** | `@X,Y` | Nhập điểm theo tọa độ tương đối | Ví dụ: `@100,50` |
| **TỌA ĐỘ TUYỆT ĐỐI** | `X,Y` | Nhập điểm theo hệ tọa độ gốc | Ví dụ: `100,50` |

---

### 1.2. Truy bắt điểm & Tracking

| Lệnh / Phím | Phím Tắt | Chức Năng | Ghi chú |
| :--- | :--- | :--- | :--- |
| **OBJECT SNAP** | `F3` | Bật chế độ truy bắt điểm | Endpoint, Midpoint, Center... |
| **OSNAP SETTINGS** | `DSETTINGS` | Mở bảng cài đặt bắt điểm | Chọn các loại bắt điểm thường dùng |
| **OBJECT SNAP TRACKING** | `F11` | Dóng điểm từ điểm đã bắt | Hỗ trợ dựng hình nhanh |
| **ENDPOINT** | `Shift + chuột phải` | Bắt điểm đầu/cuối | Dùng cực nhiều |
| **MIDPOINT** | `Shift + chuột phải` | Bắt trung điểm | Dùng cực nhiều |
| **CENTER** | `Shift + chuột phải` | Bắt tâm đường tròn / cung | Dùng cực nhiều |
| **INTERSECTION** | `Shift + chuột phải` | Bắt giao điểm | Dùng cực nhiều |
| **QUADRANT** | `Shift + chuột phải` | Bắt 4 điểm đặc biệt của đường tròn / elip | Trên, dưới, trái, phải |
| **TANGENT** | `Shift + chuột phải` | Bắt tiếp điểm | Rất hay gặp ở bài cung tròn |
| **PERPENDICULAR** | `Shift + chuột phải` | Bắt vuông góc | Dùng khi dựng hình |
| **NEAREST** | `Shift + chuột phải` | Bắt điểm gần nhất trên đối tượng | Chỉ dùng khi thật cần |
| **NODE** | `Shift + chuột phải` | Bắt vào đối tượng POINT | Dùng với POINT, DIVIDE, MEASURE |

---

### 1.3. Hiển thị & hỗ trợ quan sát

| Lệnh / Phím | Phím Tắt | Chức Năng | Ghi chú |
| :--- | :--- | :--- | :--- |
| **GRID** | `F7` | Hiện lưới | Dùng khi mới học cho dễ nhìn |
| **SNAP** | `F9` | Bật bước nhảy con trỏ | Nên tắt nếu thấy vướng |
| **CURSORSIZE** | `CURSORSIZE` | Chỉnh độ dài crosshair | Liên quan phần crosshair / display |
| **LINEWEIGHT** | `LWDISPLAY` | Hiển thị độ dày nét | Bật lên mới thấy nét đậm/nhạt |
| **ZOOMFACTOR** | `ZOOMFACTOR` | Tốc độ lăn chuột | Khuyên dùng: 60 - 100 |
| **REGEN** | `RE` | Làm tươi lại bản vẽ | Dùng khi nét hiển thị lỗi |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group2"></a>
## ✏️ Nhóm 2: Công cụ Vẽ (Draw - Group A)
*Các lệnh tạo hình cơ bản, sắp xếp theo cụm để dễ nhớ hơn.*

### 2.1. Nhóm đường thẳng / đường dựng / đường liền mạch  
*Đặt gần nhau cho dễ phân biệt.*

| Lệnh | Phím Tắt | Chức Năng | Ghi chú quan trọng |
| :--- | :--- | :--- | :--- |
| **LINE** | `L` | Vẽ đường thẳng rời. | Lệnh dùng nhiều nhất |
| **POLYLINE** | `PL` | Vẽ đa tuyến liền mạch. | Các nét dính liền nhau |
| **XLINE** | `XL` | Vẽ đường dóng vô tận. | Dùng để dựng hình chiếu / dựng giao điểm |
| **SPLINE** | `SPL` | Vẽ đường cong mềm. | **Không phải đường vô tận** |
| **MULTILINE** | `ML` | Vẽ 2 nét song song. | Dùng vẽ tường nhà |

---

### 2.2. Nhóm đường tròn / cung / hình kín cơ bản

| Lệnh | Phím Tắt | Chức Năng | Ghi chú quan trọng |
| :--- | :--- | :--- | :--- |
| **CIRCLE** | `C` | Vẽ hình tròn. | Dùng cực nhiều |
| **ARC** | `A` | Vẽ cung tròn. | Cực hay đi cùng CIRCLE |
| **RECTANGLE** | `REC` | Vẽ hình chữ nhật. | `F`: Bo tròn (Fillet)<br>`M`: Vát mép (chaMfer)<br>`D`: Bảng cài đặt (Dialog) |
| **POLYGON** | `POL` | Vẽ đa giác đều. | `I`: Nội tiếp, `C`: Ngoại tiếp |
| **ELLIPSE** | `EL` | Vẽ hình bầu dục / elip. | Khác với CIRCLE |
| **HATCH** | `H` | Tô vật liệu (Mặt cắt). | Dùng nhiều ở bài mặt cắt |

---

### 2.3. Nhóm điểm / chia điểm

| Lệnh | Phím Tắt | Chức Năng | Ghi chú quan trọng |
| :--- | :--- | :--- | :--- |
| **POINT** | `PO` | Vẽ một điểm mốc. | Bắt lại bằng **Node** |
| **DIVIDE** | `DIV` | Chia đối tượng thành số phần bằng nhau. | Rải điểm point |
| **MEASURE** | `ME` | Chia đối tượng theo khoảng cách cố định. | Khác DIVIDE ở chỗ nhập độ dài |
| **POINT STYLE** | `PTYPE` | Đổi kiểu hiển thị của điểm. | Dùng ngay sau POINT / DIVIDE / MEASURE |

---

### 2.4. Ghi nhớ nhanh nhóm vẽ
* **LINE** = đoạn thẳng rời  
* **PLINE** = nhiều đoạn nhưng là 1 polyline  
* **XLINE** = đường dựng vô tận  
* **SPLINE** = đường cong mềm  
* **CIRCLE / ARC** = hình tròn & cung tròn chuẩn  
* **ELLIPSE** = elip, không phải hình tròn

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group3"></a>
## ✂️ Nhóm 3: Công cụ Chỉnh sửa (Modify - Group B)
*Các lệnh sửa hình, lệnh nào dùng nhiều để lên trên.*

### 3.1. Cắt / nối / hiệu chỉnh biên dạng

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ERASE** | `E` | Xóa đối tượng. |
| **TRIM** | `TR` | Cắt xén phần thừa. |
| **EXTEND** | `EX` | Phóng dãn đường tới đích. |
| **OFFSET** | `O` | Copy song song (tạo tường/viền). |
| **FILLET** | `F` | Bo tròn góc (`R` nhập bán kính). |
| **CHAMFER** | `CHA` | Vát mép góc. |
| **BREAK** | `BR` | Ngắt đoạn thẳng tại 2 điểm. |
| **JOIN** | `J` | Nối các nét rời thành 1 nét liền. |
| **PEDIT** | `PE` | Chỉnh sửa Polyline. | Dùng để nối / đổi Line sang Polyline |
| **LENGTHEN** | `LEN` | Tăng / giảm chiều dài đối tượng. | Hữu ích khi chỉnh line, arc |

---

### 3.2. Di chuyển / biến đổi / sao chép

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **MOVE** | `M` | Di chuyển đối tượng. |
| **COPY** | `CO` / `CP` | Sao chép đối tượng. |
| **ROTATE** | `RO` | Xoay hình. |
| **MIRROR** | `MI` | Lấy đối xứng (Soi gương). |
| **SCALE** | `SC` | Phóng to / Thu nhỏ tỷ lệ. |
| **STRETCH** | `S` | Kéo dãn hình (Quét chuột phải sang trái). |
| **ARRAY** | `AR` | Copy mảng (Hàng cột/Vòng tròn). |
| **ALIGN** | `AL` | Căn chỉnh + xoay theo đối tượng chuẩn. |
| **MATCH PROP** | `MA` | Copy thuộc tính (Layer/Màu). |

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
| **FIELD** | `FIELD` | Chèn trường dữ liệu tự động. | Có nhắc trong phần mở rộng |

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
| **DIMEDIT** | `DED` | Chỉnh sửa dim | Dùng khi chỉnh text dim / góc dim |
| **CENTERMARK / CENTERLINE** | `CENTERMARK` / `CENTERLINE` | Ghi dấu tâm / đường tâm | Rất hợp bài cơ khí |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group6"></a>
## 📦 Nhóm 6: Block & Quản lý (Group E)

### 6.1. Block / Block động / Thuộc tính

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **BLOCK** | `B` | Đóng gói đối tượng thành khối. |
| **WBLOCK** | `WB` | Ghi block thành file riêng. |
| **INSERT** | `I` | Chèn block vào bản vẽ. |
| **EXPLODE** | `X` | Phá khối (Nổ) ra thành nét rời. |
| **PASTEBLOCK** | `Ctrl+Shift+V` | Dán thành Block ngay lập tức. |
| **REFEDIT** | `REF` | Sửa khối tại chỗ. |
| **BEDIT** | `BE` | Mở Block Editor. | Dùng cho Dynamic Block |
| **ATTDEF** | `ATTDEF` | Tạo thuộc tính cho block. |
| **EATTEDIT** | `EATTEDIT` | Sửa thuộc tính block. |
| **BATTMAN** | `BATTMAN` | Quản lý thuộc tính block. |

---

### 6.2. Layer / Tham chiếu / In ấn

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **LAYER** | `LA` | Quản lý layer. |
| **PROPERTIES** | `PR` | Xem / chỉnh thuộc tính đối tượng. |
| **XREF** | `XR` | Gắn file tham chiếu ngoài. |
| **LAYOUT** | `LAYOUT` | Quản lý các layout in. |
| **PAGESETUP** | `PAGESETUP` | Thiết lập in ấn cho layout. |
| **PLOT** | `PLOT` / `Ctrl+P` | In bản vẽ. |
| **MVIEW** | `MV` | Tạo viewport trong layout. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="group7"></a>
## 🔍 Nhóm 7: Thống kê & Hiển thị (Group F)

| Lệnh | Phím Tắt | Chức Năng |
| :--- | :--- | :--- |
| **ZOOM EXTENTS** | `Z` -> `E` | Zoom toàn bộ hình vừa màn hình. |
| **ZOOM WINDOW** | `Z` -> `W` | Zoom vùng chọn. |
| **ZOOM ALL** | `Z` -> `A` | Zoom tất cả không gian giấy. |
| **PAN** | Giữ chuột giữa | Kéo bản vẽ khi quan sát. |
| **DISTANCE** | `DI` | Đo khoảng cách X, Y nhanh. |
| **AREA** | `AA` | Tính diện tích / Chu vi. |
| **LIST** | `LI` | Xem thông tin chi tiết đối tượng. |
| **PURGE** | `PU` | Dọn rác, làm nhẹ bản vẽ. |
| **AUDIT** | `AUDIT` | Kiểm tra và sửa lỗi file bản vẽ. |
| **UNDO / REDO** | `U` / `REDO` | Quay lại / làm lại thao tác. |

[⬆️ Về đầu trang](#-mục-lục-table-of-contents)

---

<a name="dexuat"></a>
## 💡 Mục đề xuất tham khảo
*Phần này chỉ để tham khảo thêm. Không tự ý sửa mạnh nội dung cũ nếu chưa cần.*

1. **Nên để LINE - POLYLINE - XLINE - SPLINE gần nhau** như bản mở rộng này, vì đây là nhóm người mới dễ nhầm nhất.
2. **POINT STYLE** nên ghi thêm alias `DDPTYPE`, vì nhiều máy dùng tên này quen hơn.
3. **OSNAP / OBJECT SNAP** nên có mặt riêng trong file vì bài tập dùng rất nhiều truy bắt điểm.
4. **LAYER** hiện chưa xuất hiện trong bản cũ, nhưng phần bài tập tổng hợp có nhắc thiết lập Layer.
5. **SPLINE ≠ XLINE** nên có dòng ghi nhớ riêng, vì đây là lỗi nhầm rất phổ biến.
6. Nếu muốn học theo lộ trình gọn hơn, có thể chia thứ tự học:
   * **Giai đoạn 1:** LINE, CIRCLE, RECTANGLE, ARC, TRIM, OFFSET  
   * **Giai đoạn 2:** PLINE, XLINE, POLYGON, FILLET, CHAMFER, ARRAY  
   * **Giai đoạn 3:** SPLINE, ELLIPSE, POINT, DIVIDE, MEASURE, HATCH  
   * **Giai đoạn 4:** TEXT, DIM, BLOCK, LAYER, LAYOUT, PLOT

---

*Created by Clement - 2026*  
*Bản mở rộng: giữ nguyên cấu trúc cũ, chủ yếu bổ sung mục còn thiếu để tiện học theo bài tập.*
