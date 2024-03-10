# ScriptOpenWrt

1. RemoteWan Enable
```
config rule
	option enabled '1'
	option target 'ACCEPT'
	option src 'wan'
	option proto 'tcp'
	option dest_port '80'
	option name 'AllowWANWeb'
```
