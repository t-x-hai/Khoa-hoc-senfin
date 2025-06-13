---
marp: true
size: 4:3
paginate: true
---

<style>
<!-- @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;600;700&display=swap'); -->
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');


:root {
  --bgColor-main: #FFFEF9;
  --bgColor-second: #B7C5D9;
  --primaryColor: #124B92;
  --textColor: #3a3a3a;
  font-size: 25px;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
}

header {
  color: var(--textColor);
  font-weight: 700;
  font-size: 25px;
}

.col-2 {
  display: flex;
  gap: 50px;
  justify-content: center;
  align-items: center;
}

img, table {
  display: block;
  margin: 0 auto;
}

section.section2 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

h1 {
  color: var(--primaryColor);
  font-weight: 700;
}

span {
  color: var(--primaryColor)
}

section::after {
  content: 'Page ' attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
  font-size: 16px;
}

</style>


# CHƯƠNG 2: PHÂN TÍCH BÁO CÁO THU NHẬP (PHẦN 2)
---
**1.1 Giới thiệu** 
Trong phần này, hai công cụ phân tích thường được sử dụng đối với báo cáo thu nhập sẽ được thảo luận là 

- Báo cáo kết quả hoạt động kinh doanh theo tỷ trọng (common-size analysis)
- Các chỉ số tài chính trong báo cáo thu nhập (income statement ratios)

---

**1.2** **Báo cáo kết quả hoạt động theo tỷ trọng** 

>Để thực hiện phương pháp này, các khoản mục trên báo cáo thu nhập sẽ được lấy và chia cho tổng doanh thu để thể hiện dưới dạng phần trăm

Từ đó giúp so sánh hiệu quả hoạt động qua các giai đoạn khác nhau (time series analysis) và giữa các công ty (cross-sectional analysis). Điều này là do việc chuẩn hóa từng khoản mục loại bỏ ảnh hưởng về quy mô, giúp việc so sánh trở nên dễ dàng và chính xác hơn

---

**1.3 Ví dụ** 
<div style="font-size: 0.65em; margin-left:12%">

**Báo cáo thu nhập của Vĩnh Hoàn (VHC)**
</div>

<div style="font-size: 0.55em; margin-left: 12%">

| CHỈ TIÊU | 2023 | % | 2024 | % |
| --- | --- | --- | --- | --- |
| Doanh số thuần | 10033.02 | 100.00% | 12512.79 | 100.00% |
| Giá vốn hàng bán | -8540.19 | -85.12% | -10617.75 | -84.86% |
| Lãi gộp | 1492.82 | 14.88% | 1895.04 | 15.14% |
| Thu nhập tài chính | 377.05 | 3.76% | 423.31 | 3.38% |
| Chi phí tài chính | -228.56 | -2.28% | -216.75 | -1.73% |
| Trong đó: Chi phí lãi vay | -133.35 | -1.33% | -73.33 | -0.59% |
| Lãi/(lỗ) từ công ty liên doanh | 0.80 | 0.01% | 2.24 | 0.02% |
| Chi phí bán hàng | -216.29 | -2.16% | -296.51 | -2.37% |
| Chi phí quản lý doanh  nghiệp | -307.66 | -3.07% | -357.77 | -2.86% |
| Lãi/(lỗ) từ hoạt động kinh doanh | 1118.16 | 11.14% | 1449.56 | 11.58% |
| Thu nhập khác | 50.02 | 0.50% | 66.28 | 0.53% |
| Chi phí khác | -23.16 | -0.23% | -31.22 | -0.25% |
</div>
<div style="font-size: 0.55em; margin-left: 79%">
Nguồn: SSI
</div>

---
**1.3 Ví dụ** 
<div style="font-size: 0.65em;margin-left: 15%">

**Báo cáo thu nhập của Vĩnh Hoàn (VHC)**
</div>

<div style="font-size: 0.45em;margin-left: 15%;">

| CHỈ TIÊU | 2023 | % | 2024 | % |
| --- | --- | --- | --- | --- |
| Thu nhập khác, ròng | 26.87 | 0.27% | 35.07 | 0.28% |
| Lãi/(lỗ) ròng trước thuế | 1145.03 | 11.41% | 1484.63 | 11.86% |
| Thuế thu nhập doanh nghiệp – hiện thời | -169.23 | -1.69% | -185.94 | -1.49% |
| Thuế thu nhập doanh nghiệp – hoãn lại | -2.04 | -0.02% | 3.96 | 0.03% |
| Chi phí thuế thu nhập doanh nghiệp | -171.27 | -1.71% | -181.98 | -1.45% |
| Lãi/(lỗ) thuần sau thuế | 973.76 | 9.71% | 1302.65 | 10.41% | 
</div>
<div style="font-size: 0.45em; text-align:right;margin-right:18%;">
Nguồn: SSI          
</div>
<div style="font-size: 0.55em">

**Phân tích** 

>Đối với VHC, tỷ trọng các khoản mục trên doanh thu không thay đổi quá nhiều mặc dù doanh thu thuần của doanh nghiệp tăng hơn 20% trong năm 2024 so với năm 2023 
→ Doanh nghiệp vẫn **quản lý tốt**, không bị hiện tượng đội chi phí do mở rộng hoạt động sản xuất kinh doanh 
Giá vốn chiếm **tỷ trọng lớn** trong báo cáo thu nhập 
→ Biến động liên quan đến **giá đầu vào của doanh nghiệp như giá thức ăn, giá thu mua cá** của nông dân sẽ **ảnh hưởng lớn** đến **khả năng sinh lời** của doanh nghiệp
Chi phí lãi vay gia tăng 
→ Doanh nghiệp đang **gia tăng vay vốn** để tài trợ cho hoạt động sản xuất kinh doanh 

---

**1.4 Các chỉ số tài chính trong báo cáo thu nhập**

>Một trong những thông tin quan trọng mà chỉ số tài chính trong báo cáo thu nhập mang lại là **khả năng sinh lời (profitability)**

Một số chỉ số hay được dùng là:
<div style="font-size: 0.75em;">


<div>
<div style="text-align: center;">
<img src="image 3.png"  width="650"/>
</div>

---

**1.5 Ví dụ** 
<div style="font-size: em; ">

**Các chỉ số tài chính trong báo cáo thu nhập của Vĩnh Hoàn**
</div>

<div style="font-size: em;margin-left:13%;">

| CHỈ TIÊU | 2023 | 2024 |
| --- | --- | --- |
| Biên lợi nhuận gộp | 14.88% | 15.14% |
| Biên lợi nhuận hoạt động | 11.14% | 11.58% |
| Biên lợi nhuận ròng | 9.71% | 10.41% |
</div>
<div style="font-size: 0.75em; text-align:right;margin-right:14%;">
 Nguồn: Tính toán từ báo cáo tài chính của VHC

---
</div>

**1.5 Ví dụ** 

**Phân tích** 
Mặc dù biên lợi nhuận gộp giảm nhưng biên lợi nhuận ròng tăng trong năm 2024 so với năm 2023

>Đặt trong bối cảnh mở rộng hoạt động sản xuất kinh doanh, doanh thu tăng trưởng mạnh hơn 20% trong năm 2024 so với năm 2023. Thì đây là tín hiệu rất tích cực bởi vì biên lợi nhuận ròng tăng cùng với tăng trưởng trong doanh thu → Doanh nghiệp đang phát triển cả chất và lượng, nguyên nhân có thể do cách chế biến chăn nuôi mới hoặc sản phẩm mới của Vĩnh Hoàn