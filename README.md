# hidmacros-macros
Personal macros for hidmacros (https://github.com/me2d13/hidmacros)

## How to use
### Install
1. Download _HID macros_: 
http://www.hidmacros.eu/download.php or https://github.com/me2d13/hidmacros
2. Extract to your program's folder (e.g. C:\Program Files (x86)\hidmacro)
3. Right click the _HIDMacros.exe_, choose _Run as administrator_, _yes_.

### Create a Macro
1. In the _HID macros_ window, choose the _Macros_ Tab, _New_.
2. In _Edit Macro_ section:  
  a. Name: Provide a name to identify your macro (e.g. _Script-Activate_Window-Proxmox_Dashboard_Planaclanvia_External_Tunnel_).   
  b. Trigger : Hit _scan_ to detect the key you want to associate the macro. A small window will open, press the keyboard button to bind. The text field in the right will show the device associated and in the next text field the key id.   
   c. In _Action_ section, choose the _Scripted_ Tab, paste the code you want.     
   d. Press _compile_.  
   e. Press _save configuration_.   
   
 >Note: You can find macro sample codes in the _Macros_ folder of this repository.  
    
 >Note: You can make an alias for your keyboards in the _Devices_ tab using the button _Rename_.  
    
 ### Execute a Macro
 1. Just press the associated button after configure the macro as above.   
 
 >Note: HID macros must be running before you press the associated key. 
   
 ## Known Issues   
 ### 1 - All numpad keys as 144()   
 __Description:__   
 When you scan diffent numpad keys, you can momentarily see the right key id if you hold it but when you release it ends with the 144() value.  
 __Workaround:__  
~Disable the _num lock_ (lights off, represent the arrows and not the numbers).~   
Enable the _num lock_ (lights on, represents the numbers and not the arrows).  

 ### 2 - Must be out of a text input to trigger the macro  
 __Description:__   
 You CANNOT have your cursor in an active input text field otherwise your key will act in the stock behavior (e.g Number 0) instead of trigger the macro.
