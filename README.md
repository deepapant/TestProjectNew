# TestProjectNew                          
public class UptakeHomePage
{ webdriver driver; 
by HomePageTitle=By.id(""));
by IndustryPageNavigator= By.id("industry"); 
by IndustryPageTitle= By.name(""); 
public UptakeHomePage(WebDriver driver){
    this.driver = driver;
}
// go to home page// 
public void GotoHomePage()
{driver.Navigate().GoToUrl("http://uptake.com");}
// verify the home page//
public string verifyhomepagetitle() 
{ return string text=driver.findelement(HomePageTitle).gettext();
 assert.areequal(actualtitle,expectedtitle );}
// navigate to otherpage ex industries//
public void industrypage()
{drive.findelement(IndustryPageNavigator).click();}
//verify theindustry page//
public string getindustrypagetitle()
{ return strig industrypagetext= driver.findelement(IndustryPageTitle).gettext();
assert.areequal(actualtitle,expectedtitle);}
