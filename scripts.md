<!-- TITLE: Scripts -->

# Scripts

```sh
for i in $(grep -rl "Yrsimerah"); do vim -c "%s/Yrsimerah/\[Yrsimerah\]\(karaktarer\#yrsimerah\suun\)/gc" -c "wq" "$i"; done
```