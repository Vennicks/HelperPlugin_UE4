# PluginHelper contain:

FileIO:
    - Description:
        To handle reading and writing in a file (scores for examples)
      
    - FString LoadFileToString(const FString Filename);
        Read the file and store the result in an FString
      
    - void SaveStringToFile(const FString TextToSave, const FString Filename);
        Save the string in the file
      
    - TArray<FString> LoadFileToStringArray(const FString Filename);
        Read the file and store the result in an TArray<FString>
  
    - void SaveStringArrayToFile(const TArray<FString> TextToSave, const FString Filename);
        Save the array of strings in the file
