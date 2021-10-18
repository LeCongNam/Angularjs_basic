# Là những bộ lọc được định dạng sẵn
{{value | number: [sỗ chữ số thập phân đc định dạng] }}
{{value | currency: [dv tiền tệ]: [sỗ chữ số thập phân đc định dạng] }}

# Date
- day-month-year: 'dddd-MMMM-YYYY'
- Thứ: 'EEEE' hoặc 'EEE';
- Hour-minute-secon: 'hh-mm-ss '
- Sáng chiều(AM/PM): 'a/p'

# String
- uppercase 
- lower case


## Tất cả bộ lọc chỉ  áp dụng với các mảng không áp dụng với các dữ liệu khác 
## bộ lọc limitTo
- ng-repeat="sv in sinhvien | limitTo: limit: start";
## bộ lọc filter
<div ng-repeat= " sv in sinhvien | fiter: expression: comparator" ></div>
- comparator: nếu là true sẽ lọc chính xác. Nếu là false thì sẽ lọc tượng đối với tất cả thuộc tính. 
