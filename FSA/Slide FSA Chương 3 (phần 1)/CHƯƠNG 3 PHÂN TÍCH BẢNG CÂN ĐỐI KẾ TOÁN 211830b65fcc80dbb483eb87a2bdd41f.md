---
title: "Chương 5 - Trực quan hóa số liệu"
marp: true
size: 4:3
paginate: true
author: "khanh"
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
# CHƯƠNG 3: PHÂN TÍCH BẢNG CÂN ĐỐI KẾ TOÁN (PHẦN 1)

---
<div style="font-size: 0.85em">

**1.1 Giới thiệu** 

> Bảng cân đối kế toán là một lát cắt (snapshot) về tình hình tài sản và nguồn vốn của doanh nghiệp tại một thời điểm  

→ Là bức tranh tổng thể về tình hình tài chính của doanh nghiệp

> Tại Việt Nam, mỗi quý một lần các doanh nghiệp sẽ phải cập nhật bảng cân đối kế toán 

Mối quan hệ trong bảng cân đối kế toán: 

> Tổng tài sản = Vốn chủ sở hữu + Tổng nợ phải trả

**Các hình thức trình bày** 

Dựa trên các khoản mục ngắn hạn và dài hạn (phổ biến hơn tại Việt Nam)

Dựa trên tính thanh khoản
</div>

---

**1.2 Các khoản mục cơ bản trong một bảng cân đối kế toán** 
<div style="font-size: 0.85em; margin-left: 25%">

**Tài sản ngắn hạn (Current assets)**
</div>

<div style="font-size: 0.5em;">

| **Khoản mục** | **Giải thích**  |
| --- | --- |
| **Tài sản ngắn hạn khác** *(Other current assets)* | Là những tài sản có giá trị nhỏ hoặc ít phổ biến, không đủ để xếp thành một mục riêng nhưng vẫn đáp ứng điều kiện ngắn hạn và có thể chuyển đổi thành tiền trong vòng một năm. |
| **Chi phí trả trước** *(Prepaid expenses)* | Đây là các khoản chi phí doanh nghiệp đã thanh toán trước nhưng chưa được ghi nhận là chi phí trong kỳ, ví dụ như tiền thuê văn phòng hay phí bảo hiểm đã trả cho nhiều tháng tới. |
| **Hàng tồn kho** *(Inventories)* | Gồm tất cả vật tư, nguyên liệu, sản phẩm dở dang và thành phẩm đang được giữ lại để bán hoặc dùng trong sản xuất. Đây là nguồn hàng hóa giúp doanh nghiệp duy trì hoạt động kinh doanh. |
| **Khoản phải thu khách hàng** *(Trade receivables)* | Là số tiền khách hàng nợ doanh nghiệp do đã nhận hàng hoặc dịch vụ nhưng chưa thanh toán. Đây là một phần quan trọng trong quản lý dòng tiền. |
| **Chứng khoán thương mại** *(Marketable securities)* | Là các khoản đầu tư ngắn hạn vào cổ phiếu hoặc trái phiếu có tính thanh khoản cao và có thể được chuyển đổi nhanh chóng thành tiền mặt trên thị trường. |
| **Tiền và tương đương tiền** *(Cash and cash equivalents)* | Bao gồm tiền mặt và các khoản đầu tư cực kỳ an toàn, dễ dàng chuyển đổi thành tiền trong thời gian ngắn, thường dùng để đáp ứng nhu cầu thanh toán tức thì. |

</div>

---

**1.2 Các khoản mục cơ bản trong một bảng cân đối kế toán** 

<div style="font-size: 0.85em; margin-left: 25%">

**Tài sản dài hạn (Non-current assets)**
</div>

<div style="font-size: 0.5em;">

| **Khoản mục** | **Giải thích**  |
| --- | --- |
| **Tài sản thuế thu nhập hoãn lại** *(Deferred tax assets)* | Là quyền được khấu trừ thuế trong tương lai, phát sinh từ các chênh lệch tạm thời, lỗ thuế chưa sử dụng hoặc các ưu đãi thuế chưa khai thác. |
| **Tài sản tài chính** *(Financial assets)* | Gồm các khoản đầu tư tài chính dài hạn như trái phiếu, cổ phiếu hoặc công cụ phái sinh, mang lại quyền sở hữu hoặc lợi ích kinh tế trong tương lai. |
| **Lợi thế thương mại** *(Goodwill)* | Là phần giá trị vượt trội khi một công ty mua lại công ty khác, thể hiện thương hiệu, danh tiếng và mối quan hệ khách hàng mà không thể tách rời. |
| **Tài sản vô hình** *(Intangible assets)* | Là những tài sản không có hình dạng vật chất như bằng sáng chế, bản quyền, phần mềm, thương hiệu, có giá trị sử dụng lâu dài cho doanh nghiệp. |
| **Bất động sản đầu tư** *(Investment property)* | Gồm nhà đất được sở hữu nhằm mục tiêu thu lợi từ cho thuê hoặc tăng giá, không phục vụ cho hoạt động kinh doanh chính. |
| **Bất động sản, nhà xưởng và thiết bị (PPE)** *(Property, Plant & Equipment)* | Là tài sản hữu hình như đất đai, nhà máy, máy móc, được sử dụng lâu dài trong hoạt động sản xuất hoặc vận hành của doanh nghiệp. |
</div>

