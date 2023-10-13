# Misc commands from installing IDM server

Retrospectively enable to the makehomedir feature on servers that didn't get the mkhomedir flag during client install:
```
dnf install authselect-compat
authconfig --enablemkhomedir --update
```
