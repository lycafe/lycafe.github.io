---
layout: post
title: Hiểu về ý nghĩa của phân phối chuẩn
---

## Phân phối chuẩn của dữ liệu

Phân phối chuẩn, còn gọi là phân phối Gauss, là một phân phối xác suất phổ biến. Nó có hình dạng thường được gọi là "đường cong hình chuông" (curve bell 🔔) .

Nhiều tập dữ liệu hàng ngày thường tuân theo phân phối chuẩn, ví dụ: chiều cao của người trưởng thành, điểm số trong bài kiểm tra cho một lớp (số lượng lớn), sai số trong các phép đo.

Phân phối chuẩn luôn đối xứng về giá trị trung bình.

Độ lệch chuẩn là thước đo mức độ trải rộng của một tập dữ liệu được phân phối chuẩn. Đây là một thống kê cho bạn biết tất cả các ví dụ được thu thập chặt chẽ như thế nào về giá trị trung bình trong một tập dữ liệu. Hình dạng của phân phối chuẩn được xác định bởi giá trị trung bình (mean x̅) và độ lệch chuẩn (standard deviation σ). Đường cong càng dốc thì độ lệch chuẩn càng nhỏ. Nếu các mẫu được trải ra xa nhau, đường cong sẽ phẳng hơn nhiều, có nghĩa là độ lệch chuẩn lớn.

![_config.yml]({{ site.baseurl }}/images/post1/post_1-image1.gif)

Nói chung, khoảng 68.2% diện tích dưới đường cong phân phối chuẩn nằm trong 1 độ lệch chuẩn của giá trị trung bình.
Nghĩa là, nếu x̅ là giá trị trung bình và σ là độ lệch chuẩn của phần phối, thì 68% của giá trị nằm trong khoảng (x̅ - σ) và (x̅ + σ). Xem hình bên dưới, phần diện tích vừa đề cập là vùng được tô màu hồng.
Phân phối chuẩn với giá trị trung bình (x̅) bằng 0 và độ lệch chuẩn (σ) bằng 1 gọi là Phân phối chuẩn tắc (standard normal distribution)

![_config.yml]({{ site.baseurl }}/images/post1/post_1-image2.jpg)

Khoảng 95% giá trị nằm trong 2 độ lệch chuẩn (2σ) của giá trị trung bình, nghĩa là giữa (x̅ - 2σ) và (x̅ - 2σ) (Trong hình, đây là tổng của các vùng màu hồng và xanh lam: 34.1% + 34.1% + 13.6% + 13.6% = 95.4%)

Khoảng 99.7% giá trị nằm trong 3 độ lệch chuẩn (3σ) của giá trị trung bình, nghĩa là giữa (x̅ - 3σ) và (x̅ - 3σ).
(Các vùng màu hồng, xanh lam và xanh lục trong hình)

(Lưu ý rằng những giá trị này là gần đúng)

## Ví dụ

### Ví dụ 1

Có 1 tập hợp dữ liệu được phân phối bình thường với giá trị trung bình là 5. Vậy bao nhiêu phần trăm dữ liệu nhỏ hơn 5?

Phân phối chuẩn thì đối xứng về giá trị trung bình. Vì vậy, một nửa dữ liệu sẽ nhỏ hơn giá trị trung bình và một nửa dữ liệu sẽ lớn hơn giá trị trung bình.

Do đó, 50% dữ liệu nhỏ hơn 5.

### Ví dụ 2

Tuổi thọ của pin điện thoại được sạc đầy thường được phân phối với mức trung bình là 14 giờ và độ lệch chuẩn là 1 giờ. Xác suất để pin dùng được ít nhất 13 giờ là bao nhiêu?

Giá trị trung bình là 14 và độ lệch chuẩn là 1.

50% phân phối chuẩn nằm ở bên phải của giá trị trung bình, vì vậy 50% thời gian, pin sẽ kéo dài hơn 14 giờ.

Khoảng thời gian từ 13 đến 14 giờ đại diện cho một độ lệch chuẩn (1σ) ở bên trái của giá trị trung bình. Vì vậy, khoảng 34.1% thời gian, pin sẽ kéo dài từ 13 đến 14 giờ.

Do đó, xác suất để pin kéo dài ít nhất 13 giờ là khoảng 34.1% + 50%  = 84.1%

### Ví dụ 3

Trọng lượng trung bình của một quả mâm xôi là 4.4 gram với độ lệch chuẩn là 1.3 gram. Xác suất để một quả mâm xôi được chọn ngẫu nhiên có trọng lượng ít nhất 3.1 gram nhưng không quá 7.0 gram là bao nhiêu?

Giá trị trung bình là 4.4 và độ lệch chuẩn là 1.3

Ta có: 

4.4 - 1.3 = 3.1

và

4.4 + 2x1.3 = 7.0

Vì vậy, khoảng 3.1 ≤ x ≤ 7.0 thực sự nằm giữa một độ lệch chuẩn dưới mức trung bình và 2 độ lệch chuẩn trên mức trung bình.

Trong dữ liệu được phân phối chuẩn, khoảng 34.1% giá trị nằm giữa giá trị trung bình và một độ lệch chuẩn dưới giá trị trung bình và 34.1% giữa giá trị trung bình và một độ lệch chuẩn trên giá trị trung bình.

Ngoài ra, 13.5% giá trị nằm giữa độ lệch chuẩn thứ nhất và thứ hai trên mức trung bình.

Thêm các khu vực, chúng ta nhận được 34.1% + 34.1% + 13.6% = 81.8%.

Do đó, xác suất để một quả mâm xôi được chọn ngẫu nhiên sẽ nặng ít nhất 3.1 gram nhưng không quá 7.0 gram là 81.8%

### Ví dụ 4

Một thị trấn có 330,000 người lớn. Chiều cao của họ được phân bổ bình thường với giá trị trung bình là 160 cm và phương sai là 64 cm2. vậy có bao nhiêu người cao hơn 184 cm?

Phương sai của tập dữ liệu được cho là 64 cm2. Vì vậy, độ lệch chuẩn là √64 hoặc 8 cm.

Bây giờ, 160 + 3 x (8) = 184, vì vậy số người cao hơn 184 cm tương ứng với tập dữ liệu con có nhiều hơn 3 độ lệch chuẩn so với mức trung bình.

Biểu đồ trên cho thấy điều này đại diện cho khoảng 0.1% dữ liệu. Tuy nhiên, tỷ lệ phần trăm này là gần đúng và trong trường hợp này, chúng ta cần độ chính xác cao hơn. Tỷ lệ phần trăm thực tế, chính xác đến 4 chữ số thập phân, là 0.1318%.

330.000 × 0.001318≈435

Vì vậy, sẽ có khoảng 435 người trong thị trấn cao hơn 184 cm

### Reference
https://www.varsitytutors.com/hotmath/hotmath_help/topics/normal-distribution-of-data