---

**1.2 Các khoản mục cơ bản trong một bảng cân đối kế toán** 

<div style="font-size: 0.85em; margin-left: 25%">

**Nợ phải trả ngắn hạn (Current liabilities)**
</div>
<div style="font-size: 0.6em;">

| **Khoản mục** | **Giải thích** |
| --- | --- |
| **Thu nhập hoãn lại / Doanh thu chưa thực hiện** *(Deferred income / Unearned revenue)* | Là khoản tiền doanh nghiệp đã nhận trước từ khách hàng, nhưng chưa cung cấp hàng hóa hoặc dịch vụ tương ứng. |
| **Chi phí dồn tích** *(Accrued expenses)* | Các chi phí đã phát sinh trong kỳ kế toán nhưng chưa được chi trả tại thời điểm lập báo cáo tài chính. |
| **Khoản nợ phải trả tài chính** *(Financial liabilities)* | Là nghĩa vụ trả nợ phát sinh từ các khoản vay ngắn hạn với tổ chức tín dụng hoặc bên cho vay khác theo hợp đồng. |
| **Khoản phải trả nhà cung cấp** *(Trade payables)* | Số tiền doanh nghiệp còn nợ các nhà cung ứng hàng hóa hoặc dịch vụ đã nhận mà chưa thanh toán. |
</div>

---

**1.2 Các khoản mục cơ bản trong một bảng cân đối kế toán** 

<div style="font-size: 0.85em; margin-left: 25%">

**Nợ phải trả dài hạn (Long-term liabilities)**
</div>
<div style="font-size: 0.7em;">

| **Khoản mục** | **Giải thích**  |
| --- | --- |
| **Thuế thu nhập doanh nghiệp hoãn lại phải trả** *(Deferred tax liabilities)* | Là số thuế doanh nghiệp sẽ phải nộp trong tương lai do sự khác biệt về thời điểm ghi nhận doanh thu/chi phí giữa chuẩn mực kế toán và quy định thuế. |
| **Khoản nợ tài chính dài hạn** *(Long-term financial liabilities)* | Bao gồm các nghĩa vụ tài chính kéo dài trên một năm như khoản vay ngân hàng, trái phiếu, hoặc thương phiếu mà doanh nghiệp cam kết thanh toán trong tương lai. |
</div>

---

**1.2 Các khoản mục cơ bản trong một bảng cân đối kế toán** 
<div style="font-size: 0.85em; margin-left: 25%">

**Vốn chủ sở hữu (Owner’s equity)**
</div>
<div style="font-size: 0.55em;">

| **Khoản mục** | **Giải thích**  |
| --- | --- |
| **Lợi nhuận sau thuế chưa phân phối** *(Retained earnings)* | Là phần lợi nhuận giữ lại sau khi chia cổ tức, được tích lũy qua các năm để tái đầu tư hoặc trích lập các quỹ nội bộ. |
| **Quỹ đầu tư phát triển, quỹ dự phòng** *(Development and reserve funds)* | Là các khoản quỹ được trích lập từ lợi nhuận sau thuế nhằm phục vụ các mục đích cụ thể như tái đầu tư, ổn định tài chính, hoặc phòng ngừa rủi ro. |
| **Chênh lệch đánh giá lại tài sản, chênh lệch tỷ giá** *(Revaluation surplus / Foreign exchange difference)* | Là phần chênh lệch phát sinh khi điều chỉnh lại giá trị tài sản hoặc do thay đổi tỷ giá, chưa thực hiện nhưng được ghi nhận vào vốn chủ sở hữu. |
| **Cổ phiếu quỹ** *(Treasury shares)* | Là cổ phiếu mà công ty mua lại từ thị trường và nắm giữ; được ghi âm vào vốn chủ sở hữu vì làm giảm giá trị thực có của cổ đông. |
| **Cổ phiếu ưu đãi/cổ phiếu phổ thông** *(Preferred / Common stock)* | Là vốn huy động từ phát hành cổ phần cho nhà đầu tư, phân loại theo quyền lợi và nghĩa vụ khác nhau giữa cổ đông phổ thông và cổ đông ưu đãi. |
| **Vốn góp của chủ sở hữu** *(Owner’s contributed capital)* | Là phần vốn gốc ban đầu do các nhà đầu tư, cổ đông sáng lập đóng góp để thành lập hoặc mở rộng doanh nghiệp. |
</div>