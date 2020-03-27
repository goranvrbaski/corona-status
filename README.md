# Corona Status CLI Tool

This tool will scrape https://corona-stats.online/ and search the site for a phrase that you pass as an argument.

### Legend

😷 - indicates the number of known infected people  
💀 - indicates the number of known deaths

### How to use

- clone repository or `wget https://raw.githubusercontent.com/goranvrbaski/corona-status/master/corona`
- make `corona` file executable (chmod +x corona)
- run corona

```bash
./corona USA

Corona status for USA
😷 85,377
💀 1,295
```