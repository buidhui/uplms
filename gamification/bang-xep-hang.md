---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: false
  tags:
    visible: true
  actions:
    visible: true
---

# Bảng xếp hạng và campaign

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên

**Đường dẫn:** LMS → Gamification → phần bảng xếp hạng
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** Gamification (Leaderboard, Campaign)
* Bảng xếp hạng tính trên toàn tổ chức, công khai tên và ảnh đại diện của học viên.
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết

* Học viên đăng nhập thành công vào hệ thống.
* Tổ chức đã bật Gamification và chức năng bảng xếp hạng.
{% endhint %}

## II. Hướng dẫn chi tiết

<details>

<summary>Bảng xếp hạng</summary>

{% stepper %}
{% step %}
**Mở bảng xếp hạng**

Bảng xếp hạng nằm trên màn hình Gamification, bên dưới khu vực tóm tắt thành tích.

<figure><img src="../.gitbook/assets/gamification-man-chinh.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Chọn tiêu chí xếp hạng**

Mỗi chỉ số là một bảng riêng. Chọn tab tương ứng để xem bảng xếp hạng theo từng chỉ số.:

| Tab | Xếp theo |
| --- | --- |
| **Points** | Điểm (bảng mặc định) |
| **Activities** | Số hoạt động học đã hoàn thành |
| **Courses** | Số khoá đã hoàn thành |
| **Badges** | Số huy hiệu đã đạt |
| **Level** | Cấp độ (Level); nếu cùng cấp độ, xếp theo điểm tích lũy trong cấp độ. |

Tổ chức quyết định bảng nào được hiện, nên bạn có thể thấy ít hơn năm tab.
{% endstep %}

{% step %}
**Chọn khung thời gian**
<figure><img src="../.gitbook/assets/gamification-bxh-chon-thoi-gian.png" alt=""><figcaption></figcaption></figure>
Chọn một trong năm khung: **All time** (mặc định) · **This week** · **This month** · **This quarter** · **This year**. Khoảng ngày của khung đang chọn hiện ngay bên cạnh.

* Tuần bắt đầu từ thứ Hai. Tháng, quý, năm tính theo lịch.
* Bảng **Badges** và **Level** chỉ có ở **All time**. Chọn khung khác thì hai tab này ẩn đi.
{% endstep %}

{% step %}
**Xem thứ hạng của bạn**

* Ba người dẫn đầu được làm nổi bật, tiếp theo là các vị trí 4 và 5.
* Bấm **Show All** để xem toàn bộ học viên. Người chưa có chỉ số nào trong khung nằm cuối danh sách, ô thứ hạng để trống.
* Khu vực bên dưới **Show All** hiển thị thứ hạng của bạn, học viên liền sau và khoảng cách với học viên liền trước (nếu có). Nếu bạn nằm trong 5 người đầu, dòng của bạn được làm nổi bật ngay trong danh sách.
* Nhãn **Last updated** cho biết bảng được tính tới lúc nào. Bảng tính lại khoảng 8 tiếng một lần.
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Đợt thi đua (Campaign)</summary>

Campaign là đợt thi đua có thời hạn do tổ chức mở, ví dụ "Thi đua học tập tháng 11". Mỗi campaign chỉ tính điểm cho một số loại hành động tổ chức chọn, và có kết quả chốt cố định khi kết thúc để trao thưởng.

{% stepper %}
{% step %}
**Chọn campaign**
Trên bảng xếp hạng, mở danh sách campaign cạnh bộ chọn khung thời gian, sau đó chọn đợt thi đua muốn xem, rồi chọn một campaign. Danh sách gồm campaign đang chạy (**In Progress**) và đã kết thúc (**Expired**).
{% endstep %}

{% step %}
**Xem bảng của campaign**
<figure><img src="../.gitbook/assets/gamification-campaign-1.png" alt=""><figcaption></figcaption></figure>
Campaign hiện tên, khoảng thời gian và các loại hành động được tính điểm. Mỗi campaign có tối đa ba bảng:

* **Points**: chỉ cộng điểm từ các loại hành động campaign chọn, trong khoảng thời gian của campaign.
* **Activities**: số hoạt động hoàn thành trong campaign, nếu campaign có bảng này.
* **Courses**: số khoá hoàn thành trong campaign.

Dòng của bạn và người liền kề hiện giống bảng xếp hạng chung.
{% endstep %}

{% step %}
**Xem kết quả chính thức**

* Campaign đang chạy: Bảng hiển thị kết quả tạm thời, cập nhật khoảng 8 giờ một lần
* Campaign đã kết thúc: Bảng hiển thị kết quả chính thức, chốt đúng lúc kết thúc và không thay đổi nữa.
{% endstep %}
{% endstepper %}

</details>

## III. Lưu ý & Quy tắc nghiệp vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Cùng chỉ số thì ai đạt mức đó sớm hơn xếp trên. Không có hai người cùng thứ hạng.
2. Bảng theo khung thời gian tiếp tục được cập nhật: bài Test chấm muộn có thể làm thứ hạng của một khung đã qua thay đổi. Kết quả chốt cố định chỉ có ở campaign đã kết thúc.
3. Bài Test nộp trong campaign nhưng được chấm đạt sau khi campaign kết thúc thì không tính cho campaign đó.
4. Không có bộ chọn khoảng ngày tự do. Muốn xem một đợt thi đua cụ thể, chọn campaign.
{% endhint %}

## IV. Các lỗi thường gặp & Hướng dẫn xử lý

| Lỗi / Tình huống | Nguyên nhân | Cách xử lý |
| --- | --- | --- |
| Vừa học xong mà thứ hạng chưa đổi | Bảng tính lại khoảng 8 tiếng một lần | Xem nhãn **Last updated**. Điểm ở dải tóm tắt vẫn cập nhật ngay |
| Không thấy tab **Badges** hoặc **Level** | Đang chọn khung khác **All time**, hoặc tổ chức đang tắt bảng đó | Chọn **All time** |
| Không có số thứ hạng ở dòng của tôi | Bạn chưa có chỉ số nào trong khung hoặc campaign đang chọn | Học và hoàn thành hoạt động để có tên trên bảng |
| Điểm trong campaign thấp hơn điểm cùng kỳ ở bảng chung | Campaign chỉ cộng điểm từ các loại hành động được chọn | Xem danh sách hành động được tính ở phần thông tin campaign |
| Không thấy campaign sắp diễn ra | Campaign chưa bắt đầu không hiện cho học viên | Campaign xuất hiện từ ngày bắt đầu |
