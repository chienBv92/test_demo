#Những chú ý khi chạy code iSeiQ lần đầu khi gặp error

1. Giải nén thư mục .nuget.zip thành folder .nuget trong folder source code

2. Cài đặt drive ExcelCreator 10
ExcelCreator10Demo_1330.zip

3. Thêm các file sau vào folder iEnterAsia.iseiQ\App_Data của folder source code
.develop
staging
.staging
develop

4. add reference System.Web.Mvc.dell cho từng project trong folder source code

5. Chạy code nếu lỗi debug ở iEnterAsia.iseiQ\Global.asax
Hàm protected void Application_Error(Object sender, EventArgs e)
Exception ex = Server.GetLastError();

6. Vẫn Không chạy được hỏi a GiangVT