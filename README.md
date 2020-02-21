# Installation instructions

1. Download / Clone this  project to local folder
2. Open project in IDE (Eclipse)
3. Right Click on Project Maven --> Update Project

 ```
   Change tesseract data file path in Controller at 48th line to your local project download location
   instance.setDatapath("C:\\Users\\krishnareddy\\Downloads\\springboot-tesseract-ocr-master\\tessdata");
   
   Next create Environement variable TESSDATA_PREFIX = C:\\Users\\krishnareddy\\Downloads\\springboot-tesseract-ocr-master\\tessdata
   
   Check you have Microsift Visula C++ Redistribution, better to have 2019 version please download and install from 
   this link https://support.microsoft.com/en-in/help/2977003/the-latest-supported-visual-c-downloads  and second one VC_redist.x64
   
 ```

4. Right Click --> Run As --> Maven Install
5. Right Click --> Run As --> Spring Boot App
6. In browser open localhost:port/swagger-ui.html
7. Click on OCR Controller Tab click on try it out
8. At Destination Language Field enter eng
9. At file choose any image contains text
10. Execute you will see the result in response



