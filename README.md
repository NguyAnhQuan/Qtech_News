# 📰 Qtech News

> Dự án website tin tức **Qtech News** được clone từ [VnExpress](https://vnexpress.net), nhằm mục đích học tập và thực hành các kỹ năng phát triển web hiện đại, dự án của chúng tôi mang tính chất học tập và không sử dụng kinh doanh dưới mọi hình thức. Nếu bạn muốn clone dự án này vui lòng không kinh doanh dưới mọi hình thức và phải tự chịu trách nhiệm dưới hành vi của mình.

---

## 1. 🚀 Giới thiệu dự án

Qtech News là nền tảng tin tức trực tuyến, lấy cảm hứng từ VnExpress, với giao diện hiện đại, thân thiện người dùng. Dự án giúp các thành viên rèn luyện kỹ năng thiết kế, lập trình backend và quản lý cơ sở dữ liệu.

Trang Web được tạo để rèn luyện khả năng quản lý dự án, quản lý nhóm, và trau dồi các kỹ năng lập trình cũng như các kỹ năng thiết kế để tạp nên website đẹp và dễ sử dụng với người dùng cũng như đầy đủ tính năng với người quản lý.

Bạn có thể xem dự án của chúng tôi tại đây hoặc tải về và chạy với JDK và pgadmin nếu có bất cứ vấn đề nào có thể liên hệ với người chịu trách nhiệm chính của dự án hoặc đặt câu hỏi [tại đây](https://github.com/NguyAnhQuan/Qtech_News/discussions) chúng tôi không ngại giải thích nếu bạn đặt câu hỏi.

---

## 2. 👥 Người đóng góp dự án

| Ảnh đại diện | Họ và tên         | Vai trò                                                                                   |
|:------------:|:------------------|:----------------------------------------------------------------------------------------------------------|
| <img src="https://avatars.githubusercontent.com/u/93334249?v=4" width="68" style="border-radius:50%;" /> | **Nguyễn Anh Quân** | Chịu trách nhiệm chính, triển khai CI/CD |
| <img src="https://avatars.githubusercontent.com/u/141143525?v=4" width="68" style="border-radius:50%;" /> | **Nguyễn Văn Vũ**   | Thành viên dự án Qtech News                      |


---

## 3. <img src="./Demo md/Figma-logo.png" alt="Figma Logo" width="10" /> Thiết kế Figma

- Giao diện được thiết kế trước bằng [Figma](https://www.figma.com/) để đảm bảo trải nghiệm người dùng hiện đại, trực quan và dễ sử dụng.

<p align="center">
    <img src="./Demo md/Figma-logo.png" alt="Figma Logo" width="60" />
</p>

- Link bản thiết kế (nếu có): [Qtech News trên Figma của chúng tôi](https://www.figma.com/design/OiMm1P3Euuj43l1X7Xr0bY/Qtech_News?node-id=0-1&t=fKeQeLGR8UUYqJes-1)

Chúng tôi đã thiết kế Figma với hai phân khu giao diện chính:

**1. Giao diện người dùng:**
- Bao gồm các trang chính (trang chủ, danh mục, chi tiết tin tức) và các trang phụ (điều khoản, liên hệ, v.v.).
- Thiết kế các prototype cho từng luồng thao tác của người dùng.
- Sử dụng màu sắc thân thiện, hài hòa, đảm bảo trải nghiệm trực quan và dễ sử dụng.
- Demo giao diện người dùng được hiển thị đầy đủ tại trang chủ.
- Sau đây là demo một số ít trang có tại phần người dùng của chúng tôi

<table>
    <tr>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien1.png" alt="Ảnh 1" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien2.png" alt="Ảnh 2" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien3.png" alt="Ảnh 3" width="200" height="230"/>
            </div>
        </td>
    </tr>
    <tr>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien4.png" alt="Ảnh 4" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien5.png" alt="Ảnh 5" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien6.png" alt="Ảnh 6" width="200" height="230"/>
            </div>
        </td>
    </tr>
    <tr>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien7.png" alt="Ảnh 7" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien8.png" alt="Ảnh 8" width="200" height="230"/>
            </div>
        </td>
        <td align="center">
            <div style="position:relative; display:inline-block;">
                <img src="./Demo md/figma/fontend/clien9.png" alt="Ảnh 9" width="200" height="230"/>
            </div>
        </td>
    </tr>
</table>

**2. Giao diện quản trị viên:**
- Các số liệu thống kê được trực quan hóa bằng biểu đồ, giúp admin dễ dàng quản lý và theo dõi hoạt động hệ thống.
- Thông báo và các chức năng quản trị được bố trí rõ ràng, thuận tiện thao tác.
- Hỗ trợ quản lý bài viết, người dùng, phân quyền và các tính năng nâng cao khác cho admin,....

Thiết kế Figma luôn được cập nhật để phù hợp với nhu cầu phát triển và phản hồi từ người dùng, đảm bảo tính hiện đại và tối ưu cho cả hai phía: người dùng cuối và quản trị viên.

---

## 4. 💻 Thiết kế code

- **Fontend:** <img src="./Demo md/bootstrap-logo.png" alt="Boostrap" width="40" /> Boostrap, <img src="./Demo md/jquery-logo.svg" alt="Boostrap" width="80" /> jQuery

- **Backend:** <img src="./Demo md/spring-logo.png" alt="spring logo" width="80" /> PostgreSQL
 
- **Database:** <img src="./Demo md/Postgresql-logo.png" alt="PostgreSQL" width="25" /> PostgreSQL

---

## 5. 📌 Kết luận

Dự án Qtech News là sản phẩm hợp tác giữa Nguyễn Anh Quân và Nguyễn Văn Vũ, với mục tiêu nâng cao kỹ năng lập trình web, thiết kế giao diện và làm việc nhóm.  
Mọi ý kiến đóng góp hoặc liên hệ, vui lòng gửi về:

- Nguyễn Anh Quân: [![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:anhq46724@gmail.com)

---

