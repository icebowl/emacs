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
  
   </pre>
<hr />
<pre>
http://ergoemacs.org/emacs/emacs_package_system.html

</pre>
