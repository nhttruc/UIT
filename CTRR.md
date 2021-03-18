# <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-00-33-icons8_panda_60px.png" width="40"> CHƯƠNG I: CƠ SỞ LOGIC

<br>

## 1. Mệnh đề

> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-03-13-icons8_study_48px_1.png" width="25"> **<u>`Định nghĩa:`</u>** Mệnh đề là một khẳng định có giá trị `chân trị` xác định, `đúng` hoặc `sai`
> 
> Câu hỏi, câu cảm thán, mệnh lệnh,... không là mệnh đề

* **Ký hiệu:** P, Q, R... (p, q, r, ...)

* **Chân trị của mệnh đề:** Một mệnh đề chỉ có thể đúng hoặc sai, không thể vừa đúng vừa sai. Khi P đúng ta nói P có chân trị đúng, ngược lại là có chân trị sai.

* **Ký hiệu chân trị:** 
  
  * Đúng: 1 hay Đ, T
  
  * Sai: 0 hay S, F

#### <u>Các phép toán:</u> có 5 phép toán

<details>
  <summary>
   <b>1. Phép phủ định:</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-04-46-githubimg_phep_phu.PNG" width="90"> </summary>

 <u>Bảng chân trị: </u>

  ![bang_chan_tri_phep_phu.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-06-58-bang_chan_tri_phep_phu.PNG)

</details>

<details>
  <summary>
  <b>2. Phép hội (nối liền, giao):</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-07-21-phep_giao.PNG" width="60">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-07-46-bang_chan_tri_phep_giao.PNG)

</details>

<details>
  <summary>
  <b>3. Phép tuyển (nối rời, hợp:)</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-08-35-phep_hop.PNG" widtdh="20">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-08-58-bang_chan_tri_phep_hop.PNG)

</details>

<details>
  <summary>
  <b>4. Phép kéo theo:</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-09-23-phep_keo_theo.PNG" width="60"> , <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-09-35-luu_y_phep_keo_theo.PNG" >
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-10-09-bang_chan_tri_phep_keo_theo.PNG)

</details>

<details>
  <summary>
  <b>5. Phép kéo theo 2 chiều (phép tương đương):</b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-10-55-phep_tuong-duong.PNG" width="70"> , <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-11-15-luu_y_phep_tuong_duong.PNG" width="40">
  </summary>

   <u>Bảng chân trị:</u>

   ![bang_chan_tri_phep_giao.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-11-55-bang_chan_tri_phep_tuong_duong.PNG)

</details>

----

## 2. Biểu thức logic (Dạng mệnh đề)

> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-03-13-icons8_study_48px_1.png" width="25"> **<u>`Định nghĩa`</u>:** Biểu thức logic được cấu tạo từ: 
> 
> * Các mệnh đề (các hằng mệnh đề)
> 
> * Các biến mệnh đề p, q, r, ...
> 
> * Các phép toán logic

<details>
  <summary>
  <u><img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-22-01-21-icons8_example_50px.png" width="30">Ví dụ:</u>
  </summary>

  ![vd_bieu_thuc_logic.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-12-14-vd_bieu_thuc_logic.PNG)

</details>

> ![icons8_quote_26px.png](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-22-08-45-icons8_quote_26px.png) **<u>`Nhận xét:`</u>** Nếu có n biến mệnh đề thì ta có ![so_truong_hop.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-12-37-so_truong_hop.PNG) trường hợp chân trị cho bộ n biến.

<br>

![icons8_high_risk_48px_1.png](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-13-46-icons8_high_risk_48px_1.png)

<details>
  <summary>
    <b>Tương đương logic:</b>
  </summary>

* Hai biểu thức logic E và F được gọi là tương đương logic nếu chúng có `cùng bảng chân trị`
  
  Ký hiệu: ![ky_hieu_tuong_duong_logic.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-14-19-ky_hieu_tuong_duong_logic.PNG)

</details>

<details>
  <summary>
   <b>Hằng đúng, hằng sai:</b>
  </summary>

* Biểu thức logic E được gọi là hằng đúng nếu chân trị của các biến mệnh đề có trong E `luôn bằng 1`. Nói cách khác, E là hằng đúng khi ![dieu_kien_hang_dung.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-14-38-dieu_kien_hang_dung.PNG)

* Tương tự, E là hằng sai khi ![dieu_kien_hang_sai.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-14-49-dieu_kien_hang_sai.PNG)

</details>

<details>
  <summary>
  <b><u>Định lý:</u></b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-15-04-1.PNG">
  </summary>

>  Hai biểu thức logic E và F tương đương với nhau khi và chỉ khi ![e_tuong_duong_f.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-16-47-e_tuong_duong_f.PNG) là hằng đúng

</details>

<br>

<details>
  <summary>
  <b><u>Hệ quả logic:</u></b> <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-09-2.PNG">
  </summary>

> F được gọi là hệ quả logic của E nếu ![e_keo_theo_f.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-31-e_keo_theo_f.PNG) là hằng đúng
> 
> <u>Ký hiệu:</u> ![ky_hieu_he_qua_logic.PNG](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-17-50-ky_hieu_he_qua_logic.PNG)

</details>

<br>

---

### ![icons8_star_of_bethlehem_48px_3.png](https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-18-41-icons8_star_of_bethlehem_48px_3.png) **CÁC LUẬT LOGIC** (QUAN TRỌNG)

| 1. Phủ định của phủ định:                | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-19-29-phu_dinh_cua_phu_dinh.PNG">         |
|:----------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| **2. Quy tắc De Morgan:**                | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-22-26-De_Morgan.PNG">                     |
| **3. Luật giao hoán:**                   | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-23-56-Luat_giao_hoan.PNG">                |
| **4. Luật kết hợp:**                     | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-24-54-Luat_ket_hop.PNG">                  |
| **5. Luật phân phối:**                   | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-26-51-Luat_phan_phoi.PNG">                |
| **6. Luật luỹ đẳng:**                    | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-27-44-Luat_luy_dang.PNG">                 |
| **7. Luật trung hoà:**                   | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-28-19-Luat_trung_hoa.PNG">                |
| **8. Luật về phần tử bù:**               | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-29-22-Luat_ve_phan_tu_bu.PNG">            |
| **9. Luật thống trị:**                   | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-30-21-Luat_thong_tri.PNG">                |
| **10. Luật hấp thu:**                    | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-31-03-Luat_hap_thu.PNG">                  |
| **11. Luật về phép kéo theo:**           | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-33-44-Luat_ve_phep_keo_theo.PNG">         |
| **12. Luật về phép kéo theo hai chiều:** | <img src="https://raw.githubusercontent.com/nhttruc/Image/master/2021/03/18-20-36-01-Luat_ve_phep_keo_theo_2_chieu.PNG"> |

---