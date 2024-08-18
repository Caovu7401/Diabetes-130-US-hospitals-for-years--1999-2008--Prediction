GIẢI THÍCH DỮ LIỆU:

encounter_id: ID của cuộc gặp (encounter) giữa bệnh nhân và bệnh viện, mỗi giá trị là duy nhất cho một lần nhập viện cụ thể.

patient_nbr: Số định danh bệnh nhân, sử dụng để nhận diện bệnh nhân duy nhất trong dữ liệu.

race: Chủng tộc của bệnh nhân (ví dụ: Caucasian, African American, Asian, Hispanic, etc.).

gender: Giới tính của bệnh nhân ('Male', 'Female').

age: Khoảng tuổi của bệnh nhân (ví dụ: '[0-10)', '[10-20)', '[20-30)', etc.).

weight: Cân nặng của bệnh nhân, thường có nhiều giá trị bị thiếu.

admission_type_id: Mã loại nhập viện, chỉ định lý do hoặc cách bệnh nhân nhập viện (ví dụ: cấp cứu, chuyển từ một cơ sở khác, tái nhập viện theo lịch hẹn, etc.).

discharge_disposition_id: Mã trạng thái xuất viện, chỉ định tình trạng hoặc hành động khi bệnh nhân rời bệnh viện (ví dụ: xuất viện về nhà, chuyển sang cơ sở chăm sóc khác, tử vong, etc.).

admission_source_id: Mã nguồn nhập viện, chỉ định nơi bệnh nhân đến trước khi nhập viện (ví dụ: phòng khám, cấp cứu, chuyển từ cơ sở khác, etc.).

time_in_hospital: Thời gian nằm viện của bệnh nhân tính theo số ngày.

payer_code: Mã nhà thanh toán, chỉ định đơn vị thanh toán chi phí y tế (ví dụ: bảo hiểm tư nhân, Medicare, Medicaid, etc.).

medical_specialty: Chuyên khoa y tế của bác sĩ phụ trách bệnh nhân (ví dụ: cardiology, endocrinology, surgery, etc.).

num_lab_procedures: Số lượng xét nghiệm được thực hiện trong suốt cuộc gặp.

num_procedures: Số lượng các thủ thuật không phải xét nghiệm được thực hiện (ví dụ: phẫu thuật, nội soi, etc.).

num_medications: Số lượng thuốc đã được kê đơn trong suốt cuộc gặp.

number_outpatient: Số lần bệnh nhân đã khám ngoại trú trước đó trong năm.

number_emergency: Số lần bệnh nhân đã nhập viện cấp cứu trước đó trong năm.

number_inpatient: Số lần bệnh nhân đã nhập viện nội trú trước đó trong năm.

diag_1: Chẩn đoán chính (diagnosis) tại thời điểm nhập viện, được mã hóa bằng ICD-9.

diag_2: Chẩn đoán thứ cấp thứ nhất (secondary diagnosis).

diag_3: Chẩn đoán thứ cấp thứ hai (tertiary diagnosis).

number_diagnoses: Tổng số chẩn đoán liên quan đến bệnh nhân trong suốt cuộc gặp.

max_glu_serum: Giá trị cao nhất của xét nghiệm glucose huyết thanh ('None', 'Norm', '>200', '>300').

A1Cresult: Kết quả của xét nghiệm A1C ('None', 'Norm', '>7%', '>8%').

metformin: Tình trạng kê đơn thuốc Metformin ('Up', 'Down', 'Steady', 'No').

repaglinide: Tình trạng kê đơn thuốc Repaglinide.

nateglinide: Tình trạng kê đơn thuốc Nateglinide.

chlorpropamide: Tình trạng kê đơn thuốc Chlorpropamide.

glimepiride: Tình trạng kê đơn thuốc Glimepiride.

acetohexamide: Tình trạng kê đơn thuốc Acetohexamide.

glipizide: Tình trạng kê đơn thuốc Glipizide.

glyburide: Tình trạng kê đơn thuốc Glyburide.

tolbutamide: Tình trạng kê đơn thuốc Tolbutamide.

pioglitazone: Tình trạng kê đơn thuốc Pioglitazone.

rosiglitazone: Tình trạng kê đơn thuốc Rosiglitazone.

acarbose: Tình trạng kê đơn thuốc Acarbose.

miglitol: Tình trạng kê đơn thuốc Miglitol.

troglitazone: Tình trạng kê đơn thuốc Troglitazone.

tolazamide: Tình trạng kê đơn thuốc Tolazamide.

examide: Tình trạng kê đơn thuốc Examide (trong dữ liệu này không có bệnh nhân nào sử dụng thuốc này).

citoglipton: Tình trạng kê đơn thuốc Citoglipton (trong dữ liệu này không có bệnh nhân nào sử dụng thuốc này).

insulin: Tình trạng kê đơn thuốc Insulin.

glyburide-metformin: Tình trạng kê đơn kết hợp thuốc Glyburide và Metformin.

glipizide-metformin: Tình trạng kê đơn kết hợp thuốc Glipizide và Metformin.

glimepiride-pioglitazone: Tình trạng kê đơn kết hợp thuốc Glimepiride và Pioglitazone.

metformin-rosiglitazone: Tình trạng kê đơn kết hợp thuốc Metformin và Rosiglitazone.

metformin-pioglitazone: Tình trạng kê đơn kết hợp thuốc Metformin và Pioglitazone.

change: Biến đổi tình trạng thuốc (nếu bệnh nhân được thay đổi đơn thuốc so với lần nhập viện trước thì giá trị là 'Ch').

diabetesMed: Chỉ ra liệu bệnh nhân có đang sử dụng thuốc tiểu đường hay không ('Yes', 'No').

OUTPUT/readmitted: Trạng thái bệnh nhân tái nhập viện ('<30': tái nhập viện trong vòng 30 ngày, '>30': tái nhập viện sau 30 ngày, 'No': không tái nhập viện).
