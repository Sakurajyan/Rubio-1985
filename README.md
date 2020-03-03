# Rubio-1985-notes
markdown in zhihu:
replace:
\$\$\n*(.*?)\n*\$\$
to
\n\n<img src="https://www.zhihu.com/equation?tex=\1\\\\" alt="\1\\\\" class="ee_img tr_noresize" eeimg="1">\n\n
replace:
\$\n*(.*?)\n*\$
to
<img src="https://www.zhihu.com/equation?tex=\1" alt="\1" class="ee_img tr_noresize" eeimg="1">