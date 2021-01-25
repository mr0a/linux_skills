# linux_skills

### Delete a range of history in bash
`for line in $(seq 1800 1815) ; do history -d 1800; done`

### Speed test in terminal
`curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python3 -`

### Find computers in your network using nmap
`nmap -sP -PI -PT 192.168.0.1/24`
