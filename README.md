# selenium-file-upload-download
Selenium code for file upload and download from a demo site using java.
package exmoab;

import java.io.IOException:

public class fileup (

public static void main(String[] args) throws InterruptedException {

TODO Auto-generated method stub Systen.setProperty("webdriver.chrome.driver", "C:\ichamedriver.exe"); WebDriver driver-new ChromeDriver();

string baseUrl - "http://demo.guru99.com/test/upload/"; 1/WebDriver driver - new FirefoxDriver();

driver.get(baseurl);

WebElement uploadElement - driver, findElement(By.d("uploadfile_e"));

17 enter the file path onto the file-selection input field

uploadElement. sendkeys("c:\la.html"); I Il check the "I accept the terms of service check box

driver findElement(By.id("terms")).click();

/click the "uploadfile" button driver. FindElement(By.name("send").click():

