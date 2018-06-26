# multitech
Notes about multitech

## Adding a new device and ABP Authentication:
1. SSH into multiconnect
2. Use de following commands (replacing with the respective values):
```bash
# Add a new device
lora-query -x device add '{"deveui":"d2-80-00-fa-00-ce-e1-9c","class":"A"}'

# Add a new session
lora-query -x session add '{"deveui":"d2-80-00-fa-00-ce-e1-9c","dev_addr":"260112da","appeui":"00-88-88-88-00-00-e1-9c","joineui":"a2-d2-ce-82-94-fa-8b-54","net_id":"000400","app_senc_key":"a2d2ce8294fa8b54eb400220f52a14ce","fnwk_sint_key":"d11d1fa161f173C3144a8be1816ac181"}'
```
