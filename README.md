# upfirdn2d
When you are running stylegan2 or similar python projects and upfirdn2d does not compile, you can use this file instead of the original c++ file.
Just like:

from upfirdn2d import upfirdn2d

upfirdn2d(input, kernel, up=1, down=1, pad=(0, 0))
