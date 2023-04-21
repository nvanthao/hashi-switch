# Hashi-Switch
This is an utility script that helps to download and switch to different HashiCorp product binary easily for development and testing purpose.

## Usage

Execute the script and provide the `$PRODUCT` and `$VERSION`

```
sudo ./get consul 1.15.2+ent
```

Alternatively, for automation purpose

```
curl -sSL https://raw.githubusercontent.com/nvanthao/hashi-switch/main/get -o /usr/local/bin/hs
chmod +x /usr/local/bin/hs 
```

For example

```

hs consul 1.15.2
hs consul-k8s 1.1.1
hs nomad 1.5.3+ent
```