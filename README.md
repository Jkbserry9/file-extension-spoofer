# extension-spoofer

A simple Python 3.8.0 script to spoof the extension of a Windows executable file.

# Usage

```

C:\Users\Sploups21> py extension-spoofer.py

Enter the complete path to the executable to spoof (in the form of C:/titi/toto/file.exe or C:\titi\toto\file.exe):
> C:\Users\Sploups21\Desktop\file.exe

Enter the extension to spoof : pdf

[V] Extension spoofed with success.

```
  
## Tip

It is recommended to choose a filename finishing by the same letters of your extension since the extension is not removed but simply reversed, thanks to the Unicode code "U+202E".

So since the extension of your original Windows executable is ".exe", it's more coherent to rename it by a word finishing by "exe", like "reflexe" for example, and to remove the last three characters of it so you will get <strong>"refl.exe"</strong>.

Thanks to this method, <strong>an executable named refl.exe</strong>, which spoof extension is pdf, will give you <strong><em>reflexe.pdf</em></strong> 

But <strong>an executable named titi.exe</strong>, which spoof extension is pdf, will give you <strong><em>titiexe.pdf</em></strong> (which is less discrete) 

Once your file is spoofed, you can change manually the icon of your file corresponding to the extension you choosed to spoof. 

## Demo

https://user-images.githubusercontent.com/66923124/152334875-614f008e-5f04-485c-8219-4ab6902293c1.mp4



zssdvj