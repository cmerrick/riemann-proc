# Riemann Proc

Reports on the number of running processes matching a regular expression

Based on (riemann-resmon)[https://github.com/riemann/riemann-resmon/] and
(riemann-tools)[https://github.com/aphyr/riemann-tools/]

Uses 

```
ps axo args | grep <process_regexp> | grep -v grep | grep -v riemann-proc | wc -l
```

to get the running process count

# Getting started

```
gem install riemann-proc
riemann-proc --help
```
