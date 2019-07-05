<<<<<<< HEAD
--- Download project and contributing
   Paso 1. Clone or download the project
   		Paso 1.1 Click en Clone or donwload @IMAGE
   		Paso 2.2 Copy Https URL
   Paso 2. Install Git 
   		1. Use this url for get the guide https://www.atlassian.com/git/tutorials/install-git 
   Paso 3. Open Folder Of you preference to save project 
   Paso 4. Right Click on empty space of folder 
   Step 5. Click to "Git Bash Here"
   Step 6. When is Opened windows of Git. Write the sentence: "git clone https://github.com/EmySaulIntec/MetricConvertion.git"  
   Step 7. Open Folder MetricConvertion > Project > UniversalTranslator 
   Step 8. Double click in "UniversalTranslator.sln" 
   
 
 How Use the principal project is "UniversalTranslator"
   
   UniversalTranslator.Converter: this class is charge of convert metric units
   	Fields , properties and methods
   		> allowedConvertion: Is a dictionary when you add the convertions and the distance have the main convertion (M => Meter). 
   			The reason for that is used logic was: 
   		 	if (allowedConvertion[origin] >= allowedConvertion[destiny])
                return value * Math.Pow(10, distance);
            else
                return value / Math.Pow(10, distance);
       	> GetConvertion: Is a Function  in charge of the convertion. This alghoritm was created based in this url https://www.youtube.com/watch?v=ZzqP8K2NGKk&t=98s
  
  
  UniversalTranslator.Entry: This class is where its save the metrics imported of file intruduced by user.
  	Fields , properties and methods
  		> Value : Value to convert
  		> Origin : Metric from convert 
  		> Destiny : Metric to convert	
  		
  
  UniversalTranslator.FileController: This class is charge of load file and convert to list of entriy class.
  	Fields , properties and methods
  	> LoadFilePath: Search file and load returned all lines of file.
  	> ValidateLine: This verify all lines is valid with allowed format.
  	> IsNumeric: Verify this the first character in each line is numeric
  	> WriteResult: Recive the result and write in new file before convert the metrics units. When finished open the folder where found the result.
  	> LoadFileAndConvert: Execute the method "LoadFile" and "WriteResultAndGetConvertion" 	
  	
>Runtime:
>	1. Visual Studio con Target Framework [.Net Framework 4.8]   https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral
>	2. Microsoft Visual Studio Installer Projects https://marketplace.visualstudio.com/items?itemName=VisualStudioClient.MicrosoftVisualStudio2017InstallerProjects 
=======
--- Download project and contributing
   Paso 1. Clone or download the project
   		Paso 1.1 Click en Clone or donwload @IMAGE
   		Paso 2.2 Copy Https URL
   Paso 2. Install Git 
   		1. Use this url for get the guide https://www.atlassian.com/git/tutorials/install-git 
   Paso 3. Open Folder Of you preference to save project 
   Paso 4. Right Click on empty space of folder 
   Step 5. Click to "Git Bash Here"
   Step 6. When is Opened windows of Git. Write the sentence: "git clone https://github.com/EmySaulIntec/MetricConvertion.git"  
   Step 7. Open Folder MetricConvertion > Project > UniversalTranslator 
   Step 8. Double click in "UniversalTranslator.sln" 
   
 
 How Use the principal project is "UniversalTranslator"
   
   UniversalTranslator.Converter: this class is charge of convert metric units
   	Fields , properties and methods
   		> allowedConvertion: Is a dictionary when you add the convertions and the distance have the main convertion (M => Meter). 
   			The reason for that is used logic was: 
   		 	if (allowedConvertion[origin] >= allowedConvertion[destiny])
                return value * Math.Pow(10, distance);
            else
                return value / Math.Pow(10, distance);
       	> GetConvertion: Is a Function  in charge of the convertion. This alghoritm was created based in this url https://www.youtube.com/watch?v=ZzqP8K2NGKk&t=98s
  
  
  UniversalTranslator.Entry: This class is where its save the metrics imported of file intruduced by user.
  	Fields , properties and methods
  		> Value : Value to convert
  		> Origin : Metric from convert 
  		> Destiny : Metric to convert	
  		
  
  UniversalTranslator.FileController: This class is charge of load file and convert to list of entriy class.
  	Fields , properties and methods
  	> LoadFilePath: Search file and load returned all lines of file.
  	> ValidateLine: This verify all lines is valid with allowed format.
  	> IsNumeric: Verify this the first character in each line is numeric
  	> WriteResult: Recive the result and write in new file before convert the metrics units. When finished open the folder where found the result.
  	> LoadFileAndConvert: Execute the method "LoadFile" and "WriteResultAndGetConvertion" 	
  	
>Runtime:
>	1. Visual Studio con Target Framework [.Net Framework 4.8]   https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral
>	2. Microsoft Visual Studio Installer Projects https://marketplace.visualstudio.com/items?itemName=VisualStudioClient.MicrosoftVisualStudio2017InstallerProjects 
>>>>>>> 8336848ede16056c10093e2e1f04ae2d24080d63
>			