# Phần I : Cài đặt môi trường giả lập . 
## I. Dowload môi trường giả lập .
Hiện nay , Maker Hà Nội đã tạo ra được chương trình giả lập xe  trên 3 hệ điều hành khác nhau : Linux , Windows , MacOS.
Tùy theo từng hệ điều hành các bạn sử dụng , các bạn có thể dowload theo [link này .](https://github.com/makerhanoi/via-simulation-jeep/releases/tag/v0.1-alpha "Github Maker Hanoi")
![](https://i.imgur.com/Usr2cTl.png).

Nếu bạn sử dụng hệ điều hành : 
* Windows -> Select : via-simulation-windows-x86_64-20210314.zip
* Linux -> Select : via-simulation-linux-x86_64-20210314.zip
* MacOS -> Select : via-simulation-macos-x86_64-20210314.zip. 


Các bạn dowload các file zip về và giải nén file .

## II. Dowload source code
 Đầu tiên , các bạn [vào link này](https://github.com/makerhanoi/hello-via)
![](https://i.imgur.com/TUG9FiX.png)

 ->Select **Code**
 
 
![](https://i.imgur.com/DF7WLXg.png)
 -> **Dowload ZIP**

Các bạn dowload file về và giải nén 

## III. Dowload miniconda 3
Để có thể khởi động được xe , bạn cần cài đặt phần mềm [Miniconda 3](https://docs.conda.io/en/latest/miniconda.html)
Có các lựa chọn khác nhau , bạn dowload theo hệ điều hành mình sử dụng , như mình sẽ chọn **Windows Installers -> Python 3.8 -> Miniconda 3 Windows 64-bit**
Trong lúc cài đặt các bạn nhớ 1 số lưu ý sau : 
![](https://i.imgur.com/aSkRwc7.png)
![](https://i.imgur.com/VpDTeSq.png)

## IV. Thiết lập môi trường 


1. Chúng mình sẽ sử dụng **Visual Studio Code** nên các bạn có thể dowload [ở đây](https://code.visualstudio.com/download "Visual Studio Code ")
2. Open **File -> Open File -> hello-via-master** , các bạn sẽ thấy : 
![](https://i.imgur.com/OMZBOYn.png)
3. Cài đặt môi trường giả lập miniconda : **conda create -n <Tên môi trường> python=3.7**
 ![](https://i.imgur.com/Hf5KEZk.png)
 ![](https://i.imgur.com/9rE8HvV.png) 
 
 
 **-> y -> Enter**
 
 
4. Nhập lệnh **conda activate <Tên môi trường>** để khởi động môi trường
![](https://i.imgur.com/f4HfrqR.png)


5. Cài những gói cần thiết : **pip install -r requirements.txt**
![](https://i.imgur.com/Q8IbsCu.png)
