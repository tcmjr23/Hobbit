# Hobbit
This project involves manipulating the class hierarchy to print the desired elements of an ArrayList.


//constructor
# public Traveler(String name)
	{
		this.distanceTraveled = 0;
		this.name = name;
	}
 the constructor for the superclass
  public void travel(int miles)
	{
		distanceTraveled += miles;
	
  }
 method in Traveler that adds miles to their distance traveled field.
 
 # public Dwarf(String name)
	{
		super(name);
	}
 constructor for subclass. Calls the superclass constructor
 
 # public Hobbit(String name)
	{
		super(name);
		ringObsessed=false;
	}
  constructor for subclass. Automatically assigns ringObsessed field to false. 
  
  # public Wizard(String name)
	{
		super(name);
	}
	
	public void travel(int miles)
	{
		super.travel(3*miles);
	}
 travel method for Wizard. is 3 times the set distance.
 
 
 This project shows how hierarchys and polymorphism affect how we write code. It is a tool to make concise, easy to manage projects while using minimal code. 
