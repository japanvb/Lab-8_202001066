# Lab-8_202001066
# **Name : Japan Vijay Bhatt**
# **ID : 202001066**
# **Section A**

### **Final Boa class with all methods** <br>
```
public class Boa {
	private String name;
	private int length; // the length of the boa, in feet
	private String favoriteFood;
	
	public Boa (String name, int length, String favoriteFood){
		this.name = name;
		this.length = length;
		this.favoriteFood = favoriteFood;
	}
	// returns true if this boa constrictor is healthy
	public boolean isHealthy(){
		return this.favoriteFood.equals("granola bars");
	}
	// returns true if the length of this boa constrictor is
	// less than the given cage length
	public boolean fitsInCage(int cageLength){
		return this.length < cageLength;
	}
	
	public int lengthInInches() {
		return this.length * 12;
	}
 }
 ```
 
### **Test case to check healthy boa** <br>
![image](https://user-images.githubusercontent.com/123541695/233043134-4b654101-f72c-401d-8f8f-0b4d79188b2f.png) <br>
Here healthy boa is compared with true and unhealthy boa is compared with false. Hence, both the testcases are passed.<br><br>

### **Test case to check if boa fits in cage size less than boa size** <br>
![image](https://user-images.githubusercontent.com/123541695/233043515-29819469-2b9d-483b-bd15-25247477267a.png) <br>
Here the size of the cage is less than that of the boa. Hence the test case fails. <br><br>


### **Test case to check if boa fits in cage size equal to boa size** <br>
![image](https://user-images.githubusercontent.com/123541695/233043783-f7e22e65-9f75-42db-ae36-80d679c3b60e.png)<br>
Here the size of the cage is equal to that of the boa. Hence the test case fails. <br><br>

### **Test case to check if boa fits in cage size bigger than boa size** <br>
![image](https://user-images.githubusercontent.com/123541695/233044068-ea78d4ab-e03c-4ac6-bf87-306f73c96f5d.png) <br>
Here the size of the cage is greater than that of the boa. Hence the test case passes. <br><br>


### **Test case to check  if convert size of boa in inches (Passed test case)** <br>
![image](https://user-images.githubusercontent.com/123541695/233044637-ce914a7e-36dd-40a2-bf92-0310f110fecc.png) <br>
Here the length of Boa (2 feet) is compared with 24 inches, which is correct. Hence the test case passes. <br><br>


### **Test case to check  if convert size of boa in inches (Failed test case)** <br>
![image](https://user-images.githubusercontent.com/123541695/233044756-cc7a4cd1-a861-45e7-97c7-ba170c3abd94.png) <br>
Here the length of Boa (2 feet) is compared with 15 inches, which is wrong. Hence the test case fails. <br><br>


