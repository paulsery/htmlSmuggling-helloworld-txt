HTML Smuggling example 

Modified PoC by Sofiane Hamlaoui with my inert payload
  https://github.com/SofianeHamlaoui/Pentest-Notes/blob/master/offensive-security/defense-evasion/file-smuggling-with-html-and-javascript.md

Compile payload:
  gcc -o helloworld helloworld.c

Encode executable as base64
  base64 helloworld > helloworld.b64

Finally, browsing to https://paulsery.github.io/htmlSmuggling-helloworld-txt/ downloads the payload
