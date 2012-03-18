OpenERP(OpenObject) snippets
============================

HOW TO INSTALL:
--------------

1. Download [snipMate][1] plugin for VIM and install it
2. Clone this project inside of ~/.vim/snippets/
   and rename it "python" so that you end up with something
   like: ~/.vim/snippets/python
3. Remember to add ":filetype plugin on" to your ~/.vimrc file

That's all, now you have all these snippets:
 * _openerp_py.snippet	
 *  class.snippet		
 *  date.snippet		
 *  float.snippet
 *  base.snippet		
 *  class_inh.snippet	
 *  datetime.snippet	
 *  license_openerp.snippet
 *  char.snippet		
 *  class_osv.snippet	
 *  enc.snippet		
 *  m2o.snippet

HOW TO USE:
-----------
For example, open a new .py file and write
class_osv Press-TAB

You will get a new osv class ready to be filled, press TAB again to jump 
to the next field that needs to be filled. 

[1]: http://vim.sourceforge.net/scripts/script.php?script_id=2540
