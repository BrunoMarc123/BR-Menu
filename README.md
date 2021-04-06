# BR-Menu
FiveM Menu with advanced options

How To use:
1. How to set the title text (option):
exports['br-menu']:SetTitle("Your Title Here")

2. How to create normal button (not inside a category)
exports['br-menu']:AddButton("Button Text Title" , "Description" ,'trigger(example:'police:cuff')' ,'parametrs (if you dont need any parameter leave this part blank)')
   
3. How to create button ( inside a category )
exports['br-menu']:AddButton("Button Text Title" , "Description" ,'trigger(example:'police:cuff')' ,'parametrs (if you dont need any parameter leave this part blank) ,"menuname"')
   
 
4. How to create sub menu (category)
