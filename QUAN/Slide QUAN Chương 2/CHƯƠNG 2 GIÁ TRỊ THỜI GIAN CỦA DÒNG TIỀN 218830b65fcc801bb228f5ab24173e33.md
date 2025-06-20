---
marp: true
size: 4:3
paginate: true
---
# CHƯƠNG 2: GIÁ TRỊ THỜI GIAN CỦA DÒNG TIỀN

---
**1.1 Giới thiệu** 
<div style="font-size:0.9em">

> Khái niệm giá trị thời gian của tiền (Time Value of Money - TVM) cho rằng số tiền nhận được sớm có giá trị cao hơn số tiền nhận được sau này. 

>Do đó, một số tiền nhỏ hôm nay có thể có giá trị tương đương với một số tiền lớn hơn nhận được vào tương lai. TVM trong toán học đầu tư liên quan đến các mối quan hệ tương đương giữa các dòng tiền ở các thời điểm khác nhau
</div>

---

**1.2 Lãi suất** 
<div style="font-size:0.9em">

**Công thức xác định tỷ lệ lãi suất**

>r = Tỷ lệ lãi suất không rủi ro thực tế + Phần bù lạm phát + Phần bù rủi ro vỡ nợ + Phần bù thanh khoản + Phần bù kỳ hạn

</div>
<div style="font-size:0.7em">

- **Tỷ lệ lãi suất phi rủi ro**: Là tỷ lệ lãi suất cho một tài sản hoàn toàn không rủi ro trong một kỳ hạn đơn khi không có lạm phát dự kiến

- **Phần bù lạm phát**: Bù đắp cho nhà đầu tư sự mất giá trị của đồng tiền do lạm phát, phản ánh tỷ lệ lạm phát trung bình dự kiến trong suốt kỳ hạn của khoản nợ

- **Phần bù rủi ro vỡ nợ**: Bù đắp cho nhà đầu tư về khả năng người vay không trả được khoản tiền đã hứa đúng thời gian và số tiền đã thỏa thuận

- **Phần bù thanh khoản**: Bù đắp cho nhà đầu tư về rủi ro mất giá trị khi cần chuyển đổi đầu tư thành tiền mặt nhanh chóng

- **Phần bù kỳ hạn**: Bù đắp cho nhà đầu tư về sự nhạy cảm của giá trị thị trường của nợ đối với sự thay đổi của tỷ lệ lãi suất khi thời gian đáo hạn được kéo dài
</div>

---

**1.2 Lãi suất** 

<div style="font-size:0.9em">

**Lãi suất hằng năm (APR)**

>Lãi suất hằng năm là mức lãi đơn được tính theo năm

→ Đây là mức lãi suất hay được niêm yết trên các sản phẩm tài chính 

**Lãi suất hiệu quả (EAR)**

>Khi lãi kép được tính và trả nhiều kỳ trong năm (ví dụ: hàng quý, hàng tháng, hàng ngày), lãi suất thực hưởng mỗi năm sẽ lớn hơn mức lãi suất hằng năm do được tính trên cả phần lãi gộp của kỳ trước. Lãi suất thực hưởng được tính bằng công thức
</div>
<div style="font-size:0.9em; margin-left:20%">

$EAR = \left(1 + \frac{APR}{\text{số kỳ trong năm}}\right)^{\text{số kỳ trong năm}} - 1$
</div>

---

**1.2 Lãi suất** 

>**Ví dụ**: Ngân hàng Vietcombank niêm yết lãi suất tiền gửi có kỳ hạn 6 tháng là 2.9% (Lãi suất APR)

→ Lãi suất EAR theo năm là 

$$
= \left(1 + \frac{0.029}{\text{2}}\right)^{\text{2}} - 1 = 0.292
$$

---

**1.3 Giá trị hiện tại và giá trị tương lai** 

>Công thức tổng quan mối quan hệ giữa giá trị hiện tại (PV) và giá trị tương lai (FV) 

$$
PV = \frac{FV}{(1 + r)^n}
$$

**Chú thích**

r: Lãi suất chiết khấu 

n: Số kỳ chiết khấu

PV: Giá trị hiện tại

FV: Giá trị tương lai

---

**1.3 Giá trị hiện tại và giá trị tương lai** 

>**Ví dụ** 

- **FV = 1,000,000 VND**
- **r = 7% = 0.07**
- **n = 5 năm**

Thay vào công thức

$$
PV = \frac{1,000,000}{(1 + 0.07)^5}
$$

$$
PV = \frac{1,000,000}{1.40255} \approx 712,986 \, \text{VND}
$$

---

**1.4 Dòng tiền niên kim (Annuity)**

>Là dòng tiền đều, phát sinh trong một khoảng thời gian nhất định
<div style="font-size:0.75em">

>**Ví dụ**: Trong vòng 10 năm, mỗi năm nhận đều đặn 10 triệu VND

**Trả đầu kỳ** 

$$
PV = A \times \left[ \frac{1}{r} - \frac{1}{r\left(1 + r \right)^n} \right] \times (1 + r)
$$

**Trả cuối kỳ** 

$$
PV = A \times \left[ \frac{1}{r} - \frac{1}{r(1 + r)^n} \right]
$$

A: Giá trị dòng tiền trả đều mỗi kỳ 

r: Lãi suất chiết khấu

n: Số kỳ 
</div>

---

**1.4 Dòng tiền niên kim (Annuity)** 

<div style="font-size:0.85em">

>**Ví dụ**: Đầu tư vào một dự án niên kim, với mức trả mỗi năm là 10 triệu VND trong vòng 5 năm. Tỷ lệ lãi suất hàng năm là 7%. Tính PV của dự án trong trường hợp

**Trả đầu kỳ** 

$$
PV = 10 \times \left[ \frac{1}{0.07} - \frac{1}{0.07\left(1 + 0.07 \right)^5} \right] \times (1 + 0.07)= 43.87
$$

**Trả cuối kỳ** 

$$
PV = 10 \times \left[ \frac{1}{0.07} - \frac{1}{0.07(1 + 0.07)^5} \right] = 41
$$
</div>

---

**1.5 Dòng tiền niên kim vĩnh cửu (Perpetuity)**


>Là dòng tiền đều, trả cuối kỳ, không bao giờ kết thúc
<div style="font-size:0.85em">

>**Ví dụ**: Nhận đều đặn 10 triệu VND mỗi năm, bắt đầu từ hôm nay và sẽ tiếp tục nhận suốt đời mà không có thời gian kết thúc

**Công thức**

$$
PV = \frac{A}{r}
$$

A: Dòng tiền trả hàng kỳ 

r: Lãi suất chiết khấu 
</div>

---

**1.5 Dòng tiền niên kim vĩnh cửu (Perpetuity)**
<div style="font-size:0.85em">

>**Ví dụ:** Nhận đều đặn 10 triệu VND mỗi năm, bắt đầu từ hôm nay và sẽ tiếp tục nhận suốt đời mà không có thời gian kết thúc, lãi suất chiết khấu 7%. Tính PV của dòng tiền này 

$$
PV = \frac{10}{0.07}= 142.86 
$$
</div>