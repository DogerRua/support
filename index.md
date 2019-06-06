<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
    <head>
        <meta http-equiv=\"content-type\" content=\"text/html; charset=UTF-8\">
    </head>
    <style>
    body {
        margin: 0px;
        padding: 0px;
        font-size: 12px;
        background-color: black;
        text-align: center;
    }
    #container {
        margin: auto;
    }
    
    #form {
        margin-top: 60px;
    }
    
    h2 {
        color: #66CC33;
    }
    
    .upload {
        margin-top: 2px;
    }
    
    #submit input {
        background-color: #66CC33;
        color: #eee;
        font-weight: bold;
        margin-top: 10px;
        text-align: center;
        font-size: 16px;
        border: none;
        width: 120px;
        height: 36px;
    }
    
    #submit input:hover {
        background-color: #66CC00;
    }
    
    #submit input:active {
        background-color: #669900;
    }
    
    .uploadField {
        margin-top: 2px;
        width: 200px;
        height: 22px;
        font-size: 12px;
    }
    
    .uploadButton {
        background-color: #66CC33;
        color: #eee;
        font-weight: bold;
        text-align: center;
        font-size: 15px;
        border: none;
        width: 80px;
        height: 26px;
    }
    
    .uploadButton:hover {
        background-color: #66CC33;
    }
    
    .uploadButton:active {
        background-color: #669900;
    }
    
    </style>
    <body>
        <div id="container">
            <div id="form">
                <h2>WiFi File Upload</h2>
                <form name="form" action="upload.html" method="post" enctype="multipart/form-data" accept-charset="utf-8" accept="video/*">
                    <div class="upload">
                        <input type="file" name="upload1" id="upload1" style="display:none" onChange="document.form.path1.value=this.value">
                            <input class="uploadField" name="path1" readonly>
                                <input class="uploadButton" type="button" value="Open" onclick="document.form.upload1.click()">
                    </div>
                    <div class="upload">
                        <input type="file" name="upload2" id="upload2" style="display:none" onChange="document.form.path2.value=this.value">
                            <input class="uploadField" name="path2" readonly>
                                <input class="uploadButton" type="button" value="Open" onclick="document.form.upload2.click()">
                    </div>
                    <div class="upload">
                        <input type="file" name="upload3" id="upload3" style="display:none" onChange="document.form.path3.value=this.value">
                            <input class="uploadField" name="path3" readonly>
                                <input class="uploadButton" type="button" value="Open" onclick="document.form.upload3.click()">
                                    </div>
                    <div id="submit"><input type="submit" value="Submit"></div>
                </form>
            </div>
        </div>
    </body>
</html>

