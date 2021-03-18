# ![icons8_panda_30px_4.png](C:\Users\Taurus\AppData\Local\Temp\icons8_panda_30px_4.png) CHƯƠNG I: CƠ SỞ LOGIC

<br>

## 1. Mệnh đề

> **<u>Định nghĩa:</u>** Mệnh đề là một khẳng định có giá trị `chân trị` xác định, `đúng` hoặc `sai`
> 
> Câu hỏi, câu cảm thán, mệnh lệnh,... không là mệnh đề

* **Ký hiệu:** P, Q, R... (p, q, r, ...)

* **Chân trị của mệnh đề:** Một mệnh đề chỉ có thể đúng hoặc sai, không thể vừa đúng vừa sai. Khi P đúng ta nói P có chân trị đúng, ngược lại là có chân trị sai.

* **Ký hiệu chân trị:** 
  
  * Đúng: 1 hay Đ, T
  
  * Sai: 0 hay S, F

#### <u>Các phép toán:</u> có 5 phép toán

<details>
<summary> 1. **Phép phủ định:** <img src="D:\NHTT_Taurus\3_Taurus_Image\Github_img\githubimg_phep_phu.PNG"> </summary>

 <u>Bảng chân trị: </u>
   
   <img src="D:\NHTT_Taurus\3_Taurus_Image\Github_img\bang_chan_tri_phep_phu.PNG">

</details>

2. **Phép hội (nối liền, giao):** ![phep_giao.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\phep_giao.PNG)
   
   <u>Bảng chân trị:</u>
   
   ![bang_chan_tri_phep_giao.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\bang_chan_tri_phep_giao.PNG)

3. **Phép tuyển (nối rời, hợp:)** ![phep_hoi.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\phep_hoi.PNG)
   
   <u>Bảng chân trị:</u>
   
   ![bang_chan_tri_phep_hop.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\bang_chan_tri_phep_hop.PNG)

4. **Phép kéo theo:** ![phep_keo_theo.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\phep_keo_theo.PNG) , ![luu_y_phep_keo_theo.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\luu_y_phep_keo_theo.PNG)
   
   <u>Bảng chân trị:</u>
   
   ![bang_chan_tri_phep_keo_theo.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\bang_chan_tri_phep_keo_theo.PNG)
   
   > Chỉ `sai` khi `P đúng`, `Q sai`

5. **Phép kéo theo 2 chiều (phép tương đương):** ![phep_tuong-duong.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\phep_tuong-duong.PNG) , ![luu_y_phep_tuong_duong.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\luu_y_phep_tuong_duong.PNG)
   
   <u>Bảng chân trị:</u>
   
   ![bang_chan_tri_phep_tuong_duong.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\bang_chan_tri_phep_tuong_duong.PNG)
   
   > Chỉ `đúng` khi cả `P và Q có cùng chân trị`

----

## 2. Biểu thức logic (Dạng mệnh đề)

> **<u>Định nghĩa</u>:** Biểu thức logic được cấu tạo từ: 
> 
> * Các mệnh đề (các hằng mệnh đề)
> 
> * Các biến mệnh đề p, q, r, ...
> 
> * Các phép toán logic

<u>Ví dụ:</u>

![vd_bieu_thuc_logic.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\vd_bieu_thuc_logic.PNG)

> **<u>Nhận xét:</u>** Nếu có n biến mệnh đề thì ta có ![so_truong_hop.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\so_truong_hop.PNG) trường hợp chân trị cho bộ n biến.



![icons8_high_risk_48px.png](C:\Users\Taurus\AppData\Local\Temp\icons8_high_risk_48px.png)

##### Tương đương logic:

* Hai biểu thức logic E và F được gọi là tương đương logic nếu chúng có `cùng bảng chân trị`
  
  Ký hiệu: ![ky_hieu_tuong_duong_logic.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\ky_hieu_tuong_duong_logic.PNG)

##### Hẳng đúng, hằng sai:

* Biểu thức logic E được gọi là hằng đúng nếu chân trị của các biến mệnh đề có trong E `luôn bằng 1`. Nói cách khác, E là hằng đúng khi ![dieu_kien_hang_dung.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\dieu_kien_hang_dung.PNG).

* Tương tự, E là hằng sai khi ![dieu_kien_hang_sai.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\dieu_kien_hang_sai.PNG)

<br>

**<u>Định lý:</u>** ![1.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\1.PNG)

>  Hai biểu thức logic E và F tương đương với nhau khi và chỉ khi ![e_tuong_duong_f.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\e_tuong_duong_f.PNG) là hằng đúng

<br>

**<u>Hệ quả logic:</u>** ![2.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\2.PNG)

> F được gọi là hệ quả logic của E nếu ![e_keo_theo_f.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\e_keo_theo_f.PNG) là hằng đúng
> 
> <u>Ký hiệu:</u> ![ky_hieu_he_qua_logic.PNG](D:\NHTT_Taurus\3_Taurus_Image\Github_img\ky_hieu_he_qua_logic.PNG)
