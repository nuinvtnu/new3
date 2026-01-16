```mermaid
gantt
    title ICTU: KẾ HOẠCH TỔ CHỨC VÀ THAM DỰ CÁC CUỘC THI NĂM 2026
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%y
    excludes    weekends

    %% ============================
    %% I. TỔ CHỨC CUỘC THI
    %% ============================
    section Tổ chức cuộc thi

    Sáng tạo Khởi nghiệp ICTU 2026 (PH KH-CN&HTQT)          :org1, 2026-01-01, 2026-08-31

    ESDEV 2026 (Khoa CNTT)                                  :org2, 2026-03-01, 2026-03-31
    IoT Hackathon 2026 (Khoa CNTT)                          :org3, 2026-03-01, 2026-03-31
    ICTU AI Golden Bell Challenge 2026 (Khoa CNTT)          :org4, 2026-03-01, 2026-03-31
    Programming Contest (2 lần) (Khoa CNTT)                 :org5, 2026-03-01, 2026-11-30
    ICTU OJ Challenge 2026 (2 lần) (Khoa CNTT)              :org6, 2026-05-01, 2026-11-30
    ICTU CTF Challenge 2026 (Khoa CNTT)                     :org7, 2026-08-01, 2026-08-31
    EIIC – Embedded & IoT Innovation Challenge (Khoa CNTT)  :org8, 2026-09-01, 2026-09-30
    OSS + AI 2026 (mã nguồn mở tích hợp AI, Khoa CNTT)      :org9, 2026-10-01, 2026-10-31
    ICTU Artificial Intelligence Challenge 2026 (Khoa CNTT) :org10, 2026-10-01, 2026-10-31

    Thiết kế vi mạch (Khoa KT&CN)                           :org11, 2026-02-01, 2026-04-30
    IoT Challenge 2026 (Khoa KT&CN)                         :org12, 2026-04-01, 2026-06-30
    Lái xe sinh thái tiết kiệm nhiên liệu (Khoa KT&CN)      :org13, 2026-07-01, 2026-07-31
    Vũ điệu ánh sáng (Khoa KT&CN)                           :org14, 2026-10-01, 2026-10-31
    Robot Sumo đối kháng (Khoa KT&CN)                       :org15, 2026-12-01, 2026-12-31
    Robocon ABU ICTU 2026 (Khoa KT&CN)                      :org16, 2026-12-01, 2026-12-31

    Thiết kế website TMĐT (Khoa KT&QT)                      :org17, 2026-04-01, 2026-04-30
    Kinh doanh số 2026 (Khoa KT&QT)                         :org18, 2026-08-01, 2026-08-31

    Cuộc thi sáng tạo nghệ thuật cùng AI (Khoa NT&TT)       :org19, 2026-02-01, 2026-06-30
    A&C's Talent Directors 2026 – Làm phim ngắn (Khoa NT&TT):org20, 2026-10-01, 2026-10-31

    %% ============================
    %% II. THAM DỰ CUỘC THI
    %% ============================
    section Tham dự cuộc thi

    SIC 2026 (Khoa CNTT)                                   :part1, 2026-06-01, 2026-06-30
    AWRIS 2026 – SV NCKH & Đổi mới Sáng tạo (Khoa CNTT)    :part2, 2026-08-01, 2026-08-31
    Digital Dragons Cybersecurity Challenge 2025 (CNTT)    :part3, 2026-08-01, 2026-08-31
    SV với ATTT 2026 (Khoa CNTT)                           :part4, 2026-09-01, 2026-09-30
    Vòng Khu vực ICPC Lập trình Quốc tế (Khoa CNTT)        :part5, 2026-10-01, 2026-10-31
    Olympic Tin học QG, mã nguồn mở & Olympic AI (CNTT)    :part6, 2026-12-01, 2026-12-31

    Sáng tạo Robot Việt Nam 2025 & ROBOCON Châu Á TBD (KT&CN) :part7, 2026-05-01, 2026-05-31
    Thiết kế máy tự động hóa (Khoa KT&CN)                     :part8, 2026-11-01, 2026-11-30

    Kinh doanh số 2026 – Tham dự (Khoa KT&QT)                 :part9, 2026-08-01, 2026-08-31

    Triển lãm Mỹ thuật tỉnh Thái Nguyên (Khoa NT&TT)          :part10, 2026-01-01, 2026-04-30
    Triển lãm Mỹ thuật tỉnh Tuyên Quang (Khoa NT&TT)          :part11, 2026-01-01, 2026-05-31
    Triển lãm Mỹ thuật khu vực 3 Tây Bắc – Việt Bắc (NT&TT)   :part12, 2026-06-01, 2026-06-30


```mermaid
    gantt
    DateFormat  YYYY-MM-DD
    axisFormat  %m/%y
    excludes    weekends

    section Khoa CNTT
    ESDEV 2026                              :cntt1, 2026-06-01, 30d
    IoT Hackathon 2026                      :cntt2, 2026-05-01, 30d
    Programming Contest Quý L1              :cntt3, 2026-03-01, 30d
    Programming Contest Quý L2              :cntt4, 2026-10-01, 30d
    AI Golden Bell Challenge 2026           :cntt5, 2026-09-01, 30d
    EIIC + IoT Challenge 2026               :crit, cntt6, 2026-08-01, 30d
    ICTU CTF Challenge 2026                 :cntt7, 2026-09-01, 30d
    OSS + AI Challenge 2026 (mã nguồn mở)   :cntt8, 2026-10-01, 30d
    ICTU OJ Challenge 2026 L1               :cntt9, 2026-04-01, 30d
    ICTU AI Challenge 2026                  :cntt10, 2026-07-01, 30d
    ICTU OJ Challenge 2026 L2               :cntt11, 2026-09-01, 30d

    section Khoa KT&CN
    Eco Driving Contest                     :ktcn1, 2026-08-01, 30d
    Robot Sumo                              :ktcn2, 2026-09-01, 30d
    Light Dance Contest                     :ktcn3, 2026-09-01, 30d
    IC Design                               :ktcn4, 2026-10-01, 30d
    Robocon ICTU                            :crit, ktcn5, 2026-10-01, 30d

    section Khoa KT&QT
    Digital Business 2026                   :ktqt1, 2026-09-01, 30d
    E-commerce Web Design                   :ktqt2, 2026-11-01, 30d

    section Khoa NT&TT
    Talent Directors 2026 (Film)            :nttt1, 2026-10-01, 30d
    AI Art Contest                          :nttt2, 2026-11-01, 30d

    section Khoa KHCB
    English Olympic                         :khcb1, 2026-09-01, 30d
