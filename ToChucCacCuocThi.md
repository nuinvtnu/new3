```mermaid
gantt
    title ICTU: KẾ HOẠCH TỔ CHỨC ÔN LUYỆN, THAM DỰ CÁC CUỘC THI NĂM 2026
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%y
    excludes    weekends

    %% =======================
    %% KHOA CNTT
    %% =======================
    section Khoa CNTT
    AWIRS 2026 – 50M VNĐ                     :cntt1, 2026-06-01, 2026-06-30
    SIC 2026 – 50M VNĐ                       :cntt2, 2026-07-01, 2026-07-31
    ATTT 2026 – 20M VNĐ                      :cntt3, 2026-09-01, 2026-09-30
    Olympic Tin học + AI – 350M VNĐ          :crit, cntt4, 2026-06-01, 2026-11-30
    Digital Dragons – 50M VNĐ                :cntt5, 2026-08-01, 2026-08-31
    ICPC Lập trình Quốc tế – 10M VNĐ         :cntt6, 2026-08-01, 2026-08-31

    %% =======================
    %% KHOA KT&CN
    %% =======================
    section Khoa KT&CN
    Robot VN + Robocon Châu Á – 360M VNĐ     :crit, ktcn1, 2026-08-01, 2026-11-30
    Thiết kế máy tự động hóa – 5M VNĐ        :ktcn2, 2026-09-01, 2026-09-30

    %% =======================
    %% KHOA KT&QT
    %% =======================
    section Khoa KT&QT
    Kinh doanh số 2026 – 15M VNĐ             :ktqt1, 2026-10-01, 2026-10-31

    %% =======================
    %% KHOA NT&TT
    %% =======================
    section Khoa NT&TT
    Triển lãm MT Thái Nguyên (3 đợt) – 12M VNĐ   :nttt1, 2026-06-01, 2026-10-31
    Triển lãm MT Tuyên Quang (2 đợt) – 8M VNĐ    :nttt2, 2026-05-01, 2026-09-30
    Triển lãm MT Tây Bắc (3 đợt) – 15M VNĐ       :nttt3, 2026-04-01, 2026-09-30

    %% =======================
    %% TÔ MÀU THEO ĐƠN VỊ
    %% (tùy môi trường GitHub hỗ trợ classDef)
    %% =======================
    classDef cntt fill:#0077CC,stroke:#004B80,color:#ffffff
    classDef ktcn fill:#B5651D,stroke:#8B4513,color:#ffffff
    classDef ktqt fill:#009966,stroke:#006644,color:#ffffff
    classDef nttt fill:#CC3366,stroke:#991F47,color:#ffffff

    class cntt1,cntt2,cntt3,cntt4,cntt5,cntt6 cntt
    class ktcn1,ktcn2 ktcn
    class ktqt1 ktqt
    class nttt1,nttt2,nttt3 nttt
```
