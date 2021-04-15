
# How to block FLoC on your website

The easiest way I found is to edit your .htaccess file and add this line:
````
Header set Permission-Policy: interest-cohort=()
````

<br>

## Sources
* https://www.eff.org/deeplinks/2021/03/googles-floc-terrible-idea
* https://amifloced.org/
* https://developer.chrome.com/blog/floc/#how-can-websites-opt-out-of-the-floc-computation