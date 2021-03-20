# <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-00-33-icons8_panda_60px.png" width="40"> CHƯƠNG I: CƠ SỞ LOGIC

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-20-39-icons8-petition.png" title="" alt="icons8-petition.png" width="40"> 1. Mệnh đề

Mệnh đề là một khẳng định có giá trị `chân trị` xác định, `đúng` hoặc `sai`

>  ⚠️ Câu hỏi, câu cảm thán, mệnh lệnh,... không là **mệnh đề**

| Ký hiệu                               | Chân trị của mệnh đề                                                  | Ký hiệu chân trị                                         |
| ------------------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------- |
| `P`, `Q`, `R`... (`p`, `q`, `r`, ...) | Một mệnh đề chỉ có thể `đúng` hoặc `sai`, không thể vừa đúng vừa sai. | **Đúng** : `1` hay `Đ`,`T`<br>**Sai** : `0` hay `S`, `F` |

#### ![icons8-geometry.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-29-37-icons8-geometry.png) <u>Các phép toán:</u> có 5 phép toán

<details>
  <summary>
   <b>  <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-30-42-icons8-direction.png"> 1. Phép phủ định:</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-04-46-githubimg_phep_phu.PNG" width="90"> </summary>

 <u>Bảng chân trị: </u>

  ![bang_chan_tri_phep_phu.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-06-58-bang_chan_tri_phep_phu.PNG)

</details>

<details>
  <summary>
  <b>  <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-30-59-icons8-merge.png"> 2. Phép hội (nối liền, giao):</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-07-21-phep_giao.PNG" width="60">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-07-46-bang_chan_tri_phep_giao.PNG)

</details>

<details>
  <summary>
  <b>  <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-34-38-icons8-combine.png"> 3. Phép tuyển (nối rời, hợp:)</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-08-35-phep_hop.PNG" widtdh="20">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-08-58-bang_chan_tri_phep_hop.PNG)

</details>

<details>
  <summary>
  <b>  <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-35-09-icons8-hand_drag.png"> 4. Phép kéo theo:</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-09-23-phep_keo_theo.PNG" width="60"> , <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-09-35-luu_y_phep_keo_theo.PNG" >
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-10-09-bang_chan_tri_phep_keo_theo.PNG)

</details>

<details>
  <summary>
  <b>  <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-32-35-icons8-two_arrows_different_direction.png">5. Phép kéo theo 2 chiều (phép tương đương):</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-10-55-phep_tuong-duong.PNG" width="70"> , <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-11-15-luu_y_phep_tuong_duong.PNG" width="40">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-11-55-bang_chan_tri_phep_tuong_duong.PNG)

</details>

----

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/18-22-38-50-icons8-brain.png" title="" alt="icons8-brain.png" width="40"> 2. Biểu thức logic (Dạng mệnh đề)

 Biểu thức logic được cấu tạo từ: 

- Các mệnh đề (các hằng mệnh đề)
- Các biến mệnh đề `p`, `q`, `r`, ...
- Các phép toán logic

<details>
  <summary>
  <u><img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-22-01-21-icons8_example_50px.png" width="30">Ví dụ:</u>
  </summary>

  ![vd_bieu_thuc_logic.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-12-14-vd_bieu_thuc_logic.PNG)

</details>

> ![icons8_quote_26px.png](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-22-08-45-icons8_quote_26px.png) **<u>`Nhận xét:`</u>** Nếu có n biến mệnh đề thì ta có ![so_truong_hop.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-12-37-so_truong_hop.PNG) trường hợp chân trị cho bộ n biến.

### <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-13-46-icons8_high_risk_48px_1.png" title="" alt="icons8_high_risk_48px_1.png" width="35"> Các định lý lưu ý

| Định lý               | Ký hiệu                                                                                                                                                                                                                                                                                                                                                       | Mô tả                                                                                                                                                                                       | Lưu ý                                                                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Tương đương logic     | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-14-19-ky_hieu_tuong_duong_logic.PNG" title="" alt="asd" width="58">                                                                                                                                                                                                            | Khi `E` và `F` có **cùng bản chân trị**                                                                                                                                                     |                                                                                                                             |
| Hằng đúng<br>Hằng sai | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-14-38-dieu_kien_hang_dung.PNG" title="" alt="dieu_kien_hang_dung.PNG" width="55"><br><img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/03/20-13-13-26-18-20-14-49-dieu_kien_hang_sai.png" title="" alt="18-20-14-49-dieu_kien_hang_sai.png" width="53"> | Khi chân trị của `E` luôn bằng `1`<br>Khi chân trị của `E` luôn bằng `0`                                                                                                                    | <img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-15-04-1.PNG" alt="asd" width="144"> |
| Hệ quả logic          | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-50-ky_hieu_he_qua_logic.PNG" title="" alt="ky_hieu_he_qua_logic.PNG" width="54">                                                                                                                                                                                            | `F` là **hệ quả logic** của E nếu <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-31-e_keo_theo_f.PNG" title="" alt="e_keo_theo_f.PNG" width="56"> `đúng` | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-09-2.PNG" title="" alt="asd" width="173"> |

</details>

---

### <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-18-41-icons8_star_of_bethlehem_48px_3.png" title="" alt="icons8_star_of_bethlehem_48px_3.png" width="40"> **CÁC LUẬT LOGIC** (QUAN TRỌNG)

| Định luật                                                                              | Mô tả                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Phủ định của phủ định<br>Luỹ đẳng<br>Trung hoà<br>Thống trị<br>Phần tử bù<br>Giao hoán | <img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-19-29-phu_dinh_cua_phu_dinh.PNG" alt="" width="89"><br><img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-27-44-Luat_luy_dang.PNG" alt="" width="91"><br><img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-28-19-Luat_trung_hoa.PNG" alt="" width="90"><br><img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-30-21-Luat_thong_tri.PNG" alt="" width="95"><br><img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-29-22-Luat_ve_phan_tu_bu.PNG" alt="" width="106"><br><img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-23-56-Luat_giao_hoan.PNG" alt="" width="129"> |
| Qui tắc `De Morgan`                                                                    | <img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-22-26-De_Morgan.PNG" alt="" width="201">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Kết hợp                                                                                | <img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-24-54-Luat_ket_hop.PNG" alt="" width="200">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Phân phối                                                                              | <img title="" src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-26-51-Luat_phan_phoi.PNG" alt="" width="256">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Hấp thu                                                                                | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-31-03-Luat_hap_thu.PNG">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Kéo theo                                                                               | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-33-44-Luat_ve_phep_keo_theo.PNG">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Kéo theo 2 chiều                                                                       | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-36-01-Luat_ve_phep_keo_theo_2_chieu.PNG">                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
