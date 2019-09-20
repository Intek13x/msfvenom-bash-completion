# msfvenom-bc-generator
Metasploit msfvenom Bash Completions Generator

1. Copy the file into metasploit installation path
2. Run: ruby msfvenom-bc-generator.rb
3. File /etc/bash_completion.d/msfvenom will be created 

## Tutorial for N00bz 
- Download
```
git clone https://github.com/nopernik/msfvenom-bc-generator.git 
cd msfvenom-bc-generator/ 
```
- Now locate metasploit installation path 
``` 
locate msfvenom 
``` 
- Take note of the path for file 
```
/.../metasploit-framework/msfvenom
```
- Copy and run 
```
sudo cp msfvenom_bc_generator.rb /usr/share/metasploit-framework/ 
cd /usr/share/metasploit-framework/ 
sudo ruby msfvenom_bc_generator.rb
```
- Enjoy
```
Open a new terminal and type msfvenom TABTAB :)
``` 

## Credits : 
- [Alexander Korznikov](https://github.com/nopernik)

