#Week 1 Objects, Memory models, and Scope

Class example:
```
public class SimpleLocation {
	public double latitude;
	public double longitude; 

	public SimpleLocation(double lat, double lon){
		this.latitude = lat; 
		this.longitude = lon; 
	}

	public double distance(SimpleLocation other){
		...
	}
}
```

Using the class:
```
public class LocationTester {
	public static void main(String[] args){
	SimpleLocation ucsd = SimpleLocation(32.9, -117.2);
	SimpleLocation lima = SimpleLocation(-12.0, -77.0);

	System.out.println(ucsd.distance(lima));
	}
}
```
