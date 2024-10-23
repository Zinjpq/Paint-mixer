# Paint Mixer - TIA Portal Project

## Giới thiệu

Dự án **Paint Mixer** được phát triển trên **TIA Portal** nhằm điều khiển và giám sát quá trình trộn sơn tự động. Hệ thống bao gồm các thành phần chính như bể chứa sơn, bơm trộn, cảm biến mức và giao diện HMI để vận hành trực quan. Dự án này phù hợp với các ngành sản xuất yêu cầu trộn màu sơn theo tỉ lệ chính xác và tự động hóa cao.

## Tính năng

- Điều khiển tự động quá trình bơm và trộn sơn.
- Giám sát mức chất lỏng trong bể chứa.
- Hiển thị dữ liệu thời gian thực thông qua giao diện HMI.
- Cảnh báo khi có sự cố (mức thấp, quá tải, lỗi bơm).
- Điều chỉnh tỉ lệ trộn màu sơn thông qua HMI.
- Hỗ trợ nhiều công thức trộn khác nhau.
  
## Yêu cầu hệ thống

- **TIA Portal** v16 trở lên.
- **PLC Siemens S7-1200** hoặc cao hơn.
- **Màn hình HMI** (Ví dụ: KTP700 Basic).
- Các cảm biến và thiết bị ngoại vi (bơm, van, cảm biến mức, ...).

## Cài đặt

1. Tải dự án từ kho lưu trữ.
   ```bash
   git clone https://github.com/username/paint-mixer-tia-portal.git


    ├── PLC/
│   ├── MainProgram.ap16          # Chương trình chính điều khiển PLC
│   ├── Blocks/                  # Các khối hàm (FB, FC)
│   └── HMI/                     # Dự án giao diện HMI
├── Documentation/               # Tài liệu hướng dẫn sử dụng và kỹ thuật
└── README.md                    # Tệp README này

    ```

## Link youtube
https://youtu.be/vjInrGwB17w?si=SdYsBEPbvobO44qz
https://youtu.be/r2CklHVwUf4?si=vySAUYuNm1NQjRnk
