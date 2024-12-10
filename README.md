# Permate Brand SuperTag - Google Tag Manager

SuperTag Template của Permate hỗ trợ chuẩn Google Tag template, là thư viện JavaScript chứa tất cả hàm/chức năng cần có cho giải pháp theo dõi của Permate. Permate SuperTag nên được đặt ở mọi trang cần theo dõi, ngoại trừ trang thank you/xác nhận thanh toán thành công. Trên trang thank you/xác nhận thanh toán thành công thì vui lòng lựa chọn tích hợp Permate Conversion Pixel Tag.

## Tổng quan tài liệu tích hợp

<ol>
  <li>Nhập (Import) Permate SuperTag Template vào mẫu Google Tag Manager của bạn.</li>
  <li>Cài đặt Permate SuperTag vào danh sách Tag của bạn.</li>
  <li>Cài đặt Custom HTML.</li>
  <li>Cấu hình nâng cao Permate SuperTag.</li>
</ol>

## 1. Nhập (Import) Permate SuperTag Template

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Templates/Mẫu</b> sau đó chọn <b>New/Mới</b>.</li>
  <li>Click chọn vào dấu 3 chấm trên cùng bên phải, sau đó chọn <b>Import/Nhập</b>.</li>
  <li>Bạn cần tải về file <a href="https://github.com/PmHubDev/qa-offer-google-tag-manager-template/blob/main/template.tpl"><b>template.tpl</b></a> sau đó nhập vào Template/Mẫu.</li>
  <li>Chọn Save/Lưu</li>

  ![GTM_Permate_Import_SuperTag](https://github.com/user-attachments/assets/1b6217a9-d5ba-4a47-83f7-4d05e3448765)
  ![GTM_Permate_SuperTag_Template](https://github.com/user-attachments/assets/83785150-ad5d-4566-b7b4-440a0053ad73)
</ol>

## 2. Cài đặt Permate SuperTag

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Tag/Thẻ</b> sau đó chọn <b>New/Mới</b>.</li>
  <li>Chọn vào <b>Tag Configuration/Cấu Hình Thẻ</b>.</li>
  <li>Tại mục <b>Custom/Tuỳ chỉnh</b> tìm <b>Permate SuperTag</b> của Permate. Nếu bạn không tìm thấy, hãy thực hiện Import ở bước 1.</li>

  ![GTM_Permate_SuperTag_View](https://github.com/user-attachments/assets/1d49acdf-f4f5-476c-842c-2481ee750174)
  <li>Thẻ này sẽ cần sử dụng Trigger kích hoạt tất cả sự kiện <b>DOM Ready/DOM Sẵn sàng</b></li>
  
  ![GooogleTagManager_Trigger](https://github.com/user-attachments/assets/0cb3bff8-9490-4eec-b161-7637714b684c)
  <li>Đặt tên cho thẻ của bạn và mọi thứ đã hoàn thành.</li>
</ol>

## 3. Cài đặt Custom HTML

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Tag/Thẻ</b> sau đó chọn <b>New/Mới</b>.</li>
  <li>Chọn vào <b>Tag Configuration/Cấu Hình Thẻ</b>.</li>
  <li>Tại mục <b>Custom/Tuỳ chỉnh</b>, chọn vào <b>Custom HTML/HTML Tuỳ chỉnh</b>.</li>

  ![GTM_CustomHTML_View](https://github.com/user-attachments/assets/e085a442-ab8f-4925-91c8-2daa39218c7b)
  <li>Tại mục <b>HTML</b>, bạn cần điền đoạn mã Javascript trong file <a href="https://github.com/PmHubDev/qa-offer-google-tag-manager-template/blob/main/customScript.html"><b>customScript.html</b></a> vào đây</li>

  ![GTM_CustomHTML_Value](https://github.com/user-attachments/assets/ea7faeaf-45a5-411c-94e6-68753d12746e)
  <li>Thẻ này sẽ cần sử dụng Trigger kích hoạt tất cả sự kiện <b>DOM Ready/DOM Sẵn sàng</b> giống với <b>Permate SuperTag</b>.</li>
  
  ![GooogleTagManager_Trigger](https://github.com/user-attachments/assets/0cb3bff8-9490-4eec-b161-7637714b684c)
  <li>Đặt tên cho thẻ của bạn và mọi thứ đã hoàn thành.</li>
</ol>

## 4. Cấu hình nâng cao cho thẻ

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Tag/Thẻ</b> sau đó chọn thẻ <b>Permate SuperTag</b> vừa mới tạo ở bước 2.</li>
  <li>Chọn vào <b>Advanced Settings/Cài Đặt Nâng Cao</b>.</li>
  <li>Tại mục <b>Tag firing priority</b>: Bạn cần điền giá trị lớn hơn giá trị của <b>Permate Button Tag</b> (nếu có).</li>

  ![GTM_Permate_SuperTag_Priority](https://github.com/user-attachments/assets/a1d452c2-3e95-4071-99f6-ae12930db198)

  <li>Chọn <b>Save/Lưu</b></li>
  <li>Chọn thẻ <b>Custom HTML/HTML Tuỳ chỉnh</b> vừa mới tạo ở bước 3.</li>
  <li>Chọn vào <b>Advanced Settings/Cài Đặt Nâng Cao</b>.</li>
  <li>Tại mục <b>Tag firing priority</b>: Bạn cần điền giá trị lớn hơn giá trị Tag firing priority của <b>Permate SuperTag</b>.</li>

  ![GTM_Permate_CustomHTML_Priority](https://github.com/user-attachments/assets/142cd081-6fa5-4071-ad46-5c23ebe44e35)
  <li>Chọn <b>Save/Lưu</b> và mọi thứ đã hoàn thành.</li>
</ol>

## Tìm hiểu chi tiết hơn về Permate SuperTag
#### :arrow_right: Ghé thăm tại đây [Trung Tâm Trợ Giúp](https://permate.com/docs-category/brand-en/)
