# emacs
<pre>
;; ~/.emacs.d/init.el
;; load emacs 24's package system. Add MELPA repository.
(when (>= emacs-major-version 24)
  (require 'package)
  (add-to-list
   'package-archives
   ;; '("melpa" . "http://stable.melpa.org/packages/") ; many packages won't show if using stable
   '("melpa" . "http://melpa.milkbox.net/packages/")
   t))
  
   
<hr />

http://ergoemacs.org/emacs/emacs_package_system.html

<hr />
Matching parenthesis
https://www.gnu.org/software/emacs/manual/html_node/efaq/Matching-parentheses.html

Change color theme
Changing color themes is accomplished by creating a custom theme and saving it.
https://www.gnu.org/software/emacs/manual/html_node/emacs/Custom-Themes.html
Alt-x
them 
customize-themes 


</pre>

