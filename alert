package org.test;
import org.openqa.selenium.Alert;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class alertcondition {

	public static void main(String[] args) throws InterruptedException {
		// TODO Auto-generated method stub
		System.setProperty("webdriver.chrome.driver","C:\\Users\\win\\Desktop\\chromedriver.exe");
		WebDriver driver=new ChromeDriver();
		driver.get(" http://demo.automationtesting.in/Alerts.html");
		
		
		
		WebElement button =driver.findElement(By.xpath("/html/body/div[1]/div/div/div/div[1]/ul/li[1]/a"));
		button.click();
		//WebElement frame1 =driver.findElement(By.xpath("//*[@id=\'CancelTab\']/button"));
		 driver.switchTo().defaultContent();
		//Thread.sleep(3000);
		 //driver.switchTo().frame(1);
		WebElement button1 =driver.findElement(By.xpath("//*[@id=\'OKTab\']/button"));
		button1.click();
		Alert alert1=driver.switchTo().alert();
		alert1.accept();
		
		
		
	   // driver.close();
	    driver.switchTo().defaultContent();
		
		WebElement button2 =driver.findElement(By.xpath("/html/body/div[1]/div/div/div/div[1]/ul/li[2]/a"));
		button2.click();
		//WebElement frame1 =driver.findElement(By.xpath("//*[@id=\'CancelTab\']/button"));
		 driver.switchTo().defaultContent();
		//Thread.sleep(3000);
		 //driver.switchTo().frame(1);
		WebElement button3 =driver.findElement(By.xpath("//*[@id=\'CancelTab\']/button"));
		button3.click();
		Alert alert2=driver.switchTo().alert();
		alert2.dismiss();
		
		
		
		
	//driver.close();
	driver.switchTo().defaultContent();
		WebElement button4 =driver.findElement(By.xpath("/html/body/div[1]/div/div/div/div[1]/ul/li[3]/a"));
		button4.click();
		//WebElement frame1 =driver.findElement(By.xpath("//*[@id=\'CancelTab\']/button"));
		 driver.switchTo().defaultContent();
		//Thread.sleep(3000);
		 //driver.switchTo().frame(1);
		WebElement button5 =driver.findElement(By.xpath("//*[@id=\'Textbox\']/button"));
		button5.click();
		
		Alert alert3=driver.switchTo().alert();
		//Thread.sleep(3000);
		alert3.sendKeys("THIRU");
		//Thread.sleep(5000);
		alert3.accept();
	//driver.close();
	
		
		
		
		
		
	//WebElement button1 =driver.findElement(By.name("btn btn-danger"));
	//button1.click();
	//Thread.sleep(3000);
	//Alert alert1=driver.switchTo().alert();
	//alert1.accept();
//driver.close();

	}
	
	

}
