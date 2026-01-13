```mermaid
gantt
    title ICTU: KẾ HOẠCH THAM DỰ CÁC CUỘC THI
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%y
    excludes    weekends

    section Khoa CNTT
    AWIRS 2026 – 50M VNĐ                          :cntt1, 2026-06-01, 30d
    SIC 2026 – 50M VNĐ                            :cntt2, 2026-07-01, 30d
    ATTT 2026 – 20M VNĐ                           :cntt3, 2026-09-01, 30d
    Olympic Tin học + Olympic AI – 350M VNĐ       :crit, cntt4, 2026-06-01, 2026-11-30
    Digital Dragons Cybersec – 50M VNĐ            :cntt5, 2026-08-01, 30d
    ICPC Lập trình Quốc tế – 10M VNĐ              :cntt6, 2026-08-01, 30d

    section Khoa KT&CN
    Robot VN + Robocon Châu Á TBD – 360M VNĐ      :crit, ktcn1, 2026-08-01, 2026-11-30
    Thiết kế máy tự động hóa – 5M VNĐ             :ktcn2, 2026-09-01, 30d

    section Khoa KT&QT
    Kinh doanh số 2026 – 15M VNĐ                  :ktqt1, 2026-10-01, 30d

    section Khoa NT&TT
    Triển lãm Mỹ thuật TN (3 đợt) – 12M VNĐ       :nttt1, 2026-06-01, 2026-10-31
    Triển lãm Mỹ thuật Tuyên Quang (2 đợt) – 8M VNĐ :nttt2, 2026-05-01, 2026-09-30
    Triển lãm Mỹ thuật Tây Bắc (3 đợt) – 15M VNĐ  :nttt3, 2026-04-01, 2026-09-30

    %% --- Tooltip mapping ---
    click cntt1 "KP: ôn luyện, tham dự, công tac phí"
    click cntt2 "KP: ôn luyện, tham dự, công tac phí"
    click cntt3 "KP: ôn luyện, tham dự, công tac phí"
    click cntt4 "Mời chuyên gia; hướng dẫn; lưu trú & CT phí"
    click cntt5 "KP: ôn luyện, tham dự, công tac phí"
    click cntt6 "KP: ôn luyện, tham dự, công tac phí"
    click ktcn1 "Mời chuyên gia; mua thiết bị; lưu trú & CT phí"
    click ktcn2 "Phí tham dự, công tac phí"
    click ktqt1 ""Phí tham dự, công tac phí""
    click nttt1 ""Phí tham dự, công tac phí: 3 đợt" 
    click nttt2 ""Phí tham dự, công tac phí: 2 đợt"
    click nttt3 ""Phí tham dự, công tac phí: 3 đợt"

    %% --- Color coding by faculty ---
    classDef cntt fill:#0077CC,stroke:#004B80,color:#fff
    classDef ktcn fill:#B5651D,stroke:#8B4513,color:#fff
    classDef ktqt fill:#009966,stroke:#006644,color:#fff
    classDef nttt fill:#CC3366,stroke:#991F47,color:#fff

    class cntt1,cntt2,cntt3,cntt4,cntt5,cntt6 cntt
    class ktcn1,ktcn2 ktcn
    class ktqt1 ktqt
    class nttt1,nttt2,nttt3 nttt

