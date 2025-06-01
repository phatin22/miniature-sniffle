Credit to **Raj-jyot Deol / u/Switch_modder** for writing the install wireOS recovery script

```
mount -o rw,remount,exec /data {/br}
curl -o /data/install-wireOS-recovery-dev.sh http://modder.my.to:81/wireos-DEV-recOS/install-wireOS-recovery-dev.sh {/br}
chmod +rwx /data/install-wireOS-recovery-dev.sh {/br}
sh /data/install-wireOS-recovery-dev.sh {/br}
```
