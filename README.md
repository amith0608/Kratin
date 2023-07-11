import java.util.*; class Healthcare { public static void main(String args[]) { Scanner sc=new Scanner(System.in);

    System.out.println("Enter the Patient's name");

    String name=sc.nextLine();

    System.out.println("Name of the Patient is" +name);

    System.out.println("Enter the location of patient\nChoice Bengaluru, Chennai, Mysore, Udupi");

    String city=sc.nextLine();

    switch(city)
   {
       case "Bengaluru":

           System.out.println("She is from Bengaluru");

           break;

       case "Chennai":

           System.out.println("She is from Chennai");

           break;

        case "Mysore":
            System.out.println("She is from Mysore");
            break;
        case "Udupi":
            System.out.println("She is from Udupi");
            break;
            default:
        System.out.println(“Invalid City”);
}   
    System.out.println("Enter the location of Hospital\nChoice Agra, Mohali, Pune, Hyderabad");
    String hospital=sc.nextLine();
    switch(hospital)
   {
       case "Agra":
           System.out.println("hospital is in Agra");
           break;
       case "Mohali":
           System.out.println("hospital is in Mohali");
           break;
        case "Pune":
            System.out.println("hospital is in Pune");
            break;
        case "Hydrabad":
            System.out.println("Hospital is in Hydrabad");
            break;
            default:
        System.out.println("Hospital is not availabel");
   }
   System.out.println("Enter the name of hospital\nSikkim, Agartala, Patna");
   String nhp=sc.nextLine();
   switch(nhp)
   {
       case "Sikkim":
           System.out.println("Meyo Sikkim");
           break;
       case "Agartala":
           System.out.println("Kukde Agartala");
           break;
        case "Patna":
            System.out.println("Neuron Patna");
            break;
}   
 System.out.println("Enter the Patient mobile number");
    String phn=sc.nextLine();
System.out.println("The mobile number of patient is  "+phn );
    System.out.println("Enter the Hospitalphone no");
    String phn1=sc.nextLine();
    switch(phn1)
   {
       case "Bengaluru":
           System.out.println("Phone no is 758938475");
           break;
       case "Chennai":
           System.out.println("Phone no is 987464783");
           break;
        case "Mysore":
            System.out.println("Phone no is 8473782757");
            break;
        case "Hyderabad":
            System.out.println("Phone no is 8655426545");
            break;
            default:
        System.out.println("Phone no is 86554244355");
}

    System.out.println("enter the age of patient");
int age=sc.nextInt();
if(age>=65)
{
    System.out.println("U can use this medicine");
}
else
{ 
System.out.println("u can't use this medicine"); } 
System.out.println("Enter the gender of patients\nChoice Male,Female"); 
String gender=sc.nextLine(); switch(gender)
{ 
  case "Male": System.out.println("Gender is Male"); break; case "Female": System.out.println("Gender is Female"); break; default: System.out.println("Transgender"); }

    System.out.println("Enter the name of disease\nChoice heart,brain,BP,general");
    String wdisease=sc.nextLine();
   switch(wdisease)
   {
       case "heart":
           System.out.println("U refer Aspirin medicine");
           break;
       case "brain":
           System.out.println("U  refer 1mg multivitaamin supreme medicine");
           break;
        case "BP":
            System.out.println("U refer Avapro medicine");
            break;
        case "general":
        System.out.println("u refer paracetimol medicine for fever");
            break;
            default:
        System.out.println("No medicine are avail");
}   
} }
