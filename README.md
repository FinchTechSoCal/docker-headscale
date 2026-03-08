# docker-headscale
Headscale with UI

**Clone git to system**
```bash
rm -fr ~/appdata/stacks/headscale
mkdir -p ~/appdata/headscale/
git clone https://github.com/FinchTechSoCal/docker-headscale.git ~/appdata/stacks/headscale
sed -i 's;/path/to/appdata/;'$HOME'/appdata/;g' ~/appdata/stacks/headscale/.env
```