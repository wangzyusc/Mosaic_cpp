# Mosaic_cpp
This project focuses on build a solution for getting an optimal image scratch replacing result. It segments the original image to numerous small chunks, and then replace each chunk with most similar image in a given library, thus to get a "Mosaic" effect.

Example:
Source image
![alt text](http://static3.businessinsider.com/image/58586374ca7f0cfd788b4c6c/apple-is-losing-its-focus-again--and-this-time-theres-no-steve-jobs-coming-to-the-rescue.jpg)
Result image

![alt text](https://github.com/wangzyusc/Mosaic_cpp/blob/master/jobs_mosaic_initial_result.png)

Personal note:
Use the following command to get the number of lines of code:
git log --author="wangzyusc" --pretty=tformat: --numstat | awk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "added lines: %s, removed lines: %s, total lines: %s\n", add, subs, loc }' -
