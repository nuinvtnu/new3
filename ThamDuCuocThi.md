```mermaid
%%{init: {'gantt': {'barHeight': 25, 'barGap': 15}}}%%
gantt
    title ICTU: KẾ HOẠCH TỔ CHỨC ÔN LUYỆN VÀ THAM DỰ CÁC CUỘC THI NĂM 2026
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
    Triển lãm Mỹ thuật Thái Nguyên (3 đợt) – 12M VNĐ :nttt1, 2026-06-01, 2026-10-31
    Triển lãm Mỹ thuật Tuyên Quang (2 đợt) – 8M VNĐ  :nttt2, 2026-05-01, 2026-09-30
    Triển lãm Mỹ thuật khu vực Tây Bắc (3 đợt) – 15M VNĐ :nttt3, 2026-04-01, 2026-09-30
