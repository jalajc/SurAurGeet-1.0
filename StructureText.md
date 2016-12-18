Algorithm

1. Common Replace with space 
  
  1.1 Regex: PCRE (PHP)
  
  `(?|(  +)|(\t)|(\f)|(^(\r\n))(\n|\r)(\n|\r)+|(\r\n(\r\n)+)|(...)|([xX]?(\(\s+\d\s+\))))`

  `$str=str_replace("<hr />","<hr/>",str_replace("\n\n", "\n", str_replace("\r\n", "\n", str_replace("&nbsp;","",trim($str)))));`
2. Remove from Text


3. Replace with Newline


4. Conditionally remove/replace


Helpful sites: https://www.debuggex.com/, https://regex101.com/
