# Ideas

### Each project of projectdiscovery was used for integration and deployed to Github for Action for automated vulnerability scanning
### The module used is:nuclei,nuclei-templates,subfinder,httpx

### Welcome to follow me
## https://github.com/momika233
## https://twitter.com/momika233

# Remarks

### First use . Editing Automated_Incloud_Scan.yml

### Configure your keys

## Demo

```
          mkdir /home/runner/.config/subfinder
          echo "#" > /home/runner/.config/subfinder/provider-config.yaml
          echo "binaryedge: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
          echo "bufferover: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
          echo "censys: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
          echo "github: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
          echo "shodan: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
          echo "virustotal: [xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx]">>/home/runner/.config/subfinder/provider-config.yaml
```
```
          git config --local user.email "xxxx"
          git config --global user.name "xxxx"
          git commit -m "Nuclei Report" -a --allow-empty
```

# The other part

## Extensible nature of the project

### Upload your nucleus-templates in the root of your project
### Then change your configuration in Automated_Incloud_Scan.yml

```
nuclei nuclei -rl 300 -bs 35 -c 30  -mhe 10 -ni -t nuclei-templates/ -t youtemplates/ -t ...
```
### Can be modified to

### The virtual address of the project
```
/home/runner/
```
```
cd  /home/runner/ && git clone https://github.com/projectdiscovery/nuclei-templates.git
cd  /home/runner/nuclei-templates  && git clone https://github.com/youtemplates
...
...
```
# Getting started
## Until the Actions begin,Then enjoy your coffee

## I'd like some coffee, too

# Code of appreciation
(I love coffee and am very addicted to coffee:v)
<br><a href="https://www.buymeacoffee.com/momika233"><img src="https://cdn.buymeacoffee.com/buttons/default-black.png" alt="Buy Me A Coffee" height="50px"></a>

