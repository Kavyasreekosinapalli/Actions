# Actions

package testintroduction;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.Alert;
import org.openqa.selenium.By;
import org.openqa.selenium.interactions.Actions;

import io.github.bonigarcia.wdm.WebDriverManager;

public class actions {

	public static void main(String[] args) throws Exception {
		WebDriverManager.chromedriver().setup();
		
		WebDriver driver = new ChromeDriver();
		
		driver.manage().window().maximize();
		
		Actions actions = new Actions(driver);
		
		
		// action & click in demo application
		
//		driver.get("https://demo.automationtesting.in/Register.html");
//		
//		actions
//		.moveToElement(driver.findElement(By.xpath("//a[contains(text(),'Interactions')]")))
//		.moveToElement(driver.findElement(By.xpath("//a[contains(text(),'Drag and Drop')]")))
//		.moveToElement(driver.findElement(By.xpath("//a[contains(text(),'Static')]")))
//		.click()
//		.perform();
		
		//left click- click();
		//right click- context click();
		//mouse hovering-move to element();
		//double click -dou
				
		
		//double click in github
//		
//		driver.get("https://github.com/login");
//		driver.findElement(By.xpath("//input[@id='login_field']")).sendKeys("kavya");
//		actions.doubleClick(driver.findElement(By.xpath("//input[@id='login_field']"))).perform();

		
		//right click-context click
		
		driver.get("https://swisnl.github.io/jQuery-contextMenu/demo.html");
		actions.contextClick(driver.findElement(By.xpath("//span[.='right click me']"))).perform();
		Thread.sleep(3000);
		driver.findElement(By.xpath("//li[.='Edit']")).click();
		Thread.sleep(3000);
		Alert alert = driver.switchTo().alert();
		System.out.println(alert.getText());
		alert.accept();

	}

}
