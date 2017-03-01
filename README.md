# language-gcov package

Provides basic syntax highlighting for gcov source files in atom. Any \*.gcov file will have the coverage portion highlighted but actual syntax highlighting is currently supported for only the following languages:
* C
* Fortran (free and fixed form)

To support Fortran highlighting the package [language-fortran](https://atom.io/packages/language-fortran) is used.

The default style looks best in a dark theme but the colors are set in [gcov-styles.less](./styles/gcov-style.less) and can easily be adjusted.


Below is a fixed form Fortran gcov file using Base16 Tomorrow Dark theme:
![image](https://cloud.githubusercontent.com/assets/16710141/23439458/b06d8604-fde4-11e6-9cc2-7c83cc7f4f15.png)
