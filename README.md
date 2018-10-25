# Fifth-Pageflex-Extension
This extension checks if we are on the shipping page, prints to the logs what we have passed to calculate tax rates, sets the tax rate based on several zipcodes to different values. The next step should be attaching to alavara from here

This extension has a lot of the methods removed and focuses on using the users shipping info to calculate a new tax rate based on the users zipcode


Methods:
1. DisplayName()
2. UniqueName()
3. private ISINI GetSf () (reduces code throughout project)
4. IsModuleType (string x) (determines if at shipping step)
5. CalculateTax2 () 
