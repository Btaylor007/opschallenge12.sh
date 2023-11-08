# opschallenge12.sh
opschallenge12.sh

$path = "C:\users\bre\Desktop\networkreport.txt.txt"
function get-ip{select-string -Path $path -Pattern "ipv4"}
get-ip
