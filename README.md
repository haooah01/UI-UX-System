# UI-UX-System
Describe UI/UX System In Product Making
Dưới đây là phân tích chuyên sâu cho từng trụ cột trong hệ thống UI/UX từ bức ảnh:
1. User Psychology (Tâm lý học người dùng)
 * Cognitive Load (Tải nhận thức): Lượng năng lượng não bộ cần để xử lý giao diện. Thiết kế tối ưu phải giảm thiểu "Intrinsic Load" (độ phức tạp vốn có) và bỏ hoàn toàn "Extraneous Load" (gây xao nhãng không cần thiết).
 * Hick's Law (Định luật Hick): T = b \cdot \log_2(n + 1). Thời gian ra quyết định (T) tăng theo tỷ lệ thuận với số lượng lựa chọn (n). Giải pháp: Giới hạn tùy chọn trên một màn hình, dùng cơ chế Progressive Disclosure (hiển thị thông tin theo từng cấp độ).
 * Proximity & Gestalt Principles (Nguyên lý gần kề): Các phần tử nằm gần nhau sẽ được não bộ tự động nhóm lại thành một khối ngữ nghĩa. Ngoài ra còn có Nguyên lý đồng dạng (Similarity), Nguyên lý khép kín (Closure) và Nguyên lý liên tục (Continuity).
2. Interaction Design (Thiết kế tương tác)
 * Element Interaction (Tương tác thành phần): Xác định state machine của từng UI component (Default, Hover, Active, Focus, Disabled, Loading, Error).
 * Feedback Loops & Affordance: Trực quan hóa khả năng tương tác. Nút nhấn phải trông có vẻ bấm được (Affordance); khi bấm vào phải cung cấp phản hồi tức thì qua vi phản hồi (Micro-interactions), chuyển động (Motion/Animation) hoặc haptic feedback.
 * Flow & Friction Optimization: Giảm bớt số lượng thao tác thừa, tối ưu hóa các điểm vuốt/chạm (Touch Targets tối thiểu 44x44px trên Mobile) và thiết kế lộ trình người dùng (User Journey) liền mạch.
3. Visual Hierarchy (Thứ tự thị giác)
 * Size & Scale (Kích thước & Quy mô): Dùng tỷ lệ kích thước (Visual Weight) để dẫn dắt tầm mắt. Các thông tin quan trọng nhất (H1, CTA) luôn có diện tích thị giác lớn nhất.
 * Colours & Contrast (Màu sắc & Độ tương phản): Sử dụng quy tắc màu sắc 60-30-10 (60% màu chủ đạo, 30% màu thứ cấp, 10% màu nhấn/Action Color). Độ tương phản (Contrast Ratio) phải đủ lớn để tách biệt phần nổi bật và phần nền.
 * Alignment & Layout Grid (Căn chỉnh & Hệ lưới): Định hình luồng đọc của mắt theo dạng F-Pattern (đối với văn bản/web nhiều chữ) hoặc Z-Pattern (đối với trang Landing Page/ít chữ).
4. Accessibility (Khả năng tiếp cận - a11y)
 * Color Blindness & Contrast (Mù màu & Tương phản): Không bao giờ dùng duy nhất màu sắc để thể hiện trạng thái (ví dụ: lỗi không chỉ dùng màu đỏ mà phải đi kèm icon cảnh báo). Đạt chuẩn WCAG 2.1 AA với tỷ lệ tương phản văn bản tối thiểu là 4.5:1.
 * Assistive Technologies (Công nghệ hỗ trợ): Hỗ trợ Screen Readers (bộ đọc màn hình) thông qua cấu trúc Semantic HTML (dùng đúng tag <button>, <nav>) và thuộc tính ARIA labels.
 * Keyboard Navigation: Đảm bảo toàn bộ ứng dụng có thể điều hướng hoàn toàn bằng phím Tab, Enter, Space và có trạng thái Focus rõ ràng cho người không dùng chuột.
5. Visual Design (Thiết kế thị giác)
 * Layout & Grid System: Sử dụng hệ thống lưới (Layout Grid: 8pt grid system) để đảm bảo tính nhịp điệu và tỷ lệ khoảng trắng (Whitespace/Negative space) chuẩn xác giữa các thành phần.
 * Typography Hierarchy: Hệ thống kiểu chữ chuẩn hóa về Font Family, Font Size, Line Height, Letter Spacing và Font Weight để phân cấp rõ ràng giữa Title, Body, Caption.
 * Iconography & Photography: Chuẩn hóa phong cách hình ảnh (Flat, 3D, Isometric) và bộ icon (Outline, Filled, Stroke width) nhằm truyền tải ý nghĩa trực quan mà không cần dùng nhiều chữ.
6. Design System (Hệ thống thiết kế)
 * Design Tokens: Định nghĩa các biến cơ bản nhất (Atomic level) đại diện cho Màu sắc, Spacing, Typography, Shadow, Border Radius để đồng bộ trực tiếp với code.
 * Component Library (Thư viện thành phần): Xây dựng các UI components tái sử dụng (Buttons, Inputs, Modals, Cards) đi kèm với các biến thể (Variants) và trạng thái (States).
 * Governance & Documentation: Bộ quy tắc hướng dẫn cách sử dụng component (Guidelines), nguyên tắc kiến trúc giao diện, giúp bridge khoảng cách giữa đội ngũ Designer và Developer, đảm bảo tính nhất quán (Consistency) và khả năng mở rộng (Scalability) của sản phẩm.
